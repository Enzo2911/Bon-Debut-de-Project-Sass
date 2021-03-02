## Base scss 

### Pour un bon debut de project 

- Suffit de lancé npm i

- Yarn sass 

<p> et voila bon project a toi </p>

### Si Bug 

solution 1 :

clear cache 

npm install -g <module>

solution 2 :

mkdir ~/.npm-global
npm config set prefix '~/.npm-global'
export PATH=~/.npm-global/bin:$PATH ### Add this to the end of the file ~/.profile
source ~/.profile

solution 3 radical : 

npm install --unsafe-perm -g <module>

si vous ne voulez plus avoir le problem (je ne sais pas si c'est une faille de sécurité).
npm config set unsafe-perm true
or sudo npm config set unsafe-perm true

```
Utilisez ceci avec parcimonie; probablement mauvais à définir globalement pour tous les scripts en cours d'exécution. Si l'utilisateur est en cours d'exécution, rootl'application peut forcer des modifications qui pourraient s'étendre au-delà de ce qu'un script en cours d'exécution devrait avoir. Ne jamais exécuter en tant que rootet ce sera truepar défaut. Utilisez sudoautrement. Ce n'est pas une solution magique.

source : https://geedew.com/What-does-unsafe-perm-in-npm-actually-do/
```
