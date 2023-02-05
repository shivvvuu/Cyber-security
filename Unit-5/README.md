# Proxy Servers and Anonymizers
* A proxy server is another computer on the network which act as intermediary between client and server, or between one computer to anotther computer in the network.

Computer client <respone=request> proxy server <response=request> computer B(server)

* A client connects to the proxy server, requesting sone service, such as files, connections, web page or another resource available from diffrent server, proxy server then redirect the request to actual server receives response and send response back to cleint.

* Attackers can also use proxy to hide thier identity : The attacker machine connects through the prosy to access services provided by other computer (targets) onn the network.

* The target machine recives the request from any machine but cannot see the actual identity of attacker machine.

## A proxy server has following uses:
1. Hide the computer servers or system.
2. Caching: cache the frequently accessed web page to improve the reponse time for the client accessing those web pages.
3. Logging : can beused for logging the traffic goining in and out of the newtwork.
4. Encryption of resonses.
5. Load balancing: The proxy server can be used to distribute load to several server.
6. Compression: The proxy server can optimize and compress the content to send  speed up the load time. Compression means reducing the size of data so that it takes less time to transmit.

## Type of Proxy Server
1. Forward Proxies(Gateway or tunnel)
2. Reverse Proxies

#### Forward Proxies
* It provides proxy services to the clients or group of client. There are hundreds and thousands of open forward proxies on the internet.
* Forward proxies can also be anonymous proxies and allows user to hide thier IP address while browsing the internet services.

#### Reverse Proxies
* A reverse proxy does the opposite of what forward proxy dose: A forward proxy act on the behalf of client and reverse proxy work as a behalf of servers.
* Reverse proxy hides the identity of server.

# Anonymizers
* An anonymizer is a proxy server that makes internet activity untraceable and anonymous.
* It allows user to browse internet anonymously without revealing its identity.
* It is the easy way for the user to hide their IP address and loaction , and to misdirect tracking and servelliance softwares.

## Examples 
* Tunnelbear 
* Invisible Net Protect(I2P)
* Proxify
* Anonymizer Universal
* Uitrasurf 
* Net Proxy server

# Password Cracking
* Password creacking is the process of using an application program to identify an unknown or forgotten password of any computer or network resource.
* It can alos help ataacker to obtain unauthorized access to resources. Once the attacker obtain the password they csn perform range of criminal activity such as stealing bank credentials or using information to commit fraud or identity theft.

## How to create strong password
* Use atleast 12 characters long password
* Combines letter and special charaters
* Use unique password for diffrent apps.
* Avoid common password

## Password Cracking Technoques:-
* A password crakers can use various techniques to guess the password. Such as use list of words to guess passwords or use an algorithm to repeagtedly guess the password.

1. Brute Force Attack
* This is basicaly a hit and mis method as the hacker systematically checks all possible characters, calculates the hash of string combination and then compares it with the obtain password hash.
* The sucess of brute force attack depands on the length of the password Attacker tries every signal combination of letters, number and punctuation to generate a password. If the passowrd is ling, this technique takes time.

2. Dictionary Attack
* In this method, the hacker systematically enters every word in the dictionary to crack the password.
* This method can be successful because user prefer using common words as password.

3. Rainbow Table Attack
* The password are stored in server in Encrypted formate. Generally the passwords are converted into hashes and hashes are stored in table.
* Hacker can tryy to gain authentication by cracking password hash.
* Hacker use rainbow table : A list of pre-computed hashes of possible password combination.
* The hacker can look upto a rainbow table to creak the hash.

4. Phishing
* This technique does not use password cracking tools. Instead a user is fooled into clicking on an eamil attachment could install malware or prompt user to use their email to sign in to the fake website insted of real one.

5. Malware
* This technique does not use any password cracking tool. Malware can get installed in computer system and track the password
    * Keylogger-track keystrokes
    * Scrapers- Take screenshorts

