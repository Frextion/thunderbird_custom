# thunderbird_custom
## What it's about
This repo contains a .css file which customized the appearance of the email overview in Mozillas Thunderbird.
The specific changes of the styles are currently documented in the .css file itself.

## How to use
To apply the custom style sheet, you have to move the .css file into the active profile folder which is used by Thunderbird.
For windows users the path should be `"C:\Users\@usernameXXX\AppData\Roaming\Thunderbird\Profiles\profileFolderNameXXX\chrome\userChrome.css"`.

Furthermore, the configuration / extended settings option `toolkit.legacyUserProfileCustomizations.stylesheets` has to be set to `true`.
