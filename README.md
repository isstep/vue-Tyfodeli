# <img src="/public/logo.svg" alt="Logo" width="30"/> [CosmoExpress](https://vue-cosmo-express.vercel.app)

**CosmoExpress** — это интернет-магазин доставки еды, представляющий собой современное веб-приложение для удобного просмотра, сортировки и управления продуктами питания. Пользователи могут легко находить товары, добавлять их в избранное, а также управлять корзиной для оформления заказов. Проект построен на базе **Vue.js** и использует современные веб-технологии для обеспечения высокой производительности и надежности.


## 🚀 Технологии

- **Vue.js**: Основной фреймворк для разработки пользовательского интерфейса.
- **Tailwind CSS**: Утилитарный CSS-фреймворк для стилизации интерфейса.
- **Axios**: Библиотека для выполнения HTTP-запросов.
- **Vite**: Быстрый инструмент для разработки с поддержкой нативных ES-модулей.
- **Vue3 Carousel**: Компонент для создания карусели в Vue 3.
- **autoAnimatePlugin**: Библиотека для автоматических анимаций.
- **Vue Router**: Официальный маршрутизатор для Vue.js, упрощающий навигацию между компонентами и страницами.
- **Loldash**: Библиотека для реализации поиска, используется функция debounce, чтобы минимизировать нагрузку на сервер и избежать отправки большого количества запросов при каждом вводе символа.

## 🛠️ Основные компоненты

- **HeaderMain**: Компонент для отображения основного заголовка и навигации.
- **CardList**: Компонент для отображения списка продуктов с возможностью сортировки.
- **DrawerComponent**: (Закомментирован) Боковая панель для дополнительной навигации или фильтров.
- **Carouse**: Карусель для промо-контента или избранных продуктов.
- **CardComponent**: Карточка товара с изображением, названием, ценой и кнопками "Избранное" и "Добавить".
- **CartItem**: Компонент для отображения товара в корзине с возможностью его удаления.
- **CardItemList**: Список товаров в корзине с возможностью удаления каждого товара.
- **InfoCardComponent**: Карточка информации с изображением, заголовком и описанием.
- **HomePage**: Главная страница товаров.
- **FavoritePage**: Страница избранных товаров.


## 🌟 Функциональность

- **Поиск и сортировка**: Ищите продукты по названию и сортируйте их по цене или названию.
- **Избранное**: Добавляйте продукты в избранное.
- **Автоматическое обновление**: Обновление данных продуктов и избранного при изменении фильтров.
- **Корзина и заказ**: Добавляйте продукты в корзину и отправляйте заказ.

## 💻 Рекомендуемая настройка IDE

- [VSCode](https://code.visualstudio.com/) с [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (и отключением Vetur).

## 🔧 Настройка конфигурации

См. [Vite Configuration Reference](https://vitejs.dev/config/).

## 🚧 Установка проекта

```sh
npm install
