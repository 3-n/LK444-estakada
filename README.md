# Estakada kolejowa przy Warszawie Wschodniej: model 3D

Strona pokazuje projektowaną łącznicę stacji Warszawa Wschodnia z linią kolejową nr 9 (LK444, tory nr 1 i 2) na trójwymiarowej mapie okolicy: wiadukt nad ul. Chodakowską (W3.1), estakadę nad torami stacji (W3.2, 813,69 m) i wiadukt kratownicowy nad ul. Kijowską (W3.3), razem z dojazdami w korytach i na nasypie. Można zmieniać widok, datę i godzinę, żeby zobaczyć cienie, oraz włączać i wyłączać projekt.

To nieoficjalna wizualizacja poglądowa, a nie dokument projektowy.

## Skąd są dane

- **Projekt:** [dokumentacja przetargowa](https://platformazakupowa.plk-sa.pl/app/demand/notice/public/42848/details): obiekty W3.1, W3.2 i W3.3 oraz rysunki branży torowej (profile podłużne torów nr 1 i 2 LK444, przekrój normalny).
- **Położenie w planie:** plany sytuacyjne 1:1000 dopasowane do granic działek z usługi ULDK (GUGiK) i sprawdzone współrzędnymi tyczenia fundamentów wszystkich 28 podpór estakady. Położenie jest przybliżone, z dokładnością poniżej 1 m.
- **Wysokości:** profile podłużne torów (rzędne w układzie PL-EVRF2007-NH), zgodne z rzędnymi z rysunków podpór.
- **Teren:** numeryczny model terenu GUGiK (usługa services.gugik.gov.pl/nmt), siatka co 10 m.
- **Mapa Geoportal (domyślna):** ortofotomapa GUGiK z 2025 r., pobierana na żywo z geoportal.gov.pl, oraz modele 3D budynków (LoD1, 2024) i drzew (LoD1, 2023) GUGiK, przycięte do kwadratu ok. 2,2 km i uproszczone. Brakujące w nich nowe budynki przy ul. Chodakowskiej i Żupniczej są dorysowane jako proste bryły. Zapisane w pliku `surroundings.glb`.
- **Mapa Google 3D (do wyboru przełącznikiem):** Google Photorealistic 3D Tiles przez Cesium ion, pobierana na żywo. Ta strona nie przechowuje żadnych danych tej mapy.

## Dokładność

**Odczytane z rysunków:** przebieg i wysokość torów, położenie i wymiary fundamentów oraz trzonów podpór, szerokość i wysokość konstrukcyjna przęseł, rozpiętość i schemat kratownic, wiadukt ramowy nad ul. Chodakowską, zasięgi ścian oporowych, położenie klatek schodowych.

**Szacunkowe:** kształt nóg podpór ramowych (uproszczone do prostych słupów), wysokość kratownic (ok. 10,5 m), dachy klatek schodowych, rozstaw i wysokość słupów sieci trakcyjnej, nasyp za wiaduktem nad ul. Kijowską od strony toru nr 2.

## Znane ograniczenia

- Drzewa rosnące w miejscu projektu i w jego najbliższym otoczeniu są usunięte w przybliżeniu, bez inwentaryzacji zieleni. Widać je po wyłączeniu projektu.
- Balustrady na estakadzie mają w projekcie pionowe szczebliny co ok. 12 cm. Na modelu są pokazane jako półprzezroczysty szary pas w ramie. Nad ulicami Chodakowską i Kijowską balustrady mają pełne wypełnienie z poliwęglanu.
- Ciemne plamy na zdjęciach mapy to cienie z dnia nalotu. Nie zmieniają się z godziną.
- Mapa jest wczytywana tylko do ok. 1,1 km od środka estakady, żeby strona działała płynnie. Dalej widać jednolite tło.
- Na mapie Geoportal budynki to proste bryły z płaskim dachem, a drzewa to uproszczone korony. Pochodzą ze skanowania z 2023 r., więc nowsze budynki widać tylko na zdjęciu.

## Uznanie autorstwa

Dane mapy: Google, widoczne na stronie razem z logo. Silnik: [CesiumJS](https://cesium.com/platform/cesiumjs/) (Apache 2.0), przez Cesium ion. Mapa Geoportal: ortofotomapa, numeryczny model terenu oraz modele 3D budynków i drzew GUGiK z geoportal.gov.pl, przetworzone jak opisano wyżej.
