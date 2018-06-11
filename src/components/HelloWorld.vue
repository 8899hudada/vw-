<template>
  <div class="aspectratio">
      <div class="aspectratio-content">
        <div class="test">
          我是测试
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
.test {
  border: .5px solid black;
  border-bottom-width: 4px;
  font-size: 14px;
  height: 30px;
  line-height: 20px;
  position: relative;
  background-color: indianred;
}
[w-188-246] {
  width: 188px;
}

  [aspectratio] {
    position: relative;
  }
  [aspectratio]::before {
    content: '';
    display: block;
    width: 1px;
    margin-left: -1px;
    height: 0;
  }
  [aspectratio-content] {
       position:absolute;
       top: 0;
       left: 0;
       right: 0;
       bottom: 0;
       width: 100%;
       height: 100%;
  }
</style>
