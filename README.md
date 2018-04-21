# MTCGeohack.112
Public solution for (MTC Geohack.112)[https://datasouls.com/c/mts-geohack/description]

**Задача**

Можно ли предсказать, где в городе потребуются экстренные службы (полиция/скорая/пожарная/...)? Мы предоставляем геоданные по Москве, в какой день сколько звонков поступало по номеру 112. В этой задаче критически важно пользоваться данными из открытых источников, такими как Open Street Map.


**Критерии качества**

Обучившись по западной половине Москвы, участники должны предсказать вызовы экстренных служб для восточной половины. Метрика качества предсказаний — коэффициент ранговой корреляции Кендалла (Kendall's tau). Метрика обращает внимание не на точные значения предсказываемого числа звонков, а на их порядок.

