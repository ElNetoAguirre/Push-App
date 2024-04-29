<p align="center">
  <a href="https://flutter.dev/" target="blank"><img src="https://storage.googleapis.com/cms-storage-bucket/6a07d8a62f4308d2b854.svg" width="200" alt="Flutter Logo"/></a>
</p>

# Push App

Aplicación creada con [Flutter Móvil](https://flutter.dev/) y [Dart](https://dart.dev/), la cual te permite ver la configuración y el funcionamiento de las Notificaciones Push.

La primera vez que se ejecuta en un dispositivo, será necesario solicitar la autorización para dichas notificaciones, por lo que se debe presionar el icono del engrane, aparecerá un mensaje el cual debemos aprobar.

Para la generación de las notificaciones es necesario usar la consola de [Firebase](https://firebase.google.com), la cual debemos configurar siguiendo su documentación y según el dispositivo a usar.

Para esta App se utilizan dependencias como [go_router](https://pub.dev/packages/go_router), [flutter_bloc](https://pub.dev/packages/flutter_bloc), [equatable](https://pub.dev/packages/equatable), [firebase_messaging](https://pub.dev/packages/firebase_messaging), [firebase_core](https://pub.dev/packages/firebase_core), [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications); así mismo, se usará un [Servidor Personalizado](https://github.com/Klerith/firebase-get-bearer-token) para la generación del Bearer Token de Firebase (el cual tomaremos prestado de [Fernando Herrera](https://github.com/Klerith)).

Algunos de los conceptos utilizados para la generación de ésta App, son:

1. Tipos de estado de notificaciones.
2. Métodos para su manejo.
3. Entidades.
4. BLoC.
5. Leer las notificaciones push.
6. Interacciones.
7. Navegación a diferentes rutas basados en la PUSH.
8. Firebase.
9. Configuraciones de FCM.
10. Configuración de proyecto de Firebase.
11. Mezclar Push + Local Notifications.
12. Reaccionar cuando se tocan las local notifications.
13. Sonidos e iconos personalizados.
14. Evitar las dependencias ocultas.
15. Y más.

Para las Notificaciones Push en iOS, es necesario contar con un dispositivo físico de Apple (iPhone, iPad, Mac), ya que FCM vía APN's no funcionan con simuladores de iOS, tener una cuenta de [Developer Apple](https://developer.apple.com/account), realizar las configuraciones necesarias para la comunicación entre Firebase y Apple Push Notification Services, generar los perfiles y hacer los aprovisionamientos necesarios.

Otra cosa importante es que no se puede desarrollar aplicaciones para iOS y configurar las Notificaciones Push en un ambiente Windows, ya que es necesario utilizar un programa llamado Xcode, el cual solo está disponible en Mac.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
