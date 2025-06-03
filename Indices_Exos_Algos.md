## 🌱 Exercices JavaScript – Niveau Débutant (Markdown)

---

### 1. 🟢 Pair ou Impair

Écris une fonction qui prend un entier en paramètre et affiche s’il est **“Pair”** ou **“Impair”**.

<details>
<summary>🧠 Indice</summary>

Utilise l’opérateur **modulo `%`** pour tester si un nombre est divisible par 2.

</details>

```js
// Ton code ici
```

---

### 2. 🟢 Plus grand des deux

Écris une fonction qui prend **deux nombres** et retourne **le plus grand** des deux.

<details>
<summary>🧠 Indice</summary>

Utilise une structure `if` ou l’opérateur `Math.max(a, b)`.

</details>

```js
// Ton code ici
```

---

### 3. 🟢 Table de multiplication

Écris une fonction qui **affiche la table de multiplication de 1 à 10** pour un nombre donné.

<details>
<summary>🧠 Indice</summary>

Utilise une **boucle `for`** allant de 1 à 10, et multiplie à chaque tour.

</details>

```js
// Ton code ici
```

---

### 4. 🟢 Somme de 1 à N

Écris une fonction `sommeJusqua(n)` qui retourne la **somme des entiers de 1 à `n`**.

<details>
<summary>🧠 Indice</summary>

Deux options :

* Une **boucle `for`**
* Ou la **formule mathématique** : `n * (n + 1) / 2`

</details>

```js
// Ton code ici
```

---

### 5. 🟢 Factorielle

Écris une fonction `factorielle(n)` qui calcule la **factorielle de `n`** (ex : `5! = 5×4×3×2×1`).

<details>
<summary>🧠 Indice</summary>

Initialise une variable `resultat = 1`, puis utilise une boucle `for` pour multiplier tous les nombres jusqu’à `n`.

</details>

```js
// Ton code ici
```

---

Parfait ! Voici la **suite complète des exercices 6 à 15 en Markdown**, toujours avec :

* Énoncé 📘
* Bloc d’indice repliable 🧠
* Zone de code 📝

---

## 🔁 Exercices JavaScript – Niveau Intermédiaire

---

### 6. 🔵 Palindrome

Écris une fonction qui vérifie si un mot est un **palindrome** (se lit dans les deux sens).

<details>
<summary>🧠 Indice</summary>

Inverser la chaîne avec `.split('').reverse().join('')` et la comparer avec l'originale.

</details>

```js
// Ton code ici
```

---

### 7. 🔵 Compter les voyelles

Prends une chaîne et retourne **le nombre de voyelles** (`a, e, i, o, u, y`).

<details>
<summary>🧠 Indice</summary>

Parcours chaque caractère et vérifie s’il est dans `"aeiouy"` (ou utilise une expression régulière).

</details>

```js
// Ton code ici
```

---

### 8. 🔵 Inverser une chaîne

Fonction qui retourne une **chaîne inversée** (ex. `"chat"` → `"tahc"`).

<details>
<summary>🧠 Indice</summary>

Utilise `.split('')`, `.reverse()` et `.join('')`.

</details>

```js
// Ton code ici
```

---

### 9. 🔵 Plus grand élément d’un tableau

Fonction qui prend un tableau de nombres et retourne **la plus grande valeur**.

<details>
<summary>🧠 Indice</summary>

Utilise une boucle ou `Math.max(...tableau)`.

</details>

```js
// Ton code ici
```

---

### 10. 🔵 FizzBuzz

Pour les nombres de **1 à 100** :

* Affiche `"Fizz"` si divisible par 3
* `"Buzz"` si divisible par 5
* `"FizzBuzz"` si divisible par 3 et 5
* Sinon, affiche le nombre

<details>
<summary>🧠 Indice</summary>

Utilise une boucle `for`, et des conditions `if (n % 3 === 0)` etc.

</details>

```js
// Ton code ici
```

---

## 🧩 Exercices Bonus – DOM + JS Avancé

---

### 11. 🟣 Générateur de liste HTML

Crée une fonction qui, à partir d’un tableau de mots, ajoute dynamiquement une liste `<ul>` dans la page.

<details>
<summary>🧠 Indice</summary>

Utilise `document.createElement`, `appendChild`, et une boucle sur ton tableau.

</details>

```js
// Ton code ici
```

---

### 12. 🟣 Compteur dynamique

Crée un **bouton HTML** qui augmente un **compteur affiché à l’écran** à chaque clic.

<details>
<summary>🧠 Indice</summary>

Modifie le `innerText` d’un élément HTML à chaque clic (`addEventListener('click', ...)`).

</details>

```js
// Ton code ici
```

---

### 13. 🟣 Vérificateur de palindrome (DOM)

Crée un **input texte + bouton** qui vérifie si le mot entré est un palindrome et affiche le résultat.

<details>
<summary>🧠 Indice</summary>

Récupère la valeur de l’input avec `.value`, puis utilise l’algorithme du palindrome vu avant.

</details>

```js
// Ton code ici
```

---

### 14. 🟣 Générateur de mot de passe

Écris une fonction qui génère un **mot de passe aléatoire** de longueur donnée, avec **lettres, chiffres et symboles**.

<details>
<summary>🧠 Indice</summary>

Utilise une chaîne de tous les caractères possibles, puis choisis-en un aléatoire avec `Math.random()`.

</details>

```js
// Ton code ici
```

---

### 15. 🟣 Todo List interactive

Crée une **todo-list** avec :

* Ajout de tâches via un input
* Affichage dans la page
* Possibilité de supprimer ou cocher les tâches

<details>
<summary>🧠 Indice</summary>

Utilise le DOM : création d’éléments `<li>`, événements `click`, `appendChild`, et `remove()`.

</details>

```js
// Ton code ici
```
