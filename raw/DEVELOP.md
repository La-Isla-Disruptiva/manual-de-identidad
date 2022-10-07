# Utilise inkscape pour récupérer les fragments de svg

inkscape Manual\ de\ \identitad-05.svg

...

sauvegarde

# Simplifie

svgo -i dibujo.svg -o tmp.svg --config svgo-config.js

# Change la couleur par une classe

sed -i 's/fill="..."/class="..."/g' tmp.svg

