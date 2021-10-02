---
title: window.opener
slug: Web/API/Window/opener
tags:
  - DOM
  - DOM_0
  - Référence_du_DOM_Gecko
translation_of: Web/API/Window/opener
---
<p>{{ ApiRef() }}</p>
<h3 id="R.C3.A9sum.C3.A9">Résumé</h3>
<p>Renvoie une référence vers la fenêtre qui a ouvert la fenêtre courante.</p>
<h3 id="Syntaxe">Syntaxe</h3>
<pre class="eval"><i>refObj</i> = window.opener
</pre>
<h3 id="Exemple">Exemple</h3>
<pre> if window.opener != indexWin {
     referToTop(window.opener);
 }
</pre>
<h3 id="Notes">Notes</h3>
<p>Lorsqu'une fenêtre est ouverte depuis une autre fenêtre, elle conserve une référence à cette première fenêtre dans <code>window.opener</code>. Si la fenêtre courante n'a pas été ouverte par une autre fenêtre, la méthode renvoie <code>null</code>.</p>
<h3 id="Sp.C3.A9cification">Spécification</h3>
<p>{{ DOM0() }}</p>