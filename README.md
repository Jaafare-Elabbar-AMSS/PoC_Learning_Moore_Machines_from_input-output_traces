# **Preuve de concept : apprentissage des machines de Moore à partir de traces d'entrées-sorties**

## **Aperçu du projet**  
Ce dépôt documente la mise en œuvre d’une Preuve de Concept (PoC) pour vérifier la reproductibilité d'un algorithme présenté dans l'article de recherche suivant :  

**"Learning Moore Machines from Input-Output Traces"**  
Auteurs : Georgios Giantamidis, Stavros Tripakis et Stylianos Basagiannis.  
Publié dans : *International Journal on Software Tools for Technology Transfer (2021)*.  

L'objectif de ce projet est de reproduire et d'analyser l'algorithme suivant présenté dans l'article :  
- **Algorithme MooreMI** : extension de PTAP avec une agrégation d'états avancée pour assurer la minimalité et l'identification dans la limite.  

À travers cette PoC, nous visons à :  
1. Vérifier la reproductibilité des résultats de recherche.  
2. Analyser les points forts, les faiblesses et les limites de l'algorithme.  
3. Tirer des résultats supplémentaires sur des aspects non explicitement discutés dans l'article.  

---

## **Objectifs**  
- **Reproductibilité** : implémenter l'algorithme MooreMI et comparer leur résultats avec ceux présentés dans l'article.  
- **Analyse critique** : évaluer la performance de l'algorithme.  
- **Retour d'expérience** : fournir des retours constructifs sur la reproductibilité de l'article et identifier des hypothèses implicites ou manquantes.  
- **Documentation** : maintenir une documentation détaillée et claire pour garantir la fiabilité du travail.

---

## **Structure du dépôt**
- **notebook/** : Ccntient le notebook Jupyter documentant la preueve de concept étape par étape.  
- **data/** : inclut les jeux de données utilisés pour l'entraînement et les tests.  
  - `input_samples/` : données d'entrée pour l'algorithme.  
  - `outputs/` : résultats générés et sorties.  
- **script/** : tout script supplémentaires servant à l'implémentation ou au test de l'algorithme.  
- **README.md** : fichier décrivant le projet.  
- **requirements.txt** : liste des dépendances nécessaires pour exécuter le projet.  

---

## **Prise en main**

### **Prérequis**  
Assurez-vous d'avoir Python 2.7, installé sur votre système.

### **Installation**  
1. Clonez le dépôt :  
   ```bash
   git clone https://github.com/Jaafare-Elabbar-AMSS/PoC_Learning_Moore_Machines_from_input-output_traces.git  
   cd PoC_Learning_Moore_Machines_from_input-output_traces  
