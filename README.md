# InvoiceEasy Android Downloads

flutter pub get
flutter analyze
flutter test
flutter build apk --release

cp build/app/outputs/flutter-apk/invoice-easy.apk invoice-easy.apk
gh release create v3.0.0 invoice-easy.apk 
--repo Magatijoel9620/invoiceeasy-downloads 
--title "invoice-easy v3.0.0" 
--notes "Deep Links fixed."
