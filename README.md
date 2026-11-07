# Trasa po lumpeksach

Strona, która układa trasę po lumpeksach. Podajesz start, cel i godzinę, a dla każdego sklepu ocenę od 1 do 10, dzienny spadek oceny, dzień dostawy i czas na wizytę. Aplikacja wybiera sklepy o najwyższej łącznej ocenie, które zdążysz odwiedzić pieszo, rowerem albo komunikacją.

To niekomercyjny projekt do użytku prywatnego. Bez logowania dane zostają w przeglądarce użytkownika. Po zalogowaniu kontem Google lista sklepów i ustawienia są przechowywane w Google Firebase i dostępne tylko dla tego konta. Adresy i współrzędne trafiają do serwisów wymienionych niżej.

## Serwisy i dane

- Dane mapy: © współtwórcy [OpenStreetMap](https://www.openstreetmap.org/copyright), licencja ODbL
- Wyszukiwanie: [Nominatim](https://operations.osmfoundation.org/policies/nominatim/), wyłącznie po kliknięciu „Szukaj”, najwyżej jedno zapytanie na sekundę
- Trasy pieszo i rowerem: [FOSSGIS](https://routing.openstreetmap.de/about.html)
- Komunikacja: [Transitous](https://transitous.org/api/) i [jego źródła danych](https://transitous.org/sources/)
- Kafelki mapy: [CARTO](https://carto.com/attributions), biblioteka [Leaflet](https://leafletjs.com/)
- Gotowa lista lumpeksów z Wrocławia: OpenStreetMap (ODbL) i [przewodnik wroclaw.pl](https://www.wroclaw.pl/dla-mieszkanca/lumpeksy-we-wroclawiu-tutaj-kupisz-ubrania-w-atrakcyjnych-cenach), stan z listopada 2026
- Logowanie i zapis: Google Firebase
- Opcjonalnie: Google Maps Platform, z własnym kluczem użytkownika

## Kontakt

Pytania i zgłoszenia: zakładka Issues w tym repozytorium.

## Licencja

MIT, szczegóły w pliku [LICENSE](LICENSE).
