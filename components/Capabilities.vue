<template>
  <div class="main-fragment">
    <div class="container">
      <h1 class="main-header">Освоив базовый курс вы сможете</h1>
      <div class="possibility-list">
        <div class="possibility-list-item">
          <img class="possibility-list-item-img" src="~/assets/img/img16.svg" />
          <div class="possibility-list-item-text">
            Уверенно говорить, используя самую нужную грамматику
          </div>
        </div>
        <div class="possibility-list-item">
          <img class="possibility-list-item-img" src="~/assets/img/img17.svg" />
          <div class="possibility-list-item-text">
            Справиться с основными разговорными ситуациями по интерактивным
            диалогам
          </div>
        </div>
        <div class="possibility-list-item">
          <img class="possibility-list-item-img" src="~/assets/img/img18.svg" />
          <div class="possibility-list-item-text">
            Будете хорошо понимать на слух английскую речь
          </div>
        </div>
        <div class="possibility-list-item">
          <img class="possibility-list-item-img" src="~/assets/img/img19.svg" />
          <div class="possibility-list-item-text">
            Поставите хорошее произношение и научитесь хорошо читать
            транскрипцию
          </div>
        </div>
        <div class="possibility-list-item">
          <img class="possibility-list-item-img" src="~/assets/img/img20.svg" />
          <div class="possibility-list-item-text">
            Сможете легко выбирать нужные времена и конструкции
          </div>
        </div>
        <div class="possibility-list-item">
          <img class="possibility-list-item-img" src="~/assets/img/img21.svg" />
          <div class="possibility-list-item-text">
            Сможете применить наш метод для изучения других языков
          </div>
        </div>
      </div>
      <div class="possibility-footer">
        Вы освоите базовый курс из 10 модулей за 2- 4 месяца. Это зависит от
        вашего текущего уровня и интенсивности занятий.
      </div>
    </div>
  </div>
</template>

<style scoped>
.possibility-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 50px;
  row-gap: 50px;
}
.possibility-list-item {
  display: inline-flex;
  align-items: center;
}
.possibility-list-item-img {
  width: 70px;
  height: auto;
  margin-right: 20px;
}
.possibility-list-item-text {
  font-size: 18px;
}
.possibility-footer {
  ont-size: 18px;
  margin-top: 50px;
}

@media (max-width: 1024px) {
  .possibility-list {
    grid-template-columns: 1fr;
  }
}
</style>
