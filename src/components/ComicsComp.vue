<template>
  <div>
      <img :src="single.thumb" :alt="single.type">
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
        flex-basis: calc(100% / 7);
        margin: 10px;
    }

</style>