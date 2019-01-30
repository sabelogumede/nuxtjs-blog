<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news!</h1>
    </section>
    <section class="featured-posts">
      <!-- first post -->
      <nuxt-link :to="'/posts/' + 1" class="post-preview">
        <article>
          <div class="post-thumbnail" style="background-image: url('https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwj0vKeBp5XgAhWFsnEKHdeGDzwQjRx6BAgBEAU&url=http%3A%2F%2Fwww.edsgreenenergy.com%2F&psig=AOvVaw19YsCUXLsxukZIcS0P90Re&ust=1548930777758014')"></div>
          <div class="post-content">
            <h1>Post Title 1</h1>
            <p>Preview Text</p>
          </div>
        </article>
      </nuxt-link>
      <!-- second post -->
      <nuxt-link :to="'/posts/' + 2" class="post-preview">
        <article>
          <div class="post-thumbnail"></div>
          <div class="post-content">
            <h1>Post Title 2</h1>
            <p>Preview Text</p>
          </div>
        </article>
      </nuxt-link>
    </section>
  </div>
</template>


<style scoped>
.intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-size: cover; 
}
.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  padding: 10px;
  border-radius: 10px;
  box-sizing: border-box;
}

@media (min-width: 768px) {
  .intro h1 {
    font-size: 2rem;
  }
}


.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
.post-preview {
  border: 1px solid #ccc;
  box-shadow: 0 2px 2px #ccc;
  background-color: white;
  width: 90%;
}

a {
  text-decoration: none;
  color: black;
}

@media (min-width: 850px) {
  .post-preview {
    width: 400px;
    margin: 10px;
  }
}

.post-thumbnail {
  width: 100%;
  height: 200px;
  background-position: center;
  background-size: cover;
}

.post-content {
  padding: 10px;
  text-align: center;
}

a:hover .post-content,
a:active .post-content {
  background-color: #ccc;
}

</style>
