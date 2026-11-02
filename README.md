# LumoCam (native Android, Kotlin + CameraX)

Structure:
  make_project.py            generates the Android project files below (run by the workflow)
  build-apk.yml              copy of the workflow (real one lives in .github/workflows/)
  .github/workflows/build-apk.yml
  settings.gradle, build.gradle, gradle.properties
  app/build.gradle
  app/src/main/AndroidManifest.xml
  app/src/main/java/com/lumo/cam/MainActivity.kt
  app/src/main/res/mipmap-*/ic_launcher.png

Build: push to GitHub -> Actions -> "Build APK" -> download artifact Lumo-Camera-APK (app-debug.apk).
