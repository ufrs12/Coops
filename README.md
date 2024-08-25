# Классификация кооперативов
Open Logical Tools Architecture  

В данный момент в этом разделе разрабатываются и строятся инструменты, приспособления и станки для изготовления печатных плат, запайки элементной базы, сборки и корпусирования электронных изделий.  

## Варианты и этапы создания печатных плат
```mermaid
graph LR;
classDef class1 fill:#544457, stroke:#000, stroke-width:4px
classDef class2 fill:#32465e, stroke:#000, stroke-width:4px
classDef class3 fill:#455744, stroke:#000, stroke-width:4px
classDef class4 fill:#5e4832, stroke:#000, stroke-width:4px
classDef class5 fill:#5e3332, stroke:#000, stroke-width:4px

   
    A([Кооперативы])
    B([Производственные]):::class1
    C([Потребительские]):::class4
    D([Производственный]):::class1
    E([Сельскохозяйственный
      производственный]):::class1
    F([Сверхтехнологичный для меня,
      даже не рассматриваю
      на обозримое будущее.]):::class1

    A-->|Коммерческие| B;
    A-->|Некоммерческие|C;
    B-->D;
    B-->E;
    C-->F;
   click B "https://www.zakonrf.info/gk/106.1/";
   click C "https://www.zakonrf.info/gk/123.2/";
   click D "https://www.zakonrf.info/doc-15088991/";
   click E "https://www.zakonrf.info/doc-13529718/";
```
