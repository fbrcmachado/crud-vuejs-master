<template>
  <div id="app" class="container">
    <h1> Cadastro de Cervejas e Cervejarias </h1>
    <tabs>
      <tab name="t1" title="Cervejas" active=true>
        <Cervejas></Cervejas>
      </tab>
      <tab name="t2" title="Cervejarias">
        <Cervejarias></Cervejarias>
      </tab>
    </tabs>

  </div>
</template>
<script>
  import Tabs from './components/Tabs.vue'
  import Tab from './components/Tab.vue'
  import Cervejarias from './Cervejarias.vue'
  import Cervejas from './Cervejas.vue'
  export default {
    components: {
      Tabs,Tab,
      Cervejarias, Cervejas
      }
    }
</script>