<script>

export default{
  name: "HeaderComp",
  data(){
    return{
      menuLinks:[
        {
          name:'Characters',
          link:'',
          currennt:'',
        },
        {
          name:'Comics',
          link:'',
          currennt:'',
        },
        {
          name:'Movies',
          link:'',
          currennt:'',
        },
        {
          name:'Tv',
          link:'',
          currennt:'',
        },
        {
          name:'Games',
          link:'',
          currennt:'',
        },
        {
          name:'Collectibles',
          link:'',
          currennt:'',
        },
        {
          name:'Videos',
          link:'',
          currennt:'',
        },
        {
          name:'Fans',
          link:'',
          currennt:'',
        },
        {
          name:'News',
          link:'',
          currennt:'',
        },
        {
          name:'Shop',
          link:'',
          currennt:'',
        },
      ]
    }
  }
}

</script>



<template>
  <div>
    <header class="container">
      <nav class="d-flex justify-content-between align-items-center">
        <div>
          <img src="../../public/img/dc-logo.png" alt="" style="width: 70%;">
        </div>
        <div>
          <ul>
            <li>
              <a href="#">Characters</a>
            </li>
            <li>
              <a href="#">COMICS</a>
            </li>
            <li>
              <a href="#">MOVIES</a>
            </li>
            <li>
              <a href="#">TV</a>
            </li>
            <li>
              <a href="#">GAMES</a>
            </li>
            <li>
              <a href="#">COLLECTIBLES</a>
            </li>
            <li>
              <a href="#">VIDEOS</a>
            </li>
            <li>
              <a href="#">FANS</a>
            </li>
            <li>
              <a href="#">NEWS</a>
            </li>
            <li>
              <a href="#">SHOP</a>
            </li>
          </ul>
        </div>
      </nav>      
    </header>
  </div>  
</template>



<style lang="scss" scoped>

</style>
