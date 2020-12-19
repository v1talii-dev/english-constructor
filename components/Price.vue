<template>
  <div class="price-wrapper main-fragment">
    <div class="container">
      <a id="price" class="main-header-link"></a>
      <h1 class="main-header">
        Прайс
      </h1>
      <div class="price-list">
        <div class="price-list-item">
          <div class="price-list-item-title">
            <div>
              ПАКЕТ
            </div>
            <div>
              «ОПТИМАЛЬНЫЙ»
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Проверка домашних заданий
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Доступ к чату школы
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Пошаговое обучение на платформе
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Поддержка на 6 месяцев в преподавательском чате
            </div>
          </div>
          <div class="price-list-item-coast">
            1590 ₽/мес
          </div>
          <div class="price-list-item-buy">
            <a
              class="btn"
              target="_blank"
              href="https://oplatakursov.ru/payment/niharhzmtxjt"
            >
              КУПИТЬ
            </a>
          </div>
        </div>
        <div class="price-list-item">
          <div class="price-list-item-title">
            <div>
              ПАКЕТ
            </div>
            <div>
              «Вместе со всеми»
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Проверка домашних заданий
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Доступ к чату школы
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Пошаговое обучение на платформе
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Поддержка на 6 месяцев с личным куратором
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              3 занятия в месяц
            </div>
          </div>
          <div class="price-list-item-coast">
            2490 ₽/мес
          </div>
          <div class="price-list-item-buy">
            <a
              class="btn"
              target="_blank"
              href="https://oplatakursov.ru/payment/lnwdfrlebqov"
            >
              КУПИТЬ
            </a>
          </div>
        </div>
        <div class="price-list-item">
          <div class="price-list-item-title">
            <div>
              ПАКЕТ
            </div>
            <div>
              «Дайте мне лучшее»
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Проверка домашних заданий
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Доступ к чату школы
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Пошаговое обучение на платформе
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              Поддержка на 1 год обучения с методистом школы
            </div>
          </div>
          <div class="price-list-item-text">
            <img class="price-list-item-check" src="~/assets/img/img22.svg" />
            <div class="price-list-item-check-text">
              8 занятий в месяц
            </div>
          </div>
          <div class="price-list-item-coast">
            5890 ₽/мес
          </div>
          <div class="price-list-item-buy">
            <a
              class="btn"
              target="_blank"
              href="https://oplatakursov.ru/payment/myftcvkvjeco"
            >
              КУПИТЬ
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.price-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 50px;
}
.price-list-item {
  background-color: #fff;
  padding: 30px;
  box-shadow: 0px 3px 1px -2px rgba(0, 0, 0, 0.2),
    0px 2px 2px 0px rgba(0, 0, 0, 0.14), 0px 1px 5px 0px rgba(0, 0, 0, 0.12);
  display: inline-flex;
  flex-direction: column;
  justify-content: space-between;
}
.price-list-item-title {
  text-align: center;
  color: var(--primary-color);
  font-size: 20px;
  font-weight: 500;
  padding-bottom: 30px;
  text-transform: uppercase;
}
.price-list-item-text {
  display: inline-flex;
  align-items: flex-start;
  margin-bottom: 20px;
}
.price-list-item-text:last-child {
  margin-bottom: 0;
}
.price-list-item-check {
  margin-right: 12px;
  margin-top: 2px;
  width: 16px;
  height: auto;
}
.price-list-item-check-text {
  text-align: left;
}
.price-list-item-coast {
  text-align: center;
  color: var(--primary-color);
  font-size: 32px;
  font-weight: 500;
  margin-top: 30px;
  margin-bottom: 30px;
  text-transform: uppercase;
}
.price-list-item-buy {
  text-align: center;
}

@media (max-width: 1024px) {
  .price-list {
    grid-template-columns: 1fr;
    row-gap: 20px;
  }
}
@media (max-width: 414px) {
  .price-list-item {
    padding: 20px;
  }
}
</style>
