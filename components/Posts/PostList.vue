<template>
    <section class="post-list">
            <PostPreview 
                id="1"
                thumbnail= "http://www.organicexpo.co.nz/wp-content/uploads/2011/12/glm-march-2017-small.jpg"
                title="Hello there!"
                previewText="This is my first post" />
            <PostPreview 
                id="2"
                thumbnail= "http://www.organicexpo.co.nz/wp-content/uploads/2011/12/glm-march-2017-small.jpg"
                title="Hello there!"
                previewText="This is my first post" />
            <PostPreview 
                id="3"
                thumbnail= "http://www.organicexpo.co.nz/wp-content/uploads/2011/12/glm-march-2017-small.jpg"
                title="Hello there!"
                previewText="This is my first post" />
            <PostPreview 
                id="4"
                thumbnail= "http://www.organicexpo.co.nz/wp-content/uploads/2011/12/glm-march-2017-small.jpg"
                title="Hello there!"
                previewText="This is my first post" />
        </section>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
    components: {
        PostPreview
    }
}
</script>


<style scoped>
    .post-list {
        display: flex;
        padding: 20px;
        box-sizing: border-box;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
    }
</style>

