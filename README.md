# Code Together

*Formerly known as DevGPT, rebranded due to OpenAI policy changes.*

## Latest Updates

- **New ML-Focused Version**: Discover our enhanced version for building machine learning projects and pipelines [here](https://chatgpt.com/g/g-vNaToz870-code-togheter-ml).
- **OpenWebUI Prompt**: Access the OpenWebUI prompt [here](https://openwebui.com/p/fabspace/devgpt), compatible with models like Stable-Code-3B, Llama-3-8B, WizardLM2-7B, Mistral, GPT3.5, and GPT4o.

## [Try It Now](https://chat.openai.com/g/g-eN7HtAqXW-devgpt)

![DevGPT](https://github.com/fabriziosalmi/DevGPT/blob/main/DevGPT.png?raw=true)

## How to Use

Follow this guide to get started with Code Together:

1. **Initialize a Project**: Use the `/project` command followed by the project name and description.  
   Example:  
   ```bash
   /project MyApp "My application is a simple chatbot using the GPT2 Italian model"
   ```
2. **Complete Your Files**: Review the project structure and use `/complete filename` to generate the necessary files.
3. **Finish and Refine**: Use additional commands like `/improve`, `/logs`, `/debug`, or `/dim` to enhance and finalize your project.

### Additional Tips

- **Improve a File**: Type `/improve` followed by the file content to enhance a specific file.
- **Add Logging**: Use `/logs` to insert logging and debugging snippets.
- **Resource Estimation**: Estimate compute resources required with `/dim`.
- **Generate a README**: Create a project README with `/repo`.

...and much more! Code Together is continuously evolving to meet all your development needs.

## Full Command List

| Command     | Description                                                                                               | Example Use                                                    |
|-------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| `/project`  | Initialize a new project with a name and description.                                                      | `/project MyApp "My application is a simple chatbot"`            |
| `/list`     | List all needed files for the project in a Linux environment.                                              | `/list`                                                       |
| `/setup`    | Propose `main` and `requirements.txt` files with full code.                                                | `/setup`                                                      |
| `/env`      | List required imports, libraries, and environment setup steps (Linux only).                                | `/env`                                                       |
| `/dim`      | Calculate the minimum RAM and HDD space required to run the project.                                       | `/dim`                                                       |
| `/split`    | Modularize a single code snippet or file into multiple files.                                              | `/split` (after providing a large code block)               |
| `/log`      | Add logging to the existing code.                                                                          | `/log` (after selecting or providing code)                    |
| `/docs`     | Explain the functions and libraries used in the latest code snippet.                                       | `/docs` (after providing code)                               |
| `/debug`    | Add debugging code to troubleshoot issues.                                                                 | `/debug` (after selecting or providing code)                    |
| `/exec`     | Simulate running the code and display the output.                                                          | `/exec` (after setting up the required files and env.) |
| `/improve`  | Optimize and enhance the existing code.                                                                    | `/improve` (after selecting or providing code)                    |
| `/complete` | Generate a complete script for a specific file.                                                            | `/complete my_file.py`                                           |
| `/order`    | Provide the order of file execution to test the project.                                                   | `/order`                                                      |
| `/adapt`    | Update all existing files to accommodate recent changes.                                                   | `/adapt` (after modifying one file)                           |
| `/use`      | Explain how to run, use, or test the project.                                                              | `/use`                                                       |
| `/repo`     | Generate a README.md file for GitHub with all necessary project information.                               | `/repo`                                                       |
| `/fix`      | Attempt to make the script work using an alternative approach.                                             | `/fix` (when existing code doesn't work)                       |
| `/thanks`   | Encourage users to support the project by starring the GitHub repository.                                  | `/thanks`                                                      |

## Example Uses

Share your creations! I love to feature them in the "Wall of Fame" 😊

### Starter Apps:

- [Create a Simple Blockchain](https://chat.openai.com/share/f6f1a789-0a1e-4648-90c9-88ba36e40389)
- [Manage DNS with DNSControl and GitHub Actions](https://chat.openai.com/share/3ccd6a94-6ca6-4ee9-b76c-db48cfca2646)
- [Fine-Tune GPT2 LLM Model](https://chat.openai.com/share/f3c41438-47be-49ed-9800-d7c78d90f75d)
- [ScamTracker: Pattern Matching in the Stock Market (PoC)](https://chat.openai.com/share/eb8e3a42-b8c5-4abe-9ab5-b5f83904de60)
- [HTML Bootstrap Skeleton for Beginners](https://chat.openai.com/share/e927387f-75a6-4501-b204-4647e317851b)
- [AI-Enhanced Real Estate Valuation (AIREV)](https://chat.openai.com/share/1bcf9abc-ccf9-4543-aa57-09548921f338)

### Built in Minutes with DevGPT:

- [Ethical AI Automated Assessment using GitHub Actions and OpenAI API](https://github.com/fabriziosalmi/EthicalAI/tree/main)

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) for more details on how to get involved.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions, issues, or feedback, please [open an issue](https://github.com/fabriziosalmi/DevGPT/issues).
