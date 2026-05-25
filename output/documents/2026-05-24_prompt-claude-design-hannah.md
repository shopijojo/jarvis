# Prompt Claude Design — Site vitrine Hannah Guirchoun

---

Crée un site vitrine d'une seule page (HTML/CSS) pour une esthéticienne appelée **Hannah Guirchoun**, basée à **Jérusalem**.

## Identité visuelle
- Palette de couleurs : rose poudré, nude, blanc cassé, touches dorées
- Style : élégant, féminin, haut de gamme, aéré
- Typographie : serif chic pour les titres (ex. Playfair Display), sans-serif propre pour le corps
- Ambiance générale : salon de beauté premium, pas criard

## Structure du site (sections dans l'ordre)
1. **Hero** — Grand visuel plein écran, prénom "Hannah Guirchoun" bien mis en valeur, sous-titre court (esthéticienne / מטפלת פנים ויופי), bouton "Prendre rendez-vous" qui ouvre WhatsApp
2. **Services** — Cartes visuelles pour chaque prestation : Soins du visage, Maquillage, Manucure, Pédicure, Gel & Nail art
3. **Galerie** — Grille de photos (prévoir des emplacements pour vraies photos à insérer plus tard)
4. **À propos** — Courte bio chaleureuse de Hannah, son approche, sa passion
5. **Contact** — Bouton WhatsApp bien visible, localisation Jérusalem, Instagram si disponible

## Langue
- Site **bilingue français / hébreu**
- Le français est la langue principale (affichée en premier)
- L'hébreu est affiché juste en dessous de chaque texte français, en plus petit, avec `dir="rtl"`
- Pas besoin d'un vrai switch de langue, juste les deux textes côte à côte ou empilés

## Contraintes techniques
- Fichier HTML unique, CSS intégré dans `<style>`, aucune dépendance externe sauf Google Fonts
- Responsive mobile (la majorité des clientes viendront depuis leur téléphone)
- Photos : utiliser des images placeholder depuis Unsplash (beauté, mains, visage, maquillage) avec des vraies URLs
- Bouton WhatsApp avec le lien `https://wa.me/972XXXXXXXXX` (laisser le numéro à compléter)

## Ton
Chaleureux, professionnel, confiant. Pas de texte générique. Hannah est une vraie professionnelle passionnée.
