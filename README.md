
🌐 INCONNU.PNG - Cloud Storage & Media Hosting

<div align="center">

https://inconnu-png.onrender.com/uploads/Screenshot_20251227-210150_1766880189894_avm1iw2u5g.png

Professional Cloud Storage Solution · High Performance · Cross-Origin Compatible · Free & Unlimited

https://img.shields.io/badge/status-online-success.svg
https://img.shields.io/badge/version-2.0.0-blue.svg
https://img.shields.io/badge/license-MIT-green.svg
https://img.shields.io/badge/discord-join-7289da.svg
https://img.shields.io/badge/deploy-render-00c7b7.svg

🌐 Website · 📚 Documentation · 🛠 API Reference · 🤖 Discord Bot

</div>

---

🇫🇷 Version Française

🚀 Présentation

INCONNU.PNG est une solution d'hébergement cloud complète développée par INCONNU BOY. Offrant un stockage sécurisé, une API REST puissante et une interface web moderne, cette plateforme permet d'uploader, gérer et partager des fichiers multimédias de manière professionnelle.

✨ Fonctionnalités Principales

· 📁 Stockage Illimité - Hébergement gratuit de fichiers
· ⚡ Haute Performance - Transfert ultra-rapide avec CDN
· 🔒 Sécurité Maximale - Encryption SSL/TLS
· 🌐 Compatibilité Cross-Origin - Utilisable depuis n'importe quel site
· 🤖 API REST Complète - Documentation complète disponible
· 📱 Interface Responsive - Design moderne et intuitif
· 🎯 Multi-Format - Support des images, vidéos, audio, documents, archives
· 🚀 Limite 2GB - Par fichier, aucun compte requis

🛠 Installation Rapide

1. Clonez le dépôt
   ```bash
   git clone https://github.com/INCONNU-BOY/inconnu-png.git
   cd inconnu-png
   ```
2. Installez les dépendances
   ```bash
   npm install
   ```
3. Configurez le serveur
   ```javascript
   // .env
   PORT=3000
   ADMIN_PASSWORD=votre_mot_de_passe
   UPLOAD_DIR=./uploads
   ```
4. Démarrez le serveur
   ```bash
   npm start
   ```
5. Accédez à l'interface
   ```
   🌐 http://localhost:3000
   🔧 Admin: http://localhost:3000/admin
   📊 API: http://localhost:3000/api/test
   ```

📡 API REST - Endpoints Disponibles

Méthode Endpoint Description Authentification
GET / Interface web principale Publique
POST /upload Uploader un fichier Publique
GET /api/files Lister tous les fichiers Publique
DELETE /api/files/:filename Supprimer un fichier Publique
GET /api/stats Statistiques du serveur Publique
POST /api/login Authentification admin Mot de passe
GET /api/test Tester l'API Publique
GET /api/health Santé du serveur Publique

📝 Exemples d'Utilisation

Upload via cURL

```bash
curl -X POST -F "file=@image.jpg" https://inconnu-png.onrender.com/upload
```

JavaScript Fetch

```javascript
const formData = new FormData();
formData.append('file', fileInput.files[0]);

fetch('https://inconnu-png.onrender.com/upload', {
    method: 'POST',
    body: formData
})
.then(response => response.json())
.then(data => console.log(data.url));
```

Intégration HTML

```html
<img src="https://inconnu-png.onrender.com/uploads/votre-image.jpg" alt="Image">

<video src="https://inconnu-png.onrender.com/uploads/votre-video.mp4" controls></video>

<div style="background-image: url('https://inconnu-png.onrender.com/uploads/background.jpg')">
    <!-- Contenu -->
</div>
```

Markdown

```markdown
![Description](https://inconnu-png.onrender.com/uploads/image.jpg)
```

🤖 Plugin Discord Bot

Intégrez INCONNU.PNG directement dans votre bot Discord :

```javascript
// Installation
npm install axios form-data

// Commandes disponibles
!upload    # Upload un fichier attaché
!urls      # Liste les fichiers
!urlstats  # Statistiques du serveur
!shorten   # Raccourcir une URL
```

Voir le plugin complet

🎨 Interface Administrateur

https://img.shields.io/badge/admin-panel-8b5cf6.svg

Accédez au panneau d'administration complet avec :

· Gestion des fichiers
· Statistiques détaillées
· Actions système
· Logs d'activité
· Backup et restauration

```
🔐 Mot de passe admin: inconnuking
```

📊 Statistiques Techniques

· 💾 Stockage: Illimité (2GB max par fichier)
· ⚡ Vitesse: Transfert optimisé
· 📈 Uptime: 99.9% garantie
· 🔗 CORS: Entièrement compatible
· 🌍 CDN: Distribution mondiale
· 🔒 Sécurité: HTTPS/SSL

🚀 Déploiement sur Render

1. Créez un compte sur Render.com
2. Nouveau Web Service
3. Connectez votre dépôt GitHub
4. Configuration :
   ```
   Build Command: npm install
   Start Command: npm start
   Plan: Free
   ```
5. Variables d'environnement :
   ```
   PORT: 10000
   NODE_ENV: production
   ```

📄 Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

