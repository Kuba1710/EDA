### EDA - Wskaźnik Presji Zakupowo-Sprzedażowej (BSP)

Wskaźnik BSP przyjmuje wartości w zakresie od -1 do 1, gdzie 0 oznacza poziom neutralny. Wartości powyżej 0 wskazują na rosnącą presję sprzedażową, natomiast wartości poniżej 0 sygnalizują wzmożoną presję zakupową. Na pierwszy rzut oka metryka ta przypomina wskaźnik RSI, jednak jest znacznie precyzyjniejsza, ponieważ analizuje rzeczywiste dane zakupowo-sprzedażowe zamiast samej ceny aktywa.

BSP pomaga identyfikować potencjalne punkty zwrotne na rynku, wskazując najlepsze momenty do sprzedaży, gdy wartości wskaźnika są skrajnie wysokie, oraz do zakupu, gdy wskaźnik osiąga skrajnie niskie poziomy.

## Projekt

W ramach projektu kluczowe jest prowadzenie analizy w sposób płynny, tak aby każdy element kodu i treści był logicznie powiązany z pozostałymi. Poniżej znajdziesz przykładowe analizy dotyczące wskaźnika BSP, jednak najważniejsze jest samodzielne interpretowanie wyników oraz formułowanie i testowanie własnych hipotez.

### Kluczowe elementy analizy:
- Uzupełnienie pliku `src/main.ipynb`.
- Przedstawienie danych: ich składu, rozkładu oraz podstawowych parametrów statystycznych.
- Postawienie kilku hipotez i ich weryfikacja poprzez analizę danych.
- Wyciągnięcie praktycznych wniosków, które mogą być zastosowane w inwestowaniu.
- Rozwinięcie hipotez (zarówno potwierdzonych, jak i odrzuconych) na podstawie zgromadzonych wyników.

### Przykładowe kierunki analizy:
- Zachowanie ceny po przekroczeniu określonego poziomu wskaźnika BSP.
- Reakcja ceny po przekroczeniu minimum wskaźnika w danym zakresie czasowym.
- Zależności między wartościami wskaźnika a ruchem ceny.

## Cześć 2: Budowa Strategii
...

## Dane

Dane są dostępne w katalogu `data`, a ich nazwy zawierają ticker giełdowy oraz interwał czasowy. Każdy rekord danych zawiera:
- `ts` - znacznik czasu (timestamp).
- `ob_10_p_*` - świece OHLC wskaźnika BSP.
- `h`, `l`, `o`, `c` - świece OHLC ceny aktywa.

## Przykłady

W katalogu `examples` znajdują się przykładowe analizy i wykresy, które mogą posłużyć jako inspiracja do własnych badań.

Projekt ma na celu nie tylko zrozumienie wskaźnika BSP, ale także jego praktyczne zastosowanie w analizie rynkowej oraz tworzeniu strategii inwestycyjnych.

