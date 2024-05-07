<script>
  export let caption
  export let src
  export let alt
</script>

<article>
  <img class="photo" {src} {alt} />
  <p class="caption">{caption}</p>
</article>

<style>
  .photo {
    width: 500px;
    height: 350px;
    padding: 20px;
    transition: 1s;
    display: flex;
    justify-content: center;
  }
  .photo:hover {
    background-color: rgb(179, 169, 185);
    transition: 1s;
  }

  .photo:hover + p {
    background-color: rgb(179, 169, 185);
    transition: 1s;
    width: 500px;
    margin: 0px;
  }

  p {
    width: 460px;
    text-align: center;
    padding: 5px;
    padding-top: 0px;
    padding-left: 20px;
    padding-right: 20px;
    margin-bottom: 30px;
    margin-left: 20px;

    transition: 1s;
    background-color: rgb(179, 169, 185, 0.5);
  }
</style>
