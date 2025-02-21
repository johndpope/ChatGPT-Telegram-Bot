# ChatGPT Telegram Bot

Now use ChatGPT in Telegram!

<br>

### Install

1. Clone git repo.
2. Run ```npm i``` in project folder. This will install the required dependencies.
3. Populate .env file with bot token, bot dev ID, & OpenAI login credentials.

#### Bot token can be obtained from @BotFather.

#### Bot dev ID refers to the user ID of your Telegram account. This is needed to ensure there is no unauthorized access.

#### It is advisable to use Google credentials for login to ChatGPT. using OpenAI login invokes a captcha which the captcha bypasser is not always able to get through. Google login eliminates this issue.

4. Rename example.env to .env.

5. Run ```node bot``` to start the bot.

#### It's advisable to run the bot using PM2 or any startup manager for persistent execution, as this ensures you won't have to have the terminal open. You can set up auto-start as well. Or pass a cron job.

<br>

### Uninstall

1. Use ```rm -rf```.

*Note:* If you're unfamiliar with this command, delete project folder from file explorer.

<br>

### Mechanism

The bot uses the chatgpt lib to process queries, it keeps a browser window open to facilitate getting session details.

<br>


    Copyright (C) 2023  Zubin

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

