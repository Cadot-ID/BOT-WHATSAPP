<p align="center">
  <img src="https://i.ibb.co/Nnd582M/images-2-picsay.jpg" width=500/>
</p>

<div align="center"><h3>Simple Whatsapp Bot Made <br>With <a href="https://github.com/adiwajshing/Baileys">Baileys</a></h3></div> 

### Install di Termux
````
pkg install nodejs git tesseract libwebp wget imagemagick ffmpeg
git clone https://github.com/salismazaya/whatsapp-bot
wget https://raw.githubusercontent.com/tesseract-ocr/tessdata_best/master/ind.traineddata
mv ind.traineddata /data/data/com.termux/files/usr/share/tessdata 
cd whatsapp-bot
npm install
node index.js
````

### Install di Linux (ubuntu & debian)
```
sudo apt install npm git webp imagemagick ffmpeg
sudo apt install tesseract-ocr tesseract-ocr-ind
sudo npm install -g n
sudo n stable
git clone https://github.com/salismazaya/whatsapp-bot
cd whatsapp-bot
npm install
node index.js
```

### fitur
```
*GROUP ONLY*
*1.* !group _open|close_
*2.* !antilink _on|off_
*3.* !antitagall _on|off_
*4.* !antiviewonce _on|off_
*5.* !welcome _on|off_
*6.* !leave _on|off_
*7.* !setgroupicon _replyImage_
*8.* !setgroupname _text_
*9.* !setgroupdesc _text_
*10.* !hidetag _text_
*11.* !promote _@tag_
*12.* !demote _@tag_
*13.* !kick _@tag_
*14.* !add _number_
*15.* !getpp _@tag_
*16.* !tagall
*17.* !linkgroup
*18.* !revoke
*19.* !leave

*DOWNLOADER*
*20.* !play _query_
*21.* !playvid _query_
*22.* !youtubedl _query_
*23.* !ytmp3 _link_
*24.* !ytmp4 _link_
*25.* !igstory _username_
*26.* !ig _link_
*27.* !joox _song_

*STICKER*
*28.* !stickerwm _pack|author_
*29.* !takestick _pack|author_
*30.* !toimg _replySticker_
*31.* !togif _replySticker_
*32.* !semoji _emoji_
*33.* !stickerfire
*34.* !stickernobg
*35.* !stickergif
*36.* !sticker

*ANIME*
*37.* !anime _query_
*38.* !manga _query_
*39.* !chara _query_
*40.* !waifu

*EDUCATION*
*41.* !nulis _text_
*42.* !brainly _query_
*43.* !kbbi _query_
*44.* !wiki _query_

*SEARCHING*
*45.* !playstore _apk_
*46.* !happymod _apk_
*47.* !iguser _username_
*48.* !igstalk _username_
*49.* !ytsearch _query_
*50.* !ytplaylist _query_
*51.* !ytchannel _channel_
*52.* !shoope _product_
*53.* !spotify _song_
*54.* !gsmarena _hp_
*55.* !searchmusic _replyAudio_
*56.* !wallpaper _query_
*57.* !pinterest _query_
*58.* !googleimage _query_
*59.* !jagokata _kata_

*PRIMBON*
*60.* !jodoh _kamu|dia_
*61.* !artinama _nama_
*62.* !artimimpi _mimpi_

*RANDOM*
*63.* !fml
*64.* !randomquran
*65.* !meme
*66.* !darkjoke
*67.* !pantun
*68.* !nickepep
*69.* !quotes
*70.* !estetikpic

*TEXTMAKER*
*71.* !wolflogo _text1|text2_
*72.* !logoaveng _text1|text2_
*73.* !phlogo _text1|text2_
*74.* !marvellogo _text1|text2_
*75.* !gtext _text1|text2_
*76.* !pubglogo _text1|text2_
*77.* !snowwrite _text1|text2_
*78.* !watercolour _text1|text2_
*79.* !harta _text_
*80.* !thundertext _text_
*81.* !flametext _text_
*82.* !glowtext _text_
*83.* !smoketext _text_
*84.* !lithgtext _text_
*85.* !flowertext _text_
*86.* !bneon _text_
*87.* !matrix _text_
*88.* !breakwall _text_
*89.* !gneon _text_
*90.* !dropwater _text_
*91.* !tfire _text_
*92.* !sandw _text_
*93.* !epep _text_
*94.* !gplaybutton _text_
*95.* !splaybutton _text_
*96.* !text3dbox _text_
*97.* !text3d _text_
*98.* !logobp _text_
*99.* !leavest _text_
*100.* !tlight _text_
*101.* !naruto _text_
*102.* !crosslogo _text_
*103.* !cslogo _text_
*104.* !crismes _text_

*IMAGEMAKER*
*105.* !missing _text1|text2|text3|@tag_
*106.* !calender _replyImage / @tag_
*107.* !drawing _replyImage / @tag_
*108.* !sketch _replyImage / @tag_

*OTHER*
*109.* !tomp3 _replyVideo_
*110.* !removebg _replyImage / @tag_
*111.* !tts _code|text_
*112.* !qrencode _text_
*113.* !barcode _text_
*114.* !jadwalsholat _daerah_
*115.* !jadwaltv _channel_
*116.* !tebakgambar

*INFO*
*117.* !stickermenu
*118.* !owner
*119.* !limit
*120.* !info
*121.* !listvn

*OWNER*
*122.* !setpp _replyImage_
*123.* !eval _text_
*124.* !term _code_
*125.* !block _@tag_
*126.* !unblock _@tag_
*127.* !join _link_
*128.* !bc _text_
*129.* !addvn _replyAudio/vn_
*130.* !delvn _name_
*131.* !premium add _@tag_
*132.* !premium del _@tag_
*133.* !premium list
*134.* !clearall
*135.* !resetlimit
*136.* !self
*137.* !public
