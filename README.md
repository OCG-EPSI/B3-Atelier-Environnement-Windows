# 🖥️ B3 - Atelier Environnement Windows

---

## 📌 Pré-requis
- Une machine **Windows Server** (2019/2022 recommandé)  
- Au moins un **client Windows 10/11** pour les tests  
- Accès administrateur  
- Connexion réseau entre serveur et client  init

---

## 🛠️ Étapes de l’atelier
### 1️⃣ Installation et configuration du **DNS**
- Ajouter le rôle **DNS Server**
- Créer une zone de recherche directe et inversée
- Tester la résolution de noms depuis un client

---

### 2️⃣ Installation et configuration du **DHCP**
- Ajouter le rôle **DHCP Server**
- Créer un scope (plage d’adresses IP)
- Vérifier l’attribution automatique d’IP sur un client

---

### 3️⃣ Mise en place d’un **IIS** avec **WordPress**
- Installer le rôle **Web Server (IIS)**
- Ajouter PHP + MySQL/MariaDB
- Déployer WordPress et vérifier son accessibilité

---

### 4️⃣ Installation et configuration de l’**Active Directory**
- Promouvoir le serveur en **contrôleur de domaine**
- Créer des utilisateurs et groupes
- Joindre un poste client au domaine

---

### 5️⃣ Création d’une **GPO pour changer le fond d’écran**
- Créer une stratégie de groupe
- Définir un fond d’écran personnalisé
- Appliquer la GPO aux utilisateurs du domaine

---

### 6️⃣ Création d’une **GPO pour bloquer l’accès au terminal**
- Configurer la stratégie pour interdire `cmd.exe`
- Tester depuis un compte utilisateur

---

### 7️⃣ Création d’un **partage de fichiers**
- Créer un dossier partagé avec droits NTFS
- Tester l’accès depuis un client du domaine

---

### 8️⃣ GPO pour **monter automatiquement le partage de fichiers**
- Créer une GPO de mappage de lecteur réseau
- Vérifier que le lecteur apparaît au login utilisateur

---

### 9️⃣ Mise en place d’un **profil itinérant**
- Activer les profils itinérants pour certains utilisateurs
- Tester la persistance des données après reconnexion sur un autre poste

---

### 🔟 Configuration d’un **contrôleur de domaine secondaire** (AD secondaire)
- Installer un deuxième serveur Windows
- Promouvoir en **contrôleur de domaine secondaire** pour la redondance
- Vérifier la réplication AD/DNS

---

2) Installation du DHCP
3) Installation d'un IIS avec Wordpress
4) Installation de l'Active Directory ( Avec Client )
5) Mise en place d'une GPO qui change le fond d'écran 
6) Mise en place d'une GPO qui bloque l'accès au terminal
7) Créer un partage de fichier
8) Mise en place d'une GPO qui monte automatiquement le partage de fichier
9) Mise en place d'un profil itinérant pour les utilisateurs
10) Configuration d'un active directory secondaire pour la redondance