JSON je formát na ukladanie a zdieľanie údajov. JSON (vyslovuje sa Džejson) je skratkou pre JavaScript Object Notation, ale nepoužíva sa len v JavaScript-e.

JSON je textový formát, ktorý je možné použiť v programe pre počítač a je pre ľudí ľahko čitateľný.

```json
{
  "meno": "Ogre",
  "veľkosť": 90,
  "sila": 86,
  "inteligencia": 12,
  "mágia": 0
}
```

JSON **objekt** je zoznamom dvojíc kľúč-hodnota vo vnútri zložených zátvoriek `{}`.

Hodnotou môže byť aj **zoznam** vo vnútri hranatých zátvoriek `[]`:

```json
{
  "meno": "Ogre",
  "veľkosť": 90,
  "napájanie": 86,
  "inteligencia": 12,
  "magic": 0,
  "zbrane": ["kyjak", "kameň", "kosť"]
}
```