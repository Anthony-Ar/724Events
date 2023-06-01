# Projet 10 : 724 Events

### Slider
**Commit :** [fix: Slider](https://github.com/Lost-Somewhere/724Events/commit/f4456d4b19b8a51ba4c54e433613d1e9bcb162a2 "fix: Slider")

- Affichage des évènements par date en ordre décroissant
- Key unique 
- Débug des bullets points (readOnly, checked)
- CSS : correction du dépassement lors du changement de slide

### Date
**Commit :** [fix: Date (helpers)](https://github.com/Lost-Somewhere/724Events/commit/df0bdf2ef832bf889db90b80f259cf48f6479f5e "fix: Date (helpers)")

- Ajout +1 à `getMonth()` pour correspondre à `MONTHS` (par défaut, janvier = 0 et non 1) :
Résolution des décallages + "undefined" les évènements en janvier

### DataContext
**Commit :** [fix: DataContext](https://github.com/Lost-Somewhere/724Events/commit/a94102b8cbcea700195af1668163d54a5cca9709 "fix: DataContext")

- Ajout méthode `last` (Affiche le dernier évènement)

### Home
**Commit :** [fix: Home](https://github.com/Lost-Somewhere/724Events/commit/f914029edebcd65a8bcbfd63f6f17772e6132628 "fix: Home")

- Rendu conditionné ("Notre dernière prestation") => évite un message d'erreur dans la console au premier chargement
- Correction des ancrages sur la page
- Débug message de validation du formulaire (-> component Form)

### Events
**Commit :** [fix: Events](https://github.com/Lost-Somewhere/724Events/commit/3f1a15d455467ac17aca36c5f6127c18a0c71174 "fix: Events")

- Débug filtrage des évènements (-> retour value component Select)

# Tests

**Commit :** [fix: Tests (Home + Form)](https://github.com/Lost-Somewhere/724Events/commit/5d99f8687e5e2edb58f4cfa825b0bec154dcad75 "fix: Tests (Home + Form)")

- Utilisation de  `waitFor()` (react testing)

**Commit :** [feat: Tests completion](https://github.com/Lost-Somewhere/724Events/commit/3f5a42406828009614357e6cd4c8690b7dd2b18a "feat: Tests completion")
- Réalisation des parties notées `// to implement`
- Ajout de `data-testid` sur le component PeopleCard + footer
- Modification EventCard (permet de cibler une carte en particulier grâce à un testid personnalisable)

**Commit :** [feat: Last commit](https://github.com/Lost-Somewhere/724Events/commit/57c41ca9a2aadf11752e2a3d4db425b78d51de29 "feat: Last commit")
- Derniers ajustements sur les tests (plus de skipped)

