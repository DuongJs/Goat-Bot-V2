<h1 align="center"><img src="./dashboard/images/logo-non-bg.png" width="22px"> Goat Bot - Bot Chat Messenger</h1>

<p align="center">
	<a href="https://nodejs.org/en/download/">
		<img src="https://img.shields.io/badge/Nodejs%20Support-16.x-brightgreen.svg?style=flat-square" alt="Nodejs Support v16.x">
	</a>
  <img alt="size" src="https://img.shields.io/github/repo-size/ntkhang03/Goat-Bot-V2.svg?style=flat-square&label=size">
  <img alt="code-version" src="https://img.shields.io/badge/dynamic/json?color=red&label=code%20version&prefix=v&query=%24.version&url=https://github.com/ntkhang03/Goat-Bot-V2/raw/main/package.json&style=flat-square">
  <img alt="visitors" src="https://visitor-badge.laobi.icu/badge?style=flat-square&page_id=ntkhang3.Goat-Bot-V2">
  <img alt="size" src="https://img.shields.io/badge/license-MIT-green?style=flat-square">
</p>

* [`Prerequisites`](#-prerequisites)
* [`Tutorial`](#-tutorial)
* [`Support`](#-support)
* [`Support Languages`](#-support-languages)
* [`Common Problems`](#-common-problems)
* [`Screenshots`](#-screenshots)
* [`Note`](#-note)
* [`Copyright (C)`](#-copyright-c)
* [`License`](#-license)

## 🚧 Prerequisites
- [Node.js 16.x](https://nodejs.org/en/download/)

## 📝 Tutorial
#### A Tutorial has been uploaded on YouTube, Watch it by clicking on the image down below
- Replit.com: https://www.youtube.com/watch?v=nTIT8OQeRnY
- VPS/Windows:

## 📙 Support
#### If you have major coding issues with this bot, please join and ask for help.
- https://www.facebook.com/groups/goatbot
- https://www.facebook.com/groups/goatbot/permalink/493150412403231
- https://m.me/j/AbYrIGusyc0M402z
- https://discord.com/invite/DbyGwmkpVY
- ***Please do not inbox me, I do not respond to private messages, any questions please join the chat group for answers. ThankThanks!***

## 📚 Support Languages

- [x] `en: English`
- [x] `vi: Vietnamese`

- Change language in `config.json` file
- You can customize the language in the folder `languages/`, `languages/cmds/` and `languages/events/`

## 📌 Common Problems
<details>
	<summary>
		📌 Error 400: redirect_uri_mismatch
	</summary>
	<p><img src="https://i.ibb.co/4TG5Wry/redirect-uri-mismatch.jpg" width="150px"></p> 
	<p>1. Enable Google Drive API: <a href="https://youtu.be/nTIT8OQeRnY?t=347">Tutorial</a></p>
	<p>2. Add uri <a href="https://developers.google.com/oauthplayground">https://developers.google.com/oauthplayground</a> (not <a href="https://developers.google.com/oauthplayground/">https://developers.google.com/oauthplayground/</a>) to <b>Authorized redirect URIs</b> in <b>OAuth consent screen</b> <a href="https://youtu.be/nTIT8OQeRnY?t=491">Tutorial</a></p>  
	<p>3. Choose <b>https://www.googleapis.com/auth/drive</b> and <b>https://mail.google.com/</b> in <b>OAuth 2.0 Playground</b>: <a href="https://youtu.be/nTIT8OQeRnY?t=600">Tutorial</a></p>
</details>

<details>
	<summary>
		📌 Error for site owners: Invalid domain for site key
	</summary>
		<p><img src="https://i.ibb.co/BVwcxpF/invalid-domain-for-site-key.jpg" width="150px"></p>
		<p>1. Go to <a href="https://www.google.com/recaptcha/admin">https://www.google.com/recaptcha/admin</a></p>
		<p>2. Add domain <b>repl.co</b> (not <b>repl.com</b>) to <b>Domains</b> in <b>reCAPTCHA v2</b> <a href="https://youtu.be/nTIT8OQeRnY?t=698">Tutorial</a></p>
</details>

<details>
	<summary>
		📌 GaxiosError: invalid_grant, unauthorized_client
	</summary>
		<p><img src="https://i.ibb.co/DLJpsz8/invalid-grant2.jpg" width="150px"></p>
		<p><img src="https://i.ibb.co/LtHhM0L/Pics-Art-11-09-06-00-08.jpg" width="150px"></p>
		<p><img src="https://i.ibb.co/V2H8tdB/invalid-grant1.jpg" width="150px"></p>
		<p>- if you don't publish the project in google console, the refresh token will expire after 1 week and you need to get it back. <a href="https://youtu.be/nTIT8OQeRnY?t=445">Tuatorial</a></p>
</details>


## 📸 Screenshots
- ### Bot
<details>
	<summary>
 		Rank system
	</summary>

  - Rank card:
  <p><img src="https://i.ibb.co/d0JDJxF/rank.png" width="399px"></p>

  - Rankup notification:
  <p><img src="https://i.ibb.co/WgZzthH/rankup.png" width="399px"></p>

  - Custom rank card:
  <p><img src="https://i.ibb.co/hLTThLW/customrankcard.png" width="399px"></p>
</details>

<details>
	<summary>
 		Weather:
	</summary>
	<p><img src="https://i.ibb.co/2FwWVLv/weather.png" width="399px"></p>
</details>

<details>
	<summary>
 		Auto send notification when have user join or leave box chat (you can custom message):
	</summary>
	<p><img src="https://i.ibb.co/Jsb5Jxf/wcgb.png" width="399px"></p>
</details>



- ### Dashboard
<details>
	<summary>
 		Home:
	</summary>
	<p><img src="https://i.ibb.co/xzv6s2j/dbHome.png" width="399px"></p>
</details>

<details>
	<summary>
 		Stats:
	</summary>
	<p><img src="https://i.ibb.co/zVZv9LF/dbStats.png" width="399px"></p>
</details>

<details>
	<summary>
 		Login/Register:
	</summary>
	<p><img src="https://i.ibb.co/SK61MRx/dbLogin.png" width="399px"></p>
	<p><img src="https://i.ibb.co/1rchbb1/db-Register.png" width="399px"></p>
</details>

<details>
	<summary>
 		Dashboard Thread:
	</summary>
	<p><img src="https://i.ibb.co/NK5yYwx/dbThread.png" width="399px"></p>
</details>

<details>
	<summary>
 		Custom on/off:
	</summary>
	<p><img src="https://i.ibb.co/mJqsP2L/dbCustom.png" width="399px"></p>
</details>

<details>
	<summary>
 		Custom welcome message (similar with leave, rankup (coming soon), custom command (coming soon))
	</summary>
	<p><img src="https://i.ibb.co/3SyfQkz/db-Custom-Welcome.png" width="399px"></p>
</details>


## 📝 Note
- This is a messenger chat bot using a personal account, using an unofficial api and this may lead to facebook account being locked due to spam or other reasons. I am not responsible for any problems that may arise from using this bot.

## ✨ Copyright (C)
### [NTKhang (NTKhang03)](https://github.com/ntkhang03)

## 📜 License
### If you violate any rules, you will be banned from using my project
- Don't sell my source code
- Don't remove/edit my credits
