!SLIDE ============================

![](angularjs-900px.png)



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
Your name: <input ng-model="name" name="name" autocomplete="off" style="font-size: 1em; width: 7em;"><br/>
<span class="result">Hello {{name}}!</span>
</div>

<br/>

    Your name: <input ng-model="name">
    Hello {{name}}!













!SLIDE subsection =================

# “only talk to your friends”


!SLIDE ============================

![](fb.jpg)

![](network.jpg)


!SLIDE bullets top ====================

<br/>

### *une méthode ne peut appeler de méthode que :*

!SLIDE bullets top ====================

<br/>

### *une méthode ne peut appeler de méthode que :*

* de l'objet lui-même

!SLIDE bullets top ====================

<br/>

### *une méthode ne peut appeler de méthode que :*

* de l'objet lui-même
* de ses arguments

!SLIDE bullets top ====================

<br/>

### *une méthode ne peut appeler de méthode que :*

* de l'objet lui-même
* de ses arguments
* d'un objet qu'elle a créé

!SLIDE bullets top ====================
                                                                                                         
<br/>

### *une méthode ne peut appeler de méthode que :*

* de l'objet lui-même
* de ses arguments
* d'un objet qu'elle a créé
* d'une propriété **_directe_** de l'objet


!SLIDE subsection =================

# limiter le couplage !


!SLIDE ============================

![](spaghetti.jpg)


!SLIDE ============================
# “un seul point”
# <span class="green">xxx.yyy</span>
# <span class="red">xxx.yyy.zzz</span>


!SLIDE ============================
# <span class="red">prop.truc.methode()</span>


!SLIDE ============================
# <span class="red">a = prop.truc</span>
# <span class="red">a.methode()</span>


!SLIDE ============================
# prop.truc().methode()
# ?


!SLIDE subsection =================

# encapsulation


!SLIDE ============================
# <span class="red">prop.getInterne().methode()</span>


!SLIDE ============================
# <span class="green">prop.search().count()</span>


!SLIDE ============================

![](caisse.jpg)


!SLIDE subsection =================

# “tell, don't ask”


!SLIDE ============================
## <span class="red">client.portemonnaie.pieces -= 3</span>


!SLIDE left =======================
## <span class="red">&nbsp;&nbsp;client.getPortemonnaie().setPieces(</span>
## <span class="red">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;client.getPortemonnaie().getPieces() - 3)</span>


!SLIDE ============================
## <span class="green">client.payer(3);</span>


!SLIDE ============================

# déléguer des comportements
### pas des propriétés


!SLIDE ============================
## [*“Why getter and setter methods are evil”*](http://www.javaworld.com/javaworld/jw-09-2003/jw-0905-toolbox.html)
### by Allen Holub

![](holub.jpg)


!SLIDE subsection =================

# danger d'un objet “contexte”


!SLIDE ============================
## [*“Breaking the Law of Demeter is Like Looking for a Needle in the Haystack”*](http://misko.hevery.com/2008/07/18/breaking-the-law-of-demeter-is-like-looking-for-a-needle-in-the-haystack/)
### by Miško Hevery

![](misko.jpg)



!SLIDE code big ===================

    class Mechanic {
    
        Engine engine;

        Mechanic(Context context) {
            this.engine = context.getEngine();
        }
    }



!SLIDE back =======================

![](fowler.jpg)

# “loi” : à relativiser


!SLIDE bullets ====================

# violations nécessaires

* {user.profile.name}
* si les données sont un ViewModel</div>


!SLIDE subsection =================

# D D D


!SLIDE ============================

![](ddd.jpg)


!SLIDE ============================

# agrégat

![](aggr.png)

