# Digital Panda — AI workflows

Centralna biblioteka skilli, definicji agentów i procesów produkcji treści.
Repozytorium jest źródłem wersjonowanych instrukcji; nie uruchamia agentów ani nie synchronizuje automatycznie instalacji na innych kontach.

## Struktura

- `skills/<nazwa>/SKILL.md` — przenośne instrukcje oraz ich zasoby.
- `agents/` — miejsce na zatwierdzone definicje ról i konfiguracje wykonawcze.
- `workflows/` — kolejność etapów i zasady przekazywania pracy.
- `catalog.json` — katalog umiejętności lokalnych i zewnętrznych.

## Dostępne skille

| Skill | Etap | Źródło |
|---|---|---|
| Reels Quality Checker | Ocena scenariusza przed nagraniem | [Oddzielne repozytorium](https://github.com/DigitalPandaPL/reels-quality-checker) |
| Reels Explainer B-roll | Przebitki po nagraniu | [Instrukcja](skills/reels-explainer-broll/SKILL.md) |

Reels Quality Checker pozostaje w oryginalnym repozytorium. Nie kopiujemy ani nie zmieniamy jego instrukcji ani bazy wiedzy.

## Użycie na innym koncie lub w innym narzędziu

1. Zapewnij kontu dostęp do tego repozytorium.
2. Wczytaj cały folder wybranego skilla, wraz z plikami wskazanymi w `SKILL.md`. Sam link nie gwarantuje, że model przeczyta wszystkie zasoby.
3. W środowisku obsługującym instalację skilli zainstaluj wskazany folder; w innym przekaż instrukcje oraz wymagane referencje zgodnie z możliwościami narzędzia.
4. Podłącz osobno narzędzia potrzebne do wykonania pracy, np. Higgsfield, dostęp do nagrań i brandingu. Repozytorium nie przekazuje kont, uprawnień ani kredytów.
5. Przy aktualizacji pobierz nową wersję. Dla powtarzalnych produkcji zapisz SHA użytego commita w dokumentacji projektu.

`agents/openai.yaml` wewnątrz skilla zawiera metadane interfejsu Codex; główne instrukcje i referencje są w Markdown i mogą być używane przez inne zgodne środowiska. Możliwości wykonania zależą od dostępnych narzędzi.

## Rozwój biblioteki

Nowe skille trafiają do `skills/`, a gotowe definicje agentów do `agents/`. Zmiany instrukcji wersjonujemy w Git. Katalog aktualizujemy razem z dodaniem umiejętności. Materiały klientów, nagrania, wyniki generacji i dane logowania przechowujemy poza tą biblioteką.
