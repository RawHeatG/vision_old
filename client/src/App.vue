<template>
    <div id="app">
        <div id="heading">
            <h1>HygieneNet</h1>
        </div>
        <div id="description">
           <h3><b>The</b> whole package to help you perform <u>The Impeccable Hand Wash</u> Each time, Everytime!</h3>
        </div>
        <div id="wrapper">
        	<div id="image">
                <img src="./img/HandWash.gif">
            </div>
            <h2 id="emoji"> 
           		Wanna lend us your hand <span>🤝🏻</span>for a while!
           	<br>
           		We won't bite <span>&#128540;</span></h2>
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
@import url('https://fonts.googleapis.com/css2?family=Raleway');

body,
html {
    margin: 0;
    background: #5987aa;
    /* fallback for old browsers */
    background: -webkit-linear-gradient(to bottom, #5987aa, #fddcd7);
    /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to bottom, #5987aa, #fddcd7);
    /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    overflow-x: hidden;
}

h1 {
    text-align: center;
}


#heading {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 23px;
    box-shadow: 0 8px 10px 1px rgba(0, 0, 0, .14), 0 3px 14px 2px rgba(0, 0, 0, .12), 0 5px 5px -3px rgba(0, 0, 0, .3);
}

#emoji span {
	font-size: 1.7em;
}

#app {
    display: flex;
    flex-direction: column;
    font-family: 'Raleway';
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #ffffff;
}

#description {
    margin: 20px;
    text-align: center;
    line-height: 1.8;
}
/*img {
		display: flex;
    	margin-left: auto;
  		margin-right: auto;
		width: 80%;
  		height: auto;
  		border-radius: 18px;
}*/
#image{
	display: flex;
	align-items: center;
	justify-content: center;
}
#image img {
    	border-radius: 18px;	
		width: 70%;
  		height: auto;
	}



@media only screen and (max-width: 767px) {
    #app {
        width: 100%;
    }
    #wrapper{
    	display: flex;
    	flex-direction: column;
    	align-items: center;
    }

    h2{
    	text-align: center;
    }

    #image img {
    	width: 90%;
    	border-radius: 8px;
    }

    
}
</style>