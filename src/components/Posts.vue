<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

<template>
  <div id = "Posts">
      <ul>
          <li v-for="Post in Posts" :key="Post">
              <h1>{{Post.title}}</h1>
          </li>
      </ul>
  </div>
</template>

<script>
export default {
    props: {Posts:
     {
type:Array
    }
    },
  data () {
    return {
        
  }
}
}
</script>

