<template>
    
    <div class="all">
        <div class="item">
            <a href="https://brightspace.ucd.ie/d2l/home">签到</a>
        </div>
        <div class="item">

            <p>
                <a href="https://brightspace.ucd.ie/d2l/home">下载</a>
            </p>

        </div>
        <div class="item">

            <p>
                <a href="https://brightspace.ucd.ie/d2l/home">合作</a>
            </p>

        </div>
        <div class="item">
            <p>
                <a href="https://brightspace.ucd.ie/d2l/home">开播</a>
            </p>
        </div>
        <div class="item">
            <p>
                <a href="https://brightspace.ucd.ie/d2l/home">反馈</a>
            </p>
        </div>
        <div class="item">
            <p>
                <a href="window.scrollTo(0,0);">回顶</a>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'rightHelp',
    props: {
        msg: String
  }
}
</script>

<style>
    .all{
            width: 35px;
            background-color: rgb(248, 249, 250);
            right: 2px;
            margin-top: 250px;
            position: fixed;
            z-index: 10;
        }
        .item{
            font-size: 15px;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            margin: 20px 0 0 0; 
            /* margin-left: 100px; */
            padding-left: 2px;
            
        }
        a:hover{
            color: brown;
        }
</style>