<template>
  <div id="training" class="main-fragment">
    <div class="container">
      <h1 class="main-header">Как проходит обучение</h1>

      <div class="training">
        <div class="training-item">
          <img class="training-item-img" src="~/assets/img/img12.svg" />
          <div class="training-item-text">
            <img class="training-item-check" src="~/assets/img/img15.svg" />
            <div class="training-item-check-text">
              16 модулей на обучающей платформе.
            </div>
          </div>
          <div class="training-item-text">
            <img class="training-item-check" src="~/assets/img/img15.svg" />
            <div class="training-item-check-text">
              Вы изучаете и тренируете грамматику, практикуете диалоги,
              проходите тесты.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.training {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
.training-item {
  background-color: rgba(0, 0, 0, 0.05);
  padding: 40px;
  text-align: center;
}
.training-item-img {
  margin-bottom: 32px;
}
.training-item-text {
  display: inline-flex;
  align-items: flex-start;
  margin-bottom: 20px;
}
.training-item-text:last-child {
  margin-bottom: 0;
}
.training-item-check {
  margin-right: 12px;
  margin-top: 2px;
  width: 16px;
  height: auto;
}
.training-item-check-text {
  text-align: left;
}
</style>
