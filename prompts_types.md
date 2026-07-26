- ==**RTF (Role → Task → Format)**==
  collapsed:: true
	- **Zastosowania**
	  Ekspert finansowy przygotowuje analizę trendów giełdowych w formie tabeli.
	  Nauczyciel historii tworzy streszczenie wybranej epoki w punktach.
	  Trener fitness układa plan treningowy opisany w punktach dziennych.
	  Konsultant HR opracowuje instrukcję wdrożenia pracownika w formie listy kroków.
	  Szef kuchni przedstawia przepis na makaron w formie wykazu składników i kroków.
	- **Definicja**
	  ```
	  Pełnij rolę: [ROLA]
	  Twoje zadanie: [ZADANIE]
	  Format odpowiedzi: [FORMAT]
	  Kontekst / dane wejściowe: [KONTEKST]
	  ```
	- **Zasady**
		- 1. **Rola decyduje o stylu języka** – im precyzyjniej ją nazwiesz, tym lepiej (np. „UX-researcher” > „ekspert”).
		  2. **Zadanie **= czynność + kryteria jakościowe (długość, ton, struktura).
		  3. **Format** ratuje przed długimi blokami tekstu – wymuś tabele, JSON, listy.
		  4. Zacznij od wersji minimum, a potem dopytuj model: „Rozwiń punkt 2”, „Podaj 3 kolejne przykłady”.
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  1. *Plan posiłków na 5 dni*
		  Chcesz, aby dietetyk przygotował jadłospis na 5 dni dla osoby aktywnej, przy założeniu 2300 kcal dziennie. Format ma być tabelaryczny (dzień, śniadanie, obiad, kolacja, kaloryczność). Nie masz alergii i lubisz kuchnię włoską.
		  2. *Motywacyjny cytat na rano*
		  Potrzebujesz krótkiego (do 20 słów) motywacyjnego cytatu na dobry początek dnia, napisanego przez coacha motywacyjnego. Cytat ma być w formie prostego tekstu, a kontekst to praca zdalna i czasem pojawiająca się prokrastynacja.
		  3. *10-minutowy trening bez sprzętu*
		  Chcesz, aby trener personalny ułożył 10-minutowy trening bez sprzętu, zawierający rozgrzewkę i rozciąganie. Ma to być lista numerowana (ćwiczenie – czas). Mieszkasz w bloku, jesteś początkujący.
		- ***Top 3 zastosowania w pracy***
		  1. *Miniatura do YouTube*
		  Potrzebujesz 5 pomysłów na chwytliwą miniaturkę do filmu „ChatGPT vs Gemini”, zaproponowanych przez kreatywnego designera. Opisy mają być przygotowane pod mockupy. Film porównuje wady i zalety obu narzędzi.
		  2. *Lead do newslettera*
		  Chcesz, by specjalista od e-mail marketingu napisał entuzjastyczny lead (do 60 słów) do newslettera o nowej bibliotece promptów. Odbiorcami są marketerzy.
		  3. *Post na Facebooka promujący e-book*
		  Potrzebujesz posta na FB promującego e-book „100 promptów AI”, stworzonego przez social media managera. Post ma być emoji-friendly, zawierać CTA, mieć do 100 słów i 3 hashtagi. Grupa docelowa to małe biznesy.
