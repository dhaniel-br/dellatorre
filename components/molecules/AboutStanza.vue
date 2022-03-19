<template>
  <div class="about-stanza">
    <Title text="CONHEÇA A DELLATORRE" />
    <p class="">
      É uma empresa estabelecida há 11 anos no mercado, conhecida por
      proporcionar maior praticidade e conveniência para quem necessita de uma
      máquina pesada. Na Dellatorre você pode ter acesso a nossas maquinas por
      meio de três maneiras: Alugando, participando de um dos nossos consórcios
      ou comprando.
    </p>
  </div>
</template>

<style lang="scss" scoped>
.about-stanza {
  display: flex;
  flex-direction: column;
  align-items: flex-start;

  gap: 16px;

  max-width: 100%;
  height: 100%;
  font-size: 16px;
  color: color(neutral, 'light');

  p {
    text-align: justify;
  }
}
</style>
