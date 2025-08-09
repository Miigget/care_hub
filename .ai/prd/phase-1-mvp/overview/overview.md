# CareHub – Faza 1 (MVP): Przegląd

**Streszczenie**: Ten dokument opisuje zakres pierwszej wersji CareHub (MVP): co budujemy, czego nie budujemy i jak mierzymy sukces. To szybki punkt odniesienia dla osób operacyjnych planujących uruchomienie pilotażu.


## Cel
Zdefiniować MVP systemu do zarządzania usługami opiekuńczymi z myślą o przyszłym modelu „Uber-like”.

## Zakres (In Scope)
- Aplikacja webowa dla managerów: pacjenci, carerzy, grafiki (rota), zlecenia, zadania.
- interfejs do komunikacji z przyszłą aplikacją mobilną + projekt bazy danych pod przyszłą aplikację mobilną.
- Role i uprawnienia oraz rejestr zmian.
- Podstawowe notyfikacje (e-mail/SMS/powiadomienia na telefon lub komputer) i wyznaczanie trasy (architektura pod rozbudowę).

## Poza zakresem (Out of Scope)
- Aplikacje mobilne (carer/klient) – tylko przygotowanie API.
- Zaawansowane rozliczenia/payroll – wersja uproszczona.
- Automatyczne przydzielanie wizyt na żywo – w MVP przydzielamy pół‑automatycznie.

## Mierniki sukcesu
- Utworzenie tygodniowego grafiku (<50 pacjentów) w < 30 min.
- Reakcja na nowe zlecenie < 5 min.
- 80% mniej konfliktów planistycznych (czas/kwalifikacje).

## Kluczowe ryzyka
- Zgodność (RODO/UK GDPR, CQC), dane wrażliwe.
- Dostępność carerów vs popyt lokalny.
- Zależność od usług map/komunikacji (koszty, docelowy czas reakcji).

## Moduły (oddzielne PRD)
- Administracja i dostęp
- Zarządzanie pacjentami
- Zarządzanie opiekunami
- Planowanie / Rota
- Zgłoszenia i dyspozycja
- Zadania i realizacja wizyty
- Powiadomienia i trasowanie
- Zgodność i ochrona danych
- Rozliczenia i płace (lekki zakres)
- Raportowanie i analityka (lekki zakres)
