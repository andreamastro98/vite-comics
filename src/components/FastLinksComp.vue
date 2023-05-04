<script>

export default{
  name: "FastLinksComp",
  data(){
    return{
        icons:[
                    {
                        name: "digital comics",
                        url:"buy-comics-digital-comics.png",
                    },
                    {
                        name: "dc merchandise",
                        url:"buy-comics-merchandise.png",
                    },
                    {
                        name: "subscription",
                        url:"buy-comics-subscriptions.png",
                    },
                    {
                        name: "comic shop locator",
                        url:"buy-comics-shop-locator.png",
                    },
                    {
                        name: "dc power visa",
                        url:"buy-dc-power-visa.svg",
                    },   
                ]
    }
  }
}

</script>

<template>
    <section class="fastlinks">
        <div class="container d-flex justify-content-between align-items-center py-5">
            <div v-for="(elem, index) in icons">
                <img :src="`../../public/img/${elem.url}`" :alt="index">
                <a :href="elem.url">{{ elem.name }}</a>
            </div>
        </div>  
    </section>      
</template>

<style lang="scss" scoped>

</style>