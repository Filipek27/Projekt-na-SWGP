# Funkcje statystyczne w Excelu

Microsoft Excel oferuje wiele funkcji statystycznych, które pozwalają szybko analizować dane liczbowe, obliczać miary tendencji centralnej, zróżnicowania, korelacji i wiele innych. Poniżej przedstawiono najważniejsze z nich wraz z krótkim opisem.

## 📊 Miary tendencji centralnej

- **ŚREDNIA (`AVERAGE`)**  
  Zwraca średnią arytmetyczną dla podanego zakresu.  
  **Przykład:** `=AVERAGE(A1:A10)`

- **MEDIANA (`MEDIAN`)**  
  Zwraca wartość środkową z zestawu danych.  
  **Przykład:** `=MEDIAN(A1:A10)`

- **MODA (`MODE.SNGL` / `MODE.MULT`)**  
  Zwraca wartość najczęściej występującą w zestawie danych.  
  **Przykład:** `=MODE.SNGL(A1:A10)`

## 📐 Miary rozproszenia

- **ODCHYLENIE STANDARDOWE (`STDEV.S`, `STDEV.P`)**  
  Mierzy, jak bardzo wartości różnią się od średniej.  
  - `STDEV.S` – dla próbki  
  - `STDEV.P` – dla całej populacji  
  **Przykład:** `=STDEV.S(A1:A10)`

- **WARIANCJA (`VAR.S`, `VAR.P`)**  
  Kwadrat odchylenia standardowego.  
  **Przykład:** `=VAR.S(A1:A10)`

- **ZAKRES (`MAX` - `MIN`)**  
  Różnica między największą a najmniejszą wartością.  
  **Przykład:** `=MAX(A1:A10)-MIN(A1:A10)`

- **LARGE / SMALL**  
  Zwraca n-tą największą lub najmniejszą wartość w zbiorze.  
  **Przykład:** `=LARGE(A1:A10, 2)`  
  **Przykład:** `=SMALL(A1:A10, 1)`

- **RANK.EQ / RANK.AVG**  
  Określa pozycję liczby w zbiorze danych.  
  **Przykład:** `=RANK.EQ(A1, A1:A10)`

## 🔗 Korelacje i współczynniki

- **KORELACJA (`CORREL`)**  
  Oblicza współczynnik korelacji Pearsona między dwiema zmiennymi.  
  **Przykład:** `=CORREL(A1:A10, B1:B10)`

- **WSPÓŁCZYNNIK DETERMINACJI (`RSQ`)**  
  Zwraca wartość \( R^2 \), czyli dopasowanie liniowe.  
  **Przykład:** `=RSQ(A1:A10, B1:B10)`

## 📉 Analiza regresji i prognozowanie

- **FORECAST.LINEAR**  
  Prognozuje przyszłą wartość na podstawie regresji liniowej.  
  **Przykład:** `=FORECAST.LINEAR(13, A1:A12, B1:B12)`

- **TREND**  
  Zwraca wartości przewidywane na podstawie trendu liniowego.  
  **Przykład:** `=TREND(B1:B10, A1:A10)`

- **LINEST**  
  Zwraca współczynniki prostej regresji (nachylenie, przecięcie).  
  **Przykład:** `=LINEST(B1:B10, A1:A10, TRUE, TRUE)`

## 🧮 Inne funkcje statystyczne

- **LICZ.JEŻELI (`COUNTIF`)**  
  Liczy, ile komórek spełnia dany warunek.  
  **Przykład:** `=COUNTIF(A1:A10, ">100")`

- **PERCENTYL (`PERCENTILE.INC`, `PERCENTILE.EXC`)**  
  Zwraca wartość dla danego percentyla.  
  **Przykład:** `=PERCENTILE.INC(A1:A10, 0.9)`

- **KWARTYL (`QUARTILE.INC`, `QUARTILE.EXC`)**  
  Oblicza kwartyle (np. Q1, Q2, Q3).  
  **Przykład:** `=QUARTILE.INC(A1:A10, 3)`

- **AVERAGEIF / AVERAGEIFS**  
  Oblicza średnią na podstawie jednego lub wielu warunków.  
  **Przykład:** `=AVERAGEIF(A1:A10, ">100")`  
  **Przykład:** `=AVERAGEIFS(A1:A10, B1:B10, ">50", C1:C10, "<100")`

- **COUNTIFS**  
  Liczy komórki spełniające wiele warunków.  
  **Przykład:** `=COUNTIFS(A1:A10, ">0", B1:B10, "<10")`

## 🧪 Testy statystyczne

- **T.TEST**  
  Wykonuje test t-Studenta dla dwóch zestawów danych.  
  **Przykład:** `=T.TEST(A1:A10, B1:B10, 2, 1)`

- **Z.TEST**  
  Oblicza jednostronne prawdopodobieństwo w teście Z.  
  **Przykład:** `=Z.TEST(A1:A10, 80)`

- **F.TEST**  
  Porównuje wariancje dwóch zestawów danych.  
  **Przykład:** `=F.TEST(A1:A10, B1:B10)`

---

## 📘 Podsumowanie

Funkcje statystyczne Excela są nieocenione przy analizie danych – zarówno prostych, jak i zaawansowanych. Pozwalają szybko uzyskać miarodajne informacje o rozkładzie, zmienności czy zależnościach między danymi. Dzięki dodatkowym funkcjom regresji i testów statystycznych możliwa jest też bardziej pogłębiona analiza ilościowa.

---
