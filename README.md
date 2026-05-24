
---

## 📝 Méthode 2 : Créer un README plus simple (pour commencer)

Si vous voulez un README minimal mais fonctionnel :

```bash
cat > README.md << 'EOF'
# Pensee-Educ Backend

API backend pour l'application Pensee-Educ.

## Installation

\`\`\`bash
npm install
npm start
\`\`\`

## Variables d'environnement

Créer un fichier \`.env\` avec :

\`\`\`env
MONGODB_URI=votre_uri_mongodb
PORT=3000
\`\`\`

## Déploiement

Déployé sur Railway - [pensee-educ-backend.up.railway.app](https://pensee-educ-backend.up.railway.app)

## Technologies

- Node.js + Express
- MongoDB Atlas
- Redis (Upstash)
- Twilio, Cloudinary
- Orange Money, MTN Mobile Money

## Auteur

@lapenseeduc-maker
EOF

git add README.md
git commit -m "Add README documentation"
git push origin main
