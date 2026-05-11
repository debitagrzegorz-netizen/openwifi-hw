# Analiza patentowa – BPL-PLC, sprzęgacze indykcyjne i pojemnościowe oraz potencjalne zastosowanie cewek Rogowskiego

**Data opracowania:** 2026-05-11  
**Cel dokumentu:** przygotowanie poprawionej, ostrożnej metodologicznie wersji analizy patentowej do wykorzystania w dalszych pracach nad raportem dla projektu NCBR.  
**Repozytorium docelowe:** `debitagrzegorz-netizen/openwifi-hw`

---

## 1. Cel i zakres analizy

Niniejszy dokument stanowi poprawioną wersję analizy patentowej odnoszącej się do następujących zagadnień:

1. sprzęgacze sygnałowe dla systemów PLC/BPL,
2. sprzęgacze pojemnościowe stosowane do wprowadzania sygnału do linii energetycznych,
3. sprzęgacze indykcyjne stosowane w systemach transmisji po liniach elektroenergetycznych,
4. rozwiązania monitoringu i diagnostyki medium transmisyjnego,
5. potencjalne wykorzystanie cewek Rogowskiego w otoczeniu systemów PLC/BPL.

W odróżnieniu od wcześniejszego zestawienia, niniejsza wersja:
- **oddziela rzeczywiste patenty od narzędzi wyszukiwawczych i portali pomocniczych**,
- **unika zbyt daleko idących twierdzeń o trafności patentów bez analizy zastrzeżeń**,
- **klasyfikuje pozycje według stopnia powiązania z zakresem projektu**,
- **wyraźnie zaznacza, które patenty są bezpośrednio związane z BPL-PLC, a które mają jedynie znaczenie pomocnicze**.

---

## 2. Metodyka oceny patentów

Każdą pozycję oceniono według następujących kryteriów:

- **Związek z PLC/BPL** – czy patent dotyczy komunikacji po liniach energetycznych, a nie ogólnej elektroniki lub metrologii.
- **Związek ze sprzęganiem sygnału** – czy opisuje układ sprzęgający, urządzenie coupling/coupler/coupling unit lub rozwiązanie funkcjonalnie równoważne.
- **Związek z typem sprzęgacza** – czy możliwe jest przypisanie rozwiązania do klasy sprzęgaczy pojemnościowych, indykcyjnych lub ogólnych.
- **Związek z diagnostyką / jakością sygnału** – czy patent zawiera element pomiaru, monitoringu, klasyfikacji lub estymacji parametrów sygnału.
- **Związek z cewką Rogowskiego** – czy rozwiązanie rzeczywiście odnosi się do cewek Rogowskiego w kontekście PLC/BPL, a nie wyłącznie do ogólnego pomiaru prądu.

Na tej podstawie każdą pozycję zaklasyfikowano do jednej z kategorii:

- **A – bezpośrednio relewantna**,
- **B – częściowo relewantna / wymaga analizy claims**,
- **C – pomocnicza / kontekstowa**,
- **D – nierelewantna dla finalnej analizy patentowej**.

---

## 3. Wyniki audytu i poprawiona analiza patentowa

## 3.1. Patenty dotyczące sprzęgaczy dla PLC/BPL

### [P1] US8593315B2 – *Coupling device for power line communication*  
Link: https://patents.google.com/patent/US8593315B2/en

**Ocena relewancji:** **B – częściowo relewantna / wymaga analizy claims**

**Uzasadnienie:**
Tytuł patentu jednoznacznie wskazuje na związek z komunikacją po liniach energetycznych i urządzeniem sprzęgającym. Jest to wystarczająca podstawa, aby traktować go jako potencjalnie istotny dla analizy stanu techniki w obszarze PLC/BPL. Jednocześnie sam tytuł nie przesądza jeszcze, czy:
- rozwiązanie dotyczy systemów szerokopasmowych BPL,
- sprzęgacz ma charakter pojemnościowy lub indykcyjny,
- zakres obejmuje średnie lub niskie napięcie,
- patent zawiera elementy diagnostyki jakości sygnału.

**Wniosek:**
Patent można uwzględnić w analizie jako pozycję potencjalnie istotną, ale w raporcie końcowym należy opierać się na analizie abstraktu, zastrzeżeń niezależnych oraz klasyfikacji patentowej, a nie wyłącznie na tytule.

