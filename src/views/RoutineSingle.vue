<template>
  <div id="routine-single">
    <h1 class="title">
      {{routine.name}}
    </h1>
    <h2 class="category">
      {{routine.category}}
    </h2>
    <h3 class="description">
      {{routine.description}}
    </h3>
  </div>
</template>

<script>
export default {
  name: 'RoutineSingle',
    data () {
    return {
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
      ],
    routine: {},
    }  
  },
  created() {
    const ID = Number(this.$route.params.id);
    let routine = this.routines.find(routine => routine.id === ID);
    this.routine = routine;
  }
}

</script>

<style>

</style>