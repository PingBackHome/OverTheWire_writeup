# Over The Wire CTF

https://overthewire.org/wargames

## Level 0

> ssh bandit0@bandit.labs.overthewire.org\
> password: bandit0

<img width="550" alt="image" src="https://user-images.githubusercontent.com/115549820/201640255-ff548894-3f98-45bc-99dc-2690a12021e4.png">

> README: NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL


## Level 1 -> 2

'The password for the next level is stored in a file called - located in the home directory'

> ssh bandit1@bandit.labs.overthewire.org\
> password: NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201643227-58d6af5a-5d85-4c3d-9661-91cd1aba92de.png">

> -: rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi


## Level 2 -> 3

'The password for the next level is stored in a file called spaces in this filename located in the home directory'

> ssh bandit2@bandit.labs.overthewire.org\
> password: rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201643752-d7862b65-8958-4198-980d-8e38cb71bfa6.png">

> 'Spaces in this filename': aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG


## Level 3 -> 4

'The password for the next level is stored in a hidden file in the inhere directory.'

> ssh bandit3@bandit.labs.overthewire.org\
> password: aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201644359-1d89eec4-45ff-4557-adab-8ef44bf85024.png">

> .hidden: 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe


## Level 4 -> 5

'The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.'

> ssh bandit4@bandit.labs.overthewire.org\
> password: 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201645370-c1278e38-4efa-4a0e-9bbc-e694c142169f.png">

> -file07: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR


## Level 5 -> 6

'The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:'

> ssh bandit5@bandit.labs.overthewire.org\
> password: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

<img width="305" alt="image" src="https://user-images.githubusercontent.com/115549820/201647323-52b76e93-560c-4229-9283-7a87ed26ca7b.png">

> inhere/maybehere07/.file2: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU


## Level 6 -> 7

'The password for the next level is stored somewhere on the server and has all of the following properties:'

> ssh bandit6@bandit.labs.overthewire.org\
> password: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201677282-5cd3c8b9-b0d8-4e69-98d7-fcc86c5c946f.png">

> /var/lib/dpkg/info/bandit7.password: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S


## Level 7 -> 8

'The password for the next level is stored in the file data.txt next to the word millionth'

> ssh bandit7@bandit.labs.overthewire.org\
> password: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201678794-bc769a5e-fa4c-4cfa-acad-b954e2e6eb04.png">

> data.txt: TESKZC0XvTetK0S9xNwm25STk5iWrBvP


## Level 8 -> 9

'The password for the next level is stored in the file data.txt and is the only line of text that occurs only once'

> ssh bandit8@bandit.labs.overthewire.org\
> password: TESKZC0XvTetK0S9xNwm25STk5iWrBvP

<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201682716-59f07a5f-6c6c-4a1b-994c-b824018031ff.png">
<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201682760-e64e9bac-4841-4553-87b0-0d4e6a72f06a.png">

> data.txt: EN632PlfYiZbn3PhVK3XOGSlNInNE00t


## Level 9 -> 10

'The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.'

> ssh bandit9@bandit.labs.overthewire.org\
> password: EN632PlfYiZbn3PhVK3XOGSlNInNE00t

<img width="300" alt="image" src="https://user-images.githubusercontent.com/115549820/201683519-3fa1440e-269e-46b0-bf2a-f32d737d5aba.png">

> data.txt: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s


## Level 10 -> 11

'The password for the next level is stored in the file data.txt, which contains base64 encoded data'

> ssh bandit10@bandit.labs.overthewire.org\
> password: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

<img width="413" alt="image" src="https://user-images.githubusercontent.com/115549820/201686500-212eb643-f27b-425b-b104-798ee94ae656.png">

> data.txt: The password is 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM


## Level 11 -> 12

'The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions'

> ssh bandit11@bandit.labs.overthewire.org\
> 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

<img width="413" alt="image" src="https://user-images.githubusercontent.com/115549820/201687991-5dfe550d-78ae-45b8-967c-6d2a642a00c1.png">

> data.txt: The password is JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv


## Level 12 -> 13

'The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work using mkdir. For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv (read the manpages!)'

> ssh bandit12@bandit.labs.overthewire.org\
> password: JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

<img width="413" alt="image" src="https://user-images.githubusercontent.com/115549820/201691684-b6a91c15-5347-4ed0-b455-5f0d3d5d3e5e.png">

> data9: The password is wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw


## Level 13 -> 14

'The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on'

> ssh bandit13@bandit.labs.overthewire.org\
> password: wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw

<img width="529" alt="image" src="https://user-images.githubusercontent.com/115549820/201693460-8d4cad88-e868-471e-b83f-05d5da4671c6.png">

<img width="306" alt="image" src="https://user-images.githubusercontent.com/115549820/201693622-ca35e9ae-7692-49a8-b90b-2a405cbc71ee.png">

> bandit14: fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq


## Level 14 -> 15

'The password for the next level can be retrieved by submitting the password of the current level to port 30000 on localhost.'

> ssh bandit14@bandit.labs.overthewire.org\
> password: fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq

<img width="515" alt="image" src="https://user-images.githubusercontent.com/115549820/201694717-3b9b79af-e5c3-4e0a-8ea3-b74ea71f36c6.png">

> bandit15: jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt


## Level 15 -> 16

'The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL encryption.'

