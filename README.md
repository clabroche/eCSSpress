# eCSSpress #

eCSSpress est un framework permettant de coder plus vite la partie CSS en ayant pour base un ensemble de regles personnalisable. 

## Installation ##

Vous pouvez installer ce framework avec bower: 



```
#!bash
echo '{        
  "name" : "projet",
  "version": "0.1",
  "dependencies" : {
    "eCSSpress" : "https://Iryu54@bitbucket.org/Iryu54/ecsspress.git"
  }
}' > bower.json && bower install

```
ou si vous possedez déjà un bower.json, ajoutez simplement la ligne suivante dans la partie dependencies


```
#!bash
"eCSSpress" : "https://Iryu54@bitbucket.org/Iryu54/ecsspress.git"

```



## Documentation ##

La documentation du framework est situé dans le dossier demo

Selon votre choix vous pouvez utiliser :

1. la version compilé du framework (dist/css/eCSSpress.css)
2. la verison sass (dist/scss) 

Dans le cas où vous utilisez la version sass, vous pouvez vous inspirer du fichier dist/scss/eCSSpress.scss pour importer vos éléments et vous pouvez les customiser les variables dans le fichier dist/scss/_variablesCustom.scss 