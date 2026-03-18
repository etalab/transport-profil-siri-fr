# Changelog - Historique des changements

## v1.8

### Généralités

La version 1.8 du profil France de SIRI est la **dernière version basée sur la [XSD de SIRI v2.1](https://github.com/SIRI-CEN/SIRI/tree/v2.1)**.
Cette version a été officiellement validée en session plénière du GT7 (Groupe de Travail sur l’information voyageur et l’exploitation des services de mobilités, au sein de la Commission de normalisation Transport Public de l'AFNOR) en date du 20 novembre 2025, puis en session plénière de la CN03 (Commission de normalisation Transport Public) en date du 19 décembre 2025.
Sa publication effective sur le site [normes.transport.data.gouv.fr](https://normes.transport.data.gouv.fr/) a été faite en date du 16 mars 2026.

### Changements détaillés

Les changements détaillés ci-dessous sont présentés selon les sections du profil France et/ou les services SIRI.

|Section - Service SIRI|Changements principaux|Référence des Pull Requests|
|-----------------------|-----------|---------------------------|
|Introduction et avant-propos |- Mise à jour des éléments éditoriaux <br />- Suppression des éléments obsolètes<br />- Corrections de typos |[#54](https://github.com/etalab/transport-profil-siri-fr/pull/54), [#59](https://github.com/etalab/transport-profil-siri-fr/pull/59) |
|Facility Monitoring (FM) |Correction des éléments pour l'accessibilité |[#37](https://github.com/etalab/transport-profil-siri-fr/pull/37) |
|Estimated Timetable (ET) |- Correction de la description de l'attribut DirectionRef <br />- Changement de cardinalité pour l'attribut order dans EstimatedCall |[#44](https://github.com/etalab/transport-profil-siri-fr/pull/44), [#52](https://github.com/etalab/transport-profil-siri-fr/pull/52) |
|Situation Exchange (SX) |- Correction et clarification de l'ensemble de la structure PtSituationElement et Affects, avec inclusion d'exemple <br />- Changement des éléments de la structure ActionData <br />- Ajout de valeurs pour l'énumération Severity <br />- Mise en conformité de l'énumération Reason avec la XSD de SIRI |[#40](https://github.com/etalab/transport-profil-siri-fr/pull/40), [#41](https://github.com/etalab/transport-profil-siri-fr/pull/41), [#51](https://github.com/etalab/transport-profil-siri-fr/pull/51), [#55](https://github.com/etalab/transport-profil-siri-fr/pull/55), [#57](https://github.com/etalab/transport-profil-siri-fr/pull/57) |

---

## v1.7

### Généralités

La version 1.7 du profil France de SIRI est la **première version du profil ayant bénéficié du changement d'outillage du GT7**. 
En effet, cette version est la première à avoir été bénéficié :
- de la migration de documents bureautiques vers des éléments en Markdown,
- d'un répertoire de travail dédié pour publication sur le site normes.transport.data.gouv

Cette version a été officiellement validée en session plénière du GT7 (Groupe de Travail sur l’information voyageur et l’exploitation des services de mobilités, au sein de la Commission de Normalisation Transport Public de l'AFNOR) en date du 17 mars 2023. Sa publication effective sur le site normes.transport.data.gouv.fr a été faite en date du 27 juillet 2023.


### Changements détaillés

- Mise à jour des éléments éditoriaux
- Ajout de la structure RecordedCall au service ET
- Ajout d'un descriptif de la gestion des passages échus
- Renvoi pour la construction des identifiants vers le profil NeTEx France Eléments communs
- Les tableaux ont aussi été « optimisés » pour le transfert vers Markdown et GitHub
- Les éléments sur lesquels un consensus ne s’était pas dégagé ont été supprimés (gestion de l’abonnement en particulier)
