# RenderZe: OpenGL FLIP Fluid Simulation

Un projet simple de simulation de fluide basé sur la méthode **FLIP (Fluid-Implicit Particle)** utilisant **OpenGL**, **GLFW**, **GLAD** et **GLM** pour le rendu et les calculs mathématiques.

---

## **Structure du projet**
RenderZe: OpenGL FLIP Fluid Simulation

---

src/
├── main.cpp          # Point d'entrée du programme
├── shader.cpp/h      # Gestion des shaders OpenGL
├── simulation.cpp/h  # Logique de la simulation FLIP
├── grid.h            # Utilitaires pour la grille
├── particle.h        # Système de particules
└── config.h          # Configuration globale

---

## **Dépendances**
- **GLFW** : Gestion des fenêtres et des entrées utilisateur.
- **GLAD** : Chargement des fonctions OpenGL.
- **GLM**  : Bibliothèque mathématique pour les calculs 3D.

---

## **Compilation et exécution**

### **1. Configuration initiale (une seule fois)**

```sh
cmake -B build
cmake --build build --config Debug
```

### **2. Compilation (après chaque modification)**

```sh
cmake --build build --config Debug
```

### **3. Lancement de l'exécutable**
```sh
./build/Debug/renderze.exe
```



