<template>
  <div class="cards">
    <div class="card">
      <div class="heading">
        <img src="https://i.imgur.com/qbylLwK.png" class="cover" />
        <CardTitle :text="'Pa Carregadeira CAT 930R 1990 (2. Un)'" />
      </div>
      <div class="buttons">
        <WhatsappButton :text="'Ver detalhes'" />
        <CallButton />
      </div>
    </div>

    <div class="card">
      <div class="heading">
        <img src="https://i.imgur.com/r4p20HE.png" class="cover" />
        <CardTitle :text="'Retroescavadeira CAT 416E 4x2 2003'" />
      </div>
      <div class="buttons">
        <WhatsappButton :text="'Ver detalhes'" />
        <CallButton />
      </div>
    </div>

    <div class="card">
      <div class="heading">
        <img src="https://i.imgur.com/1etKedG.png" class="cover" />
        <CardTitle :text="'Mini Carregadeira CAT 216B 2014'" />
      </div>
      <div class="buttons">
        <WhatsappButton :text="'Ver detalhes'" />
        <CallButton />
      </div>
    </div>

    <div class="card">
      <div class="heading">
        <img src="https://i.imgur.com/c2meAbs.jpg" class="cover" />
        <CardTitle :text="'Trator esteira Komatsu D30 1982'" />
      </div>
      <div class="buttons">
        <WhatsappButton :text="'Ver detalhes'" />
        <CallButton />
      </div>
    </div>

    <div class="card">
      <div class="heading">
        <img src="https://i.imgur.com/ZM1NTdu.jpg" class="cover" />
        <CardTitle :text="'Motoniveladora CAT 120B 1982'" />
      </div>
      <div class="buttons">
        <WhatsappButton :text="'Ver detalhes'" />
        <CallButton />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.cards {
  @include screen('infinity', 'large') {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    gap: 64px;
    overflow-x: scroll;
  }
  @include screen('medium') {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
  @include screen('small') {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    overflow-x: hidden;
  }
  .card {
    /* Auto layout */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 16px;

    width: 344px;
    height: 346px;

    /* Background/light */
    background: #22292e;
    box-shadow: 0px 24px 32px rgba(0, 0, 0, 0.08);
    border-radius: 4px;

    /* Inside auto layout */
    flex: none;
    order: 0;
    flex-grow: 0;
    margin-top: 24px;

    .cover {
      height: 168px;
      width: 312px;
      object-fit: cover;
      border-radius: 4px;
    }
    .heading {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    .buttons {
      display: flex;
      flex-direction: row;
      gap: 6px;
      margin-top: 64px;
    }
  }
}
</style>