- ==**TAG (Task → Action → Goal)**==
  collapsed:: true
	- **Zastosowania**
	  Opracuj raport, wyciągnij kluczowe wnioski, aby pomóc w decyzji.
	  Stwórz quiz, wygeneruj pytania, by sprawdzić wiedzę uczniów.
	  Zaproponuj menu, wskaż najlepsze zestawienia smaków, aby zwiększyć sprzedaż w restauracji.
	  Przygotuj bazę danych, załaduj dane klientów, aby usprawnić obsługę klienta.
	  Przygotuj opis stanowiska, podświetl wymagania, by ułatwić rekrutację.
	- **Definicja**
	  ```
	  Task (co zrobić): [ZADANIE]
	  Action (jak to zrobić): [DZIAŁANIA / NARZĘDZIA]
	  Goal (cel końcowy): [OCZEKIWANY REZULTAT]
	  Kontekst / dane wejściowe: [KONTEKST]
	  ```
	- **Zasady**
		- 1. **Task = jedno, konkretne zadanie** – bez „i jeszcze”.
		  2. **Action** precyzuje proces: narzędzia, techniki, styl pracy.
		  3. **Goal** musi być mierzalny lub jednoznaczny (liczba, deadline, %).
		  4. Dodaj **kontekst**, gdy wynik zależy od branży czy grupy odbiorców.
		  5. Gdy model „pływa”, skróć Action do 1 zdania i podbij Goal liczbami.
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  1. *Usprawnienie porannej rutyny*
		  Chcesz zaplanować swoje poranne czynności tak, by całość trwała 30 minut, wykorzystując technikę habit stacking. Celem jest energiczne rozpoczęcie dnia i punktualny start o godzinie 7:00. Pracujesz z domu i masz dwójkę dzieci.
		  2. *Zdrowsze przekąski do pracy*
		  Potrzebujesz propozycji pięciu fit-przekąsek, każda do 150 kcal, bazujących na produktach dostępnych w Lidlu lub Biedronce. Nie masz alergii, a w biurze nie możesz korzystać z piekarnika.
		  3. *Szybkie ćwiczenia oddechowe*
		  Chcesz uzyskać prostą, 5-minutową sesję oddechową z instrukcją krok po kroku i rozpisanymi timingami, by zredukować stres przed spotkaniem online. Pracujesz głównie siedząco.
		  ***Top 3 zastosowania w pracy***
		  1. *SEO tytuł wpisu blogowego*
		  Potrzebujesz trzech propozycji tytułów artykułu o GPT-4o w e-commerce. Chcesz, by zawierały słowa kluczowe „AI” i „sprzedaż online” oraz osiągały CTR powyżej 8% w Google. Grupą docelową są właściciele sklepów.
		  2. *Sekwencja kampanii e-mailowej*
		  Zależy Ci na przygotowaniu sekwencji trzech maili powitalnych, opartych na storytellingu i jednym CTA, których celem jest konwersja subskrybenta w pierwszą sprzedaż w ciągu 7 dni. Kontekst to kurs online „Podstawy prompt-engineeringu”.
		  3. *Raport KPI do prezentacji zarządu*
		  Chcesz podsumować wyniki za Q2 w formie prezentacji PowerPoint z wykresami (przychód, CAC, LTV). Potrzebujesz maksymalnie 10 slajdów, korzystając z danych zawartych w arkuszu Excel (link do pliku).
