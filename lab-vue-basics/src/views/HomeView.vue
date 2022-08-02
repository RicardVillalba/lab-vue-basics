<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <NewComponent/>
    <NewComponent2/>
    <Iteration2/>
    <Iteration3/>
    <!-- <Iteration4/> -->
  </div>
</template>

<script>

import NewComponent from '@/components/NewComponent.vue'
import NewComponent2 from '@/components/NewComponent2.vue'
import Iteration2 from '@/components/Iteration2.vue'
import Iteration3 from '../components/Iteration3.vue'
import Iteration4 from '../components/Iteration4.vue'
export default {
  name: 'HomeView',
  components: {
    NewComponent,
    NewComponent2,
    Iteration2,
    Iteration3,
    Iteration4
}
}
</script>
