# Guide de Configuration Google Play Console - Tuum Baore

## 📋 Checklist Complète

- [ ] Politique de confidentialité publiée
- [ ] Contenu de l'application
- [ ] Annonces
- [ ] Classification du contenu
- [ ] Cible
- [ ] Sécurité des données
- [ ] Applications gouvernementales
- [ ] Fonctionnalités financières
- [ ] Santé

---

## 1. 🔗 Politique de Confidentialité

### URL à fournir :
```
https://VOTRE_USERNAME.github.io/tuumbaore-legal/
```

**Comment obtenir cette URL :**
1. Créez un dépôt GitHub nommé `tuumbaore-legal`
2. Uploadez `index.html` (politique de confidentialité)
3. Activez GitHub Pages dans Settings → Pages
4. L'URL sera générée automatiquement

---

## 2. 📱 Décrire le contenu de votre application

### Question 1 : Contenu généré par les utilisateurs
**Réponse :** ✅ **OUI**

**Détails :**
- Les prestataires créent des services (descriptions, photos)
- Publient des informations professionnelles

### Question 2 : Modération du contenu
**Réponse :** Choisissez selon votre implémentation

**Option A - Si vous modérez :** 
- ✅ Oui, tous les contenus sont modérés
- Expliquer : "Nous révisons manuellement les nouveaux services avant publication"

**Option B - Si pas de modération immédiate :**
- ⚠️ Non, mais nous avons un système de signalement
- Les utilisateurs peuvent signaler du contenu inapproprié

**Recommandation pour le MVP :** Choisissez l'option B (plus simple)

### Question 3 : Interaction entre utilisateurs
**Réponse :** ✅ **OUI**

**Type d'interaction :**
- ☑️ Communication directe entre utilisateurs
- ☑️ Partage d'informations de contact

**Détails à fournir :**
```
Les clients peuvent contacter directement les prestataires via :
- Appels téléphoniques
- Messages WhatsApp

Ces communications se font en dehors de l'application.
```

---

## 3. 📢 Annonces

### Votre application contient-elle des annonces publicitaires ?
**Réponse :** ❌ **NON**

*(Si vous ajoutez des pubs plus tard, revenez modifier cette section)*

---

## 4. 🎯 Classification du contenu

### Type d'application
**Catégorie :** Utilitaires et productivité / Services et commerce

### Questionnaire de contenu

| Question | Réponse |
|----------|---------|
| Contient-elle de la violence ? | ❌ Non |
| Contenu sexuel ? | ❌ Non |
| Langage grossier ? | ❌ Non |
| Contenu choquant ? | ❌ Non |
| Discrimination ? | ❌ Non |
| Drogues/alcool/tabac ? | ❌ Non |
| Thèmes pour adultes ? | ❌ Non |

### Tranche d'âge résultante
**PEGI 3 / Tout public** ✅

---

## 5. 👥 Cible

### Tranche d'âge ciblée
**Réponse :** ☑️ **18 ans et plus**

**Justification :**
- Application de services professionnels
- Nécessite la majorité légale pour créer un compte prestataire
- Transactions commerciales

### Votre app est-elle destinée principalement aux enfants ?
**Réponse :** ❌ **NON**

---

## 6. 🔐 Sécurité des données (SECTION CRITIQUE)

### Types de données collectées

#### A. Informations personnelles

**Nom :**
- ✅ Collecté
- **Finalité :** Fonctionnalité de l'application (profil prestataire)
- **Obligatoire :** Oui
- **Chiffré en transit :** Oui (HTTPS)
- **Chiffré au repos :** Oui (base de données)
- **Peut être supprimé :** Oui

**Numéro de téléphone :**
- ✅ Collecté
- **Finalité :** 
  - Fonctionnalité de l'application (contact prestataire)
  - Communication (vérification compte)
- **Obligatoire :** Oui
- **Visible publiquement :** Oui (pour permettre le contact)
- **Chiffré en transit :** Oui
- **Peut être supprimé :** Oui