6. Password Guessing 
* An attacker may be able to guess the password without useing any tool. If the password using any tool. If the attacker has enough information about the victim or the victim is using common enogh password , gussing is easy.

## Password Cracking Tools
1. Coin and Abel - Password recovery tool
2. John and Ripper - Dictiionary Attack
3. Ophcrack - Uses rainbow table and brute force attack

# Key Loggers
* A key logger (Key strock logger) is a tool that captures every single keystroke from the user to steal sensitive information including credentials and other information.
* A Keylogger can either store the imformation on the computer or can send  it directly to the attacker.
* A Keylogger can often install in the computer through Trojan horses a virus or a worm.
* For Example : As soon as user open the browser and some specific word like "Credit card, "account", "adhar card number", appear in the browser, the keylogger will record everything typed by user during a legitimate transaction and send the recorded information to the cyber criminal.
* Keyloggers are very powerful cybertool. They are widely destributed through email or spyware therfore often bypass antivirus protaction.

## Types of Keyloggers:
1. Hardware based keyloggers
* This is also called Physical Keylogger. It is a hardware device that can be user for keylogging.
* This is usually a small device that can be placed between the user's keyboard and main system.

2. Software Keyloggers
* Software Keylogger are dedicated program that is designed to track and log user keystrokes. These programs can be executed in windows, linus macOS, and even mobile devices.

## catagoried of software keylogger:
* Kernel based keylogger
* API based Keylogger
* Hybervisor Keylogger
* Web form or grabbing keyloggers

Key loggers can also be used in legal ways for example Employerds canuse keyloggers to maintain thier employee, activity.

# Spyware
* Spyware is one of the biggest danger we face on the internet.
It's A type of malicios software that can invade privacy and cause damage to computer system.
* Spyware is relatively a new phenomenon and does not have a long history as viruses, Trozen and worms.
* Spyware get install in someines's computer without their knowlage or by tricking them. One comman way is when any spyware insatlled in the computer, Spyware gets installed without user Knowledge or misleads about what it actually does.

## What does Spyware Do?
1. Spyware soy on user's behaviour. They can watch web pages you visit and report that information to server or persone and invade privacy.
2. It shows unwanted advertix=sing / pop up ads. As it spy , it pushes ads that user likes the most.
3. Spyware can use unwanted system memory and bring performace slow down sometimes system become unusable.
4. They can also allows installation of backdoors which allows attacker to log into the computer remotelt and do malicious activity on the computer such as sending spams.
5. Spyware can also change settings and hijack your web browser.

# VIRUS
* Viruses were one of the real security threat people has to deal with when started using computer system.
* The first computer viruse were invented in 1980s , however in 1990s they become real threat when everyone connected their computer to internet.
* Before Internet Viruses spread via floppy disks or CD's, Internet is wide source of virus now.
* A viruse consist of malicious code that is installed in the system without users knowlege and has capabillity of replicating itself.
## Virus Sources
1. External Media:-
    Any storage divce such as Floppy disk, CD's or DVD that can be inserted or connected into computer.

2. A Network Connection:-
    Can be spread through internet. In chat , email, via the web, via computer to computer network.

## Reasons of Spreading Viruses
1. Joke or Vandalism
    Sometimes virus writers just want to know if they have succeeded in getting a virus into computwe. so they post messges or alerts to your computer.

2. Data Destruction or Corruption
    Viruses can infact files, damgae them and make them unusable. They can also delete data from entire har drive.

3. Spam Distribution
    Some virus writter write the viruses so that they can send smap messages/ email from your computer.

4. Data or Information Theft
    Some viruses can steal sensitive or confidential information from computer.

5. Hijacking
    Viruses can turn the computer into Zombie. When a computer is Zombified. It can sent huge amount of data to another computer. Thousands of zombies can together crash web server like yahoo, amazom.

6. Virus Distribution 
    An infected computer can destributie viruses to another computer connected to it.

