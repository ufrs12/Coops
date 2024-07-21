## Кредитные кооперативы
```mermaid
graph TD;
classDef class1 fill:#544457, stroke:#000, stroke-width:4px
classDef class2 fill:#32465e, stroke:#000, stroke-width:4px
classDef class3 fill:#455744, stroke:#000, stroke-width:4px
classDef class4 fill:#5e4832, stroke:#000, stroke-width:4px
classDef class5 fill:#5e3332, stroke:#000, stroke-width:4px

   
    A([Лига кредитных союзов])
    B([Ассоциация кредитных союзов "Гардарика"]):::class5
    C([Хотелось бы избежать.
      Мне не подходит.]):::class4
    D([Мой вариант]):::class3
    E([Более технологичный
      вариант, чем мой.  
      Возможно, к нему неплохо было бы
      стремиться в будущем.]):::class2
    F([Сверхтехнологичный для меня,
      даже не рассматриваю
      на обозримое будущее.]):::class1

    A-->B;
    A-->C;
    A-->D;
    A-->E;
    A-->F;

   click A "https://ligaks.ru/"
   click B "https://www.gardarikacu.ru/"
```
