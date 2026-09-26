# CONTEXT.md — Contexte du projet pour Claude Code

> Ce fichier est le point d'entrée pour tout assistant IA travaillant sur ce repo.
> Il résume les décisions narratives, l'univers, les personnages et le workflow.

---

## Le projet

Roman de science-fiction anticipation géopolitique.
**Titre :** Horizon 2100
**Auteur :** Clément (écrit lui-même le texte — les fichiers chapitres contiennent la structure narrative, pas la prose)

---

## Règle fondamentale

Les fichiers `chapitres/chXX_*.md` contiennent uniquement :
- La structure narrative détaillée
- Les intentions de scène
- Les éléments à ne pas oublier
- Les annotations réel/fictif si pertinent

**Jamais de prose rédigée dans le repo.** L'auteur écrit lui-même.

**Référentiel :** [`BIBLE.md`](BIBLE.md) est la référence pour tous les termes, concepts et acteurs de l'œuvre.

---

## L'univers

### La Tétrarchie
Quatre méga-corporations qui contrôlent en 2100 **75 % des richesses mondiales**. Surnommées "Tétrarchie" (référence au régime romain) par économistes et journalistes indépendants. Ce terme est violemment rejeté par les corporations qui le qualifient de complotisme via leur empire médiatique.

Trajectoire de concentration du capital (réel → fictif) :
- **1911** : Standard Oil ≈ 3 % du PIB américain `[RÉEL]`
- **2026** : Nvidia ≈ 17 % du PIB américain `[RÉEL]`
- **2100** : Tétrarchie = 75 % des richesses mondiales `[FICTIF]`
- **2150** : projections = 99,9 % `[FICTIF]`

### La Continuité
Terme entré dans le langage courant dans les années 2060. Désigne 80 ans de choix politiques reconduits :
- Fermeture des frontières face aux réfugiés climatiques
- Post-capitalisme de plateforme (abandon des services publics au marché)
- Libertarisme économique et refus d'agir sur le climat
- Montée graduelle de la température — jamais assez brutale pour déclencher une rupture

Formule : *"Nous avons vu, nous avons su, et nous n'avons pas réussi à faire changer les choses."* — sans culpabilité.

### Le Mesh
Réseau internet pair-à-pair physique, fonctionnant sur fréquences indétectables. Chaque utilisateur est un nœud. Indestructible par définition. Créé par le Professeur, libéré en open source. Permet de briser le blocus médiatique de la Tétrarchie et d'héberger le procès de 2100.

### HydraCore
Filiale eau de la Tétrarchie. L'eau est facturée à un prix exorbitant et distribuée par les anciennes infrastructures publiques, accaparées par la Tétrarchie. Pas de livraison par drone.

---

## Les trois mouvements de résistance

| Mouvement | Rôle | Méthode |
|-----------|------|---------|
| **Syndicat Global du Bien Commun** | Résistance légale et institutionnelle | Guérilla juridique (millions d'amendements, obstruction parlementaire) |
| **L'Archipel** | Infrastructure clandestine | Déploiement et maintenance du Mesh |
| **Terra Nullius** | Désobéissance civile totale | Grève mondiale des loyers et crédits, Organisme de Gestion du Retour |

---

## Les personnages

| Personnage | Rôle | Notes |
|------------|------|-------|
| **Marta** | Protagoniste, 83 ans, Marseille | Génération charnière — a tout vu venir. Point d'entrée du roman (ch01) |
| **K. Andersen** | Journaliste norvégien, *Nordlys Fritt* | Héritier narratif d'Ida Tarbell. Co-auteur du rapport des 75 % |
| **E. Moreau** | Jeune économiste français | L'un des premiers membres du Syndicat. Co-auteur du rapport avec Andersen |
| **Le Professeur** | Père du Mesh | Ancien architecte réseau des corporations. Assassiné au ch06. Son code lui survit |

### Références historiques
- **Ida Tarbell** : journaliste d'investigation américaine, enquête sur Standard Oil (1902-1904, *McClure's Magazine*). Ancêtre narrative de K. Andersen.
- **Standard Oil** : monopole pétrolier démantelé par la Cour Suprême américaine le 15 mai 1911 en 34 sociétés — qui se sont reconcentrées en ExxonMobil, Chevron, BP.

---

## Structure du roman

```
ch00 — L'Ancien Monde avait déjà su        (prologue — Standard Oil 1911 → retour 2100)
ch01 — Le Chiffre de la Fin du Monde       (Marta / le rapport Andersen-Moreau)
ch02 — Les Saboteurs de la Démocratie      (guérilla juridique du Syndicat)
ch03 — La Naissance du Mesh                (le Professeur / l'Archipel)
ch04 — Les Nœuds du Risque                 (déploiement du Mesh / les sous-traitants rebelles)
ch05 — Le Tribunal Décentralisé            (le procès de 2100 sur le Mesh)
ch06 — Le Sacrifice du Prométhée           (cyberattaque + assassinat du Professeur + verdict)
ch07 — L'Insurrection Légale               (révélations / Terra Nullius / grève des loyers)
ch08 — L'Organisme du Retour vs Les Drones (guerre physique / armée de drones)
```

---

## Workflow

- **Ce repo** : source de vérité — structure narrative, bible, personnages
- **L'auteur** : écrit le texte dans son éditeur personnel
- **Claude Code** : génère et maintient les fichiers markdown de structure
- **Claude.ai (projet Écriture)** : réflexion narrative, recherches, décisions d'univers

---

## Thèse philosophique sous-jacente

L'IA comme outil ultime du capital (filiation avec le *Fragment sur les machines* de Marx / *Grundrisse*) : le *general intellect* absorbé par le capital fixe, étendu désormais aux cadres et au savoir immatériel. Trois issues possibles recoupant les mouvements du roman :
1. Néo-féodalisme de la rente (revenu universel corporate) → ce que subit le monde en 2100
2. Réappropriation publique du calcul et de l'énergie
3. Sécession par les communs → le Mesh

Le vrai goulot de la Tétrarchie : contrôle de l'énergie, des puces et du foncier des data centers.
