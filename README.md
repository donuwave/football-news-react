# ⚽ Football News

Футбольный дашборд: турнирная таблица, прошедшие и ближайшие матчи, подробная страница матча со статистикой и составами, избранные клубы.

![Статус](https://img.shields.io/badge/статус-в_разработке-orange?style=flat)

**[🔗 Демо](https://football-news-one.vercel.app)**

> [!NOTE]
> **В планах:** выбор лиги на главной странице. Сейчас данные показываются по одной лиге.

https://user-images.githubusercontent.com/73935646/236626207-a685f9c2-cd03-492e-8b94-859d9e5d6d49.mp4

## Возможности

**Главная**
- Турнирная таблица лиги
- Прошедшие и ближайшие матчи с фильтром и слайдером
- Избранные клубы: добавление и удаление

**Страница матча**
- Счёт и информация о матче
- Стартовые составы обеих команд, расставленные на схеме поля
- Статистика матча: владение, удары, угловые и другие показатели со сравнительными шкалами
- Блок «Игрок матча»

## Стек

![React](https://img.shields.io/badge/React_18-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat&logo=react&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_6-CA4245?style=flat&logo=react-router&logoColor=white)
![styled-components](https://img.shields.io/badge/styled--components-DB7093?style=flat&logo=styled-components&logoColor=white)
![Swiper](https://img.shields.io/badge/Swiper-6332F6?style=flat&logo=swiper&logoColor=white)

- React 18 + TypeScript
- **Zustand**: отдельные сторы для стран, лиг, таблицы, матчей и фильтров
- React Router v6
- Axios
- styled-components, Swiper
- [APIfootball](https://apifootball.com)
- Деплой на Vercel

## Запуск

```bash
git clone https://github.com/donuwave/football-news-react.git
cd football-news-react
npm install
npm start
```

Нужен ключ [APIfootball](https://apifootball.com). Его можно получить бесплатно после регистрации.
