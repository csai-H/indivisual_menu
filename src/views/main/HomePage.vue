<!-- 系统首页 -->
<template>
  <div>
<el-descriptions title="个人用户">
    <el-descriptions-item label="用户名">张三</el-descriptions-item>
    <el-descriptions-item label="电话">18100000000</el-descriptions-item>
    <el-descriptions-item label="地址">武汉</el-descriptions-item>
    <el-descriptions-item label="爱好">
      <el-tag size="small">登山</el-tag>
    </el-descriptions-item>
    <el-descriptions-item label="我的足迹">
      武汉，云南，苏州，沈阳
    </el-descriptions-item>
  </el-descriptions>

  <div class="myfriends">我的搭伴:</div>
  <div class="friends">
    <img src="@/assets/img/team1.png" alt="" class="friend"> 
    <img src="@/assets/img/team2.png" alt="" class="friend">
    <img src="@/assets/img/team3.png" alt="" class="friend">
  </div>
  <div class="mytour">我的旅途:</div>
  <div class="tours">
    <img src="@/assets/img/fengjing2.jpg" alt="" class="tour">
    <img src="@/assets/img/fengjing4.jpg" alt="" class="tour">
    <img src="@/assets/img/fengjing1.jpg" alt="" class="tour">
  </div>


  <div class="saying">我的旅途寄语: </div>
  <p class="saying">旅途中，愿你的每一步都充满阳光，每一处风景都带来惊喜，每一个瞬间都值得珍惜。享受旅途，让心灵和身体都得到释放和滋养。</p>
</div>
 
</template>

<script>
    export default {
        name: "HomePage"
    }
</script>

<style scoped>
.myfriends {
  float: left;
  margin-top:20px;

}
.mytour {
  float:left;
  margin-top:20px;
}

.friend {
  margin-left:10px;
  margin-top:20px;

}

.tour {
  margin-left:10px;
  margin-top:20px;
}
img {
  width:200px;
  height:200px;
}

.saying {
  float: left;
  margin-top: 20px;
  color:#a0cfff;
}

.comment {
  margin: 50px 20px;
  height:100px;
  background-color: skyblue;
}

.views {
  height:100px;
  background-color:skyblue;
  margin-top:20px;
}
</style>
