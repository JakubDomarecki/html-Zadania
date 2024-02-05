![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


## Zadanie 1 - rozwiązywane z wykładowcą

> ### Przygotowanie
>
> Zmodyfikuj plik `vite.config.js` tak, aby zmienna `exercisePath` wskazywała na:
>
> - `01_Dzien_1/05_Tlo/01_Zadanie_1`
>
> **Pamiętaj aby włączyć serwer deweloperski (`npm run dev`).**

### Część 1

Wyzeruj dla **body** marginesy, a następnie ostyluj banner o klasie **.banner**. Powinien on:

- zajmować pełną wysokość strony
- powinien mieć grafikę w tle, która znajduje się w w **images/bg.jpg**
- grafika powinna zajmować jego całą powierzchnię i być wycentrowana

### Część 2

Element o klasie `.banner__text` ostyluj w następujący sposób:

- wielkość **70px**
- **biały** kolor
- krój **Georgia**
- cień o parametrach **0 0 30px** i koloru **rgba(36,134,115,0.7)**
- margines górny wyzerowany
- padding górny ustawiony na `calc(50vh - 40px)`

### Część 3

Poniżej baneru znajduje się przykładowy tekst. Nadaj mu stylowanie:

- tło gradientowe 2 kolorowe: **#27C6A2** i **#169678**
- wewnętrzny odstęp od krawędzi **100px**
- krój Georgia,
- biały kolor tekstu
- wielkość tekstu `1.2rem` oraz `2rem` wielkość interlinii


## Zadanie 2

> ### Przygotowanie
>
> Zmodyfikuj plik `vite.config.js` tak, aby zmienna `exercisePath` wskazywała na:
>
> - `01_Dzien_1/05_Tlo/02_Zadanie_2`
>
> **Pamiętaj aby włączyć serwer deweloperski (`npm run dev`).**

- Utwórz element div i nadaj mu klasę **rocks**.
- W CSS-ie ustaw rozmiar diva - szerokość **600px**, wysokość **350px**.
- Ustaw jako tło obrazek **rocks.jpg**, znajdziesz go w katalogu **images/**.
- Wykorzystaj **background-size** i **background-position** tak aby obrazek był pokazany na samym środku.


## Zadanie 3

> ### Przygotowanie
>
> Zmodyfikuj plik `vite.config.js` tak, aby zmienna `exercisePath` wskazywała na:
>
> - `01_Dzien_1/05_Tlo/03_Zadanie_3`
>
> **Pamiętaj aby włączyć serwer deweloperski (`npm run dev`).**

Twoim zadaniem będzie dodanie stylowania do elementu `.banner`, który znajduje się na górze strony.

Do elementu `.banner` dodaj następujące właściwości:

- kolor tła **czarny**
- grafikę tła, którą będzie obrazek `banner.jpg` znajdujący się w katalogu `images`. Pamiętaj o odpowiedniej ścieżce
- wielkość tła taka by zawsze przykrywała cały baner
- tło wycentrowane w poziomie i przyklejone do górnej krawędzi
- przypnij tło za pomocą właściwości `background-attachment: fixed`
- kolor tekstu na biały
