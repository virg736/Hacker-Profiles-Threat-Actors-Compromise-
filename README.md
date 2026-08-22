
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Educational](https://img.shields.io/badge/Purpose-Educational-blue)
![Defensive Security](https://img.shields.io/badge/Security-Defensive-important)
![Ethical](https://img.shields.io/badge/Ethical-Yes-success)
<p align="center">
  <img src="Hacker_profiles_threat_actor.PNG" alt="Hacker Profiles Cover" width="100%">
</p>


<hr>

<h1 align="center">
  Profils d'attaquants & niveaux de menace<br>
  (Threat Actors)
</h1>

<p align="center">
  © 2026 <strong>Virginie Lechene</strong> 
</p>

<p align="center">
  <img src="https://licensebuttons.net/l/by-nc/4.0/88x31.png" alt="Creative Commons BY-NC">
</p>

---

Ce chapitre présente une **classification des profils d’attaquants** couramment rencontrés en cybersécurité, ainsi qu’une **estimation de leur niveau de menace**.

L’objectif est de **mieux comprendre les comportements, motivations et capacités** des différents acteurs malveillants, afin d’adapter les stratégies de défense et de prévention.

---

## 📑 Sommaire

- [Objectif du projet](#objectif-du-projet)
- [Profils de menace](#profils-de-menace)
  - [Niveau faible – Low Threat](#niveau-faible--low-threat)
  - [Niveau moyen – Medium Threat](#niveau-moyen--medium-threat)
  - [Niveau élevé – High Threat](#niveau-eleve--high-threat)
  - [Niveau critique – Critical Threat](#niveau-critique--critical-threat)
- [Synthèse des profils](#synthese-des-profils)
- [Implications pour la défense](#implications-pour-la-defense)
- [Panorama des menaces](#panorama-des-menaces)
  - [Ingénierie sociale](#ingenierie-sociale-facteur-humain)
  - [Attaques sur les mots de passe](#attaques-sur-les-mots-de-passe)
  - [Vulnérabilités logicielles](#vulnerabilites-logicielles)
  - [Réseaux et infrastructure](#reseaux--infrastructure)
  - [Systèmes et serveurs](#systemes--serveurs)
  - [Cloud et services en ligne](#cloud--services-en-ligne)
  - [Chaîne d’approvisionnement](#chaine-dapprovisionnement-supply-chain)
  - [Logiciels malveillants](#logiciels-malveillants-malware)
  - [Accès physiques](#acces-physiques)
  - [Erreurs humaines et organisationnelles](#erreurs-humaines--organisationnelles)
- [Scénario : Ingénierie sociale](#scenario--ingenierie-sociale--phishing-interne)
- [Démonstration d’attaque](#demonstration-dattaque--ingenierie-sociale--exposition-de-service)
- [Cadre du projet](#cadre-du-projet)
- [Cadre éthique du projet](#cadre-ethique-du-projet)
- [Conclusion](#conclusion)
- [Licence](#licence)

---

- [Démonstration en environnement contrôlé](#démonstration-en-environnement-contrôlé)

---

# Pourquoi classifier les attaquants ?

Tous les attaquants ne disposent **ni du même niveau technique, ni des mêmes ressources, ni des mêmes objectifs.**

Comprendre **le profil, les motivations et les capacités d’un attaquant** aide à adapter les mesures de défense.

---

## Profils de menace

---

<h3 align="center">Threat Levels</h3>

<p align="center">
  <img src="threat_levals.PNG" alt="Threat Levels" width="600">
</p>

## 🟢 Profil : Script Kiddie

- Compétences techniques généralement limitées
- Utilise souvent des outils existants avec une compréhension technique limitée
- Motivations possibles : curiosité, défi, reconnaissance
- Impact variable selon la cible et les outils utilisés

➡️ **Profil souvent opportuniste, avec un niveau de sophistication généralement limité.**

---

## 🟠 Profil : Phisher / Ingénieur social

- Exploite principalement le facteur humain
- Peut être efficace sans compétences techniques avancées
- S’appuie sur la manipulation psychologique, la confiance ou l’urgence
- Impact variable selon la cible et les informations obtenues

### Hacktiviste

- Motivations souvent idéologiques, sociales ou politiques
- Recherche fréquemment la visibilité ou un impact médiatique
- Peut provoquer des interruptions de service ou des fuites d’informations
- Capacités techniques très variables selon les individus ou les groupes

➡️ **Ces profils peuvent présenter des niveaux de sophistication et d’impact très variables selon le contexte.**


---

## 🔴 Profils : Cybercriminel / Opérateur de malware / Opérateur de botnet

### Cybercriminel

- Motivation souvent financière
- Peut agir seul ou au sein d’une organisation structurée
- Peut mener des attaques répétées ou ciblées
- Capacités techniques variables selon les individus ou les groupes

### Opérateur de malware

- Développe ou utilise des logiciels malveillants
- Peut chercher à maintenir un accès persistant aux systèmes
- Capacités variables selon les outils et les objectifs

### Opérateur de botnet

- Contrôle ou exploite des réseaux de machines compromises
- Peut être utilisé pour des attaques massives ou coordonnées
- Impact variable selon la taille du botnet et la cible

➡️ **Ces profils peuvent présenter un niveau de sophistication et un impact importants, mais variables selon le contexte.**


---

## ⚫ Profils : Opérateur de ransomware / Menace interne / APT

### Opérateur de ransomware

- Utilise des rançongiciels pour chiffrer ou exfiltrer des données
- Peut provoquer des impacts financiers, opérationnels et juridiques importants
- Les attaques peuvent être opportunistes ou très préparées
- Impact variable selon la cible et l’étendue de la compromission

### Menace interne (Insider Threat)

- Dispose d’un accès légitime ou autorisé à certaines ressources
- Connaît généralement l’environnement interne
- Peut être malveillante, négligente ou accidentelle
- Peut être difficile à détecter selon le contexte

### APT (Advanced Persistent Threat)

- Dispose généralement de ressources et de capacités importantes
- Mène souvent des opérations discrètes et de longue durée
- Peut viser l’espionnage, le sabotage ou des objectifs stratégiques
- Certaines APT sont associées à des États, mais ce n’est pas systématique

➡️ **Ces profils peuvent présenter un impact très important, selon leurs objectifs, leurs capacités et la cible visée.**

## ⚫ Niveau CRITIQUE - Critical Threat

### Opérateur de ransomware
- Chiffrement des données et extorsion
- Impacts financiers, opérationnels et juridiques majeurs
- Attaques souvent très bien préparées

### Menace interne (Insider Threat)
- Accès légitime aux systèmes
- Connaissance de l’environnement interne
- Difficile à détecter

### APT (Advanced Persistent Threat – acteur étatique)
- Ressources importantes
- Attaques discrètes et sur le long terme
- Espionnage, sabotage, déstabilisation stratégique

➡️ **Menace maximale**, ciblée et persistante.

---

##  Synthèse des profils

- Tous les attaquants ne nécessitent pas des exploits complexes
- Les attaques les plus efficaces exploitent souvent :
  - la confiance
  - les erreurs humaines
  - les mauvaises configurations
- Le niveau de menace dépend autant de la **motivation** que du **niveau technique**

---

##  Implication pour la défense

Une stratégie de sécurité efficace doit :
- intégrer la dimension humaine
- prendre en compte les profils d’attaquants réalistes
- adapter les contre-mesures au niveau de menace
- renforcer la sensibilisation et les procédures internes

---


# Panorama des menaces - Pentest & Sensibilisation à la cybersécurité

Chaîne d’attaque simplifiée (vue globale)

[Humain]
   ↓
[Erreur]
   ↓
[Exposition]
   ↓
[Accès]
   ↓
[Impact]

Points de défense :
- Sensibilisation & formation (Humain / Erreur)
- Procédures & contrôles (Exposition)
- MFA / ACL / Durcissement (Accès)
- Logs / Surveillance / Détection (Impact)

Ce projet propose une **vue d’ensemble des principales méthodes utilisées lors des compromissions de systèmes**, avec une approche **pédagogique, analytique et défensive**.

L’objectif n’est **pas** de montrer *comment attaquer*, mais de **comprendre pourquoi et comment les attaques fonctionnent dans le monde réel**, afin de mieux les prévenir.


<p align="center">
  <img src="threat_actor-profiles.PNG" alt="Threat Actor Profiles" width="800">
  <br>
  <em>Threat actor profiles overview</em>
</p>


---

##  1. Ingénierie sociale (facteur humain)

**Exploiter le comportement humain plutôt que les failles techniques.**

L’ingénierie sociale cible la **confiance**, les **habitudes** et les **émotions** des utilisateurs.

**Techniques courantes :**
- Phishing (emails, SMS, appels)
- Spear-phishing (attaques ciblées)
- Faux support technique
- Faux profils et arnaques sur les réseaux sociaux
- Manipulation psychologique (urgence, peur, autorité, confiance)
- Shoulder surfing (observation de la saisie d’informations sensibles)
- Usurpation d’identité

🔑 **Il s’agit du vecteur d’attaque n°1 dans le monde réel.**

---

## 🔐 2. Attaques sur les mots de passe

**Lorsque les mécanismes d’authentification sont faibles ou mal gérés.**

- Mots de passe faibles ou réutilisés
- Fuites de bases de données
- Credential stuffing (réutilisation de mots de passe compromis)
- Attaques par force brute
- Absence d’authentification multifacteur (MFA / 2FA)

---

##  3. Vulnérabilités logicielles

**Exploiter des bugs ou des failles connues dans les logiciels.**

- Logiciels non mis à jour
- Failles zero-day
- CMS vulnérables (WordPress, plugins, thèmes, etc.)
- Applications mal conçues ou mal codées
- Dépendances compromises ou vulnérables

---

## 🌐 4. Réseaux & infrastructure

**Problèmes de configuration ou de conception réseau.**

- Réseaux Wi-Fi mal sécurisés
- Routeurs ou box mal configurés
- Ports ouverts inutilement
- VPN mal configurés
- Réseaux publics non sécurisés
- Attaques de type Man-in-the-Middle (MITM)

---

##  5. Systèmes & serveurs

**Accès abusifs ou non autorisés aux machines.**

- Mauvaise gestion des droits et privilèges
- Comptes administrateurs exposés
- Services inutiles actifs
- Accès distants mal sécurisés
- Manque de supervision et de journalisation

---

## ☁️ 6. Cloud & services en ligne

**Une source très fréquente d’incidents aujourd’hui.**

- Stockage cloud exposé publiquement par erreur
- Clés API ou secrets exposés
- Mauvaise configuration des permissions
- Comptes SaaS compromis
- Sauvegardes accessibles publiquement

---

##  7. Chaîne d’approvisionnement (Supply Chain)

**Cibler un fournisseur plutôt que la victime finale.**

- Mises à jour logicielles compromises
- Librairies ou dépendances infectées
- Prestataires mal sécurisés
- Détournement d’outils légitimes

---

##  8. Logiciels malveillants (Malware)

**Installer un programme malveillant sur la machine de la victime.**

- Virus
- Chevaux de Troie
- Rançongiciels
- Spywares / keyloggers
- Backdoors
- Fichiers piégés (PDF, ZIP, EXE)

---

##  9. Accès physiques

**Souvent sous-estimés, mais très efficaces.**

- Clés USB piégées
- Postes de travail laissés déverrouillés
- Vols d’ordinateurs ou de téléphones
- Espionnage direct
- Accès non autorisé aux locaux

---

##  10. Erreurs humaines & organisationnelles

**Sans attaque technique directe.**

- Mauvaises configurations
- Secrets exposés (GitHub, forums, dépôts publics…)
- Absence de sauvegardes
- Mauvaise gestion des employés
- Manque de formation et de sensibilisation à la sécurité

---

##  Conclusion

 **Le hacking n’est presque jamais “magique”**  
 Il repose principalement sur :
- des erreurs humaines  
- de la négligence  
- une confiance excessive  
- des systèmes mal protégés  

Les incidents de sécurité sont généralement le résultat de **faiblesses cumulées**, et non d’une attaque sophistiquée isolée.

---


## Scénario : Ingénierie sociale - Phishing interne

### Attaquant (Parrot)
- Profil : Phisher
- Méthode : Mail RH urgent
- Technique : Urgence + confiance
- Objectif : Accès aux données internes

### Victime (Debian)
- Profil : Employé standard
- Action : Réception du mail
- Erreur : Confiance excessive
- Impact : Données internes exposées

### Pourquoi l’attaque fonctionne
- Facteur humain
- Absence de vérification
- Autorité perçue

### Mesures de prévention
- Sensibilisation
- Procédures internes
- Vérification des mails

<p align="center">
  <img src="phisting_internal_access_simulation.png" width="45%" />
  <img src="victim_phisting_mail_opened.png" width="45%" />
</p>


---

J’ai simulé un serveur interne RH sur une machine Debian.  
Ce serveur était accessible sans authentification sur le réseau interne.  
Depuis une machine attaquante (Parrot), j’ai pu accéder directement aux données confidentielles avec une simple requête HTTP.  
Cela démontre qu’une mauvaise configuration suffit à exposer des données sensibles, même sans malware.

---

## Démonstration d’attaque - Ingénierie sociale & exposition de service

### Contexte
Simulation d’une attaque interne suite à une mauvaise configuration.

### Environnement
- Attaquant : Parrot OS
- Victime : Debian
- Réseau : 192.168.100.0/24

### Scénario
Un employé reçoit un mail interne des RH.  
Un service interne est exposé sans protection.

### Attaque

`curl http://192.168.100.10:8080`

<p align="center">
  <img src="attack_internal_service_access.png" width="45%">
  <img src="victim_internal_service_exposed.png" width="45%">
</p>


----

## ⚖️ Cadre du projet

Ce contenu est :
- pédagogique
- orienté analyse et prévention
- sans démonstration offensive
- sans attaque réelle
- réalisé dans un cadre éthique et contrôlé

---

### ⚖️ Cadre éthique du projet

Ce projet est :
- à visée pédagogique  
- orienté défense et sensibilisation  
- réalisé dans un environnement contrôlé et isolé  
- sans attaque réelle ni exploitation illégale  

---

✍️ Auteur : *Virginie Lechene*

---

## Licence
Le script est publié sous la licence MIT.

## À propos de l’usage
Ce projet est destiné exclusivement à des fins pédagogiques, notamment dans le cadre de :
- d’une formation en cybersécurité,
- de tests d’intrusion légaux (pentest),
- d’analyses réseau dans un environnement contrôlé.

⚠️ L’auteure ne cautionne ni n’autorise l’utilisation de ce script en dehors d’un cadre légal strictement défini.
Toute utilisation non conforme est interdite et relève uniquement de la responsabilité de l’utilisateur.


## 📷 Droits sur les visuels

Les visuels de ce dépôt sont protégés par la licence CC BY-ND 4.0.
Attribution obligatoire – Modification interdite.

© 2026 Virginie Lechene