---

### [P2] US7982716B2 – *Coupling unit for power line communication*  
Link: https://patents.google.com/patent/US7982716B2/en

**Ocena relewancji:** **B – częściowo relewantna / wymaga analizy claims**

**Uzasadnienie:**
Patent dotyczy jednostki sprzęgającej dla PLC, a więc znajduje się w centrum obszaru zainteresowania projektu. Jednocześnie obecnie nie ma podstaw, by uznać go automatycznie za patent dotyczący konkretnie sprzęgaczy indykcyjnych lub pojemnościowych stosowanych w BPL-PLC. Bez analizy zastrzeżeń ochronnych nie można ustalić, czy opisuje:
- interfejs ogólny dla PLC,
- układ fizycznego sprzęgania do linii,
- obwód dopasowujący,
- czy też zintegrowany blok ochrony i filtracji.

**Wniosek:**
Patent warto zachować w analizie, ale jako źródło **warunkowo istotne**. Powinien zostać zweryfikowany pod kątem zakresu technicznego i typu sprzęgania.

---

## 3.2. Patenty związane z cewkami Rogowskiego

### [P3] EP1763131A1 – *Use of Rogowski coils in power line communication*  
Link: https://patents.google.com/patent/EP1763131A1/en

**Ocena relewancji:** **A/B – potencjalnie bezpośrednio relewantna, ale wymaga obowiązkowej weryfikacji pełnego opisu**

**Uzasadnienie:**
To najbardziej obiecująca pozycja z punktu widzenia związku między cewkami Rogowskiego a PLC. Jeżeli rzeczywisty zakres patentu odpowiada tytułowi i obejmuje wykorzystanie cewki Rogowskiego w systemie power line communication, jest to pozycja bardzo cenna dla projektu. Może ona wskazywać, że pomysł wykorzystania cewki Rogowskiego w otoczeniu PLC nie jest całkowicie nowy, ale jednocześnie pozwala określić:
- jaki był dotychczasowy zakres zastosowania,
- czy dotyczył on sprzęgania, detekcji, monitoringu czy pomiaru,
- czy obejmował ocenę jakości sygnału,
- czy można wskazać nowy, niezastrzeżony obszar rozwojowy.

**Wniosek:**
Patent powinien być potraktowany jako **pozycja priorytetowa do szczegółowej analizy**. Dopiero po sprawdzeniu abstraktu, opisu i claims można ocenić, czy ogranicza przestrzeń innowacyjną projektu, czy tylko dostarcza ważnego punktu odniesienia.

---

### [P4] US20150268495A1 – *High frequency Rogowski coil for current measurement*  
Link: https://patents.google.com/patent/US20150268495A1/en

**Ocena relewancji:** **C – pomocnicza / kontekstowa**

**Uzasadnienie:**
Patent dotyczy wysokoczęstotliwościowej cewki Rogowskiego do pomiaru prądu, co jest ważne z punktu widzenia charakterystyki czujnika i możliwości akwizycji sygnałów szybkozmiennych. Nie ma jednak wystarczających podstaw, by traktować tę pozycję jako patent bezpośrednio odnoszący się do BPL-PLC, sprzęgaczy dla PLC lub oceny jakości sygnału komunikacyjnego.

**Wniosek:**
Patent można przywołać w części dotyczącej potencjału metrologicznego cewki Rogowskiego, ale **nie powinien być prezentowany jako centralny patent sektora BPL-PLC**.

---

## 3.3. Pozycje usunięte z analizy patentowej jako niebędące patentami

### [R1] PATLIB AGH  
Link: https://patenty.bg.agh.edu.pl/

**Ocena relewancji:** **D – nierelewantna jako pozycja patentowa**

**Uzasadnienie:**
PATLIB jest punktem dostępu do informacji patentowej i narzędziem wsparcia wyszukiwania. Nie jest patentem ani dokumentem stanu techniki w sensie merytorycznym.

**Decyzja:**
Usunąć z zasadniczej analizy patentowej. Można pozostawić jedynie w aneksie metodologicznym jako narzędzie wyszukiwawcze.

---

### [R2] Google Patents  
Link: https://patents.google.com/

