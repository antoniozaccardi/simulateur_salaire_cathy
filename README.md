# 💰 Simulateur de Salaire

Calculatrice interactive pour simuler le salaire net mensuel de Catherine ZACCARDI en fonction de différents paramètres.

## 📋 Fonctionnalités

- **Calculs en temps réel** : Les résultats se mettent à jour instantanément lors de la modification des paramètres
- **Paramètres ajustables** :
  - Nombre de jours de travail par semaine (4 ou 5)
  - Heures travaillées par jour
  - Taux horaire pour heures normales
  - Taux horaire pour heures supplémentaires
  - Indemnités (entretien + repas)
  
- **Affichage détaillé** :
  - Calcul des heures normales et heures supplémentaires
  - Décomposition du salaire mensuel
  - Détail des indemnités
  - Salaire net global

## 🚀 Utilisation

1. Ouvrir `index.html` dans un navigateur
2. Ajuster les paramètres dans le panneau de gauche
3. Consulter les résultats en temps réel dans le panneau de droite

## 📊 Calculs

### Heures par semaine
- **Configuration par défaut** : 4 jours/semaine × 9h/jour = 36h/semaine
- Les heures au-delà de 35h/semaine sont comptabilisées comme heures supplémentaires

### Salaire mensuel
- Basé sur une moyenne annuelle (52 semaines / 12 mois)
- **Jours mensuels** : 
  - 4 jours/semaine = 18 jours/mois
  - 5 jours/semaine = 22 jours/mois

### Formule
```
Net Global = 
  (Heures normales × Taux normal) + 
  (Heures sup × Taux sup) + 
  (Jours mensuels × Indemnité journalière)
```

## 💻 Technologies

- HTML5
- CSS3 (responsive design)
- JavaScript vanilla (pas de dépendances)

## 📝 Exemple

**Configuration** :
- 4 jours/semaine, 9h/jour
- Taux normal : 3.75€/h
- Taux sup : 5.63€/h
- Indemnités : 5€/jour (4€ entretien + 1€ repas)

**Résultats mensuels** :
- Heures normales : ~140h × 3.75€ = 525€
- Heures sup : ~6.5h × 5.63€ = 36.60€
- Indemnités : 18 jours × 5€ = 90€
- **NET : ~651.60€**

---

Créé pour Catherine ZACCARDI | Yerres (91330)
