# Corridor-Walkthrough

# Port Scaning 
I used nmap to try to find open ports there was no open ports execpt for 80 http 
![nmap](https://user-images.githubusercontent.com/57154996/193298059-1532dac9-ee95-4b95-aafd-e39b41674585.PNG)

# Directory busting
Unfortunately dirb and gobuster didn't provide me with any information, so I headed directly to the main page of their web server
![dirb](https://user-images.githubusercontent.com/57154996/193301572-9516450b-178d-4abc-a349-510a9fba9055.PNG)

# Hash Decryption 
At this point I didn't find any thing useful, just a photo of a corridor that contains 13 doors
![hall](https://user-images.githubusercontent.com/57154996/193302454-553d414c-4085-4386-bd92-cb23fd197b10.PNG)

until I noticed that the doors are clickable, each door redirects you to the same photo of an empty room but they are different directories
![url](https://user-images.githubusercontent.com/57154996/193303132-907713d3-ce41-48a6-973f-875c2fe44607.PNG)

Ummmmmm!! these directories URL endpoint seems familiar , are they md5 hashes?
![MD5](https://user-images.githubusercontent.com/57154996/193304224-4472d489-d4ae-4ced-b2e8-a26f920c2afc.PNG)

Nice, now we can decrypt the directory name of each door , you will find that the doors are numbered ascendingly from 1 to 13 

# Flag

