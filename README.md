# AI chat application

A UI wrapper for an OpenAI chat completions API 

## Motivation ✨

+ Paid ChatGPT subscription isn't be the best option for users that only use AI occasionally, but still sometimes need to work with powerful models like GPT-4.
+ The project was created to utilize **pay as you go** model of OpenAI's API **instead of monthly subscriptions** while preserving ChatGPT-like user experience.
+ Also I wanted to add some additional features, which I miss in ChatGPT

## Demo 📺
<div align="center">
    <img src="https://dl.dropboxusercontent.com/scl/fi/etrx3xy1byv3uvsosp2bd/Overall_demo.gif?rlkey=54rsdc52roj94un0dpprr1h8z&st=mv3ncq75&dl=1" style="width:450px;" />
</div>

<h2 title="*In comparison with ChatGPT">Unique features* ⭐️</h2>

#### Prompts library 📚
+ Your **system prompts** (custom rules and instructions for an assistant) are saved and can be re-used

<div align="center">
<img src="https://dl.dropboxusercontent.com/scl/fi/n0w81ax3a7lk9a23m5my0/Prompts_library_demo.gif?rlkey=we14ghubm18x85zcnchnfoety&st=x6mc0ddk&dl=1" style="width:450px;" />
</div>

#### Parallel message generation ✉️
+ This app allows simultaneous message generation in different chats

<div align="center">
<img src="https://dl.dropboxusercontent.com/scl/fi/a48ahtl285ds2st3huyta/Parallel_generation_demo.gif?rlkey=rd6979330uvp74tlgbyoj7o4r&st=gsjt6yir&dl=1" style="width:450px;" />
</div>

#### Pay per token with your own API key 🔑
+ You have full control of how much you spend, because you pay per token (input and output). You can check out pricing [on this page](https://openai.com/pricing)
+ Users are able to save their API keys to personal account on this app for convenience
+ Alternatively, if you are worried about security, you have an option to not save the key.

#### Chat specific system prompts 💬
+ You can configure system prompts for each chat separately, not just globally

## Features to be implemented 📌

#### Assistants API 🤖
Assistants API is more convenient for a developer than a completions API.
These changes will not probably affect end-users, because full implementation (assistants creation and configuration) is not
currently in near future plans. 

#### Work with images 🖼️
Image analysis DALLE-3 integration

#### Theming 🌓

Currently only dark theme is supported

## Technology stack 🛠️

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) ![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)

## How to Use? 🚀

Application is available online at [chat.krglkvrmn.me](https://chat.krglkvrmn.me) 🏳️‍🌈
For a local development check out separate instructions for [frontend](https://github.com/krglkvrmn/openai_api_ui_frontend) and [backend](https://github.com/krglkvrmn/openai_api_ui_backend)

In order to use it, you should [acquire an OpenAI API key](https://platform.openai.com/api-keys) 🔑 and add [credits to balance of your OpenAI account](https://platform.openai.com/settings/organization/billing/overview) 💳

## Browser support 🌐

The app was tested in most popular browsers including:

![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white) ![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white) ![Edge](https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white) ![Opera](https://img.shields.io/badge/Opera-FF1B2D?style=for-the-badge&logo=Opera&logoColor=white) ![Safari](https://img.shields.io/badge/Safari-000000?style=for-the-badge&logo=Safari&logoColor=white)

📱Mobile browsers are supported, but minor UI problems may occur

## License

This project is licensed under the terms of the MIT license.

## Contacts

If you have any questions, please contact @krglkvrmn - Telegram or kruglikov1911@mail.ru - Email


