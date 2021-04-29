<template>
  <div id="app">
    Hello, world.
    <RestaurantScreen />
  </div>
</template>

<script>
import RestaurantScreen from '@/components/RestaurantScreen';

export default {
  name: 'App',
  components: {RestaurantScreen},
};
</script>