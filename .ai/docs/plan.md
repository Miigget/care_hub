## Plan dokumentacji projektu SaaS

Poniżej znajduje się kompletny spis dokumentów, ułożony od najbardziej „high‑level” (strategia i wizja) do najbardziej szczegółowych (specyfikacje techniczne, testy, operacje). Dla każdego elementu podano krótkie objaśnienie i oczekiwane artefakty. Skróty są rozwinięte przy pierwszym użyciu, a pełny słownik znajduje się na końcu.

### 1. Dokumenty strategiczne i biznesowe (high‑level)
- [1.1. Wizja Produktu (PVD — Product Vision Document)](../../docs/01-strategia/1.1-wizja-produktu-pvd.md): dlaczego produkt istnieje, dla kogo, jaki problem rozwiązuje, unikalna propozycja wartości.
  - Artefakty: deklaracja wizji, misja, cele długoterminowe, anty‑cele.
- [1.2. Executive Summary (jednostronicowy skrót dla decydentów)](../../docs/01-strategia/1.2-executive-summary.md): kondensacja kluczowych informacji o produkcie, rynku, ryzykach, planie.
- [1.3. Business Case (Uzasadnienie biznesowe)](../../docs/01-strategia/1.3-business-case.md): założenia finansowe, koszty, przychody, scenariusze, analiza wrażliwości.
- [1.4. Analiza Rynku i Konkurencji](../../docs/01-strategia/1.4-analiza-rynku-i-konkurencji.md): segmenty, trendy, krajobraz konkurencyjny, pozycjonowanie.
- [1.5. Segmentacja Klientów, Persony i JTBD (Jobs To Be Done)](../../docs/01-strategia/1.5-segmentacja-persony-jtbd.md): kto kupuje/używa, ich zadania do wykonania, motywacje, bariery.
- [1.6. Propozycja Wartości i Strategia Cenowa](../../docs/01-strategia/1.6-propozycja-wartosci-i-strategia-cenowa.md): Value Proposition Canvas, pakiety, cennik, metryki wartości.
- [1.7. Strategia Go‑To‑Market (GTM)](../../docs/01-strategia/1.7-strategia-go-to-market-gtm.md): kanały pozyskania, messaging, lejek sprzedażowy, partnerstwa.
- [1.8. Mapa Interesariuszy i RACI (Responsible, Accountable, Consulted, Informed)](../../docs/01-strategia/1.8-mapa-interesariuszy-i-raci.md): role, odpowiedzialności, wpływ.
- [1.9. Cele i Metryki (North Star Metric, KPI — kluczowe wskaźniki, OKR — cele i kluczowe rezultaty)](../../docs/01-strategia/1.9-cele-i-metryki-nsm-kpi-okr.md): definicje, sposób pomiaru, częstotliwość przeglądu.
- [1.10. Rejestr Ryzyk (Risk Register)](../../docs/01-strategia/1.10-rejestr-ryzyk.md): ryzyka, prawdopodobieństwo, wpływ, właściciel, plany mitygacji.

### 2. Zakres i wymagania produktu
- [2.1. MRD (Market Requirements Document — Wymagania rynkowe)](../../docs/02-wymagania/2.1-mrd-wymagania-rynkowe.md): potrzeby rynku i segmentów, priorytety na poziomie rynku.
- [2.2. BRD (Business Requirements Document — Wymagania biznesowe)](../../docs/02-wymagania/2.2-brd-wymagania-biznesowe.md): cele biznesowe, procesy, reguły biznesowe.
- [2.3. PRD (Product Requirements Document — Wymagania produktowe)](../../docs/02-wymagania/2.3-prd-wymagania-produktowe.md): zakres funkcji, user stories, kryteria akceptacji.
- [2.4. Definicja MVP (Minimum Viable Product) i iteracji](../../docs/02-wymagania/2.4-definicja-mvp-i-iteracje.md): co wchodzi do pierwszego wydania, kolejne incrementy.
- [2.5. User Stories i Use Cases](../../docs/02-wymagania/2.5-user-stories-i-use-cases.md): opisy potrzeb użytkowników i scenariuszy użycia.
- [2.6. Kryteria Akceptacji i Definition of Done](../../docs/02-wymagania/2.6-kryteria-akceptacji-i-definition-of-done.md): warunki zaliczenia prac, standardy jakości.
- [2.7. Priorytetyzacja (MoSCoW, RICE)](../../docs/02-wymagania/2.7-priorytetyzacja-moscow-rice.md): metoda nadawania priorytetów i wyniki.
- [2.8. Roadmapa Produktu](../../docs/02-wymagania/2.8-roadmapa-produktu.md): kamienie milowe, przybliżone terminy, zależności.
- [2.9. Plan Wydań (Release Plan)](../../docs/02-wymagania/2.9-plan-wydan.md): kadencja, zakres wersji, kryteria wejścia/wyjścia.

