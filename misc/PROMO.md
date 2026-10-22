# intro

`SceneSetup.intro();`

# intro-play-button

[<div class="mini-icon" pic="play1"></div> JOUEZ! <div class="mini-icon" pic="play2"></div>](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: derp

`publish("show_options_bottom")`

# intro-start-2

`clearText()`

(...1000)

`publish("intro-to-game-2")`

n2: CELA ES UN HUMAIN

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

`SceneSetup.act1();`

(...300)

n: ET CECI ES L'ANXIÉTÉ DE LUI

n: _TU_ ES L'ANXIÉTÉ

[On manges tout seul pour diner! Encore!](#act1a_alone)

[Nous ne sommes pas occupés quand on mangeons!](#act1a_productive)

[Ce pain blanc va nous empoisonner!](#act1a_bread)

# act1a_alone

`bb({mouth:"small", eyes:"narrow"})`

b: Savais-tu que la solitude est aussi associée à mourir jeune que le fait de fumer 15 cigarettes par jour?-

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({mouth:"normal", eyes:"normal_right"})`

b: (Holt-Lunstad et al, 2010, PLoS Medicine)

`hong({mouth:"0_neutral", eyes:"0_annoyed"})`

h: Euh.. merci d'avoir cité ton sources mais--

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({body:"fear", mouth:"normal", eyes:"fear"})`

b: Ce qui veut dire que si on ne trouve pas d'a *tout de suite* on va-

`bb({body:"panic"})`

b: MOURIIIIIIIIIIIIIR

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("20p", "alone");
publish("hp_show");
```

(...2500)
