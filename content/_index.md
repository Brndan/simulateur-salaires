---
title: "Prime d’attractivité : quel montant ?"
date: 2020-10-23T08:08:47+02:00
draft: false
---

Le ministre a promis une revalorisation « exceptionnelle » du salaire des personnels. Mais s’agit-il véritablement d’une hausse importante du salaire ? SUD éducation vous propose ce simulateur pour faire le point.

{{< rawhtml >}}




<script type="text/javascript" src="js/salaires.js"></script>
<link rel="stylesheet" type="text/css" href="css/resultat.css">

<h2>Votre situation</h2>
<div class="blocSelection">
   <label for="statut">Sélectionnez votre corps ou statut&nbsp;:</label>
   <div class="menuSelection">
      <select name="Corps" id="statut" onchange="afficheEchelon();">
         <option value="rien" selected>Choisissez…</option>
         <option value="pe">Professeur⋅e des écoles</option>
         <option value="certifie">Certifié⋅e, PLP, PEPS, CPE, PsyÉN</option>
         <option value="contrat">Contractuel⋅le enseignant⋅e</option>
         <option value="agrege">Agrégé⋅e</option>
         <option value="autre">Autre</option>
      </select>
   </div>
</div>
<div class="blocSelection" id="menuEchelon">
   <label for="echelon">Sélectionnez votre échelon&nbsp;:</label>
   <div class="menuSelection">
      <select name="echelon" id="echelon" onchange="afficheEchelon();">
         <option value="1">Échelon 1</option>
         <option value="2">Échelon 2</option>
         <option value="3" selected>Échelon 3</option>
         <option value="4">Échelon 4</option>
         <option value="5">Échelon 5</option>
         <option value="6">Échelon 6</option>
         <option value="7">Échelon 7</option>
         <option value="8">Échelon 8</option>
         <option value="9">Échelon 9 et plus</option>
      </select>
   </div>
</div>
<div class="boutonCalcul" id="calcul">
   <input type="button" value="Calculer" onclick="calcul();" />
</div>
<div id="aAfficher">
   <div id="resultat">
      <h2>Résultat</h2>
      <p>Le gouvernement envisage le versement d’une prime dégressive à mesure que l’on progresse dans la carrière.</p>
   </div>
   <div id="debutCarriere">
      <p>Le versement de la “prime d’attractivité” du ministère n'est pas prévu par le ministère au premier échelon. SUD éducation dénonce cette décision, d’autant plus que les salaires des enseignant-e-s en début de carrière sont scandaleusement bas. SUD éducation revendique une augmentation des salaires d’autant plus forte que les salaires sont faibles, pour tous les personnels.</p>
	  <p>Pour mémoire, depuis 1995, le gel du point d’indice a conduit les <b>salaires dans la fonction publique à baisser de 19,82% en raison de l’inflation.</b></p>
   </div>
   <div id="echelonEleve">
      <p>Au-delà du septième échelon de la classe normale, aucune revalorisation n’est prévue pour les personnels, pourtant enseignants depuis de nombreuses années.</p>
	  <p>Pour mémoire, depuis 1995, le gel du point d’indice a conduit les <b>salaires dans la fonction publique à baisser de 19,82% en raison de l’inflation.</b>
   </div>
   <div id="autre">
      <p>Vous n’êtes pas personnel enseignant&nbsp;? La revalorisation n’est pas prévue pour vous. Pour SUD éducation, ce sont <b>bien tous les personnels qui doivent bénéficier d’une augmentation de salaire maintenant</b>.</p>
	  <p>Pour mémoire, depuis 1995, le gel du point d’indice a conduit les <b>salaires dans la fonction publique à baisser de 19,82% en raison de l’inflation.</b>
   </div>
   <div id="contrat">
      <p>Pour les enseignant-e-s non-titulaires, le ministère prévoit le versement forfaitaire d’une prime dégressive en fonction de l’ancienneté dans la carrière.</p>
      <figure>
         <table>
            <thead>
               <tr>
                  <th>Carrière</th>
                  <th>Montant brut annuel</th>
                  <th>Montant brut mensuel</th>
                  <th>Montant net mensuel</th>
               </tr>
            </thead>
            <tbody>
               <tr>
                  <td>Palier 1</td>
                  <td>700€ bruts</td>
                  <td>58,33€ bruts</td>
                  <td>49,93€ nets</td>
               </tr>
               <tr>
                  <td>Palier 7</td>
                  <td>400€ bruts</td>
                  <td>33,33€ bruts</td>
                  <td>28,5€ nets</td>
               </tr>
            </tbody>
         </table>
      </figure>
	  <p>Ces primes sont plus faibles que celles des titulaires. Ce sont donc une nouvelles fois les personnels avec les conditions d’emploi les moins favorables qui sont les plus mal traités</p>
	  <p>Pour mémoire, depuis 1995, le gel du point d’indice a conduit les <b>salaires dans la fonction publique à baisser de 19,82% en raison de l’inflation.</b>
   </div>
   <div id="scenarios">
      <p id="sc3">
      <p id="sc3inflation"></p>
   </div>
</div>



{{< /rawhtml >}}