# Types of Virus
## MACRO Virus
* A macro is a programming language which is used to write automated task. For example A macro program to formate word document.
* A macro can be very short program or it can contain zillions of lines of code.
* Macro is designed to run as soon as any file with which it is attached to it is open.
* Virus attacker use this technique as an great opportunity to spread virus. The virus writters write viruses in micro and attach it to a file , then be sends the file attachment in the email. Once victim Open the attachment, macro is executed.
* Melissa :- A famous virus. It was famous for its speed, within first 3 days it has infacted 1 lakhh computers. It was spread through Email attachment (word document).
    1. Infect the documents in the system 
    2. Damage system by turning off security program including antivirus.
    3. Modify window registery or distroy data.

## Memory Resident Virus
* It is the type of computer virus that sits in computer's RAM(Random Access Memory).
* In RAM , files and program are loaded when user started them. For example: When power point is open, windows load it to RAM.
* As virus also resides in the memory, it gets asccess to all key operations carried out on the computer and it corrupt files and program with greate ease.
* As RAM is volatile, when the computer is turned off, all the data is the memory is clear out including virus.
* When it infects the system it ensures it is activated in memory every time a computer turns on.
* Memory resident virus can slow down your computer by stealing system resources. They can damage data and files which could stop computer fromm running correctly.

## File infecting Virus
* File infecting virus is one of the most common types of virus. It infects files with .exe pr .com extensions. Whne the infected file is accessed or executed, The virus is also executed , Files may be partially or completely overridden by virus.
* File infector virus can damage program or data files, it can even completely delete hard disk data.

## Boot Sector virus
* The boot sector virus, it the type of virus which infects boot sector/MBR(Member Boot Record) of hard disk.
* Member Boot Recor: MBR is small program in hard disk which loads Operating system.
* This virus can override MBR or the part of MBR program with malicius code. Every time the system loads malicious program gets executed.
* This virus uses DOS command sto spread itslef windows 95 make minimal use of DOS commands , therefore the virus starts to fade after window 95 was launched.
These virus are commanly spread using physical media 
    * Infected floppy disk
    * USB drive 
    * Email Attachment
* Removing Boot Sector virus is difficult in  many cases, user may not be aware that they have infected with virus , until they run antivirus software.

## How to sprevent virus infection 
* Resolve security loopholes by systemetically updateing the os and apps.
* Be familiar with current trends and reports.
* Scan the viruses regularly with antivirus software.
* Do not open the attachments of suspicios email.
* Check the web source before entring and sensitive data into website.

# WORMS
* Both virus and worms are malicious computer program that can dange a computer system, without user's knowledge replicates itself.
* Worms are exactly same as viruses but below are the key diffrences among them.
* A virus requires a program , or a file that helps it to spread. If user installs a program or open a file virus get installed in the machine.
* But worms are able to self replicate and spread without user action.
* Worms takes the advantage of security loopholes in operating system and application and because of this , worms cause disruption to normal traffic and computer activites. They can spread and replicate very fast.
* When worm replocate itself it was victim's computer power, it's processing power, memory and slows down the computer system. In Some cases it may even cause system to crash.
* worms are known for spreading far and wide over the internet in very shoet time.
* In 2001, A worm named NIMDA spread accross they entire network in just 22 minutes. In 2009 a worm named CONFICKER was spread. This is one of the largest worm till now , It was able to infact between 9-15 millions computer.
* Worms can easily spread if it finf windows operating system patch.

# Troznn Horse
* Trozons are the malicious program that can cause considerable damge to both hardware and software of a system.
* Trozon is the kind of channel that casuses malicios programs. A Trozon horse or Trozon is a malware that apparently a normal program but actullay contains virus/malicious program.
* Trozon horses appears to be usefull programs after user is tricked into installing them , they do bas things such as deploying viruses it open door to other malicious program to enter into the computer.
* Trozon horse can
    * Steal sensitive informaton (keylogger installed)
    * Store illegal material
    * Used as FTP server for pirated softerware

