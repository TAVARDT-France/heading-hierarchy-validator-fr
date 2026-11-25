# Analyseur de Balises H1-H6 et Hierarchie Semantique

[![Analyseur Balises H1-H6](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/fr/analyseur-balises-h1-h6/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audit de la structure de titres HTML5, unicite du titre principal H1 et respect des referentiels d accessibilite.

Developpe et maintenu par l equipe d accessibilite et semantique de **TAVARDT**.

***

## Capacites d Audit des Balises H1-H6

* **Unicite de la Balise H1**: Controle de la presence d un unique titre `<h1>` definissant la thematique de la page.
* **Detection des Sauts de Niveaux**: Reperage des discontinuites de niveaux (passage d un `<h2>` a un `<h4>`) prejudiciables aux lecteurs d ecran.
* **Controle des Titres Vides**: Identification des balises d en-tete depourvues de contenu textuel.
* **Plan Semantique du Document**: Restitution visuelle et arborescente du plan de titrage HTML5.
* **Score de Conformite Semantique**: Evaluation sur 100 avec priorisation des corrections RGAA et W3C WCAG.

***

## Installation et Utilisation

Fonctionne avec Python 3.8 ou superieur sans bibliotheque tierce.

```bash
git clone https://github.com/TAVARDT-France/heading-hierarchy-validator-fr.git
cd heading-hierarchy-validator-fr
python heading_hierarchy_validator.py https://entreprise.fr
```

Sortie detaillee au format JSON:

```bash
python heading_hierarchy_validator.py https://entreprise.fr -json
```

***

## Outil d Audit en Ligne

Testez la structure semantique de vos pages sur notre plateforme officielle:

* **Analyseur de Balises H1-H6 Officiel**
* **[Portail TAVARDT](https://ag.tavardt.com/fr/)**

***

## Conseil et Accompagnement Technique

Pour une mise en conformite semantique avec Referentiel General d Amelioration de l Accessibilite et W3C WCAG, contactez **TAVARDT**.

***

## Liens Utiles

* **Portail Entreprise:** https://ag.tavardt.com/fr/
* **Suite de Diagnostic:** https://tools.tavardt.com/fr/
* **Contact Technique:** https://ag.tavardt.com/fr/contact/

***

### Licence
Distribué sous la licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.

***

© 2026 TAVARDT. Tous droits réservés.
