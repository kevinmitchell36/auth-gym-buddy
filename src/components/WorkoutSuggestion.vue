<template>
  <div class="">
    <h1>Welcome to Gym Buddy</h1>
    <h3>What do you want to do today?</h3>
    <a class="hairy" href="#">Weights</a>
    <a class="hairy" href="#">Weights</a>
    <a class="hairy" href="#">Weights</a>
    <a class="hairy" href="#">Weights</a>
  </div>
</template>
<script>
export default {
  name: 'WorkoutSuggestion',
  components: {
  }
}
</script>

<style>

a.hairy {
  height: 160px;
  width: 500px;

  display: block;
  background-image: url('https://images.unsplash.com/photo-1529516624803-d5e9c2fb067e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1650&q=80');
  background-position: center;

}


</style>