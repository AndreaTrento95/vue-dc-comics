<template>
  <div>
      <img :src="single.thumb" :alt="single.type">
      <h5>{{ single.series }}</h5>
  </div>
</template>

<script>
export default {
    name: 'ComicsComp',
    props:{
        single: Object
    }
}
</script>

<style lang="scss" scoped>


    div{
        flex-basis: calc(100% / 6 - 20px);
        margin: 0 20px 20px 0;
        img{
            width: 100%;
        }
        h5{
            color: white;
            margin-top: 5px;
            font-weight: 400;
        }
    }

</style>