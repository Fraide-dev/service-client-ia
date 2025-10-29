# Service Client IA - Node-RED

Service client intelligent avec IA, déployé sur Render.com.

## Fonctionnalités

- Réponses IA automatiques
- Analyse de sentiment
- Support multilingue (FR/EN)
- Dashboard temps réel
- Sans API externe nécessaire

## 🛠️ Déploiement

1. **Connecte ce repo à Render.com**
2. **Déploie automatiquement**
3. **Accède à l'URL fournie**

## 📞 Utilisation

### Webhook d'entrée :
```bash
POST /webhook-message
Content-Type: application/json

{
  "message": "Votre message ici",
  "contexte": "support"
}
