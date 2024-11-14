<script>

</script>
<style>
   /* Stil for hele siden */
   :global(body) {
       background-color: #9c9d9d;
       display: flex;
       justify-content: center;
       align-items: center;
       height: 100vh;
       margin: 0;
       font-family: Arial, sans-serif;
   }
   
   /* Ytre boks (banneren) */
   .outer-box {
       width: 250%;
       height: 195px;
       border: 2px solid #004d40;
       display: flex;
       justify-content: center;
       align-items: center;
       background: rgb(65, 12, 81);
       box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
       position:relative;
       overflow: hidden;
   }

   /* Indre boks med gradient bakgrunn og rundere hjørner */
   .inner-box {
       width: 100%;
       height: 22%;
       overscroll-behavior-block: url ;
       background: linear-gradient(-60deg, #002171 50%, #0d47a1 50%);
       display: flex;
       gap: 1em;
       justify-content: center;
       justify-content: space-between;  
       align-items: center;
       padding: 30px;
       text-align: center;
       border-radius: 100px;
       position: relative;
   }

   .top-text {
       position: absolute; 
       top: 10px; 
       left: 50%; 
       transform: translateX(-50%); 
       font-size: 20px;
       color: white;
       font-weight: bold;
   }

   /* Stil for tekst inni den indre boksen */
    .inner-box h1 {
       font-size: 24px;
       margin: 0;
    }
    
    .text-wrapper{
        position: relative;
        text-align: center;
        flex: 1 1 50%;
        min-width: 120px;
        position: absolute;

   }
    
   
   .image {
       max-width: 100px;
       height: 90px;
       object-fit: cover;
       border-radius: 50px;
       margin-left:-22px;
    }
    
    
    .image_2 {
        position:absolute;
        right: 10px;
        margin-right:-2px;
    }

    /* Responsiv styling for mobilskjermer */
@media (max-width: 600px) {
   .outer-box {
       flex-direction: column;
       align-items: center;
       width: 90%; 
       padding: 10px;
   }
}     
     
    .inner-box p {
        flex-direction: column;
        font-size: 1.2em;
        margin-top: 10px;
    }

    @media (max-width: 480px) {
   .outer-box {
       padding: 10px;
   }
}      

    .number-95 {
        position: absolute;
        top: 50%;
        left: 320px;
        font-size: 45px !important;/* Økt skrifttørrelse*/
        font-weight: bold;
        color: white;
        margin: 0 12px;
        align-self: flex-End;
        transform:translate(-5%, -12%);
    }
    .grønn-text {
        position:absolute;
        top: 50%;  
        left: 250px;
        font-size: 45px !important;/* Økt skrifttørrelse*/
        font-weight: bold;
        color: #aaff72; 
        margin: 0 12px;
        transform: translatex(-50%);
        transform:translate(-50%, -10%);
    }
    
    .name_name_1{
        color: white; 
        font-weight: bold;
        font-size: 1,2em;
        position:absolute;
        transform: translateY(-20%);
        top: 45%;
        left: 65px;
        align-self: flex-end;
        white-space: nowrap;
    }
    .name_name_2{
        color: white; 
        font-weight: bold;
        font-size: 1,2em;
        position:absolute;
        transform: translateY(-20%);
        top: 45%;
        left: 490px;
        align-self: flex-End;
        white-space: nowrap;
    }   
    
</style>

   <div class="outer-box">  
      <div class="inner-box">
            <div class="top-text">
              Jakten på Bjørndalen 
            </div> 

           <img class="image" src="https://static.tv2.no/s/files/2024/11/12/boe-square.jpg" alt="venstre bilde">
           <img class="image image_2" src="https://static.tv2.no/s/files/2024/11/12/bjoerndalen.jpg" alt="høyre bilde">
        
             <section class="text-wrapper">
               <p class="name_name_1">Johannes<br>Thingsnes Bø</p>
               <p class="grønn-text">84</p>
               <p class="number-95">95</p>
               <p class="name_name_2">Ole Einar<br>Bjørndalen</p>
            </section>
      </div>
   </div>




