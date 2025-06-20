# Contribuciones de Aldo Luna Bueno

## Sprint 1

- 2025-06-08: Creé Hooks de Git para mejorar la trazabilidad de nuestro proyecto colabarativo
    
    Commits:
    - feat(hooks): implementar hook commit-msg para validar mensaje de commit
    - feat(hooks): implementar hook pre-commit para validar nombre de ramas
    - docs(hooks): documentar acerca de commit-msg y pre-commit

    Pull request grupal: #9

- 2025-06-09: Instrucciones iniciales y submódulos

    Commits:
    - feat(submódulos): crear submódulo git vacío para simular módulo externo
    - docs: documentar la instalación del proyecto
    - docs(patrones): explicar brevemente cinco patrones de diseño

    Pull request grupal: #14

- 2025-06-11: Arreglo rápido para admitir commits desde ramas hotfix

    Commits:
    - feat(hooks): añadir validación de ramas hotfix

    Pull request grupal: #30

## Sprint 2

- 2025-06-11: Manejo del estado de toda la infraestructura

    Commits:
    - chore(gitignore): ignorar archivos de terraform estado y archivos json
    - feat(scripts): verificar estado de toda la infraestructura instanciada

    Pull request grupal: #32

- 2025-06-15: Implementar y automatizar módulo Composite

    Commits:
    - feat(composite): implementar modulo y submódulos por composición
    - feat(composite): implementar run.sh para automatizar la ejecución

    Pull request grupal: #39

- 2025-06-15: Extender lógica del diagramador

    Commits: 
    - feat(diagrams): implementar generador de diagramas de infraestructura
    - fix(diagrams): cambiar directorio de destino de diagrama a docs/
    
    Pull request grupal: # 43

## Sprint 3

- 2025-06-17: Renombré src/ como iac_patterns/ y cambié varios nombres al inglés

    Commits:
    - refactor: renombrar src/ y cambiar referencias en archivos
    - refactor: nombres de archivos, funciones y variables en inglés

- 2025-06-19: Extendí el módulo Composite y creé un script Bash para verificarlo
    
    Commits:
    - feat(composite): refinar el módulo composite con más variables
    - test(composite): implementar test para verificar salida

- 2025-06-19: Actualicé la documentación sobre el módulo Composite

    Commits:
    - docs(composite): actualizar readme

     Pull request grupal: #66
     
- 2025-06-19: Extendí el módulo Factory

    Commits:
    - test(factory): test módulo factory
    - feat(composite): añadir 2 variables de entrada y 1 salida