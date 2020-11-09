<template>
    <div class="outlist">
        <ul class="list">
            <li><a href="https://www.w3school.com.cn/js/js_intro.asp">w3school</a></li>
            <li><a href="https://brightspace.ucd.ie/d2l/home">brightspace</a></li>
            <li><a href="https://csmoodle.ucd.ie/moodle/course/view.php?id=893">csmoodle</a></li>
            <li><a href="https://www.csdn.net/">CSDN</a></li>
        </ul>
    </div>
</template>

<script>
// window.onload = function(){
//         var myTab = document.getElementById("tab");    
//         var myUl = myTab.getElementsByTagName("ul")[0];
//         var myLi = myUl.getElementsByTagName("li"); 
//         var myDiv = myTab.getElementsByTagName("div"); 
//         debugger;
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
  name: 'NavigationBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{ margin:0; padding: 0; }
    a{ text-decoration: none; }
    .outlist{
         width: 100%; 
         height: 40px;
         margin-top: 30px; 
         background-color: rgb(90, 78, 70); 
         }
    .list{ 
        width: 100%; 
        height: 40px; 
        margin: 0px; 
        list-style-type: none; 
    }
    .list li{ 
        float: left; 
        padding-left: 81px;
    }
    .list li a{ 
        padding: 0 100px; 
        color: #aaa; 
        line-height: 40px; 
        display: block; 
    }
    .list li a:hover{ 
        background:rgb(247, 11, 148); 
        color:#fff;
    }
    h{
        text-align: center;
    }
    
</style>
