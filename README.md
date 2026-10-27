# ntlc-config-maps-automation — réplica del caso NotiPlus

Estado del repositorio **después del PASO 1** del caso con resolución IA.

```
files/
├── dev/specific/properties/dev/aks/aksveu2ntlcd02/ntlc/business-ntlc-notificaciones-v1.yml
├── cert/specific/properties/cert/aks/aksveu2ntlcc02/ntlc/business-ntlc-notificaciones-v1.yml
└── prod/specific/properties/prod/aks/aksveu2ntlcp02/ntlc/business-ntlc-notificaciones-v1.yml
delivery.json
```

La `api-key` del proveedor SMS **no** está en ningún archivo: se gestiona en HashiCorp Vault.
