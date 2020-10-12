# Setting up your Mac for Development
All the content in this guide assumes that you are using a MacOs.

## Requirements
1. [Git](https://github.com/madebyid/handbook/blob/master/setup-mac.md#git)
2. [NVM](https://github.com/madebyid/handbook/blob/master/setup-mac.md#nvm)
3. [Yarn Package Manager](https://github.com/madebyid/handbook/blob/master/setup-mac.md#yarn-package-manager)
4. [Github](https://github.com/madebyid/handbook/blob/master/setup-mac.md#github)

### Git
We use Git as version control system.

By default Macos already have Git installed so for checking it run

<pre><code>git --version</pre></code>

### NVM
We use [NVM](https://github.com/nvm-sh/nvm) for being able to manage multiple active node.js versions. Sometimes you could be working in different projects with different Node version requirements.

[Install instructions](https://github.com/nvm-sh/nvm#install--update-script)<br>
[Troubleshooting on MacOS](https://github.com/nvm-sh/nvm#troubleshooting-on-macos)<br>
[Verify installation](https://github.com/nvm-sh/nvm#verify-installation)<br>
[Usage](https://github.com/nvm-sh/nvm#usage)

### Yarn Package Manager
We use [Yarn](https://yarnpkg.com/) as package manager.

Easiest way to install yarn with NVM is with this command

<pre><code>npm install -g yarn</pre></code>

**NOTE:** This only will install yarn for the active Node version in your NVM. If you install other Node version you will need install yarn again or [migrate global packages while installing](https://github.com/nvm-sh/nvm#migrating-global-packages-while-installing).

### Github
We use [Github](https://github.com/) as development platform.

You don't need install anything because is a web but you will need configure your account.

#### Two Factor Authentication
[Securing your account with two-factor authentication (2FA)](https://help.github.com/en/github/authenticating-to-github/securing-your-account-with-two-factor-authentication-2fa)

#### SSH
Avoid using HTTP for connecting Git and Github, always clone the project using SSH.

[Generating a new SSH key and adding it to the ssh-agent](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)<br>
[Adding a new SSH key to your GitHub account](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

[More info](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
