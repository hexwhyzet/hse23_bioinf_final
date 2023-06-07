# HSE23 Bioinf Final Project

KMT2C является одним из наиболее часто мутирующих генов при ER-положительном раке молочной железы (когда ER рецепторы на
клетке получают через Прогестерон сигнал о размножении)

Отключение KMT2C влияет на уменьшение H3K27ac в энхансерах ER-рецепторов и следовательно мешает развитию рака молочной
железы [1]

Больше всего экспрессируется в щитовидной железе, яичниках и костном мозге

Состоит из доменов PHD, HMG, FYRN-FYRC, SET, POST

[1] Gala K, Li Q, Sinha A, Razavi P, Dorso M, Sanchez-Vega F, Chung YR, Hendrickson R, Hsieh JJ, Berger M, Schultz N,
Pastore A, Abdel-Wahab O, Chandarlapaty S. KMT2C mediates the estrogen dependence of breast cancer through regulation of
ERα enhancer function. Oncogene. 2018 Aug;37(34):4692-4710. doi: 10.1038/s41388-018-0273-5. Epub 2018 May 14. PMID:
29755131; PMCID: PMC6107480.

Таблички с E-value:
![table2.png](images%2Ftable2.png)
Таблички с -log(Evalue):
![table.png](images%2Ftable.png)
Тепловая карта созданная по табличке -log(E-value), 300 - потолок:
![hitmap.png](images%2Fhitmap.png)

Видим что во всех многоклеточных >100, но странно что в черве не 300, так как drosophila и c.elegans отделились вместе от остальных многоклеточных.

Ищем белок гомолог, мышь нам подходит так как E-value < 1e10
![homologue2.png](images%2Fhomologue2.png)

![homologue.png](images%2Fhomologue.png)
Это KMT2D, по названию видно что это паралог, а значит гомолог