- ==**BAB (Before → After → Bridge)**==
  collapsed:: true
	- **Zastosowania**
	  Opisz sytuację klienta przed i po wdrożeniu usługi oraz wyjaśnij, jak do tego doszło.
	  Przedstaw stan firmy przed digitalizacją, po jej wdrożeniu i omów proces tej transformacji.
	  Opisz poziom wiedzy ucznia przed i po szkoleniu oraz metody wsparcia tego rozwoju.
	  Zilustruj kondycję zdrowotną przed rozpoczęciem diety, wyniki po i kluczowe zmiany żywieniowe.
	  Wskaż wydajność systemu przed optymalizacją, po niej oraz podaj listę zastosowanych usprawnień.
	- **Definicja**
	  ```
	  Before (obecna sytuacja / problem): [PRZED]
	  After  (pożądany rezultat):          [PO]
	  Bridge (co zrobić krok po kroku):    [DZIAŁANIA]
	  
	  Kontekst / ograniczenia: [INFO]
	  ```
	- **Zasady**
		- 1. **Before** opisuj faktami (dane, obserwacje) – zero ocen.
		  2. **After** zrób SMART: liczby, daty, parametry jakości.
		  3. **Bridge** = konkretne kroki lub narzędzia; jeśli to lista, poproś o kolejność priorytetową.
		  4. Dodaj **kontekst** (zasoby, budżet, ograniczenia), żeby most był realistyczny.
		  5. Przy dużych celach rozbij Bridge na milestone’y i poproś o KPI do monitorowania.
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  1. Poranne pobudki
		  Obecnie wstajesz zmęczony o 7:30, a chcesz zacząć dzień pełen energii już o 6:30. Potrzebujesz 14-dniowego planu snu i porannych rytuałów, dostosowanego do pracy zdalnej i opieki nad dwójką małych dzieci.
		  2. Wdzięczność na co dzień
		  Zauważasz, że często wieczorami narzekasz, a chciałbyś codziennie dostrzegać 3 dobre rzeczy. Szukasz propozycji prostego dziennika wdzięczności z przypomnieniami, który możesz prowadzić na iPhonie i w Notion.
		  3. Zdrowsze kolacje
		  Twoje kolacje to najczęściej gotowe pizze, a chciałbyś jeść zdrowiej – posiłki do 600 kcal, gotowe w 15 minut. Potrzebujesz 5 przepisów wraz z listą zakupów do Lidla, z uwzględnieniem braku piekarnika.
		- ***Top 3 zastosowania w pracy***
		  1. SEO ranking
		  Twoja strona jest obecnie na pozycji w top 30 na frazę „kurs AI”, a celem jest wejście do top 5 w ciągu 90 dni. Potrzebujesz szczegółowej roadmapy SEO, obejmującej audyt, content i link-building, przy budżecie 2000 zł miesięcznie.
		  2. Onboarding nowych pracowników
		  Nowi pracownicy mają trudności z odnalezieniem się w procesach, a Ty chcesz, by byli całkowicie samodzielni w ciągu 2 tygodni. Szukasz checklist i materiałów wideo do wdrożenia w firmie SaaS liczącej 30 osób, pracującej na Slacku.
		  3. Lejek sprzedażowy B2B
		  Obecnie konwersja z leadu na demo wynosi 1%, a chcesz podnieść ją do 3% w trzecim kwartale. Potrzebujesz propozycji optymalizacji e-maili, landing page oraz pomysłów na A/B testy, przy założeniu, że sprzedajesz software dla e-commerce (ICP: B2B).
- ==**CARE (Context → Action → Result → Example)**==]
  collapsed:: true
	- **Zastosowania**
	  Dla sklepu z niską konwersją zaproponuj działania, opisz efekty i daj przykład komunikatu.
	  W środowisku szkolnym wskaż problem, wdrożone rozwiązanie, rezultat i zilustruj konkretną lekcją.
	  Opisz sytuację w zespole, podjęte działania integracyjne, osiągnięty wynik i konkretną aktywność.
	  Przedstaw kontekst spadku motywacji, zastosowane narzędzie, efekt i gotowy szablon do użycia.
	  Dla firmy IT omów wyzwanie, podjęte studia przypadków i finalny przykład wdrożenia
	- **Definicja**
	  ```
	  Context  (tło / problem): [OPIS SYTUACJI]
	  Action   (zadania):        [CO NALEŻY WYKONAĆ]
	  Result   (oczekiwany efekt): [JAKI WYNIK / KPI]
	  Example  (wzór odpowiedzi): [KRÓTKI PRZYKŁAD FORMATU]
	  
	  Ograniczenia / zasoby: [INFO]
	  ```
	- **Zasady**
		- 1. **Context** bezpośrednio z briefu – fakty, branża, odbiorca, zasoby.
		  2. **Action** = lista zadań lub jedno kluczowe polecenie; unikaj „i… i…”.
		  3. **Result** SMART-uj: liczby, daty, metryki („+20 %”, „do końca Q2”).
		  4. **Example** to „kalibracja” – pokaż mikro-fragment idealnego formatu/tonu.
		  5. Gdy AI zbacza, rozbuduj Example albo dorzuć próbkę „co jest OK vs. nie-OK”.
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  1. **Plan nauki języka hiszpańskiego**
		  Pracujesz od 9 do 17 i masz tylko 30 minut dziennie na naukę hiszpańskiego na poziomie A2. Chcesz czterotygodniowego planu micro-lekcji, który pozwoli Ci opanować 200 nowych słówek i podstawy czasu przeszłego. Plan powinien być w formie tabeli na każdy tydzień: dzień, temat, ćwiczenie, czas.
		  2. **Menu na tydzień**
		  Potrzebujesz tygodniowego jadłospisu na diecie 1800 kcal bez glutenu, z listą zakupów. Chcesz, aby każdy dzień zawierał 3 posiłki, a przygotowanie nie zajmowało więcej niż 30 minut. Jadłospis powinien być w formie tabeli z kolumną „kcal”.
		  3. **Poranny newsletter z newsami tech**
		  Chcesz mieć rano przed 8:00 skrót 3 najważniejszych newsów technologicznych z wczoraj, na bazie artykułów z The Verge i Wired. Każde podsumowanie powinno mieć maksymalnie 100 słów i być w formie wypunktowanej listy z linkiem do źródła.
		- ***Top 3 zastosowania w pracy***
		  1. **Analiza rynku**
		  Jesteś w polskim start-upie SaaS HR, planującym ekspansję na rynek DACH. Potrzebujesz analizy konkurencji (ceny, funkcje) w formie raportu PDF (5–7 stron) wraz z tabelą porównawczą (firma vs. funkcje vs. cena).
		  2. **Case study klienta**
		  Twoja firma wdrożyła rozwiązanie AI u klienta X i chcesz napisać case study: opis problemu, rozwiązania oraz wyników, w długości 600–800 słów, w tonie biznesowym, ale przystępnym. Przykład: nagłówki H2, krótkie akapity, 1 cytat klienta.
		  3. **Skrypt cold-call dla audytu SEO**
		  Sprzedajesz usługę audytu SEO dla firm e-commerce i potrzebujesz 60-sekundowego skryptu rozmowy otwierającej, który zwiększy odsetek umówionych demo do 15% leadów. Skrypt w formie dialogu handlowca z klientem, z trzema pytaniami diagnostycznymi.
