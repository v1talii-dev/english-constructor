<template>
  <div>
    <div class="header">
      <div class="container">
        <div class="header-container">
          <div class="logo">
            LOGO
          </div>

          <div class="menu">
            <a class="menu-item" href="#about">О курсе</a>
            <a class="menu-item" href="#training">Обучение</a>
            <a class="menu-item" href="#recall">Отзывы</a>
            <a class="menu-item" href="#price">Прайс</a>
            <a class="menu-item" href="#faq">FAQ</a>
            <a class="menu-item" href="#contacts">Контакты</a>
          </div>
        </div>
      </div>
    </div>
    <Nuxt class="main" />
  </div>
</template>

<style>
html {
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  --primary-color: #43a047;
  --secondary-color: #00701a;
}

body {
  padding: 0;
  margin: 0;
}

h1 {
  color: var(--primary-color);
  text-transform: uppercase;
}

h1 {
  font-size: 44px;
  font-weight: 400;
}

.btn {
  background-color: var(--primary-color);
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  transition: all 230ms;
  font-weight: 500;
  font-size: 16px;
  line-height: 52px;
  padding: 0 18px;
  box-shadow: 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 2px 2px 0 rgba(0, 0, 0, 0.14),
    0 1px 5px 0 rgba(0, 0, 0, 0.12) !important;
}

.btn:hover {
  background-color: var(--secondary-color);
}

.container {
  width: 1366px;
  max-width: 100%;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
  box-sizing: border-box;
}

.header {
  padding: 24px 0;
  position: fixed;
  width: 100%;
  background-color: #fff;
  z-index: 1;
}
.header-container {
  display: inline-flex;
  align-items: center;
}

.logo {
  margin-right: 32px;
  font-size: 48px;
  color: var(--primary-color);
  line-height: 1;
}

.menu {
  display: inline-flex;
}
.menu-item {
  padding-right: 32px;
  color: #696969;
  text-transform: uppercase;
  text-decoration: none;
  font-size: 18px;
  font-weight: 400;
}
.menu-item:hover {
  color: var(--primary-color);
}

.main {
  padding-top: 96px;
}
.main-fragment {
  padding: 50px 0;
}
.main-fragment--grey {
  background-color: rgba(0, 0, 0, 0.05);
}
.main-header {
  margin-top: 0;
  margin-bottom: 50px;
  text-align: center;
}
</style>
