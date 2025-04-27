# Liberty App 🗽

Proyecto de aplicación cívica y social descentralizada, basada en Stacks (Layer 2 sobre Bitcoin), para tokenizar participación ciudadana, vigilancia social y toma de decisiones comunitarias.

## 📌 ¿Qué es Liberty?

Una app donde los usuarios pueden:
- Participar en decisiones sociales.
- Reportar irregularidades en su ciudad, gobierno o instituciones.
- Auditar acciones públicas.
- Ganar tokens de recompensa (token $LIBERTY) por su participación activa.

## 🛠 Tecnologías a utilizar

- **Blockchain:** Stacks (L2 sobre Bitcoin)
- **Lenguaje Smart Contracts:** Clarity
- **Frontend:** React / Next.js
- **Backend:** Node.js + API REST (o GraphQL)
- **Base de Datos:** MongoDB / Firebase (para no on-chain)
- **Repo y CI/CD:** GitHub + Vercel o Netlify
- **Comunidad:** Discord + GitHub Discussions
- **Tokens:** $LIBERTY y futuro $LUZ

## 📦 Estructura inicial del proyecto

liberty-app/
├── backend/
│   ├── src/
│   │   └── index.js
│   └── package.json
│
├── contracts/
│   ├── README.md
│   └── my-first-contract.clar
│
├── frontend/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── package.json
│
├── .gitignore
├── README.md
├── ROADMAP.md
└── LICENSE



## 🔥 MVP (Mínimo Producto Viable)

- Landing page con explicación del proyecto.
- Registro de usuarios con Stacks Wallet.
- Registro de incidentes / reportes.
- Votación simple.
- Recompensa en tokens $LIBERTY.
- Panel básico de comunidad.
- Contrato del token desplegado.

## 🚀 Cómo ejecutar el proyecto (local)

1. Clonar el repo:
```bash
git clone https://github.com/tuusuario/liberty-app.git
cd liberty-app


2.Instalar dependencias Frontend:

cd frontend
npm install
npm run dev

3.Instalar dependencias Backend:

cd backend
npm install
npm run dev

Correr los contratos: Instalar Clarity CLI: https://docs.stacks.co/clarity/clarinet

clarinet check
clarinet test

📣 Comunidad
Unite a nuestro Discord 👉 [discord.gg/loquevayascargar]
Canales:

#general

#ideas

#bug-reports

#propuestas

#dev-log

📑 Licencia
MIT

# 🗺️ Roadmap Liberty App

✅ Definición de idea y tokenomics inicial  
✅ Creación de repositorio y estructura base  
🔜 Setup de Discord y comunidad  
🔜 Desarrollo MVP:
  - Sistema de votaciones básicas
  - Reporte de irregularidades
  - Generación y distribución de tokens
  - Primer smart contract en Stacks
  - Landing web

📅 Lanzamiento Beta Privada: Q3 2025
📅 Apertura de comunidad testers: Q4 2025
