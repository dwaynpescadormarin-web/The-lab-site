# THE LAB — Site vitrine V1

Site responsive Next.js (App Router), TypeScript, Tailwind CSS 4 et Lucide.

## Prérequis
- Node.js 20.9+ et npm

## Démarrage

```bash
npm install
cp .env.example .env.local
npm run dev
```

Sur Windows PowerShell : `Copy-Item .env.example .env.local`.

Ouvre http://localhost:3000.

## À personnaliser avant publication

Dans `.env.local`, remplace `https://discord.gg/REMPLACE-MOI` par ton **vrai lien d'invitation Discord** :

```
NEXT_PUBLIC_DISCORD_INVITE=https://discord.gg/TON-CODE
```

Redémarre le serveur après modification.

- `app/page.tsx` : textes, services, FAQ, liens et sections.
- `app/globals.css` : couleurs et styles.
- `app/layout.tsx` : titre et description SEO.

## Mise en ligne (Vercel)

1. Mets le projet dans un dépôt GitHub.
2. Importe le dépôt sur https://vercel.com/new.
3. Ajoute la variable d'environnement `NEXT_PUBLIC_DISCORD_INVITE` dans Vercel.
4. Lance le déploiement.

## Roadmap
- V1 : site vitrine et liens Discord.
- V2 : authentification Discord, demandes et planning.
- V3 : gestion des coachs, statistiques, tournois et éventuellement paiements.

Aucune intégration API Discord ni système de réservation n'est implémenté dans cette V1.
