# Skille do szkolenia „Granice spójności i współbieżności”

- [`problem-classifier`](problem-classifier/SKILL.md): przypisuje operację z wymagań, makiety albo kodu do jednej z czterech klas problemu modelarskiego (CRUD, transformacja i prezentacja, integracja, rywalizacja o zasób) i dopytuje tam, gdzie wymagania nie rozstrzygają.
- [`context-distiller`](context-distiller/SKILL.md): szuka, które pojęcia da się bezpiecznie uogólnić w jednym kontekście, a gdzie uogólnienie musi się skończyć.

## Jak uruchomić w Claude Code

```bash
git clone https://github.com/pilloPl/granice-spojnosci-skille.git
cp -R granice-spojnosci-skille/problem-classifier granice-spojnosci-skille/context-distiller ~/.claude/skills/
```

Potem w Claude Code: `/problem-classifier <wymagania>` albo `/context-distiller <pojęcia do sprawdzenia>`.
