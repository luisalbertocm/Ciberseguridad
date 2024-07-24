# CIBERSECURITY


FIRTS START WITH CTF BEGINNERS


![Screenshot_2024-07-24_01_08_21](https://github.com/user-attachments/assets/c7d0e0bb-0e35-4bba-9b99-ada138e5e4c8)

The first exercise is blender

![Screenshot_2024-07-24_01_15_20](https://github.com/user-attachments/assets/b6f4d12f-e3b4-43e0-8bab-dcbd3f8e0b32)

Enter in the URL provided in the page http://10.0.41.1:1337/


This is the website
![Screenshot_2024-07-24_01_24_27](https://github.com/user-attachments/assets/c7944a62-7ed0-4bb6-b429-7da1147652d6)

You only need to add robots.txt to the URL provided
http://10.0.41.1:1337/robots.txt and you will see the first flag

![Screenshot_2024-07-24_01_29_07](https://github.com/user-attachments/assets/ddf7218a-1391-4894-b64c-7848a4833a94)

```txt
ETSCTF_ae1764e05e046f3770ac7b396c4ab0a2
```
If you check the site, you will see the directory 
/nogooglebot/
Check the new site with this directory 
http://10.0.41.1:1337/nogooglebot/

Then open the source page and you will see the other flag

![Screenshot_2024-07-24_01_36_33](https://github.com/user-attachments/assets/1e8c2363-38e5-434f-996e-cfbe8a7d3103)

```txt
ETSCTF_e79422930da899e5634d7f9da9c601a2
```



idiotr
![Screenshot_2024-07-24_01_38_35](https://github.com/user-attachments/assets/93756503-104b-4cb2-b90f-b524e2da8753)

Enter in the URL provided in the page http://10.0.41.2:1337/

![Screenshot_2024-07-24_01_40_58](https://github.com/user-attachments/assets/29e05bee-d608-45fc-aa20-29b3e9d252d1)

If you check the url when you click in the bottom Home About Blogs Secret you will that the Url changes and with this you find the first clue 

![Screenshot_2024-07-24_01_45_40](https://github.com/user-attachments/assets/f296020e-5230-4ad0-bae6-958f9109b394)

![Screenshot_2024-07-24_01_45_49](https://github.com/user-attachments/assets/084e5dca-6c8a-4aaf-8f7b-ed9b880c95e6)


With this try to change the URL with other numbers  

For example with http://10.0.41.2:1337/?id=1

![Screenshot_2024-07-24_01_49_56](https://github.com/user-attachments/assets/ff8eb7c8-265f-4a02-99b8-cd44391f7e60)

you will see the flag

```txt
ETSCTF_764762092a32a29c2694d8c67209e5ce
```



POSTOFFICE

![Screenshot_2024-07-24_01_52_06](https://github.com/user-attachments/assets/b9c67b86-84dd-49f4-91fe-022cd1b1bdce)

Enter in the URL provided in the page  http://10.0.41.3:1337/

![Screenshot_2024-07-24_01_54_01](https://github.com/user-attachments/assets/f75d0a78-f084-4bfa-8b03-fc9e05294314)

The clue here is the name of the challenge "Post" you need to use the tool curl with -XPOST to send an HTTP POST request to the server located

```txt
curl -XPOST http://10.0.41.3:1337 
```
![Screenshot_2024-07-24_02_00_02](https://github.com/user-attachments/assets/7704b5a0-64f9-4494-8685-7f6426346773)

And you will see the flag

```txt
ETSCTF_4928fe50c7d8d80eba74e908dd1594de
```



HEADOFFICE

![Screenshot_2024-07-24_02_03_16](https://github.com/user-attachments/assets/82e7b60b-a00a-4dca-a1d7-0aecebdbf170)

The clue here is the same of the past challenge "POSTOFFICE" the diference here is that you need to use the HEAD 

```txt
curl -I http://10.0.41.4:1337/  -XHEAD
```

![Screenshot_2024-07-24_02_18_54](https://github.com/user-attachments/assets/5d83194d-45b6-4c5d-a866-68a8195e1f2f)

And you will see the flag!


```txt
ETSCTF_138cdb84157cf6e761c48072d034d4d0
```



























