# Administracja i dostęp (MVP)

**Streszczenie**: Moduł odpowiada za zakładanie kont, nadawanie ról i kontrolę dostępu. Zapewnia bezpieczeństwo i ślad zmian, aby wiadomo było kto i kiedy coś edytował.


## Cel
Bezpieczne zarządzanie użytkownikami, rolami i uprawnieniami, z audytem działań.

## MVP
- Tworzenie/edycja/dezaktywacja użytkowników.
- role i uprawnienia: predefiniowane role (Admin, Manager, Scheduler, Carer, Viewer).
- Logowanie, reset hasła, dodatkowe uwierzytelnianie (np. kod SMS) (opcjonalnie), wymuszanie silnych haseł.
- rejestr zmian kluczowych akcji.

## Zakres poza MVP
- Delegacje ról wielooddziałowych, SSO.

## Otwarte pytania
- Struktura organizacyjna (oddziały/rejony)?
- Polityka haseł/dodatkowe uwierzytelnianie (np. kod SMS)? Retencja logów?
