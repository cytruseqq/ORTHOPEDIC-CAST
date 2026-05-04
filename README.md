# 🦴 Dedykowane Unieruchomienie Ortopedyczne – Model 3D

> Projekt wizualizacji dedykowanego usztywnienia ortopedycznego (ortezy) na model ręki ludzkiej, wykonany w programie \*\*Blender\*\* w ramach zajęć z Tworzenia Modeli Wyrobów Medycznych (P2 – 2026L).

\---

## 📋 Opis projektu

Projekt dotyczy modelowania **indywidualnego unieruchomienia ortopedycznego** przeznaczonego dla pacjenta po złamaniu prawej ręki w dalszej części **kości promieniowej bez przemieszczenia**.

Po nastawieniu złamania zastosowano dedykowane usztywnienie zapewniające prawidłowy proces gojenia. Model został opracowany na podstawie rzeczywistych danych anatomicznych, z zachowaniem wymogów klinicznych co do zakresu unieruchomienia i geometrii wyrobu.

\---

## 🩻 Scenariusz kliniczny

|Parametr|Opis|
|-|-|
|**Pacjent**|Złamanie prawej ręki|
|**Lokalizacja złamania**|Dalsza część kości promieniowej|
|**Typ złamania**|Bez przemieszczenia|
|**Zastosowanie**|Unieruchomienie dedykowane po nastawieniu|
|**Zakres usztywnienia**|Od głów kości śródręcza do okolicy poniżej zgięcia łokciowego|

\---

## 🖼️ Galeria modelu

### Widok od strony wewnętrznej

!\[Cast – widok 1](Photos/cast1.png)

Orteza obejmuje całą powierzchnię dłoniową i grzbietową przedramienia. Widoczna siatka trójkątna zapewniająca wentylację oraz zmniejszenie masy konstrukcji.

\---

### Widok boczny – strona łokciowa

!\[Cast – widok 2](Photos/cast2.png)

Widok z boku przedstawiający pełny zasięg unieruchomienia od nadgarstka wzdłuż całego przedramienia. Kratownicowa struktura otworów rozmieszczona równomiernie na całej powierzchni.

\---

### Widok od strony grzbietowej

!\[Cast – widok 3](Photos/cast3.png)

Grzbietowa część ortezy z wyraźnie zaznaczoną strukturą siatkową. Model szczelnie otacza anatomię ręki, zapewniając stabilizację stawu nadgarstkowego.

\---

### Widok z otwarciem konstrukcji

!\[Cast – widok 4](Photos/cast4.png)

Widok prezentujący dwuczęściowy charakter ortezy – model rozłożony na połówki, co ilustruje sposób zakładania i zdejmowania usztywnienia.

\---

## ⚙️ Parametry techniczne modelu

|Parametr|Wartość|
|-|-|
|**Grubość ścianki**|3–5 mm|
|**Wzór otworów**|Siatka trójkątna|
|**Odstępy między otworami**|5–15 mm|
|**Stabilizacja**|Staw nadgarstkowy|
|**Zakres proksymalny**|Tuż poniżej zgięcia łokciowego|
|**Zakres dystalny**|Głowy kości śródręcza|

\---

## 🛠️ Metodologia i narzędzia

Projekt zrealizowano w **programie Blender**, zgodnie z wytycznymi zadania P2. Proces tworzenia obejmował:

1. **Selekcja modelu ręki** – wyodrębnienie powierzchni prawej ręki z danych medycznych DICOM (`NormalRightArmDICOM.zip`)
2. **Czyszczenie i wygładzanie** – usunięcie artefaktów, wypełnienie ubytków siatki, wygładzenie powierzchni
3. **Kalibracja wymiarów** – weryfikacja zgodności modelu z rzeczywistymi wymiarami anatomicznymi
4. **Modelowanie ortezy** – nałożenie offsetu na powierzchnię ręki (3–5 mm), odcięcie zakresu unieruchomienia
5. **Perforacja kratownicowa** – wycięcie siatki trójkątnej w celu redukcji masy i poprawy wentylacji
6. **Wygładzenie krawędzi** – zaokrąglenie i zamknięcie krawędzi wyrobu dla bezpieczeństwa użytkowania

\---

## 📁 Struktura projektu

```
📦 projekt/
├── 📂 Photos/                  # Rendery modelu usztywnienia
│   ├── cast1.png               # Widok od strony dłoniowej
│   ├── cast2.png               # Widok boczny – strona łokciowa
│   ├── cast3.png               # Widok od strony grzbietowej
│   └── cast4.png               # Widok z otwarciem konstrukcji
├── hand.blend                  # Projekt Blender – model ręki + orteza
├── hand.stl                    # Model 3D ręki (eksport STL)
└── hand\_cast.stl               # Model 3D usztywnienia (eksport STL)
```

\---

## 🚀 Jak otworzyć projekt

1. Zainstaluj [Blender](https://www.blender.org/download/) (zalecana wersja 3.x lub nowsza).
2. Sklonuj lub pobierz repozytorium:

```bash
   git clone https://github.com/TWOJ\_LOGIN/NAZWA\_REPO.git
   ```

3. Otwórz plik projektu w Blenderze:

```
   File → Open → hand.blend
   ```

4. Pliki STL można zaimportować do dowolnego oprogramowania do druku 3D (np. Cura, PrusaSlicer) lub CAD (np. Autodesk Fusion):

```
   File → Import → Stl (.stl) → hand.stl / hand\_cast.stl
   ```

\---

## 📚 Literatura i odniesienia

* [3D-printed short arm casts – reliability, validity, feasibility](https://www.researchgate.net/publication/364438704_3D-printed_short_arm_casts_reliability_validity_feasibility_compared_with_conventional_waterproof_fiberglass_casts)
* [Design of a Patient Specific 3D printed Arm Cast](https://www.researchgate.net/publication/313654100_Design_of_a_Patient_Specific_3D_printed_Arm_Cast)
* [Blender – tutorial modelowania ortezy (3DWASP)](https://www.youtube.com/watch?v=lKnBd6LXo7A)

\---

## 👤 Autor

**Adrian Witów**

Projekt wykonany w ramach przedmiotu **Tworzenie Modeli Wyrobów Medycznych – P2 (2026L)**.

\---

## 📄 Licencja

Projekt stworzony w celach edukacyjnych. Wszelkie prawa zastrzeżone © Adrian Witów.

