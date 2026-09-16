# Contrat graphiste

Deux pages qui produisent le contrat de prestation graphique de TAONSA : prestation, confidentialité et cession de droits d'auteur dans un seul document. Le graphiste remplit le formulaire, signe, imprime en PDF.

`index.html` est la version complète, en onze articles, pour une identité visuelle ou une mission de plusieurs semaines. `court.html` est la version courte, en sept articles tenant sur une seule page A4, pour une commande ponctuelle de faible montant. Les deux pages se renvoient l'une à l'autre et partagent les informations de TAONSA, à saisir une seule fois.

## Utilisation

Ouvrir les fichiers en local, ou via GitHub Pages une fois la branche fusionnée sur `main` :

```
https://<user>.github.io/taonsa-catalog/contrat-graphiste/
https://<user>.github.io/taonsa-catalog/contrat-graphiste/court.html
```

Le bouton « Exemple » remplit tous les champs avec des données fictives pour voir le document fini.

Chaque partie signe soit directement dans le cadre, au doigt ou à la souris, soit en important une photo de sa signature tracée sur une feuille blanche. À l'import, le fond de la photo est rendu transparent et le tracé est recadré, pour que la signature s'intègre au contrat sans rectangle blanc autour.

Saisir d'abord les informations de TAONSA (section 01). Elles sont conservées dans le navigateur, donc à faire une seule fois. Le graphiste complète ensuite les sections 02 à 06, signe et joint sa pièce d'identité. Le bouton « Imprimer / PDF » ouvre la boîte de dialogue d'impression, où « Enregistrer au format PDF » produit le fichier final.

Envoyer ce PDF aux deux adresses e-mail figurant en tête du contrat. C'est cet échange qui sert de preuve en cas de contestation.

Sur la version courte, un indicateur au-dessus de la feuille mesure en continu la hauteur du texte et signale le dépassement avant l'impression, pour que le contrat tienne réellement sur une page.

## Contenu de la version complète

Articles 1 et 2 : mission, livrables, délais, nombre de corrections incluses, fichiers sources exigés à la livraison.

Article 3 : montant en chiffres et en toutes lettres, échéancier, pénalités de retard.

Article 4 : cession exclusive des droits patrimoniaux, conforme à l'Annexe VII de l'Accord de Bangui (OAPI).

Article 5 : garantie d'originalité et garantie d'éviction, avec obligation de fournir les licences des éléments tiers.

Article 6 : confidentialité des fournisseurs, prix d'achat, marges, catalogue, accès et statistiques.

Articles 7 à 11 : accès et sous-traitance, portfolio, résiliation, signature électronique, droit burkinabè.

## Fonctionnement

Aucune dépendance JavaScript et aucun serveur : tout est calculé dans le navigateur. Les signatures et la pièce d'identité ne quittent pas l'appareil. Le brouillon est conservé dans le `localStorage` ; le bouton « Réinitialiser » l'efface.

Le PDF est produit par l'impression du navigateur, ce qui donne un texte sélectionnable au format A4. Chaque contrat porte une référence et un horodatage.

Les polices viennent de Google Fonts. Hors ligne, la page bascule sur des polices système sans casser la mise en page.

## Avant la première utilisation

Le texte est rédigé pour le droit burkinabè mais n'a pas été validé par un juriste. Le faire relire une fois avant de le faire signer.
