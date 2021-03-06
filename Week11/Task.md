## Task - Restaurant Cook

Към вас се обръща хотел Маринела. Искат да направите система, която да съхранява информация за различните видове ястия, които готвачите в хотела могат да предоставят.

Да се реализира йерархията от класове: **CookerBook** (книга с ястия/меню), **Starter** (начално ястие), **Dish** (ястие), **MainDish** (главно ястие), **Dessert** (десерт)

Класа **CookerBook** има полетата:

- автор
- издателство
- списък с ястия
- име

**Dish** съдържа:

- име
- описание
- мазнини (грама)
- въглехидрати (грама)
- белтъчини (грама)
- функция за изчисляване на калории

Класовете **Starter**, **MainDish**, **Dessert** наследяват класа **Dish** . За класовете трябва да се реализират голяма 4-ка(ако е нужно).

### Как се изчисляват калориите на едно ястие?

> (*мазнини* x 9) + (*въглехидрати* x 4) + (*белтъчини* x 4) = **общо калории**

Добър подход би бил да изкарате трите характеристики (мазнини, въглехидрати, белтъчини) в отделна структура.

```
struct NutritionalData {
    int protein;
    int carbohydrates;
    int fats;
};
```