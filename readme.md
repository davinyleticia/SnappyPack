# SnappyInstall

## Developer Tools Setup

This project provides a Bash script that automates the installation of essential tools for a development environment on Linux (Debian/Ubuntu-based) systems. The script installs code editors, web browsers, database managers, and other important developer utilities.

[https://SnappyInstall.codes](https://SnappyInstall.codes)

<img class="mascote" src='https://snappyinstall.codes/img/mascote.png'/>

## Installed Tools (DEV Package)

The script will install the following tools:

- **Visual Studio Code**: Microsoft's code editor, highly popular among developers.
- **Google Chrome**: Internet browser.
- **Insomnia REST**: Tool for testing REST APIs.
- **Git**: Version control system.
- **NVM**: Node Version Manager, to manage Node.js versions.
- **DBeaver**: Universal database client.
- **FileZilla**: FTP client.
- **OBS Studio**: Screen recording and live streaming software.
- **Raspberry Pi Imager**: System burning tool for SD cards and USB drives.

## Prerequisites

To run the script, you need to:

- **Operating Syste**: Ubuntu, Debian, or any .NET-based Linux distribution `apt`.
- **Privilégios de Superusuário**: Run the script with sudoto allow installation of packages.

## How to Use

You can run the script directly using the command `curl`:

```bash
curl -sSL snappyinstall.codes/dev | sudo bash
```

This command downloads and runs the script directly, ensuring a quick installation without the need to download the file manually.

## Script Structure

The script follows the following structure:

1. **Permissions Check**: Confirms that the user has privileges `sudo`.
2. **System Update**: Updates the system to avoid installation conflicts.
3. **Installing Tools**: Downloads and installs each tool, using aptor files .debwhen necessary.
4. **Cleanup**: Removes downloaded temporary files such as `.deb`.

## Troubleshooting

- **Permission Error**: Make sure you run the script with `sudo`.
- **Missing Dependencies**: During runtime, `apt` may prompt to install additional dependencies for some tools.
- **Unsupported Distribution**: This script is made for Linux-based systems `apt`. Distributions like Fedora or Arch Linux will require adaptations to the script.

## Contribution

Contributions are welcome! Feel free to open an *issue* or submit a *pull request* .


## License

This project is licensed under the MIT License. See the file LICENSEfor more details.

## Contributors 🤝

We thank everyone who contributes to this project! 🎉


<table>
  <tr>
    <td align="center">
      <a href="https://github.com/davinyleticia">
        <img src="https://avatars.githubusercontent.com/davinyleticia" width="200px;" height="203px" alt="Foto do Contribuidor"/><br>
        <sub><b>DavinyLetícia</b></sub>
      </a><br>
      Founder
    </td>

     <tr>
    <td align="center">
      <a href="https://github.com/DaniDJunior">
        <img src="https://avatars.githubusercontent.com/DaniDJunior" width="200px;" height="203px" alt="Foto do Contribuidor"/><br>
        <sub><b>Daniele Junior</b></sub>
      </a><br>
      Contributors
    </td>

     <tr>
    <td align="center">
      <a href="https://github.com/isjanebea">
        <img src="https://avatars.githubusercontent.com/isjanebea" width="200px;" height="203px" alt="Foto do Contribuidor"/><br>
        <sub><b>Beatriz Ramerindo</b></sub>
      </a><br>
      Contributors
    </td>
    

  </tr>
</table>


---

### Observation

This script installs the most commonly used tools in development environments. For additional or more specific configurations, consult the official documentation for each tool.

