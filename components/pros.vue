<template>
  <div id="app">
    <div>
        
          <router-link to="/mine">
          <Button class=bts1> 
            <div class="text">
              <p>我</p>
              <p>的</p>
            </div>
          </Button>
          </router-link>
        <router-link to="/all">
          <Button class=bts2>
            <div class="text">
              <p>全</p>
              <p>部</p>
            </div>
          </Button>
          </router-link>
    <router-view></router-view>
    </div>
  </div>
</template>

<script>
import project from './project.vue'
export default {
  components: {
    project
  }
}
</script>

<style>
.bts1{
  position: fixed;
  font-size: 12px;
  color:#4a4a48;
  left:0%;
  top:0px;
  width: 30px;
  height: 60px;
  border-radius:0px;
}
.bts2{
  position: fixed;
  font-size: 12px;
  color:#4a4a48;
  left:0%;
  top:60px;
  width: 30px;
  height: 60px;
  border-radius:0px;
}
.text{
  position: absolute;
  left:9px;
  top:12px;
}
</style>
