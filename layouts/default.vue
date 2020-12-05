<template>
  <div>
    <div class="header">
      <div class="container">
        <div class="header-container">
          <a href="#promo">
            <img class="logo" src="~/assets/logo.png" />
          </a>

          <div class="menu" :class="menuActive ? ['menu--active'] : []">
            <a class="menu-item" @click="menuToggle()" href="#about">О курсе</a>
            <a class="menu-item" @click="menuToggle()" href="#training">
              Обучение
            </a>
            <a class="menu-item" @click="menuToggle()" href="#recall">Отзывы</a>
            <a class="menu-item" @click="menuToggle()" href="#price">Прайс</a>
            <a class="menu-item" @click="menuToggle()" href="#faq">FAQ</a>
            <a class="menu-item" @click="menuToggle()" href="#contacts">
              Контакты
            </a>
          </div>

          <button class="menu-btn" type="button" @click="menuToggle()">
            <img
              v-show="!menuActive"
              class="menu-icon"
              src="~/assets/img/menu.svg"
            />
            <img
              v-show="menuActive"
              class="menu-icon"
              src="~/assets/img/cancel.svg"
            />
          </button>
        </div>
      </div>
    </div>
    <Nuxt class="main" />
  </div>
</template>

<script>
export default {
  data: () => {
    return {
      menuActive: false
    };
  },

  methods: {
    menuToggle() {
      this.menuActive = !this.menuActive;
    }
  }
};
</script>

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
  font-size: 38px;
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
  padding: 14px 20px;
  box-shadow: 0 3px 1px -2px rgba(0, 0, 0, 0.2), 0 2px 2px 0 rgba(0, 0, 0, 0.14),
    0 1px 5px 0 rgba(0, 0, 0, 0.12) !important;
  display: inline-block;
  text-decoration: none;
}

.btn:hover {
  background-color: var(--secondary-color);
}

.container {
  width: 1180px;
  max-width: 100%;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
  box-sizing: border-box;
}

.header {
  padding: 12px 0;
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
  margin-left: -8px;
  margin-right: 24px;
  width: 90px;
  height: auto;
}

.menu {
  display: inline-flex;
}
.menu-item {
  padding-right: 32px;
  color: #696969;
  text-transform: uppercase;
  text-decoration: none;
  font-size: 16px;
  font-weight: 400;
}
.menu-item:hover {
  color: var(--primary-color);
}

.main {
  padding-top: 96px;
}
.main-header {
  margin-top: 0;
  margin-bottom: 50px;
  text-align: center;
}
.main-header-link {
  display: block;
  position: relative;
  top: -150px;
  visibility: hidden;
}
.main-fragment {
  padding: 60px 0;
}
.main-fragment--grey {
  background-color: rgba(0, 0, 0, 0.05);
}
.main-fragment--primary {
  background-color: var(--primary-color);
  color: #fff;
}
.main-fragment--primary .main-header {
  color: #fff;
}
.menu-btn {
  display: none;
  border: none;
  padding: 0;
  background-color: transparent;
}

@media (max-width: 768px) {
  .header-container {
    width: 100%;
    justify-content: space-between;
  }
  .logo {
    width: 54px;
    margin-right: 0;
  }
  .menu {
    display: none;
  }
  .menu--active {
    display: block;
    position: fixed;
    width: 100%;
    background-color: #fff;
    top: 70px;
    left: 0;
    text-align: center;
    padding-bottom: 10px;
  }
  .menu--active a {
    display: block;
    padding: 8px 0;
  }
  .menu-btn {
    display: block;
  }
  .menu-btn:focus,
  .menu-btn:active {
    outline: none;
  }
  .menu-icon {
    width: 26px;
    height: auto;
    cursor: pointer;
    display: block;
  }

  .main {
    padding-top: 70px;
  }
  .main-header-link {
    top: -110px;
  }
  .main-fragment {
    padding: 40px 0;
  }
  .main-header {
    margin-bottom: 40px;
  }
}

@media (max-width: 768px) {
  h1 {
    font-size: 32px;
  }
}

@media (max-width: 414px) {
  h1 {
    font-size: 26px;
  }
}
</style>
