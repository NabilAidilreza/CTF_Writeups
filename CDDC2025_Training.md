# CDDC 2025 Training Challenges

[10-20 Minute Read] Team NTU/SMU Unzipped

Team Members: Stickybit, ...

CTF Hosted by dsta.gov.sg/CDDC (https://www.dsta.gov.sg/brainhack)

```
Dive into the cyberspace and uncover what it takes to defend against digital threats

Participate in a Jeopardy-style Capture-The-Flag (CTF) competition integrated with cybersecurity training.

Engage in hands-on challenges while mastering essential skills to defend against online threats.

Elevate your knowledge through immersive experiences and be equipped to protect against cyberattacks.
```

## Overview

```
Challenge                                     Category       Flag
[CyberSec-02] Katze                            Basics        CDDC2025{netcat_challenge_success}
[CyberSec-03] 101                              Basics        CDDC2025{hidden_in_binary}
[CyberSec-04] Our secret                       Basics        CDDC2025{Kap00vv_congratulations}
[CyberSec-05] Silver dime                      Basics        CDDC2025{cr4ck3d_m3_fast}
[CyberSec-06] Super calc                       Basics        CDDC2025{5uP3r_p0W3r3d_c4lCuL4t0r}

[LinuxFunds-02] Reversed hidden flag           Basics        CDDC2025{1t_W45_ju5t_h1dd3n}
[LinuxFunds-03] random fruit                   Basics        CDDC2025{this_is_Random_fruits}
[LinuxFunds-04] Find File                      Basics        CDDC2025{Y0u_F1nd_Me56}
[LinuxFunds-05] Unknown Program                Basics        CDDC2025{W0w_Y0U_F0UnD_1T}

[WindowsFunds-02] fast console flag            Basics        CDDC2025{pR1nt_4nD_g0}
[WindowsFunds-03] traces                       Basics        CDDC2025{ReG_hAcK}
[WindowsFunds-04] is it javascript?            Basics        CDDC2025{YES_1t_1S_JAVA2CR1pt}
[WindowsFunds-05] My Startup Program           Basics        CDDC2025{W3ll_d0n3_Y0u_F0un[)_17}
[WindowsFunds-06] animal farm                  Basics        CDDC2025{aNiMa1_FaRm_S2CrEt}
[WindowsFunds-08] Gentleman's History          Basics        CDDC2025{d08df2b8de382d42c60e116368c3ee799e00f286}
[WindowsFunds-09] Excel hidden flag            Basics        CDDC2025{3xcEl_H1dden_fl4g}

[NetworkingFunds-02] F4K3                      Basics        CDDC2025{Sometimes_what_you_see_may_not_be_all_that_you_see}
[NetworkingFunds-03] HTTP                      Basics        CDDC2025{I_use_a_password_of_more_than_10_digits!}
[NetworkingFunds-04] ICMP                      Basics        CDDC2025{I_Love_ICMP}
[NetworkingFunds-05] TELNET                    Basics        CDDC2025{Use_SSH_Instead_Of_Telnet}

[MalwareFunds-02] INJECTOR                     Basics        CDDC2025{You_Found_Me_Hiding?}
[MalwareFunds-03] Script_Drop                  Basics        CDDC2025{Malware_Can_Be_Disguised_As_JavaScript}
[MalwareFunds-04] Doc_drop                     Basics        CDDC2025{You_Have_Learned_To_Dropper}
[MalwareFunds-05] Encoded_Code                 Basics        CDDC2025{Did_You_Even_Know_This?}

[CryptoFunds-02] secretextus                   Basics        CDDC2025{cl4ssic_ciph3rs_n3ver_g3t_0ld}
[CryptoFunds-03] confusion                     Basics        CDDC2025{frequency_analysis_attack_on_substitution_cipher}
[CryptoFunds-04] ezRSA                         Basics        CDDC2025{g00d_j0b_0n_5olv1ng_RSA}
[CryptoFunds-05] RSA-uth                       Basics        CDDC2025{it5_0nly_m3_wh0_kn0w_my_priv4te_k3y_ther3fore_1ts_m3}

[WebSecurityFunds-02] Are you robot            Basics        CDDC2025{You_can_find_the_page_that_the_administrator_wants_to_hide}
[WebSecurityFunds-03] COOKIE                   Basics        CDDC2025{A_VERY_DELICIOUS_COOKIE}
[WebSecurityFunds-04] Automation               Basics        CDDC2025{Well_done_collecting_everything}
[WebSecurityFunds-05] (["_"])                  Basics        CDDC2025{Who_the_hell_made_this..}

[CWEFunds-02] What_is_the_vuln                 Basics        CDDC2025{0n-Chip_Debug_and_Test_Interface_With_Impr0per_Access_C0ntr0l}
[CWEFunds-03] What_Weakness                    Basics        CDDC2025{Sensitive_Information_in_Hardware_Pin_State}
[CWEFunds-04] SHADOWWRITE                      Basics        CDDC2025{NOW_Attacker_can_not_Write_2_Shadow_Register}
[CWEFunds-05] JTAG_MADNESS                     Basics        CDDC2025{jtag_access_granted_over_jtag}
[CWEFunds-06] Heaven's Vault                   Basics        CDDC2025{1_L1ST3N3D_T0_Y0UR_C0D3_T1CK1NG}
```

# Template
## TITLE

**Challenge**

?

**Solution**

?

**Flag**

```
THE FLAG
```

## [CyberSec-02] Katze

**Challenge**
Attention please!
Calling all brainhackers to communicate with below port now!

52.76.13.43 8085

**Solution**

Connect to given ip:addr using netcat

Answer the qns 

SSH => 22

SMTP => 25

HTTPS => 443

**Flag**

```
CDDC2025{netcat_challenge_success}
```

## [CyberSec-03] 101

**Challenge**
What is this?!?!

A random number?

Why is it only 1 and 0? How do I read this?

**Solution**

It is a binary string.

Convert binary to text (https://www.rapidtables.com/convert/number/binary-to-ascii.html)

**Flag**

```
CDDC2025{hidden_in_binary}
```

## [CyberSec-04] Our secret

**Challenge**

Check the image and...

Kapow!!!

**Solution**

Put through Aperisolve

Steghide function detected a flag.txt

**Flag**

```
CDDC2025{Kap00vv_congratulations}
```

## [CyberSec-05] Silver dime

**Challenge**

I found something!

Bit strange, a zip file huh..

Brainhacker, please help me, I will share some dimes :)

**Solution**

Recover zip password (https://www.lostmypass.com/file-types/zip/) OR use john the ripper
Get flag in the zip file.

**Flag**

```
CDDC2025{cr4ck3d_m3_fast}
```

## [CyberSec-06] Super calc

**Challenge**

You need a super calculator to solve this! 

nc 52.76.13.43 8084

**Solution**

Use Python socket to solve the questions.

**Flag**

```
CDDC2025{5uP3r_p0W3r3d_c4lCuL4t0r}
```

## [LinuxFunds-02] Reversed hidden flag

**Challenge**

Find the hidden flag fragment and complete the flag!

nc 52.76.13.43 8086

**Solution**

Check around for flag with ls -l commands

You will find 3 flag.txt, combine and reverse string for the flag.

**Flag**

```
CDDC2025{1t_W45_ju5t_h1dd3n}
```
## [LinuxFunds-03] random fruit 

**Challenge**

Look for the flags through the executable!

nc 52.76.13.43 8087

**Solution**

ls -a
cat fruits

**Flag**

```
CDDC2025{this_is_Random_fruits}
```
## [LinuxFunds-04] Find File

**Challenge**

We found a desktop left in one of Cypher's lookouts.

On the desktop, there are flag-related files in the 'flag' folder.

One of the files have a different file type.

Can you find what it is?

nc 52.76.13.43 8088

**Solution**

ls -al Desktop/*/* => Spotted a file with different size than the rest

**Flag**

```
CDDC2025{Y0u_F1nd_Me56}
```
## [LinuxFunds-05] Unknown Program

**Challenge**

The desktop from Cypher's lookout has an unknown software installed.

Default password of it seems to be exposed.

Can you find it?

nc 52.76.13.43 8089

**Solution**

Concept: /opt is where installed programs usually are

in /opt => Spotted "cat identify_flag.sh" in /var/identify

Navigate to path and find a "Readme.md"

**Flag**

```
CDDC2025{W0w_Y0U_F0UnD_1T}
```
## [WindowsFunds-02] fast console flag

**Challenge**

Run the file and check the flag that prints on the console.

It goes super fast, so you will have to be even faster!

**Solution**

Simply run exe file on cmd prompt to see output.

**Flag**

```
CDDC2025{pR1nt_4nD_g0}
```
## [WindowsFunds-03] traces

**Challenge**

Programs do not print anything, but they leave important information somewhere in the system.

In the Windows system, find the area where the user's software settings are saved!

File's password : reg

**Solution**

Unzip folder to find two exe files.
Run hidden_reg_flag.exe.

**Flag**

```
CDDC2025{ReG_hAcK}
```
## [WindowsFunds-04] is it javascript?

**Challenge**

Cypher hid a flag value in this file.

We might need to look into it.

**Solution**

jsf**k language => https://www.dcode.fr/jsfuck-language

**Flag**

```
CDDC2025{YES_1t_1S_JAVA2CR1pt}
```
## [WindowsFunds-05] My Startup Program

**Challenge**

A part of registry file has been converted to a text file.

I hear that a startup program is configured.

Do you mind looking for it?

**Solution**

Concept: Whats the reg key for startup files?
HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Run
Will find a exe with flag name.

**Flag**

```
CDDC2025{W3ll_d0n3_Y0u_F0un[)_17}
```
## [WindowsFunds-06] animal farm

**Challenge**

There is a set of suspicious files.

What is Cypher doing with a bunch of animal pictures?

Let's find a lead (or a flag) in the pictures.

**Solution**

Multiple pngs => Suspiciously huge file => Tiger.png

Aperisolve and found traces of data from binwalk.

Flag found in data.

**Flag**

```
CDDC2025{aNiMa1_FaRm_S2CrEt}
```
## [WindowsFunds-08] Gentleman's History

**Challenge**

A wise man once said...

"A true gentleman never asks about another man's salary, love life, or browser history."

So, instead of asking, I need you to peek into THIS history. :P

**Solution**

It is a sqlite3 db file.
Check under "urls" table => Found CDDC website visits
Flag param found in link.

**Flag**

```
CDDC2025{d08df2b8de382d42c60e116368c3ee799e00f286}
```
## [WindowsFunds-09] Excel hidden flag

**Challenge**

Cypher hid a flag inside the Excel file!

Find the flag!

**Solution**

Concept: Can change Excel to zip format to see base files
Flag found in sharedStrings.xml

**Flag**

```
CDDC2025{3xcEl_H1dden_fl4g}
```
## [NetworkingFunds-02] F4K3

**Challenge**

Cheating the other person's common sense and eyes is also part of security. Don't believe what you see as it is.

**Solution**

Use Wireshark for pcap analysis.
Filter HTTP => Flag in url

**Flag**

```
CDDC2025{Sometimes_what_you_see_may_not_be_all_that_you_see}
```
## [NetworkingFunds-03] HTTP

**Challenge**

Destination tried to log in from a web page using HTTP. Find your ID and password and get the flag

**Solution**

Filter by HTTP => login.php found
Follow TCP Stream => Details found

**Flag**

```
CDDC2025{I_use_a_password_of_more_than_10_digits!}
```
## [NetworkingFunds-04] ICMP

**Challenge**

ICMP is such a great protocol

**Solution**

Filter by ICMP
Follow stream to see raw data being transmitted.
Form the flag.

**Flag**

```
CDDC2025{I_Love_ICMP}
```
## [NetworkingFunds-05] TELNET

**Challenge**

Telnet is very, very, very vulnerable

**Solution**

Filter by Telnet
Follow stream
Flag found in conversation.

**Flag**

```
CDDC2025{Use_SSH_Instead_Of_Telnet}
```
Malware to CWE TBC
