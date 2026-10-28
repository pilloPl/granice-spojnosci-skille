# Skille do szkolenia „Granice spójności i współbieżności”

- [`problem-classifier`](problem-classifier/SKILL.md): przypisuje operację z wymagań, makiety albo kodu do jednej z czterech klas problemu modelarskiego (CRUD, transformacja i prezentacja, integracja, rywalizacja o zasób) i dopytuje tam, gdzie wymagania nie rozstrzygają.
- [`context-distiller`](context-distiller/SKILL.md): szuka, które pojęcia da się bezpiecznie uogólnić w jednym kontekście, a gdzie uogólnienie musi się skończyć.
- [`aggregate-designer`](aggregate-designer/SKILL.md): prowadzi krok po kroku przez projekt jednostki spójności: komendy, konflikty parami, minimalne dane, obciążenie i sposób blokowania.

## Jak uruchomić w Claude Code

```bash
git clone https://github.com/pilloPl/granice-spojnosci-skille.git
cp -R granice-spojnosci-skille/problem-classifier granice-spojnosci-skille/context-distiller granice-spojnosci-skille/aggregate-designer ~/.claude/skills/
```

Potem w Claude Code: `/problem-classifier <wymagania>`, `/context-distiller <pojęcia do sprawdzenia>` albo `/aggregate-designer <lista komend>`.
