<!-- src/App.vue -->
<template>
  <div id="app" :style="{ backgroundColor: '#fff' }">
    <ActivityList />
  </div>

</template>

<script>
import ActivityList from './components/ActivityList.vue';

export default {
  components: {
    ActivityList
  }
};
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  margin: 0 auto;
  padding: 20px;
  max-width: 600px;
}
</style>
