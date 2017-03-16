<template>  
  <div id="header">
    <!-- Fixed navbar -->  
    <div id="fixed-bar" class="navbar-fixed-top">  
        <!-- logo  -->
        <div class="nav navbar-header navbar-left"> 
          <a href="#">
            <img id="logo" src="../../assets/pic/home/logo.png">
          </a> 
        </div>  
      
        <!-- 登陆信息 -->
        <div>  
          <ul class="nav navbar-nav navbar-right">  
            <li class="active"><a href="/">用户:{{userName}}</a></li>  
            <li><a href="#">修改密码</a></li>  
            <li><a href="#">退出</a></li>  
          </ul>  
        </div>
      </div>
  </div>
</template>  

<style>
  #fixed-bar{
      border: 1px solid black;    
      margin: 5px 60px;
      padding: 2px 16px;
  }
  #logo{
    height: 45px;
  }
  
</style>


<script>  
export default {  
  name: 'header',  
  data () {  
    return {  
      userName: '管理员'  
    }  
  }  
}  
</script>  
