# StickerApp
StickerApp is an app that let you load sticker packs to WhatsApp.
http://play.google.com/store/apps/details?id=com.kanelai.stickerapp

Recipes (all without downloading separate apps for each sticker set):

## Recipe ONE: Export stickers packs from Telegram and import to WhatsApp
1. Go to Telegram and talk to the @ExportStickerPack bot (https://telegram.me/ExportStickerPackBot).
2. Send it any sticker from a Telegram sticker set.
3. It returns you a sticker pack file.
4. Open it with StickerApp.

## Recipe TWO: Create your own sticker packs using Telegram, and use them in both Telegram and WhatsApp
1. Go to Telegram and use the official @Stickers bot to create your own sticker set.
2. Follow Recipe ONE to have the stickers available in WhatsApp as well.

## Recipe THREE: Hand-make your own sticker pack files and import to WhatsApp
1. Create your own ".stickerpack" file
2. Open it with StickerApp




About Sticker Pack File
=======================

Sticker pack file is simply a zip file with one json and several sticker images in webp format.

It follows the WhatsApp official "assets" folder format.:
https://github.com/WhatsApp/stickers/tree/master/Android/app/src/main/assets

For an example, refer to [Animals.stickerpack](Animals.stickerpack). Just rename it to ".zip" and extract it.

Quick Notes:
- Due to restrictions of WhatsApp, each sticker pack must have 3-30 stickers.
- Due to restrictions of WhatsApp, the dimention of each sticker must be in webp format and in 512x512 pixels.
- Due to restrictions of WhatsApp, the dimention of the tray image must be in webp format and in 96x96 pixels.
- Each ".stickerpack" file can contain multiple sticker packs.
