<template>
  <div class="promo-wrapper container">
    <div class="promo">
      <h1 class="title">
        Английский как конструктор
      </h1>
      <div class="subtitle">
        Инженерный подход к изучению языка
      </div>
      <div class="info">
        Освежи школьные знания и заговори по-английски легко.
      </div>
      <button class="btn">
        УЗНАТЬ ПОДРОБНЕЕ
      </button>
      <img class="img" src="~/assets/img/img.svg" />
    </div>
  </div>
</template>

<style scoped>
.promo {
  height: 60vh;
  position: relative;
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  width: 100%;
}

.promo-wrapper {
  margin-bottom: 50px;
}

.title {
  margin: 0 0 20px 0;
}

.subtitle {
  font-size: 32px;
  font-weight: 300;
  margin-bottom: 20px;
  color: var(--primary-color);
}

.info {
  color: rgba(0, 0, 0, 0.6);
  margin-bottom: 60px;
}

.img {
  position: absolute;
  bottom: 0;
  right: 0;
  width: 600px;
  height: auto;
}
</style>