## Indicators of Trozon Attack
1. CD-ROM drawer closes/ opens automatically
2. Computer screen blinks or inverted
3. background / Wallpaper settings chnages automatically.
4. Color settings changes automatically.
5. Anti-virus is automatically disables.
6. Data and tme chnages.
7. Mouse pointer Disappear.
8. Pop ups suddenly appears

## Types of Trozon horse
Based on the manner in which trozon function , they are grouped into below categories:-
1. Remort Access Trozon Provides full contyroll over victim's computer.
2. Data sending Trozons will install a keylogger and can provide access to confidential data.
3. Destructive Trozon will delete files on the target system . A DoS attack Trozen allows attacker to start Destributed Denial of Service Attack(DDoS).
4. Proxy Trozons turns a computer into proxy server making the computer accessible to attacker.
5. FTP Trozon open the port 21, allowing the attacker to connect via FTP.
6. other Troxen can also disable antivirus software

## Trozon Counter Measures
1. Do not Download files from unkown sites.
2. Run antivirus, firewall, and Intrusion Detection software on computer.
3. Run trozon scanner
4. While downloading useful files do not download other programs/
5. Scan for suspicios port, running process.

## Countermeasures tools.
Antitrozon software should be run along with antivirus softeare and must be kept upto date.
## Anti Trozon Softwares
* Trozen Hunter
* Comdo Badean 
* Spyware Doctor
* Spyware Fighter

# Backdoors
* The backdoor attack is using any malware or technology to gain inauthorized access to any application or system by bypassing all the security measures.
* Backdoor allows attackers to quitely get into the system by bypassing security protocols and gain administrative acsess.
* After gaining admin access the cyber attackers can perform various task likje:
    * Hack the devices
    * Steal sensitive data
    * Chnaging entiore settings of the system

## Type of Backdoors
1. Administrative Backdoor
* Some times software developers intentionally leave a backdoor into the software program so that in case of future or error they can easily reach software code and solve the issue without any authentication .
* Through such backdoors are only knoiwn to developers, a skillful hacker can silently use it for malicious purpose.
* So  administrative Backdoors can a type of loophole in the program.

2. Malicios Backdoor
* Malicious backdoors are the backdoors installed on the system by cyber criminals using malware programs like trozon horses
* They are specially designed to perform malicious task.
* Troxzen horses apperarsto useful proframs but once attacker tricks the user for installing them they can reach root of thhe system and install backdoor.

## Why backdoors are dangerous
* Backdoors can be gateway for danagerous programs like trozon horses, ransomware, spyware, virus, worms etc.
* Backdoors are the best medius to conduct DDoS Attack.
* Using backdoor , hackers can modify sensitive system settings like admin password and other.
* Using backdoor user can steal sensitive information like account number password etc.

# Buffer and Buffer Overflow
* A buffer is a temporary data storage area with limited storage capacity.
* A buffer is typically area in the memory that is used to transfer data from one location to another location.
* Buffer are basically allocated in RAM to the processes. When any program is extecuted it is loaded into RAM and some memory is temporarily allocated to the program called Buffer.

## Buffer overflow
* Buffer overflow is an attack that occurs when the amount of data that is submitted is larger then the buffer.
* for example in C we create array of 5 size.
* If the user enter more then 5 it will override the data stored in memory further.

## How to protact against buffer overflow
* Basically the type of attack is possible due to poorly written application code or operating system code.
* To protact against Buffer overflow attack programmmer as well as organization need to ensure:-
    1. Programers should properly test/handle all the overflow conditions.
    2. Organization should ensure all the operationg system and applications are updated with latest updates, service packs and patches.
*
## How attacker use Buffer overflow attack
* Buffer overflow attacks can result in 
    1. Injection of malicious code.
    2. Denial of services Attack (DoS)
    3. SQL injection

