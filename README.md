# HALAL-SCANNER — compagnon halal

Application web responsive en français :
- recherche de produits alimentaires par code-barres avec Open Food Facts ;
- scan caméra EAN/UPC lorsque le navigateur prend en charge BarcodeDetector ;
- horaires de prière par ville, méthode de calcul et géolocalisation facultative ;
- direction de la Qibla ;
- compteur de Tasbih et invocations.

## Lancer le site
Hébergez les fichiers à la racine avec GitHub Pages, Netlify ou Vercel. Caméra et géolocalisation nécessitent HTTPS (ou localhost).

## Sources
- Open Food Facts : fiches produits et ingrédients.
- AlAdhan : horaires de prière et date hégirienne.
- BigDataCloud : géocodage inversé facultatif.

## Limites
L'analyse des ingrédients est indicative, pas une fatwa ni une certification halal. L'origine de certains additifs (E471/E472), enzymes, arômes, présures et gélatines varie selon le fabricant. « Aucun ingrédient à risque détecté » ne signifie pas « certifié halal ». Les horaires varient selon la méthode et doivent être comparés à ceux de la mosquée locale.

## Confidentialité
La caméra ne démarre qu'après action de l'utilisateur. La géolocalisation est facultative et demandée uniquement sur action. Les requêtes produits et horaires sont envoyées aux services tiers indiqués ci-dessus.