**Adresse email :**
- ❌ Non collectée (sauf si vous l'ajoutez)

#### B. Photos et vidéos

**Photos :**
- ✅ Collectées (photos de services)
- **Finalité :** Fonctionnalité de l'application (illustrer services)
- **Obligatoire :** Non
- **Visibles publiquement :** Oui
- **Peuvent être supprimées :** Oui

#### C. Localisation

**Localisation approximative :**
- ✅ Collectée (ville/quartier)
- **Finalité :** 
  - Fonctionnalité de l'application (recherche proximité)
  - Zones d'intervention des prestataires
- **Obligatoire :** Non (optionnel pour recherche)
- **Chiffré en transit :** Oui
- **Peut être supprimée :** Oui

**Localisation précise (GPS) :**
- ❌ Non collectée

#### D. Identifiants de l'appareil

**Identifiant de l'appareil :**
- ✅ Collecté (pour notifications, si implémenté)
- **Finalité :** Fonctionnalité de l'application
- **Obligatoire :** Non
- **Peut être supprimé :** Oui

### Pratiques de sécurité

**Chiffrement des données en transit :**
- ✅ Oui (HTTPS/TLS)

**Demande de suppression des données :**
- ✅ Oui
- **Méthode :** 
  - Via l'application (Profil → Paramètres → Supprimer compte)
  - Par email à support@tuumbaore.com

**Partage de données avec des tiers :**
- ✅ Oui (mais limité)
- **Avec qui :** Fournisseur d'hébergement uniquement
- **Finalité :** Hébergement des données
- **Type de données :** Toutes les données collectées

**Collecte de données obligatoire vs optionnelle :**
- **Obligatoire :** Nom, téléphone (pour créer compte prestataire)
- **Optionnelle :** Localisation, photos

---

## 7. 🏛️ Applications gouvernementales

### Votre application est-elle une application gouvernementale officielle ?
**Réponse :** ❌ **NON**

---

## 8. 💰 Fonctionnalités financières

### Achat ou vente de biens/services physiques
**Réponse :** ❌ **NON**

**Justification :**
```
Tuum Baore est uniquement une plateforme de mise en relation.
Nous ne gérons aucune transaction financière.
Les paiements se font directement entre clients et prestataires,
en dehors de l'application.
```

### Transactions in-app
**Réponse :** ❌ **NON**

### Services financiers
**Réponse :** ❌ **NON**

---

## 9. 🏥 Santé

### Collecte de données de santé
**Réponse :** ❌ **NON**

### Recherche ou étude clinique
**Réponse :** ❌ **NON**

---

## 📝 Récapitulatif Final

### Données collectées :
1. ✅ Nom et prénom
2. ✅ Numéro de téléphone WhatsApp
3. ✅ Photos (services)
4. ✅ Localisation approximative (ville/quartier)
5. ✅ Mot de passe (haché)

### Données NON collectées :
- ❌ Email
- ❌ Position GPS précise
- ❌ Données bancaires
- ❌ Données de santé
- ❌ Contacts téléphoniques
- ❌ Historique de navigation web

### Finalités principales :
- Création et gestion de profils prestataires
- Mise en relation clients-prestataires
- Recherche géographique de services
- Communication entre utilisateurs

### Mesures de sécurité :
- ✅ Chiffrement HTTPS/TLS
- ✅ Hachage des mots de passe
- ✅ Possibilité de suppression de compte
- ✅ Hébergement sécurisé

---

## 🚨 Points d'attention

### ⚠️ IMPORTANT : Emails de contact

Dans tous les documents et dans Google Play Console, utilisez des emails **valides et fonctionnels** :

**À modifier avant publication :**
- `privacy@tuumbaore.com` → Votre vrai email
- `support@tuumbaore.com` → Votre vrai email
- `legal@tuumbaore.com` → Votre vrai email

**Option si vous n'avez pas de domaine :**
- Utilisez Gmail : `tuumbaore.support@gmail.com`
- Créez des alias pour différentes catégories

### ⚠️ Numéro de téléphone WhatsApp uniquement burkinabé

Assurez-vous que votre code valide bien que le numéro commence par :
- `+226` (code du Burkina Faso)
- Ou `00226`
- Ou directement `226`

### ⚠️ Âge minimum 18 ans

Vérifiez que votre code bloque bien l'inscription de mineurs (même si Google ne le vérifie pas activement).

---

## ✅ Ordre de remplissage recommandé

1. **Publier la politique de confidentialité sur GitHub Pages** (1h)
2. **Remplir "Sécurité des données"** (30 min) - Le plus long
3. **Remplir "Classification du contenu"** (10 min)
4. **Remplir "Cible"** (5 min)
5. **Remplir "Contenu de l'application"** (10 min)
6. **Cocher "NON" pour Annonces, Gouvernemental, Financier, Santé** (5 min)
7. **Ajouter l'URL de la politique de confidentialité** (2 min)

**Temps total estimé : 2-3 heures**

---

## 📧 Support Google Play

Si vous avez des questions ou des rejets :
- Support Google Play Console
- Forum d'aide : https://support.google.com/googleplay/android-developer/

---

**Bonne chance avec votre publication ! 🚀**

*Guide créé pour Tuum Baore - Février 2026*
