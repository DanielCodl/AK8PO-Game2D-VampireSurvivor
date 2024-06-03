# Game Design Document: Vampire Survivor

## 1. Přehled hry
### 1.1 Název hry
**Vampire Survivor**

### 1.2 Popis hry
Vampire Survivor je jednoduchá 2D střílečka zasazená do post-apokalyptického světa, který je zaplaven upíry. Hráč se ujímá role dobrovolníka ozbrojeného pistolí s nabitými stříbrnými kulkami a jeho úkolem je přežít vlny upírů, kteří přicházejí ze všech směrů. Hra obsahuje automatické střílení a hráč se pohybuje pomocí klávesových zkratek. Hra je vyvinuta v systému Godot 4.2.

### 1.3 Cíl hry
Hlavním cílem je přežít co nejdéle a zničit příchozí vlny upírů. Hra je navržena tak, aby ukázala základní dovednosti ve vývoji her a zaujala návštěvníky dne otevřených dveří na FAI UTB ve Zlíně, zejména ty, kteří mají zájem o studium informatiky.

### 1.4 Cílová skupina
Návštěvníci dne otevřených dveří na FAI UTB ve Zlíně, zejména zájemci o studium informatiky.

### 1.5 Informace o vývojáři
**Autor:** Daniel Codl  
**Role:** Projektový manažer, vývojář, tester, marketér

## 2. Herní mechaniky
### 2.1 Ovládání hráče
- **Pohyb:** 
  - `W` - Pohyb nahoru
  - `A` - Pohyb doleva
  - `S` - Pohyb dolů
  - `D` - Pohyb doprava
- **Střelba:** Automatická (nevyžaduje vstup hráče)

### 2.2 Chování nepřátel
- **Upíři:**
  - Upíři se náhodně generují v předem daných intervalech pomocí časovače.
  - Pohybují se směrem k postavě hráče ze všech směrů.
  - Při kolizi s hráčem se snižuje hráčovo zdraví.

### 2.3 Bodovací systém
- Body jsou udělovány za každého zničeného upíra.
- Cílem je dosáhnout co nejvyššího skóre před tím, než hráče přemohou.

### 2.4 Systém zdraví
- Hráč má určité množství zdraví.
- Zdraví se snižuje při kolizi s upírem.
- Hra končí, když zdraví hráče dosáhne nuly.

## 3. Technické specifikace
### 3.1 Vývojová platforma
- **Engine:** Godot 4.2

### 3.2 Grafika
- **Styl:** 2D pixelová grafika
- **Sprite hráče:** Jednoduchá lidská postava s pistolí.
- **Sprite upíra:** Různé designy upírů pro vizuální rozmanitost.

### 3.3 Zvuk
- Hudba na pozadí pro vytvoření strašidelné atmosféry.
- Zvukové efekty pro střelbu a zničení upíra.

### 3.4 Výkon
- Optimalizováno pro plynulý výkon na standardních PC.
- Minimální doba načítání a responzivní ovládání.

## 4. Průběh hry
### 4.1 Hlavní menu
- **Start hry:** Spustí hru.
- **Instrukce:** Zobrazí ovládání a cíl hry.
- **Konec:** Ukončí hru.

### 4.2 Ve hře
- **HUD:** Zobrazuje hráčovo skóre a zdraví.
- **Herní oblast:** Hráč se pohybuje a bojuje v omezeném prostoru, do kterého přicházejí upíři ze všech stran.

### 4.3 Konec hry
- Zobrazí konečné skóre hráče.
- Možnost restartovat hru nebo se vrátit do hlavního menu.

## 5. Časový harmonogram vývoje
### 5.1 Předprodukce
- **Vývoj konceptu:** 1 týden
- **Tvorba herního designového dokumentu:** 1 týden

### 5.2 Produkce
- **Programování:** 2 týdny
- **Design grafiky a zvuku:** 1 týden
- **Integrace a testování:** 1 týden

### 5.3 Postprodukce
- **Finální testování:** 1 týden
- **Marketing a propagace:** Před událostí

## 6. Marketingová strategie
### 6.1 Zapojení cílové skupiny
- Představit hru během dne otevřených dveří na FAI UTB ve Zlíně.
- Ukázat proces vývoje hry potenciálním studentům informatiky.

### 6.2 Propagační materiály
- Plakáty a letáky s informacemi o hře a screenshoty.
- Živé demonstrace a možnost vyzkoušet si hru během události.

## 7. Závěr
Vampire Survivor je jednoduchá, ale poutavá 2D střílečka navržená tak, aby ukázala základní koncepty vývoje her a zaujala návštěvníky dne otevřených dveří. Hra poskytuje vzrušující výzvu pro hráče a zároveň představuje potenciál studia informatiky na FAI UTB ve Zlíně.