**Ocena relewancji:** **D – nierelewantna jako pozycja patentowa**

**Uzasadnienie:**
Google Patents jest wyszukiwarką patentową i platformą dostępu do dokumentów patentowych. Nie stanowi samodzielnej pozycji merytorycznej.

**Decyzja:**
Usunąć z listy patentów. Dopuszczalne jest pozostawienie go wyłącznie jako narzędzia badawczego w opisie metodyki.

---

## 4. Kluczowe wnioski z poprawionej analizy patentowej

1. **Jedynie część wcześniej wskazanych pozycji patentowych można uznać za rzeczywiście relewantne dla tematu BPL-PLC.**
2. **Największą wartość dla projektu mają patenty bezpośrednio odnoszące się do coupling device / coupling unit w systemach PLC oraz ewentualnie patenty łączące Rogowski coil z PLC.**
3. **Patenty dotyczące ogólnych cewek Rogowskiego do pomiaru prądu mają znaczenie pomocnicze, a nie centralne.**
4. **Narzędzia wyszukiwawcze i portale patentowe nie mogą być wykazywane jako patenty w analizie stanu techniki.**
5. **Obecny materiał patentowy jest zbyt skromny, by stanowić pełną analizę patentową dla projektu NCBR.** Niezbędne jest wykonanie kolejnej, pogłębionej kwerendy obejmującej:
   - rodziny patentowe,
   - klasy CPC/IPC,
   - zgłaszających,
   - zakres terytorialny,
   - status ochrony,
   - analizę zastrzeżeń niezależnych.

---

## 5. Obszary wymagające dalszej kwerendy patentowej

W celu zbudowania właściwej analizy patentowej do raportu końcowego rekomenduje się dalsze wyszukiwanie w następujących obszarach:

1. **inductive coupler for power line communication**,  
2. **capacitive coupler for power line communication**,  
3. **broadband over power line coupling device**,  
4. **signal injection device for medium-voltage power line communication**,  
5. **non-invasive monitoring of PLC signal on power lines**,  
6. **Rogowski coil in power line communication**,  
7. **high-frequency sensing for PLC diagnostics**,  
8. **channel quality estimation in power line communication systems**.

Wyszukiwanie powinno obejmować co najmniej:
- Google Patents,
- Espacenet,
- WIPO Patentscope,
- oraz – jeśli to możliwe – analizę klas IPC/CPC powiązanych z komunikacją po liniach energetycznych i pomiarem sygnałów HF.

---

## 6. Rekomendacje do raportu NCBR

Do finalnego raportu dla projektu NCBR zaleca się przyjąć następujące zasady:

1. **nie wykazywać narzędzi wyszukiwawczych jako patentów**,  
2. **nie opierać wniosków patentowych wyłącznie na tytułach patentów**,  
3. **oddzielić patenty bezpośrednio związane z BPL-PLC od patentów tylko pomocniczych**,  
4. **wyraźnie oddzielić technologie sprzęgania od technologii pomiarowych**,  
5. **dla cewek Rogowskiego wskazywać ostrożnie, że obecnie wykazano jedynie częściowe przesłanki patentowe dla zastosowań związanych z PLC**,  
6. **traktować przestrzeń innowacyjną projektu nie jako „samą cewkę Rogowskiego”, lecz jako zintegrowany system: czujnik + akwizycja + analiza sygnałowa + estymacja jakości kanału BPL-PLC**.

---

## 7. Podsumowanie

Poprawiona analiza patentowa pokazuje, że wcześniejsze zestawienie wymagało istotnej korekty. Spośród sześciu pozycji umieszczonych pierwotnie w sekcji patentowej:
- dwie pozycje można uznać za **potencjalnie relewantne dla sprzęgaczy PLC/BPL**,
- jedna pozycja jest **potencjalnie bardzo istotna dla wątku Rogowski + PLC**,
- jedna pozycja ma **wyłącznie charakter pomocniczy**,
- dwie pozycje **nie są patentami i nie powinny znajdować się w analizie patentowej**.

Oznacza to, że pełna analiza patentowa dla projektu NCBR wymaga dalszej, pogłębionej kwerendy. Niniejszy dokument stanowi jednak poprawioną podstawę metodologiczną i porządkującą do dalszych prac.
