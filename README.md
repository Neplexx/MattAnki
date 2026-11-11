<div align="center">

# 🧠 MattAnki

**La répétition espacée moderne, fluide et respectueuse de votre vie privée.**

[![PWA Live](https://img.shields.io/badge/Web_App-Disponible-6366f1?style=for-the-badge&logo=pwa&logoColor=white)](https://neplexx.github.io/MattAnki/)
[![Releases](https://img.shields.io/github/v/release/neplexx/MattAnki?style=for-the-badge&label=T%C3%A9l%C3%A9charger&color=10b981)](https://github.com/neplexx/MattAnki/releases)
[![Plateformes](https://img.shields.io/badge/Plateformes-Windows_%7C_macOS_%7C_Linux_%7C_Web-8b5cf6?style=for-the-badge)](https://github.com/neplexx/MattAnki/releases)
[![Stockage](https://img.shields.io/badge/Synchronisation-Google_Drive_Priv%C3%A9-ea4335?style=for-the-badge&logo=googledrive&logoColor=white)](#-synchronisation-privée-google-drive)

<br/>

[🚀 Lancer la Web App (PWA)](https://neplexx.github.io/MattAnki/) • [💻 Télécharger pour Desktop](https://github.com/neplexx/MattAnki/releases) • [🔒 Synchronisation](#-synchronisation-privée-google-drive) • [📖 Fonctionnalités](#-fonctionnalités-phares)

</div>

---

## 🌟 Présentation

**MattAnki** est une application d'apprentissage par **répétition espacée (SRS)** pensée pour maximiser la mémorisation à long terme tout en éliminant la complexité superflue.

Conçue avec une interface sombre moderne, épurée et sans distraction, MattAnki réinvente l'expérience de révision pour vous permettre de vous concentrer sur l'essentiel : **apprendre efficacement et sans friction**, que vous soyez sur ordinateur, tablette ou smartphone.

---

## 🚀 Accès Rapide

| Version | Format | Accès / Téléchargement |
| :--- | :--- | :--- |
| **🌐 Web App (PWA)** | Navigateur & Mobile (iOS / Android) | [**neplexx.github.io/MattAnki**](https://neplexx.github.io/MattAnki/) |
| **🪟 Windows** | `.exe` (Installateur standard) / `.msi` | [**Télécharger sur GitHub Releases**](https://github.com/neplexx/MattAnki/releases) |
| **🍎 macOS** | `.dmg` | [**Télécharger sur GitHub Releases**](https://github.com/neplexx/MattAnki/releases) |
| **🐧 Linux** | `.deb` / `.AppImage` | [**Télécharger sur GitHub Releases**](https://github.com/neplexx/MattAnki/releases) |

---

## ✨ Fonctionnalités Phares

- **🎨 Ergonomie Repensée** : Une interface sombre néo-moderne soignée, intuitive, et pensée pour réduire la fatigue oculaire lors des longues sessions d'étude.
- **⚡ Performance & Légèreté** :
  - **Sur Desktop** : Propulsé par **Tauri v2** et un cœur natif en **Rust**, garantissant un démarrage instantané et une consommation mémoire minime (< 50 Mo de RAM).
  - **Sur le Web** : Moteur de base de données **SQLite WebAssembly** intégré pour une réactivité totale directement dans le navigateur.
- **📱 PWA Installable & Mode Hors-ligne** : Installez MattAnki sur votre iPhone, iPad ou smartphone Android en un clic depuis votre navigateur. Vos données sont disponibles localement à tout moment.
- **📊 Prévisions & Statistiques** : Visualisez d'un coup d'œil le volume de cartes à réviser au cours des jours à venir pour mieux planifier vos sessions.
- **🔄 Importation Anki (.apkg)** : Importez facilement vos paquets existants pour continuer vos révisions sans repartir de zéro.

---

## 🔒 Synchronisation Privée Google Drive

Contrairement à la majorité des services cloud, **MattAnki ne stocke aucune de vos données sur des serveurs propriétaires**.

```
[ Vos Cartes & Progression ]
             │
             ▼
  [ Chiffrement & Sandbox ]
             │
             ▼
[ Votre Google Drive Personnel (appDataFolder) ]
             ▲
             │
    Synchronisation directe
(PC 💻 ⟷ Web PWA 📱 ⟷ Tablette)
```

- **Zero-Knowledge** : Vos paquets de cartes, votre historique et vos statistiques sont stockés exclusivement sur **votre propre compte Google Drive personnel**.
- **Dossier d'application isolé (`appDataFolder`)** : MattAnki n'a accès qu'à son dossier réservé et n'a **aucun accès** à vos autres fichiers personnels Google Drive.
- **Synchronisation transparente** : Retrouvez votre état d'apprentissage à jour entre votre ordinateur de bureau et votre smartphone en un clic sur le bouton *Synchroniser*.

---

## 📲 Installer la Web App sur Mobile (PWA)

Vous pouvez utiliser MattAnki comme une véritable application native sur votre smartphone :

### Sur iOS (iPhone / iPad) :
1. Ouvrez [**https://neplexx.github.io/MattAnki/**](https://neplexx.github.io/MattAnki/) dans **Safari**.
2. Appuyez sur le bouton **Partager** (icône rectangle avec flèche vers le haut).
3. Sélectionnez **Sur l'écran d'accueil**.

### Sur Android :
1. Ouvrez [**https://neplexx.github.io/MattAnki/**](https://neplexx.github.io/MattAnki/) dans **Chrome**.
2. Appuyez sur le menu **⋮** en haut à droite.
3. Sélectionnez **Installer l'application** ou **Ajouter à l'écran d'accueil**.

---

## 📄 Mentions Légales & Confidentialité

- [Politique de confidentialité](https://neplexx.github.io/MattAnki/privacy)
- [Conditions d'utilisation](https://neplexx.github.io/MattAnki/terms)

MattAnki est une application gratuite pour un usage personnel. Tous droits réservés.
