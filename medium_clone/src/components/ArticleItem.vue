<script>
export default {
    name: 'ArticleItem',
    props: {
        articleName: {
            type: String,
            
        },
        articleImage: {
            type: String,
            required: true
        },
        articleNumber: {
            type: String,
           
        },
        articleAuthor: {
            type: String,
            required: true
        },

        articleDate: {
            type: String,
            required: true
        },

    }
}

</script>
<template>
    <article class="col-sm-4 mb-3">
        <div class="row">
            <div class="col-1 pb-5 px-1">
                <strong>
                    <h2 style="color:rgb(230, 230, 230);">
                        {{ articleNumber }}
                    </h2>
                </strong>
            </div>
            <div class="col-11">
                <img class="rounded-circle" :src="articleImage">
                <span class="px-2 small ml-1">
                    {{ articleAuthor }}
                </span>
                <h6 class="mt-2">
                    <strong>
                        {{ articleName }}
                    </strong>
                </h6>
                <ul class="list-unstyled">
                    <li>
                        <small class="text-secondary">
                            {{ articleDate }}
                        </small>
                    </li>
                </ul>
            </div>
        </div>
    </article>
</template>
