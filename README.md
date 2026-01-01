# Le Gardien des Systèmes 👽🛡️

**Dashboard Splunk ultime de surveillance Windows + Sysmon**

[![Stars](https://img.shields.io/github/stars/cgambigh/le-gardien-des-systemes?style=social)](https://github.com/cgambigh/le-gardien-des-systemes/stargazers)
[![Forks](https://img.shields.io/github/forks/cgambigh/le-gardien-des-systemes?style=social)](https://github.com/cgambigh/le-gardien-des-systemes/network/members)
[![License](https://img.shields.io/github/license/cgambigh/le-gardien-des-systemes)](https://github.com/cgambigh/le-gardien-des-systemes/blob/main/LICENSE)
[![Version](https://img.shields.io/badge/version-v5.1-blue)](https://github.com/cgambigh/le-gardien-des-systemes/releases)

Créé par **Claude GAMBIGHA** (cgambigh)  
Formation 1337 - Niveau XX 💪  
Date : Janvier 2026

> "Je ne dors jamais. Je veille. Avec Sysmon, plus rien ne m'échappe."  
> — Le Gardien des Systèmes

## Fonctionnalités phares
- **Score de Sécurité Global** (0-100) avec sparkline et trend
- Alerte visuelle clignotante en cas de brute force massive
- Suivi complet des connexions réussies / échouées / déconnexions
- Surveillance Active Directory (créations, suppressions, modifications)
- **Intégration Sysmon avancée** :
  - Process creation suspecte (EventID 1)
  - Connexions réseau sortantes (EventID 3)
  - Injection de code / process access (EventID 10)
  - Création de fichiers malveillants (EventID 11)
- Heatmap d'activité annuelle (Security + Sysmon)
- Design dark theme ultra-lisible et impactant

## Prérequis
- Splunk Enterprise ou Cloud
- Logs Windows Security activés
- Sysmon déployé (fortement recommandé pour la section avancée)

## Installation rapide
1. Télécharge `le_gardien_des_systemes_v5.1.xml`
2. Dans Splunk : **Dashboards → Create New Dashboard → Edit Source**
3. Colle le contenu XML → Save → Profit !

## Captures d'écran

Voici à quoi ressemble un dashboard Splunk moderne en dark theme (exemples similaires à "Le Gardien") :

<grok-card data-id="2ffb09" data-type="image_card"  data-arg-size="LARGE" ></grok-card>



<grok-card data-id="4473b6" data-type="image_card"  data-arg-size="LARGE" ></grok-card>



<grok-card data-id="b1f7c4" data-type="image_card"  data-arg-size="LARGE" ></grok-card>



<grok-card data-id="d80128" data-type="image_card"  data-arg-size="LARGE" ></grok-card>


*généré avec Splunk Dashboard Studio / Classic en dark mode – ton Gardien aura le même style pro et immersif !*

## Contribution
Les pull requests sont les bienvenues !  
Si tu ajoutes des détections Sigma, des alertes ou des améliorations visuelles → je merge direct 🔥

## License
MIT License – libre d'utilisation et de modification.

---

**Star ce repo si "Le Gardien" t'a sauvé la mise un jour** ⭐  
Made with passion by cgambigh 👽💪
