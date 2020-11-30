<template>
  <div id="contacts" class="main-fragment">
    <div class="container">
      <h1 class="main-header">
        Контакты
      </h1>

      <div class="contacts-list">
        <a href="https://vk.com/learn_itnow" target="_blank">
          <img
            class="contacts-list-img contacts-list-img--vk"
            src="~/assets/img/img23.svg"
          />
        </a>
        <a href="https://t.me/Sergey_Stepanow" target="_blank">
          <img
            class="contacts-list-img contacts-list-img--tg"
            src="~/assets/img/img24.svg"
          />
        </a>
        <a href="skype:Sergius_don?chat" target="_blank">
          <img class="contacts-list-img" src="~/assets/img/img25.svg" />
        </a>
        <a href="https://wa.me/380990484863" target="_blank">
          <img class="contacts-list-img" src="~/assets/img/img26.svg" />
        </a>
      </div>
    </div>
  </div>
</template>

<style scss>
.contacts-list {
  display: inline-flex;
  align-items: center;
}
.contacts-list-img {
  height: 40px;
  object-fit: contain;
  margin-right: 30px;
}
.contacts-list-img--vk {
  height: 48px;
}
.contacts-list-img--tg {
  height: 34px;
}
</style>
