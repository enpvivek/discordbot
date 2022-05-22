
# Simple Discord Bot

A simple modular lightweight Discord Bot which can be scaled if needed.

## Deployment

To deploy this project 

Create a newfile named .env and add config variables from .envtemplate file.

Install yarn

```bash
  npm install yarn

```
Then run yarn start script
```bash
  yarn start

```


## Deploy to Heroku
To Deploy this project to Heroku

    1. Fork this repository.
    2. Create a new app with unique appname.
    3. Go to deploy section and connect your Github repository.
    4. Go to settings > secrets,  add config vars - APPLICATION_ID , GUILD_ID, and TOKEN.
    5. Enable automatic deploys and click on deploy button.
## Run Locally

Clone the project

```bash
  git clone https://github.com/enpvivek/discordbot
```

Go to the project directory

```bash
  cd discordbot
```

Install yarn

```bash
  npm install yarn
```

Build and Start the server

```bash
  yarn start
```


## Usage/Examples
You can add more commands in this bot by creating new command file in /src/slash-commands/yourcommandname.ts
```javascript
import { SlashCommandBuilder, memberNicknameMention} from "@discordjs/builders";
import { SlashCommand } from "../types";


export const CommandName: SlashCommand = {
command: new SlashCommandBuilder()
        .setName('commandname')
        .setDescription('command description'),
    async run(interaction){
        //Write your command response here
        });
    } ,   
};
```


## License
MIT License

Copyright (c) 2022 Vivek Yadav

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


[MIT](https://choosealicense.com/licenses/mit/)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Demo

https://github.com/enpvivek/discordbot/blob/main/Images/image.png

