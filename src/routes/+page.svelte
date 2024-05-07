<script>
  import Header from '$lib/Header.svelte'
  import Card from '../lib/card.svelte'
</script>

<Header />

<main>
  <Card caption="$19.90 - Māwhero / Pink brick wall" src="/pink-brick.jpg" />
  <Card caption="$4.90 - Kōwhai / Yellow run down wall" src="/yellow-run-down.jpg" />
  <Card caption="$9.90 - Pereki / Unpainted brick wall" src="/unpainted-brick.jpg" />
  <Card caption="$14.90 - Waiti / White brick wall" src="/white-brick.jpg" />
  <Card caption="$4.90 - Mātoretore / Rough wall" src="/rough.jpg" />
  <Card caption="$4.90 - Parāone Pākarukaru / Tan run down wall" src="/tan-run-down.jpg" />
  <Card caption="$11.90 - Karaka / Orange plaster wall" src="/orange-plaster.jpg" />
  <Card caption="$4.90 - Kiwikiwi Pākarukaru / Grey run down wall" src="/grey-run-down.jpg" />
  <Card caption="$24.90 - Putiputi / Flower wall" src="/flowers.jpg" />
  <Card caption="$34.90 - Kōwaiwai / Art deco wall" src="/art-deco.jpg" />
</main>

<footer>
  <p>&copy; Emma Fitzgerald Craighead Diocesan School 2024</p>
</footer>

<style>
  @import url('https://fonts.googleapis.com/css2?family=M+PLUS+1+Code:wght@100..700&display=swap');
  main {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    font-family: 'M PLUS 1 Code', monospace;
  }

  p {
    font-family: 'M PLUS 1 Code', monospace;
    background-color: #768c9e;
  }

  @media screen and (max-width: 600px) {
    main {
      width: 600px;
      display: inline-block;
    }
  }
</style>