- ==**RISE (Role → Input → Steps → Expectation)**==
  collapsed:: true
	- **Zastosowania**
	  Pracuj jako marketer, korzystaj z danych kampanii, zaproponuj kolejne kroki i oczekuj wzrostu konwersji.
	  Zostań ekspertem ds. rekrutacji, przeanalizuj CV, przeprowadź selekcję krok po kroku i przedstaw rekomendację.
	  Rola trenera personalnego, wykorzystaj wyniki badań klienta, stwórz plan działania i oczekuj raportu z postępami.
	  Ekspert językowy, użyj próbki tekstu, zaproponuj poprawki, rezultatem jest tekst poprawiony stylistycznie.
	  Doradca podatkowy, wczytaj dane finansowe, sporządź kalkulację podatków i przedstaw praktyczne wnioski.
	- **Definicja**
	  ```
	  Role (kim jesteś):          [ROLA]
	  Input (dane / materiały):   [WEJŚCIE]
	  Steps (instrukcje 1-2-3…):  [KROKI]
	  Expectation (efekt / format / KPI): [OCZEKIWANY WYNIK]
	  ```
	- **Zasady**
		- 1. **Role** ustawia styl i kompetencje – im precyzyjniej (np. „Senior DevOps w FinTech”), tym lepsze decyzje modelu.
		  2. **Input** daj w jednym bloku; AI nie będzie dopytywać o brakujące puzzle.
		  3. **Steps** to instrukcja działania – używaj trybu rozkazującego i kolejności (1-2-3).
		  4. **Expectation** zrób mierzalne lub restrykcyjne: format pliku, limit znaków, KPI, deadline.
		  5. Gdy dostajesz za mało/za dużo, doprecyzuj Input albo zwęź Steps (np. „podaj tylko TOP 5”).
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  1. **Personalny jadłospis na redukcję**
		  Chcesz, by dietetyk sportowy opracował dla Ciebie jadłospis dopasowany do wagi 72 kg i celu redukcji 0,5 kg tygodniowo. Przekazujesz listę ulubionych produktów. Oczekujesz, że specjalista obliczy Twoje zapotrzebowanie kaloryczne (CPM), ułoży menu na 7 dni (po 3 posiłki dziennie) i przygotuje listę zakupów. Efekt: tabela z kalorycznością każdego posiłku i podsumowaniem makroskładników.
		  2. **Weekendowy city-break w Berlinie**
		  Potrzebujesz planera podróży budżetowych, który ułoży szczegółowy, godzinowy plan dwudniowego pobytu w Berlinie. Budżet wynosi 400 euro, a interesujesz się street-artem i kawą speciality. Oczekujesz agendy z rozpiską: dzień, godzina, aktywność, koszt w euro, a także linki do ciekawych miejsc.
		  3. **Poranna rutyna mindfulness**
		  Chcesz, by trener mindfulness zaplanował dla Ciebie 10-minutową poranną rutynę – krótką medytację i dwa ćwiczenia oddechowe, bo masz stresującą pracę w IT. Oczekujesz instrukcji krok po kroku z dokładnym czasem, pozycją i praktycznymi uwagami.
		- ***Top 3 zastosowania w pracy***
		  1. **Artykuł SEO na 1500 słów**
		  Potrzebujesz, by copywriter B2B SaaS napisał artykuł na 1500 słów o „AI w e-commerce”, bazując na briefie, słowach kluczowych, profilach odbiorców i tonie komunikacji. Oczekujesz outline’u, nagłówków H2/H3, pełnej treści gotowej do wrzucenia w CMS oraz meta-tytułu do 60 znaków.
		  2. **Roadmapa produktu**
		  Chcesz, by product manager przygotował roadmapę, mając backlog funkcji, feedback klientów i ograniczenia zespołu (20 SP/iteracja). Oczekujesz priorytetyzacji z wykorzystaniem MoSCoW, rozpisania pracy na 2-tygodniowe sprinty, wyznaczenia kamieni milowych oraz efektu w postaci tabeli (xlsx) i wykresu Gantta do końca Q4.
		  3. **Dashboard KPI**
		  Potrzebujesz, aby analityk danych na podstawie pliku CSV ze sprzedażą z lat 2023–2024 przygotował dashboard KPI z MRR, churnem i CAC. Oczekujesz oczyszczenia danych, policzenia wskaźników, wizualizacji w Looker Studio oraz linku do dashboardu z opisem trzech najważniejszych insightów.
