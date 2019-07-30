JSON er et format for lagring og deling av data. JSON (uttales djeisån) står for JavaScript Object Notation, men det brukes ikke bare med JavaScript.

JSON er et tekstformat som kan brukes i kode og er ganske enkelt for folk å lese.

```json
{
  "navn": "Troll",
  "størrelse": 90,
  "kraft": 86,
  "intelligens": 12,
  "magi": 0
}
```

Et JSON **objekt** er en liste over nøkkel-verdi par inni krøllparanteser `{}`.

En verdi kan også være en **liste** inni hakeparenteser `[]`:

```json
{
  "navn": "Troll",
  "størrelse": 90,
  "kraft": 86,
  "intelligens": 12,
  "magi": 0,
  "våpen": ["klubbe", "stein", "knokkel"]
}
```