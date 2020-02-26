<template>
  <div class="routine-list">
   <div v-for="routine in routines" :routine="routine" :key="routine.id" class="column">
        <router-link :to="'/routine/' + routine.id">
          <RoutineCard :routine="routine" />
        </router-link>
      </div>
  </div>
</template>

<script>
import RoutineCard from '@/components/RoutineCard';
export default {
  name: 'routine-list',
  components : {
    RoutineCard
  },
  data () {
    return {
      routine: {},
      routines: [
        {
          id: 1,
          name: 'Lat Pull',
          category: 'Pull',
          description: 'Pull bar down', 
        },
        {
          id: 2,
          name: 'Dumbell Flys',
          category: 'Push',
          description: 'Dont hit your face'
        }
      ]
    }  
  }
}
</script>
<style scoped>

</style>