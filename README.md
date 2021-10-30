# fluttercrypto_aes

// erledigt: in alle Formulare einfügen (sonst klappt IOS 11 nicht):

Expanded(
child:

vor: ElevatedButton(

und nach ), // Elevated Button noch
), einfügen

nicht eintragen:
overflow: TextOverflow.ellipsis,
ergibt: aus ...

uses pointycastle: ^3.3.4 for encryption

https://pub.dev/packages/pointycastle

uses url_launcher: ^6.0.12 for text-link to fluttercrypto homepage

https://pub.dev/packages/url_launcher

project is null safety

getestet auf IOS 15 und Android 11 (SDK 30)

FlutterCrypto Programm Icon gesetzt

in AndroidManifest.xml ergänzt:

    <queries>
        <!-- If your app opens https URLs -->
        <intent>
            <action android:name="android.intent.action.VIEW" />
            <data android:scheme="https" />
        </intent>
    </queries>

# To add assets to your application, add an assets section, like this:
assets:
- assets/images/flutter_crypto_raw2.png

examples: Passwort12345
Mein wichtiges Geheimnis

{
"algorithm": "AES-256 CBC PBKDF2",
"iterations": "15000",
"salt": "K+nlfiHr8pOufpT9h8YKH5umGudl4GjUddNhIDvL5nQ=",
"iv": "t62daCp/VW4e/WU8VL/nyQ==",
"ciphertext": "CwqHiM8cNe7/JMSayUnET23XMUTbqRg2LXhdpc/0ubE=",
"gcmTag": "nicht benutzt"
}

{
"algorithm": "AES-256 GCM PBKDF2",
"iterations": "15000",
"salt": "/PjJS1SedH+coSN6Oq7qbsEi1t6OTFBk2VrogqcRKfc=",
"iv": "Dvj0yWfCTNUYbsCd",
"ciphertext": "cmEVXh+b8ZrFqxGXxH6tcXEBcNocvLFS",
"gcmTag": "U/euSItxBCUaECxQAzsfrw=="
}


A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
