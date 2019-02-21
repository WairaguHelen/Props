<template>
  <div>
    <app-Posts v-bind:Posts="Posts"></app-Posts>
  </div>
</template>

<script>
import Posts from './Posts';
export default {
  name: 'App',
  components: {
    'app-Posts':Posts
  },
  data () {
    return {
        Posts: [
         {title: "My journey with Vue"},
         {title: "I love Vue"},
         {title: "Vue"}
        ]
  }
}
}
</script>

<style>

</style>
