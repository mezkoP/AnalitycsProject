# Projekt: Analiza i Wizualizacja Danych Nieruchomości 

## Wprowadzenie

Niniejszy projekt ma na celu analizę i wizualizację danych dotyczących rynku nieruchomości. Dane pochodzą z zbioru `housing.csv`, który zawiera informacje takie jak mediana dochodów, mediana wartości nieruchomości, bliskość do oceanu oraz geograficzne współrzędne nieruchomości. Celem analizy jest zidentyfikowanie wzorców i zależności pomiędzy różnymi zmiennymi oraz wizualizacja tych zależności w celu lepszego zrozumienia rynku nieruchomości.

## Cechy zbioru

Zbiór danych `housing.csv` zawiera następujące kolumny, na których będziemy pracować:

- **longitude**: Długość geograficzna lokalizacji nieruchomości.
- **latitude**: Szerokość geograficzna lokalizacji nieruchomości.
- **housing_median_age**: Średni wiek nieruchomości w danym obszarze.
- **total_rooms**: Całkowita liczba pokoi w nieruchomościach w danym obszarze.
- **total_bedrooms**: Całkowita liczba sypialni w nieruchomościach w danym obszarze.
- **population**: Liczba mieszkańców w danym obszarze.
- **households**: Liczba gospodarstw domowych w danym obszarze.
- **median_income**: Mediana dochodów gospodarstw domowych w danym obszarze.
- **median_house_value**: Mediana wartości nieruchomości w danym obszarze.
- **ocean_proximity**: Kategoria określająca bliskość nieruchomości do oceanu.

### Opis Kolumn

1. **longitude** i **latitude**:
   - Te kolumny zawierają współrzędne geograficzne, które pozwalają na zlokalizowanie nieruchomości na mapie. Będą one wykorzystywane do tworzenia map punktowych przedstawiających wartości nieruchomości w zależności od lokalizacji.

2. **housing_median_age**:
   - Średni wiek nieruchomości może być używany do analizy wpływu wieku budynków na ich wartość. Może to również pomóc w identyfikacji starszych i nowszych dzielnic.

3. **total_rooms** i **total_bedrooms**:
   - Te kolumny dostarczają informacji o wielkości nieruchomości, co może wpływać na ich wartość. Liczba pokoi i sypialni może być używana do analizy preferencji mieszkaniowych.

4. **population** i **households**:
   - Dane o liczbie mieszkańców i gospodarstw domowych w danym obszarze mogą pomóc w analizie gęstości zaludnienia i struktury demograficznej, co może wpływać na ceny nieruchomości.

5. **median_income**:
   - Mediana dochodów jest kluczowym wskaźnikiem ekonomicznym, który pozwala na analizę zależności między zamożnością mieszkańców a cenami nieruchomości.

6. **median_house_value**:
   - Mediana wartości nieruchomości jest główną zmienną zależną w analizie. Jest to wartość, którą staramy się modelować i zrozumieć poprzez inne zmienne.

7. **ocean_proximity**:
   - Kategoria bliskości do oceanu jest używana do analizy wpływu lokalizacji względem wody na wartość nieruchomości. Różne kategorie (np. `NEAR BAY`, `NEAR OCEAN`, `INLAND`) mogą wykazywać różne średnie wartości nieruchomości.

### Wnioski

Zbiór danych `housing_data` zawiera szeroki zakres informacji, które pozwalają na kompleksową analizę rynku nieruchomości. Praca z tymi danymi umożliwi zidentyfikowanie kluczowych czynników wpływających na wartość nieruchomości, takich jak dochody mieszkańców, wiek budynków, liczba pokoi oraz lokalizacja geograficzna. Analiza tych danych przyczyni się do lepszego zrozumienia dynamiki rynku nieruchomości i może być użyteczna dla inwestorów, deweloperów oraz decydentów.

## Metody Analizy i Wizualizacji

### 1. Wykres Rozrzutu

Wykres rozrzutu został użyty do przedstawienia zależności między medianą dochodów a medianą wartości nieruchomości. Wykres ten pozwala zidentyfikować pozytywną korelację między tymi dwoma zmiennymi.

### 2. Mapa Cieplna Korelacji

Mapa cieplna korelacji między zmiennymi w zbiorze danych pokazuje, jak silnie zmienne są ze sobą powiązane. Kolorystyka mapy pomaga w łatwym zidentyfikowaniu silnych i słabych korelacji.

### 3. Histogram Rozkładu Mediany Wartości Nieruchomości

Histogram pozwala zobaczyć rozkład mediany wartości nieruchomości. Jest to przydatne do zidentyfikowania najczęściej występujących wartości w zbiorze danych.

### 4. Wykres Słupkowy Średnich Wartości dla Różnych Kategorii Bliskości do Oceanu

Wykres słupkowy pokazuje, jak bliskość do oceanu wpływa na średnią wartość nieruchomości. Kategoria ocean_proximity pozwala zidentyfikować lokalizacje, które mają wyższe średnie wartości nieruchomości.

### 5. Mapa Punktowa Wartości Nieruchomości na Mapie Geograficznej

Mapa punktowa przedstawia wartości nieruchomości na mapie geograficznej, co pozwala zobaczyć, jak wartości nieruchomości są rozmieszczone przestrzennie.

## Zagadnienia Branżowe
### Rynek Nieruchomości
Rynek nieruchomości jest dynamicznym i kompleksowym sektorem gospodarki, który obejmuje zarówno handel nieruchomościami, jak i ich wynajem, zarządzanie i finansowanie. Kluczowe czynniki wpływające na wartości nieruchomości to lokalizacja, warunki ekonomiczne, polityka rządowa, stopy procentowe oraz demografia.

#### Wpływ Dochodów na Wartość Nieruchomości
Mediana dochodów mieszkańców danego obszaru jest jednym z głównych czynników wpływających na wartość nieruchomości. Wyższe dochody zazwyczaj korelują z wyższymi cenami nieruchomości, co wynika z większej zdolności nabywczej oraz większego zapotrzebowania na lepsze standardy mieszkaniowe.

### Geograficzne Rozmieszczenie Wartości Nieruchomości
Lokalizacja jest jednym z najważniejszych czynników determinujących wartość nieruchomości. Bliskość do centrów miejskich, miejsc pracy, szkół, parków oraz dostęp do transportu publicznego znacząco wpływają na ceny nieruchomości. Bliskość do wody, takiej jak oceany czy jeziora, często podnosi wartość nieruchomości ze względu na atrakcyjność wizualną i dostęp do rekreacji.
