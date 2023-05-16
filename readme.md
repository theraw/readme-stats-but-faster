This will reset redis cached data once in 24h, first req in 24h may be bit slow rest after should be faster.
redis config can be set here : 

https://github.com/theraw/readme-stats-but-faster/blob/master/src/common/utils.js#L160


You can test it out from here : 
```md
https://github-stats.dopehosting.net/?username=theraw
```
if you change domain don't use `/api` anymore.

✅ => `https://github-stats.dopehosting.net`

❌ => `https://github-stats.dopehosting.net/api`



Not all are set to cache and run faster currently i'm using only the account stats and as for repo/top langs/wakatime i have not setup these to cache on redis yet.

```md
[![My GitHub stats](https://github-stats.dopehosting.net?username=theraw)](https://github.com/theraw/readme-stats-but-faster)
```


### Adding private contributions count to total commits count

 Options: `&count_private=true`

```md
![GitHub stats](https://github-stats.dopehosting.net?username=theraw&count_private=true)
```
![GitHub stats](https://github-stats.dopehosting.net?username=theraw&count_private=true)
### Showing icons

To enable icons, you can pass `&show_icons=true` in the query param, like so:

```md
![GitHub stats](https://github-stats.dopehosting.net?username=theraw&show_icons=true)
```
![GitHub stats](https://github-stats.dopehosting.net?username=theraw&show_icons=true)
### Themes

Use `&theme=THEME_NAME` parameter like so :

```md
![GitHub stats](https://github-stats.dopehosting.net?username=theraw&show_icons=true&theme=radical)
```

#### All inbuilt themes

(e.g. `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `dracula`).

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stats Themes" width="600px"/>

#### Dark/Light Themes
```js
![GitHub stats-Dark](https://github-stats.dopehosting.net?username=theraw&show_icons=true&theme=dark)
![GitHub stats-Light](https://github-stats.dopehosting.net?username=theraw&show_icons=true&theme=default)
```
![GitHub stats-Dark](https://github-stats.dopehosting.net?username=theraw&show_icons=true&theme=dark)
![GitHub stats-Light](https://github-stats.dopehosting.net?username=theraw&show_icons=true&theme=default)

##### Transparent theme

We have included a `transparent` theme that has a transparent background. This theme is optimized to look good on GitHub's dark and light default themes. You can enable this theme using the `&theme=transparent` parameter like so:

```md
![GitHub stats](https://github-stats.dopehosting.net?username=theraw&show_icons=true&theme=transparent)
```
<details>
<summary>:eyes: Show example</summary>

![GitHub stats](https://github-stats.dopehosting.net?username=theraw&show_icons=true&theme=transparent)
</details>

##### Add transparent alpha channel to a themes bg_color

You can use the `bg_color` parameter to make any of the available themes transparent. This is done by setting the `bg_color` to a color with a transparent alpha channel (i.e. `bg_color=00000000`):

```md
![GitHub stats](https://github-stats.dopehosting.net?username=theraw&show_icons=true&bg_color=00000000)
```

<details>
<summary>:eyes: Show example</summary>

![GitHub stats](https://github-stats.dopehosting.net?username=theraw&show_icons=true&bg_color=00000000)

</details>

##### Continue reading details
You can follow forked from repo and read full details/options for github stats cards as this is simply a faster option doesn't change anything else.