* Attackers can take the advantage of this phenomenon by submitting too much data, which may cause errors and in some case enable attackers to execute malicious code in the system.

* The example is when a program ask for a phone number instead of entering 10 digits needed in the software, attacker sends 10000 digits followed by command to execute malicious code, becouse the software program does not have proper error handling it exexutes the command.

* Sometimes the attacker can crash the system and arruse DoS.

# DoS and DDoS Attack
* Denial of Service attacks are the major threat to the systems connected to the internet. Specially for e-commerce, financial services, and govt service.
* Computer Network majorly works on client server archeitecture. There are number of clients sending request to the same server.
* Serrver offers various services like HTTP or FtP (File Transfer Protocol) with which client can interact to or share information.
* When server cannot respond to client request DoS condition arries disruption in sending information or communication.
* The network can only send certain amount of data at a time Any data exeed network bandwidth will not reach the destination.

2 ways atacker can force DoS condition

1. Fooding :- 
* In this attack continuously flood unwanted requtest/traffic to the target server and consumes all tthe available bandwith. In such setuation the request from legimate user will not reach the server 
* Attacker use UDP(User Datagram Protocol),ICMP(Internet Control Message Protocol), and TCP(Transmission Control Protocol) to flood the target server.
* One Famous Technique attacker use is SYN Flood . In this attacker tranmits large number of TCP SYN packets to the target machine and initial TCP handshake.
* The attacker sends the conection request but does not sent acknowlegment back to server.
* The server waits for Acknowladgement thst attacker never sends and session remain open and server not able to accept further request from legimate user.

2. Resource Starvation
* Resource Starvation means overutilization of resources so that they are not vailable to use. This occurs when there is overutilization of system resources such as CPU, memory etc can cause system to fail.
* Network devices such as firewall, riuters , switch can also fails which results in DoS condition.
* Sometimes server can itself goes into DoS condition if its 100% CPU is used and serrver is incable of responding to further requests.

3. Slowlories
* Where attacker sends HTTP Get request with partials headers to apache web server. The server will wait for attacker to send rest of http headers but the attacker never sends complete headers , it only sends fake headers to server to make it waiting.
* In this way server keeps onb waiting and DoS condition arrives.

# Distributed Denial of Service(DDoS Attack)
* A distributed denial of service attack is the subclass of senial of service attack.
* A Distributed Denial of Service Attack involver multiple connection online devices/computer collective known as botnet, ehich is used to flood target site with fake traffic.
* DDoS attacks also aims to make website or server unavailable for legitimatye users. 

# Phishing
* The term phishing refers to an attacks using mail programs to tricks web that can be usd for criminal purposes.
* In general, hacker contuct phishing attacks by using email messages that looks to appear as through they come from a genuine source like post office, a bank or online service. Attackers can also use text messages, phone calls instant messaging.
* The most common Example is asking user to update his accounbt or change his password for security reasones.
* Cyber criminals know that organizatons and Internet Service Providers use anti spam detection Software and taken preventive measures such as Blocking some IP address. Then criminals keep their own adjustments. They invented new methods to byPass detaction tools.

# Phishing Techniques
1. Social Engineering Phishing Techniques
* Social Engineering is a kind of fraud which takes the advantage of human error to gain unauthorised access or sensitive data.
* People are more vulnerable to social engineering then technolgy attack, As it is easier to fix technical error but difficult to fix human flaws/ error.
* Social Engineering takes the adsvantage of hume phychology as human are contolled by strong emotions such as Greed, Fear curosity etc.
* There is 3 social engineering phishing
    * Deceptive Phishing:
        * In Deceptive Phishing attackers sends fake emails which mimic the emails of reputable source or business.
        * Deceptive phishing is when a customer receives fake email from the bank asking them to click the link and check their account information. This Kind of phishing technique is also calledf as brand impersonation.
        * The top 5 Subject lines of the emails are -"URGENT", "REQUEST", "IMPORTANT", "PAYMENT", and "ATTENTION". To get the reaction attacker send email to large number of audience.

    * Spear Phishing:
        * Spear phishing targets speific organization and individuals as opposed to random people.
        * To make the email appear more authentic, attacker gathers information about target audience from various source such as social networking sites , bloges and forums and gain their personal as well as professional information.
        * Because the information contained in email are highly authentic and real it is extremely difficult to detect spear phishing.

    * Whaling Phishing
        * In this phishing attack, attacker targets high profile employee such as CEO or Cheif financial officer. This attack is also call as CEO Fraud.

