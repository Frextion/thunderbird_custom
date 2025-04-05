# thunderbird_custom
## What it's about
This repo contains a .css file which customizes the appearance of the email overview in Mozillas Thunderbird email client.
The specific changes of the styles are currently documented in the .css file itself.

## How to use
To apply the custom style sheet, you have to move the .css file into the active profile folder which is used by Thunderbird.
For windows users the path should be `"C:\Users\@usernameXXX\AppData\Roaming\Thunderbird\Profiles\profileFolderNameXXX\chrome\userChrome.css"`.

> [!important]
> The folder `/chrome` and its content `userChrome.css` have to exist with these specific names in order to be regocnized by Thunderbird.

Furthermore, the Thunderbird configuration / extended settings option `toolkit.legacyUserProfileCustomizations.stylesheets` has to be set to `true`.
