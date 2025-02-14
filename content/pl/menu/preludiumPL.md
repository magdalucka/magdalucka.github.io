---
author: "Magdalena Łucka"
title: "PRELUDIUM 21"
date: 2021-07-13
description: "Zapoznaj się z moim głównym projektem zajmującym się danymi SAR, lodowcami oraz uczeniem maszynowym."
thumbnail: /lodowiec.png
---

<script src="https://kit.fontawesome.com/ee68e4fa6d.js" crossorigin="anonymous"></script>

<span style="color: RoyalBlue; font-size: 1.5em;">Nowe spojrzenie na badanie kinematyki lodowców w kontekście globalnych zmian klimatycznych 
</span>

#### Cel projektu oraz jego znaczenie <i class="fa-solid fa-bullseye"></i>
<p style="text-align: justify;"> Celem projektu jest opracowanie nowej metody monitorowania ruchów lodowców z wykorzystaniem danych SAR i uczenia maszynowego. Łącząc technikę Offset-Tracking (OT) i DInSAR z obrazami SAR o wysokiej rozdzielczości, przeanalizuje zmiany w kinematyce lodowca, wykryje anomalie i oceni trendy prędkości na Grenlandii i Svalbardzie. Badania obejmują testowanie algorytmów uczenia maszynowego w celu optymalizacji oceny przemieszczeń, a następnie analizy porównawcze z wykorzystaniem oprogramowania GIS. Ostatecznym celem jest zapewnienie dokładniejszego i skuteczniejszego sposobu monitorowania zachowania lodowców i zmian środowiskowych.</p>

<hr style="border:1px solid black">

#### Plan badań <i class="fa-solid fa-list-check"></i>

**Zadanie 1. Zbieranie satelitarnych obrazów radarowych dla wybranych obszarów badawczych**
<p style="text-align: justify;">Badania będą prowadzone na grupach lodowców w dwóch głównych regionach: Grenlandii i Svalbardu. Na Grenlandii uwaga zostanie zwrócona na zachodnie wybrzeże, w szczególności na następujące lodowce: Jakobshavn (najwyższe prędkości na Grenlandii), Sermaq (występowanie basenów zapadliskowych) i Petterman (problemy hydrologiczne z rzekami, które destabilizują lodowiec). Lodowce Nathorstbreen, Kronebreen i Hansbreen będą szczególnie badane w regionie Svalbard, który charakteryzuje się mniejszymi prędkościami w porównaniu z Grenlandią. Zbierane będą obrazy radarowe z satelity Sentinel-1, ponieważ są one dostępne bezpłatnie i w regularnych odstępach czasu. Ponadto, w zależności od dostępności danych, planowane jest wykorzystanie zestawów danych o wysokiej rozdzielczości z dobrze znanych (Cosmo-SkyMed, TerraSAR-X) lub nowo opracowanych misji SAR (ICEYE, RCM, Capella Space lub NISAR), które mogą być przydatne na obszarach o wolniejszych ruchach lub mniejszym zasięgu przestrzennym.</p>

**Zadanie 2. Przetwarzanie danych SAR z wykorzystaniem klasycznych metod obliczeniowych**
<p style="text-align: justify;">W drugim etapie zebrane zbiory danych SAR zostaną przetworzone za pomocą takich metod jak DInSAR i OT w celu uzyskania informacji o polu przemieszczenia w wybranych regionach. Dodatkowo, obliczenia zostaną ulepszone poprzez wykorzystanie pola przesunięcia do poprawy analizy DInSAR w celu wykrycia lokalnych deformacji. Podejście to znajduje zastosowanie w obszarach trzęsień ziemi, jednak nie jest powszechnie stosowane w monitorowaniu lodowców. W rezultacie informacje o przemieszczeniach poziomych i LOS zostaną uzyskane dla każdego obszaru badawczego.</p>

**M1 – pierwszy kamień milowy: charakterystyka pola przemieszczeń pozyskana na podstawie danych SAR**

**Zadanie 3. Tworzenie nowego algorytmu w oparciu o uczenie maszynowe**
<p style="text-align: justify;">Wstępnie przetworzone dane SAR zawierające informacje fazowe, spójność, amplitudę sygnału i współczynnik rozproszenia wstecznego zostaną wykorzystane jako dane wejściowe do testowania różnych modeli ML i jako efekt do stworzenia optymalnego algorytmu wykrywania pełnego pola przemieszczenia. Różne modele ML i ich parametry zostaną przetestowane w celu uzyskania najlepszej jakości wyników. Każdy model zostanie oceniony na podstawie statystyk obliczonych po każdej epoce.</p>

