CSS Snippets for Discord. Tested on Vencord but I assume other CSS loaders work fine.

# Small fixes / Reverting "refreshed" look

## Bigger textbox buttons
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/bigger_textbox_buttons.css
```
Makes the buttons on the textbox as big as emojis so they don't look tiny with the "refreshed" taller textbox.

## Thicker scrollbars
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/thicker_scrollbars.css
```
Thickens the minuscule scrollbars on server channels, recent DMs, and search panels.

## Thinner channel/recent DMs panel (no longer needed)
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/thinner_channel_panel.css
```
Reverts the new UI width on the channel list panel.

## Typing above textbox (no longer needed, default behavior since 2025-09-10, finally a good UI update)
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/move_typing_above_chatbox.css
```
Moves the "X is typing" above chatbox so chatbox is aligned with user info.  
Warning: If there's more than one line of text typed in the textbox the "Typing..." element goes through the textbox since its position is fixed. Nothing I can do without JS.

## Transparent "Create DM" button (no longer needed, button is gone)
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/thinner_channel_panel.css
```
Makes the "Create DM" button transparent so it doesn't stand out like a sore thumb.

# No more upselling/ads

## Hide store and nitro tabs
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/hide_store_nitro_tabs.css
```
Gives more space to the recent DMs page by hiding the Nitro and Store entries. Also conveniently hides the "New!" store ad nagging.

## Hide gift and app launcher icons from textbox
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/hide_useless_textbox_icons.css
```
Hides app launcher and gift icons from the message textbox.

## Hide "Set DM wallpaper"
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/hide_set_dm_wallpaper_context_item.css
```
Hides "Set DM Wallpaper" context menu item when right clicking a user in the DMs tab.

## Hide rewards popup
```
https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/hide_rewards_popup.css
```
Hides those stupid game ads.