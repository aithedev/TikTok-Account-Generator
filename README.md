<h2 align="center">๐ฏ TikTok Account Generator</h2>
  <p align="center">This is a TikTok account generator in which it allows you to mass create TikTok accounts automatically. This generator uses TikTok's private mobile API and is fully requests based. This may be used for a variety of purposes, including marketing or botting purposes. 
    <br />
    This code is very rough and is in a testing phase. I probably won't continue working on this.
    <br />
    <br />
    <a href="https://github.com/aithedev/TikTok-Account-Generator/issues">Report Bug</a>
    ยท
    <a href="https://github.com/aithedev/TikTok-Account-Generator/issues">Request Feature</a>
    ยท
    <a href="https://github.com/aithedev/TikTok-Account-Generator/pulls">Contribute</a>
  </p>

### `โญ` Features
- Multi-threading
- HTTP/S Proxy support 
- Auto email verification using temp mail (lasagna.pro)
- Saves accounts to `./output/accounts.txt` (**Format** - device_id:install_id:mail:password:session_id)

### `โ๏ธ` Setup
- Star this project or else it wont work
- Enter your http/s proxies in `proxies.txt`
- Run the following command in CMD: `pip install requests pycrypto ptyz Terminalia`
- CD into the dir of the project and run `python3 main.py`

### `๐` To-Do
- Auto set avatar, nickname, username, & bio
- Make UI look nicer

### `๐ชฒ` Known bugs
- "Too many attempts" error after some accounts registered (**solution**: fix up the device generator)
- Sometimes outputs the same session id as well as the same did's & iid's 

### `๐บ` Demo
https://user-images.githubusercontent.com/105955582/216878344-c67cc4c8-a313-409a-91f7-5678f5e82eb5.mp4


## `๐งโ๐ป` Contact
- **Telegram**: t.me/aithedev
- **Discord**: ai#4444 (1078432806646054922)