**Zadanie 4. Zbieranie danych referencyjnych oraz ich analiza**
<p style="text-align: justify;">Zbierane i analizowane będą informacje o lodowcach z niezależnych baz danych. Na obszarze Grenlandii zbadane zostaną następujące bazy danych: MEaSUREs, CPOM Near Real-Time i Promice. W przypadku Svalbardu zbadane zostaną trzy zbiory danych: z Uniwersytetu w Oslo, norweskiego serwisu Copernicus Glacier oraz Polskiej Bazy Danych Polarnych ze stacji polarnej Hornsund. Bazy te zawierają różne informacje, takie jak prędkość, pozycja końcowa, bilans masy lub pomiary in situ z lasek ablacyjnych lub stacji meteorologicznych. Część tych zbiorów danych zostanie wykorzystana do analizy dynamiki lodowców, natomiast część danych zawierających informacje o prędkościach lub przemieszczeniach posłuży do sprawdzenia poprawności nowo opracowanej metody.</p>

**Zadanie 5. Walidacja nowego algorytmu**
<p style="text-align: justify;">Na tym etapie wyniki uzyskane przy użyciu standardowego podejścia i nowej metody zostaną porównane z wartościami ruchu z niezależnych baz danych. W przypadku braku danych, jako punkt odniesienia wykorzystane zostaną wyniki klasycznych obliczeń. W rezultacie wybrany zostanie najlepszy algorytm i przygotowany do wykorzystania w dalszych badaniach, w tym długoterminowej analizie przemieszczeń.</p>

**M2 – drugi kamień milowy: zbudowany oraz zwalidowany algorytm**

**Zadanie 6. Analiza dynamiki wybranych lodowców**
<p style="text-align: justify;">Narzędzia stworzone w Zadaniu 5 pozwolą na długoterminową analizę dynamiki lodowców. Pełne pole przemieszczeń zostanie przeanalizowane w długich okresach czasu, aby określić, jak wybrane lodowce zmieniają się w czasie. Szczególna uwaga zostanie zwrócona na znalezienie obszarów i dat, w których wystąpiły zapadliska. Analizowane będzie również, kiedy pojawia się okres przyspieszenia i czy istnieje jakakolwiek zależność między przemieszczeniami poziomymi i LOS w czasie. Pozwoli to również na ciągłe monitorowanie lodowców i wykrywanie ewentualnych anomalii w trendach ich dynamiki.</p>

**M3 - trzeci kamień milowy: informacje o fizyce zjawiska, prcesach zachodzących na wybranych lodowcach**

<hr style="border:1px solid black">

### Postęp & Wyniki częściowe <i class="fa-solid fa-bars-progress"></i>

**Materiały pokonferencyjne:**\
"Training Dataset for the Machine Learning Approach in Glacier Monitoring Applying SAR Data" - Ł. Piwowar, M. Łucka, W. Witkowski\
Przeczytaj więcej: [tutaj](https://ieeexplore.ieee.org/document/10281675)

**Artykuły:**\
"Investigation of machine learning algorithms to determine glaciers displacements" - M. Łucka\
Remote Sensing Applications: Society and Envrionment, 2025\
Przeczytaj więcej: [tutaj](https://doi.org/10.1016/j.rsase.2025.101476)

**Kody i przykładowe dane:**\
Wypróbuj nowy algorytm wykrywania ruchów poziomych korzystający z konwolucyjnych sieci neuronowych (Łucka, 2025)!\
<i class="fa-brands fa-github"></i>     https://github.com/magdalucka/TrackOff  <i class="fa-brands fa-github"></i>

Zaproponowany schemat działania:
<p align="center">
    <img src="../workflow.png">

Przykładowe wyniki dla danych syntetycznych - zdjęcie przesuniete wzajemnie o wektor [-10,-3]:
<p align="center">
    <img src="../syntheticdata.png">

Przykładowe wyniki dla danych rzeczywistych - zobrazowania radarowe lodowca Daugaard-Jensen (Grenlandia):
<p align="center">
    <img src="../DJ_data.png">