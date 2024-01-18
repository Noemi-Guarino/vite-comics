<script>
export default {
    data() {
        return {
          dccomics:[
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
          ],
          shop: [
          {
              link:'shop Dc',
            },
            {
              link:'shop dc collectibles',
            },
          ],
          dc:[
          {
              link:'Terms of use',
            },
            {
              link:'Privacy politicy(New)',
            },
            {
              link:'Ad Choices',
            },
            {
              link:'Advertising',
            },
            {
              link:'Jobs',
            },
            {
              link:'Subscriptions',
            },
            {
              link:'Talent Workshops',
            },
            {
              link:'Cpsc certificates',
            },
            {
              link:'Ratings',
            },
            {
              link:'Shop help',
            }, 
            {
              link:'Contact us',
            },         
          ],
          sites: [
          {
              link:'Dc',
            },
            {
              link:'Mad magazine',
            },
            {
              link:'Dc kids',
            },
            {
              link:'Dc universe',
            },
            {
              link:'Dc power visa',
            },
          ],
        };
    },
    methods: {

    }
}
</script>

<template>
    <footer>
      <div class="bg_footer">
            <div class="container">
                <div class="top_footer">
                  <div class="column"> 
                    <h3>DC COMICS</h3>
                    <ul>
                      <li v-for="(link, index) in dccomics">
                        <a href="">{{ dccomics[index].link }}</a>
                      </li>
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                      <li v-for="(link, index) in shop">
                        <a href="">{{ shop[index].link }}</a>
                      </li>
                    </ul>
                  </div>
                  <div class="column">
                    <h3>DC</h3>
                    <ul>
                      <li v-for="(link, index) in dc">
                        <a href="">{{ dc[index].link }}</a>
                      </li>
                    </ul>
                  </div>
                  <div class="column">
                    <h3>SITES</h3>
                    <ul>
                      <li v-for="(link, index) in sites">
                        <a href="">{{ sites[index].link }}</a>
                      </li>
                    </ul>
                  </div>
                </div>  
            </div>
        </div>

    </footer>
</template>

<style lang="scss" scoped>
</style>
