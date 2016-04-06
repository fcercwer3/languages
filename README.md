# Return To The Roots

Language files for s25client

## Updating po template (rttr.pot)

- Checkout current master branch
- Download and install poedit (https://poedit.net) >= 1.8.7
- Open `rttr.pot`
- Press "Update" or "Catalog"->"Update from sources"
- Save and commit
- Optional: Update po files of your language using poedit.
    - Open po file
    - Click "Catalog"->"Update from POT file" (`rttr.pot`)
    - Check and fix auto-translations
    - Remove unused translations (Validate, that they are actually unused)
    - Save and commit. (Note: Better do this after each step so changes are easier to see)
- Create a pull request with the change

## Updating/Changing po files (Translations)

1. Use poedit (https://poedit.net) to edit .po files and create a pull request
    - Checkout current master branch
    - Open po file of your language
    - Make any changes to the translations
    - Save and commit

2. Translate online via https://translations.launchpad.net/s25rttr (could take longer to get into release)   
You can drop us a hint on IRC if you did a larger translation.