> ssh bandit15@bandit.labs.overthewire.org\
> password: jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt

<img width="670" alt="image" src="https://user-images.githubusercontent.com/115549820/201870736-b79c08e5-8fe5-4eb8-8bd9-bb7e7484531b.png">

> bandit16: JQttfApK4SeyHwDlI9SXGR50qclOAil1


## Level 16 -> 17

'The credentials for the next level can be retrieved by submitting the password of the current level to a port on localhost in the range 31000 to 32000. First find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.'

> ssh bandit16@bandit.labs.overthewire.org\
> password: JQttfApK4SeyHwDlI9SXGR50qclOAil1

<img width="401" alt="image" src="https://user-images.githubusercontent.com/115549820/201895240-fee83c41-9b45-455f-85e1-8eb5047abb5a.png">

<img width="673" alt="image" src="https://user-images.githubusercontent.com/115549820/201897243-fabd998d-e5c8-4464-b976-64d721dbd2cb.png">

> bandit17: privatekey


## Level 17 -> 18

'There are 2 files in the homedirectory: passwords.old and passwords.new. The password for the next level is in passwords.new and is the only line that has been changed between passwords.old and passwords.new'

> ssh -i id_rsa bandit17@bandit.labs.overthewire.org -p 2220\
> password: privatekey

<img width="335" alt="image" src="https://user-images.githubusercontent.com/115549820/201899425-b58ba9d0-9974-4f01-a649-24e7cf7583f0.png">

> bandit18: hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg


## Level 18 -> 19

'The password for the next level is stored in a file readme in the homedirectory. Unfortunately, someone has modified .bashrc to log you out when you log in with SSH.'

> ssh bandit18@bandit.labs.overthewire.org -p 2220\
> password: hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg

<img width="428" alt="image" src="https://user-images.githubusercontent.com/115549820/201901189-95eb83c2-3d9a-44ee-b7ec-fe4e7d5e984d.png">

> bandit19: awhqfNnAbc1naukrpqDYcF95h7HoMTrC


## Level 19 -> 20

'To gain access to the next level, you should use the setuid binary in the homedirectory. Execute it without arguments to find out how to use it. The password for this level can be found in the usual place (/etc/bandit_pass), after you have used the setuid binary.'

> ssh bandit19@bandit.labs.overthewire.org\
> password: awhqfNnAbc1naukrpqDYcF95h7HoMTrC

<img width="383" alt="image" src="https://user-images.githubusercontent.com/115549820/201906741-5955d51f-b45e-459c-b672-dbf930d9b0ca.png">

> bandit20: VxCazJaVykI6W36BkBU0mJTCM8rR95XT

## Level 20 -> 21

'There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).'

> ssh bandit20@bandit.labs.overthewire.org\
> password: VxCazJaVykI6W36BkBU0mJTCM8rR95XT

<img width="520" alt="image" src="https://user-images.githubusercontent.com/115549820/201915634-b3e5512a-d3e8-49b8-ae7c-3b5eefa50c5d.png">

> bandit21: NvEJF7oVjkddltPSrdKEFOllh9V1IBcq


## Level 21 -> 22

'A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.'

> ssh bandit20@bandit.labs.overthewire.org\
> password: NvEJF7oVjkddltPSrdKEFOllh9V1IBcq

<img width="600" alt="image" src="https://user-images.githubusercontent.com/115549820/201917608-dc957ece-546b-47f8-ad0a-3f28c787617e.png">

> bandit22: WdDozAdTM2z9DiFEQ2mGlwngMfj4EZff


## Level 22 -> 23

'A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.'

> ssh bandit22@bandit.labs.overthewire.org\
> password: WdDozAdTM2z9DiFEQ2mGlwngMfj4EZff

<img width="600" alt="image" src="https://user-images.githubusercontent.com/115549820/201920583-bc9c4c48-c779-47c3-a1ca-72fdc8c248fa.png">

> bandit23: QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G


## Level 23 -> 24

'A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.'

> ssh bandit23@bandit.labs.overthewire.org\
> password: QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G
>
<img width="338" alt="image" src="https://user-images.githubusercontent.com/115549820/201941456-c38b7e58-1c42-470b-a0e4-49d2e5b85f4b.png">

<img width="338" alt="image" src="https://user-images.githubusercontent.com/115549820/201941680-3df934fa-8833-4de1-9298-1b495f6f1b5b.png">

> bandit24: VAfGXJ1PBSsPSnvsjI8p759leLZ9GGar


## Level 24 -> 25

'A daemon is listening on port 30002 and will give you the password for bandit25 if given the password for bandit24 and a secret numeric 4-digit pincode. There is no way to retrieve the pincode except by going through all of the 10000 combinations, called brute-forcing.'

> ssh bandit24@bandit.labs.overthewire.org
> password: VAfGXJ1PBSsPSnvsjI8p759leLZ9GGar

<img width="401" alt="image" src="https://user-images.githubusercontent.com/115549820/201944952-177ec59d-6e77-4a61-8bd2-22bdb1e27afe.png">

<img width="401" alt="image" src="https://user-images.githubusercontent.com/115549820/201944814-5970c482-58e2-4ee2-94a8-e3caf01545f7.png">

> bandit25:p7TaowMYrmu23Ol8hiZh9UvD0O9hpx8d



