---
title: "Test Liens Anchor"
date: 2022-02-03T21:52:45-05:00
draft: true
meta: ""
hidemeta: false
hidedescription: true

tags: []
categories: [""]

cover:
  image: "/recits/.jpg"
  
  alt: ""
  caption: "Photo:"
  relative: false # To use relative path for cover image, used in hugo Page-bundles

ShowShareButtons: true
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
---
{{< code-html >}} 
<div class="contexte">
<p></p>
</div>
{{< /code-html >}}

+++

Paragraphe de texte

1. [Lien 1]({{< ref "test-liens-anchor.md#1" >}} "1")
2. Lien 2
3. Lien 3

## {#1} 
Paragraphe 1

Paragraphe 2


Votre stoïcisme laisse curieusement sa place à une sensation que vous aviez oubliée: vous ressentez de la félicité, de l'admiration devant cette prestation magistrale.

La foule ne cesse d'applaudir. Vous jetez des coups d'oeil furtifs vers les autres juges. Malgré leur neutralité, vous remarquez sur leur visage que le duo les a profondément touchés. En grands professionnels, ils se penchent toutefois sur leurs écrans pour y inscrire leurs scores.

Le temps file. Vous devez faire de même. C'est maintenant que le plan doit se mettre à exécution. Le doute s'empare de vous. Pour la première fois de votre carrière, vous songez à ne pas respecter vos ordres. La performance que vous venez de voir était tellement bonne qu'il ne ferait aucun sens de lui accorder une mauvaise note. "Ça va se savoir, c'est beaucoup trop évident!"

{{< code-html >}} 
<style>
#option1 {
  width: 100%;
  margin-top: 20px;
  display: none;
}
#option2 {
  width: 100%;
  margin-top: 20px;
  display: none;
}
</style>

<script>
function myFunction() {
  var x = document.getElementById("option1");
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
function myFunction2() {
  var y = document.getElementById("option2");
  if (y.style.display === "block") {
    y.style.display = "none";
  } else {
    y.style.display = "block";
  }
}
</script>

<p><strong>Agente 47, que faites-vous à cet instant?</strong></p>

<p><button onclick="myFunction()" style="background:var(--secondary); color:var(--theme); padding: 10px; border: 1px solid var(--secondary);">Vous désobéissez</button>

<button onclick="myFunction2()" onclick="hideoption1()" style="background:var(--secondary); color:var(--theme); padding: 10px; border: 1px solid var(--secondary);">Vous obéissez</button>

<div id="option1">
<p><strong>Vous désobéissez.</strong></p>
</div>

<div id="option2">
<p><strong>Vous obéissez.</strong></p>
</div>

{{< /code-html >}}

+++

{{< code-html >}} 
<div class="contexte">
<p></p>
<p>Si vous avez apprécié votre lecture et que vous avez envie de partager ce récit, vous me donneriez un super coup de pouce! :hearts:</p>

<p>Toutes les updates de Relectures sont sur <a href=”https://www.facebook.com/relectures.ca”>Facebook</a>, <a href=”https://www.instagram.com/relectures/”>Instagram</a> et <a href=”https://twitter.com/relectures_”>Twitter</a>.</p>
</div>
{{< /code-html >}}