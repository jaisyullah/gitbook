---
icon: php
---

# Mobile Apps Additional Script

Navigate to "mobile" folder, there are 2 subfolders and config.php

* Config.php store sensitive data need to store separately, using your actual value if any changed credential / telegram bot token.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

* And 2 folders to store into 2 different subdomain folder, in my case i have 2 subdomain api & patrol

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

* Extract / move into each frontend (eg patrol) and backend (eg api) folder
* config.php as above only store into backend folder (/api/public)
* Custom your Database setting for this additional script, navigate into your backend folder /mobile/Initialize.php
*   Find Database::connect, setting according your mysql credential and host, port is optional.

    <figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>
* Done