2. Man In Middle Phishing Technique
* In MIM technique, attecker puts himself between two communicating parties without their knowledge. All the traffic between two parties are routed to the attacker.
* Attacker can now monitor all the information passing through the network and gain sensitive data.

3. Proxy Based Phishing
* A proxy act as intermediary between the web browser and server.
* The main function of proxy includes :
    * Caching website content to speed up the response time.
    * Restricting access to some inappriate  website in the office or campus.
* If the attacker is successful in attacking these proxies then they can easily stral username and password when forms are submitted or to hijack already authenticated sessions by using victims cookies.

4. Search Engine Phishing
* Search Engine Phishing is also known as SEO Poisoning or SEO Trozon is where attackers creates a website with the intension of stealing individual's personal information and work to bring this website a top hit on search engine.
* Attacker then steal personal information when interact with site and steal sensitive data.

# Attack on wireless network
* Wireless network are one of the integral part of how we conduct out bussiness today. Wireless networks are not required to setup wires or hardware.
* wireless technologies are convinient , fast and less expensive, on the other hand it is more vulnerable to attack.
* These attacks are normally carried out get the targeted information shared over the network.

## types of wireless attack
1. Packet Sniffing
* In wireless network the information is sent from one device to another device in the form of packets. As these packes are sent through internet it is very easy to capture them.
* In wireless network a lot of packets are sent in clear text formate using protocols like HTTP,FTP,SMTP,etc.
* i.e there is not encryption technique used if the attcker captures these information they can easily read them
* Using the free available tools like wireshark, anyone can easily read data in plain text . As a result any one with malicious intension can steal password and other sensitive data.
* Encryption data can also be capture but it wont be easy for attacker to decypher it . so it unable to use them.

2. Rogue Access Point
* A rouge access point is basically a access point added to one's network without their knowlegde.
* It is an unauthorized access point added by any attacker or ever misinformed employee.
* These access pont can add a very huge amount of security concers . Rouge access point can act asd a kind of backdoor for attackers.
* Moreover rogue access point can make entire network vulnerable to DoS attack and packet capture
* Organizations should use Network access Control and Network access Protocol or introduce authentication process to protect themself.

3. Password theft
* When we use public wifi or public network to connect to internet password stealing become very easy for attacker.
* While using public wireless network, if user enters password and send it over the network and the site does not use SSL or TLS security, that password will br transmitted in the form of plan text without any encryption, and it can be easily read by attacker.

4. Man in Middle attack
* In man in the middle attack(MIM or MITM attack) attacker puts himself between two communicating parties without their knowledge.
* All the traffic between two parties are routed to the attacker.
* Because the attacker can inject himself between communicatin parties the attacker has the ability to control content of the information .
The attacker can read or even change the content before sending (if encyption is not used) and even if encryption is used the attacker can still deny or dely communications.
* There are two type of MIM attack
    * Active session attack:The attacker disable client computer ability to communicate with the service. If the attack is successful, the attacker will be able to perform any opration.
    * Passive session attack:- The attacker quitely monitor all data passing through the session. As a resuklt attacker can collect all the sensitive data passing through the network.
* Jamming also known as interference also to disrupt the network.
* Jamming attacks can cause DoS or either transmission or reception functionality