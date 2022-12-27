<script>
	
  export default {
   data(){
     return{
      programing:{
        language:'c++',
        author:[
          'name author languege',
          'idea creating languege c++'
        ]
      }
     }
   } 
  }  
</script>

<template>
  <div class="flexDiv">
    <p class="cpp">
    	C++
    </p>

    <p class="cpp">
    	Python
    </p>

    <p class="cpp">
    	JavaScript
    </p>
    
    <p class="cpp">
    	Java
    </p>
    
    <p class="cpp">
    	C#
    </p>
    
  </div> 
  <h1 class="iff">
    {{programing.author.length >= 3 ?  'ogogogogogogo' : 'Every language unical in own'}}
  </h1>
</template>

<style>
  body{
    background: linear-gradient( 180deg, #f990ff 0, #a974ff 25%, #5353f2 50%, #0033b2 75%, #001979 100%);
    background-repeat:no-repeat;
  }
  .flexDiv{
    display:flex;
    width:100%;
   	
  }
  p{
    margin-left:0.8em;
  }
  .cpp{
    background-color:#42AAFF;
    width:10%;
    height:30px;
    border:3px solid black;
    border-radius:10px;
    text-align:center;
  }
  .iff{
    background-color:#C5D0E6;
    border:4px solid black;
    width:59%;
    padding:0.5em;
    border-radius:20px;
  }
</style>
