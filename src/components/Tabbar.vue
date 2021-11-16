<template>
    <div class="tabbar">
        <router-link tag="div" class="item" to="/recommend">
            <span>推荐</span>
        </router-link>
         <router-link tag="div" class="item" to="/singer">
            <span>歌手</span>
        </router-link>
         <router-link tag="div" class="item" to="/rank">
            <span>排行</span>
        </router-link>
         <router-link tag="div" class="item" to="/search">
            <span>搜索</span>
        </router-link>
    </div>
</template>

<script>
export default {
    name: "Tabbar"
}
</script>

<style scoped lang="scss">
@import "../assets/css/variable";
@import "../assets/css/mixin";
    .tabbar {
        width: 100%;
        height: 84px;
        @include bg_sub_color();
        // 文字水平排版
        display: flex;
        justify-content: space-around;
    }
</style>