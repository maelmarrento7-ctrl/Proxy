# Proxyname: tc_proxy
description: TC PROXY - Aplicativo legítimo de proxy para conexão segura
publish_to: 'none'
version: 1.0.0+1

environment:
  sdk: '>=3.0.0 <4.0.0'
  flutter: ">=3.10.0"

dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.6
  shared_preferences: ^2.2.2
  http: ^1.1.0
  google_fonts: ^6.1.0
  flutter_svg: ^2.0.9
  provider: ^6.1.1
  connectivity_plus: ^5.0.2
  permission_handler: ^11.1.0
  fluttertoast: ^8.2.4
  intl: ^0.19.0

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^3.0.0

flutter:
  uses-material-design: true
  assets:
    - assets/images/
