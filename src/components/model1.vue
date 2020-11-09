<template>
    <div id = "index" class = "Title1">
        <lu id = "firstLine">
            <li id = "one"><a href="#" id="firstBigTitle"><img src = "a.png">英雄联盟</a><a href="#" id="checkAll">全部</a></li>
            <!-- <li id = "two"><a href="#"><img src = "a.png">主机单机</a></li>
            <li id = "three"><a href="#"><img src = "a.png">绝地求生</a></li> -->
         </lu>
        <lu id = "secondLine">
            <br>
            <li id="A"><img src = "a.png">A</li>
            <li id="B"><img src = "a.png">B</li>
            <!-- <li id="C"><img src = "a.png">C</li>
            <li id="D"><img src = "a.png">D</li>
            <li id="E"><img src = "a.png">E</li>
            <li id="F"><img src = "a.png">F</li> -->
        </lu>
        <lu id = "thirdLine">
            <li id="G"><img src = "a.png">G</li>
            <li id="H"><img src = "a.png">H</li>
            <!-- <li id="I"><img src = "a.png">I</li>
            <li id="JK"><img src = "a.png">J</li>
            <li id=""><img src = "a.png">K</li>
            <li id="L"><img src = "a.png">L</li> -->
        </lu>
    </div>
    
</template>

<script>
export default {
    name: 'model1',
    props: {
        msg: String,
        index : Number
  }
}
</script>

<style>
    .Title1{
        list-style-type: none;
        position: relative;
        background-color: rgb(205, 225, 243);
        width: 25%;
        height: 250px;
        margin-top: 10px;
        float: left;
    }
    a{
        text-decoration: none;
        color: black
        
    }
    a:hover{
        color: darkkhaki;
    }
    #model1pic{
        position: relative;

    }
    #firstBigTitle{
        margin: 10px 100px 10px 20px;
        font-size: x-large;
        font-weight: bold;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
   
    #secondLine li{
        margin: 10px 100px 10px 20px;
        font-size: xx-large; 
    }
    /*#A{
        float: left;
    }
    #G{
        float: left;
    }
    #thirdLine li{
        margin: 10px 100px 10px 20px;
        font-size: xx-large;
    } */
</style>