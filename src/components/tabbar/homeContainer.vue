<template>
    <div>
        <mt-swipe :auto="4000">
            <mt-swipe-item>
                <img src="http://img1.gtimg.com/chinanba/pics/hv1/112/212/2290/148961422.jpg" alt="">
            </mt-swipe-item>
            <mt-swipe-item>
                <img src="http://img1.gtimg.com/chinanba/pics/hv1/129/190/2290/148955829.jpg" alt="">
            </mt-swipe-item>
            <mt-swipe-item>
                <img src="http://img1.gtimg.com/chinanba/pics/hv1/213/197/2290/148957698.jpg" alt="">
            </mt-swipe-item>
            <mt-swipe-item>
                <img src="http://img1.gtimg.com/chinanba/pics/hv1/161/229/2290/148965806.jpg" alt="">
            </mt-swipe-item>
        </mt-swipe>
        <ul class="mui-table-view mui-grid-view mui-grid-9">
            <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3"><router-link to="/home/newList">
                <span class="mui-icon iconfont icon-tiyu-lanqiu"></span>
                <!--<span class="mui-icon mui-icon-home"></span>-->
                <div class="mui-media-body">体育资讯</div></router-link></li>
            <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3"><router-link to="/home/photolist">
                <!-- <img src="../../images/2.png" alt=""> -->
                <span class="mui-icon iconfont icon-tiyu-kualan"></span>
                <!--<span class="mui-icon mui-icon-email"><span class="mui-badge">5</span></span>-->
                <div class="mui-media-body">比赛图集</div></router-link></li>
            <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3"><router-link to="/home/goodslist">
                <!-- <img src="../../images/3.png" alt=""> -->
                <span class="mui-icon iconfont icon-tiyu-qipao"></span>
                <!--<span class="mui-icon mui-icon-chatbubble"></span>-->
                <div class="mui-media-body">识货团购</div></router-link></li>
            <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3"><a href="#">
                <!-- <img src="../../images/4.png" alt=""> -->
                <span class="mui-icon iconfont icon-tiyu-zihangche"></span>
                <!--<span class="mui-icon mui-icon-location"></span>-->
                <div class="mui-media-body">球队赛程</div></a></li>
            <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3"><a href="#">
                <!-- <img src="../../images/5.png" alt=""> -->
                <span class="mui-icon iconfont icon-tiyu-gaoerfuqiu"></span>
                <!--<span class="mui-icon mui-icon-search"></span>-->
                <div class="mui-media-body">热门视频</div></a></li>
            <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3"><a href="#">
                <!-- <img src="../../images/6.png" alt=""> -->
                <span class="mui-icon iconfont icon-tiyu-wangqiu"></span>
                <!--<span class="mui-icon mui-icon-phone"></span>-->
                <div class="mui-media-body">社区话题</div></a></li>
        </ul>
        <!--<h3>这是HomeContainer页面</h3>-->
    </div>
</template>

<script>
    import { Toast } from 'mint-ui'
    export default {
        data(){
            return {
                lunbotuList:[]
            }
        },
        created(){
            // this.getLunbotu()
        },
        methods:{
            // getLunbotu(){
            //     this.$http.get("http://localhost:5000/server.html").then(result => {
            //        if(result.body.state === 0){
            //            this.lunbotuList = result.body.message;
            //            Toast('加载图片成功...')
            //        }else {
            //             Toast('加载图片失败...')
            //        }
            //     })
            // }
        }
    }
</script>

<style scoped lang="less">
    .mint-swipe{
        height: 250px;
        .mint-swipe-item{
            width: 100%;
            img{
                width: 100%;
                height: 100%;
            }
        }
    }
    .mui-grid-view.mui-grid-9{
        background-color: #fff;
        border: none;
        // span{
        //     display: block;
        //     width: 60px;
        // }
        .mui-media-body{
            font-size: 15px;
        }
    }
    .mui-grid-view.mui-grid-9 .mui-table-view-cell{
        text-align: center;
        border: none;
        color: #a41f24;
        .iconfont{
            font-size: 50px;
        }
    }
</style>