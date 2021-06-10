<template lang="pug">
h1.title
  | В этом приложении:
ul
  li Полная настройка шаблона Vue CLI;
  li Установка и настройка Vue-router для Vue.js 3;
  li Динамическая перерисовка без перезагрузки страницы;
  li Динамическая навигация;
  li Обработка несуществующих маршрутов;
  li Хеши и моды для роутера;
  li Настройка общего конфига.
p
  | Сделано на курсе: 
  a(href="https://tocode.ru/courses/vuejs-3-s-nulya-do-rezultata/" target="_blank") 
    | Курс по Vue.js 3 с нуля до результата
</template>

<style lang="scss" scoped>
.title {
  margin-top: 20px;
  font-weight: 300;
}
ul,
li {
  margin-left: 14px;
  list-style-type: disc;
  font-size: 16px;
  color: #777;
}
p {
  margin-top: 20px;
  font-size: 14px;
  a {
    text-decoration: underline;
    color: rgb(37, 95, 172);
    transition: 0.3s all ease;
    &:hover {
      color: rgb(109, 147, 197);
      text-decoration: none;
    }
  }
}
li:not(:first-child) {
  padding-top: 10px;
}
</style>
