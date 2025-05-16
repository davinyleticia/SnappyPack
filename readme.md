# Snappy Pack

## Developer Tools Setup

This project provides a Bash script that automates the installation of essential tools for a development environment on Linux (Debian/Ubuntu-based) systems. The script installs code editors, web browsers, database managers, and other important developer utilities.

[https://snappypack.vidal.press](https://snappypack.vidal.press)

<div class="container">
    <h2>What is Snappy Pack?</h2>
    <p>snappypack is an open-source Bash script that installs essential development tools and utilities on Debian/Ubuntu-based Linux systems. It helps you bootstrap your development setup with just one command.</p>
<h2>Packages Available</h2>
<h3>Design Tools</h3>
<ul>
<li>Figma (via web)</li>
<li>GIMP</li>
<li>Inkscape</li>
<li>Krita</li>
<li>Blender</li>
<li>Darktable</li>
<li>OBS Studio</li>
<li>Google Chrome</li>
    </ul>
    <h3>Data Tools</h3>
    <ul>
       <li> Python 3 + pip</li>
<li>Jupyter Notebook</li>
<li>R e RStudio</li>
<li>DBeaver</li>
<li>PostgreSQL</li>
<li>MongoDB</li>
<li>Apache Spark</li>
<li>Google Chrome</li>
    </ul>
    <h3>Development Tools</h3>
<ul>
<li><strong>Visual Studio Code</strong>: Microsoft's code editor, highly popular among developers.</li>
<li><strong>Google Chrome</strong>: Internet browser.</li>
<li><strong>Insomnia REST</strong>: Tool for testing REST APIs.</li>
<li><strong>Git</strong>: Version control system.</li>
<li><strong>N</strong>: Node Version Manager, to manage Node.js.</li>
<li><strong>DBeaver</strong>: Universal database client.</li>
<li><strong>FileZilla</strong>: FTP client.</li>
<li><strong>OBS Studio</strong>: Screen recording and live streaming software.</li>
<li><strong>Raspberry Pi Imager</strong>: System burning tool for SD cards and USB drives.</li>
</ul>
    <h2>Installation</h2>
    <p>To install everything in one go, you can choose from the following categories.</p> 
    <p>To install a specific category, run the following command:</p>
    <pre><code>curl -sSL https://snappypack.vidal.press/{packege} | sudo bash </code></pre>
    <p>Packege: Dev, Design, Data<p>
    <p>Make sure to run the command with <code>sudo</code> to allow package installations.</p>
    <h2>Developer Tools Setup</h2>
    <p>This project provides a Bash script that automates the installation of essential tools for a development environment on Linux (Debian/Ubuntu-based) systems. The script installs code editors, web browsers, database managers, and other important developer utilities.</p>
    <h2>Prerequisites</h2>
    <p>To run the script, you need:</p>
    <ul>
        <li><strong>Operating System:</strong> Ubuntu, Debian, or any Linux distribution that uses <code>apt</code>.</li>
        <li><strong>Superuser Privileges:</strong> Run the script with <code>sudo</code> to allow installation of packages.</li>
    </ul>
    <h2>How to Use</h2>
    <p>You can run the script directly using:</p>
    <pre><code>curl -sSL https://snappypack.vidal.press/dev | sudo bash</code></pre>
    <p>This command downloads and runs the script immediately, ensuring a quick setup without needing to download files manually.</p>
    <h2>Script Structure</h2>
    <ul>
        <li><strong>Permissions Check:</strong> Confirms the user has <code>sudo</code> privileges.</li>
        <li><strong>System Update:</strong> Updates system packages to avoid installation conflicts.</li>
        <li><strong>Installing Tools:</strong> Downloads and installs each tool using <code>apt</code> or <code>.deb</code> files when needed.</li>
        <li><strong>Cleanup:</strong> Removes temporary files such as <code>.deb</code> packages.</li>
    </ul>
    <h2>Troubleshooting</h2>
    <ul>
        <li><strong>Permission Error:</strong> Ensure you are running the script with <code>sudo</code>.</li>
        <li><strong>Missing Dependencies:</strong> The script may prompt for additional dependencies during execution.</li>
        <li><strong>Unsupported Distribution:</strong> This script is designed for systems using <code>apt</code>. It will require adaptation for Fedora, Arch, or other distributions.</li>
    </ul>
    <h2>Contributing</h2>
    <p>Contributions are welcome! Feel free to open an issue or submit a pull request on <a href="https://github.com/davinyleticia/snappypack" target="_blank">GitHub</a>.</p>
    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for more details.</p>
    <h2>Contributors</h2>
    <p>We thank everyone who contributes to this project! 🎉</p>
    <div class="contributor">
        <img src="https://avatars.githubusercontent.com/davinyleticia" alt="Daviny Letícia">
        <div>
            <p><strong>Daviny Letícia</strong><br>Founder</p>
            <p></p><a href="https://github.com/davinyleticia">Github</a></p>
        </div>
    </div>
</div>
<div class="call-to-action">
    <p>Issues and Contributor!</p>
    <a href="https://github.com/davinyleticia/snappypack/issues" class="cta-button">Issues</a>
</div>
<footer class="footer">
    <p>&copy; 2025 snappypack. All rights reserved. Make in Brasil</p>
</footer>
