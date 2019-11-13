JSON — це формат для зберігання та обміну даними. JSON (вимовляється Джейсон) розшифровується як JavaScript Object Notation, але він використовується не тільки з JavaScript.

JSON is a text format that can be used in code and is fairly easy for people to read.

```json
{
  "name": "Ogre",
  "size": 90,
  "power": 86,
  "intelligence": 12,
  "magic": 0
}
```

A JSON **object** is a list of key-value pairs inside curly brackets `{}`.

A value can also be a **list** inside square brackets `[]`:

```json
{
  "name": "Ogre",
  "size": 90,
  "power": 86,
  "intelligence": 12,
  "magic": 0,
  "weapons" : ["club", "rock", "bone"]
}
```