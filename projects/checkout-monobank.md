# Оплата через monobank

**Приймання оплати, яке не губить гроші: підпис кожного вебхука, захист від дублікатів і звірка з банком.**

<p align="center">
  <img src="checkout-monobank/1.png" alt="Слайд 1" width="24%">
  <img src="checkout-monobank/2.png" alt="Слайд 2" width="24%">
  <img src="checkout-monobank/3.png" alt="Слайд 3" width="24%">
  <img src="checkout-monobank/4.png" alt="Слайд 4" width="24%">
</p>

## Що зроблено

- Кожен вебхук перевіряється підписом ECDSA
- Запізнілий чи повторний вебхук не ламає статус
- Доступ покупцю видається рівно один раз

**Стек:** TypeScript · Hono · SQLite

---

[← Усі проєкти](../README.md) · Потрібне схоже рішення — пишіть у [Telegram](https://t.me/garry_portman) або [Instagram](https://www.instagram.com/garry_portman/).
