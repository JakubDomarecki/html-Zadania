![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


## Zadanie domowe - Kolorowe kafelki

> ### Przygotowanie
>
> Zmodyfikuj plik `vite.config.js` tak, aby zmienna `exercisePath` wskazywała na:
>
> - `06_Dzien_3_-_Praca_domowa/01_Kolorowe_kafelki`
>
> **Pamiętaj aby włączyć serwer deweloperski (`npm run dev`).**

W pliku `index.html` znajduje się przykładowy kod mini galerii z projektami. Twoim celem będzie nadanie jej wyglądu jak na poniższej grafice:

![](images/01_example.png)

Wytyczne do zadania:

- elementy mają wymiary `250x200`,
- elementy mają zaokrąglenie narożników o wielkości `10px`
- tekst w elementach pisany jest krojem `sans-serif` o wielkości `20px` i kolorze białym.
- jeżeli mają na tyle miejsca, powinny wyświetlić się obok siebie. Jeżeli będziemy zmniejszać okno przeglądarki, powinny spadać do kolejnych rzędów

Kolory kolejnych elementów to:

- orangered
- gold
- blueviolet
- mediumspringgreen
- dodgerblue
- lawngreen
- coral
- darkgray


## Flexbox Defense

Ukończ grę Flexbox Defense do której link znajdziesz tutaj: [http://www.flexboxdefense.com/](http://www.flexboxdefense.com/).


## Zadanie domowe

> ### Przygotowanie
>
> Zmodyfikuj plik `vite.config.js` tak, aby zmienna `exercisePath` wskazywała na:
>
> - `06_Dzien_3_-_Praca_domowa/03_Strona_eventowa`
>
> **Pamiętaj aby włączyć serwer deweloperski (`npm run dev`).**

Stwórz stronę jak na załączonym obrazku:

![](images/03_example.jpg)

- Zacznij od zresetowania wszystkich właściwości CSS zależnych od przeglądarki (prosty reset wystarczy).
- Dołącz do strony font [Bungee Inline](https://fonts.google.com/specimen/Bungee+Inline). Podłącz rodzinę czcionek bezpośrednio z Google Fonts.
- Do body dodaj 3 elementy:
  - `header`
  - `section`
  - `footer`
- Stwórz klasę **container**. Ustaw jej szerokość `800px` i spraw, żeby zawsze była wyśrodkowana w poziomie.
- Ustaw elementowi `header` szerokość `100%` oraz wysokość `700px` i użyj pliku **concert.jpg** z katalogu **images** jako tła.
- Niech tło w elemencie `header` zawsze będzie wyśrodkowane i zawsze odpowiednio rozciągnięte aby pokryć cały element (użyj odpowiednich wartości przy właściwościach `background-size` i `background-position`).
- Wewnątrz elementu `header` umieść tekst (wykorzystaj odpowiedni semantyczny element), wyśrodkuj go w pionie i poziomie względem rodzica i nadaj mu odpowiednie właściwości:
  - waga czcionki na `700`,
  - wielkość czcionki na `50px`,
  - kolor ustaw na `#FFFFFF`
- Ustaw elementowi `section` szerokość `100%` i kolor tła `#FFFFFF`.
- W pliku **text.txt** jest tekst, jaki należy umieścić wewnątrz elementu `section`.
- Pamiętaj, że tekst w elemencie `section` musi zostać ograniczony przez odpowiedni element z klasą **container**.
- Odsuń tekst od góry i od dołu o `100px` i nadaj mu odpowiednie właściwości:
  - waga czcionki `400`,
  - wielkość czcionki `22px`,
  - wysokość linii `26px`
- Ustaw elementowi `footer` szerokość `100%` i wysokość `200px` oraz kolor tła `#000000`.
- Tekst w elemencie `footer` jest wyśrodkowany w pionie i przesunięty maksymalnie w prawo (pamiętaj, że jest ograniczony przez element z klasą **container**).
- Tekst w elemencie `footer` ma następujące właściwości:
  - waga czcionki `400`,
  - wielkość czcionki `20px`,
  - kolor czcionki `#FFFFFF`.
