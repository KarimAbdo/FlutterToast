# Toast

A Flutter Toast plugin.


[![pub package](https://img.shields.io/pub/v/toast.svg)](https://pub.dev/packages/toast)



## How to Use

```yaml
# add this line to your dependencies
toast: ^0.1.4
```

```dart
import 'package:toast/toast.dart';
```

```dart
Toast.show("Toast plugin app", context, duration: Toast.LENGTH_SHORT, gravity:  Toast.BOTTOM);
```

property | description
--------|------------
msg | String (Not Null)(required)
context | BuildContext (Not Null)(required)
duration| Toast.LENGTH_SHORT or Toast.LENGTH_LONG (optional)
gravity | Toast.TOP (or) Toast.CENTER (or) Toast.BOTTOM
textStyle | TextStyle (default fontSize:15, color: Colors.white)
backgroundColor | Color (default Color(0xAA000000))
backgroundRadius | double （default 16)
border| Border (optional)


![toast](https://github.com/huclengyue/FlutterToast/blob/master/screenshot/141107.png)
![toast](https://github.com/huclengyue/FlutterToast/blob/master/screenshot/141134.png)


## License

    MIT License

