<template>
  <div id="app">
       <h1>Question One</h1>
   Title<input type="txt" v-model="title"/>
   First Name<input type="text" v-model="first_name"/>
   Last Name<input type="text" v-model="last_name" />

   <p>Welcome {{title}} {{first_name}} {{last_name}}</p>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
  },
  data() {
    return {
      title:'',
      first_name:'',
      last_name:''
    }
  },
  mounted(){
  },
  methods:{
    sum(){

    }
  }
}
</script>

<style>
</style>
