# Carpet Rules database

The central database of all the rules available in carpet and it's extensions.  
This project uses a custom parser to read and process the rules from java files themselves.  

## Contribute

### Adding your repo to the database

If you want to add your extension to the database,  
please add your extension to [data/repos.json](data/repos.json) and submit a pull request.

The schema for rule follows:
```json
{
    "name": "Your carpet extension name",
    "ownerRepo": "owner/repo",
    "settingsFiles": [
        "group/path/to/settings/file.java",
        "group/path/to/another/settings/file.java"
    ],
    "branches": [
        "branch",
        "another-branch"
    ]
}
```

### Code contributions

Please make an issue or contact me over on [discord](#contact) to discuss your ideas before submitting a pull request.  
Once you are good to go, follow the steps below to submit a pull request.

- Fork/Clone the repo
- Add your modifications to the repo
- Create a pull request

### Contact

Discord: `Crec0#0420`