Json ಒಂದು ಸ್ವರೂಪವಾಗಿದೆ ಡೇಟಾವನ್ನು ಸಂಗ್ರಹಿಸಲು ಮತ್ತು ಹಂಚಿಕೊಳ್ಳಲು ಇದನ್ನು ಬಳಸಲಾಗುತ್ತದೆ. Json ಎಂದರೆ JavaScript Object Notation, ಆದರೆ ಇದನ್ನು JavaScript ‌ನೊಂದಿಗೆ ಬಳಸಲಾಗುವುದಿಲ್ಲ.

JavaScript ಸ್ವರೂಪವಾಗಿದೆ ಅದನ್ನು ಕೋಡ್(Code)‌ನಲ್ಲಿ ಬಳಸಬಹುದು ಮತ್ತು ಜನರಿಗೆ ಓದಲು ಸಾಕಷ್ಟು ಸುಲಭ.

```json
{
  "name": "Ogre",
  "size": 90,
  "power": 86,
  "intelligence": 12,
  "magic": 0
}
```

A JSON **object**ಇದು key value ಜೋಡಿಗಳ ಪಟ್ಟಿ (List) ಸುರುಳಿಯಾಕಾರದ ಆವರಣಗಳ ಒಳಗೆ`{0}`.

ಮೌಲ್ಯವು **list** ಚದರ(square) ಆವರಣಗಳ ಒಳಗೆ ಇರಬಹುದು `[]`:

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