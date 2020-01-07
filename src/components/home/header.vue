<template>
    <div class="header-container">
        <div class="header-left">
            <i class="iconfont">&#xe624;</i>
        </div>
        <div class="header-search">
            <span><i class="iconfont">&#xe632;</i>输入城市/景点/游玩主题</span>
        </div>
        <div class="header-right">
            <span>城市<i class="iconfont icon-arrow">&#xe64a;</i></span>
        </div>
    </div>
</template>

<script>
    export default {}
</script>

<style scoped lang="less">
    @import "~@styles/variables";
    .header-container{
        display: flex;
        line-height: .86rem;
        background: @bgcolor;
        color: #fff;
        .header-left{
            width: .64rem;
            float: left;
            text-align: center;
            i{
                font-size: .32rem;
            }
        }
        .header-search{
            flex: 1;
            height: .64rem;
            line-height: .64rem;
            background: #fff;
            margin-top: .12rem;
            margin-left: .12rem;
            padding-left: .2rem;
            border-radius: .1rem;
            color: #ccc;
        }
        .header-right{
            width: 1.24rem;
            float: right;
            text-align: center;
            .icon-arrow{
                font-size: .24rem;
                padding-left: .02rem;
            }
        }
    }
</style>