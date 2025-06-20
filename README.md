# Diseño y compartición de módulos IaC con patrones de software

- Alumno: Aldo Luna Bueno
- Código: 20170325B
- Correo institucional: alunab@uni.pe
- Enlace del repo grupal: https://github.com/AldoLunaBueno/pc3-grupo4-tema3

En el sprint 1, el rol que adopté fue parecido a un Scrum Master. Primero me encargué de asegurar las buenas prácticas colaborativas. Creé:
- El repositorio de forma segura para que no se puedan hacer push directos a main y que los PRs no se puedan autoaceptar
- El tablero Kanban con base en nuestras necesidades de flujo de trabajo
- Hooks para automatizar la verificación de convenciones sobre commits y ramificación y así aumentar la trazabilidad y minimizar conflictos de fusión.

En los sprints 2 y 3 mi rol fue netamente de desarrollador. Desarrollé los módulos Composite y Factory, así como algunos scripts puntuales, y también documenté todo lo que implementé. Sobre el módulo Factory debo decir que solo lo extendí y refiné, mas no lo creé desde su base.

# Instalación

```bash
git clone https://github.com/AldoLunaBueno/pc3_repo_individual
cd pc3_repo_individual
python3 -m venv .venv
# en windows
source .venv/Scripts/activate
# en linux 
source .venv/bin/activate
pip install -r requirements.txt
```

# Ejecución de scripts

- Módulo Composite

```bash
cd iac_patterns/composite
bash run.sh
```

- Módulo Factory

```bash
cd iac_patterns/factory
bash run_factory.sh
# Obs.: no creé este módulo, sino que lo extendí y refiné
```

(Además, en cada módulo hay un script de testeo que puede ejecutar opcionalmente).

- Scripts generales

```bash
cd scripts
python generate_diagram.py
python verify_state.py
```