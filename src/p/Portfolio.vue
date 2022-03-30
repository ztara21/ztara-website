<style>
  @import url('../style/Pages.css');
</style>

<template>
    <div class="content-header">
        <h1 class="big-title">Portfolio</h1>
    </div>
</template>

<script>
  export default {
    data: () => {
      return {
        portfolioItems: [
          {
            title: '',
            thumb: '',
            tags: [],
            to: ''
          }
        ],
      }
    }      
  }
</script>