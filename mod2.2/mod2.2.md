Львівський національний університет природокористування

Факультет механіки, енергетики та інформаційних технологій

Кафедра інформаційних технологій

Звіт з лабораторної роботи №2.2

на тему: 
 # Структурні Шаблони


Виконав: студент групи ІТ-22сп Юрчишин Назар

Перевірив: Татомир А. В.

**Мета роботи:** 
Ознайомитися з структурними шаблонами та їх застосування на практиці.
 
 ## Завдання
1. Короткий теоретичний опис групи структурних шаблонів.
2. Опис вибраного шаблону.
3. Приклад коду.

 ## Хід роботи
1. Структурні шаблони — шаблони проєктування, у яких розглядається питання про те,
як із класів та об'єктів утворюються більші за розмірами структури. 
 
 Перелік структурних шаблонів:
  
           Адаптер (Adapter)
           Декоратор (Decorator)
           Замісник (Proxy)
           Компонувальник (Composite)
           Міст (Bridge)
           Легковаговик (Flyweight)
           Фасад (Facade)
 
2. Міст — це структурний патерн проектування, який розділяє один або кілька класів на дві окремі ієрархії — абстракцію та реалізацію, 
дозволяючи змінювати код в одній гілці класів, незалежно від іншої.

3. [Програма](https://github.com/Yurchyshyn0/OOP_Yurchyshyn/blob/847f6af1e1db3b4653f3d422c0460bae058e1f1f/mod2.2.py)

  Результат програми:
   
        Abstraction: Base operation with:
        ConcreteImplementationA: Here's the result on the platform A.

        ExtendedAbstraction: Extended operation with:
        ConcreteImplementationB: Here's the result on the platform B.
