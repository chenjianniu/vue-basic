<template>
  <p>{{ say }}</p>
  <MyDiv msg="hello"></MyDiv>
</template>

<script>
import MyDiv from './components/MyDiv.vue'
export default {
  data() {
    return {
      say: 'hi'
    }
  },
  components: {
    MyDiv
  }
}
</script>
