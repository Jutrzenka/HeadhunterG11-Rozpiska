# Informacje o projekcie
**Tu będę umieszczał wszystkie istotne linki, wykresy i informacje odnośnie projektu HeadHunter.**
## :cherries: Repozytoria:
### [Frontend](https://github.com/Jutrzenka/HeadHunterG11-FR)
### [Backend](https://github.com/Jutrzenka/HeadHunterG11-BE)
### [Backlog i Taski - dokumentacja](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/Backlog.md)

# Spis treści:
- :cherries: [Repozytoria](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#cherries-repozytoria)
- :strawberry: [Logo projektu](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#strawberry-logo-projektu)
- :banana: [Dane od klienta i przydatne linki](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#banana-dane)
- :tangerine: [Lista osób w grupie i harmonogram](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#tangerine-lista-os%C3%B3b-w-grupie)
- :mushroom: [Konfiguracja eslint w projektach](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#mushroom-konfiguracja-eslint-w-projektach)
- :hibiscus: [Konfiguracja, struktura i tworzenie branchy](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#hibiscus-konfiguracja-struktura-i-tworzenie-branchy)
- :peach: [Baza danych](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#peach-baza-danych)
- :fish_cake: [SCRUM daily template](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#fish_cake-scrum-daily-template)
- :egg: [Ważne notatki](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/README.md#egg-wa%C5%BCne-notatki)


## :strawberry: Logo projektu:
![LOGO MEGAK](https://media.discordapp.net/attachments/998337171998113922/999379494810947644/400_609bb5e2d9a39.png)

[LINK DO LOGO](https://media.discordapp.net/attachments/998337171998113922/999379494810947644/400_609bb5e2d9a39.png)

## :banana: Dane:
### Dane od klienta:
- [Specyfikacja](https://docs.google.com/document/d/1j3iltSfaJXB8lVi5dwApL9UU0ze7A8kz9DBDChIVwfw/edit)
- [Makieta](https://xd.adobe.com/view/864faeb9-d762-4277-a5d1-5b7565dcf543-d31c)
### Linki związane z projektem:
- [Nasza tablica Trello](https://trello.com/b/fJ0v7K6u/mega-k-head-hunter)
- [Planning Poker](https://planningpokeronline.com/)

## :tangerine: Lista osób w grupie:
### [Harmonogram godzinowy](https://docs.google.com/spreadsheets/d/1P3q45U8Sn6ScgMWPRxp0AnmOyEpyUiCAE8NckNMZKGU/edit?usp=sharing)
**Członkowie grupy (nick na GitHub):**
1. [Jutrzenka](https://github.com/Jutrzenka)
2. [iwanczakrafal](https://github.com/iwanczakrafal)
3. [madridista5](https://github.com/madridista5)
4. [Marcel998](https://github.com/Marcel998)
5. [marooonio](https://github.com/marooonio)
6. [NorGoz](https://github.com/NorGoz)
7. [OllaWilk](https://github.com/OllaWilk)
8. [RafalKuchta](https://github.com/RafalKuchta)

**Szczególne role:**
- SM: **Jutrzenka#2251**
- Autor materiałów DEMO: **Marcel998#5607**

## :mushroom: Konfiguracja eslint w projektach
### Konfigurowanie eslint'a:

![eslint](https://user-images.githubusercontent.com/93550588/180338326-6ba4c998-a7e3-4abb-8b3b-57c7f5639999.png)

0. Znajdź w ustawieniach okienko ESlinta
1. Zaznacz `Manual ESlint configuration`
2. Wybierz `ESlint package` jako paczkę znajdującą się w `node_modules` tego projektu
3. Zaznacz `Configuration file`, a następnie wybierz `.eslintrc.js` znajdujący się w tym projekcie
4. Zaznacz `Run ESlint --fix on save
5. ESlint powinien być skonfigurowany. Teraz przejdź do konfiguracji prettiera.

### Konfigurowanie prettier'a:

![prettier](https://user-images.githubusercontent.com/93550588/180338353-f1575b90-1bd0-46bb-98b2-03ae28f0c00b.png)

0. Znajdź plugin prettier
1. Wyłącz plugin (W tej konfiguracji ESlint sam używa prettiera, a plugin powoduje jedynie crashe)
2. Konfiguracja powinna być gotowa!

### Zrób tak dla Backendu i Frontendu!

## :hibiscus: Konfiguracja, struktura i tworzenie branchy:
Mamy dwa głowne branche
1. main
2. develop

**Nowe branche tworzymy według wzoru.**

Struktura nazwy brancha: `#{kod referencyjny}/{opis zadania}` np. `#0004/Konfiguracja_baz_danych`

### Aby zakodować nową funkcję wpierw tworzycie branch pod dany Backlog z tabeli Trello.

**Przykład:**
Backlog z trello:

![image](https://user-images.githubusercontent.com/93550588/180336093-9381929d-8485-407d-a279-26b3b6736f73.png)

**Branch:**

`#0004/Konfiguracja_baz_danych`

### Następnie na bazie stworzonego brancha tworzycie nowy specjalnie pod dany task.

**Przykład:**
Task z trello:

![image](https://user-images.githubusercontent.com/93550588/180336582-768ad26f-3a72-424d-95d4-0b981b4693d5.png)

**Branch:**

`#0004-4/MongoDB`

#### UWAGA! W PRZYPADKU TASKÓW (ALE NIE BACKLOGÓW) NIE MUSICIE PODAWAĆ PEŁNEJ NAZWY TASKA. MOŻECIE PODAĆ ZROZUMIAŁĄ SKRÓCONĄ WERSJĘ
Możecie zmienić:
`#0004-4/KONFIGURACJA_BAZ_DANYCH:Przygotować_schema_MongoDB`
na
`#0004-4/MongoDB`

Prawidłowo wyglądająca struktura:

![image](https://user-images.githubusercontent.com/93550588/180337827-7793946b-3ece-45b3-b664-d33c1d8d93d7.png)

### Mergowanie
Mergowanie odbywa się w następującym schemacie:

`branch taska -> branch backloga -> branch develop -> branch main`

**Przykład:**

`#0004-4/MongoDB -> #0004/Konfiguracja_baz_danych -> (Gdy backlog zostanie wykonany w całości) -> develop -> main`

## :peach: Baza danych:
![BAZA DANYCH WYKRES](https://user-images.githubusercontent.com/93550588/180282358-76fd9627-83c7-4938-ae62-85926376089b.png)

## :fish_cake: SCRUM daily template
```
**- Co robiłam/robiłem wczoraj?**
<odpowiedź>
**- Co planuje zrobić dzisiaj?**
<odpowiedź>
**- Czy pojawiły się jakieś przeszkody?**
<odpowiedź>
```

## :egg: Ważne notatki:
- [Notatka ze spotkania z klientem #1](https://github.com/Jutrzenka/HeadhunterG11-Rozpiska/blob/main/SpotkanieZKlientem1.md#notatka-ze-spotkania-z-klientem)