### 3. Projekt doświadczenia użytkownika (UX/UI)
- [3.1. Architektura Informacji i Sitemap](../../docs/03-ux-ui/3.1-architektura-informacji-i-sitemap.md): struktura treści i nawigacji.
- [3.2. User Flows i Customer Journey Maps](../../docs/03-ux-ui/3.2-user-flows-i-customer-journey-maps.md): ścieżki użytkownika, punkty tarcia.
- [3.3. Wireframes i Prototypy (low/high fidelity)](../../docs/03-ux-ui/3.3-wireframes-i-prototypy.md): szkice ekranów, klikalne prototypy.
- [3.4. Design System](../../docs/03-ux-ui/3.4-design-system.md): design tokens, biblioteka komponentów, zasady stosowania.
- [3.5. Dostępność (WCAG 2.2 AA)](../../docs/03-ux-ui/3.5-dostepnosc-wcag-2-2-aa.md): cele, checklisty, testy dostępności.
- [3.6. Strategia Treści (tone of voice, mikrocopy)](../../docs/03-ux-ui/3.6-strategia-tresci.md): zasady językowe, styl komunikacji.
- [3.7. Lokalizacja i Internacjonalizacja (i18n/l10n)](../../docs/03-ux-ui/3.7-lokalizacja-i-internacjonalizacja-i18n-l10n.md): języki, formaty, proces tłumaczeń.

### 4. Architektura i projekt techniczny
- [4.1. Przegląd Architektury (Model C4)](../../docs/04-architektura/4.1-przeglad-architektury-model-c4.md): diagramy kontekstu, kontenerów, komponentów i opcjonalnie kodu.
- [4.2. ADRs (Architecture Decision Records — Rejestr decyzji architektonicznych)](../../docs/04-architektura/4.2-adrs-rejestr-decyzji-architektonicznych.md): decyzje, kontekst, alternatywy, konsekwencje.
- [4.3. Wymagania Niefunkcjonalne (NFR)](../../docs/04-architektura/4.3-wymagania-niefunkcjonalne-nfr.md): wydajność, skalowalność, dostępność, niezawodność, bezpieczeństwo, prywatność.
- [4.4. Model Danych](../../docs/04-architektura/4.4-model-danych-erd.md): ERD (diagram związków encji), słownik danych, standardy nazewnictwa.
- [4.5. Strategia Multi‑tenancy dla SaaS](../../docs/04-architektura/4.5-strategia-multi-tenancy-saas.md): izolacja najemców (tenantów), partycjonowanie danych, ograniczenia zasobów.
- [4.6. API](../../docs/04-architektura/4.6-api-specyfikacje.md): styl (REST/GraphQL), standardy, specyfikacje (OpenAPI/GraphQL SDL), wersjonowanie, limity, idempotencja.
- [4.7. Integracje Zewnętrzne](../../docs/04-architektura/4.7-integracje-zewnetrzne.md): webhooks, kolejkowanie, polityki retry, obsługa błędów.
- [4.8. Bezpieczeństwo](../../docs/04-architektura/4.8-bezpieczenstwo.md): model zagrożeń (STRIDE), uwierzytelnianie i autoryzacja (OAuth 2.1/OIDC), RBAC/ABAC, szyfrowanie w spoczynku i tranzycie, zarządzanie sekretami.
- [4.9. Zgodność i Prywatność](../../docs/04-architektura/4.9-zgodnosc-i-prywatnosc.md): RODO/GDPR, DPIA (ocena skutków), DPA (powierzenie przetwarzania), minimalizacja danych.
- [4.10. Observability](../../docs/04-architektura/4.10-observability.md): logowanie, metryki, śledzenie (tracing), SLI/SLO/SLA, deskryptory dashboardów.
- [4.11. Kopie Zapasowe i Odzyskiwanie (Backup/DR)](../../docs/04-architektura/4.11-kopie-zapasowe-i-odzyskiwanie-backup-dr.md): strategia, RTO/RPO, testy odtwarzania.
- [4.12. Zarządzanie Konfiguracją i Feature Flagami](../../docs/04-architektura/4.12-zarzadzanie-konfiguracja-i-feature-flags.md): standardy, procesy, narzędzia.
- [4.13. Plan Wydajności i Skalowania](../../docs/04-architektura/4.13-plan-wydajnosci-i-skalowania.md): budżety wydajnościowe, testy obciążeniowe, autoskalowanie.
- [4.14. Model Błędów i Odporność](../../docs/04-architektura/4.14-model-bledow-i-odpornosc.md): circuit breaker, backoff, rate limiting, timeouts.

