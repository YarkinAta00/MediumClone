<script>
import ArticleItem from './ArticleItem.vue';
export default {
    data() {
        return {
            imgUrl: 'https://picsum.photos/30/30',
        }
    },
    components: {
        ArticleItem,
    },
}
</script>

<template>
    <div class="border-bottom border-secondary-subtle 1.5px solid mx-3 pb-4">
        <div class="row pt-4 mt-3 mb-4">
            <div class="col-12">
                <h6 class="ml-3">
                    <small>
                        <strong class="px-5">
                            Trending on Medium
                        </strong>
                    </small>
                </h6>
            </div>
        </div>
        <div class="row mb-3 px-4">
            <ArticleItem articleName="What Really Happens to a Human Body at Titanic Depths"
                articleImage="https://picsum.photos/30/30" articleNumber="01" articleAuthor="JP Brown"
                articleDate="Jun 2 22 - 4 min read" />
            <ArticleItem articleName="America Failed Generation X" articleImage="https://picsum.photos/30/30"
                articleNumber="02" articleAuthor="Rocco Pendola" articleDate="Jun 2 22 - 6 min read" />
            <ArticleItem articleName="Finding a Needle in the Ocean" articleImage="https://picsum.photos/30/30"
                articleNumber="03" articleAuthor="Avi Loeb" articleDate="Jun 2 22 - 5 min read" />
            <ArticleItem articleName="Register now for Medium Day" articleImage="https://picsum.photos/30/30"
                articleNumber="04" articleAuthor="Medium Staff" articleDate="Jun 2 22 - 4 min read" />
            <ArticleItem articleName="4 Mental Habits that Cause Low Self-Esteem" articleImage="https://picsum.photos/30/30"
                articleNumber="05" articleAuthor="Nick Wignall" articleDate="Jun 2 22 - 6 min read" />
            <ArticleItem articleName="Stark Contrasts: Desperate Search for Missing Submarine versus..."
                articleImage="https://picsum.photos/30/30" articleNumber="06" articleAuthor="Jahanzeb Ali Rizvi"
                articleDate="Jun 2 22 - 5 min read" />
        </div>
    </div>
</template>