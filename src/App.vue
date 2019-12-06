<template>
  <div id="app">
    <div>
      <h2>标题</h2>
      <p>{{headerListData}}</p>
    </div>
    
  </div>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator';
import HelloWorld from './components/HelloWorld.vue';

@Component({
  components: {
    HelloWorld,
  },
})


export default class App extends Vue {}



// export default {
//   name:"App",
//     data() {
//     return {
//       IsRouterAlive: true,
//       headerListData: "hahhahaha",
//       router: false
//     };
//   },
//   methods:{

//   }
// }
</script>

<style lang="less">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
