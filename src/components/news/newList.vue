<template>
    <div>
       <ul class="mui-table-view">
				<!-- <li class="mui-table-view-cell mui-media" v-for="item in newsList" :key="item.id">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
						<div class="mui-media-body">
							<h1>{{ item.title }}</h1>
							<p class='mui-ellipsis'>
                                <span>{{ item.add_time }}</span>
                                <span>{{ item.click }}</span>
                            </p>
						</div>
					</a>
				</li> -->
                <ul class="mui-table-view">
				 <li class="mui-table-view-cell mui-media">
					<router-link to="/home/newsinfo/1">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/100/84/2291/148993795.jpg">
						<div class="mui-media-body">
							<h1>圆桌会议：印象中国红 祝姚明生日快乐！</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 15:44</span>
                                <span>浏览次数：99</span>
                            </p>
						</div>
					</router-link>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/20/91/2291/148995500.jpg">
						<div class="mui-media-body">
							<h1>德克盛赞东契奇：他的天赋令人难以置信</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 17:18</span>
                                <span>浏览次数：38</span>
                            </p>
						</div>
					</a>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/73/89/2291/148995043.jpg">
						<div class="mui-media-body">
							<h1>格林：小卡不会走 他无法拒绝多伦多的热情</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 16:46</span>
                                <span>浏览次数：69</span>
                            </p>
						</div>
					</a>
				</li>
               <li class="mui-table-view-cell mui-media">
					<router-link to="/home/newsinfo/1">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/238/86/2291/148994443.jpg">
						<div class="mui-media-body">
							<h1>尝试多种可能 湖人鼓励库兹马尝试三号位</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 16:18</span>
                                <span>浏览次数：29</span>
                            </p>
						</div>
					</router-link>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/39/85/2291/148993989.jpg">
						<div class="mui-media-body">
							<h1>猛龙将于22日举行新援介绍会 小卡格林将出席</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 15:44</span>
                                <span>浏览次数：49</span>
                            </p>
						</div>
					</a>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/102/77/2291/148992012.jpg">
						<div class="mui-media-body">
							<h1>莫雷：德帅对球队很有信心 新援可完美融入体系</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 12:05</span>
                                <span>浏览次数：63</span>
                            </p>
						</div>
					</a>
				</li>
                <li class="mui-table-view-cell mui-media">
					<router-link to="/home/newsinfo/1">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/244/73/2291/148991134.jpg">
						<div class="mui-media-body">
							<h1>承担起领袖责任 乐福在迈阿密组织球队集训</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 11:05</span>
                                <span>浏览次数：30</span>
                            </p>
						</div>
					</router-link>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/35/70/2291/148990160.jpg">
						<div class="mui-media-body">
							<h1>阿伦：湖人没那么多投手 詹姆斯需调整自己</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 10:17</span>
                                <span>浏览次数：75</span>
                            </p>
						</div>
					</a>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/236/69/2291/148990106.jpg">
						<div class="mui-media-body">
							<h1>哈斯勒姆谈重回热火：全因对于球队的热爱</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-12 10:07</span>
                                <span>点击次数：109</span>
                            </p>
						</div>
					</a>
				</li>
                <li class="mui-table-view-cell mui-media">
					<router-link to="/home/newsinfo/1">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/27/52/2291/148985562.jpg">
						<div class="mui-media-body">
							<h1>封神演绎：林疯狂38分7助攻让科比爆粗口</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-11 16:20</span>
                                <span>浏览次数：1500</span>
                            </p>
						</div>
					</router-link>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/85/34/2291/148981030.jpg">
						<div class="mui-media-body">
							<h1>拉文：我已恢复到100% 感觉自己更强壮了</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-11 10:26</span>
                                <span>浏览次数：61</span>
                            </p>
						</div>
					</a>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/147/31/2291/148980327.jpg">
						<div class="mui-media-body">
							<h1>帕克：黄蜂马刺报价相似 偶像亲自招募令我动心</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-11 09:53</span>
                                <span>浏览次数：209</span>
                            </p>
						</div>
					</a>
				</li>
                <li class="mui-table-view-cell mui-media">
					<router-link to="/home/newsinfo/1">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/122/245/2290/148969847.jpg">
						<div class="mui-media-body">
							<h1>马努致敬迪奥：你是我遇到的最好的队友之一</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-10 09:15</span>
                                <span>浏览次数：189</span>
                            </p>
						</div>
					</router-link>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/135/242/2290/148969095.jpg">
						<div class="mui-media-body">
							<h1>曝德文-布克将接受右手手术 无限期休战</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2018-09-10 08:07</span>
                                <span>浏览次数：31</span>
                            </p>
						</div>
					</a>
				</li>
				<li class="mui-table-view-cell mui-media">
					<a href="javascript:;">
						<img class="mui-media-object mui-pull-left" src="http://img1.gtimg.com/chinanba/pics/hv1/76/107/2238/145553311.jpg">
						<div class="mui-media-body">
							<h1>一日为师念念不忘 NBA赛场上那些师徒情谊</h1>
							<p class='mui-ellipsis'>
                                <span>发表时间：2017-09-10 18:16</span>
                                <span>浏览次数：4699</span>
                            </p>
						</div>
					</a>
				</li>
			</ul>
			</ul>
    </div>
</template>

<script>
    //  import { Toast } from 'mint-ui'
    // export default {
    //     data(){
    //         return {
    //             newsList:[]
    //         }
    //     },
    //     created(){
    //         this.getNewsList()
    //     },
    //     methods:{
    //         getNewsList(){
    //             this.$http.get("api/newList").then(result => {
    //                if(result.body.state === 0){
    //                    this.newsList = result.body.message;
    //                    Toast('加载图片成功...')
    //                }else {
    //                     Toast('加载图片失败...')
    //                }
    //             })
    //         }
    //     }
    // }
</script>

<style scoped lang="less">
    .mui-table-view{
        li{
            h1{
                font-size: 14px;
			}
            .mui-ellipsis{
                font-size: 12px;
                color: #226aff;
                display: flex;
                justify-content: space-between;
            }
        }
    }
</style>