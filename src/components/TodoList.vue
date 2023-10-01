<script>
export default {
  data(){
    return {
      message:'Hello'
    }
  },
  props: [
      'todos'
  ]
}
</script>

<template>
  <div>
  {{message}}
    {{todos}}
  </div>
</template>