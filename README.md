# SAP Cloud Application Programming - Development Container Template

A template for a development container for SAP Cloud Application Programming Model

## Installation

### Docker & VSCode - `(local development)`

1. Install [**Docker desktop**](https://www.docker.com/products/docker-desktop/)
2. Clone `capm-devcontainer-template` using below command :

```bash
git clone https://github.com/tobkle/capm-devcontainer-template ./capm-project
```

3. Open project in `VSCode` using:

```bash
code capm-project
```

4. Change GIT remote origin to your origin

```bash
git remote remove origin
git remote add origin https://github.com/username/capm-project.git
git branch -M main
git push -u origin main
```

5. Install [Remote development pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) VScode extension

6. COMMAND + SHIFT + P on `MacOS` or CTRL + SHIFT + P on `Windows`

   1. Type - `Rebuild and Reopen in Container` - This step will start creating the container project and start the Node server.

7. Start development as usual.

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### SAP Business Application Studio - `(BAS)`

1. Clone `capm-devcontainer-template` using below command :

```bash
git clone https://github.com/tobkle/capm-devcontainer-template ./capm-project
```

2. Change GIT remote origin to your origin

```bash
git remote remove origin
git remote add origin https://github.com/username/capm-project.git
git branch -M main
git push -u origin main
```

3. Install the following npm packages

```bash
npm install -g typescript ts-node
```

4. Start development as usual.

```bash
npm start
```

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>
