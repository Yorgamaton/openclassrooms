<template>
      <div class="menu-item">
        <img
          class="menu-item__image"
          :src="image.source"
          :alt="image.alt"
        />
        <div>
          <h3>{{ name }}</h3>
          <p v-if="inStock">En stock</p>
          <p v-else>En rupture de stock</p>
          <div>
            <label for="add-item-quantity"
              >Quantité : {{ quantity }}</label
            >
            <input
              v-model.number="quantity"
              id="add-item-quantity"
              type="number"
            />
            <button @click="addToShoppingCart(quantity)">
              Ajouter au panier d'achat
            </button>
          </div>
        </div>
      </div>
</template>

<script>
export default {
  name: 'MenuItem',
  props: ["addToShoppingCart", "image", "inStock", "name", "quantity"]
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
