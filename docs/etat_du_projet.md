# 📔 Journal de Bord - lereglageparfait.com
**Dernière mise à jour :** 21 décembre 2025  
**Statut actuel :** Architecture validée, contenu déployé, phase de debug visuel.

---

## 🛠️ Configuration & Inventaire Technique
- **Thème :** PaperMod avec personnalisations (`custom.css`, `extend_head.html`).
- **Configuration Hugo :** `canonifyURLs = false` (pour corriger les chemins médias), `params.cover` configuré pour afficher les images.
- **Assets :** - Favicons complets.
    - PDF "Checklist photo de nuit" dans `/static/downloads/`.
    - Images critiques (`header.webp`, `optique-about.webp`) dans `/static/images/`.

## 📝 État du Contenu (12 Articles Piliers)
Tous les articles sont structurés en **Page Bundles** (Dossier + `index.md` + images locales) :
- **Technique :** Triangle d'exposition, Guide débutant, Composition.
- **Matériel :** Focale fixe, Objectif Zoom, Filtre ND, Filtre Diffusion, Flash, Trépied, Cartes mémoire.
- **Pratique & Guides :** Photo de nuit, Checklist sac photo (1000€).
- **Institutionnel :** Page "À Propos" (`/about/`) rédigée avec un ton E-E-A-T.

## ⚙️ Décisions Techniques & SEO
- **SEO :** Utilisation systématique du champ `description` et balises `alt` descriptives.
- **Performance :** Format **WebP** généralisé pour toutes les images.
- **Structure :** URL de la page À Propos fixée sur `/about/`. Maillage interne en silos (en cours de vérification).

## ✅ Réalisations de la session
- Déploiement réussi de la page À Propos et du fichier de configuration corrigé.
- Validation de l'accessibilité des médias en ligne (URL directe OK).
- Nettoyage du Front Matter (suppression du `layout: simple`).

## ✅ Réalisations
- Fix structurel : Passage de la page About en Page Bundle (dossier).
- Validation de l'affichage de l'image de couverture en production.
- Nettoyage des fichiers doublons à la racine de /content/.

## ✅ Réalisations
- Optimisation SEO de l'article "Triangle d'Exposition".
- Création d'un maillage interne circulaire (Technique <-> Matériel).
- Validation de l'image de couverture en mode relatif.
## ✅ Réalisations
- Optimisation de l'article 'Photographie de Nuit'.
- Activation du lien de téléchargement PDF.
- Maillage retour vers le 'Triangle d'Exposition'.
