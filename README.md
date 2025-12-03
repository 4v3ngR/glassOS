# glassOS
A collection of themes and styles for KDE for a glassOS look

## Better blur
This collection can work with any of the better blur forks. The switcher only edits brightness, contrast, and saturation when switching between dark and light modes.

## Glass
This collection can work with any colorscheme that provides transparency. For best results, using the [my fork](https://github.com/4v3ngR/Glass) of Darkly application style is recommended.

## The switcher script
The switcher script (switcher/theme) now has four options:
- dark
- light
- dark-glass
- light-glass

The script updates:
- global theme
- plasma theme
- better blur settings (brightness, contrast, saturation, blur level)
- default konsole profile (dark or light)

### The switch script auto mode
Not only does the switch script allow for changing of themes, blur settings, and konsole profiles, it can do it automatically based on time.

```sh
theme auto
```

This can be run as a cron job to fully automate the change

```
* * * * * /usr/local/bin/theme auto
```

![Dark Glass](/images/dark.png)
![Light Glass](/images/light.png)
![Dark](/images/dark-opaque.png)
![Light](/images/light-opaque.png)
