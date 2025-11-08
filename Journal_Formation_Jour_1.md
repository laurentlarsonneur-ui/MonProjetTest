# 🧭 Synthèse — Jour 1 / Semaine 1 : Mise en place de l’environnement

_Date : 08/11/2025_

---

## ⚙️ Objectif du jour
Installer, configurer et tester les outils nécessaires au programme d’autoformation :  
langages (C, C#, Java, VBA), bases de données SQL Server, et outils de versionnement Git/GitHub.

---

## 🧰 1. Environnement installé et vérifié

| Domaine | Outils / Actions principales | Résultat |
|----------|------------------------------|-----------|
| **C / C++ / C#** | Visual Studio 2022 – test “Hello World” | ✅ Fonctionnel |
| **Java** | JDK 21 + IntelliJ IDEA Community – test de version | ✅ OK |
| **Base de données** | SQL Server + SSMS – test de connexion et configuration | ✅ OK après réglages SSL |
| **Versionnement** | Git + GitHub – installation, compte, dépôt local et distant | ✅ OK avec token personnel |
| **Journal** | Utilisation de StackEdit (Markdown web) pour le suivi | ✅ Solution retenue |

---

## 🧩 2. Points techniques abordés

- Configuration SQL Server : instances multiples (`MSSQLSERVER`, `TEW_SQLEXPRESS`), activation TCP/IP, désactivation du chiffrement forcé.  
- Erreurs rencontrées et corrigées :
  - SSL non approuvé  
  - Instance inaccessible  
  - Erreur WMI → recompilation du fichier MOF  
- Tests de connexions :
  - SSMS ↔ SQL Server  
  - Visual Studio (C#) ↔ SQL Server  
  - IntelliJ (Java) ↔ SQL Server (ajout du bon driver JDBC)

---

## 🌐 3. Git & GitHub

- Création d’un dépôt local et d’un dépôt distant GitHub.  
- Configuration HTTPS avec **token personnel GitHub** (PAT).  
- Synchronisation locale ↔ distante :
  - Résolution des erreurs classiques :
    - `src refspec main does not match any`
    - `refusing to merge unrelated histories`
    - `Automatic merge failed` → résolution de conflit dans `README.md`
- Vérification du stockage sécurisé des identifiants via `manager-core`.

---

## 📘 4. Bilan du jour

| Domaine | Objectif atteint |
|----------|------------------|
| Installation et tests des IDEs | ✅ |
| Configuration SQL Server et SSMS | ✅ |
| Connexions depuis C#, Java | ✅ |
| Installation et tests Git/GitHub | ✅ |
| Outil de suivi Markdown choisi (StackEdit) | ✅ |

🟢 **Statut final du jour 1 : Environnement complet prêt, bases fonctionnelles validées.**
