<template>
  <div>
    <h1>{{ title }} - 19 is the next one!</h1>
    <p>{{ greeting() }}</p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'Your first Vue file, wooo!',
    }
  },
  methods: {
    greeting: function() {
      return 'heeey cowboy!';
    }
  }
}
</script>

<style>
body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

</style>
