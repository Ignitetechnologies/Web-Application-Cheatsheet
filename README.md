# Web Application Cheatsheet (Vulnhub)

This cheatsheet is aimed at the CTF Players and Beginners to help them understand Web Application Vulnerablity with examples. There are multiple ways to perform the same tasks. We have performed and compiled this list on our experience. Please share this with your connections and direct queries and feedback to [Pavandeep Singh](https://www.linkedin.com/in/pavan2318).

[1.1]: http://i.imgur.com/tXSoThF.png
[1]: http://www.twitter.com/rajchandel
# Follow us on [![alt text][1.1]][1]

<img src="https://i.ibb.co/xfPQjzq/vulnhub-web-app.jpg" alt="vulnhub-web-app" border="0">

Table of Contents
=================

* [Drupal](#drupal)
* [Jenkins](#jenkins)
* [Joomla](#joomla)
* [WebMin](#webmin)
* [Wordpress](#wordpress)
* [Builder Engine](#builder)
* [CMS Made Simple](#cmsms)
* [CouchDB](#couch)
* [Cuppa](#cuppa)
* [Cute News 2.0.3](#cute)
* [Impress](#impress)
* [LibreNMS](#librenms)
* [Moodle](#moodle)
* [Php Mailer](#phpmailer)
* [Playsms](#playsms)
* [Rips](#rips)
* [SPHP Blog](#sphp)
* [Squirrel Mail](#squirrel)
* [PHPText](#phptext)
* [Wolf](#wolf)
* [Zenphoto](#zen)
* [Redis](#redis)
* [Nano CMS](#nano)


<a name="drupal"></a>
##  Drupal [⤴](#table-of-contents)

|No.| Machine Name             | Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Droopy](https://www.hackingarticles.in/hack-droopy-vm-ctf-challenge/)|[Drupalgeddon](https://www.exploit-db.com/exploits/34992)|
|2. |[Billu Box 2](https://www.hackingarticles.in/hack-billu-b0x-vm-boot2root-challenge/)|[Drupalgeddon2](https://www.exploit-db.com/exploits/44449) |
|3. |[Lampiao : 1](https://www.hackingarticles.in/hack-the-lampiao-1-ctf-challenge/)|[Drupalgeddon2](https://www.exploit-db.com/exploits/44449) |
|4. |[Typhoon : 1.02](https://www.hackingarticles.in/typhoon-1-02-vulnhub-walkthrough/)|[Drupalgeddon2](https://www.exploit-db.com/exploits/44449) |
|5. |[DC-1](https://www.hackingarticles.in/dc-1-vulnhub-walkthrough/)|[Drupalgeddon2](https://www.exploit-db.com/exploits/44449)|
|6. |[RootThis : 1](https://www.hackingarticles.in/vulnhub-rootthis-1-walkthrough/)|Manual|
|7. |[DC:7](https://www.hackingarticles.in/dc7-vulnhub-walkthrough/)|Manual|

<a name="jenkins"></a>
##  Jenkins [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Jarbas : 1](https://www.hackingarticles.in/hack-the-jarbas-1-ctf-challenge/)|[Jenkins Script Console](https://www.rapid7.com/db/modules/exploit/multi/http/jenkins_script_console)| 

<a name="joomla"></a>
##  Joomla [⤴](#table-of-contents)

|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Hackademic-RTB2](https://www.hackingarticles.in/hack-the-hackademic-rtb2-boot2root/)|SQL Injection|
|2. |[Kevgir](https://www.hackingarticles.in/hack-kevgir-vm-ctf-challenge/)|[Joomla! 1.5.x - 'Token'](https://www.exploit-db.com/exploits/6234)
|3. |[DC-3](https://www.hackingarticles.in/dc-3-walkthrough/)|[Joomla! 3.7.0 - 'com_fields' SQL Injection](https://www.exploit-db.com/exploits/42033)|
|4. |[Born2Root: 2](https://www.hackingarticles.in/born2root-2-vulnhub-walkthrough/)|Enumeration|

<a name="webmin"></a>
##  WebMin [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[pWnOS -1.0](https://www.hackingarticles.in/hack-the-pwnos-1-0-boot-to-root/)|[Webmin File Disclosure](https://www.rapid7.com/db/modules/auxiliary/admin/webmin/file_disclosure) 
|2. |[VulnOS: 1](https://www.hackingarticles.in/hack-the-vulnos-1-ctf-challenge/)| [DistCC Daemon Command Execution](https://www.rapid7.com/db/modules/exploit/unix/misc/distcc_exec)
|3. |[Nezuko:1](https://www.hackingarticles.in/nezuko-1-vulnhub-walkthrough/)|[Webmin 1.920 - Remote Code Execution](https://www.exploit-db.com/exploits/47293) 


<a name="wordpress"></a>
##  Wordpress [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. | [Hackademic-RTB1](https://www.hackingarticles.in/hack-the-hackademic-rtb1-vm-boot-to-root/)|Enumeration|
|2. | [Mr. Robot](https://www.hackingarticles.in/hack-mr-robot-vm-ctf-challenge/)|Bruteforce|
|3. | [Stapler](https://www.hackingarticles.in/hack-stapler-vm-ctf-challenge/)|Enumeration/Bruteforce|
|4. | [Minotaur](https://www.hackingarticles.in/hack-minotaur-vm-ctf-challenge/)|[Wordpress SlideShow Gallery Authenticated File Upload](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_slideshowgallery_upload)|
|5. | [Freshly](https://www.hackingarticles.in/hack-freshly-vm-ctf-challenge/)  |Manual|
|6. | [USV](https://www.hackingarticles.in/hack-usv-vm-ctf-challenge/)          |Enuemration|
|7. | [Quaoar](https://www.hackingarticles.in/hack-quaoar-vm-ctf-challenge/)    |Enumeration|
|8. | [Lazysysadmin](https://www.hackingarticles.in/hack-lazysysadmin-vm-ctf-challenge/) |[WordPress Admin Shell Upload](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_admin_shell_upload)| 
|9. | [BTRSys:dv 2.1](https://www.hackingarticles.in/hack-btrsys-v2-1-vm-boot2root-challenge/)|Enumeration|
|10. | [Basic Penetration](https://www.hackingarticles.in/hack-the-basic-penetration-vm-boot2root-challenge/) |[WordPress Admin Shell Upload](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_admin_shell_upload)| 
|11. | [DerpNStink](https://www.hackingarticles.in/hack-the-derpnstink-vm-ctf-chAllenge/)|[Wordpress SlideShow Gallery Authenticated File Upload](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_slideshowgallery_upload)|
|12. | [BSides Vancuver: 2018](https://www.hackingarticles.in/hack-the-bsides-vancouver2018-vm-boot2root-challenge/) |[WordPress Admin Shell Upload](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_admin_shell_upload)| 
|13. | [Raven](https://www.hackingarticles.in/hack-the-raven-walkthrough-ctf-challenge/)|Enumeration|
|14. | [HackinOS : 1](https://www.hackingarticles.in/hackinos1-vulnhub-lab-walkthrough/)|Enumeration|
|15. | [Web Developer : 1](https://www.hackingarticles.in/web-developer-1-vulnhub-lab-walkthrough/)|[WordPress Photo Gallery Unrestricted File Upload](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_photo_gallery_unrestricted_file_upload)|
|16. | [DC-2](https://www.hackingarticles.in/dc-2-walkthrough/)                 |Enumeration/Bruteforce|
|17. | [DC6](https://www.hackingarticles.in/dc6-lab-walkthrough/)        |[Plainview Activity Monitor 20161228](https://www.exploit-db.com/exploits/45274)|
|18. | [symfonos : 1](https://www.hackingarticles.in/symfonos1-vulnhub-walkthrough/)          |[WordPress Plugin Mail Masta 1.0 - Local File Inclusion](https://www.exploit-db.com/exploits/40290)|
|19. | [PumpkinFestival](https://www.hackingarticles.in/mission-pumpkin-v1-0-pumpkinfestival-vulnhub-walkthrough/) |Enumeration|
|20. | [SP:Jerome](https://www.hackingarticles.in/spjerome-vulnhub-walkthrough/)|[WordPress Crop-image Shell Upload](https://www.rapid7.com/db/modules/exploit/multi/http/wp_crop_rce)|
|21. | [dpwwn:2](https://www.hackingarticles.in/dpwwn2-vulnhub-walkthrough/)  |[Wordpress Plugin Site Editor 1.1.1](https://www.exploit-db.com/exploits/44340)|
|22. | [GrimTheRipper:1](https://www.hackingarticles.in/grimtheripper-1-vulnhub-walkthrough/)       |Bruteforce|
|23. |[symfonos : 2](https://www.hackingarticles.in/symfonos1-vulnhub-walkthrough/)|[WordPress Plugin Mail Masta 1.0 - Local File Inclusion](https://www.exploit-db.com/exploits/40290)|
|24. |[Prime: 1](https://www.hackingarticles.in/prime-1-vulnhub-walkthrough/)| Enumeration|

<a name="builder"></a>
##  Builder Engine [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Sedna](https://www.hackingarticles.in/hack-sedna-vm-ctf-challenge/)|[builderengine_upload_exec](https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/multi/http/builderengine_upload_exec.rb)|


<a name="cmsms"></a>
##  CMS Made Simple [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[West Wild: 2](https://www.hackingarticles.in/westwild-2-vulnhub-walkthrough/)|[CMSMS Showtime2 File Upload RCE](https://www.rapid7.com/db/modules/exploit/multi/http/cmsms_showtime2_rce) |


<a name="couch"></a>
##  CouchDB [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Moonraker:1](https://www.hackingarticles.in/moonraker1-vulnhub-walkthrough/)|[Node.js deserialization RCE](https://opsecx.com/index.php/2017/02/08/exploiting-node-js-deserialization-bug-for-remote-code-execution/)|


<a name="cuppa"></a>
##  Cuppa [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[W1R3S.inc](https://www.hackingarticles.in/hack-the-w1r3s-inc-vm-ctf-challenge/)|['/alertConfigField.php' LFI/RFI](https://www.exploit-db.com/exploits/25971)|
|2. |[BRAVERY](https://www.hackingarticles.in/digitalworld-local-bravery-vulnhub-walkthrough/)|['/alertConfigField.php' LFI/RFI](https://www.exploit-db.com/exploits/25971)|


<a name="cute"></a>
##  Cute News [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Simple](https://www.hackingarticles.in/hack-simple-vm-ctf-challenge/)|[CuteNews 2.0.3 Remote File Upload](https://www.exploit-db.com/raw/37474)|


<a name="impress"></a>
##  Impress [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Breach 1.0](https://www.hackingarticles.in/hack-breach-1-0-vm-ctf-challenges/)|Enumeration|

<a name="moodle"></a>
##  Moodle [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Golden Eye:1](https://www.hackingarticles.in/hack-the-golden-eye1-ctf-challenge/)|[Moodle - Remote Command Execution](https://www.exploit-db.com/exploits/29324)|


<a name="phpmailer"></a>
##  PHP Mailer [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Raven : 2](https://www.hackingarticles.in/raven-2-vulnhub-walkthrough/)|[PHPMailer < 5.2.18 - Remote Code Execution](https://www.exploit-db.com/exploits/40974)|


<a name="playsms"></a>
##  Playsms [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Dina](https://www.hackingarticles.in/hack-dina-vm-ctf-challenge/)|[PlaySMS import.php Authenticated CSV File Upload Code Execution](https://www.rapid7.com/db/modules/exploit/multi/http/playsms_uploadcsv_exec)|


<a name="rips"></a>
##  Rips [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Mercy](https://www.hackingarticles.in/mercy-vulnhub-walkthrough/)|[RIPS 0.53 - Multiple Local File Inclusions](https://www.exploit-db.com/exploits/18660)|


<a name="sphp"></a>
##  Simple PHP Blog [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[pWnOS -2.0](https://www.hackingarticles.in/hack-the-pwnos-2-0-boot-2-root-challenge/)|[Simple PHP Blog Remote Command Execution](https://www.rapid7.com/db/modules/exploit/unix/webapp/sphpblog_file_upload) 


<a name="squirrel"></a>
##  Squirrel Mail [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[DE-ICE:S1.140](https://www.hackingarticles.in/hack-the-de-ice-s1-140-boot-to-root/)|Enumeration|

<a name="phptext"></a>
##  PHPTax [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Kioprtix: 5](https://www.hackingarticles.in/hack-the-kioptrix-5-ctf-challenge/)|[PhpTax Remote Code Injection](https://www.rapid7.com/db/modules/exploit/multi/http/phptax_exec)

<a name="wolf"></a>
##  Wolf [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[SickOS 1.1](https://www.hackingarticles.in/hack-sickos-1-1-vm-ctf-challenge/)|[Default Credential](https://en.wikipedia.org/wiki/Default_Credential_vulnerability)


<a name="zen"></a>
##  Zenphoto [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Orcus](https://www.hackingarticles.in/hack-orcus-vm-ctf-challenge/)|Enumeration|


<a name="redis"></a>
##  Redis [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[Gemini inc:2](https://www.hackingarticles.in/hack-the-gemini-inc2-ctf-challenge/)|Remote Code Execution(RCE)|


<a name="nano"></a>
##  Nano CMS [⤴](#table-of-contents)
|No.| Machine Name             |Exploit/Vulnerability|
|---|-----------------------|------------|
|1. |[LAMPSecurity: CTF 5](https://www.hackingarticles.in/hack-the-lampsecurity-ctf-5-ctf-challenge/)|[NanoCMS '/data/pagesdata.txt' Password Hash Information Disclosure](https://www.securityfocus.com/bid/34508/exploit)|
