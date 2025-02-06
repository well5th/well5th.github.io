<script>
    let { img, title, type, text } = $props();
  </script>
  
<div class="kaue">
    <div class="letra">

  
  <div class="card h-100" style="width: 18rem;">
    <img src={img} class="card-img-top" alt="invisibility" width="200px" />
    <div class="card-body">
      <h1 class="card-title">{title}</h1>
      <h6 class="card-subtitle mb-2 text-body-secondary">{type}</h6>
      <p class="card-text">{text}</p>
    </div>
  </div></div>
</div>


<body>
  <style>
    

      .kaue {
        background-color: #d4d3cb;
           padding: 50px;
           border-radius: 80px;
           min-height: 0vh;
           color: #000000 ;
           width: 300px;
           font-size:300px:
       }
       .letra {
       
           color: #000000 ;
           font-size:200px:
       }



   </style>
</body>