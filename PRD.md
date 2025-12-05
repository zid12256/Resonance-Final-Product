# PRD — Site web de présentation de casques (version fichier)

## Résumé

Projet : site statique de présentation de casques/écouteurs.
Objectif : rendre le site accessible, performant et prêt au déploiement.

## Objectifs produit

- Présenter les produits audio (images, caractéristiques, CTA).
- Fournir une page de support/FAQ.
- Assurer une expérience mobile-first, accessible (WCAG 2.1 AA), et performante.

## Utilisateurs cibles

- Acheteurs potentiels (mobile-first)
- Utilisateurs techniques
- Clients recherchant support

## Périmètre

In-scope : améliorations HTML/CSS, optimisation images, accessibilité, SEO basique, déploiement statique.
Out-of-scope : backend, panier, CMS complet.

## Fonctionnalités principales (MUST)

- Pages : `index.html`, `headphones.html`, `support.html`.
- Navigation claire, galerie image optimisée, fiche technique, responsive, accessibilité (alt, focus).
- Performance : WebP, lazy-loading, CSS minifié.
- SEO : title, meta description, Open Graph.

## Exigences non-fonctionnelles

- HTTPS en production
- Budget initial ≤ 1MB
- Compatibilité navigateurs récents

## Critères d'acceptation

- Title et meta description présents pour chaque page
- Alt pour toutes les images
- Navigation accessible au clavier
- Lighthouse: Accessibility ≥ 90, Performance ≥ 80

## Architecture & navigation

Header : logo + menu
Footer : mentions légales, contact

## Plan & livrables

- Audit rapide
- Corrections meta & alt
- Optimisation images
- Tests Lighthouse
- Déploiement GitHub Pages / Netlify

## Checklist prioritaire

- [ ] Titles & meta
- [ ] Alt images
- [ ] WebP + srcset
- [ ] loading="lazy"
- [ ] Tests Lighthouse


---

Fichier créé : `/Users/mac/Downloads/site/PRD.md`
