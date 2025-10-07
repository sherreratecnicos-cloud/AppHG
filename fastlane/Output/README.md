# GestorProyectosHG – Build sin firma

Proyecto iOS preparado para compilar automáticamente en GitHub Actions y generar un `.ipa` **sin firma**.

## 🚀 Estructura
- `fastlane/Fastfile`: automatización de build
- `ExportOptions.plist`: exportación sin firma
- `.github/workflows/ios-ci.yml`: CI en GitHub Actions

## 💡 Uso
1. Sube este proyecto a un repositorio público en GitHub.
2. Asegúrate de tener rama `main`.
3. Haz un push: GitHub Actions generará automáticamente el `.ipa`.
