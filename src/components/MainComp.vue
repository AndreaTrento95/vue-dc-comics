<template>
  <main>
      <div class="container">
          <h3>Content goes here</h3>
      </div>
      
  </main>
</template>

<script>

import Comics from '@/assets/data/dc-comics.js'

export default {
    name: 'MainComp'
}
</script>


<style lang="scss" scoped>
    main {
        height: 70px;
        background-color: black;
        line-height: 70px;
        h3{
            color: white;
        }
    }
</style>