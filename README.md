# Tuum Baore - Documents Légaux

Ce dépôt contient les documents légaux pour l'application mobile Tuum Baore.

## 📄 Documents inclus

1. **Politique de Confidentialité** (`privacy-policy.md` / `index.html`)
2. **Conditions d'Utilisation** (`terms-of-service.md`)

## 🚀 Déploiement sur GitHub Pages

### Méthode 1 : Créer un nouveau dépôt

1. **Créez un nouveau dépôt GitHub** :
   - Nom : `tuumbaore-legal` (ou `tuumbaore-privacy`)
   - Public ✅
   - Cochez "Add a README file"

2. **Uploadez les fichiers** :
   ```bash
   git clone https://github.com/VOTRE_USERNAME/tuumbaore-legal.git
   cd tuumbaore-legal
   
   # Copiez les fichiers de ce dossier
   cp /chemin/vers/index.html .
   cp /chemin/vers/privacy-policy.md .
   cp /chemin/vers/terms-of-service.md .
   
   git add .
   git commit -m "Add privacy policy and terms of service"
   git push
   ```

3. **Activez GitHub Pages** :
   - Allez dans **Settings** → **Pages**
   - Source : **Deploy from a branch**
   - Branch : **main** / **root**
   - Cliquez sur **Save**

4. **Récupérez l'URL** :
   - L'URL sera : `https://VOTRE_USERNAME.github.io/tuumbaore-legal/`
   - Cette URL est à mettre dans Google Play Console !

### Méthode 2 : Ajouter au dépôt existant

Si vous avez déjà un dépôt pour Tuum Baore :

```bash
cd votre-projet-tuumbaore
mkdir docs
cp /chemin/vers/index.html docs/
cp /chemin/vers/privacy-policy.md docs/
cp /chemin/vers/terms-of-service.md docs/

git add docs/
git commit -m "Add legal documents"
git push
```

Puis dans **Settings** → **Pages** :
- Source : **Deploy from a branch**
- Branch : **main** / **/docs**
- L'URL sera : `https://VOTRE_USERNAME.github.io/VOTRE_REPO/`

## 📝 URLs pour Google Play Console

Une fois déployé, utilisez ces URLs :

- **Politique de confidentialité** : `https://VOTRE_USERNAME.github.io/tuumbaore-legal/`
- **Conditions d'utilisation** : `https://VOTRE_USERNAME.github.io/tuumbaore-legal/terms-of-service.html`

*(Vous devrez créer un fichier `terms-of-service.html` si vous voulez aussi héberger les conditions)*

## ⚙️ Personnalisation

Avant de publier, **modifiez** :

1. **Les emails de contact** dans les documents :
   - `privacy@tuumbaore.com`
   - `support@tuumbaore.com`
   - `legal@tuumbaore.com`

2. **L'adresse physique** (si nécessaire)

3. **Les dates** si vous déployez plus tard

## 🔄 Mise à jour

Pour mettre à jour les documents :

```bash
# Modifiez les fichiers
git add .
git commit -m "Update privacy policy"
git push
```

Les changements seront visibles sous quelques minutes.

## ✅ Checklist pour Google Play

- [ ] Politique de confidentialité publiée sur GitHub Pages
- [ ] URL ajoutée dans Google Play Console
- [ ] Emails de contact valides
- [ ] Date de dernière mise à jour correcte
- [ ] Vérifier que la page s'affiche correctement sur mobile

## 📱 Intégration dans l'app

Dans votre application React Native, ajoutez des liens vers ces documents :

```javascript
// Dans votre écran de paramètres ou d'inscription
<TouchableOpacity onPress={() => Linking.openURL('https://VOTRE_URL/privacy-policy.html')}>
  <Text>Politique de Confidentialité</Text>
</TouchableOpacity>

<TouchableOpacity onPress={() => Linking.openURL('https://VOTRE_URL/terms-of-service.html')}>
  <Text>Conditions d'Utilisation</Text>
</TouchableOpacity>
```

## 🇧🇫 Conformité Burkina Faso

Ces documents sont adaptés pour :
- Le contexte burkinabé
- Les numéros WhatsApp locaux
- Les lois applicables au Burkina Faso
- Les exigences de Google Play Store

## 📞 Support

Pour toute question, contactez : support@tuumbaore.com

---

**Tuum Baore - Grenier des Métiers** 🇧🇫
