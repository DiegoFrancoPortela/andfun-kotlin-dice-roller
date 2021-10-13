# Make your First App - Dice Roller 

Esta app pertenece a la primera lección del curso: [Android App Development in Kotlin course on Udacity](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012).

## Dice Roller

Dice Roller es una app que permite lanzar un dado y obtener un número de forma aleatoria.

## Cambios realizados en esta Rama

1. [Primer Commit](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/27de4fd128cd0b3d0c0e96a6b3b062000ea45a08)

Básicamente, en este commit añado el OnClickListener, método que nos servirá para definir que acción hará el botón cuando lo clickeemos.
Posteriormente he creado una nueva rama (esta misma), en la que he añadido los ejercicios 1 y 2. 

2. [Segundo Commit](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/2c3a65d4753c993d929d0a043402927bb4d0eed3)

Creamos un método **"rollDice"**, que genera un número aleatorio del 1 al 6 y mediante TextView lo mostramos en pantalla.

3. [Tercer Commit](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/d37912592749b034df5c83576d90819cb5da5fba) - Librería Material Design

Añadimos en nuestro **build.gradle**;
  ```
  implementation 'com.google.android.material:material:1.4.0'
  ```
  O si quisiéramos usar la versión 5.0 en Alpha:
  ```
  implementation 'com.google.android.material:material:1.5.0-alpha03'
  ```
  * Es importante que, si queremos usar esta última versión, tendremos que actualizar nuestro SDK a 31.
    * https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/9f1a570d25307103bd482f13ebfb740ea6ac58f1
  
  Una vez se haya completado el proceso de instalación, podremos cambiar el estilo de nuestra App:
  
   * ✘ <style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
  
   * ✔ **<style name="AppTheme" parent="Theme.MaterialComponents.DayNight.DarkActionBar">**
  
  También podremos añadir un Icono a nuestro botón:
  [Click!](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/08723084757016aac9aa6fd5b588ebc24d9fb9d1)
  
4. [Cuarto Commit](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/9f362cecde954ea3b5ba7c1d20bcbcbc1af9b85d)

Actualización de nuestro método **"rollDice"**, que genera un número aleatorio del 1 al 6 y mediante **ImageView** mostrará la imagen de nuestro dado en función del número que obtengamos.
  
5. [Quinto Commit](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/8fa92fabf412530ceff8e510b4f3ceb255dac411)

  Aprovecharemos para optimizar nuestro método anteriory hacerlo funcionar de forma más eficiente.
  
6. [Sexto Commit](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/fd9aad80a9bc991a78ff578dea3ef561c189850a)

  Cambiamos "android:src" por "app:srcCompat", este último soporta [VectorDrawable](https://developer.android.com/reference/android/graphics/drawable/VectorDrawable.html) e incluso a partir de la versión 23.3.0 de AndroidStudio, esta será la única manera posible para poder integrarlos.
  
7. [Séptimo Commit](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/e36602cb98bf35980f551ed59de93f13a2b3adf8)

  Añadimos nuevos layouts de idiomas a nuestra aplicación.
  
8. [Octavo Commit](https://github.com/DiegoFrancoPortela/andfun-kotlin-dice-roller/commit/4897c71df36bd57e09fdeedce0c41fc6aa759ba0)

  Cambiamos el método Random por Shuffled.
  
## Screenshots

![Screenshot1](screenshots/screen0.png) ![Screenshot1](screenshots/screen1.png)
