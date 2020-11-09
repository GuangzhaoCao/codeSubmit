<template>
    <div id = "tab" class="tab">
            <ul>
                <li id = "list1" class = "on tab-item"><div class="tab-header">第一页</div>
                <div id="first" class = "hide tab-content">
                    <a href="#">我很奇怪</a><br>
                    <a href="#">为什么</a><br>
                    <a href="#">在外面</a><br>
                    <a href="#">再加一层</a><br>
                </div></li>
                <li id = "list2" class = "off tab-item"><div class="tab-header">第二页</div>
                <div id="second" class = "hide tab-content">
                    <a href="#">div</a><br>
                    <a href="#">还用getid方法</a><br>
                    <a href="#">他就不行了</a><br>
                    <a href="#">很奇怪</a><br>
                </div></li>
                <li id = "list3" class = "off tab-item"><div class="tab-header">第三页</div>
                <div id="third" class = "hide tab-content">
                    <a href="#">只能这样</a><br>
                    <a href="#">他才可以</a><br>
                    <a href="#">运行</a><br>
                    <a href="#">？？？？</a><br>
                 </div></li>
                <li id = "list4" class = "off tab-item"><div class="tab-header">第四页</div>
            <div id="fourth" class = "hide tab-content">
                    <a href="#">阿巴</a><br>
                    <a href="#">阿巴</a><br>
                    <a href="#">阿巴</a><br>
                    <a href="#">阿巴</a><br>
                 </div></li>
            </ul>
    
    </div>
</template>

<script>
// window.onload = function(){
//         var myTab = document.getElementById("tab");    
//         var myUl = myTab.getElementsByTagName("ul")[0];
//         var myLi = myUl.getElementsByTagName("li"); 
//         var myDiv = myTab.getElementsByTagName("div"); 
//         for(var i = 0;i < myLi.length; i++){
//             myLi[i].index = i;
//             myLi[i].onmouseover = function(){
//                 for(var j = 0; j < myLi.length; j++){
//                     myLi[j].className = "off";
//                     myDiv[j].className = "hide";
//                 }
//                 this.className = "on";
//                 myDiv[this.index].className = "";
//             };
//         }
//     };
export default {
  name: 'BoxChange',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{ margin:0; padding: 0; }
    a{ text-decoration: none; }

    h1{ 
        margin: 10px ; 
        text-align: center; 
    }
    .tab-item{
        position: relative;

    }
    .tab-header{
        position: absolute;
        top:0;
        left: 0;
    }
    .tab-content{
        position: absolute;
        top:0;
        left: 0;
    }

    .tab{
        width: 100%;
        height: 100%;
        margin: 20px 20px 50px 20px;
        padding: 10px;
         clear: both; 
    }
    .tab ul li{
        float: left;
        list-style-type: none;
        padding: 0 100px;
        font-size: 30px;
        margin-left: 60px;
    } 
    .tab ul li.on{
        border-top:3px solid rgb(164, 156, 240); 
        border-bottom:2px solid #FFF;
    }
    .tab div{
        height: 500px;
        width: 260px;
        margin-left: 160px;
        margin-top: 100px;
        position: absolute;
        border: 2px solid #6495ed;
        font-size: 20px;
        background-color: #6495ed;
        z-index: 1;
    }
    .tab div a{
    color: #2c3e50;
    margin-bottom: 20px;
    } 

    /* #first{
        margin-left: 5%;
    }
    #second{
        margin-left: 30%;
    }
    #third{
        margin-left: 55%;
    }
    #fourth{
        margin-left: 80%;
    } */
    .hide {
        display: none;
    }
</style>
