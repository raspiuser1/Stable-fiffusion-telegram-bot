# 4K Stable Diffusion telegram bot
Create a Stable Diffusion Telegram Bot which allows you to generate images in the bot via the API of the stable diffusion interface 
the resulution can be changed in HD or in 4K which uses the upscaler.

## Setup
- You need to install this repro: 
https://github.com/AUTOMATIC1111/stable-diffusion-webui 

- Enable the API by adding this line to your webui.bat file: 
<code>set COMMANDLINE_ARGS=--api --xformers --listen --enable-insecure-extension-access</code> 

- Replace 'http://192.168.1.90:7860' in the url variable in the code with the correct URL of your Stable Diffusion API endpoint.

- Get a key from the @botfather and put this in the key.txt file
run the script by <code>python3 run_main.py</code> 

## commands
- /get  and then put your search promt here 
- /cfg [number] the cfg you would set in the Gui standard its set to 14 
- /sr [number 1 or 2] change the resolution to 1920 x 1080 or to 4K 

## Video
https://youtu.be/uDzJ0iYHOqg <br />
[![IMAGE VIDEO](https://img.youtube.com/vi/uDzJ0iYHOqg/0.jpg)](https://www.youtube.com/watch?v=uDzJ0iYHOqg)<br />
