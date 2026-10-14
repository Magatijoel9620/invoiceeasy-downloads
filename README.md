# InvoiceEasy Android Downloads

flutter pub get
flutter analyze
flutter test
flutter build apk --release
cp build/app/outputs/flutter-apk/app-release.apk farmora.apk
gh release create vX.Y.Z farmora.apk --repo Magatijoel9620/farmora-downloads --title "Farmora vX.Y.Z" --notes "Describe changes and fixes."
