# Translations
The base language is English and can be found [here](text-en.yaml).

## How language works in MemeNgin
- If a translation file exists, then MemeNgin parses it and uses it as the current language.
- If there is no available translation, MemeNgin uses English as fallback.

## Editing existing translations
If you want to edit an existing translation (Fixing typos, updating it to a newer version, etc), you can just use the github file editor to edit the file.

-   Click the language you want to edit from the list above
-   Click the small "edit" symbol on the top right

<img src="https://i.imgur.com/gZnUQoe.png" alt="edit symbol" width="200">

-   Do the changes you wish to do (Be sure **not** to translate placeholders! For example, `time: minutes` should get `time: 분` and **not** `시간: 분`!)

-   Click "Propose Changes"

<img src="https://i.imgur.com/zc0SPs3" alt="propose changes" width="200">

-   Click "Create pull request"

<img src="https://i.imgur.com/oVljvRE.png" alt="create pull request" width="200">

-   I will review your changes and make comments, and eventually merge them so they will be in the next release! Be sure to regulary check the created pull request for comments.

## Adding a new language
Please DM me on Discord. I'll make a language template for you.

Please use the following template:
Hey, could you add a new translation?

"es-419": {
  name: "Español",
  data: "assets/translations/text-es.yaml",
  code: "es",
  region: "es",
},

<h6> Referenced from tobspr/shapez.io </h6>