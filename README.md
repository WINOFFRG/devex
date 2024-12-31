# 🧰 Corp DevEx


### 📁 Effortlessly sync configuration files
Sync files like `.netrc` or `.npmrc` across your projects with ease without having to manually copy them around. This is secure as you won't be creating new auth tokens always. This saves times as you won't need to search for your old tokens again. 

Manage tokens all at one place and sync them across your projects.

⚙️ Installation:


This script will install and setup the required tooling for you. 
1. Create a new Github PAT as per your requirement
2. Create your desired `.netrc` or `.npmrc` file
3. Paste that file in `~/` directory so that it can be synced across your projects
4. Run the script and follow the instructions
```bash
bash -c "$(curl -fsSL https://gist.githubusercontent.com/WINOFFRG/d2072f5453329db1d1b907237f0147b8/raw)"
```
5. Start using `sync <file>` to sync your files across your projects
