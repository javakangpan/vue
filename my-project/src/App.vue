<template>
  <div id="app" class="main">
    <div class="top-contant">客户群新闻</div>
      <el-row>
        <el-col>
          <div class="news">
            <div>
            <img src="../images/12.png" class="image">
            <div class="image-text"><a href="#">特朗普回应G7“被围攻”：我们很融洽</a></div>
            <div class="span-text"><a href="#">特朗普回应G7“被围攻”：我们很融洽</a></div>
            <div class="bottom clearfix">
              <time class="time">2018-12-28 00:00:00</time>
            </div>
            </div>
          </div>
        </el-col>
        <el-col>
          <div class="news">
            <div>
            <img src="../images/11.jpg" class="image">
            <div class="image-text"><a href="#">2018年俄罗斯世界杯足球赛将在这里开幕”</a></div>
            <div class="span-text"><a href="#">2018年俄罗斯世界杯足球赛将在这里开幕</a></div>
            <div class="bottom clearfix">
              <time class="time">2018-12-28 00:00:00</time>
            </div>
            </div>
          </div>
        </el-col>
        <el-col>
          <div class="news">
            <div>
            <img src="../images/15.jpg" class="image">
            <div class="image-text"><a href="#">50人耗时13小时包出20余米长粽子 有7层楼高</a></div>
            <div class="span-text"><a href="#">50人耗时13小时包出20余米长粽子 有7层楼高</a></div>
            <div class="bottom clearfix">
              <time class="time">2018-12-28 00:00:00</time>
            </div>
            </div>
          </div>
        </el-col>
        <el-col>
          <div class="news">
            <div>
            <img src="../images/14.jpg" class="image">
            <div class="image-text"><a href="#">江苏盱眙：5万人共享“龙虾宴”</a></div>
            <div class="span-text"><a href="#">江苏盱眙：5万人共享“龙虾宴</a></div>
            <div class="bottom clearfix">
              <time class="time">2018-12-28 00:00:00</time>
            </div>
            </div>
          </div>
        </el-col>
        <el-col>
          <div class="news">
            <div>
            <img src="../images/13.jpg" class="image">
            <div class="image-text"><a href="#">小学入学面试 上千家长带板凳连夜排队”</a></div>
            <div class="span-text"><a href="#">小学入学面试 上千家长带板凳连夜排队</a></div>
            <div class="bottom clearfix">
              <time class="time">2018-12-28 00:00:00</time>
            </div>
            </div>
          </div>
        </el-col>
    </el-row>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>
<style>
  .image-text a{
    color: wheat;
    text-decoration:none;
    z-index:2;
    font-size:12px;
    color:white;
  }
  .image-text a:hover{
    font-weight: bold;
  }
  .span-text a{
    color:black;
    text-decoration:none;
    font-size: 14px;
  }
  .main{
   float: left;
   margin-left: 10px;
  }
  .top-contant{
    margin-left: 6px;
    color:black;
    font-size: 18px;
  }
  .image-text{
    text-align: center;
    opacity:0.6;
    background-color: black;
    position:absolute;
    top:80px;
    width: 160px;
    word-break:break-all;
  }
  .span-text{
    width: 160px;
    word-break:break-all;
    margin-top: 10px;
  }
  .news{
    text-align: center;
    float: left;
    padding: 4px;
  }
  .time {
    font-size: 13px;
    color: #999;
  }
  .bottom {
    margin-top: 13px;
    line-height: 12px;
  }
  .image {
    width: 160px;
    height: 90px;
    display: block;
  }
  .clearfix:before,
  .clearfix:after {
      display: table;
      content: "";
  }
  .clearfix:after {
      clear: both
  }
</style>
