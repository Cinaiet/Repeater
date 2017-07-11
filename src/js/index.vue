<template>
    <div>
        <header>
            <div class="header-add">+</div>
            <div class="header-file">文件</div>
            <div class="header-play">正在播放</div>
        </header>
        <nav>
            <homeList></homeList>
        </nav>
        <footer>
            <div class="footer-set">设置</div>
            <div class="footer-compile">编辑</div>
        </footer>
    </div>
</template>
<script>
import homeList from './components/homeList.vue';
export default {
    components: {
       homeList 
    }
}
</script>
<style lang="scss" scoped>
    header{
        background: red;
        padding: 5px;

        div{
            background: grey;
        }
    }
    nav{
        background: orange;
    }
    footer{
        background: yellow;
    }
</style>
