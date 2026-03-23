# 💰 Mon Taf, Mon Pécule

> *Le temps, c'est de l'argent. Period.*
> Par Loris PEREZ : https://loris-perez.fr

## 👉 [Lancer l'application](https://lperez33.github.io/mon-pecule/compteur_salaire_taf.html)

Une application web de décompte en temps réel qui te montre exactement combien tu gagnes à chaque seconde que tu passes au taf — et qui te donne les outils pour vérifier ta fiche de paie.

---

## 🚀 Fonctionnalités

- **Compteur en temps réel** — voit chaque centime qui rentre, à la seconde près
- **Décompte du temps restant** — sait exactement combien de temps il te reste à tafer
- **Taux horaire & à la minute** — visualise ta valeur temps en direct
- **Récapitulatif mensuel** — total d'heures, taux horaire, valeur d'une journée
- **Vérificateur de fiche de paie** — compare ce que tu es censé gagner vs ce que ta fiche dit
- **Données persistantes** — ta config est sauvegardée, même après rechargement de page

---

## 📱 Comment utiliser

### 1. ⚙️ Config
Remplis une seule fois :
- **Salaire mensuel** (ex: `1800`)
- **Tes jours de taf** — clique sur les jours de la semaine où tu bosses
- **Heures par jour** (ex: `7`)
- **Heure de début de session** (ex: `09:00`)
- **Durée de la session** si elle diffère de ta journée normale

### 2. 🔴 Live
Lance le compteur et regarde l'argent rentrer. L'écran affiche :
- Le montant gagné depuis le début de ta session (mis à jour chaque seconde)
- Une barre de progression de ta journée
- Le temps qu'il te reste
- Ton taux horaire et à la minute
- Des messages de motivation toutes les 4 secondes

### 3. 📊 Récap
Un résumé complet de ton mois avec la formule de vérification :

```
Nombre total d'heures × Taux horaire = Salaire mensuel
```

Si ta fiche de paie dit autre chose → **tu demandes** 👊

---

## 🧮 Calcul du taux horaire

```
Taux horaire = Salaire mensuel ÷ (Jours/semaine × 4.33 semaines × Heures/jour)
```

Exemple pour 1 800 €/mois, 5 jours/semaine, 7h/jour :
```
1800 ÷ (5 × 4.33 × 7) = 1800 ÷ 151.55 ≈ 11,88 €/h
```

---


## 🛠️ Stack technique

- **HTML/CSS/JS** — vanilla, zéro dépendance
- **Fonts** — Syne (titres) + Space Mono (chiffres), via Google Fonts
- **Animations** — CSS natif (blink, spin, progress bar)

---

## 💡 Idée originale

> *"À chaque fois que je suis au taf et tout, j'me dis tout ça pourquoi et tout. Du coup, il me faut une application où je vois que frérot, je suis là, mais je gagne de l'argent."*

Une vision. Une app. Même si par heure tu gagnes quatorze centimes — tu le vois. 👁️

---

## 📄 Licence

Free to use. Share the vision.
