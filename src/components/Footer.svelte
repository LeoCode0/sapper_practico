<style>
  .Footer{
      background: rgba(28, 41, 56, 0.8);
      color: #FFF;
      padding: 1.5em 0;
      margin: 2em 0 0 0;
      font-size: 13px;
      font-weight: 300;
  }

  .Footer-container{
      display: grid;
      grid-template-columns: minmax(auto, 1024px);
      justify-content: center;
      align-items: center;
  }

  .Footer-content{
      display: flex;
      justify-content: space-between;
      align-items: center;
  }

  .Footer-svelte{
      display: flex;
      align-items: center;
  }

  .Footer-svelte img{
      margin: 0 0 0 0.5em;
  }
</style>

<footer class="Footer">
  <div class="Footer-container">
    <div class="Footer-content">
      <div class="Footer-copy">
        Hecho con amor en Platzi
      </div>
      <div class="Footer-svelte">
        Proudly powered by svelte
        <img src="https://static.platzi.com/media/public/uploads/svelte_f8c83ae3-afb6-45b8-9ed4-179188bf97fd.png" alt="svelte">
      </div>
    </div>
  </div>
</footer>