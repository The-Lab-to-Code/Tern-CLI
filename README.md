# Tern-CLI

A lightweight command-line interface (CLI) built with Clojure.

## Prerequisites

Before running `Tern-CLI`, ensure your environment meets the following requirements:

- **Clojure (v1.12.6 or later):** Install the latest version from the [Official Clojure Getting Started Guide](https://clojure.org/guides/install_clojure).
- **System PATH:** Ensure the `clojure` (or `clj`) executable is added to your system's `PATH` environment variable so it can be invoked globally.
- **Terminal Environment:** 
  * **Windows:** Command Prompt, PowerShell, or Windows Terminal.
  * **macOS / Linux:** Any standard shell (Bash, Zsh, etc.).
  * **IDE Integration:** An integrated terminal such as VS Code (paired with the [Calva](https://calva.io/) extension for Clojure support).

## Installation & Running

* **Windows:** When you have finished downloading the zip file `ternZipped.zip`, unzip the file into a folder. Then, run the `.bat` file. The CLI will launch automatically.
* **macOS:** When you have finished downloading `ternZipped.zip`, double-click the file in Finder (or run `unzip ternZipped.zip` in Terminal) to extract it into a folder. Open Terminal, navigate to the extracted folder (`cd path/to/folder`), make the shell script executable (`chmod +x tern.sh`), and run `./tern.sh` to launch the CLI. *(Note: If macOS Gatekeeper blocks the script on first run, right-click the file and select **Open**, or allow it under **System Settings > Privacy & Security**.)*
* **Linux:** When you have finished downloading `ternZipped.zip`, extract it into a folder using your file manager or `unzip ternZipped.zip -d tern-cli`. Open your terminal, navigate to the folder (`cd tern-cli`), grant execution permissions (`chmod +x tern.sh`), and run `./tern.sh` to launch the CLI.

This program has commands that have access to your filesystem (as any other language does). Do not run any random delete commands, which risks deleting important files. **Always** delete files in a safe manner. 

Do: `file.system.remove("helloworld.txt")` <- Files that are harmless to the computer

Don't: `file.system.remove("system32")` <- Files that can severely damage or ruin the computer/operating system

Tern v3.25
