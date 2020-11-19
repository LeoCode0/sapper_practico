<script context="module">
  export function preload() {
    return this.fetch(`blog.json`)
      .then(r => r.json())
      .then(posts => {
        return { posts };
      });
  }
</script>

<script>
  import Post from "../components/Post.svelte";
  export let posts;
</script>

<style>
  .Posts {
    display: grid;
    justify-content: space-between;
    grid-gap: 15px;
    grid-template-columns: 1fr;
  }
</style>

<svelte:head>
  <title>LeoCode0</title>
  <meta name="description" content="Blog de LeoCode0" />
  
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:site" content="@LeoCode0" />
  <meta name="twitter:creator" content="@LeoCode0" />
  <meta name="twitter:title" content="LeoCode0 Blog" />
  <meta name="twitter:description" content="Blog de LeoCode0"/>
  <meta name="twitter:image" content="https://arepa.s3.amazonaws.com/blogpost-cover.png" />

  <meta name="og:title" content="LeoCode0" >
  <meta name="og:description" content="Blog de LeoCode0" >
  <meta name="og:image" content="https://arepa.s3.amazonaws.com/blogpost-cover.png" />
  <meta name="og:url" content="/" />
  <meta name="og:site_name" content="LeoCode0" />
  <meta name="og:locale" content="es_ES" />
  <meta name="og:type" content="article" />
  <meta name="fb:app_id" content="" />
</svelte:head>

<div class="Home">
  <div class="Posts">
    {#each posts as post}
      <Post {post} />
    {/each}
  </div>
</div>
