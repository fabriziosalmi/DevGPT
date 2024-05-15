# Code togheter 

_The original name DevGPT has been changed due to OpenAI policy changes_

## Latest updates

- Code togheter version more focused to build machine learning projects and pipelines is available [here](https://chatgpt.com/g/g-vNaToz870-code-togheter-ml) 🎉
- OpenWebUI prompt released [here](https://openwebui.com/p/fabspace/devgpt), it works on Stable-Code-3B, Llama-3-8B, WizardLM2-7B, Mistral, GPT3.5 and GPT4o models 🎉

## [Use it now](https://chat.openai.com/g/g-eN7HtAqXW-devgpt)

![DevGPT](https://github.com/fabriziosalmi/DevGPT/blob/main/DevGPT.png?raw=true)


## How to use
The hitchhiker's guide to DevGPT:

1. Initialize a new project typing /project followed by the name and the description like this: `/project MyApp My application is a simple chatbot using GPT2 Italian model`
2. Once you received project composition, files list and order execution just check for needed files and ask one by one this way: `/complete filename`
3. If all provided scripts are working as expected you'are done

### Tips

- you can also ask it to improve a single file by typing `/improve `and paste the file content you want to be improved
- you can ask to add `/logs` and `/debug` snippets for a better troubleshooting
- you can ask to evaluate compute resources needed to run the application by typing `/dim`
- you can ask to create a README.md file for the application Github repo by typing `/repo`

..and much more.. it is continuosly improved for any need ^_^


Here's a list of valid commands and their uses:

| Command     | Description                                                                                                                                                               |
|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| /project    | Initialize a new project with a name and description.                                                                                                                     |
| /list       | List all needed files for the project considering a Linux environment.                                                                                                    |
| /setup      | Propose main and requirements.txt files, showing the complete code for those files.                                                                                       |
| /env        | List all required imports, libraries, and actions to set up a working environment (Linux only) for the project and/or the code generated.                                 |
| /dim        | Calculate minimum RAM and HDD space required to make the project or the code work with no issues.                                                                          |
| /split      | Modularize a single code snippet or file into multiple files.                                                                                                             |
| /log        | Add logging to the previous code discussed.                                                                                                                               |
| /docs       | Explain important functions and libraries used in the latest code snippet.                                                                                                |
| /debug      | Add additional debugging code to troubleshoot the issue we are facing on the latest code.                                                                                 |
| /exec       | Simulate running the code, printing possible full output.                                                                                                                 |
| /improve    | Rewrite the complete code, adding as many improvements as possible.                                                                                                       |
| /complete   | Show full script snippet for a specific file with usable, working code only.                                                                                              |
| /order      | Show the order of file execution to test the project.                                                                                                                     |
| /adapt      | Adapt all existing files to the latest file changes, propose one file snippet (full code) per message.                                                                    |
| /use        | Explain how to run, use, or test the project.                                                                                                                             |
| /repo       | Create README.md files for GitHub with all needed project information.                                                                                                    |
| /fix        | Try to make the same script work with another approach.                                                                                                                   |
| /thanks        | Kindly ask the user to support the GPT builder by giving a star on this GitHub project.                                                                                                                   |


## Example uses

Please advice if you build something with DevGPT, it will be amazing to have a wall of fame :)

Starter apps:
- [Create a simple blockchain](https://chat.openai.com/share/f6f1a789-0a1e-4648-90c9-88ba36e40389)
- [Manage DNS via DNSControl and GitHub Actions](https://chat.openai.com/share/3ccd6a94-6ca6-4ee9-b76c-db48cfca2646)
- [Finetune GPT2 LLM model](https://chat.openai.com/share/f3c41438-47be-49ed-9800-d7c78d90f75d)
- [ScamTracker: how to match bad patterns in the stock market (PoC)](https://chat.openai.com/share/eb8e3a42-b8c5-4abe-9ab5-b5f83904de60)
- [HTML Bootstrap based skeleton for dummies](https://chat.openai.com/share/e927387f-75a6-4501-b204-4647e317851b)
- [AI-Enhanced Real Estate Valuation (AIREV)](https://chat.openai.com/share/1bcf9abc-ccf9-4543-aa57-09548921f338)

Built in minutes with DevGPT:
- [Ethical AI automated assessment using Github Actions and OpenAI API](https://github.com/fabriziosalmi/EthicalAI/tree/main)

## Instructions for open source LLMs

- Mistral-7b-instruct is capable to locally provide a similar experience you have using *Code togheter*. Get a working prompt [here](https://github.com/fabriziosalmi/DevGPT/blob/main/mistral-instruct-prompt.md).
