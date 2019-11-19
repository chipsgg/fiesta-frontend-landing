<template>
  <div class="home">
    <img class="logo" src="@/assets/logo.png">
    <div class="description">
      Our Mexicans are currently cooking up a fiesta in the background,
      to bring back the good ol’ famous Fiesta, that we all knew and loved
      but with a twist…We’ve redecorated. We’re excited to show you all! 
    </div>
    <a href="https://twitter.com/thecsgofiesta" target="_blank"><div class="button">Keep up to date, via our Twitter</div></a>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    // HelloWorld
  }
}
</script>


<style scoped>
  .home {
    position: relative;
    z-index: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }

  .logo {
    max-width: 327px;
  }

  .description {
    max-width: 422px;
    color: #E4E6FA;
    margin: 30px 50px;
    text-align: center;
    opacity: 0.4;
    line-height: 1.5em;

  }

  .button {
    width: 272px;
    height: 70px;
    background: #272655;
    border-radius: 5px;
    color: #E4E6FA;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    transition: 0.3s all ease-in-out;
  }

  .button:hover {
    font-size: 1.1em;
    font-weight: bold;
    color: #272655;
    background: #E4E6FA;
  }
</style>
