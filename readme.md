# Ejemplo HTML/JS para integraci�n API.AI + BotLibre 3D Avatar

C�digo de integraci�n de un bot de API.AI conectado a un avatar animado de Botlibre funcionando en navegador.

### Autor: Patricio Gerpe

![Avatar](/images/prevista.png)

## TUTORIAL
https://planetachatbot.com/tutorial-paso-a-paso-corre-tu-chatbot-en-tu-web-conectado-a-un-avatar-3d-animado-usando-a81aab24ad8f

# Requisitos

* Un agente en API.AI https://www.api.ai
* Una cuenta en BotLibre https://www.botlibre.com

# Instalaci�n

* Bajas el repositorio
* Entras al directorio del repositorio -> javascripts -> ai.js

En ese script cambias los tokens de las APIs de API.AI y Botlibre:

```javascript
// ACA VA TU APPLICATION ID DE BOT LIBRE
SDK.applicationId = "<botLibreApplicationID>";

// ACA VA EL ID DE TU AVATAR EN BOT LIBRE
web.avatar = "<avatarID>";

// ACA VA EL ACCESSTOKEN DE TU AGENTE EN API.AI
var accessToken = "<apiAIaccessToken>";
```

! Pronto versi�n 2.0 integrada a una aplicaci�n de Node-Express con script funcionando en back-end.