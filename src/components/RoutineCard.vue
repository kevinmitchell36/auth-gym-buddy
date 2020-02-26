<template>
  <div class="routinecard">
    <div class="card">
      <div class="card-content">
        <h2 class="heading">{{ routine.name }}</h2>
        <small class="routine-date">{{ routine.category }}</small>
        <span>{{ routine.description }}</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: [
    'routine'
  ]
}
</script>

<style scoped>

.card {
  border: 1px solid black;
}

ul.details {
  align-items: left;
}

ul.details li {
  list-style: none; 
}
  
</style>