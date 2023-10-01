<script >
import TodoList from "./components/TodoList.vue";
import Counter from "@/components/Counter.vue";

export default {
  components:{
    TodoList,
    Counter
  },
  data(){
    return{
      tasks:['something1','something2','something3']
    }
  }
}
</script>

<template>
  <div>
    <TodoList :todos = 'tasks'/>
    <Counter/>
  </div>
</template>

<style>

</style>
