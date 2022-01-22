# flutter and dart tips
Aquí iré subiendo todos los **tips** conforme los vaya aprendiendo, para mejorar el rendimiento en el desarrollo de aplicación **flutter** con **dart**, estarán orientados a mejorar nuestro código y la interfaz o diseño, ademas pequeños trucos para hacer mas fácil el desarrollo, sin perder de vista el rendimiento de nuestra app que es los mas importante.


[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/jmezquita)

## Tips

### Eliminar la diferencia de color entre el statubar y el app bar en Android ###

import el paquete de flutte service
```dart
import 'package:flutter/services.dart';
```

Agrega este código en el main 
```dart
  SystemChrome.setSystemUIOverlayStyle(const SystemUiOverlayStyle(
      statusBarColor: Colors.transparent,
      statusBarBrightness: Brightness.light));
```

Como esta por defecto y como quedaria:

![flutter-and-dart-tips](/screenshot/tip.png)


Simple verdad!!! :smile: :smile: :smile:

### Eliminar el modo baner de nuesta app ###

para esto solo tenemso que agregar la siguiente linea de código:

```dart
     debugShowCheckedModeBanner: false,
```
a esto me refiero :smile:
![flutter-and-dart-tips](/screenshot/ti1.png)
