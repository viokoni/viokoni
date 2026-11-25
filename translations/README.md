# vioKoni translations

The app's English texts and their translations. Anyone can suggest a better wording or a new language.

**Just reading?** [`languages/de.md`](languages/de.md) shows all German texts as a table, grouped by screen. The [glossary](glossary.md) lists the fixed terms.

## Found a bad translation?

[Open an issue](https://github.com/viokoni/viokoni/issues/new?template=translation.yml): which text, what it says now, what it should say, and where in the app you saw it. A screenshot helps a lot — most bad translations come from missing context.

## Want to fix it yourself?

1. Open the file of your language in [`languages/`](languages), e.g. [`languages/de.json`](languages/de.json).
2. Each line is `"English text" : "translation"`. Change only the right-hand side. An empty `""` means "not translated yet" (the app then shows English).
3. Open a pull request.

### Placeholders

Texts like `%@`, `%lld` or `%1$@` are filled in by the app (a name, a number, a date). Keep every placeholder of the English text, same number, same kind. If your language needs them in a different order, number them: `%1$@ fell from %2$@ to %3$@` → `%1$@ fiel am %4$@ von %2$@ auf %3$@`. `%%` is a literal percent sign. Translations with wrong placeholders can't be taken over.

### Style

See the [glossary](glossary.md): fixed terms, names that stay as they are, and the tone (German uses the informal *du*). Keep it short — on Apple TV a button has little room. The `.md` table next to each `.json` shows where a text appears in the app.

Every suggestion is checked in context before it goes into the app; you'll get an answer on your issue or pull request.

## A new language

[Open an issue](https://github.com/viokoni/viokoni/issues/new?template=language.yml), or copy [`template.json`](template.json) to `languages/<code>.json` (e.g. `fr.json`, `pt-BR.json`) and open a pull request. Partial translations are welcome: anything left empty shows in English.

## License

By contributing a translation you agree that it is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain), so it can be used in the app without restrictions.

## Deutsch

Eine schlechte Übersetzung meldest du über ein [Issue](https://github.com/viokoni/viokoni/issues/new?template=translation.yml), am besten mit Screenshot und der Stelle in der App. Zum Lesen gibt es alle Texte als Tabelle in [`languages/de.md`](languages/de.md), die festen Begriffe im [Glossar](glossary.md). Selbst korrigieren kannst du sie in [`languages/de.json`](languages/de.json) per Pull Request: nur die rechte Seite ändern, Platzhalter wie `%@` und `%lld` behalten.
