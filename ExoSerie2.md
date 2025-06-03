## 🌱 **Logique et manipulations simples**

### 1. **Additionne les chiffres d’un nombre**

> Écris une fonction `sommeChiffres(n)` qui prend un nombre entier positif et renvoie la somme de ses chiffres.
> **Exemple :** `sommeChiffres(123)` renvoie `6` (car 1 + 2 + 3 = 6).
> ➕ Aide : convertis le nombre en chaîne (`String(n)`), puis parcours chaque chiffre.

---

### 2. **Compter jusqu’à N avec des sauts**

> Écris une fonction `compterParPas(n, pas)` qui affiche tous les nombres de 0 jusqu’à `n`, en sautant de `pas` à chaque fois.
> **Exemple :** `compterParPas(10, 2)` affiche : 0, 2, 4, 6, 8, 10.

---

### 3. **Nombre positif, négatif ou nul**

> Crée une fonction qui prend un nombre et affiche :
>
> * `"Positif"` s’il est > 0
> * `"Négatif"` s’il est < 0
> * `"Zéro"` si égal à 0.

---

### 4. **Afficher chaque lettre d’un mot**

> Demande un mot et affiche chaque lettre sur une ligne différente.
> ➕ Aide : utilise une boucle pour parcourir la chaîne.

---

### 5. **Trouver le carré d’un nombre**

> Écris une fonction `carre(n)` qui retourne le carré d’un nombre (n × n).

---

## 🔁 **Niveau 2 — Tableaux, chaînes et logique un peu plus poussée**

### 6. **Nombre de fois qu’un caractère apparaît**

> Demande une lettre et une phrase, et compte combien de fois cette lettre apparaît dans la phrase.
> **Exemple :** `'a'` dans `"Banana"` → 3 fois.
> ➕ Aide : pense à mettre tout en minuscule pour éviter les erreurs (`.toLowerCase()`).

---

### 7. **Somme des éléments d’un tableau**

> Écris une fonction qui prend un tableau de nombres et retourne la somme de tous les éléments.
> ➕ Aide : boucle `for` ou méthode `.reduce()`.

---

### 8. **Trouver les nombres pairs dans un tableau**

> Crée une fonction `filtrerPairs(tab)` qui renvoie un nouveau tableau avec seulement les nombres pairs du tableau donné.

---

### 9. **Remplacer une lettre par une autre dans un mot**

> Prends un mot, et deux lettres :
>
> * la lettre à remplacer,
> * et celle qui la remplace.
>   Puis retourne le mot modifié.
>   **Exemple :** `"chat", "a", "o"` → `"chot"`.

---

### 10. **Fusionner deux tableaux**

> Écris une fonction `fusionner(tab1, tab2)` qui retourne un seul tableau contenant tous les éléments des deux tableaux, sans utiliser `.concat()`.

---

## 🧠 **Niveau 3 — Réflexion, conditions complexes, mini-algorithmes**

### 11. **Deviner un nombre (sans interface)**

> Simule un petit jeu : le programme choisit un nombre au hasard entre 1 et 10.
> L’utilisateur (en simulation via variable) fait une proposition.
> Le programme indique si le nombre à trouver est plus grand, plus petit, ou trouvé.
> ➕ Aide : utilise `Math.random()` et une boucle `while`.

---

### 12. **Tri d’un tableau (version simple)**

> Demande à l’utilisateur un tableau (ex. `[4, 1, 3]`) et retourne une version triée du plus petit au plus grand (sans `.sort()`, fais-le à la main).
> ➕ Aide : utilise des boucles imbriquées ou un algorithme comme le tri par sélection.

---

### 13. **Convertir les minutes en heures et minutes**

> Écris une fonction `convertirTemps(min)` qui transforme un nombre de minutes en heures et minutes.
> **Exemple :** `130` → `"2h10"`.

---

### 14. **Vérifie si deux mots sont des anagrammes**

> Deux mots sont des **anagrammes** s’ils contiennent les mêmes lettres dans un ordre différent.
> Écris une fonction qui prend deux mots et dit s’ils sont des anagrammes.
> **Exemple :** `"chien"` et `"niche"` → ✅.
> ➕ Aide : trie les lettres de chaque mot (`split`, `sort`, `join`) et compare les chaînes.

---

### 15. **Convertisseur Celsius ↔ Fahrenheit**

> Écris deux fonctions :
>
> * `celsiusVersFahrenheit(c)`
> * `fahrenheitVersCelsius(f)`
>   Elles doivent faire la conversion selon les formules :
> * °F = °C × 1.8 + 32
> * °C = (°F − 32) ÷ 1.8