- ==**AIM (Action → Intent → Metric)**==
  collapsed:: true
	- **Zastosowania**
	  Zoptymalizuj treść strony, by zwiększyć czas przebywania, mierz efekty przez średni czas sesji.
	  Skróć proces rekrutacji z zamiarem przyspieszenia decyzji, mierz czas od ogłoszenia do zatrudnienia.
	  Stwórz kampanię reklamową, z celem wzrostu sprzedaży, oceniaj skuteczność przez wzrost przychodów.
	  Zaktualizuj politykę bezpieczeństwa, by zmniejszyć liczbę incydentów, śledź liczbę zgłoszeń po wdrożeniu.
	  Uporządkuj bazę danych, aby poprawić trafność wyszukiwań, mierz procent poprawnych wyników.
	- **Definicja**
	  ```
	  Action  (co wykonać):   [DZIAŁANIE]
	  Intent  (po co / dlaczego): [CEL / UZASADNIENIE]
	  Metric  (jak ocenić sukces): [MIARA / KPI]
	  
	  Kontekst / ograniczenia: [INFO]
	  ```
	- **Zasady**
		- 1. **Action** – jedno klarowne polecenie, unikaj spójników „i”.
		  2. **Intent** – odsłania motywację; pozwala AI dobrać styl i priorytety.
		  3. **Metric** – zawsze liczba, procent, deadline lub zakres znaków.
		  4. Kiedy wynik jest za „miękki”, doszczegółów Metric („≤120 s”, „JSON valid”).
		  5. Przy długich projektach rozbij Metric na kamienie milowe i poproś o review po każdym etapie.
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  1. **Lepszy sen**
		  Chcesz uzyskać propozycję 30-minutowej wieczornej rutyny, której celem jest szybsze zasypianie i budzenie się wypoczętym. Twój wskaźnik sukcesu to zasypianie w maksymalnie 15 minut w ciągu 7 dni.
		  2. **Oszczędzanie na wakacje**
		  Potrzebujesz planu budżetowego według metody 50/30/20, by skuteczniej odkładać pieniądze na wakacje. Miarą sukcesu jest zgromadzenie 1 000 zł w ciągu 3 miesięcy.
		  3. **Nauka słówek po hiszpańsku**
		  Chcesz codziennie otrzymywać listę 20 nowych słów po hiszpańsku wraz z quizem, aby przygotować się do egzaminu na poziomie A2. Celem jest osiągnięcie 90% poprawnych odpowiedzi w tygodniowym teście.
		- ***Top 3 zastosowania w pracy***
		  1. **Post na LinkedIn o trendach AI 2025**
		  Potrzebujesz napisać post o trendach AI na 2025 rok, aby zbudować wizerunek eksperta. Twoją miarą sukcesu jest zdobycie co najmniej 100 reakcji w ciągu 48 godzin.
		  2. **Raport konkurencji w HRTech**
		  Chcesz przygotować porównanie cen pięciu topowych narzędzi SaaS z branży HRTech, by podjąć decyzję o nowej polityce cenowej. Raport ma mieć maksymalnie 5 stron i zawierać wykres porównujący ceny i funkcje.
		  3. **Kampania Facebook Ads dla kursu online**
		  Potrzebujesz zaprojektować 3 kreacje reklamowe wraz z tekstami, by zwiększyć liczbę leadów dla kursu online. Celem jest osiągnięcie kosztu pozyskania leada (CPL) nie wyższego niż 15 zł w pierwszym tygodniu kampanii.
