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
              link:'shop',
            }           
          ]
        };
    },
    methods: {

    }
}
</script>

<template>
  
    <header>
      <div class="bg_container">
        <div class="container">
          <div class="nav_bar">
            <div class="logo_container">
              <img src="../img/dc-logo.png" alt="logodc">
            </div>
            <div>
              <nav>
                <ul>
                  <li v-for="(link, index) in navbar">
                    <a href=""> {{ navbar[index].link }}</a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
      </div>
    </header>
</template>

<style lang="scss" scoped>

</style>
