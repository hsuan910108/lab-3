<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js">
</script>

<script>
$(document).ready(function(){
  $("#describe").click(function(){
    $("#list").slideToggle("slow");
  });
});
</script>

<html>

<style>
 .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
 
 body {
      background-color:#E8E8D0;
    }
 

 #north, #south, #east, #west {
   font-size: 60px;
   text-align: center;
   color: #106B00;
 }
 
 #describe, #list {
  padding: 5px;
  text-align: center;
  background-color: #f0e68c;
  border: solid 1px #c3c3c3;
}

#list {
  padding: 50px;
  display: none;
}
</style>
  
  
<body>
  
  <h1>美食札記</h1>
    
 <p>
  生活中的困擾，沒有甚麼是吃解決不了的！
 </p>
 <p>
  在這裡除了是自己的小小記錄之外，還想跟大家分享所有好吃的東西。
 </p>
 
 <header>
 <div id="describe">點選以查看或隱藏分類</div>
  <ul id="list">
   <li><a href="#north">北部</a></li>
   <li><a href="#west">中部</a></li>
   <li><a href="#south">南部</a></li>
   <li><a href="#east">東部</a></li>  
  </ul>
 </header>
  
 
 
 <h1 id="north">北部</h1>
  <p>
  1.寶島漫波義大利麵<br> 辣味蒜香小卷義大利麵
  </p>
  <img src="https://i.imgur.com/qbOyoR1.jpg" width=400px alt="一張圖片">
  <p>
  2.Afterhours&nbsp;Cafe<br>日本山形水蜜桃戚風 <br> 焦糖脆片戚風蛋糕
  </p>
  <img src="https://i.imgur.com/qUSJ7h2.jpg" width=400px alt="一張圖片">
  
 <h2 id="west">中部</h2>
  <p>
  1.小田生活 <br> 玫瑰生乳酪 <br> 伯爵生乳酪 <br> 抹茶拿鐵 <br> 美式咖啡
  </p>
  <img src="https://i.imgur.com/15NmufM.jpg" width=400px alt="一張圖片">
  <p>
    
 <h3 id="south">南部</h3>
  <p>
  1.小北家灶咖ZAOKA <br> 鮮蝦野菇炊飯 <br> 自製香料香烤雞腿排 <br> 南洋風牛肉咖哩飯
  </p>
  <img src="https://i.imgur.com/WgdCfpg.jpg" width=400px alt="一張圖片">
  
  
 <h4 id="east">東部</h4>
  <p>
  1.榕樹下米苔目 <br> 米苔目(小)(乾)
  </p>
  <img src="https://i.imgur.com/NNlZfRR.jpg" width=400px alt="一張圖片">
  <p>
  2.玉里橋頭臭豆腐 <br> 臭豆腐(小份)
  </p>
  <img src="https://i.imgur.com/10wj8M1.jpg" width=400px alt="一張圖片">


</body>
</html>
