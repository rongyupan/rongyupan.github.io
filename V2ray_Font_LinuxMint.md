# v2ray and font setting on Linux-mint

## I. Set qv2ray

The v2ray service I use is from `just my socks`, where 3 of the 5 VPS have supported v2ray in recent months. The other 2 VPS still support Shadowsocks. 

V2ray is replacement of Shadowsocks for its security and speed. 

Qv2ray is a GUI program supporting windows, macos and linux. 

Although we can configure v2ray in Bash, which is complicated, I recommend to use qv2ray that can achieve same effect.

### Download v2ray-core

- From `https://github.com/v2fly/v2ray-core/releases` download `v2ray-linux-64.zip`. Place this *folder* into `/home/xxx/.config/qv2ray`

### Attention

Please remind the following two options:

**Set `Alter ID=0`**

**Do not Enable `TLS`**

If you use `just my socks` and can't succeed, you can check whether these two selections are right!

## II. Font Setting

### terminal & editor

For editors, I prefer "Monaco", which is the default font of MacOS terminal.

Besides "Monaco", I also recommend "Menlo" and "Lucida Grande" of MacOS.

Besides fonts from MacOS, popular fonts like "Consolas", "DejaSans"and "FiraCode" works well.

All fonts can be found in google.

### Font Setting 

I just change `Document font` and `Window title font`. 

Actually, you don't have to change `Window title font` for `Charcoal` doesn't make a deep difference.

```
"Default font": Ubuntu Regular

"Desktop font": Ubuntu Regular

"Document font": Monaco Regular

"Monospace font": Monospace Regular

"window title font": Charcoal Regular

```
