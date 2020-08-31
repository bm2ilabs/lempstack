<p align="center"><strong>Auto Install & Optimize LEMP Stack on CentOS 7, 8</strong></p>
<p align="center"><strong>Author: Sanvv - HOSTVN.NET Technical</strong></p>
<p align="center"><strong>Home Page: https://hostvn.vn/ , https://hostvn.net</strong></p>
<p align="center"><strong>Document: https://hostvn.vn/huong-dan/</strong></p>
<p align="center"><strong>Groups Support: https://www.facebook.com/groups/hostvn.vn</strong></p>

<p align="center"> <img src="https://blog.hostvn.net/wp-content/uploads/2020/07/logo-big-2.png" /> </p>

########################################################################################

Script written in shell used to install LEMP Stack (Nginx - MariaDB - PHP-FPM) on CentOS 7, CentOS 8.

<b>Please do not copy, reissue for commercial purposes, donate. Thank you.</b>

## 1. Script details:

### 1.1. Setting

- Constantly updated, providing menus for easy operation and automatic installation.
- Install the latest versions from the home page.
- Mariadb: 10.5.
- Nginx version: 1.18.0 Stable.
- Allows to choose PHP version:
    + centOS 7: 5.6, 7.0, 7.1, 7.2, 7.3, 7.4.
    + centOS 8: 7.2, 7.3, 7.4.
- phpMyAdmin 4.9.5 if the default PHP installation is 5.6,, phpMyAdmin 5.0.2 if the default PHP install is 7.x.
- Proftpd installation helps with FTP management.
- Install PHPMemcachedAdmin, phpRedisAdmin, phpSysInfo, Opcache Dashboard.
- Install memcached, redis cache. (It won't turn on by default).
- CSF Firewall and CSF GUI Setup - Manage CSF with web interface.
- Let's Encrypt SSL integration.
- Provide Nginx, MariaDB, PHP, Redis, Memcached, phpMyAdmin upgrade menu.
- Install WP-CLI, Composer, Rclone.
- Install: ClamAV, Naxsi Firewall.
- DO NOT COLLECT ANY INFORMATION ON YOUR VPS.

### 1.2. Optimal

- Optimal configuration of MySQL, Nginx, PHP, Opcache, Memcached, Redis in accordance with VPS parameters.
- Configure Brotli Compress.
- Configure URL rewrite with some popular source codes: WordPress, Laravel, Opencart, Magento, Drupal ...
- Allows running two PHP versions in parallel.
- Managing FTP is easy in case you hire a coder and just want them to be allowed access to certain directories.
- Allows you to choose Redis Cache or Memcached to speed up your website.
- Allow to configure Let's Encrypt auto-renew.
- The menu supports paid SSL configuration.
- Menu view error log Nginx, Mysql, PHP and view each specific domain name.
- Cronjob automatically updates Cloudflare's latest IP range for Nginx and CSF Firewall.
- And More ...

### 1.3. Security

- Configure for enhanced security from the webserver tier.
- Do not turn off Selinux on CentOS.
- Configure the website to run with different users to limit the spread of malicious code between websites.
- Disable dangerous functions, turn on open_basedir and a few other configs to increase security.
- Auto block brute force SSH, FTP .... with CSF Firewall.
- Block run shell in WordPress uploads folder. Block access to sensitive folders and files on WordPress
- Anti-Brute Force wp-admin.
- BLock, Unblock IP easily with CSF Gui (CSF management via Web interface) and CSF management menu
- Disable User API - /wp-json/wp/v2/users - in WordPress avoid exposing User information (Will develop disable toggle menu).
- Change SSH Port to avoid SSH scans.
- Allow to change the Admin port.
- Allows to change FTP port.
- Configure FTP security
- Automatically generate strong passwords.
- Scan Malware with Clamav.
- Limiting XSS, SQL Injection, RFI ... with Naxsi Firewall.
- And More ...

### 1.4. Manage WordPress

- Check which version of WordPress you are using.
- Update WordPress.
- Update plugins.
- Database optimization.
- Repair Database.
- Data Backup (Local / GG Drive).
- Data recovery (Local / GG Drive).
- Change domain name.
- Change the admin password (wp-admin).
- Automatic WordPress installation.
- Enable / Disable Yoast Seo config.
- Enable / Disable Rank Math Seo config.
- Configure Nginx with some popular cache plugins: WP-Rocket, w3 total cache, wp supercache, Cache Enabler, Swift Performance, Fast cache.
- Add a cache key to avoid duplicate content between sites when using memcached or redis.
- Enable / Disable Debug.
- Enable / Disable maintenance mode.
- Enable / Disable disable xmlrpc (Default will be disabled xmlrpc to avoid DDOS exploitation).
- Deactivate all plugins.
- Random database prefix when using the automatic installation function.

### 1.5. Backup / Restore data
- Backup and restore data from Google Drive with Rclone.
- Backup, restore at Local.
- Set the number of backups to be archived.
- Manage backups.
- Allows connecting multiple Google Drive accounts.

## 2. Requirement

- VPS is at least 1G ram and has not installed any services.
- CentOS 7, CentOS 8.

## 3. How to install

`curl -sO https://scripts.hostvn.net/install && chmod +x install && ./install`

## 4. Features will evolve

- Select PHP version in website.
- Quick deploy source code on VPS (extract file, import Database).
- Alert via email, telegram.
- Rewrite config vhost returns to default.
- Image optimization.
- Crontab automatically clears cache redis, memcached avoids full cache.
- Support creating Subdomain, Alias ​​Domain.
- Menu check DDOS.
- Swap creation menu.
- Management menu Naxsi Firewall.
- Supports Wordpress Multisite.
- Scan bug WordPress.
- Change Prefix database for wordpress.
- Enable / disable 2-layer protection for wp-admin.
- Option to disable wp cron, cPanel to use cronjob to speed up WordPress.
- Select website when automatic backup
- Added sync via 1 backup vps.
- Features requested by users.

## 5. Using

- Please access: https://hostvn.vn/huong-dan/

## 6. Source of software download

- Nginx: http://nginx.org/en/download.html
- MariaDB: https://downloads.mariadb.org/
- PHP: https://www.php.net/
- phpMyAdmin: https://www.phpmyadmin.net/
- PHPMemcachedAdmin: https://github.com/elijaa/phpmemcachedadmin
- phpRedisAdmin: https://github.com/erikdubbelboer/phpRedisAdmin
- phpSysInfo: https://github.com/phpsysinfo/phpsysinfo
- Pure-FTPD: https://www.pureftpd.org/project/pure-ftpd/
- Rclone: https://rclone.org/
- WP-CLI: https://wp-cli.org/
- Composer: https://getcomposer.org/
- ClamAV: https://www.clamav.net/
- Naxsi Firewall: https://github.com/nbs-system/naxsi

## 7. Contact

- Homepage: https://hostvn.vn , https://hostvn.net
- Group: hhttps://www.facebook.com/groups/hostvn.vn
- Email: Sanvv@hostvn.com

## 8. Feedback

- 
Due to the lack of experience, Scripts cannot avoid shortcomings. We hope to receive your suggestions to make Scripts more and more complete.
- Any suggestions, please send to sanvv@hostvn.com, Groups Facebook: https://www.facebook.com/groups/hostvn.vn or create Github Issues.

## 9. Contributors & Credits
### Developers / Maintainers
- Sanvv

### Contributors
- Mbrother GP
- Thanhnv
- Vouuvhb (Mtdev)
- Giapvv
- Lamhn
- tannm2611
- Nguyễn Cảnh Sơn

### Translate to english
- Boukraa Mohamed (bm2ilabs)