- ==**GRO (Goal → Reason → Output)**==
  collapsed:: true
	- **Zastosowania**
	  Popraw wyniki uczniów, ponieważ spadły w ostatnim semestrze, przedstaw rekomendowane zmiany w programie.
	  Zwiększ zadowolenie klientów, aby ograniczyć rezygnacje, przedstaw plan poprawy obsługi.
	  Wprowadź nowe funkcjonalności, bo klienci o nie pytają, przedstaw listę propozycji rozwoju produktu.
	  Zoptymalizuj koszty produkcji, bo spada rentowność, zaproponuj listę działań oszczędnościowych.
	  Rozwiń kompetencje zespołu, z powodu nowych wymagań rynkowych, przygotuj plan niezbędnych szkoleń.
	- **Definicja**
	  ```
	  Goal   (co chcę osiągnąć):      [CEL]
	  Reason (dlaczego to ważne):     [POWÓD]
	  Output (co ma zostać dostarczone): [OCZEKIWANY EFEKT / FORMAT]
	  
	  Kontekst / ograniczenia: [INFO]
	  ```
	- **Zasady**
		- 1. **Goal** rób jedno-zdaniowy i mierzalny, jeśli to możliwe.
		  2. **Reason** dodaje kontekst biznesowy / osobisty – AI lepiej priorytetyzuje.
		  3. **Output** to konkretny format (tabela, lista, JSON, PDF) + ew. restrykcje długości.
		  4. Gdy dostajesz zbyt ogólną odpowiedź, doprecyzuj Output (np. „użyj bullet-points ≤10 słów”).
		  5. Przy złożonych celach połącz G-R-O z innym frameworkiem (np. RISE dla kroków wykonawczych).
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  1. **Planowanie aktywnego weekendu w Krakowie**
		  Twoim celem jest zaplanowanie aktywnego weekendu w Krakowie, bo odwiedza Cię znajoma z UK i chcesz jak najlepiej wykorzystać wolny czas. Oczekujesz godzinowego harmonogramu z kosztorysem atrakcji i wydatków.
		  2. **Nowa poranna rutyna**
		  Chcesz wprowadzić 20-minutową poranną rutynę, ponieważ czujesz spadek energii i zależy Ci na lepszym starcie dnia. Oczekujesz listy kroków do wykonania wraz z minutnikiem do każdego etapu.
		  3. **Lista książek o nawykach**
		  Poszukujesz 5 książek na temat nawyków, bo przygotowujesz prezentację o samodoskonaleniu. Oczekujesz tabeli z tytułem, autorem i głównym wnioskiem z każdej pozycji.
		- ***Top 3 zastosowania w pracy***
		  1. **Lead magnet: e-book o AI w marketingu**
		  Potrzebujesz tytułu i zarysu e-booka „AI w marketingu”, ponieważ szukasz materiału do generowania leadów przed premierą kursu. Oczekujesz 5 propozycji tytułu oraz spisu treści.
		  2. **Analiza przyczyn churnu w SaaS**
		  Chcesz zrozumieć, dlaczego klienci rezygnują z subskrypcji Twojego SaaS – churn wzrósł do 7% w Q1, a celem jest obniżenie go do 4%. Oczekujesz listy 5 hipotez oraz planu testów A/B, które pozwolą zweryfikować te przyczyny.
		  3. **Opis stanowiska „AI Prompt Engineer”**
		  Musisz przygotować ogłoszenie o pracę na stanowisko „AI Prompt Engineer”, bo planujesz rekrutację w maju. Oczekujesz ogłoszenia o długości 300–400 słów, napisanego przyjaznym i eksperckim tonem.
