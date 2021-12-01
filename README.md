<img src="static/img/logo_lectaurep.png" width=150 align=right>

# lectaurep-repertoires
Lectaurep-Repertoires, ground truth for various Parisian notary's registries of deeds (French 19th and 20th centuries) 

<!-- badges -->
[![CC BY 4.0][cc-by-shield]][cc-by]
![Region Badges](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/alix-tz/0e95bc706b498b2b8428697e992a5755/raw/rep_regions.json)
![Lines Badges](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/alix-tz/0e95bc706b498b2b8428697e992a5755/raw/rep_lines.json)
![Characters Badges](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/alix-tz/0e95bc706b498b2b8428697e992a5755/raw/rep_chars.json)


## Contexte de production 

Le projet [LECTAUREP](https://lectaurep.hypotheses.org/) (LECTure Automatique de REPertoires), qui a débuté en 2018, est une initiative conjointe du Minutier central des notaires de Paris des Archives Nationales, de l’équipe ALMAnaCH (Automatic Language Modeling and Analysis &amp; Computational Humanities) à Inria et de l’EPHE (Ecole Pratique des Hautes Etudes), en partenariat avec le Ministère de la Culture.

Le projet vise à repenser l’utilisation actuellement faite des registres des actes notariés, l’une des sources historiques les plus consultées aux Archives nationales, par les chercheurs et les utilisateurs des fonds d’archives notariales. Pour ce faire, le projet a instaurer un workflow de traitement de ces manuscrits à l’aide de la reconnaissance automatique des documents manuscrits (HTR) et d'extraction d’information (NER) en adoptant notamment l'application eScriptorium pour produire la vérité de terrain, entraîner des modèles de reconnaissance et corriger les transcriptions résultants.

Les corpus `lectaurep-repertoires` rassemblent les données d'entraînement spécifiques aux répertoires de notaires. 

## Détail des lots

| Nom                | Importance matérielle | Dates extremes    | Particularité | Notaire  | Identifiant db |
| ------------------ | --------------------- | ----------------- | ------------- | -------- | -------------- |
| lectaurep-rigault6 | 35 pages              | 05/1907 - 03/1908 | 1 seule main  | Rigault  | [#50](https://escriptorium.inria.fr/document/50/images/) (2-37) |



## Règles de transcription

![illus_superscript](static/img/illus_superscript.png)

- le texte suscrit a été signalé par un `^` liminaire. Le phénomène "**dud<sup>t</sup>**" (dudit) est donc transcrit par "dud^t".

- l'emploi des minuscules et majuscules a été respecté.


![illus_superscript](static/img/illus_ligatures.png)

- les mots agglutinés et ligaturés sont généralement transcrits tels quels.


![illus_superscript](static/img/illus_printed.png)

- les segments correspondant à du texte pré-imprimés sont signalé par le type "printed"


---

<!-- logo institutionnels -->

| Inria                               | Archives nationales                                             |
| :---------------------------------: | :-------------------------------------------------------------: |
| ![inria](static/img/logo_inria.png) | ![archives nationales](static/img/logo_archives-nationales.png) |



