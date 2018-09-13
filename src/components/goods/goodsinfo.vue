<template>
    <div class="goodsinfo-container">
        <transition
        @before-enter="before"
        @enter="enter"
        @after-enter="after">
            <div class="ball" v-show="ballFlag" ref="ball"></div>
        </transition>

        <div class="mui-card">
			<div class="mui-card-content">
				<div class="mui-card-content-inner">
					<mt-swipe :auto="4000">
                        <mt-swipe-item>
                            <img src="https://c.static-nike.com/a/images/t_PDP_1280_v1/f_auto/ciuh5lj40jvk51birk2a/kyrie-4-ep-男子篮球鞋-1l1wok.jpg" alt="">
                        </mt-swipe-item>
                        <mt-swipe-item>
                            <img src="https://c.static-nike.com/a/images/t_PDP_1280_v1/f_auto/om5h7qjwnrfflf3aklcn/kyrie-4-ep-男子篮球鞋-1l1wok.jpg" alt="">
                        </mt-swipe-item>
                        <mt-swipe-item>
                            <img src="https://c.static-nike.com/a/images/t_PDP_1280_v1/f_auto/cuq51rsze3dhl6froww7/kyrie-4-ep-男子篮球鞋-1l1wok.jpg" alt="">
                        </mt-swipe-item>
                        <mt-swipe-item>
                            <img src="https://c.static-nike.com/a/images/t_PDP_1280_v1/f_auto/tub3jeqfvdci3uzgpr6h/kyrie-4-ep-男子篮球鞋-1l1wok.jpg" alt="">
                        </mt-swipe-item>
                        <mt-swipe-item>
                            <img src="https://c.static-nike.com/a/images/t_PDP_1280_v1/f_auto/umoihb0ilwusuyohwjdu/kyrie-4-ep-男子篮球鞋-1l1wok.jpg" alt="">
                        </mt-swipe-item>
                    </mt-swipe>
				</div>
			</div>
		</div>


        <div class="mui-card">
				<div class="mui-card-header">Nike Kyrie 4</div>
				<div class="mui-card-content">
					<div class="mui-card-content-inner">
						<P class="price">
                            市场价：<del>￥1099</del> &nbsp;&nbsp;&nbsp;现售价：<span class="now">￥739</span>
                        </P>
                        <p>购买数量：<numbox @getcount="getSelectCount"></numbox></p>
                        <p>
                            <mt-button type="primary" size="small">立即购买</mt-button>
                            <mt-button type="danger" size="small" @click="addToShopCar">加入购物车</mt-button>
                        </p>
					</div>
				</div>
		</div>


        <div class="mui-card">
				<div class="mui-card-header">商品详情</div>
				<div class="mui-card-content">
					<div class="mui-card-content-inner">
                        <p>
                            <span class="goods-title">品牌：</span>
                            <span class="goods-content">Nike/耐克</span>
                            </p>
						<p>
                            <span class="goods-title">款号：</span>
                            <span class="goods-content">943807-002</span>
                            </p>
                        <p>
                            <span class="goods-title">上市时间：</span>
                            <span class="goods-content">2018年春季</span>
                            </p>
                        <p>
                            <span class="goods-title">外底材料：</span>
                            <span class="goods-content">耐磨橡胶</span>
                        </p>
                        <p>
                            <span class="goods-title">运动鞋科技：</span>
                            <span class="goods-content">气垫 缓震胶</span>
                        </p>
					</div>
				</div>
				<div class="mui-card-footer">
                    <mt-button type="primary" size="large" plain @click="goDesc()">图文介绍</mt-button>
                     <mt-button type="danger" size="large" plain @click="goComment()">商品评论</mt-button>
                </div>
			</div>
    </div>
</template>

<script>
    
    import numbox from '../subcomponents/goodsinfo-box.vue'

    export default {
        data(){
            return {
                ballFlag:false,
                selectedCount:1
            }
        },
        methods:{
            goDesc() {
                this.$router.push({name:"goodsdesc"})
            },
            goComment() {
                this.$router.push({name:"goodscomment"})
            },
            addToShopCar(){
                this.ballFlag = !this.ballFlag;
            },
            before(el){
                el.style.transform = "translate(0,0)";
            },
            enter(el,done){
                el.offsetWidth;
                const ballPosition = this.$refs.ball.getBoundingClientRect();
                const badgePosition = document.getElementById('badge').getBoundingClientRect();
                const xDist = badgePosition.left - ballPosition.left;
                const yDist = badgePosition.top - ballPosition.top;
                el.style.transform = `translate(${xDist}px,${yDist}px)`
                el.style.transition = "all 1s cubic-bezier(.4,-0.3,1,.68)"
                done()
            },
            after(el){
                this.ballFlag = !this.ballFlag
            },
            getSelectCount(count){
                this.selectedCount = count;
            }
        },
        components:{
            numbox
        }
    }
</script>

<style lang="less" scoped>
    .goodsinfo-container{
        background-color: #eee;
        overflow: hidden;
        .mint-swipe{
            width: 100%;
            height: 300px;
            background-color: #fff;
        .mint-swipe-item{
            text-align: center;
            width: 100%;
            img{
                // width: 100%;
                height: 100%;
            }
        }
    }
    }
    .now{
        color: red;
        font-size: 16px;
        font-weight: bold;
    }
    .mui-card-footer{
        display: block;
        button{
            margin: 15px 0;
        }
    }
    .ball{
        width: 15px;
        height: 15px;
        border-radius: 50%;
        background-color: red;
        position: absolute;
        z-index: 99;
        top: 490px;
        left: 150px;
    }
</style>

