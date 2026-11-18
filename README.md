# Karta Mini Projektu MP1 – Przestrzeń Forma

## 1. Opis fikcyjnej firmy
* **Nazwa firmy:** Przestrzeń Forma – Studio Architektury Wnętrz
* **Branża:** Architektura i projektowanie wnętrz
* **Oferta:** Kompleksowe projekty wnętrz mieszkań i domów (koncepcja 3D, dokumentacja techniczna, nadzór autorski), konsultacje online oraz projekty pojedynczych pomieszczeń.
* **Grupa docelowa:** Klienci indywidualni (w wieku 28–50 lat) kupujący mieszkania od dewelopera lub remontujący domy w dużych miastach i okolicach.

---

## 2. Persony użytkowników

### Persona 1: Anna Nowak (34 lata, Project Managerka w IT)
* **Cel:** Chce zlecić kompleksowy projekt nowego mieszkania 75 m² „pod klucz”, ponieważ nie ma czasu samodzielnie nadzorować ekip remontowych i wybierać materiałów.
* **Problem:** Obawia się ukrytych kosztów, przekroczenia budżetu oraz trudności w komunikacji z wykonawcami.
* **Urządzenie:** Laptop (przeglądanie portfolio wieczorami) oraz smartfon (szybki kontakt w ciągu dnia).
* **Oczekiwana akcja (CTA):** Wypełnienie formularza wyceny projektu na podstronie *Kontakt* lub pobranie orientacyjnego cennika z zakładki *Oferta*.

### Persona 2: Marek Kowalski (42 lata, Właściciel firmy transportowej)
* **Cel:** Szuka inspiracji i szybkiej konsultacji architekta przed remontem salonu i kuchni w domu jednorodzinnym.
* **Problem:** Nie wie, jak funkcjonalnie połączyć strefę dzienną i czy jego budżet wystarczy na zmiany układu ścian.
* **Urządzenie:** Smartfon (przegląda realizacje w przerwach w pracy).
* **Oczekiwana akcja (CTA):** Umówienie 30-minutowej konsultacji online lub kliknięcie przycisku bezpośredniego połączenia telefonicznego.

---

## 3. Mapa strony (Sitemap)
Struktura obejmuje 7 podstron na maksymalnie 2 poziomach zagłębienia:

* **Strona główna** *(skrót oferty, wybrane realizacje, opinie, przycisk CTA do wyceny)*
  * **O nas** *(zespół, proces współpracy w 4 krokach, wartości studia)*
  * **Oferta** *(pakiety projektowe, cennik orientacyjny, konsultacje online)*
    * **Projekt kompleksowy** *(szczegóły pakietu „pod klucz” – poziom 2)*
    * **Konsultacje wnętrzarskie** *(szczegóły spotkań online – poziom 2)*
  * **Realizacje (Portfolio)** *(galeria dotychczasowych projektów z opisem metrażu i stylu)*
  * **Kontakt** *(formularz wyceny Contact Form 7, telefon, e-mail, obszar działania)*
  * **Polityka prywatności** *(informacje o przetwarzaniu danych osobowych RODO i cookies)*

---

## 4. Uzasadnienie wyboru systemu CMS
Wybieram system **WordPress**, ponieważ według danych W3Techs (październik 2026) napędza on aż 40,2% wszystkich stron w internecie i posiada 58,7% udziału w rynku CMS, co gwarantuje ogromne wsparcie społeczności, bezpieczeństwo oraz łatwy dostęp do specjalistów. W przeciwieństwie do zamkniętych rozwiązań SaaS (jak Wix czy Shopify, który jest dedykowany głównie pod e-commerce), self-hosted WordPress daje firmie pełną własność kodu, brak uzależnienia od abonamentu platformy (vendor lock-in) oraz swobodę rozbudowy o własne formularze czy galerie realizacji. Z kolei rozbudowany Drupal (0,6% rynku), wykorzystywany głównie w dużych portalach i sektorze publicznym, byłby dla małego studia architektonicznego zbyt kosztowny i skomplikowany we wdrożeniu oraz codziennej edycji treści.

---

## 5. Użycie AI
* **Narzędzie:** Model językowy AI (asystent tekstowy).
* **Cel użycia:** Wygenerowanie wstępnej propozycji opisu fikcyjnej firmy, dopasowanie person do wymagań zadania, sformatowanie pliku `README.md` w składni Markdown oraz weryfikacja poprawności składniowej plików JSON i YAML.
* **Wkład własny i poprawki:** Weryfikacja zgodności wszystkich elementów z kartą zadań L1 i danymi z wykładu WL01 (W3Techs), ręczne uruchomienie oraz przetestowanie środowisk w WordPress Playground i GitHub Codespaces.
