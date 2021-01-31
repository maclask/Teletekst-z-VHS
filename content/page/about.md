+++
title = "O projekcie"
description = ""
date = "2019-02-28"
aliases = ["o-projekcie", "about", "about-us", "about-hugo"]
author = "Maciej Laskowski"
license = "CC BY-NC-ND"
lastmod = "2020-01-31"
+++

Strona jest efektem projektu grupowego przeprowadzonego w ramach studiów magisterskich na wydziale Elektroniki, Telekomunikacji i Informatyki Politechniki Gdańskiej w roku 2020/2021.

Celem projektu jest odzyskanie i zarchiwizowanie informacji przekazywanych w systemie teletekstu, a zapisanych (wraz z programami telewizyjnymi) na kasetach VHS.

## Proces pozyskania teletekstu

Pozyskanie teletekstu odbywa się poprzez rejestracje materiału filmowego z kasety VHS zawierającej nagraną transmisję telewizyjną. 

W niewidocznej dla widza części ekranu VBI (Vertical Blanking Interval)  zakodowana jest tam informacja teletekstu, czy popularnej "telegazety". Rejestracja musi więc odbywać się za pomocą urządzenia 
przechwytującego, które jest w stanie rejestrować tę część obrazu. W tym projekcie posłużono się kartą telewizyjną Hauppauge WinTV 44914 podłączoną do komputera poprzez złącze PCI. 
Kaseta odtwarzana była poprzez magnetowid Panasonic NV-SD420. 

Do rejestracji oraz zdekodowania teletekstu wykorzystano kod źródłowy projektu [VHS teletext](https://github.com/ali1234/vhs-teletext) udostępnionego na licencji GPL 3.0.

Całość uruchomiona była na systemie Linux przy wsprciu rdzeni CUDA karty graficznej Nvidia GTX 1660 Ti. 

## Strona internetowa

Strona internetowa stworzona jest dzięki generatorowi stron statycznych [Hugo](https://gohugo.io/). Hostowana jest w [repozytorium GitHub](https://github.com/maclask/Teletekst-z-VHS).

## Autorzy

29@KSMM'2020 Odczyt i archiwizacja teletekstu z nagrań programów telewizyjnych na kasetach VHS 
 
Kierownik projektu: Maciej Laskowski

Członkowie zespołu: Karol Jaros, Maciej Szpiech

Opiekun projektu: dr inż. Piotr Odya

