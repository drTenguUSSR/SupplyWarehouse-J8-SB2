# java8-apps-testlab

## [249_SupplyWarehouse-SB2](249_SupplyWarehouse-SB2)

Java8 SpringBoot2+JPA(Hibernate)

system downgraded: Java 8, SpringBoot 2.7.18
added: log4j2 yaml support

сборка проекта в maven

## [24B-AspectJ-baseAnimalLib](24B-AspectJ-baseAnimalLib)

базовый (библиотечный) проект для отработки AspectJ
цель: проект компилируется в jar без знания об AspectJ
внешний проект использует 24B и как-то накладывает на него перехват вызовов 
внутри библиотеки, без вмешательства в её исходный код и перекомпиляции

сборщик - maven

## 24B-AspectJ-console

отработка aspectj-компиляции на консольком приложении
библиотеки - lombok,aspectj-maven-plugin
сборщик - maven

## [24C-AspectJ-via-gradle] (24C-AspectJ-via-gradle)

консольное приложение собираемое через gradle 6.8.2
проект на Java 8.
задача - отработка перехвата вызовов
24С-m1 - внутри проекта
24С-m2 - во внешнем коде (24B)