#Portfolio – Unity / Godot / C# Game Projects / C# Desktop Projects

# I. Aplikacje / Projekty Programistyczne

Zbiór aplikacji wykonanych w C#.

---

# 1. Biblioteczka Domowa – aplikacja desktopowa
**Opis:** Aplikacja desktopowa umożliwiająca przeglądanie, dodawanie, edytowanie i usuwanie książek. Aplikacja napisana w C# i w technologii WPF, dane zapisywane w pliku JSON.

**Funkcje:**
- Wyszukiwanie po tytule i autorze 
- Dynamiczna lista książek
- Formularz dodawania i edytowania książek
- Możliwość przeglądania i usuwania książek
- Zapisywanie książek do pliku JSON (bazy danych)

**Repo:** [https://github.com/Konczlap/Biblioteczka_Domowa](https://github.com/Konczlap/Biblioteczka_Domowa)

---

# 2. Mastermind – gra logiczna w konsoli
**Opis:** Aplikacja konsolowa implementująca grę logiczną Mastermind. Gracz próbuje odgadnąć czteroznakowy szyfr wylosowany z puli sześciu symboli (@#$%&*) w maksymalnie 10 rundach. Po każdej próbie gracz otrzymuje informację zwrotną w postaci znaków O (symbol i pozycja poprawna) oraz N (symbol poprawny, ale w złej pozycji). Projekt zawiera również testy jednostkowe weryfikujące działanie logiki gry.

**Funkcje:**
- Losowanie szyfru na początku gry
- Zgadywanie czteroznakowego szyfru
- System informacji zwrotnej O/N
- Ograniczenie liczby prób do 10
- Testy jednostkowe logiki gry

**Repo:** [https://github.com/Konczlap/Mastermind/tree/main/Testowanie_Aplikacji](https://github.com/Konczlap/Mastermind/tree/main/Testowanie_Aplikacji)

---

# II. Game Development – Unity

Zbiór projektów wykonanych w Unity 2D i 3D, rozwijanych samodzielnie ponad materiał kursowy.

---

# 1. Zombie Runner – FPS 3D
**Opis:** Gra typu FPS, w której gracz eksploruje mapę w poszukiwaniu bunkra i walczy z przeciwnikami, korzystając z czterech rodzajów broni (pistolet, karabin, shotgun, snajperka).

**Moje rozszerzenia:**
- UI: pasek baterii latarki  
- UI: pasek życia gracza
- Przejście poziomu (ucieczka samochodem)
- Dźwięki poruszania postaci i strzelania
- Funkcja wyłączająca bunkier gdy Gracz go nie widzi (oszczędzanie FPS)
- Modyfikacja zoomu dla broni z animacją
- Nowe tekstury dla pistoletu, shotguna i snajperki  
- Poprawiona czytelność i prezentacja UI  

**Repo:** [https://github.com/Konczlap/ZombieRunner](https://github.com/Konczlap/Zombie-Runner)

---

# 2. Delivery Driver – 2D Top-Down
**Opis:** Gra 2D, w której gracz wciela się w kuriera dostarczającego paczki po mieście.

**Moje rozszerzenia i funkcje:**
- Zmodyfikowany system poruszania pojazdu
- Stacja paliw + system tankowania
- Pasek paliwa w UI  
- Prędkościomierz wyświetlany w UI
- Pojemność samochodu (ile paczek można przewozić jednocześnie)  
- Portfel gracza + wyświetlanie pieniędzy w UI  
- Mini-mapa  
- **Pełny GameLoop dnia:**  
  - losowe rozmieszczenie paczek i klientów każdego dnia  
  - losowanie wartości paczek  
  - po dostarczeniu wszystkich paczek wraca się do punktu startowego, aby przejść do następnego dnia
  - dni są liczone
- **System zapisu i wczytywania gry** w dowolnym momencie  

**Repo:** [https://github.com/Konczlap/Deliver-Driver](https://github.com/Konczlap/Deliver-Driver)

---

# 3. TileVania – Platformer 2D
**Opis:** Klasyczna platformówka 2D, w której gracz steruje wojowniczą żabą pokonującą przeszkody i przeciwników.

**Moje dodatki:**
- Użycie innych niż w kursie darmowych assetów
- Stworzenie własnych poziomów
- Projekt rozszerzony o własne poprawki wizualne i gameplayowe (modyfikacje drobne).  

**Repo:** [https://github.com/Konczlap/TileVania](https://github.com/Konczlap/TileVania)

---

# III. Game Development – Godot

Projekt zespołowy wykonany w ramach zajęć na studiach w metodyce Agile.

# 1. Symulator Kuriera – 2D Top-Down
**Opis:** Gra 2D, w której gracz wciela się w kuriera rozwożącego paczki po mieście.

**Mój wkład:**
- Systemu poruszania pojazdu
- Mechaniki podnoszenia i dostarczania paczek
- System zarobków za dostawy
- Systemu paliwa (zużycie, tankowanie)
- Ograniczenie pojemności pojazdu
- Implementacja systemu czasu i GameLoop (dzień, zakończenie dnia, podsumowanie)
- System zapisu i wczytywania gry (autosave, reset dnia)
- Współpraca w zespole w metodyce Agile (podział zadań, iteracje)


**Projekt zawierał m.in.:**
- System sklepu (kupowanie różnych pojazdów o różnych parametrach)
- Mini mapa
- System wskazywania paczek do zebrania
- System wskazywania kierunku do klientów podniesionych paczek
- System świateł samochodu
- System pogody
- System dźwięków w grze

**Repo:** [https://github.com/Konczlap/Godot_Game](https://github.com/Konczlap/Godot_Game)

---