### 5. Infrastruktura i operacje (DevOps)
- [5.1. Środowiska (dev/test/stage/prod)](../../docs/05-devops/5.1-srodowiska.md): cel, izolacja, różnice konfiguracji.
- [5.2. IaC (Infrastructure as Code)](../../docs/05-devops/5.2-iac.md): standardy (np. Terraform/CloudFormation), struktura repo, konwencje.
- [5.3. CI/CD (Continuous Integration/Continuous Delivery)](../../docs/05-devops/5.3-ci-cd.md): pipeline’y, bramki jakości, polityka release’ów.
- [5.4. Konteneryzacja i Orkiestracja](../../docs/05-devops/5.4-konteneryzacja-i-orkiestracja.md): obrazy Docker, Kubernetes, zarządzanie zasobami.
- [5.5. Zarządzanie Konfiguracją (12‑Factor App)](../../docs/05-devops/5.5-zarzadzanie-konfiguracja-12-factor-app.md): źródła prawdy, tajemnice (Vault/KMS).
- [5.6. Monitoring i Alerting](../../docs/05-devops/5.6-monitoring-i-alerting.md): metryki, progi, rotacje on‑call.
- [5.7. FinOps (optimizacja kosztów chmury)](../../docs/05-devops/5.7-finops.md): budżety, alokacja kosztów, tagowanie, alerty.
- [5.8. Polityka Wersjonowania (SemVer)](../../docs/05-devops/5.8-polityka-wersjonowania-semver.md): zasady zmiany wersji i kompatybilności.

### 6. Jakość i testowanie
- [6.1. Strategia Testów (piramida testów)](../../docs/06-jakosc-testy/6.1-strategia-testow.md): podejście, narzędzia, pokrycie.
- [6.2. Testy Funkcjonalne](../../docs/06-jakosc-testy/6.2-testy-funkcjonalne.md): jednostkowe, integracyjne, E2E.
- [6.3. Testy Niefunkcjonalne](../../docs/06-jakosc-testy/6.3-testy-niefunkcjonalne.md): wydajnościowe, bezpieczeństwa, dostępności, chaos engineering.
- [6.4. Plan Testów i Przypadki Testowe](../../docs/06-jakosc-testy/6.4-plan-testow-i-przypadki-testowe.md): zakres, dane testowe, harmonogram.
- [6.5. Automatyzacja Testów w CI](../../docs/06-jakosc-testy/6.5-automatyzacja-testow-w-ci.md): kryteria blokujące, raportowanie.
- [6.6. UAT (User Acceptance Testing)](../../docs/06-jakosc-testy/6.6-uat-testy-akceptacyjne.md): plan, role, protokół odbioru.
- [6.7. Testy Regresyjne](../../docs/06-jakosc-testy/6.7-testy-regresyjne.md): zakres, kadencja, kryteria.
- [6.8. Metryki Jakości](../../docs/06-jakosc-testy/6.8-metryki-jakosci.md): defekty, MTTR/MTBF, pokrycie testów.

