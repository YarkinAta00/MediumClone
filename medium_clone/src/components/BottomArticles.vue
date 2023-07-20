<script>
import BottomArticleItem from './BottomArticleItem.vue'
import BottomButtons from './BottomButtons.vue';
export default {
    name: 'BottomArticles',
    components: {
        BottomArticleItem,
        BottomButtons,
    }
}

</script>

<template>
    <div class="container">
        <div class="row mt-5">
            <section class="col-sm-8">
                <BottomArticleItem/>
                <BottomArticleItem/>
                <BottomArticleItem/>
            </section>
            <aside class="col-sm-4">
                <BottomButtons />
            </aside>
        </div>
    </div>
</template>