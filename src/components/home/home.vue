<template>
  <div id='home'>
	<div id='container' class="container-fluid">
		<div id="header">
	        <v-header></v-header>
	    </div>
	    <div id="content">
	        <v-content></v-content>
	    </div>
	    <div id="footer">
	        <v-footer></v-footer>
	    </div>

	</div>
</div>
</template>


<script>
  import vHeader from '../header/header.vue'
  import vFooter from '../footer/footer.vue'
  import vContent from '../home/content.vue'
    export default {
      
      components:{
          vHeader, vFooter, vContent, 
      },
    }
</script>

<style>

	/* div {
	    border: 1px solid black;    
	} */
	/* div, p, h2 {
	    margin: 2px;
	    padding: 5px;
	}
	
	#container {
	    width: 788px;
	    margin: 10px auto;
	    border: 1px solid green;
	    background: green;
	} */
	#header,#footer {
	    width: 772px;
	}

	#content {
	    float: left;
	    width: 360px;    
	}
	
	#footer {
	    clear: both;
	}
</style>