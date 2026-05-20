# Amics Castelló — App de gestió de cantera 🏀

Aplicació de gestió esportiva per al Club Amics del Bàsquet Castelló.  
Basada en la infraestructura de l'app del CD La Magdalena, completament adaptada al bàsquet.

## Equipos incluidos (cantera real del club)

Baby · Prebenjamín · Benjamín A/B · Alevín A/B/C/Verde/Blanco · Infantil A/B/C/Verde/Blanco/Azul · Cadete A/B/C/Verde/Blanco/Rojo/Azul · Junior A/B/C · Senior

## Posiciones (FEB)

Base (1) · Escolta (2) · Alero (3) · Ala-Pívot (4) · Pívot (5) + variantes mixtas

## Estadísticas por partido

Min · Pts · Ast · Reb · Reb.Of · Tap · Rob · Perd · Falt · Nota

## Categorías de ejercicios

Técnico · Táctico · Físico · Específico por posición · Estratégico · Globalizado/Juego real · Psicológico · Contraataque · Defensa zona · Bloqueo directo/P&R · Tiro · Juego de poste · Calentamiento

## Pizarra táctica

Cancha de baloncesto completa o media cancha con zonas pintadas, línea de 3 puntos y aros.

## Colores del club

Verde titular — Blanco reserva (reflejado en la UI: color primario verde)

## Contraseña coordinador

`AMICS`

## Configurar Firebase

Edita `src/firebase.js` con los datos de tu proyecto Firebase.  
Los datos se guardan en colección **`amicscastello`** (separada del fútbol).

1. Crea proyecto en https://console.firebase.google.com
2. Habilita Firestore Database
3. Copia las credenciales en `firebaseConfig`

## Instalación

```bash
npm install
npm run dev
```

## Despliegue Vercel

Sube a GitHub → importa en Vercel → despliega.