### 7. Dokumentacja inżynieryjna
- [7.1. Standardy Kodowania i Style Guide](../../docs/07-inzynieria/7.1-standardy-kodowania-i-style-guide.md): konwencje, lintery, formatowanie.
- [7.2. Struktura Repozytorium i Workflow](../../docs/07-inzynieria/7.2-struktura-repozytorium-i-workflow.md): monorepo vs polyrepo, gałęzie, konwencje commitów.
- [7.3. Wytyczne Kontrybucji (CONTRIBUTING) i Code of Conduct](../../docs/07-inzynieria/7.3-wytyczne-kontrybucji-i-code-of-conduct.md): zasady współpracy.
- [7.4. Przeglądy Kodu (Code Review Policy)](../../docs/07-inzynieria/7.4-przeglady-kodu-code-review-policy.md): kryteria, checklisty, wymagania PR.
- [7.5. Zarządzanie Zależnościami i Licencjami (SBOM — Software Bill of Materials)](../../docs/07-inzynieria/7.5-zarzadzanie-zaleznosciami-i-licencjami-sbom.md): ewidencja, aktualizacje, skanowanie.
- [7.6. Dokumentacja API dla deweloperów](../../docs/07-inzynieria/7.6-dokumentacja-api-dla-deweloperow.md): opisy endpointów, przykłady, SDK.
- [7.7. Changelog i Notatki Wydań](../../docs/07-inzynieria/7.7-changelog-i-notatki-wydan.md): zakres zmian, migracje, ryzyka.
- [7.8. Instrukcje Uruchomienia Lokalnie i Wdrożenia](../../docs/07-inzynieria/7.8-instrukcje-uruchomienia-lokalnie-i-wdrozenia.md): wymagania, komendy, troubleshoot.

### 8. Operacje i wsparcie (SRE/ITOps)
- [8.1. Runbooki i Playbooki](../../docs/08-operacje/8.1-runbooki-i-playbooki.md): procedury rutynowe i reakcyjne.
- [8.2. On‑Call i Eskalacje](../../docs/08-operacje/8.2-on-call-i-escalacje.md): rotacje, matryca powiadomień, SLO.
- [8.3. Zarządzanie Incydentami (ITIL)](../../docs/08-operacje/8.3-zarzadzanie-incydentami-itil.md): klasyfikacja, komunikacja, RCA (root cause analysis), post‑mortem.
- [8.4. Plan Ciągłości Działania (BCP) i Odporność](../../docs/08-operacje/8.4-plan-ciaglosci-dzialania-bcp.md): scenariusze, testy, zależności krytyczne.
- [8.5. Zarządzanie Tożsamością i Dostępem (IAM)](../../docs/08-operacje/8.5-zarzadzanie-tozsamoscia-i-dostepem-iam.md): role, zasady najmniejszego uprzywilejowania.
- [8.6. Plan Pojemności (Capacity Planning)](../../docs/08-operacje/8.6-plan-pojemnosci.md): prognozy, limity, rezerwy.

### 9. Aspekty prawne i zgodność (Legal & Compliance)
- [9.1. Regulamin Świadczenia Usług (Terms of Service)](../../docs/09-legal-compliance/9.1-regulamin-swiadczenia-uslug-tos.md): prawa/obowiązki, ograniczenia odpowiedzialności.
- [9.2. Polityka Prywatności](../../docs/09-legal-compliance/9.2-polityka-prywatnosci.md): zakres danych, cele, podstawy prawne, prawa użytkowników.
- [9.3. DPA (Data Processing Agreement — Umowa powierzenia przetwarzania danych)](../../docs/09-legal-compliance/9.3-dpa-umowa-powierzenia.md): role stron, zobowiązania.
- [9.4. DPIA (Data Protection Impact Assessment — Ocena skutków dla ochrony danych)](../../docs/09-legal-compliance/9.4-dpia-ocena-skutkow.md): ryzyka, środki zaradcze.
- [9.5. Polityka Cookies](../../docs/09-legal-compliance/9.5-polityka-cookies.md): typy, cele, preferencje.
- [9.6. Polityki Bezpieczeństwa Informacji](../../docs/09-legal-compliance/9.6-polityki-bezpieczenstwa-informacji.md): dostęp, hasła, zarządzanie podatnościami.
- [9.7. Zarządzanie Dostawcami](../../docs/09-legal-compliance/9.7-zarzadzanie-dostawcami-sla.md): due diligence, umowy, ocena ryzyka, SLA.

### 10. Klient i sukces klienta (Customer Success)
- [10.1. Centrum Pomocy / Baza Wiedzy](../../docs/10-customer-success/10.1-centrum-pomocy-baza-wiedzy.md): artykuły, FAQ, poradniki.
- [10.2. Przewodniki Onboardingowe](../../docs/10-customer-success/10.2-przewodniki-onboardingowe.md): konfiguracja, pierwsze kroki, checklisty.
- [10.3. Dokumentacja Publicznego API](../../docs/10-customer-success/10.3-dokumentacja-publicznego-api.md): dla integratorów i partnerów.
- [10.4. Playbook Sukcesu Klienta (CSM)](../../docs/10-customer-success/10.4-playbook-sukcesu-klienta.md): health score, QBR, plany sukcesu.
- [10.5. Materiały Sprzedażowe i Demo](../../docs/10-customer-success/10.5-materialy-sprzedazowe-i-demo.md): prezentacje, skrypty demo, one‑pagers.
- [10.6. SLA (Service Level Agreement)](../../docs/10-customer-success/10.6-sla.md): definicje poziomów usług, czasy reakcji, rekompensaty.

