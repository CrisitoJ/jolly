### Jolly Hugo Theme
Honestly, this is a combination(free software,you now) of [Luke Smith](https://github.com/LukeSmithxyz/lugo/tree/master) ,[Eric Murphy](https://github.com/ericmurphyxyz/ericmurphy.xyz/tree/master) and [Holy](https://github.com/serkodev/holy/tree/master) themes.

![jolly](./photos/example.png)


### Features
-   0 dependencies, just html, css and hugo
-   categories section on main page
-   Custom presentation

```bash
git submodule add https://github.com/CrisitoJ/jolly themes/jolly

```

```bash
 #set up the theme adding this line on config.toml
 theme = "jolly"

```

Set your own presentation on config.toml
```bash
    #for each paragraph
    [[menu.pres]]
    name = "your presentation"
```
Add your personal photo or gif with
```bash
    [[params]]
    gif = "link"
```
