# Farmaci & Integratori Tracker

App per tracciamento giornaliero farmaci e integratori.

## Deploy su Render

1. Push questa cartella su un repo GitHub
2. Su [render.com](https://render.com) → **New** → **Static Site**
3. Collegare il repo GitHub
4. Impostazioni:
   - **Build Command**: lasciare vuoto (o `echo done`)
   - **Publish Directory**: `.`
5. **Create Static Site**

## PWA

Una volta aperta l'app dal browser mobile:
- **iOS**: Safari → Condividi → "Aggiungi alla schermata Home"
- **Android**: Chrome → menu → "Installa app"

L'app funziona offline dopo la prima visita.

## Dati

I dati sono salvati in `localStorage` del browser — rimangono sul dispositivo.
