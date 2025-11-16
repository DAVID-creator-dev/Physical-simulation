# 🧠 Simulation Physique 3D

Ce projet est une **simulation physique ** en 3D, développée autour des systèmes de collisions et de dynamique rigide.
Il met en œuvre une chaîne complète de détection et de résolution physique : **broadphase → narrowphase → EPA → impulsions → friction et rotation angulaire**.

---

## ⚙️ Fonctionnalités principales

* **Broadphase (AABB)** : détection rapide des paires potentielles de collisions.
* **Narrowphase (GJK)** : calcul précis des intersections convexes.
* **EPA (Expanding Polytope Algorithm)** : obtention de la normale et profondeur de pénétration.
* **Résolution par impulsion** :

  * Calcul du point de contact (avec interpolation barycentrique).
  * Application des impulsions linéaires et angulaires.
  * Gestion du rebond (restitution).
* **Frottement dynamique et statique** 
* **Rotation angulaire** avec tenseur d’inertie.

---

## 🎮 Commandes du jeu / simulation

| Touche            | Action                                    |
| ----------------- | ----------------------------------------- |
| **Z / Q / S / D** | Déplacer le personnage                    |
| **Espace**        | Tirer une boule                           |
| **R**             | Sélectionner un objet                     |