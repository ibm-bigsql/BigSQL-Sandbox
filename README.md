# IBM Big SQL Sandbox
## Abstract
Before you install the IBM Big SQL Sandbox application, get familiar with the most important information related to the installation process.

## Supported versions
- Windows:
  - Windows 10
- Mac:
  - OS X Yosemite 10.10.3, and later

## Installing the application
- If you use an older toolbox-based version of Docker, uninstall it before you install the Sandbox application.
- If you have other containers that run on your computer, stop them before you start the installation process of the Sandbox because your computer might have resource constraints.
- The Sandbox pulls a Docker container during the installation process. The installation takes about 15 to 20 minutes on a standard network speed of about 15-20 Mbps. A typical corporate VPN is likely to limit the download speed. Consider it while you wait for the installation to finish.
- If you already have the Sandbox installed and want to upgrade to a new version, from the menu in the upper-right corner select Uninstall.

## Launching the application
- If you are a Mac user, the following security warning is displayed when you launch the Sandbox application:
  - "IBM Big SQL Sandbox can't be opened because it is from an unidentified developer"
In this case, from the Apply menu, choose System Preferences, click Security & Privacy, then click General. In the General pane, click Open Anyway button. For details, see https://support.apple.com/kb/PH25088?locale=en_US.

You can visit our [Big SQL Community](https://developer.ibm.com/answers/topics/big_Sql_sandbox.html) for asking product related questions. You can also refer to our FAQ section here and open an issue for unanswered question.

## FAQs

- I already have docker installed on my laptop, will you use the existing install of docker or replace it?
  - We will only install Docker if you do not have it installed, or you have an older Docker installed.
- Which versions of Windows operating system are supported for IGC Trial?
  - Windows 10
- On a Mac, I see the warning message during launch: "IBM Big SQL Sandbox can't be opened because it is from an unidentified developer"
  - In this case, from the Apply menu, choose System Preferences, click Security & Privacy, then click General. In the General pane, click Open Anyway button. For details, see https://support.apple.com/kb/PH25088?locale=en_US.
- On Windows, I see the warning during launch:
 - You need to click on more-info then Run Anyway to launch the app
- My app installation seems to be hung with installation for more than 20 mins.
  - The app installation takes no more than 20 mins on a standard network download speed of 15 - 20 MBPS. A typical corporate VPN will likely limit the download speed so user must consider this while waiting to finish the install. If you loose an internet connection during the install, restart the install application when your connection is restored. In some cases, rebooting your computer and restarting the application will complete the installaltion successfully.
