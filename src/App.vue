<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
<style>
    @font-face{
        font-family : "Roboto";
        src : url('./assets/fonts/Roboto-Regular.ttf');
        font-weight: normal;
    }
    @font-face{
        font-family : "Roboto";
        src : url('./assets/fonts/Roboto-Bold.ttf');
        font-weight: 700;
    }
    @font-face{
        font-family : "Roboto";
        src : url('./assets/fonts/Roboto-Light.ttf');
        font-weight: 300;
    }
    @font-face{
        font-family : "Roboto";
        src : url('./assets/fonts/Roboto-Black.ttf');
        font-weight: 900;
    }
    @font-face{
        font-family : "Roboto";
        src : url('./assets/fonts/Roboto-Thin.ttf');
        font-weight: 100;
    }

    #app {
        font-family: 'Roboto';
        font-weight: 300;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        color: #414141;
    }
</style>
