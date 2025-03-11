# Домашнее задание 
$\text{Власов Иван Юрьевич, группа 3}$

Код выполненя находится в файле `./code.ipynb`, материалы в папке `results`

## Ответы на вопросы из задания

**Оценка чтений:**

1. Качество чтений: Высокое (Phred > 30), но небольшое снижение качества к концу чтений (нормально).
2. Дубликаты: ENCFF000AOG — низкие (5.53%), ENCFF000APV и ENCFF000APW — умеренные (27.12% и 13.25%).
3. GC-состав: ENCFF000AOG — 41%, ENCFF000APV — 47%, ENCFF000APW — 50% (слегка смещен).
4. Адаптеры: Не обнаружены.
5. Перепредставленные последовательности: Менее 1% во всех образцах.

Подрезания не требуется проводить, так что я пропускаю этот шаг

**Почему процент выравнивания низкий?**

- 81.36% прочтений не выровнялись — возможны проблемы с качеством данных
- 14.01% множественных выравниваний — могут указывать на повторяющиеся регионы в геноме или шум в данных.

**Пересечение пиков:**
Пересечение пиков между вашим набором данных и ENCODE невелико (67–81 пиков), что может быть связано с разными версиями генома, методами вызова пиков, критериями фильтрации или экспериментальными условиями.
