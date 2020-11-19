<style>
  .Header{
    background-color: #fafbfc;
    color: #191a22;
    padding: 1em 0 0 0;
  }

  .Header-container{
      display: grid;
      grid-template-columns: minmax(auto, 1024px);
      justify-content: center;
      align-items: center;
  }

  .Header-content{
      display: flex;
      align-items: center;
      justify-content: space-around;
   }

   .Header h1{
       color: #191a22;
       font-size: 20px;
       font-weight: 700;
       letter-spacing: 0.8px;
       cursor: pointer;
   }

   .Header h1 span{
       display: block;
       font-size: 13px;
       font-weight: 300;
       letter-spacing: normal;
       margin: 0.3em 0 0 0;
   }

   .Header ul {
       margin: 0;
       padding: 0;
       list-style: none;
   }

   .Header li {
       display: inline-block;
       margin: 0 0.5em 0 0;
   }

   .Header a{
       text-decoration: none;
       font-weight: 300;
       font-size: 14px;
   }

   .Header-social img{
       width: 20px;
   }

</style>

<header class="Header">
   <div class="Header-container">
     <div class="Header-content">
       <div class="Header-logo">
         <h1>
         Leonardo Espinoza
           <span>Frontend developer</span>
         </h1>
       </div>
       <div class="Header-social">
         <ul>
           <li>
             <a href="/github" target="_blank" rel="noreferrer">
               <img src="https://static.platzi.com/media/public/uploads/github-icon_4245c4fc-13bb-4b20-8f43-07ff0cb96be5.png" alt="Github">
             </a>
           </li>
           <li>
             <a href="/instagram" target="_blank" rel="noreferrer">
               <img src="https://static.platzi.com/media/public/uploads/instagram-icon_0b939c93-a0eb-4c28-a966-5b6f9ea359ad.png" alt="instagram">
             </a>
           </li>
           <li>
             <a href="/facebook" target="_blank" rel="noreferrer">
               <img src="https://static.platzi.com/media/public/uploads/facebook-icon_53a08160-0197-4ade-a94b-9259474030a2.png" alt="facebook">
             </a>
           </li>
         </ul>
       </div>
     </div>
   </div>
</header>