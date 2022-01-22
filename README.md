# flutter and dart tips
Aquí iré subiendo en un redme todos los **tips** conforme los valla aprendiendo, para mejorar el rendimiento en el desarrollo de aplicación **flutter** con **dart**, estarán orientados a mejorar nuestro código y la interfaz o diseño, ademas pequeños trucos para hacer mas fácil el desarrollo, sin perder de vista el rendimiento de nuestra app que es los mas importante.


[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/jmezquita)

## Tips

### Eliminar la diferencia de color entre el statubar y el app bar en Android ###

importa el paquete de flutte service
```dart
import 'package:flutter/services.dart';
```

Agrega este código en void main() 
```dart
  SystemChrome.setSystemUIOverlayStyle(const SystemUiOverlayStyle(
      statusBarColor: Colors.transparent,
      statusBarBrightness: Brightness.light));
```



![flutter-and-dart-tips](/screenshot/tip1.png)
