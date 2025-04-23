---
icon: laravel
---

# Backend

After Download your purchased script, you need to ensure to compile as below.

Backend :&#x20;

* Go to "php-laravel-api" folder

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

* Run your favorite code / editor and run at this folder, for run command purpose
* Custom you .env file, originally it show as below

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

* Lets say my domain app is patrol.kreatifdev.com and my api domain is api.kreatifdev.com, modify the file like this

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

* Upload the whole folder into your webserver folder pointing to your subdomain, eg in my case is api.kreatifdev.com
*   Open terminal / if your hosting allow ssh terminal run "composer install", wait process to done

    <figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>
* Ensure package/extension on php8.2 installed like cli, mysql, xml, mbstring, curl, zip, intl because it needed by laravel to run smoothly
* Done
