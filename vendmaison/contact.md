---
title: Vend maison d'artiste
layout: default
---

### Je désire recevoir des informations sur votre bien à la vente.<br/>

<form enctype="text/plain" method="post" action="MAILTO:sci.lasource@laposte.net">
<fieldset>
<select name="titre">
  <option value="Monsieur">Monsieur</option>
  <option value="Madame">Madame</option>
  <option value="Mademoiselle">Mademoiselle</option>
</select>

<label for="nom">Nom</label>
<input type="text" name="nom" placeholder="Nom"></input>

<label for="prenom">Prénom</label>
<input type="text" name="prenom" placeholder="Prénom"></input>

<label for="tel">Téléphone</label>
<input type="tel" name="tel" placeholder="+33(0)6 123 456"></input>

<label for="email">Email</label>
<input type="email" name="email" placeholder="xxx@yyy.zz"></input>

<label for="message">Message</label>
<textarea rows="10" cols="50" name="message" placeholder="Laissez votre
 message ici">
</textarea>

</fieldset>

<fieldset>
<input type="submit" value="Envoyer"></input>
</fieldset>

</form>