- ==**FIT (Format → Input → Task)**==
  collapsed:: true
	- **Zastosowania**
	  Przygotuj raport w tabeli na podstawie wyników sprzedaży.
	  Sformatuj odpowiedź jako lista, korzystając z przesłanych notatek.
	  Zastosuj wykres, opracuj na jego podstawie analizę trendów.
	  Przedstaw wynik zadania w formie tekstu ciągłego na podstawie danych z ankiet.
	  Podsumuj analizę w punktach, korzystając z pliku danych.
	- **Definicja**
	  ```
	  Format (struktura wyjścia): [OPIS FORMATU: tabela / JSON / lista / markdown …]
	  
	  Input  (dane do użycia):     [WSZYSTKIE ISTOTNE MATERIAŁY, KONTEKST, LINKI]
	  
	  Task   (główne zadanie):     [POLECENIE W 1 ZDANIU]
	  
	  ```
	- **Zasady**
		- 1. **Format** ustaw na początku – to „ogranicznik kreatywności” modelu.
		  2. **Input** wrzucaj w jednym bloku; brakujące dane = brak precyzji.
		  3. **Task** musi być jednym zdaniem imperatywnym; jeśli są pod-zadania, użyj numeracji.
		  4. Przy dużych datasetach daj link lub próbkę, a w Input doprecyzuj „użyj tylko kolumn A-D”.
		  5. Gdy AI „rozlewa” tekst, zawęź Format (np. „max 50 słów na punkt”) – to natychmiast przycina wodolejstwo.
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  :LOGBOOK:
		  CLOCK: [2025-07-23 Wed 22:48:00]
		  :END:
		  1. **Plan tygodniowych posiłków**
		  Format: tabela (dzień, śniadanie, obiad, kolacja, kcal).
		  Input: preferujesz kuchnię azjatycką, dietę bez nabiału, 2000 kcal dziennie.
		  Task: ułóż jadłospis na 7 dni oraz przygotuj listę zakupów.
		  2. **Checklistę pakowania na city-break**
		  Format: lista punktowana z emoji.
		  Input: wyjazd do Berlina na 3 dni, prognoza 15°C, nocleg w Airbnb z pralką.
		  Task: przygotuj checklistę rzeczy do spakowania.
		  3. **Zestaw ćwiczeń na 15 minut**
		  Format: tabela (ćwiczenie, czas, uwagi).
		  Input: ćwiczenia bez sprzętu, poziom początkujący, cel – wzmocnienie core, trening do wykonania w salonie.
		  Task: zaproponuj 15-minutowy zestaw ćwiczeń.
		- ***Top 3 zastosowania w pracy***
		  1. **Raport konkurencji w HR-tech**
		  Format: tabela (firma, produkt, cena, USP).
		  Input: lista 5 firm SaaS z branży HR-tech wraz z linkami do stron.
		  Task: porównaj funkcje i ceny produktów.
		  2. **Opis stanowiska Senior Prompt Engineer**
		  Format: ogłoszenie o pracę (300–350 słów), podzielone na sekcje: O nas, Zadania, Wymagania, Benefits.
		  Input: notatki od HR oraz kultura firmy „remote-first”.
		  Task: napisz atrakcyjny opis stanowiska (JD).
		  3. **Podsumowanie spotkania (meeting notes)**
		  Format: markdown (Agenda, Decyzje, Action items z osobami i terminami).
		  Input: transkrypcja 20-minutowego calla (link do nagrania).
		  Task: streść najważniejsze ustalenia i przypisz zadania konkretnym osobom z terminami.
