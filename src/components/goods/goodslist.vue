<template>
    <div class="goods-list">
        <router-link class="goods-item" to="/home/goodsinfo" tag="div">
            <img src="http://shihuo.hupucdn.com/trade/reposition/2018-08-14/7e2f09f8bec2d7478e7e7a1dedd99ecf.png" alt="">
            <h1>Nike Kyrie 4</h1>
            <div class="info">
                <p class="price">
                    <span class="new">￥739</span>
                    <span class="old">￥1099</span>
                </p>
                <p class="sell">
                    <span>热销中</span>
                    <span>剩余36件</span>
                </p>
            </div>
        </router-link>
         <router-link class="goods-item" to="/home/goodsinfo" tag="div">
            <img src="http://shihuo.hupucdn.com/def/20180802/0c85c6ca6f1d7b862eef2ec2ac057b971533219738.jpg" alt="">
            <h1>Air Jordan 11</h1>
            <div class="info">
                <p class="price">
                    <span class="new">￥999</span>
                    <span class="old">￥1250</span>
                </p>
                <p class="sell">
                    <span>热销中</span>
                    <span>剩余10件</span>
                </p>
            </div>
        </router-link>
         <router-link class="goods-item" to="/home/goodsinfo" tag="div">
            <img src="http://shihuo.hupucdn.com/def/20180813/3226d37301549848d13cbcd9bd43379a1534161327.jpg" alt="">
            <h1>Adidas D Rose 7 罗斯7代全掌boost男篮球鞋</h1>
            <div class="info">
                <p class="price">
                    <span class="new">￥510</span>
                    <span class="old">￥785</span>
                </p>
                <p class="sell">
                    <span>热销中</span>
                    <span>剩余300件</span>
                </p>
            </div>
        </router-link>
         <router-link class="goods-item" to="/home/goodsinfo" tag="div">
            <img src="http://shihuo.hupucdn.com/def/20170925/2e8f184ae0cfd9f0e5e89933e91a82061506304706.jpg" alt="">
            <h1>Nike Hypershift EP 实战篮球鞋</h1>
            <div class="info">
                <p class="price">
                    <span class="new">￥375</span>
                    <span class="old">￥499</span>
                </p>
                <p class="sell">
                    <span>热销中</span>
                    <span>剩余500件</span>
                </p>
            </div>
        </router-link>
         <router-link class="goods-item" to="/home/goodsinfo" tag="div">
            <img src="http://shihuo.hupucdn.com/trade/reposition/2018-08-04/8443a97c90b0570d889572e06620abaa.png" alt="">
            <h1>Air Jordan 1小黑红Mid</h1>
            <div class="info">
                <p class="price">
                    <span class="new">￥980</span>
                    <span class="old">￥1150</span>
                </p>
                <p class="sell">
                    <span>热销中</span>
                    <span>剩余150件</span>
                </p>
            </div>
        </router-link>

        <mt-button type="danger" size="large">加载更多</mt-button>
    </div>
</template>

<script>
    
</script>

<style lang="less" scoped>
    .goods-list{
        display: flex;
        flex-wrap: wrap;
        padding: 8px;
        justify-content: space-between;
        .goods-item{
            width: 49%;
            border: 1px solid #ccc;
            box-shadow: 0 0 8px #ccc;
            margin: 4px 0;
            padding: 2px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            min-height: 280px;
            img{
                width: 100%;
            }
            h1{
                font-size: 14px;
            }
            .info{
                background-color: #eee;
                p{
                    margin: 0;
                    padding: 5px;
                }
                .price{
                    .new{
                        color: red;
                        font-weight: bold;
                        font-size: 16px;
                    }
                    .old{
                        text-decoration: line-through;
                        margin-left: 10px;
                    }
                }
                .sell{
                    display: flex;
                    justify-content: space-between;
                    font-size: 12px;
                }
            }
        }
    }
</style>

