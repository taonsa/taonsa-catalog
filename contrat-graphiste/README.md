# Contrat graphiste — générateur

Page unique et autonome (`index.html`) qui génère le **contrat de prestation graphique, de cession de droits d'auteur et de confidentialité** de TAONSA : le graphiste remplit le formulaire, signe au doigt ou à la souris, et le contrat se met à jour en direct.

## Utilisation

Ouvrir `index.html` — en local, ou via GitHub Pages une fois fusionné sur `main` :

```
https://<user>.github.io/taonsa-catalog/contrat-graphiste/
```

1. **Exemple** remplit tous les champs avec des données fictives, pour voir le rendu final.
2. Renseigner les mentions légales de TAONSA (section 01) : elles restent enregistrées dans le navigateur, à ne faire qu'une fois.
3. Le graphiste complète les sections 02 à 06, signe, et joint sa pièce d'identité.
4. **Imprimer / PDF** → dans la boîte de dialogue, choisir « Enregistrer au format PDF ».
5. Envoyer le PDF par e-mail aux deux adresses indiquées en tête du contrat : c'est cet échange qui constitue la preuve de l'accord.

## Ce que couvre le contrat

| Article | Objet |
|---|---|
| 1–2 | Mission, livrables, délais, nombre de corrections incluses, fichiers sources exigés |
| 3 | Montant, montant en toutes lettres, échéancier, pénalités de retard |
| 4 | Cession exclusive des droits patrimoniaux (OAPI / Annexe VII de l'Accord de Bangui) |
| 5 | Garantie d'originalité et garantie d'éviction (images, polices, éléments générés par IA) |
| 6 | Confidentialité : fournisseurs, prix d'achat, marges, catalogue, accès, statistiques |
| 7 | Accès, sécurité, sous-traitance |
| 8 | Portfolio : autorisé après publication, ou interdit |
| 9–11 | Résiliation, signature électronique et preuve, droit burkinabè |

## Notes techniques

- Aucune dépendance JavaScript, aucun serveur : tout est calculé dans le navigateur.
- **Aucune donnée ne quitte l'appareil** — signatures et pièce d'identité comprises. Le brouillon est conservé dans le `localStorage` du navigateur ; « Réinitialiser » l'efface.
- Le PDF est produit par l'impression du navigateur : texte sélectionnable, mise en page A4.
- Chaque contrat porte une référence, un horodatage et une empreinte SHA-256 de son contenu.
- Polices chargées depuis Google Fonts ; hors ligne, la page bascule sur des polices système sans casser la mise en page.

## Avant la première utilisation

Le modèle est rédigé pour le droit burkinabè mais **n'a pas été validé par un juriste**. Faites-le relire une fois avant de le faire signer.
