# Tutoriel Markdown pour Jupyter

Ce notebook montre comment utiliser du **markdown** dans JupyterLab.

Une cellule peut être en mode **Code** (executer du Python) ou en **Markdown** (formatage de texte)

## Titres

Nous pouvons créer des titres avec le caractere `#`

```
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
```

# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3

## Interpretation du HTML

Nous pouvons utiliser des balises html pour le formatage de notre texte. 

```
<h1>Titre de niveau 1</h1>
<h2>Titre de niveau 2</h2>
<h3>Titre de niveau 3</h3>
```

<h1>Titre de niveau 1</h1>
<h2>Titre de niveau 2</h2>
<h3>Titre de niveau 3</h3>

## Mise en forme du texte

- Italique : `*texte*` -> *texte*
- Gras: `**texte**` -> **texte**
- Barré: `~~texte~~` -> ~~texte~~
- Code: \`texte\` -> `texte`


# Listes 

Liste à puces :

```
- Element 1
- Element 2
    - Sous-element
```

- Element 1
- Element 2
    - Sous-element

Liste numérotée : 

```
1. Element 1
2. Element 2
```

1. Element 1
2. Element 2

# Tableaux 

```
| Nom | Age      | Ville      | 
|-----|:-----:|-------:|
|Toto | 25  | Londre |
|Titi | 30  | Paris  |
```

| Nom de famille | Age de la personne | Ville de naissance | 
|-----|:-----:|-------:|
|Toto | 25  | Londre |
|Titi | 30  | Paris  |

# Code

Pour afficher un bloc de code, nous pouvons utiliser 3 backstick ``` :

```python
def hello_world()
    print("Hello World !!")
```

# Mathematiques (LaTeX)

On peut insérer des formules : 

Formule en 1 ligne : `$E = mc^2$` -> $E = mc^2$ 

Bloc centré: 
```latex
$$\int_0^1 x^2 dx = \frac{1}{3}$$
```

$$\int_0^1 x^2 dx = \frac{1}{3}$$
