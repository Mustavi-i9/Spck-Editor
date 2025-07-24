<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Get dynamically generated GitHub stats on your READMEs!</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img alt="Tests Coverage" src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://securityscorecards.dev/viewer/?uri=github.com/anuraghazra/github-readme-stats">
      <img alt="OpenSSF Scorecard" src="https://api.securityscorecards.dev/projects/github.com/anuraghazra/github-readme-stats/badge" />
    </a>
    <br />
    <br />
    <a href="https://vercel.com?utm\_source=github\_readme\_stats\_team\&utm\_campaign=oss">
      <img src="./powered-by-vercel.svg"/>
    </a>
  </p>

  <p align="center">
    <a href="#all-demos">View Demo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new?assignees=&labels=bug&projects=&template=bug_report.yml">Report Bug</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml">Request Feature</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/discussions/1770">FAQ</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/discussions/new?category=q-a">Ask Question</a>
  </p>
  
<p align="center">Please note that documentation translations may be outdated; try to use English documentation if possible.</p>

<p align="center">Love the project? Please consider <a href="https://www.paypal.me/anuraghazra">donating</a> to help it improve!</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://cfstatic.give.do/logo.png" alt="Give india logo" width="200" />
</a>

Are you considering supporting the project by donating to me? Please DO NOT!!!

<img src="https://cfstatic.give.do/910ede2a-7892-43fe-8c8a-dea45e96d950.webp" alt="Picture of Coromandel Express train tragedy" width="35%">

India has recently suffered one of the most devastating train accidents, and your help will be immensely valuable for the people who were affected by this tragedy.

