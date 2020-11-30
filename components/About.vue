<template>
  <div id="about" class="main-fragment main-fragment--primary">
    <div class="container">
      <h1 class="main-header">О курсе</h1>

      <div class="step">
        <div class="step-info">
          <div class="step-title">1 шаг</div>
          <div class="step-text">
            Вы узнаете основы изучения языка. Мы определим ваши задачи и
            поставим цели обучения.
          </div>
        </div>
        <img class="step-img" src="~/assets/img/img7.svg" />
      </div>
      <div class="step">
        <div class="step-info">
          <div class="step-title">2 шаг</div>
          <div class="step-text">
            Мы научимся изучать и отрабатывать грамматику. Вы сможете говорить
            без ошибок.
          </div>
        </div>
        <img class="step-img" src="~/assets/img/img8.svg" />
      </div>
      <div class="step">
        <div class="step-info">
          <div class="step-title">3 шаг</div>
          <div class="step-text">
            Вы освоите прочное запоминание слов. Теперь все слова надолго
            останутся в памяти.
          </div>
        </div>
        <img class="step-img" src="~/assets/img/img9.svg" />
      </div>
      <div class="step">
        <div class="step-info">
          <div class="step-title">4 шаг</div>
          <div class="step-text">
            Мы приступаем к практическому изучению языка. Вы быстро учитесь
            говорить, используя все изученные времена.
          </div>
        </div>
        <img class="step-img" src="~/assets/img/img10.svg" />
      </div>
      <div class="step">
        <div class="step-info">
          <div class="step-title">5 шаг</div>
          <div class="step-text">
            Мы используем интерактивные диалоги. Вы погружаетесь в разговорную
            ситуацию и начинаете говорить.
          </div>
        </div>
        <img class="step-img" src="~/assets/img/img11.svg" />
      </div>

      <div class="step-footer">
        Весь курс разбит на 5 шагов. Каждый шаг приближает вас к хорошему
        владению языком.
      </div>
    </div>
  </div>
</template>

<style scoped>
.step {
  display: inline-flex;
  width: 100%;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 40px;
}

.step-info {
  width: 70%;
}

.step-title {
  text-transform: uppercase;
  font-size: 28px;
  font-weight: 500;
  margin-bottom: 10px;
}

.step-img {
  width: 60px;
  height: auto;
}

.step-footer {
  color: rgba(255, 255, 255, 0.7);
}
</style>
