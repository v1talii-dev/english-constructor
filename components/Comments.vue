<template>
  <div id="recall" class="comments-wrapper main-fragment">
    <div class="container">
      <h1 class="main-header">
        Отзывы учеников
      </h1>
      <div class="comments-list">
        <div class="comments-list-item">
          <img
            class="comments-list-item-img"
            src="~/assets/img/comments/tatyana.jpg"
            alt="Татьяна"
          />
          <div class="comments-list-item-name">
            Татьяна
          </div>
          <div class="comments-list-item-text">
            «Вас можно посоветовать в качестве репетитора английского, как и
            детям так и взрослым. У Вас очень интересные и особенные методики
            изучения языка.»
          </div>
        </div>
        <div class="comments-list-item">
          <img
            class="comments-list-item-img"
            src="~/assets/img/comments/olga.jpg"
            alt="Татьяна"
          />
          <div class="comments-list-item-name">
            Ольга
          </div>
          <div class="comments-list-item-text">
            «Рекомендую вас как преподавателя для тех, кто не верит, что сможет
            разобраться в языке, кто считает, что очень сложная грамматика и не
            очень верит в себя.»
          </div>
        </div>
        <div class="comments-list-item">
          <img
            class="comments-list-item-img"
            src="~/assets/img/comments/oksana.jpg"
            alt="Татьяна"
          />
          <div class="comments-list-item-name">
            Оксана
          </div>
          <div class="comments-list-item-text">
            «Постоянно ищет новые способы обучения. Индивидуальный подход.
            Хорошо выявляет пробелы в знаниях и помогает их преодолеть.»
          </div>
        </div>
        <div class="comments-list-item">
          <img
            class="comments-list-item-img"
            src="~/assets/img/comments/anna.jpg"
            alt="Татьяна"
          />
          <div class="comments-list-item-name">
            Анна
          </div>
          <div class="comments-list-item-text">
            «Преподаватель, который может сделать процесс обучения доступным,
            занимательным, эффективным, мотивированным, и в конечном итоге
            обеспечить успех в овладении иностранным языком»
          </div>
        </div>
        <div class="comments-list-item">
          <img
            class="comments-list-item-img"
            src="~/assets/img/comments/yasha.jpg"
            alt="Татьяна"
          />
          <div class="comments-list-item-name">
            Яков
          </div>
          <div class="comments-list-item-text">
            «Отличный учитель, который может преподнести любую тему интересно»
          </div>
        </div>
        <div class="comments-list-item">
          <img
            class="comments-list-item-img"
            src="~/assets/img/comments/elena.jpg"
            alt="Татьяна"
          />
          <div class="comments-list-item-name">
            Елена
          </div>
          <div class="comments-list-item-text">
            «Я бы охотно порекомендовала вас и своим друзьям и любому, кто бы
            спросил, как хорошего преподавателя языков.»
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.comments-wrapper {
  background-color: rgba(0, 0, 0, 0.05);
}
.comments-list {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 50px;
  row-gap: 50px;
}
.comments-list-item {
  background-color: #fff;
  padding: 30px;
}
.comments-list-item-img {
  border-radius: 50%;
  object-fit: cover;
  width: 140px;
  height: 140px;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.comments-list-item-name {
  font-size: 22px;
  text-align: center;
  padding: 16px 0;
  font-weight: 500;
}
</style>
