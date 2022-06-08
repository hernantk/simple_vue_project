<script setup>

</script>

<template>

  <div style="height: 100vh; display: flex;">
    <div style="width: 60%; height: 100%;  ">
      <header class="border_item" style="display: flex; align-items: center; gap: 4vw; padding: 2vw;">
        <img src='./assets/logo.png' style="height: 50px; width: 250px; object-fit: cover; " />
        <span style="height: 60px; border-style: solid; border-width: 1px; "></span>
        <div style="display: flex; gap: 15vw;">
          <text class='text_item'>Ferramenta de Apredizagem de Calculo</text>
          <text class='text_item'>07/06/2022</text>
        </div>
      </header>
      <article style="display: flex; flex-direction: column; padding-left: 4vw; padding-right: 4vw; padding-top: 1vw;">
        <img src='./assets/banner.jpg'
          style="height: 250px; word-wrap: normal; border-radius: 10px; object-fit: cover; " />
        <div style="display: flex; flex-direction: column; gap: 1vw; padding-left: 1vw; padding-right: 1vw; padding-top: 1vw;">
          <text class='title'>Para ser muito bom amanha é preciso começar a práticar hoje</text>
          <div class="border_item" style="display: flex; gap: 2vw;padding-bottom: 1vw;">
            <text class='text_item'> Prof. Cleiton</text>
            <span> * </span>
            <text class='text_item'> 07 Jun 22</text>
            <span> * </span>
            <text class='text_item'> 16:40</text>
          </div>
          <div style="height: 100%; display: flex; flex-direction: column; row-gap: 2vw;">
            <div style="height: 50%;  width: 100%; color:var(--text-color) ">
              <text>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
                dolore magna aliqua. Nunc sed id semper risus. Consectetur adipiscing elit duis tristique sollicitudin
                nibh sit. Purus viverra accumsan in nisl nisi scelerisque. Pellentesque nec nam aliquam sem et tortor.
                Amet aliquam id diam maecenas. Id volutpat lacus laoreet non curabitur gravida arcu ac. Vestibulum
                rhoncus
                est pellentesque elit ullamcorper dignissim cras. Fringilla phasellus faucibus scelerisque eleifend
                donec
                pretium. Tincidunt augue interdum velit euismod in.
              </text>
            </div>
            <div style="height: 50%; width: 100%; color:var(--text-color) ">
              <text>
                Risus quis varius quam quisque id. Tellus elementum sagittis vitae et leo duis. Consectetur adipiscing
                elit duis tristique. Non enim praesent elementum facilisis. Non curabitur gravida arcu ac tortor
                dignissim
                convallis aenean et. Nibh venenatis cras sed felis eget. Posuere lorem ipsum dolor sit amet. Ornare
                suspendisse sed nisi lacus sed. Praesent semper feugiat nibh sed pulvinar proin gravida hendrerit
                lectus.
                Faucibus a pellentesque sit amet. Fringilla est ullamcorper eget nulla facilisi etiam dignissim. Sed
                euismod nisi porta lorem mollis aliquam. Quis viverra nibh cras pulvinar mattis nunc sed blandit.
              </text>
            </div>
          </div>
        </div>

      </article>
    </div>
    <div
      style="display: flex; flex-direction: column;width: 40%; height: 100%; background-color: var(--backgrond-calcule); ">

      <div class='border_item' style="display: flex; flex-direction: column; gap: 4vw; height: 30%;padding: 2vw;">
        <div style="display: flex; align-items: center; justify-content: center; gap:0.8vw;">
          <text class="title" style="color: white;"> Voce tem </text>
          <text id='id_ponto' style="color: white;" class="title"> 0 </text>
          <text class="title" style="color: white;"> pontos </text>
        </div>

        <button type="button" style="width: 60%; align-self: center; 
          height: 35%; background-color: var(--button-new); 
          color: white; border-color: white; border-radius: 15px; font-size: 1.4em; font-weight: bold;">
          Novo Desafio
        </button>
      </div>
      <div style="display:flex; flex-direction:column;justify-content: center;height: 30%; row-gap: 3vw;">
        <text style="font-size: 1.5em; color:white;  padding-left: 5vw;">Quanto é :</text>
        <div style="display: flex;  gap: 3vw; justify-content: center;  ">
          <div class="center_item tag_item">5</div>
          <div class="center_item tag_item">+</div>
          <div class="center_item tag_item">5</div>
        </div>
      </div>
      <div style="display:flex; flex-direction:column;height: 25%; row-gap: 3vw;">
        <text style="font-size: 1.5em; color:white; padding-left: 5vw; ">
          Sua Resposta :
        </text>
        <div style="display: flex;  gap: 3vw; justify-content: center;  ">
          <div class="center_item tag_item" style="width: 30%;">10</div>
        </div>
      </div>
      <button type="button" style="
          width: 60%; align-self: center; 
          height: 7.5%; background-color: var(--button-valid); 
          color: white; border-style: none; border-radius: 15px; font-size: 1.4em; font-weight: bold;">
        Validar
      </button>
    </div>

  </div>
</template>

<style>
@import './assets/base.css';

.tag_item {
  background-color: #a485ec;
  height: 60px;
  width: 60px;
  color: white;
  border-radius: 15px;
  font-weight: bold;
  font-size: 1.3em;
}

.center_item {
  display: flex;
  align-items: center;
  justify-content: center;
}

.title {
  font-size: 2.5em;
  font-weight: bold;
  color: var(--text-color);
}

.text_item {
  font-weight: 600;
  color: var(--text-color-header);
  width: max-content;
}

.border_item {
  border-color: #cacaca;
  border-style: solid;
  border-width: 0;
  border-bottom-width: 1px;
}
</style>
