## Base scss 

<a><img src="https://github.com/Enzo2911/Bonne-Base-Pour-Mes-Project/blob/main/Bonne%20Base%20SCSS/img%20readme/Pour_un_bon_Debut_de_Project-removebg-preview.png"></a>
<center>

- Suffit de lancé npm i

- Yarn sass 

- Now Good Luck with your project. :)
</center>

<a><center><img src="https://github.com/Enzo2911/Bonne-Base-Pour-Mes-Project/blob/main/Bonne%20Base%20SCSS/img%20readme/Bug__-removebg-preview.png"></center></a>

<h1> Solution 1 : </h1>

```
npm cache clean --force

npm install <module> or sudo
``` 

<h1> Solution 2 : </h1>

```
npm install -g <module> or sudo 
``` 

<h1> Solution 3 : </h1>

```
mkdir ~/.npm-global
npm config set prefix '~/.npm-global'
export PATH=~/.npm-global/bin:$PATH ### Add this to the end of the file ~/.profile
source ~/.profile
``` 

<h1> Solution 4 radical : </h1>

```
npm install --unsafe-perm -g <module>
``` 

Si vous ne voulez plus avoir le problem (je ne sais pas si c'est une faille de sécurité).
npm config set unsafe-perm true
or sudo npm config set unsafe-perm true

```
Utilisez ceci avec parcimonie; probablement mauvais à définir globalement pour tous les scripts en cours d'exécution. Si l'utilisateur est en cours d'exécution, rootl'application peut forcer des modifications qui pourraient s'étendre au-delà de ce qu'un script en cours d'exécution devrait avoir. Ne jamais exécuter en tant que rootet ce sera truepar défaut. Utilisez sudoautrement. Ce n'est pas une solution magique.

source : https://geedew.com/What-does-unsafe-perm-in-npm-actually-do/
```

