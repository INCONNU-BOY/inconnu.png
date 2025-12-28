🌐 INCONNU.PNG - Cloud Storage & Media Hosting



INCONNU.PNG est une solution d'hébergement cloud complète développée par INCONNU BOY. Offrant un stockage sécurisé, une API REST puissante et une interface web moderne, cette plateforme permet d'uploader, gérer et partager des fichiers multimédias de manière professionnelle.

✨ Fonctionnalités Principales

<div align="center">

Fonctionnalité Description Icône
📁 Stockage Illimité Hébergement gratuit de fichiers 📁
⚡ Haute Performance Transfert ultra-rapide avec CDN ⚡
🔒 Sécurité Maximale Encryption SSL/TLS 🔒
🌐 Compatibilité Cross-Origin Utilisable depuis n'importe quel site 🌐
🤖 API REST Complète Documentation complète disponible 🤖
📱 Interface Responsive Design moderne et intuitif 📱
🎯 Multi-Format Support des images, vidéos, audio, documents, archives 🎯
🚀 Limite 2GB Par fichier, aucun compte requis 🚀

</div>

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
   🌐 Interface: http://localhost:3000
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
<!-- Image -->
<img src="https://inconnu-png.onrender.com/uploads/votre-image.jpg" alt="Image">

<!-- Vidéo -->
<video src="https://inconnu-png.onrender.com/uploads/votre-video.mp4" controls></video>

<!-- Background -->
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

https://img.shields.io/badge/📂_Voir_le_plugin_complet-5865F2?style=for-the-badge&logo=discord&logoColor=white

🎨 Interface Administrateur

https://img.shields.io/badge/admin-panel-8b5cf6.svg

Accédez au panneau d'administration complet avec :

· 📂 Gestion des fichiers - Upload, suppression, organisation
· 📊 Statistiques détaillées - Usage, trafic, performances
· ⚙️ Actions système - Maintenance, nettoyage, backup
· 📋 Logs d'activité - Historique complet des actions
· 💾 Backup et restauration - Sauvegarde automatique

```
🔐 Mot de passe admin: inconnuking
```

📊 Statistiques Techniques

Métrique Valeur Icône
💾 Stockage Illimité (2GB max par fichier) 💾
⚡ Vitesse Transfert optimisé ⚡
📈 Uptime 99.9% garantie 📈
🔗 CORS Entièrement compatible 🔗
🌍 CDN Distribution mondiale 🌍
🔒 Sécurité HTTPS/SSL 🔒

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

---

<div align="center">

🔗 Liens Officiels

https://img.shields.io/badge/🌐_Accéder_au_Site-000000?style=for-the-badge&logo=windowsterminal&logoColor=white
https://img.shields.io/badge/🔧_Panneau_Admin-8B5CF6?style=for-the-badge&logo=admin&logoColor=white
https://img.shields.io/badge/🧪_Tester_l'API-00D26A?style=for-the-badge&logo=test&logoColor=white

https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white
https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white
https://img.shields.io/badge/Render-00C7B7?style=for-the-badge&logo=render&logoColor=white

Développé avec ❤️ par INCONNU BOY

</div>

---

Logo SVG pour INCONNU.PNG :

```svg
<svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <defs>
        <linearGradient id="gradient" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#8B5CF6" />
            <stop offset="100%" stop-color="#00C7B7" />
        </linearGradient>
        <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
            <feDropShadow dx="0" dy="0" stdDeviation="5" flood-color="#8B5CF6" flood-opacity="0.5"/>
        </filter>
    </defs>
    
    <!-- Background Circle -->
    <circle cx="100" cy="100" r="90" fill="url(#gradient)" filter="url(#shadow)" opacity="0.9"/>
    
    <!-- Cloud Shape -->
    <path d="M60,90 Q50,70 70,60 Q90,50 110,60 Q130,70 120,90 Q140,110 110,120 Q90,130 70,120 Q50,110 60,90 Z" 
          fill="white" stroke="#4C1D95" stroke-width="3"/>
    
    <!-- Upload Arrow -->
    <path d="M100,40 L100,80 M100,40 L85,55 M100,40 L115,55" 
          stroke="#8B5CF6" stroke-width="8" stroke-linecap="round"/>
    
    <!-- File Icon -->
    <rect x="75" y="85" width="50" height="40" rx="5" fill="white" stroke="#8B5CF6" stroke-width="3"/>
    <path d="M80,95 L120,95 M80,105 L115,105 M80,115 L110,115" 
          stroke="#8B5CF6" stroke-width="2" stroke-linecap="round"/>
    
    <!-- Text -->
    <text x="100" y="170" text-anchor="middle" font-family="Arial, sans-serif" font-size="16" font-weight="bold" fill="white">
        INCONNU.PNG
    </text>
</svg>
```

Logo Minimaliste :

```svg
<svg width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
    <defs>
        <linearGradient id="minigradient" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#8B5CF6" />
            <stop offset="100%" stop-color="#00C7B7" />
        </linearGradient>
    </defs>
    
    <!-- Circle Background -->
    <circle cx="50" cy="50" r="45" fill="url(#minigradient)"/>
    
    <!-- Cloud -->
    <path d="M30,45 Q25,35 35,30 Q45,25 55,30 Q65,35 60,45 Q70,55 55,60 Q45,65 35,60 Q25,55 30,45 Z" 
          fill="white" stroke="#4C1D95" stroke-width="1.5"/>
    
    <!-- Arrow -->
    <path d="M50,20 L50,40 M50,20 L42,28 M50,20 L58,28" 
          stroke="#8B5CF6" stroke-width="4" stroke-linecap="round"/>
</svg>
```

Badge SVG pour liens :

```svg
<svg width="150" height="40" viewBox="0 0 150 40" xmlns="http://www.w3.org/2000/svg">
    <defs>
        <linearGradient id="badgegradient" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#8B5CF6" />
            <stop offset="100%" stop-color="#00C7B7" />
        </linearGradient>
    </defs>
    
    <!-- Badge Background -->
    <rect x="2" y="2" width="146" height="36" rx="18" fill="url(#badgegradient)" stroke="white" stroke-width="1"/>
    
    <!-- Small Cloud Icon -->
    <path d="M30,20 Q28,16 32,14 Q36,12 40,14 Q44,16 42,20 Q46,24 40,26 Q36,28 32,26 Q28,24 30,20 Z" 
          fill="white" stroke="#4C1D95" stroke-width="1"/>
    
    <!-- Arrow -->
    <path d="M35,12 L35,18 M35,12 L31,16 M35,12 L39,16" 
          stroke="white" stroke-width="2" stroke-linecap="round"/>
    
    <!-- Text -->
    <text x="55" y="25" font-family="Arial, sans-serif" font-size="12" font-weight="bold" fill="white">
        INCONNU.PNG
    </text>
</svg>
```

Ces logos SVG peuvent être :

1. Sauvegardés dans des fichiers .svg
2. Inclus directement dans le HTML avec <img src="logo.svg">
3. Utilisés comme favicon
4. Intégrés dans des badges et boutons

Pour les afficher dans votre README :

```markdown
![INCONNU.PNG Logo](https://inconnu-png.onrender.com/uploads/logo.svg)
```

Ou en HTML :

```html
<a href="https://inconnu-png.onrender.com" target="_blank">
    <img src="logo.svg" alt="INCONNU.PNG Logo" width="200">
</a>
```


