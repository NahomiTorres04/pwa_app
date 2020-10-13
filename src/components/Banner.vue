<template>
   <div id="banner" class="text-center">
      <div class="container">
        <div class="row">
          <div class="twelve columns bann">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Perspiciatis consequatur unde omnis rerum, architecto ad sint
              adipisci corporis nobis aperiam? Maiores nulla, nisi animi
              mollitia consectetur iure repellat dolorum assumenda natus quis
              aut ad facere voluptatibus id atque corrupti placeat, ipsa
              sapiente, optio velit ut. Illo odio sint ab eum? Lorem ipsum dolor
              sit amet, consectetur adipisicing elit. Sapiente saepe enim quidem
              molestias adipisci perferendis architecto nobis ullam similique
              eius. Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Cupiditate, illo!
              <br />
              <br />
              <button>Leer más</button>
            </p>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'Banner'
}
</script>

<style scoped>
    #banner{
        height: auto;
        background-image: url(../assets/img/fheader.jpg);
        background-position: center;
        background-size: cover;
        background-repeat: repeat;
        background-attachment: fixed;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    #banner .container {
        margin: 80px 0;
        height: auto;
        background-color: var(--gradientbanner);
        backdrop-filter: blur(6px);
    }
    #banner .container .row{
        height: auto;
    }
    #banner .container .row .bann{
        height: auto;
    }
    #banner .container .row .bann p{
        margin: 20px;
          padding: 35px;
          border: solid 1px var(--fontc);
          font-family: var(--fontcontent);
          font-size: 13px;
    }
</style>