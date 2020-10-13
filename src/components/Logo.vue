<template>
  <div id="Logo" class="text-center">
      <div class="container">
        <div class="row">
          <div class="twelve columns item">
            <h1>Hotel Confortable</h1>
            <p>Lorem ipsum dolor sit amet.</p>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: "Logo"
}
</script>

<style scoped>
    #Logo {
        background-color: var(--bckglog);
        }
    .container .row .item {
        padding: 55px 0;
      }
    .container .row .item h1 {
          font-family: var(--fontt2);
          font-size: 45px;
          color: var(--fontc);
        }
    .container .row .item p {
          font-family: var(--fontcontent);
          font-size: 15px;
          color: var(--fontc);
        }
</style>