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
```

Les fichiers PNG générés peuvent ensuite être rangés dans `diagrams/generated/`.
