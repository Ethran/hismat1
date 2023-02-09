# Wykład 14: 11-01-2023 Rozwój Analizy Matematycznej, część III Newton i Leibniz

Tagi: Newton, wiek XVII, Leibniz, Principia, język uniwersalny

## Wiek XVII - globalny kryzys

- Wojny religijne, kontrreformacja, wojna domowa w Anglii (purytanie vs papiści, 1640s), Leibniz w tym czasie jest na misjach dyplomatycznych w Europie w sprawie zjednoczenia kościołów.

- Epidemia dżumy (1665-1666), masa zgonów, w Londynie $\ge6000$ tygodniowo w listopadzie 1665, skutkiem było zamknięcie Uniwersytetu w Cambridge od sierpnia 1665 do marca 1666. Rok 1666 był cudownym rokiem (annus mirabilis) dla **Newtona** (który miał wtedy 23 lata), bo lubił pracować sam i zrobił sobie wtedy "korzeń" do swoich późniejszych prac.

- Mała Epoka Lodowcowa, nawet Tamiza zamarzła (pisał o tym Samuel Pepys w swoich pamiętnikach).

## Rewolucja naukowa

- Uwolnienie się nauki od Kościoła.

- Ogromne ambicje.

- Mechaniczny model świata - świat można "obliczać".

- Zastosowanie rozwiązań matematycznych w problemach praktycznych.

## Isaac Newton (1643-1727)

- **Cambridge** (1661-1695) - "Philosophiae naturalis principia mathematica" (1687), zajmował się matematyką, mechaniką, grawitacją, biblistyką, alchemią, astrologią i numerologią

- **Londyn** (1695-1727) - kurator Mennicy Królewskiej, prezes Royal Society (1703-1727), spór z Leibnizem.

## Gottfried Wilhelm Leibniz (1646-1716)

- **Lipsk, Norymberga** - zajmował się prawem, filozofią i dyplomacją.

- **Paryż** (1672-1676) - Huygens wprowadził go do matematyki, poznał rachunek różniczkowy i całkowy

- **Hanower** (1677-1716) - bibliotekarz księcia Hanoweru (Leibniz się wycwanił i dużo podróżował pod pretekstem badania genealogii rodu księcia), wkład w praktycznie każdą dziedzinę nauki - matematyka, logika, fizyka, "informatyka", semiotyka, psychologia i więcej

## Matematyka w XVII wieku

- Zadania są geometryczne, wymagana jest konstrukcja rozwiązania.

- Kartezjusz wprowadził nowość - geometrię analityczną, która wymagała dwóch etapów rozwiązania:
  - Analiza - ułożenie równania algebraicznego na podstawie wzajemnej relacji odcinków na rysunku docelowym. 
  - Synteza - konstrukcja równania, czyli geometryczna konstrukcja odcinka odpowiadającego rozwiązaniu równania algebraicznego.

## Nowa analiza - Newton, rozwinięcie potęg dwumianu
$(a+b)^2 = a^2 + 2ab + b^2$

$(a+b)^3 = a^3 + 3a^2b + 3ab^2 + b^3$

$\cdots$

$(a+b)^{\frac{m}{n}}=a^{\frac{m}{n}}+\sum_{k=1}^{\infty}\frac1{k!}(\frac{m}{n})(\frac{m}{n}-1)\cdots(\frac{m}{n}-k+1)a^{\frac{m}{n}-k}b^k$


Newton wykorzystał silnię do obliczenie wielu całek dla całych klas krzywych, także niealgebraicznych (nazywane krzywymi mechanicznymi), stąd jego przewaga nad "Geometrią" Kartezjusza, który w ogóle nie zajmował się całkowaniem i badał tylko krzywe algebraiczne. Newton wykorzystywał również inne rozwinięcia funkcji w szeregi nieskończone dla konkretnych obliczeń numerycznych. Metody Newtona wykorzystywano np. w nawigacji. Newton lubił liczyć i podawał aproksymację logarytmu z dokładnością do nawet ponad 50 miejsc po przecinku.

## Wzór Newtona
$f(b) - f(a) = \int_a^b f'(x)dx$

## Philosophiae naturalis principia mathematica

- Najwybitniejsze dzieło naukowe w języku geometrii. 
- Aksjomaty, twierdzenia matematyczne.
- Ruch ciał w ośrodkach bez tarcia (grawitacja).
- Ruch ciał w ośrodkach z tarciem (płyny, ale w jego doświadczeniach były istotne błędy).
- Zastosowania w astronomii (teoria księżyca).
- Za pomocą prostych narzędzi rozwiązywał ciężkie problemy.
- Głównie to były rysunki i ewentualnie tekst opisujący je.
- Duże kontrowersje wywołało odkrycie działania sił na odległość.
- Napisane po łacinie.

## Prawa Keplera
1. Każda planeta Układu Słonecznego porusza się wokół Słońca po elipsie, w jednym z ognisk jest Słońce.
2. W równych odstępach czasu promień wodzący planety od Słońca zakreśla równe pola.
3. Stosunek kwadratu okresu obiegu planety wokół Słońca do sześcianu wielkiej półosi jej orbity jest stały dla wszystkich planet Układu Słonecznego.

## Prawo grawitacji Newtona
$F = \frac{Gm_1m_2}{r^2}$ -> wynika z praw Keplera

## Leibniz - rachunek różniczkowy i całkowy
Wymyślił genialną symbolikę używaną współcześnie.

$z=z(y(x)), \frac{dz}{dx}=\frac{dz}{dy}\frac{dy}{dx}$

$\frac{dy}{dx}=f(x)\implies dy=f(x)dx\implies y = \int dy = \int f(x)dx$

Pracował nad uniwersalnym językiem formalnym "characteristica universalis" (bazowane jest na tym wiele języków programowania, np. Algol, Fortran czy Mathematica, a także język teorii mnogości i algebra uniwersalna).

Inne wzory wprowadzone przez Leibniza:
- $\frac{d}{dx}(f(x)g(x))=\frac{df(x)}{dx}g(x)+f(x)\frac{dg(x)}{dx}$
- $\int cf(x)dx=c\int f(x)dx$
- $\int f(x)+g(x)dx = \int f(x)dx + \int g(x)dx$

## Ewolucja nazwy
- 1675 - summa (Leibniz)
- 1690 - integral (Bernoulli)
- 1804 - całka (Śniadecki)

## Maszyna licząca Leibniza
- Przedstawiona w 1673r. na posiedzeniu Towarzystwa Królewskiego w Londynie. 
- Potrafiła odejmować, mnożyć, dzielić i pierwiastkować (pierwiastek kwadratowy).
- Oparta na wcześniejszych maszynach **Schickarda** (zegar liczący - 1623, dla Keplera, dodawanie, odejmowanie, mnożenie, dzielenie) i **Pascala** (pascalina - 1645, dodawanie, odejmowanie).

## Newton vs Leibniz
- Newton
  - Fizykę należy opisywać w języku matematyki.
  - Dowody matematyczne w Principiach są w języku geometrii.
  - Metody geometryczne Newtona spowodowały zastój matematyki w UK (zmiana parametru kompletnie zmieniała równanie).
- Leibniz
  - Wyraził rachunek różniczkowy i całkowy oraz jego prawa w języku analitycznym. Rachunek jako algorytm.
  - Rachunek różniczkowy i całkowy był tylko częścią planu zbudowania uniwersalnego języka formalnego.
  - Dzięki symbolice Leibniza jego rachunek szybko rozwijał się w Europie.


