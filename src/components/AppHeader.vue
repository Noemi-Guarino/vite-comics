<script>
export default {
    data() {
        return {
          navbar: [
            {
              link:'charachters',
            },
            {
              link:'comics',
            },
            {
              link:'movies',
            },
            {
              link:'tv',
            },
            {
              link:'games',
            },
            {
              link:'collectibles',
            },
            {
              link:'videos',
            },
            {
              link:'fans',
            },
            {
              link:'news',
            },
            {
              link:'WaveShaperNode',
            }           
          ]
        };
    },
    methods: {

    }
}
</script>

<template>
  <div>
    <header>
      <div class="container">
        <div class="logo_container">
          <img src="../img/dc-logo.png" alt="logodc">
        </div>
        <nav>
          <ul>
            <li v-for="(link, index) in navbar">
              <a href=""> {{ navbar[index].link }}</a>
            </li>
          </ul>
        </nav>
      </div>
    </header>
  </div>
</template>

<style lang="scss" scoped>

</style>
