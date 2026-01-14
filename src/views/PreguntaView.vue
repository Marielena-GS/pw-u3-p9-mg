<template>
  <div>
    <PreguntaComponent />
  </div>
</template>

<script>

import PreguntaComponent from '@/components/PreguntaComponent.vue';
export default {
  name: 'PreguntaView',
  components: {
    PreguntaComponent
  }
}
</script>

<style scope>

.view-container{
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 50px;
  align-items: center;
  text-align: center;
}
h2{
  font-size: 50px;
}

</style>