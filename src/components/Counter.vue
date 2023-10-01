<script>
export default {
  data(){
    return{
      count:0
    }
  },
  methods:{
    Increment(){
      this.count = this.count + 1
    },
    Decrement(){
      this.count = this.count - 1
    }
  }
}
</script>

<template>
  <div>
    <button @click = 'Decrement'>decrement</button>
    {{count}}
    <button @click = 'Increment'>increment</button>
  </div>
</template>