AutoGPT Reading Note

- support Azure Open AI service by following this [guidance](https://gist.github.com/primaryobjects/523577860628974501ffd3c52cd73525#automatic-login-to-azure)

- test goal: what components are used in the repo, the root path of repo is "/workspace/Auto-GPT/auto_gpt_workspace/share-now"? do not parse file, just read file line by line.

- get token:
```
az account get-access-token --resource https://cognitiveservices.azure.com
```
