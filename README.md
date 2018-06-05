# steam-account-generator

## Step 1: installing dependencies and requirements
You must have node.js 8 or above


You must have npm 5.6.0 or above


You must have pm2 (`npm i -g pm2`)

pip install requests  

Just type `npm i`, the package.json already has all of the deps.

## Step 2: anti-captcha
Get an account for anti-captcha.com and deposit some funds, 


please save the api key as you will need it for later.

## Step 3: Config

Assuming you have created an account and deposited some money in anti-captcha.com get your api key and place it in the config.json file

you can do stuff in index with proxies idk

### variables:


prof_image - url to desired profile image (must be a direct link).


summary - profile summary/description.


username - profile username.


country - country that will show up on your profile, use KP for north korea.


prof_privacy - privacy stuff, 3 = public, 2 = friends only, 1 = private.


## Step 4: Run
`sudo pm2 start index.js` and do `sudo pm2 logs` to see the logs


accounts will be in accounts.cg.json


just delete it if you want a new empty accounts.cg.json (perhaps your accounts got banned or whatever idk)


# Yeah that's basically it. Contact me on @martsklava on telegram if you want any further assistance. Generate away.


# Please contact me there for issues or use the issue tracker with logs, issues help me make the generator more stable.
