<template>
  <div id="app">
    <input type="text" v-model="text" />
    <p>{{text}}</p>
  </div>
</template>

<script>
export default{
  data(){
    return{
      text:""
    };
  }
};
</script>
