<template>
  <div id="app">
       <h1>Question Three</h1>
   first number<input type="number" v-model="first_number"/>
   second number<input type="number" v-model="second_number" />

   <button @click="sum()">Sum</button>

   <p>total: {{total}}</p>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
  },
  data() {
    return {
      first_number:0,
      second_number:0,
      total:0
    }
  },
  methods:{
      sum(){
          const firstNumber=parseInt(this.second_number);
          const secondNumber=parseInt(this.second_number);
          this.total=firstNumber+secondNumber;
      }
  }
}
</script>

<style>
</style>
