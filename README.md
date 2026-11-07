# Système de gestion du complexe sportif

Projet UML réalisé avec PlantUML.

## Organisation

- `diagrams/source/` : sources PlantUML et style partagé.
- `diagrams/generated/overview/` : diagramme de classes complet.
- `diagrams/generated/classes/` : diagrammes isolés par classe.
- `docs/reference/` : document PDF de référence du projet.

## Génération

Depuis la racine du projet, avec PlantUML installé :

```powershell
java -jar plantuml.jar -tpng diagrams/source/class_diagram.puml
java -jar plantuml.jar -tpng diagrams/source/classes_isolated.puml
java -jar plantuml.jar -tpng -o ../generated/sequence diagrams/source/sequence_diagrams.puml
```

Les fichiers PNG générés peuvent ensuite être rangés dans `diagrams/generated/`.
Les diagrammes de séquence sont générés dans `diagrams/generated/sequence/`.
