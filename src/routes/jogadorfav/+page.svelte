<script>
    import CartaMagic from '$lib/components/CartaMagic.svelte';
    import { cards } from '$lib/data.js';
  </script>
  
  <div class="row g-4">
    {#each cards as card}
      <div class="col">
        <CartaMagic {...card} />
      </div>
    {/each}
  </div>

  <body>
   
    <style>
     
     body {
            background-image: url('https://wallpapers.com/images/hd/ja-morant-1920-x-1080-background-gyt6mk4ujtxrdgfq.jpg'); 
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            height: 100vh;
        }

       .batata2 {
            background-color: rgba(9, 1, 1, 0.5);
            padding: 50px;
            border-radius: 30px;
            min-height: 0vh;
            color: #000000 ;
            width: 200px;
            

        }
        .time {
            background-color: rgba(9, 1, 1, 0.5);
            padding: 50px;
            border-radius: 30px;
            min-height: 0vh;
            color: #000000 ;
            width: 200px;
            

        }



        


       
    </style>
</body>


 