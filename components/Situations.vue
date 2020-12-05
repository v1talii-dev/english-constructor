<template>
  <div class="main-fragment">
    <div class="container">
      <h1 class="main-header">Вам знакомы такие ситуации?</h1>
      <div class="situation-list">
        <div class="situation-list-item">
          <img class="situation-list-item-img" src="~/assets/img/img1.svg" />
          <div class="situation-list-item-text">
            В школе не учат английскому должным образом
          </div>
        </div>
        <div class="situation-list-item">
          <img class="situation-list-item-img" src="~/assets/img/img2.svg" />
          <div class="situation-list-item-text">
            За рубежом некомфортно без хорошего английского
          </div>
        </div>
        <div class="situation-list-item">
          <img class="situation-list-item-img" src="~/assets/img/img3.svg" />
          <div class="situation-list-item-text">
            Нужен язык для карьеры, но не знаю, с чего начать
          </div>
        </div>
        <div class="situation-list-item">
          <img class="situation-list-item-img" src="~/assets/img/img4.svg" />
          <div class="situation-list-item-text">
            Плохо запоминаются английские слова
          </div>
        </div>
        <div class="situation-list-item">
          <img class="situation-list-item-img" src="~/assets/img/img5.svg" />
          <div class="situation-list-item-text">
            Не могу понять английскую речь
          </div>
        </div>
        <div class="situation-list-item">
          <img class="situation-list-item-img" src="~/assets/img/img6.svg" />
          <div class="situation-list-item-text">
            Трудно выбрать учителя или репетитора
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.situation-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 50px;
  row-gap: 50px;
}
.situation-list-item {
  display: inline-flex;
  align-items: center;
}
.situation-list-item-img {
  width: 70px;
  height: auto;
  margin-right: 20px;
}
.situation-list-item-text {
  font-size: 18px;
}

@media (max-width: 1024px) {
  .situation-list {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 414px) {
  .situation-list-item-text {
    font-size: 16px;
  }
}
</style>
