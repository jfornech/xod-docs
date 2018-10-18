---
title: Téléversement vers une carte Arduino
---

# #02. Téléversement vers une carte Arduino

<div class="ui segment note">
<span class="ui ribbon label">Remarque</span>
This is a web-version of a tutorial chapter embedded right into the XOD IDE.
To get a better learning experience we recommend to install the
<a href="/downloads/">desktop IDE</a> or start the
<a href="/ide/">browser-based IDE</a>, and you’ll see the same tutorial there.
</div>

Voyons comment téléverser ce nœud vers une Arduino ! À titre 
d'exemple nous allons utiliser le patch "welcome-to-xod/02-deploy".La démarche restera la même pour le téléversement de vos futurs patch vers une carte Arduino.

![Patch](./patch.png)

## Circuit test

![Circuit](./circuit.fz.png)

[↓ Télécharger le projet Fritzing](./circuit.fzz)

## Instructions pour le desktop IDE

1.  Connecter votre Arduino sur votre ordinatuer.
2.  Cliquer sur "Deploy → Upload to Arduino" depuis le menu principal.
3.  Sélectionnez votre modèle de carte et le port auquel elle est connectée, puis cliquer sur
    “Upload”.

![Téléverser vers une carte Arduino](./upload-desktop.gif)

## Instructions for the browser IDE

The browser version does not have permissions to access USB-ports. So you can’t
upload directly. However, you can use an existing Arduino IDE installation to do
this.

La version du navigateur ne dispose pas des autorisations nécessaires pour accéder aux ports USB. Donc vous ne pouvez pas
transférer votre patch directement. Vous devrez utiliser une version de l'IDE Arduino installé sur votre ordinateur pour effectuer la mise à jour de votre carte Arduino.

1.  Assemblez le circuit conformément à l'image ci-dessus.
2.  Générez le code source Arduino de votre premier programme. Pour ce faire, cliquez sur “Deploy → Show Code for Arduino”. Sélectionnez tout le code (Ctrl-A) et copiez-le (Ctrl-C).
3.  Lancez L'IDE Arduino et collez (Ctrl-V) votre code tel quel.
4.  Sélectionnez le port et la carte appropriés depuis le menu «Outils».
5.  Cliquer sur “Téléverser” dans la barre d'outils.

<div class="ui segment note">
<span class="ui ribbon label">Note</span>
Si vous aviez déjà vue à quoi ressemblait le code Arduino pour faire clignoter une LED, vous pourriez être étonné en voyant la quantité de code produite par XOD.
Ne vous inquiétez pas. Il s’agit en grande partie de code destiné à l’environnement d’exécution XOD, qui nécessite peu de traitement pendant la compilation.
Vous n'avez pas réellement besoin de comprendre comment cela fonctionne. Pour le moment, considérez-ceci comme une boîte noire.
</div>

![Upload via Arduino IDE](./upload-web.gif)

<div class="ui segment note">
<span class="ui ribbon label">Retour d'information</span>
Vous avez un problème avec le téléversement? S'il vous plaît le signaler sur notre 
<a href="//forum.xod.io">forum</a>. Décrivez ce que vous avez fait, ce que vous souhaitez 
obtenir, et ce que vous obtenez réellement. Nous vous aiderons.
</div>

[Lesson suivante →](../03-inspector)
