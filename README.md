# git-hook-base-py
- Hook de GIT para mostrar mensaje y audio si el archivo base.py fue modificado - Uso especifico para ciertos proyectos
- Limitaciones: Uso pensado para Windows

### Pasos
- **Paso 1:** Clonar proyecto a una ubicacion especifica:
```bash
# /c/projects/git-hook-base-py
```

- **Paso 2:** Dar permisos al archivo pre-commit 
```bash
chmod +x /c/projects/git-hook-base-py/pre-commit
```


- **Paso 3:** Asignar Hook al config global de git
```bash
git config --global core.hooksPath /c/projects/git-hook-base-py/
```

### Adicional

Si es necesario modificar el comportamiento, se modificar el hook:
```bash
vim /c/projects/git-hook-base-py/pre-commit
```
