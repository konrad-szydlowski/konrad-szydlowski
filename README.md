<div align="center">

<img src="https://raw.githubusercontent.com/konrad-szydlowski/konrad-szydlowski/main/naglowek.svg" alt="Konrad Szydłowski — strony WWW, wtyczki WordPress, automatyzacje" width="880">

### Naprawiam to, co przestało działać — i buduję to, co ma działać samo.

`WordPress` · `wtyczki na miarę` · `automatyzacje` · `Python` · `integracje API`

</div>

---

## 🔍 Trzy projekty — i ekran z każdego

Konto jest nowe, więc nie mam tu gwiazdek ani opinii. Zamiast prosić o zaufanie, pokazuję
**ekrany działających systemów i kod, który można przeczytać przed decyzją.**

Trzy projekty, nie trzydzieści. Dwa z nich powstały jako **zadania sprawdzające
od doświadczonego programisty** — skończone, oddane i recenzowane po oddaniu; poprawki
z recenzji widać w historii wydań. Trzeci to mój własny produkt.

<br>

### 1 · Sklep z wtyczkami AI — w całości na WordPressie

<img src="https://raw.githubusercontent.com/konrad-szydlowski/konrad-szydlowski/main/assets/sklep-agentow.png" alt="Sklep Agentów — strona sprzedażowa wtyczek-botów" width="100%">

Wtyczka sklepu: płatności Stripe, obsługa RODO, paczki do pobrania po opłaceniu — plus dwa
produkty, które ten sklep sprzedaje: **ChatBot LIVE** i **Segregator maila**.

| Co widać na ekranie | Dlaczego to nie jest zwykła podstrona |
|---|---|
| sklep, koszyk i dostęp do plików bez WooCommerce | mniej zależności = mniej rzeczy, które za rok przestaną działać |
| tryb testowy — pełny zakup kartą testową, bez pobierania pieniędzy | klient sprawdza całą ścieżkę zakupu, zanim cokolwiek zapłaci |
| zielony bąbelek w rogu to działający ChatBot LIVE | produkt sprzedaje się, pokazując siebie w akcji |

**738 commitów, 296 scalonych pull requestów i 17 wydań** — liczby z repozytorium, stan 09.09.2026.

🔒 Repozytorium prywatne — to mój produkt, nie pokaz kodu. Dwa pozostałe projekty są
otwarte i można je przeczytać w całości przed decyzją.

<br>

### 2 · Zgłoszenia serwisowe i reklamacje

<img src="https://raw.githubusercontent.com/konrad-szydlowski/konrad-szydlowski/main/assets/mp-service-suite.png" alt="Panel spraw serwisowych — lista zgłoszeń ze statusami i terminami SLA" width="100%">

Trzy wtyczki WordPress: formularz zgłoszenia z kontem klienta · rejestr numerów seryjnych
i gwarancji z importem CSV · automat przydziałów, terminów, powiadomień i raportów.

| Co widać na ekranie | Dlaczego to nie jest zwykła tabelka |
|---|---|
| 12 spraw, każda z numerem, rodzajem, statusem i osobą przydzieloną | statusy nie są etykietą — sterują tym, co system wolno zrobić dalej |
| terminy SLA, część na czerwono: **„po terminie"** | zegar liczy się sam i przypomina, **zanim** klient zadzwoni z pretensją |
| filtry po statusie, rodzaju i osobie | przy 12 sprawach to wygoda, przy 400 — jedyny sposób, żeby cokolwiek znaleźć |

**23 wydania · licencja GPL · kontrole jakości uruchamiane przy każdej zmianie**

