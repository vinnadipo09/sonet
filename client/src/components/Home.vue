<template>
  <div class="hello">
      <div class="home-parallax">
          <v-parallax src="/static/page3.png">
            <div class="home-text">
                <h1>ViadTechnologies</h1>
                <h3>The Future Predetermined</h3>
            </div>
          </v-parallax>
      </div>
      <h1>Home Page</h1>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
.home-parallax{
    margin-top: 60px;
}
.home-text{
    margin-top: 400px;
    /* margin-right: 10px; */
}
</style>
