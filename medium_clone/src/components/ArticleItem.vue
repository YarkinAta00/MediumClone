<script>
export default {
    name: 'ArticleItem',
    props: {
        articleName: {
            type: String,
            required: true
        },
        articleImage: {
            type: String,
            required: true
        },
        articleNumber: {
            type: String,
            required: true
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
    <article class="col-sm-4">
        <div class="row">
            <div class="col-1 px-2">
                <strong>
                    <h1 class="display-6" style="color:rgb(230, 230, 230);">
                        {{ articleNumber }}
                    </h1>
                </strong>
            </div>
            <div class="col-11 px-5 py-2">
                <img class="rounded-circle" :src="articleImage" >
                <span class="px-2"> 
                    {{ articleAuthor }}
                    JP Brown
                </span>
            </div>
        </div>
        <div class="col-11">
            <h5 class="px-5">
                <small>
                    <strong class="px-1">
                        {{ articleName }}
                        What Really Happens to a Human Body at Titanic Depths
                    </strong>
                </small>
            </h5>
            <ul class="list-unstyled px-5">
                <li>
                    <small class="text-secondary">
                        {{ articleDate }}
                        Jun 2 22 - 4 min read
                    </small>
                </li>
            </ul>
        </div>
    </article>
</template>