➜ **[Zobacz kod](https://github.com/konrad-szydlowski/mp-service-suite)**

<br>

### 3 · Wtyczki dla pensjonatu dla kotów

<img src="https://raw.githubusercontent.com/konrad-szydlowski/konrad-szydlowski/main/assets/catsnboard.png" alt="Galeria zdjęć — karuzela kart ze zdjęciami" width="100%">

Zadanie sprawdzające od doświadczonego programisty, recenzowane po oddaniu — poprawki
z recenzji widać w historii 15 wydań. Galeria, kalendarz wydarzeń z zapisami, wielojęzyczność
z tłumaczeniem treści i panel do zarządzania tym wszystkim.

| Co widać na ekranie | Dlaczego to nie jest wtyczka z półki |
|---|---|
| galeria wpięta w **istniejący motyw**, bez jego przebudowy | wtyczkę dokłada się do gotowej strony — nie trzeba jej stawiać od nowa |
| licznik `03 / 12` i płynne przewijanie | zdjęcia doczytują się partiami — 200 zdjęć nie kładzie telefonu |
| ta sama treść po polsku i po angielsku | tłumaczenia opisów wydarzeń, nie tylko przycisków |

**15 wydań · licencja GPL**

➜ **[Zobacz kod](https://github.com/konrad-szydlowski/catsnboard)**

---

## 🧪 Czego na zrzucie nie widać

To jest ta część, o której zwykle nikt nie mówi, dopóki coś nie padnie.

**Sprawdzam swoją robotę cudzymi rękami.** Skończona paczka nie jedzie do klienta z mojego
komputera, gdzie „u mnie działa". Ląduje na **czystej instalacji WordPressa** i przechodzi
osobny przebieg kontrolny, którego jedynym celem jest ją złamać: zła kolejność kliknięć,
przerwana płatność, plik nie ten, dwie osoby robiące to samo w tej samej sekundzie.

Co przy tym wyjdzie — **spisuję razem z miejscem w kodzie i datą.** Dzięki temu przy oddaniu
wiem, co jest zrobione, a co świadomie zostawiam na później. I mówię to **przed** fakturą, nie po.

> Komplet zielonych testów mówi tylko tyle, że kod przechodzi te testy, które ktoś zdążył
> pomyśleć. Osobny przebieg kontrolny mojego największego projektu wyłapał rzeczy, których
> nie złapał żaden z nich.

---

## 🎯 Co robię najczęściej

<table>
<tr>
<td width="33%" valign="top">

### 🔧 Naprawy

Strona przestała działać po aktualizacji? Formularz nie wysyła? Sklep zwalnia?

Biorę **jedną konkretną usterkę**, naprawiam i piszę, co było nie tak.

**Co z tego masz:** działa dziś, nie za dwa tygodnie. Płacisz za naprawę, nie za abonament.

</td>
<td width="33%" valign="top">

### ⚙️ Automatyzacje

Ktoś u Was codziennie przepisuje te same dane z formularza do maila, z maila do arkusza?

Buduję coś, co robi to samo — n8n, integracje API, webhooki, import danych.

**Co z tego masz:** znika godzina dziennie ręcznej roboty i znikają literówki.

</td>
<td width="33%" valign="top">

### 🧩 Wtyczki na miarę

Potrzebujesz na stronie rzeczy, której nie ma w żadnej gotowej wtyczce?

Piszę własną — katalog, kalendarz, importer, panel. Kod zostaje Twój.

**Co z tego masz:** nie płacisz co roku za cudzą wtyczkę i nie zależysz od jej autora.

</td>
</tr>
</table>

---

## 🤝 Jak pracuję

- **Najpierw spisuję, co dokładnie ma powstać.** Dopiero potem buduję. Bez tego zawsze wychodzi
  „miało być inaczej".
- **Pokazuję postęp na żywo**, nie po fakcie. Możesz zobaczyć i powiedzieć „nie tak", zanim skończę.
- **Oddaję z instrukcją napisaną po ludzku** — bez żargonu, żebyś nie musiał do mnie wracać
  przy każdej drobnej zmianie.
- **Jeśli w trakcie okaże się, że robota jest większa, niż zakładaliśmy — mówię o tym przed
  fakturą, nie po.**
- **Hosting i domena zostają na Twoim koncie.** Nie trzymam klientów u siebie.

W kodzie pomagają mi narzędzia AI — piszą fragmenty, wyłapują błędy, generują dokumentację.
Nie jest to gadżet: dzięki temu ten sam zakres kosztuje mniej, niż gdybym pisał wszystko ręcznie.
Architektura, decyzje i odpowiedzialność są moje.

---

## 📬 Kontakt

**kontakt.dobrastrona@gmail.com** · piszę po polsku, prosto, bez żargonu · pracuję zdalnie, w całej Polsce

Napisz, co ma działać — odpiszę, czy to robota na 300 zł, czy na 3 000, i ile potrwa.
Bez zobowiązań i bez żargonu.
