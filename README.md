# Database_Administration_for_DevOps_Engineers_HW_1
## VADIM TSVETKOV

«Типы и структура СУБД»

**Задание 1.**

- Документоориентированные базы - поддерживают json.
- Графовые базы - содержит Узлы хранения сущностей данных, а рёбра — для хранения взаимосвязей между сущностями, как аналог складов и дорог между ними.
- Иерархические базы - класическое дерево.
- Ключ-значение базы.
- Реляционные базы - набор таблиц: магазин, товары, покупатель.

**Задание 2.**

- CAP : AP -- PACELC : PA EL
- CAP : AP -- PACELC : PA EL
- CAP : CP -- PACELC : PC EC

**Задание 3.**

Нет, т.к. они противоречат друг другу: ACID - делает уклон на надежность и предсказуемость, а BASE - производительность в ущерб надежности и предсказуемости.

**Задание 4.**

Redis - работает в однопоточном режиме, отсутствие синтаксиса языка SQL, завивсит от объема оперативное памяти т.к. данные в момент работы хранятся в оперативной памяти.
