[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![NSF-1948926](https://img.shields.io/badge/NSF-1948926-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1948926)

# Neotoma Current R Workshop

A repository to host interactive R workshops. This repository will always be set up for the most recent/current Neotoma Workshop. All past workshops will be archived in the [Neotoma Workshops](https://github.com/NeotomaDB/Workshops) repository.

This repository is built with the structure required to serve the content through an interactive, online RStudio session using Binder (and Docker). Clicking the Binder link will open RStudio in the user's browser.

**Currently, this repo hosts the Workshop to be delivered for the online African Pollen Database workshop.**

*Russian description:*

Репозиторий для проведения интерактивных семинаров по R. Этот репозиторий всегда будет содержать самую последнюю/текущую Neotoma Workshop. Все прошедшие семинары будут храниться в архивном репозитории  [Neotoma Workshops](https://github.com/NeotomaDB/Workshops). 

Этот репозиторий построен таким образом, что позволяет работать в онлайн режиме через RStudio с использованием Binder (и Docker). Щелкнув ссылку Binder, вы откроете RStudio в браузере пользователя.

**В данный момент, в этом репозитории хранится семинар, который будет проведен онлайн и называется: African Pollen Database workshop**
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NeotomaDB/Current_Workshop/main?urlpath=rstudio)

## Contributors / Авторы

This is an open project and contributions are welcome from any individual.  All contributors to this project are bound by a [code of conduct](CODE_OF_CONDUCT.md).  Please review and follow this code of conduct as part of your contribution.

*Russian description:*

Это открытый проект и приветствуется вклад всех желающих. Участники проекта связаны [Правилами поведения](CODE_OF_CONDUCT.md). Пожалуйста, ознакомитесь с правилами и следуйте им, это является обязательным условием для участников проекта.

* [![orcid](https://img.shields.io/badge/orcid-0000--0002--7926--4935-brightgreen.svg)](https://orcid.org/0000-0002-7926-4935) [Socorro Dominguez Vidana](https://sedv8808.github.io/)

* [![orcid](https://img.shields.io/badge/orcid-0000--0002--2700--4605-brightgreen.svg)](https://orcid.org/0000-0002-2700-4605) [Simon Goring](http://goring.org)

## How to use this repository / Как использовать репозиторий

This repository contains two different R workflows, a complex workflow that shows how to manage and modify chronologies with the R package, and a simple workflow that shows how to access data and perform relatively simple analysis. These workflows may be modified for content (e.g., focusing on different dataset types or geospatial contexts).

Users may clone this workshop and modify the content, but be aware that the Binder links are specific to this repository, and must be modified through the users' own Binder setup.

* `runtime.txt` is used to define the R environment to be used by Docker/Binder
* `apt.txt` defines a set of packages required by Binder/Docker to enable the spatial tools in the `neotoma2` R package.

*Russian description:*

В репозитории содержится два разных R workflow (фиксированный пошаговый процесс обработки данных и отчетности): **сложный рабочий процесс** показывает как управлять хронологиями (*наборы данных Neotoma*) и изменять их с помощью пакета R, и **простой рабочий процесс**, который показывает как получить доступ к данным и выполнить относительно простой анализ. Эти рабочие процессы могут быть изменены под ваши задачи (например, сделать акцент на разные типы наборов данных или геопространственные данные).

Пользователи могут клонировать это рабочее пространство и модифицировать содержимое, но важно помнить, что ссылки Binder связаны именно с этим репозиторием и должны быть измененны посредством собственного Binder.

* `runtime.txt` Используется для определения среды R, которая будет использоваться Docker/Binder
* `apt.txt` Используется для определения набора пакетов необходимых для работы Binder/Docker с досутпом к пространственным данным из пакета R`neotoma2`.
