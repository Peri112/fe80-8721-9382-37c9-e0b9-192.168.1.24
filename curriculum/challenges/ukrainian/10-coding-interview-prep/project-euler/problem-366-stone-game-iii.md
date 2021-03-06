---
id: 5900f4da1000cf542c50ffed
title: 'Задача 366: Гра в камені III'
challengeType: 5
forumTopicId: 302027
dashedName: problem-366-stone-game-iii
---

# --description--

Два гравці, Антон та Бернхард, грають у наступну гру.

Є купка з $n$ каменів.

Перший гравець може взяти будь-яку додатню кількість каменів, але не всю купу.

Відтак кожен гравець може забрати щонайбільше вдвічі більше каменів, які його противник взяв у попередньому ході.

Гравець, який візьме останній камінь, стає переможцем.

Наприклад. $n = 5$

Якщо перший гравець бере більше одного каменя, наступний гравець зможе забрати все, що залишиться.

Якщо перший гравець бере один камінь, залишаючи чотири, і його опонент також візьме один, а отже в підсумку їх буде три.

Перший гравець не може забрати всі три, адже він може взяти не більше $2 \times 1 = 2$ каменів. Скажімо, він візьме один камінь — відповідно залишиться 2.

Інший гравець, взявши ті два, що залишилися, переможе.

Тому 5 — це програшна позиція для першого гравця.

Для першого гравця є більше одного можливого кроку для виграшної позиції.

Наприклад. якщо $n = 17$, перший гравець може взяти один або чотири камені.

Нехай $M(n)$ — максимальна кількість каменів, яку може забрати перший гравець для виграшної позиції за перший крок. тоді $M(n) = 0$ — для будь-якої іншої позиції.

$\sum M(n)$ для $n ≤ 100$ — 728.

Знайдіть $\sum M(n)$ for $n ≤ {10}^{18}$. Дайте відповідь за модулем ${10}^8$.

# --hints--

`stoneGameThree()` має повернути `88351299`.

```js
assert.strictEqual(stoneGameThree(), 88351299);
```

# --seed--

## --seed-contents--

```js
function stoneGameThree() {

  return true;
}

stoneGameThree();
```

# --solutions--

```js
// solution required
```
