# NonSteamEasyShortcut

How steam works on a steamdeck

1. It stores profile and user information in ~/.steam/steam/config/loginusers.vdf (Not Binary)
   - Note: This contains all the user information and the STEAMID_32BIT per user
3. It stores Non-Steam shortcuts information in ~~/.steam/steam/userdata/(STEAMID_32BIT)/config/shortcuts.vdf
   - Note: At first steam doesnt create that file until a shortcut have been created in steam.
   - Note: [AppID32-bit] is in here
4. It stores custom images in ~/.steam/steam/userdata/(STEAMID_32BIT)/config/grid/
  - Covers are stored as [AppID32-bit]p.jpg
  - Wide covers are stored as [AppID32-bit].jpg
  - Logos are stored as [AppID32-bit]_logo.jpg
  - Backgrounds are stored as [AppID32-bit]_hero.jpg
  - Note: the grids directory when never created doesnt exist
  - Note: It doesnt remove the old images
