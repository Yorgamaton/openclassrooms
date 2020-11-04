// ./components/HomeLink.vue
<template>
	<a :href="url">{{ text }}</a> 
</template>

<script>
export default {
	name: 'NavLink',
	props: ['url', 'text']
}
</script>

<style scoped>
	a {
		text-decoration: none;
        color: green;
        font-weight: bold;
	}
</style>