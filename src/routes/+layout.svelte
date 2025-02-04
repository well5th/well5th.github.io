<script>
  let { children } = $props();
</script>

<nav class="navbar navbar-expand-sm bg-body-tertiary">
  <div class="container-fluid">
      <a class="navbar-brand" href="/#">
        
          
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
       <div class="layout">

          <ul class="navbar-nav">
              
              
                  <a class="nav-link" href="/sobre">Sobre min/</a>
              
             
              
              
                  <a class="nav-link" href="/jogadorfav">jogador fav/</a>
              
             
              
              
                  <a class="nav-link" href="/momentos">recordaç2ões</a>
              
              
          </ul>
       </div>
      </div>
  </div>
</nav>

{@render children()}

<body>
   
    <style>


.layout {
        
        background-color: #b8b7ae; 
        padding: 10px;
    border-radius: 10px;
    min-height: 5vh;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    color: #12520c ;
        width:600px;
        display: flex;
            justify-content: center;
            font-size:20px;
                    
    }
    

  
  </style>
  </body>
