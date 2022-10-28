Intro to Podman
===============
2 days, 8 ac.hrs, 7 as.hrs.

Prerequisites
=============
- [ ] RAM ≥ 4Gb
- [ ] Доступен git repo с данным руководством {{ git-repo }} `https://github.com/eugene-krivosheyev/podman`
- [ ] Доступен {{ registry-host }}
- [ ] Доступ учетной записи {{ registry-account }} на {{ registry-host }}

---

Intro to containerization and Podman <sup>30 мин</sup>
====================================
Задачи контейнеризации
----------------------

Контейнеризация vs виртуализация
--------------------------------

Ключевые термины контейнеризации
--------------------------------

Podman vs другой популярный стиральный порошок
----------------------------------------------


Hands-on practice quest #00: Prerequisites sound-check and tools install <sup>20 мин парной практики + 10 мин дебриф</sup>
=======================
Given
-----
- [ ] Пары участников

When
----
- [ ] Установлен Podman
```shell
sudo dnf install -y podman
```

Then участники отвечают на вопросы
----


Жизненный цикл готового образа <sup>30</sup>
==============================
Как идентифицируется образ
--------------------------

Как управлять образами c Crane
------------------------------

Как хранится образ
------------------

Hands-on practice quest #01: Pre-built disk image lifecycle with Crane <sup>20 + 10</sup>
=======================


Жизненный цикл пода и контейнера <sup>30</sup>
================================

Hands-on practice quest #02: Pod and Container lifecycle <sup>20 + 10</sup>
=======================


Контейнеризация простого сервиса: автоматическая сборка образа <sup>40</sup>
================================
Задачи сборщиков
----------------

Как собирать с Buildah
----------------------


Hands-on practice quest #03: Simple java application containerization with Buildah <sup>30 + 10</sup>
=======================

Изоляция данных <sup>20</sup>
===============

Hands-on practice quest #04: Simple _stateful_ application containerization <sup>20 + 10</sup>
=======================

Оркестрация <sup>40</sup>
===========
Задачи оркестраторов
--------------------

Управление группой контейнеров с Podman Compose
------------------------------------------------

Hands-on practice quest #05: Multi-component stateful application containerization with Compose <sup>30 + 10</sup>
=======================

Рекомендуемые практики <sup>30</sup>
======================
