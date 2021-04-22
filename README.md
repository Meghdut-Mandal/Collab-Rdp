

#  Collab-Rdp 

# If you wnat to use google collab instance with RDP then do the folowing step

## Open the notebook Click on below button

<a href="https://colab.research.google.com/github/Shubham2157/Collab-Rdp/blob/main/Colab_RDP.ipynb"><img src="https://image.freepik.com/free-vector/big-blue-now-open-button-sticker-door-3d-style_223622-319.jpg" width="200" height="200"></a>

This notebook will be open

![image](https://user-images.githubusercontent.com/50911878/115740249-4313b700-a3ac-11eb-95f6-c0ffc1fb5ff7.png)

## Step - 1 Connection

**In Right Corner Click on connect arrow**

![image](https://user-images.githubusercontent.com/50911878/115741913-cd104f80-a3ad-11eb-941d-64a8d5c98fcd.png)

 **After that you will see some options like**
 
 ![image](https://user-images.githubusercontent.com/50911878/115742562-67709300-a3ae-11eb-893d-198a454da4cf.png)
 
 **click on `connect to hosted runtime` which will allocate & connect to google cloud inctance**
---------

> You can skip above step and dirctly click on run button of create user cell all the above procees will be done automatically

## Step - 1-a User Creation

user and password are used for machine and will be needed if you lock the linux machine

![image](https://user-images.githubusercontent.com/50911878/115743896-b539cb00-a3af-11eb-92b7-1e82ab425f5e.png)

After you click on run button you will get a warning dilog box click on run anyway

![image](https://user-images.githubusercontent.com/50911878/115744541-490b9700-a3b0-11eb-8ea0-a7163594f85b.png)

now you will see user creation process will be started and after few seconds you will see a user is created successfully

![image](https://user-images.githubusercontent.com/50911878/115745108-c1725800-a3b0-11eb-934d-20c91f3cbca7.png)

## Step - 2 RDP conection using google remote desktop

visit this link 

<a href="https://remotedesktop.google.com/headless">![image](https://user-images.githubusercontent.com/50911878/115745857-74db4c80-a3b1-11eb-8993-d46254d82144.png)</a>


you will see install button in url tab before bookmark button 
click it to install in your desktop so that you do not have to open browser


![image](https://user-images.githubusercontent.com/50911878/115747446-e5cf3400-a3b2-11eb-9b82-bd11f5d0c908.png)



now you will see a icon in desktop 

![image](https://user-images.githubusercontent.com/50911878/115750697-1369ac80-a3b6-11eb-8abd-496ef5b9702f.png)

**open that**

you will see window like this 

![image](https://user-images.githubusercontent.com/50911878/115750899-46ac3b80-a3b6-11eb-8508-b92b61aab9f4.png)


## Step 3 - Authorization

click on begin button

![image](https://user-images.githubusercontent.com/50911878/115751173-8d9a3100-a3b6-11eb-830e-9fb29c04edb8.png)


then click on next 

![image](https://user-images.githubusercontent.com/50911878/115751414-cc2feb80-a3b6-11eb-8128-cb3e12327494.png)


then click on authorise

![image](https://user-images.githubusercontent.com/50911878/115751587-f2ee2200-a3b6-11eb-979c-9deade2bc7bf.png)


now google sign in dilog will pop up then select any one of account to authorise

![image](https://user-images.githubusercontent.com/50911878/115753047-5a58a180-a3b8-11eb-8f44-3262a83ed6ca.png)


**choose any one of the account**

after authentication some key will be genreted

![image](https://user-images.githubusercontent.com/50911878/115753256-9db31000-a3b8-11eb-8829-47d16ebd2308.png)

you have to copy key of Debian Linux

![image](https://user-images.githubusercontent.com/50911878/115753348-bcb1a200-a3b8-11eb-8c58-b29dbd61dcd1.png)

## Step - 4 Configuration 

Paste this key to crp text field in notebook

![image](https://user-images.githubusercontent.com/50911878/115753588-fda9b680-a3b8-11eb-809a-9f1602d494ef.png)

> **You Can change the `pin` if you want it will required in connecting with the inctance**

After that click run button of RDP cell then it will install some tools

![image](https://user-images.githubusercontent.com/50911878/115758065-5b8bcd80-a3bc-11eb-836a-11e9cebf648b.png)


![image](https://user-images.githubusercontent.com/50911878/115756328-b8d34f00-a3bb-11eb-9342-e8a2122c61a7.png)

after Installation completed then go to the google remote desktop


![image](https://user-images.githubusercontent.com/50911878/115753348-bcb1a200-a3b8-11eb-8c58-b29dbd61dcd1.png)


**And click on `remote access`**

![image](https://user-images.githubusercontent.com/50911878/115759059-71e65900-a3bd-11eb-8210-e5266c75308d.png)

after that you will see an online instance(remote device)

![image](https://user-images.githubusercontent.com/50911878/115759234-a6f2ab80-a3bd-11eb-9595-7ff6222f4eea.png)

click on that you will see connecting

![image](https://user-images.githubusercontent.com/50911878/115759362-ca1d5b00-a3bd-11eb-9456-1dd225447ce4.png)

after connecting copy the pin from the notebook in `RDP Cell` 

![image](https://user-images.githubusercontent.com/50911878/115759583-0650bb80-a3be-11eb-9941-3a54c9e3fb69.png)

and paste in the text field in google remote desktop

![image](https://user-images.githubusercontent.com/50911878/115759664-22545d00-a3be-11eb-87a8-b8d987acf7d8.png)

then check the checkbox

![image](https://user-images.githubusercontent.com/50911878/115759854-59c30980-a3be-11eb-98fb-dae4dfdc4ade.png)

and click on the arrow button

![image](https://user-images.githubusercontent.com/50911878/115759945-73fce780-a3be-11eb-823d-acd05fdd38c7.png)

it will show connecting

![image](https://user-images.githubusercontent.com/50911878/115759999-8119d680-a3be-11eb-9f61-964f77c3cabb.png)

after connectimg it will open the linux instance

![image](https://user-images.githubusercontent.com/50911878/115760162-a870a380-a3be-11eb-832e-29737aa712e5.png)

click on `use default config` 

![image](https://user-images.githubusercontent.com/50911878/115760252-c2aa8180-a3be-11eb-98a8-58991917bddd.png)

click on browser from the task bar at bottom

![image](https://user-images.githubusercontent.com/50911878/115760771-35b3f800-a3bf-11eb-9d21-bf9c6a4c6570.png)


then click on `ok`

![image](https://user-images.githubusercontent.com/50911878/115760830-47959b00-a3bf-11eb-8664-7055c444afea.png)


now chrome will be open 

![image](https://user-images.githubusercontent.com/50911878/115760892-5aa86b00-a3bf-11eb-8e17-d8ea0d317293.png)


now create new tab and check the speed

![image](https://user-images.githubusercontent.com/50911878/115761049-89264600-a3bf-11eb-9cab-a2dc1cb0a8d6.png)


![image](https://user-images.githubusercontent.com/50911878/115761187-b4109a00-a3bf-11eb-9a13-42922debbc26.png)


---------

