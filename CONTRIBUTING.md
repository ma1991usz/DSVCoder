# 🤝 Przewodnik Kontrybutora DSVCoder

Dziękujemy za zainteresowanie wkładem w rozwój DSVCoder! 🎉

Ten dokument zawiera wytyczne, które pomogą Ci efektywnie kontrybuować do projektu.

---

## 📋 Spis Treści

- [Kod Postępowania](#-kod-postępowania)
- [Jak Mogę Pomóc?](#-jak-mogę-pomóc)
- [Zgłaszanie Issues](#-zgłaszanie-issues)
- [Pull Requesty](#-pull-requesty)
- [Standardy Kodu](#-standardy-kodu)
- [Proces Review](#-proces-review)
- [Społeczność](#-społeczność)

---

## 📜 Kod Postępowania

### Nasze Zobowiązanie

W interesie wspierania otwartego i przyjaznego środowiska, my jako kontrybutorzy i maintainerzy zobowiązujemy się do tego, aby uczestnictwo w naszym projekcie i społeczności było wolne od nękania dla wszystkich, niezależnie od wieku, budowy ciała, niepełnosprawności, etniczności, tożsamości i ekspresji płciowej, poziomu doświadczenia, narodowości, wyglądu osobistego, rasy, religii lub tożsamości i orientacji seksualnej.

### Nasze Standardy

Przykłady zachowań, które przyczyniają się do tworzenia pozytywnego środowiska:

- ✅ Używanie przyjaznego i inkluzywnego języka
- ✅ Szacunek dla różnych punktów widzenia i doświadczeń
- ✅ Przyjmowanie konstruktywnej krytyki z wdzięcznością
- ✅ Skupienie się na tym, co jest najlepsze dla społeczności
- ✅ Okazywanie empatii wobec innych członków społeczności

Przykłady nieakceptowalnych zachowań:

- ❌ Używanie języka lub obrazów o charakterze seksualnym
- ❌ Trolling, obraźliwe komentarze i ataki osobiste lub polityczne
- ❌ Nękanie publiczne lub prywatne
- ❌ Publikowanie prywatnych informacji innych osób bez wyraźnej zgody
- ❌ Inne zachowania, które mogłyby być uznane za niewłaściwe w środowisku zawodowym

---

## 💡 Jak Mogę Pomóc?

Istnieje wiele sposobów, aby wnieść wkład w DSVCoder:

### 1. 🐛 Zgłaszanie Bugów
Znalazłeś błąd? Pomóż nam go naprawić!

### 2. 💡 Propozycje Funkcjonalności
Masz pomysł na ulepszenie? Podziel się nim!

### 3. 📖 Ulepszanie Dokumentacji
Znalazłeś literówkę? Coś jest niejasne? Pomóż ulepszyć dokumentację!

### 4. 📝 Dodawanie Przykładów
Masz ciekawy case study? Dodaj go do katalogu `examples/`!

### 5. 🔧 Rozwijanie Kodu
Chcesz dodać nową funkcjonalność lub poprawić istniejącą? Śmiało!

### 6. 🌍 Tłumaczenia
Pomóż udostępnić DSVCoder w innych językach!

### 7. ⭐ Promowanie Projektu
Powiedz o DSVCoder innym! Udostępnij, daj gwiazdkę na GitHub!

---

## 🐛 Zgłaszanie Issues

### Przed Zgłoszeniem

1. **Sprawdź istniejące issues** - może ktoś już zgłosił podobny problem
2. **Zaktualizuj do najnowszej wersji** - problem może być już naprawiony
3. **Przygotuj przykład** - pomaga to w reprodukcji problemu

### Zgłaszanie Buga

Użyj tego template do zgłoszenia buga:

```markdown
### Opis problemu
Krótki opis tego, co się stało i czego oczekiwałeś.

### Kroki do reprodukcji
1. Zrób to...
2. Potem to...
3. Zobacz błąd...

### Oczekiwane zachowanie
Co powinno się stać.

### Aktualne zachowanie
Co się faktycznie dzieje.

### Środowisko
- OS: [np. Windows 11, macOS 14, Ubuntu 22.04]
- IDE: [np. VS Code 1.85, IntelliJ IDEA 2023.3]
- GitHub Copilot: [wersja]
- Język programowania: [jeśli dotyczy]

### Dodatkowy kontekst
Screenshoty, logi, lub inne informacje pomocne w zrozumieniu problemu.
```

### Propozycja Funkcjonalności

Użyj tego template do zaproponowania nowej funkcjonalności:

```markdown
### Opis funkcjonalności
Jasny opis proponowanej funkcjonalności.

### Motywacja
Dlaczego ta funkcjonalność jest potrzebna? Jaki problem rozwiązuje?

### Proponowane rozwiązanie
Jak widzisz implementację tej funkcjonalności?

### Alternatywy
Jakie inne rozwiązania rozważałeś?

### Dodatkowy kontekst
Mockupy, diagramy, przykłady z innych projektów, etc.
```

---

## 🔀 Pull Requesty

### Proces Tworzenia PR

1. **Fork repozytorium**
   ```bash
   # Kliknij "Fork" na GitHub
   ```

2. **Sklonuj swój fork**
   ```bash
   git clone https://github.com/TWOJA-NAZWA/DSVCoder.git
   cd DSVCoder
   ```

3. **Stwórz branch dla swojej zmiany**
   ```bash
   git checkout -b feature/moja-funkcjonalnosc
   # lub
   git checkout -b fix/naprawa-buga
   ```

4. **Wprowadź zmiany**
   - Pisz czytelny kod
   - Dodaj komentarze gdzie potrzeba
   - Zaktualizuj dokumentację
   - Dodaj przykłady użycia (jeśli dotyczy)

5. **Commituj z dobrymi komunikatami**
   ```bash
   git add .
   git commit -m "feat: dodaj wsparcie dla Rust w przykładach"
   # lub
   git commit -m "fix: popraw literówkę w instrukcjach Copilot"
   ```

6. **Push do swojego forka**
   ```bash
   git push origin feature/moja-funkcjonalnosc
   ```

7. **Otwórz Pull Request**
   - Idź do oryginalnego repozytorium na GitHub
   - Kliknij "New Pull Request"
   - Wybierz swój branch
   - Wypełnij template PR

### Template Pull Request

```markdown
### Opis zmian
Krótki opis tego, co zostało zmienione i dlaczego.

### Typ zmiany
- [ ] 🐛 Bug fix (non-breaking change)
- [ ] ✨ Nowa funkcjonalność (non-breaking change)
- [ ] 💥 Breaking change (zmiana, która może złamać istniejący kod)
- [ ] 📚 Dokumentacja
- [ ] 🎨 Styling (formatowanie, brakujące średniki, etc.)
- [ ] ♻️ Refactoring (bez zmian funkcjonalności)
- [ ] ⚡ Performance improvement
- [ ] ✅ Test (dodanie lub poprawka testów)

### Checklist
- [ ] Mój kod jest zgodny ze standardami projektu
- [ ] Przeprowadziłem self-review swojego kodu
- [ ] Dodałem komentarze w trudnych miejscach
- [ ] Zaktualizowałem dokumentację
- [ ] Moje zmiany nie generują nowych warningów
- [ ] Dodałem testy weryfikujące moją zmianę
- [ ] Wszystkie testy przechodzą lokalnie

### Powiązane Issues
Fixes #(numer issue)

### Screenshots (jeśli dotyczy)
Dodaj screenshoty pokazujące zmiany.
```

---

## 📏 Standardy Kodu

### Ogólne Zasady

1. **Czytelność > Sprytność**
   - Kod powinien być łatwy do zrozumienia
   - Unikaj zbyt skomplikowanych konstrukcji
   - Dodawaj komentarze wyjaśniające "dlaczego", nie "co"

2. **Spójność**
   - Trzymaj się istniejącego stylu kodu
   - Używaj tych samych konwencji nazewnictwa
   - Zachowuj podobną strukturę do istniejącego kodu

3. **Dokumentacja**
   - Dokumentuj publiczne API
   - Dodawaj przykłady użycia
   - Wyjaśniaj nieoczywiste decyzje

### Dokumentacja (Markdown)

```markdown
✅ DOBRZE:
# Jasny nagłówek

Krótki, zwięzły paragraf wyjaśniający koncepcję.

## Przykład

```python
# Kod z komentarzami
def example():
    pass
```

### Wyjaśnienie
Dokładne wyjaśnienie tego, co kod robi.

❌ ŹLE:
#nagłówek bez spacji

Długi, poplątany tekst bez struktury i formatowania który ciągnie się w nieskończoność...

```kod bez określenia języka
przykład()
```
```

### Instrukcje Copilot

- Używaj jasnych, zrozumiałych sformułowań
- Zawieraj praktyczne przykłady
- Grupuj powiązane koncepcje
- Używaj emoji dla lepszej czytelności (ale nie przesadzaj)
- Testuj instrukcje z Copilotem przed commitowaniem

### Przykłady Kodu

- Zawsze określaj język w blokach kodu
- Używaj angielskiego dla nazw zmiennych i komentarzy w kodzie
- Dodawaj wyjaśnienia po polsku poza blokiem kodu
- Przykłady powinny być kompletne i działające

---

## 🔍 Proces Review

### Co sprawdzamy w PR

1. **Jakość kodu**
   - Czy kod jest czytelny?
   - Czy jest zgodny ze standardami?
   - Czy nie ma oczywistych bugów?

2. **Dokumentacja**
   - Czy zmiany są udokumentowane?
   - Czy dokumentacja jest aktualna?
   - Czy przykłady działają?

3. **Testy**
   - Czy są testy dla nowej funkcjonalności?
   - Czy wszystkie testy przechodzą?

4. **Funkcjonalność**
   - Czy zmiana rozwiązuje problem?
   - Czy nie wprowadza regresji?
   - Czy jest zgodna z filozofią projektu?

### Timeline Review

- Pierwsze spojrzenie: **1-3 dni robocze**
- Pełne review: **3-7 dni roboczych**
- Merge po aprobacie: **1-2 dni robocze**

*Uwaga: Timeline może się różnić w zależności od złożoności PR i dostępności maintainerów.*

### Co po Review?

1. **Otrzymałeś komentarze**
   - Przeczytaj uważnie feedback
   - Zadaj pytania jeśli coś jest niejasne
   - Wprowadź sugerowane zmiany
   - Odpowiedz na komentarze

2. **Otrzymałeś approval**
   - Gratulacje! 🎉
   - Maintainer zmerge'uje PR
   - Twoje zmiany będą w następnym release

3. **PR został zamknięty**
   - Przeczytaj uzasadnienie
   - Możesz poprawić i otworzyć nowy PR
   - Możesz rozpocząć dyskusję w issue

---

## 👥 Społeczność

### Gdzie Możesz Znaleźć Pomoc?

- **GitHub Issues** - pytania techniczne, bugs, propozycje
- **GitHub Discussions** - ogólne dyskusje o projekcie
- **Pull Requests** - code review, feedback na zmiany

### Bądź Dobrym Członkiem Społeczności

- 🤝 Bądź pomocny i cierpliwy
- 💬 Komunikuj się jasno i szanuj innych
- 🎓 Dziel się wiedzą i ucz innych
- 🙏 Dziękuj za pomoc i feedback
- 🌟 Celebruj sukcesy innych kontrybutorów

---

## 🎯 Priorytetowe Obszary

Obecnie szczególnie szukamy pomocy w:

1. **Przykłady dla więcej języków**
   - Rust, Go, Ruby, PHP, Swift
   - Każdy przykład bardzo pomaga!

2. **Tłumaczenia**
   - Angielska wersja dokumentacji
   - Instrukcje Copilot w innych językach

3. **Case Studies**
   - Rzeczywiste przykłady użycia DSVCoder
   - Success stories z projektów

4. **Integracje**
   - Inne IDE (IntelliJ, PyCharm, etc.)
   - Narzędzia CI/CD

5. **Dokumentacja wideo**
   - Tutoriale na YouTube
   - Screencasts pokazujące DSVCoder w akcji

---

## 📧 Kontakt

Masz pytania dotyczące kontrybuowania?

- Otwórz **Discussion** na GitHub
- Skomentuj w odpowiednim **Issue**
- Zadaj pytanie w **Pull Request**

---

## 🙏 Podziękowania

Dziękujemy wszystkim kontrybutorm, którzy pomagają rozwijać DSVCoder!

Każdy wkład, bez względu na wielkość, jest cenny i doceniany. 💖

---

## 📄 Licencja

Kontrybuując do tego projektu, zgadzasz się że Twoje wkłady będą licencjonowane na licencji MIT, tak jak reszta projektu.

---

<div align="center">

**Dziękujemy za chęć pomocy w rozwijaniu DSVCoder!** 🚀

Twój wkład pomaga całej społeczności developerów. ❤️

[⬆ Wróć na górę](#-przewodnik-kontrybutora-dsvcoder)

</div>
