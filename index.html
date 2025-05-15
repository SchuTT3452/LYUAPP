// Список товаров
var PRODUCTS = [
  "Абрикос солод", "Алоэ полынь", "Ананас лемонграсс", "Апельсин ваниль", "Бамбук юдзу",
  "Берёзовый эль липа и мята", "Вишня шисо", "Ежевика гранат", "Жасмин бузина", "Имбирь вербена",
  "Инжирный лист чабрец", "Кактус ренет", "Кислый", "Клюква левзея", "Ладан кокос", "Малина пан",
  "Манго маракуйя", "Мате виноград", "Облепиха Личи", "Пало Санто банан", "Персик молочный улун",
  "Помело ромашка", "Слива рислинг", "Смородина вереск", "Миндаль шафран", "Фейхоа иланг иланг",
  "Фуджи сакура", "Черёмуха личи кардамон", "Черника лаванда", "Яблоко Саган дайля"
];

// Главная функция — HTML страница
function doGet() {
  return HtmlService.createHtmlOutputFromFile('index')
    .setTitle('Заказ товаров');
}

// Получить список товаров
function getProducts() {
  return PRODUCTS;
}

// Проверка логина и пароля
function checkLogin(login, password) {
  var sheet = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('Пользователи');
  var data = sheet.getDataRange().getValues();
  for (var i = 1; i < data.length; i++) {
    if (data[i][0] == login && data[i][1] == password) {
      return {success: true, name: data[i][2], company: data[i][3]};
    }
  }
  return {success: false};
}

// Сохранить заявку
function saveOrder(login, name, company, cart) {
  var sheet = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('Заявки');
  var now = new Date();
  for (var i = 0; i < cart.length; i++) {
    sheet.appendRow([now, login, name, company, cart[i].product, cart[i].quantity]);
  }
  return true;
}
