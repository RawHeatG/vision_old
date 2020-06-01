<template>
    <div id="app">
        <div id="heading">
            <h1> Covid Hygienenet</h1>
        </div>
        <div id="description">
            The virus is spread at an alarming rate without the knowledge of the infected person. Covid-19 spreads when infected person coughs, sneezes or talks and droplets from their mouth or nose are launched into air and land in the “T Zone(Eyes, Nose, Mouth)” of people nearby. Therefore, wearing Mask is necessary step to be taken for safety of humanity as masks are the safety shield from the transfer of droplets. The usage of masks is the best and most effective method to stop the transfer of virus directly safeguarding self and others.
        </div>
        <div id="wrapper">
            <h1> Hygienenet</h1>
            <Capture />
        </div>
    </div>
</template>
<script>
import Capture from './components/Capture.vue';


export default {
    name: 'app',
    components: {
        Capture,

    }
}
</script>
<style lang="css">
</style>
<style>
@import url('https://fonts.googleapis.com/css?family=Raleway');

body,
html {
    padding: 10px;
    margin: 0;
    background: #56CCF2;
    /* fallback for old browsers */
    background: -webkit-linear-gradient(to bottom, #2F80ED, #56CCF2);
    /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to bottom, #2F80ED, #56CCF2);
    /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    overflow-x: hidden;
}

h1 {
    text-align: center;
}

#app {
    display: flex;
    flex-direction: column;
    font-family: 'Raleway';
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #ffffff;
}

#wrapper {
    margin-top: 30px;
    flex-direction: column;
    box-shadow: 0 8px 10px 1px rgba(0, 0, 0, .14), 0 3px 14px 2px rgba(0, 0, 0, .12), 0 5px 5px -3px rgba(0, 0, 0, .3);
    width: 95%;
    display: flex;
    padding-bottom: 30px;
}
</style>