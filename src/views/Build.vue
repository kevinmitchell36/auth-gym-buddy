<template>
  <div class="routinelist">
    <h2 class="2-heading">
      View your routines
    </h2>
    <div class="items">
      <RoutineList />
    </div>
  </div>
</template>

<script>
import RoutineList from '@/components/RoutineList';
export default {
  name: 'routinelist',
  components: {
    RoutineList
  }
}
</script>

<style scoped>

</style>