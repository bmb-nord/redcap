## Environment Setup

Before

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Setting up this project

1. Download and install `Git for Windows` from [git-scm.com](https://git-scm.com/install/windows).

2. Open `Git Bash` app in windows and follow the commands below

    change directory to your project directory
    ```bash
    cd /your/project/directory
    ```
    clone the repo
    ```bash
    git clone https://github.com/bmb-nord/redcap.git .
    ```

    create virtual environment
    ```bash
    python -m venv venv
    ```
    activate the vitual environment
    ```
    source venv/Scripts/activate
    # or in powershell use
    .\venv/Scripts/activate
    ```
    install dependencies
    ```
    pip install -r requirements.txt
    ```

    Start the live-reloading docs server
    ```
    mkdocs serve
    ```

3. Start development in VSCode or editor of your choice.

    !!! note
        You can install vscode.markdown-language-features extension to enable and visualize markdown display side-by-side

4. somsoms