# 🧘 Well Tracker Ecosystem

**Well Tracker** est une solution holistique de suivi et d'analyse du bien-être. Ce projet combine une application mobile intuitive, un moteur d'intelligence artificielle performant et une infrastructure Cloud sur **Azure** pour offrir une expérience de suivi de santé complète et prédictive.

---

## 🏗️ Architecture du Projet

Le projet est structuré en deux piliers majeurs :

1.  **[Mobile App (Well_tracker)](https://github.com/Boinet-Elie/Well_tracker)** : Interface utilisateur développée en **Flutter** permettant la saisie et la visualisation des données de santé (sommeil, pas, calories).
2.  **[AI Engine (IA-Well-Tracker)](https://github.com/fuxau/IA-Well-Tracker)** : Module de Data Science en **Python** analysant les corrélations de données pour générer des scores de bien-être.

---

## ✨ Fonctionnalités Clés

*   **Dashboard Multisensoriel** : Centralisation des données de fréquence cardiaque, activité physique et sommeil.
*   **Analyse Prédictive par IA** : Identification automatique des tendances de fatigue ou de stress.
*   **Synchronisation Cloud** : Données sauvegardées et accessibles via les services **Azure**.
*   **Interface Moderne** : Design fluide et réactif grâce au framework Flutter.

---

## 🛠️ Stack Technique

| Secteur | Technologies |
| :--- | :--- |
| **Mobile** | Flutter, Dart, Material Design 3 |
| **Intelligence Artificielle** | Python, Pandas, Scikit-Learn, Jupyter |
| **Cloud & DevOps** | Microsoft Azure (App Services / Static Web Apps), Git |
| **Data** | JSON, API REST |

---

## 🌐 Déploiement Cloud (Azure)

Le projet exploite la puissance d'**Azure** pour garantir la disponibilité des services :
*   **Hébergement** : Les services sont déployés via Azure App Services.
*   **Scalabilité** : L'infrastructure est configurée pour supporter une montée en charge des analyses de données.
*   **Continuous Deployment** : Intégration possible avec GitHub Actions pour un déploiement automatisé sur Azure.

---

## ⚙️ Installation Locale

### 📱 Application Flutter
```bash
git clone [https://github.com/Boinet-Elie/Well_tracker.git](https://github.com/Boinet-Elie/Well_tracker.git)
cd Well_tracker
flutter pub get
flutter run
