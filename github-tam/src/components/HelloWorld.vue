<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <!-- <h3>My company </h3> -->
     <p>
      I work here<br />
      <a href="https://eip.ypcloud.com/zh_TW/" target="_blank" rel="noopener"
        >YPCLOUD</a
      >.
    </p>

    <ul>
    <li>
      <img alt="chibi" src="../assets/jboard.png">
     <a  

          href="https://jboard.ypcloud.com/"
          target="_blank"
          rel="noopener"
          >jboard</a>

  <img alt="chibi" src="../assets/jbuilder.png">
     <a  

          href="https://jbuilder.ypcloud.com/"
          target="_blank"
          rel="noopener"
          >jbuilder</a>     

<img alt="chibi" src="../assets/fbuilder.png">
     <a  

          href="https://fbuilder.ypcloud.com/"
          target="_blank"
          rel="noopener"
          >jbuilder</a>
             
    </li>
    </ul>
    <ul>

<img alt="chibi" src="../assets/ioctouch.png">
     <a  
          href="https://ioctouch.ypcloud.com/"
          target="_blank"
          rel="noopener"
          >ioctouch</a>
        

<img alt="chibi" src="../assets/gitwork.png">
     <a  
          href="https://gitwork.ypcloud.com/"
          target="_blank"
          rel="noopener"
          >gitwork</a>
        

<img alt="chibi" src="../assets/tg.png">
     <a  
          href="https://web.telegram.org/"
          target="_blank"
          rel="noopener"
          >ioctouch</a>
        
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  
}
img{
  height: 100px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
