# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

[PLAY!](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: Alors, avant que nous départ, before we start, comment voulez-*vous* lire?

`publish("show_options_bottom")`

# intro-start-2

n3: Maintenant, nous commence notre histoire...

```
publish("hide_tabs");
clearText();
```

(...1000)

`publish("intro-to-game-2")`

n2: CELA ES UN HUMAIN

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

```
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
```

(...300)

n: ET CECI ES L'ANXIÉTÉ DE LUI

n: _TU_ ES L'ANXIÉTÉ

(#act1_normal)


# act1_normal

```
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Non. Non, non, je ne t'écoute pas. Gonna check my phone.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: TON TÂCHE VA ÊTRE DE PROTECTRE VOTRE HUMAIN CONTRE LE *DANGER*

`bb({eyes:"look", mouth:"small_lock", body:"fear"})`

b: Mon dieux! Tu gâches ta vie sur Twitter! Encore!

```
bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
```

h: Oui, je demande pourquoi je ne m'assois plus pour écouter mon cerveau.

`hong({eyes:"neutral"});`

n: RAPIDEMENT, DIS-LUI À PROPOS LE *DANGER!*

```
bb({eyes:"look"});
```

[Mon dieux, regarde ça article horrible!](#act1d_news)

[Mon dieux, est-ce que ce tweet parle à propos *nous?*](#act1d_subtweet)

[Regard, un GIF de un chat qui boir de lait!](#act1d_milk)

# act1d_milk

`hong({mouth:"smile", eyes:"surprise"});`

h: Oh, oui, c'est très mignon, je--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: LES CHATS NE PEUT PAS BOIR LE LAIT ET NOUS SOMMES MAUVAIS PARCE QUE NOUS AIMIONS

(...200)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("20p", "bad");
publish("hp_show");
```