- ==**LED (Level → Expectation → Direction)**==
  collapsed:: true
	- **Zastosowania**
	  Na poziomie podstawowym oczekuję prostego wyjaśnienia, kieruj się jasnością i prostotą.
	  Poziom zaawansowany, oczekuję szczegółowego porównania, skup się na złożonych aspektach.
	  Średni poziom, oczekuję konkretnych przykładów, skoncentruj się na praktyce.
	  Ekspercki poziom, oczekuję analizy z referencjami, wskazuj na źródła naukowe.
	  Szkolny poziom, oczekuję kreatywnego rozwiązania, ukierunkuj się na zabawę i motywację.
	- **Definicja**
	  ```
	  Level  (poziom trudności / szczegółowości): [np. „dla początkujących”, „CXO-ready”, „techniczny deep-dive”]
	  Expectation (co ma wrócić):  [np. „podaj 5 pomysłów”, „stwórz outline artykułu”, „wyciągnij 3 insighty”]
	  Direction   (forma / ton / styl):  [np. „luźny, z emoji”, „tabela markdown”, „w stylu Harvard Business Review”]
	  Kontekst / dane wejściowe: [INFO]
	  ```
	- **Zasady**
		- 1. **Level** ustawia „wysokość poprzeczki” – im klarowniej, tym mniej żargonu lub… więcej szczegółów.
		  2. **Expectation** = liczba/forma treści; redukuje ryzyko „ściany tekstu”.
		  3. **Direction** to styl, ton, format – traktuj jak CSS dla promptu.
		  4. Zbyt ogólnie? Zwęź Level („średnio-zaawansowany student CS”) i Direction („tabela 3 kolumny, bez opisów”).
		  5. Przy iteracjach zmieniaj tylko jedną literę – łatwiej debugować efekt.
	- **Przykłady**
		- ***Top 3 zastosowania w użytku codziennym***
		  1. **Przepis dla laików**
		  Poziom: totalny kuchenny noob.
		  Oczekujesz instrukcji przygotowania spaghetti bolognese w 6 krokach, napisanej potocznym językiem i z emoji 🍝.
		  2. **Porada finansowa dla początkujących**
		  Poziom: osoba zaczynająca przygodę z budżetowaniem.
		  Oczekujesz 3 prostych sposobów na oszczędzanie 200 zł miesięcznie, w formie listy numerowanej (maksymalnie jedno zdanie na punkt).
		  3. **Wprowadzenie do AI dla licealisty**
		  Poziom: licealista.
		  Oczekujesz definicji „uczenie maszynowe” w formie metafory i z przykładem z TikToka.
		- ***Top 3 zastosowania w pracy***
		  1. **Brief zarządczy Q1**
		  Poziom: C-level, brak czasu na szczegóły.
		  Oczekujesz podsumowania wyników za Q1 w maksymalnie 120 słowach, formalnie, w punktach.
		  2. **Specyfikacja API dla senior backend developera**
		  Poziom: senior backend dev.
		  Oczekujesz przykładu requestu i response JSON dla endpointu /users, z komentarzami inline w kodzie.
		  3. **Post employer branding dla juniorów**
		  Poziom: kandydaci juniorzy.
		  Oczekujesz 5 powodów, by dołączyć do Twojego zespołu – tekst ma być entuzjastyczny, emoji-friendly i zawierać hashtagi.