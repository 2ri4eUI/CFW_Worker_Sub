## IP API FOR CFW BOT

in this repo in will instruct how to create your own backend for CFW-BOT subscription workers

you can install bot from this repo :
https://github.com/2ri4eUI/CFW-BOT

##Tutorial 

1. register for a free account on in https://fofa.info. you can use your gmail, just  first change the language to english 
![image](https://github.com/2ri4eUI/CFW_Worker_Sub/assets/139592104/46796f15-8d68-4fef-9ebc-6be2984edce2)

2. search for ip that are on cloudflare server, use this query example

```bash
server=="cloudflare" && port=="443" && country=="NL" && city=="Amsterdam"
```
you can use any desired port, country and city , there are infinite option 
and there are other query you can use as well, so far this is the one i get more cleaned ip with 

3. change the ip view to last month, this increase your change to find more usable ips

4. download results of your search,  your download will be in personal center [here](https://en.fofa.info/userInfo/downloadRecords)

![image](https://github.com/2ri4eUI/CFW_Worker_Sub/assets/139592104/94ebe172-ddf7-4673-9529-c6f734d4b991)

6. copy the ip column of your downloaded csv file and use your desired cloudflare speed test tool to find suitble ips

## example of checking speed of cloudflare ips
1. i use this tool [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest), download it for your OS. 
2. copy ips that you downloaded in csv file in ip.txt file in Cloudflarespeedtest folder
3. open terminal and run ./CloudflareST.exe if you are using windows. for more info on how to use it read its document.

5. it show the working ips in terminal and will generate a result.csv file . use ip with best speed.
![image](https://github.com/2ri4eUI/CFW_Worker_Sub/assets/139592104/f8ff60fb-9b67-4e4e-947b-fa485d859f0b)

## Creating CFW subscription backend (IP_API)

1. for more detail about the CFW-BOT go [HERE](https://github.com/2ri4eUI/CFW-BOT)
2. create a text file in any web service you know that can provide you a public link. for purpose of this tutorial i use github.
3. create a .txt file with your desired name
4. use this format for adding ip
```bash
ip:port#name of your config
```
each ip should be in seperate line, you can use `ips.txt` file in this repo as guide
if you dont provide any port it will use 443 as default port

6. save file and get the raw link of your .txt file, just click on RAW on top of the file and copy its link from browser.
5. go to bot and select subscription ips button
   
   ![image](https://github.com/2ri4eUI/CFW_Worker_Sub/assets/139592104/88cbdc47-4035-4c40-83be-b1c8144258d0)

7. select change button and paste your file RAW link
   
   ![image](https://github.com/2ri4eUI/CFW_Worker_Sub/assets/139592104/434228b5-e677-4955-9d98-50cd8f3c7da8)

9. DONE🎉. from now on, every user that you create will have your NEW and UNIQUE backend in their subcription link.

## Changing Ips in users Subscriptions

To fetch updates in the IP_API backend on your sub link, simply update your subscription in your desired app (all app e.g:v2rayng or any other app you are using have this option). The changes typically reflect in the subscription link within 3-5 minutes. 