### 11. Zarządzanie projektem i organizacja
- [11.1. Project Charter (Karta Projektu)](../../docs/11-zarzadzanie-projektem/11.1-project-charter.md): cel, zakres, ograniczenia, sukces.
- [11.2. Plan Komunikacji](../../docs/11-zarzadzanie-projektem/11.2-plan-komunikacji.md): kanały, rytuały, odbiorcy, częstotliwość.
- [11.3. Harmonogram (Gantt/Milestones)](../../docs/11-zarzadzanie-projektem/11.3-harmonogram.md): kamienie milowe, zależności, ścieżka krytyczna.
- [11.4. RACI (role i odpowiedzialności)](../../docs/11-zarzadzanie-projektem/11.4-raci.md): mapa ról dla głównych obszarów.
- [11.5. Rejestr Ryzyk i Zagadnień (Issues Log)](../../docs/11-zarzadzanie-projektem/11.5-rejestr-ryzyk-i-zagadnien.md): status, właściciel, działania.
- [11.6. Plan Zasobów i Budżet](../../docs/11-zarzadzanie-projektem/11.6-plan-zasobow-i-budzet.md): obciążenia, koszty, rezerwy.
- [11.7. Zasady Governance i Decyzji](../../docs/11-zarzadzanie-projektem/11.7-zasady-governance-i-decyzji.md): kto decyduje, jak eskalować, ADR na poziomie produktu.

### 12. Migracje i wdrożenia
- [12.1. Plan Migracji Danych](../../docs/12-migracje-wdrozenia/12.1-plan-migracji-danych.md): źródła, mapowanie, walidacja, czyszczenie.
- [12.2. Strategia Cutover](../../docs/12-migracje-wdrozenia/12.2-strategia-cutover.md): Big‑Bang vs. Blue/Green/Canary — kryteria wyboru, ryzyka.
- [12.3. Plan Rollbacku](../../docs/12-migracje-wdrozenia/12.3-plan-rollbacku.md): scenariusze, decyzje „go/no‑go”.
- [12.4. Weryfikacja po Wdrożeniu](../../docs/12-migracje-wdrozenia/12.4-weryfikacja-po-wdrozeniu.md): smoke tests, monitoring wczesny.
- [12.5. Checklisty Przed/Po Wdrożeniu](../../docs/12-migracje-wdrozenia/12.5-checklisty-przed-po-wdrozeniu.md): operacyjne i produktowe.

### 13. Analityka i zarządzanie danymi
- [13.1. Plan Analityki Produktowej](../../docs/13-analityka-dane/13.1-plan-analityki-produktowej.md): pytania biznesowe, metryki, eventy.
- [13.2. Taksonomia Zdarzeń i Schematy](../../docs/13-analityka-dane/13.2-taksonomia-zdarzen-i-schematy.md): definicje, konwencje nazewnictwa, wersjonowanie.
- [13.3. Raporty i Dashboardy](../../docs/13-analityka-dane/13.3-raporty-i-dashboardy.md): zakres, właściciele, częstotliwość odświeżania.
- [13.4. Polityka Retencji Danych i Anonimizacja](../../docs/13-analityka-dane/13.4-polityka-retencji-danych-i-anonimizacja.md): czasy retencji, procedury usunięcia.
- [13.5. Zarządzanie Zgodami (Consent Management)](../../docs/13-analityka-dane/13.5-zarzadzanie-zgodami-consent-management.md): modele zgód, audyt.
- [13.6. Data Governance](../../docs/13-analityka-dane/13.6-data-governance.md): role (data owner/steward), jakość danych, linie rodowodu (data lineage).

### 14. Załączniki i metadane
- [14.1. Glosariusz Pojęć](../../docs/99-zalaczniki/99.1-glosariusz-pojec.md): definicje domenowe.
- [14.2. Słownik Skrótów](../../docs/99-zalaczniki/99.2-slownik-skrotow.md): rozwinięcia i objaśnienia (patrz niżej).
- [14.3. Szablony i Checklisty](../../docs/99-zalaczniki/99.3-szablony-i-checklisty.md): np. szablon ADR, PRD, plan testów, post‑mortem.
- [14.4. Źródła i Referencje](../../docs/99-zalaczniki/99.4-zrodla-i-referencje.md): normy, standardy, materiały.

