<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <b><a href="https://blog.sodifrance.fr/les-linters-javascript/#:~:text=Un%20linter%20est%20un%20outil,style%20ou%20des%20bonnes%20pratiques.">Linter</a> :</b> 
        c'est un outil d'analyse statique de code source. Il sert à détecter les erreurs, 
        les problèmes de syntaxe et le non-respect d'un style ou des bonnes pratiques.
      </li>
      <li>
        <b><a href="https://fr.wikipedia.org/wiki/Test_unitaire#:~:text=En%20programmation%20informatique%2C%20le%20test,%C2%BB%20ou%20%C2%AB%20module%20%C2%BB).">Les tests unitaires</a> :</b> 
        En programmation informatique, le test unitaire (ou « T.U. », ou « U.T. » en anglais) ou test de 
        composants est une procédure permettant de vérifier le bon fonctionnement d'une partie précise d'un 
        logiciel ou d'une portion d'un programme (appelée « unité » ou « module »). <br>
        La bibliothèque <a href="https://jestjs.io/">jestjs</a>.
      </li>
      <li>
        <b><a href="https://blog.testingdigital.com/quest-test-de-bout-bout-end-to-end-1288">Test end to end (e2e)</a> :</b> 
        Les tests de bout en bout sont une technique utilisée pour vérifier si une application (site Internet, 
        application mobile…) se comporte comme prévu du début à la fin. Le testeur doit se mettre dans la peau 
        d’un utilisateur et dérouler les tests comme s’il utilisait véritablement l’outil mis à sa disposition. 
        Cette technique permet de valider le fonctionnement du front. Mais aussi de vérifier son intégration avec le 
        back-office et autres webservices. <br>
        La bibliothèque <a href="https://www.cypress.io/">cypress</a>.
      </li>
    </ul>
    <p>
      Pour aller plus loin dans la création d'un projet vue : <a href="https://cli.vuejs.org/guide/creating-a-project.html">documentation</a>
    </p>
    <!-- <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
