<template>
    <div class="cmt-container">
        <h3>发表评论：</h3>
        <hr>
        <textarea placeholder="请输入你要发表的内容"></textarea>
        <mt-button type="primary" size="large">发表评论</mt-button>
        <div class="cmt-list">
            <div class="cmt-items">
                <div class="cmt-title">
                    第一楼 &nbsp;&nbsp;用户：匿名&nbsp;&nbsp;&nbsp; 发表时间&nbsp;&nbsp;&nbsp; 2018-09-09 19:50
                </div>
                <div class="cmt-body">
                    致敬，大姚！！！
                </div>
            </div>
             <div class="cmt-items">
                <div class="cmt-title">
                    第二楼 &nbsp;&nbsp;用户：匿名&nbsp;&nbsp;&nbsp; 发表时间 &nbsp;&nbsp;&nbsp;2018-09-09 19:50
                </div>
                <div class="cmt-body">
                   站在2米26的高度，他几乎以一举之力改变了NBA只在一个国度风靡的局面，推动了NBA至关重要的全球化发展。
                </div>
            </div>
             <div class="cmt-items">
                <div class="cmt-title">
                    第三楼 &nbsp;&nbsp;用户：匿名&nbsp;&nbsp;&nbsp; 发表时间&nbsp;&nbsp;&nbsp; 2018-09-09 19:50
                </div>
                <div class="cmt-body">
                    火箭总冠军！！！
                </div>
            </div>
            <div class="cmt-items">
                <div class="cmt-title">
                    第四楼 &nbsp;&nbsp;用户：匿名&nbsp;&nbsp;&nbsp; 发表时间&nbsp;&nbsp;&nbsp; 2018-09-09 19:50
                </div>
                <div class="cmt-body">
                    姚麦，我的青春，我的梦！！！
                </div>
            </div>
            <div class="cmt-items">
                <div class="cmt-title">
                    第五楼 &nbsp;&nbsp;用户：匿名&nbsp;&nbsp;&nbsp; 发表时间&nbsp;&nbsp;&nbsp; 2018-09-09 19:50
                </div>
                <div class="cmt-body">
                    大姚，生日快乐！！！
                </div>
            </div>

        </div>
        <mt-button type="danger" size="large" plain>加载更多</mt-button>
    </div>
</template>

<script>
    
</script>

<style scoped lang="less">
    .cmt-container{
        margin: 20px 10px 0;
        h3{
            font-size: 18px;
        }
        textarea{
            font-size: 14px;
            height: 85px;
            margin: 0;
        }
        .cmt-list{
            margin: 5px 0;
            .cmt-items{
                .cmt-title{
                    background-color: #ccc;
                    font-size: 13px;
                    line-height: 30px;
                    color:#a41f24;
                }
                .cmt-body{
                    line-height: 30px;
                    text-indent: 2em;
                    color:steelblue;
                }
            }
        }
    }
</style>

