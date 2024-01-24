Оберни в теги хтмл, додай форматування але збережи весь оригінальний текст:
шрифіти: Montserrat,Arial,sans-serif
class="container"  - в боді
в файл CSS:
<style>
  /* Форматування для комп'ютерів */
  @media screen and (min-width: 768px) {
    .container {
      width: 80%;
    }
  }

  /* Форматування для мобільних телефонів */
  @media screen and (max-width: 767px) {
    .container {
      width: 100%;
    }
  }
</style>
