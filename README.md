

````markdown
# Module PrestaShop : Formulaire de Contact Personnalisé

## 📝 Description
Ce module PrestaShop permet d'ajouter un formulaire de contact avancé et personnalisé sur votre boutique. Il offre une gestion simplifiée via le back-office et une interface utilisateur moderne côté front-end.

**Fonctionnalités clés :**
* ✅ **Interface d’administration dédiée** : Gérez vos messages directement depuis le back-office.
* ✅ **Validation JavaScript** : Retour d’état en temps réel pour l’utilisateur.
* ✅ **Design responsive** : Adapté aux mobiles et tablettes.
* ✅ **Structure MVC** : Code propre respectant l’architecture PrestaShop.

---

## 🚀 Installation

1. **Téléchargement** : Téléchargez le dossier du module (ou clonez le dépôt).
2. **Compression** : Compressez le dossier en `formulaire.zip`.
3. **Upload** : Allez dans votre back-office PrestaShop > **Modules** > **Gestionnaire de modules**.
4. **Installation** : Cliquez sur « Installer un module » et glissez-y le fichier ZIP.

Ou via Git (dans le dossier `/modules`) :

```bash
git clone https://github.com/mohameden19961/formulaire.git
````

---

## 📂 Structure du projet

```
formulaire/
├── classes
│   └── formulaire.class.php
├── config_fr.xml
├── controllers
│   └── admin
│       └── AdminFormulaire.php
├── formulaire.php
├── logo.png
└── views
    ├── css
    │   └── styles.css
    ├── img
    │   ├── 6084255.jpg
    │   ├── logo1.png
    │   └── logo.png
    ├── js
    │   └── script.js
    └── templates
        ├── admin
        │   └── view.tpl
        └── front
            └── formulaire.tpl
```

---

## 🛠️ Technologies utilisées

* **PHP** (logique serveur PrestaShop)
* **Smarty** (moteur de templates)
* **JavaScript** (interactions et statut des messages)
* **CSS** (mise en forme personnalisée)

---

## 📸 Aperçu

### Formulaire côté client

<img src="https://github.com/user-attachments/assets/6f03aed4-108d-4395-9d4b-ce3e30c9022d" width="600"/>

### Liste des messages

<img src="https://github.com/user-attachments/assets/ce02c256-7390-41e3-ad66-52724072fdc6" width="800"/>

### Détail d’un message

<img src="https://github.com/user-attachments/assets/5e59211a-3927-4855-888a-254d2bb0a151" width="800"/>

### Ajout / Modification d’un formulaire

<img src="https://github.com/user-attachments/assets/00f6f54d-13c9-4107-a7ca-9ea104bf759e" width="800"/>

### Page de configuration du module

<img src="https://github.com/user-attachments/assets/cd424f51-64c8-4f1d-9fa5-4a44970ec8b9" width="800"/>

---

## 👤 Auteur

**Abdy Mohameden**

* GitHub : [mohameden19961](https://github.com/mohameden19961)
```
