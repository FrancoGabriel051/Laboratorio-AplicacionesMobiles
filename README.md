Estado	Criterio	Verificación
✅	Android Studio instalado y operativo	Android Studio abre correctamente, permite crear proyectos y no presenta errores de instalación.
✅	Proyecto HolaYo creado con Empty Views Activity, minSdk 26	El proyecto utiliza la plantilla Empty Views Activity, Kotlin como lenguaje y tiene minSdk = 26.
✅	Sé señalar dónde vive cada parte del proyecto	Código: app/src/main/java/.../MainActivity.kt
Recursos: app/src/main/res/
Manifiesto: app/src/main/AndroidManifest.xml
minSdk: app/build.gradle.kts
✅	La app corre en el emulador y en mi teléfono	La aplicación inicia correctamente, muestra mis datos y el botón responde al tocarlo.
✅	Tengo la ruta y el peso del app-debug.apk anotados	Se generó el APK de debug y tengo registrada su ubicación y tamaño.
✅	Ícono propio	Se creó un ícono personalizado mediante Image Asset y los recursos fueron generados en mipmap.
✅	APK instalado en otro dispositivo	El app-debug.apk fue transferido e instalado correctamente en otro dispositivo Android.
✅	Tercer dato opcional	Se agregó un tercer atributo opcional (String?) al Perfil y se muestra únicamente cuando existe, utilizando ?.let { }.