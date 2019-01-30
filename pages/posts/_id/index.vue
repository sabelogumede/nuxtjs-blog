<template>
    <div class="single-post-page">
        <section class="post">
            <h1 class="post-title">Title of the Post</h1>
            <div class="post-details">
                <div class="post-detail">Last updated on XXX</div>
                <div class="post-detail">Written by NAME</div>
            </div>
                <p class="post-content">Content of the post: Donec aliquam mollis diam, at pulvinar elit tempus vel. Aenean blandit purus orci, in molestie urna bibendum non. Morbi finibus, ipsum a imperdiet consequat, felis nisi placerat augue, at aliquet metus nunc at dolor. Morbi tincidunt nec velit id efficitur. In mattis malesuada magna, at viverra risus auctor ac. Nam a diam scelerisque, porttitor odio vitae, semper ex. </p>
        </section>
        <section class="post-feedback">
            <p>Let me know what you think about the post, send a mail to <a href="mailto:feedback@my+awesome-domain.com">feedback@my+awesome-domain.com</a>.</p>
        </section>

    </div>
</template>

<style scoped>
    .single-post-page {
        padding: 30px;
        text-align: center;
        box-sizing: border-box;
    }

    .post {
        width: 100%;
    }

    @media (min-width: 768px) {
        .post {
            width: 100%;
        }
    }

    @media (min-width: 768px) {
        .post {
            width: 600px;
            margin: auto;
        }
    }

    .post-title {
        margin: 0;
    }

    .post-details {
        padding: 10px;
        box-sizing: border-box;
        border-bottom: 3px solid #ccc;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
    
    /*  */
    @media (min-width: 768px) {
        .post-details {
        flex-direction: row;
        }
    }


    .post-detail {
        color: rgb(88, 88, 88);
        margin: 0 10px;
    }

    .post-feedback a {
        color: red;
        text-decoration: none;
    }

    .post-feedback a:hover,
    .post-feedback a:active {
        color: salmon;
    }

</style>
