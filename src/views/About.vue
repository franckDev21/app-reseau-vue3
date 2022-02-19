<template>
  <div class="about">
    <h1>This is an about page</h1>
    <button>cliquer ici</button>
  </div>
</template>

<style lang="scss" scoped>
  .about{
    button{
      padding: 1rem 2rem;
      background-color: rebeccapurple;
      border-radius: .5rem;
      color: #fff;
      border: none;
      outline: none;
      font-size: 2rem;
      cursor: pointer;
      &:active{
        transform: scale(.93);
      }
    }
  }
</style>
