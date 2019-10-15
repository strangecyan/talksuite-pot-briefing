# Talksuite PoT
## Briefing dialogues and LUIS models

Import the model.json file to the [luis.ai](luis.ai) portal.

To deploy these dialogues to your talksuite organisation. To do so:
* Install the talksuite CLI by running `npm i @talksuite/talksuite-cli -g`.
* Log in to the CLI with your talksuite account by running `ts login`.
* Download or checkout this repo.
* Run the following command in the root folder `ts import-content ./dialogues/` and choose the organisation you want to use.

In talksuite your bot should be configured with:
* The "Briefing" project
* An active briefing process