Please visit [this link](https://give.do/fundraisers/stand-beside-the-victims-of-the-coromandel-express-train-tragedy-in-odisha-donate-now) and make a small donation to help the people in need. A small donation goes a long way. :heart:

</p>

# Features <!-- omit in toc -->

- [GitHub Stats Card](#github-stats-card)
- [WakaTime Stats Card](#wakatime-stats-card)
    - [Demo](#demo-3)
- [All Demos](#all-demos)
  - [Quick Tip (Align The Cards)](#quick-tip-align-the-cards)
- [Deploy on your own](#deploy-on-your-own)
  - [On Vercel](#on-vercel)
    - [:film\_projector: Check Out Step By Step Video Tutorial By @codeSTACKr](#film_projector-check-out-step-by-step-video-tutorial-by-codestackr)
  - [On other platforms](#on-other-platforms)
  - [Disable rate limit protections](#disable-rate-limit-protections)
  - [Keep your fork up to date](#keep-your-fork-up-to-date)
- [:sparkling\_heart: Support the project](#sparkling_heart-support-the-project)

# Important Notices <!-- omit in toc -->


<img alt="Uptime Badge" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fgithub-readme-stats-git-monitoring-github-readme-stats-team.vercel.app%2Fapi%2Fstatus%2Fup%3Ftype%3Dshields">







### Themes

With inbuilt themes, you can customize the look of the card without doing any [manual customization](#customization).

Use `&theme=THEME_NAME` parameter like so :

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### All inbuilt themes

GitHub Readme Stats comes with several built-in themes (e.g. `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `dracula`).

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stats Themes" width="600px"/>

You can look at a preview for [all available themes](themes/README.md) or checkout the [theme config file](themes/index.js). Please note that we paused the addition of new themes to decrease maintenance efforts; all pull requests related to new themes will be closed.

#### Responsive Card Theme

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra\&show_icons=true\&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#responsive-card-theme#gh-dark-mode-only)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra\&show_icons=true\&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#responsive-card-theme#gh-light-mode-only)

Since GitHub will re-upload the cards and serve them from their [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), we can not infer the browser/GitHub theme on the server side. There are, however, four methods you can use to create dynamics themes on the client side.

##### Use the transparent theme

We have included a `transparent` theme that has a transparent background. This theme is optimized to look good on GitHub's dark and light default themes. You can enable this theme using the `&theme=transparent` parameter like so:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)
```

<details>
<summary>:eyes: Show example</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra\&show_icons=true\&theme=transparent)

</details>

##### Add transparent alpha channel to a themes bg\_color

You can use the `bg_color` parameter to make any of [the available themes](themes/README.md) transparent. This is done by setting the `bg_color` to a color with a transparent alpha channel (i.e. `bg_color=00000000`):

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)
```

<details>
<summary>:eyes: Show example</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra\&show_icons=true\&bg_color=00000000)

</details>

##### Use GitHub's theme context tag

You can use [GitHub's theme context](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) tags to switch the theme based on the user GitHub theme automatically. This is done by appending `#gh-dark-mode-only` or `#gh-light-mode-only` to the end of an image URL. This tag will define whether the image specified in the markdown is only shown to viewers using a light or a dark GitHub theme:

```md
[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)
```

<details>
<summary>:eyes: Show example</summary>

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra\&show_icons=true\&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra\&show_icons=true\&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Use GitHub's new media feature

You can use [GitHub's new media feature](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) in HTML to specify whether to display images for light or dark themes. This is done using the HTML `<picture>` element in combination with the `prefers-color-scheme` media feature.

```html
<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true" />
</picture>
```

<details>
<summary>:eyes: Show example</summary>

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true" />
</picture>

</details>


#### Common Options

| Name | Description | Type | Default value |
| --- | --- | --- | --- |
| `title_color` | Card's title color. | string (hex color) | `2f80ed` |
| `text_color` | Body text color. | string (hex color) | `434d58` |
| `icon_color` | Icons color if available. | string (hex color) | `4c71f2` |
| `border_color` | Card's border color. Does not apply when `hide_border` is enabled. | string (hex color) | `e4e2e2` |
| `bg_color` | Card's background color. | string (hex color or a gradient in the form of *angle,start,end*) | `fffefe` |
| `hide_border` | Hides the card's border. | boolean | `false` |
| `theme` | Name of the theme, choose from [all available themes](themes/README.md). | enum | `default` |
| `cache_seconds` | Sets the cache header manually (min: 21600, max: 86400). | integer | `21600` |
| `locale` | Sets the language in the card, you can check full list of available locales [here](#available-locales). | enum | `en` |
| `border_radius` | Corner rounding on the card. | number | `4.5` |


##### Gradient

You can provide multiple comma-separated values in the bg\_color option to render a gradient with the following format:

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

##### Available locales

Here is a list of all available locales:

<table>
<tr><td>

| Code | Locale |
| --- | --- |
| `cn` | Chinese |
| `zh-tw` | Chinese (Taiwan) |
| `ar` | Arabic |
| `cs` | Czech |
| `de` | German |
| `en` | English |
| `bn` | Bengali |
| `es` | Spanish |
| `fr` | French |
| `hu` | Hungarian |

</td><td>

| Code | Locale |
| --- | --- |
| `it` | Italian |
| `ja` | Japanese |
| `kr` | Korean |
| `nl` | Dutch |
| `pt-pt` | Portuguese (Portugal) |
| `pt-br` | Portuguese (Brazil) |
| `np` | Nepali |
| `el` | Greek |
| `ru` | Russian |
| `uk-ua` | Ukrainian |

</td><td>

| Code | Locale |
| --- | --- |
| `id` | Indonesian |
| `ml` | Malayalam |
| `my` | Burmese |
| `sk` | Slovak |
| `tr` | Turkish |
| `pl` | Polish |
| `uz` | Uzbek |
| `vi` | Vietnamese |
| `se` | Swedish |

</td></tr>
</table>

If we don't support your language, please consider contributing! You can find more information about how to do it in our [contributing guidelines](CONTRIBUTING.md#translations-contribution).



#### Repo Card Exclusive Options

| Name | Description | Type | Default value |
| --- | --- | --- | --- |
| `show_owner` | Shows the repo's owner name. | boolean | `false` |
| `description_lines_count` | Manually set the number of lines for the description. Specified value will be clamped between 1 and 3. If this parameter is not specified, the number of lines will be automatically adjusted according to the actual length of the description. | number | `null` |

#### Gist Card Exclusive Options

| Name | Description | Type | Default value |
| --- | --- | --- | --- |
| `show_owner` | Shows the gist's owner name. | boolean | `false` |

#### Language Card Exclusive Options

| Name | Description | Type | Default value |
| --- | --- | --- | --- |
| `hide` | Hides the [specified languages](#hide-individual-languages) from card. | string (comma-separated values) | `null` |
| `hide_title` | Hides the title of your card. | boolean | `false` |
| `layout` | Switches between five available layouts `normal` & `compact` & `donut` & `donut-vertical` & `pie`. | enum | `normal` |
| `card_width` | Sets the card's width manually. | number | `300` |
| `langs_count` | Shows more languages on the card, between 1-20. | integer | `5` for `normal` and `donut`, `6` for other layouts |
| `exclude_repo` | Excludes specified repositories. | string (comma-separated values) | `null` |
| `custom_title` | Sets a custom title for the card. | string | `Most Used Languages` |
| `disable_animations` | Disables all animations in the card. | boolean | `false` |
| `hide_progress` | Uses the compact layout option, hides percentages, and removes the bars. | boolean | `false` |
| `size_weight` | Configures language stats algorithm (see [Language stats algorithm](#language-stats-algorithm)). | integer | `1` |
| `count_weight` | Configures language stats algorithm (see [Language stats algorithm](#language-stats-algorithm)). | integer | `0` |


#### WakaTime Card Exclusive Options

| Name | Description | Type | Default value |
| --- | --- | --- | --- |
| `hide` | Hides the languages specified from the card. | string (comma-separated values) | `null` |
| `hide_title` | Hides the title of your card. | boolean | `false` |
| `line_height` | Sets the line height between text. | integer | `25` |
| `hide_progress` | Hides the progress bar and percentage. | boolean | `false` |
| `custom_title` | Sets a custom title for the card. | string | `WakaTime Stats` |
| `layout` | Switches between two available layouts `default` & `compact`. | enum | `default` |
| `langs_count` | Limits the number of languages on the card, defaults to all reported languages. | integer | `null` |
| `api_domain` | Sets a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/mujx/hakatime) or [Wakapi](https://github.com/muety/wakapi) | string | `wakatime.com` |
| `display_format` | Sets the WakaTime stats display format. Choose `time` to display time-based stats or `percent` to show percentages. | enum | `time` |
| `disable_animations` | Disables all animations in the card. | boolean | `false` |

***



# Top Languages

The top languages card shows a GitHub user's most frequently used languages.

> [!NOTE]\
> Top Languages does not indicate the user's skill level or anything like that; it's a GitHub metric to determine which languages have the most code on GitHub. It is a new feature of github-readme-stats.



### Thank you
> [!Warning]\
> thank you 💖

> I am a `Software Engineer =` at `Google`  [WakaTime](https://wakatime.com) username.

```md
Mustavi
```

### Usage

You can use the `&layout=donut` option to change the card design.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=donut)](https://github.com/anuraghazra/github-readme-stats)
```


> [!WARNING]\
> you should [deploy your own instance](#deploy-on-your-own) using your own **GitHub** API token.

> [!NOTE]\
> The global percentile is based on the cumulative distribution function of the [exponential](https://wikipedia.org/wiki/exponential_distribution)

> [!IMPORTANT]\
> Tata everyone


> [!WARNING]\
> We use caching to decrease the load on our servers (see <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Our cards have a default cache of 6 hours (21600 seconds). Also, note that the cache is clamped to a minimum of 6 hours and a maximum of 24 hours. If you want the data on your statistics card to be updated more often you can [deploy your own instance](#deploy-on-your-own) and set [environment variable](#disable-rate-limit-protections) `CACHE_SECONDS` to a value of your choosing.

