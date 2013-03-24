!SLIDE ============================

![](angularjs-900px.png)


!SLIDE image ======================

# Thierry Chatel
![](photo-Thierry-Chatel.png)


!SLIDE image ======================

![](lunel.png)


!SLIDE image ======================

![](logo_methotic.png)

<table>
 <tr>
  <td>![](architect.jpg)</td>
  <td>![](good.png)</td>
  <td>![](not-solid.png)</td>
 </tr>
</table>


!SLIDE image ======================

<table>
 <tr>
  <td>![](prof.png)</td>
  <td>![](angularjs-logo.png)</td>
 </tr>
</table>


!SLIDE image ======================

<table>
 <tr>
  <td>![](java.png)</td>
  <td>![](ibm.png)</td>
  <td>![](trilog.png)</td>
 </tr>
</table>


!SLIDE image ======================

![](flowbuilder.jpg)


!SLIDE image ======================

![](angular-old.png)


!SLIDE image ======================

![](angular-new.png)


!SLIDE image ======================

![](trends.png)


!SLIDE subsection =================

# Qu'est-ce qu'AngularJS ?


!SLIDE ============================

# framework JavaScript

### 43866 lignes de code JavaScript
### minified 77 KB


!SLIDE code small =======================

<code>
AngularJS versions

Release Date    Version     Codename
Feb 20, 2013    1.1.3       radioactive-gargle
Feb 20, 2013    1.0.5       flatulent-propulsion
Jan 22, 2013    1.1.2       tofu-animation
Jan 22, 2013    1.0.4       bewildering-hair
Nov 26, 2012    1.1.1       pathological-kerning
Nov 26, 2012    1.0.3       bouncy-thunder
Aug 31, 2012    1.1.0       increase-gravatas
Aug 31, 2012    1.0.2       debilitating-awesomeness
Jun 25, 2012    1.0.1       thorium-shielding
<strong class="red">Jun 13, 2012    1.0.0       temporal-domination</strong>
Jun 12, 2012    1.0.0rc12   regression-extermination
Jun 10, 2012    1.0.0rc11   promise-resolution
May 23, 2012    1.0.0rc10   tesseract-giftwrapping
May 14, 2012    1.0.0rc9    eggplant-teleportation
May 6,  2012    1.0.0rc8    blooming-touch
Apr 30, 2012    1.0.0rc7    rc-generation
Apr 20, 2012    1.0.0rc6    runny-nose
Apr 12, 2012    1.0.0rc5    reality-distortion
Apr 5,  2012    1.0.0rc4    insomnia-induction
Mar 29, 2012    1.0.0rc3    barefoot-telepathy
Mar 20, 2012    1.0.0rc2    silence-absorption
Mar 13, 2012    1.0.0rc1    moiré-vision
Jan 17, 2012    0.10.6      bubblewrap-cape
Nov 8,  2011    0.10.5      steel-fist
Oct 22, 2011    0.10.4      human-torch
Oct 13, 2011    0.10.3      shattering-heartbeat
Oct 8,  2011    0.10.2      sneaky-seagull
Sep 9,  2011    0.10.1      inexorable-juggernaut
Sep 2,  2011    0.10.0      chicken-hands
Aug 20, 2011    0.9.19      canine-psychokinesis
</code>

!SLIDE ============================

<table>
 <tr>
  <td>![](misko-hevery.jpg)<br/><br/>
        Miško Hevery</td>
  <td>![](vojta-jina.jpg)<br/><br/> 
        Vojta Jína</td>
  <td>![](igor-minar.jpg)<br/><br/>
        Igor Minar</td>
 </tr>
</table>
<br/><br/>

![](google-logo-small.png)


!SLIDE ============================

# _“HTML enhanced_
# _for web apps!”_


!SLIDE image ======================

![](trello.png)


!SLIDE image ======================

![](doubleclick.jpg)

<table style="width: 100%">
 <tr>
  <td style="text-align: right">![](angularjs-logo-small.png)</td>
 </tr>
</table>
<br/><br/>


!SLIDE image ======================

![](ovh.png)


!SLIDE image ======================

![](youtube-ps3.png)


!SLIDE big ========================

# _HTML enhanced ?_


!SLIDE back =======================

<a href="https://twitter.com/nickmuth/status/230465353078153216">![](html6.png)</a>

# _HTML 6 ?_

!SLIDE image ======================

<a href="http://www.appliness.com/february-issue-with-misko-hevery/">![](interview.png)</a>


!SLIDE image ======================

![](one-way-db.png)


!SLIDE image ======================

![](two-way-db.png)


!SLIDE big ======================

## AngularJS Hello World!

<br/>

<div class="left bigger">
Your name: <input ng-model="me" name="name" autocomplete="off" style="font-size: 1em; width: 7em;"><br/>
<span class="result">Hello {{me}}!</span>
</div>

<br/>

    Your name: <input ng-model="me">
    Hello {{me}}!


!SLIDE ============================

## code JavaScript
# ↓
# modèle


!SLIDE ============================

# indépendant de la vue

<div class="right">![](idea.png)</div>

!SLIDE image ======================

![](magic.png)


!SLIDE ============================

# watches
# +
# dirty cheching


!SLIDE ============================

![](watch.png)
## expression = propriété, fonction, etc.


!SLIDE image ======================

![](checklist.png)


!SLIDE image ======================

![](mandelbrot.png)


!SLIDE ============================

# 2000 *watches* simples


!SLIDE ============================

# Web Components
# Object.observe()


!SLIDE image ======================

![](structure.png)


!SLIDE ============================

# appli AngularJS ?

<br/>

    <div ng-app="myApp">
      ...
    </div>


!SLIDE ============================

# plusieurs applis
# dans une page web

<div class="right">![](idea.png)</div>


!SLIDE ============================

![](mono-page.png)

# appli mono-page


!SLIDE ============================

![](routage.png)

# AngularJS gère le routage

![](bookmark.png)
![](back.png)
![](forward.png)


!SLIDE ============================

# modules
# services
## injection de dépendances

<div class="right">![](idea.png)</div>


!SLIDE ============================

# objets & fonctions JS *quelconques*

<div class="right">![](idea.png)</div>


!SLIDE bullets =====================

![](components.png)

* vues : directives & filtres
* logique : services


!SLIDE bullets =====================

![](idea.png)

* code JS indépendant des vues
* injection de dépendances
* objets JS quelconques
* pas d'état global


!SLIDE ============================

# facilement testable

### tests unitaires de tout le code JS
### avec [Karma](http://karma-runner.github.com/) (ex-Testacular)


!SLIDE ============================

# tests end-to-end

### outil d'automatisation de scénarios
### qui s'appuie sur le framework


!SLIDE ============================

![](swiss-knife.png)

## plate-forme très complete
### au bon niveau d'abstraction


!SLIDE back ========================

![](ui.png)

# AngularUI, AngularStrap, etc.


!SLIDE ============================

![](opinionated.png)

# _“opinionated framework”_



!SLIDE back ========================

![](tutorial.png)

# tutoriel sur angularjs.org


!SLIDE back ========================

![](angular-seed.png)

# angular-seed sur GitHub


!SLIDE back ========================

![](egghead.png)

# vidéos sur EggHead


!SLIDE back ========================

![](frangular.png)

# FrAngular


!SLIDE subsection =================

# Exemples


