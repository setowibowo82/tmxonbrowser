# TMXONBROWSER
Run Termux on your Browser (Likes a Remote Virtual Desktop on your Mozzila or Chrome)

#ON YOUR ANDROID PHONE
1. Install Termux
```
    https://play.google.com/store/apps/details?id=com.termux
```
2. Install NGROK on Termux
```
    * Sign In on site
    * Download NGROK from https://ngrok.com/download
    * unzip /path/to/ngrok.zip 
    * connect your account : ./ngrok authtoken <your_auth_token>
```
3. Install TTYD on Termux
```
    $ apt get install ttyd
    $ ttyd -p 8080 bash
```
4. Run NGROK on Termux (>>>Important<<<: "Enable your Hotspot first") 
```
    $ ./ngrok http 8080
```
5. Copy your link Termux and paste on your Browser
```
    https://*********.ngrok.io/
```
#ON YOUR BROWSER
```
     Paste link https://*********.ngrok.io/
```
![](https://github.com/setowibowo82/temuxonbrowser/blob/main/SC.jpg)
