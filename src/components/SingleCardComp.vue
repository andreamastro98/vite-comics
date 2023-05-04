<script>

export default{
  name: "SingleCardComp",
  props: {
    singleCard: Object
  },
}

</script>

<template>

    <div class="card">
        <img :src="singleCard.thumb" alt="">
        <span>{{ singleCard.series }}</span>
    </div>    
           
</template>

<style lang="scss" scoped>

.card{
        width: calc(90%/6);
        background-color: #1C1C1C;
        border: 0;
        margin-bottom: 1rem;
        margin-right: 1.6%;

        img{
            width: 100%;
            margin-bottom: 1rem;
            height: 73%;
        }

        span{
            text-transform: uppercase;
            color: white;
        }
    }    

</style>