## Proponowana struktura katalogów dokumentacji

Poniższa struktura jest sugerowana — można ją dostosować do potrzeb zespołu.

```text
docs/
  01-strategia/
  02-wymagania/
  03-ux-ui/
  04-architektura/
  05-devops/
  06-jakosc-testy/
  07-inzynieria/
  08-operacje/
  09-legal-compliance/
  10-customer-success/
  11-zarzadzanie-projektem/
  12-migracje-wdrozenia/
  13-analityka-dane/
  99-zalaczniki/
```

## Słownik skrótów (z objaśnieniami po polsku)

- **PVD (Product Vision Document)**: dokument wizji produktu — streszcza misję, odbiorców i długoterminowe cele.
- **MRD (Market Requirements Document)**: wymagania rynkowe — czego oczekuje rynek i segmenty klientów.
- **BRD (Business Requirements Document)**: wymagania biznesowe — cele i reguły wynikające z procesu biznesowego.
- **PRD (Product Requirements Document)**: wymagania produktowe — co produkt ma robić z perspektywy użytkownika.
- **JTBD (Jobs To Be Done)**: zadania do wykonania — ramy rozumienia potrzeb użytkowników.
- **RACI (Responsible, Accountable, Consulted, Informed)**: macierz odpowiedzialności w zespole.
- **KPI (Key Performance Indicator)**: kluczowy wskaźnik efektywności.
- **OKR (Objectives and Key Results)**: metoda wyznaczania celów i mierzenia rezultatów.
- **MVP (Minimum Viable Product)**: minimalny produkt zdolny do weryfikacji hipotez.
- **WCAG (Web Content Accessibility Guidelines)**: wytyczne dostępności treści w sieci.
- **C4 (model)**: standard prezentacji architektury na 4 poziomach — kontekst, kontenery, komponenty, kod.
- **ADR (Architecture Decision Record)**: zapis ważnych decyzji architektonicznych.
- **NFR (Non‑Functional Requirements)**: wymagania niefunkcjonalne (np. wydajność, bezpieczeństwo).
- **ERD (Entity‑Relationship Diagram)**: diagram encji i relacji dla modelu danych.
- **REST (Representational State Transfer)**: styl projektowania API.
- **GraphQL SDL (Schema Definition Language)**: język definicji schematów GraphQL.
- **OAuth 2.1 / OIDC (OpenID Connect)**: standardy uwierzytelniania i autoryzacji.
- **RBAC/ABAC**: modele kontroli dostępu — oparte na rolach/atrybutach.
- **RODO/GDPR**: europejskie przepisy o ochronie danych osobowych.
- **DPIA (Data Protection Impact Assessment)**: ocena skutków dla ochrony danych.
- **DPA (Data Processing Agreement)**: umowa powierzenia przetwarzania danych.
- **SLI/SLO/SLA**: wskaźnik poziomu usługi / cel poziomu usługi / umowa o poziomie usługi.
- **DR (Disaster Recovery)**: odtwarzanie po awarii.
- **RTO/RPO**: docelowy czas odtworzenia / docelowy punkt odtworzenia.
- **IaC (Infrastructure as Code)**: definiowanie infrastruktury jako kod.
- **CI/CD (Continuous Integration/Continuous Delivery)**: ciągła integracja i ciągłe dostarczanie.
- **KMS (Key Management Service)**: usługa zarządzania kluczami szyfrującymi.
- **FinOps**: praktyki zarządzania i optymalizacji kosztów chmurowych.
- **SBOM (Software Bill of Materials)**: spis komponentów oprogramowania i ich licencji.
- **ITIL (Information Technology Infrastructure Library)**: zbiór dobrych praktyk ITSM.
- **BCP (Business Continuity Plan)**: plan ciągłości działania organizacji.
- **IAM (Identity and Access Management)**: zarządzanie tożsamościami i dostępem.
- **i18n/l10n**: internacjonalizacja/lokalizacja — przygotowanie i tłumaczenie produktu.
- **UAT (User Acceptance Testing)**: testy akceptacyjne prowadzone przez użytkowników.


