## Counter-Strike:Global-Offensive
###*Optimal Configuration*

##Recommended Launch Options

####Explanation

>**-novid** (removes the video that plays when cs:go is launched)

>**-threads 4** (runs cs:go on multiple cores - match number with physical cpu cores)

>**-tickrate 128** (sets the default tickrate of locally hosted servers)

>**-noaafonts** (improves fps slightly by avoiding the anti-aliasing of text)

>**-freq 144** (set this to your monitors maximum refresh rate for smoother and more responsive experience)

>**-nojoy** (avoid the loading of modules related to joystick controls, as they are not needed)

>**-high** (sets the default process priority to high which can improve performance relative to other open applications)

>**+mat_vignette_enable 0** (removes the vignette from the top and bottom of the hud, which improves performance slightly)

####Copy/Paste Version

```
-novid -threads 4 -tickrate 128 -noaafonts -nojoy -high +mat_vignette_enable 0
```
