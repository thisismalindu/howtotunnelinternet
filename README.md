# How to get Free Internet on Android/Windows PC
### This consists of 3 main steps:

 **1. Activating a Content Based Package from your Mobile Network Provider**
 - I Use Hutch - Learn From Package for Rs.219 - 30GB/month. This is like a zoom package. This is the most affordable from Hutch at the moment.
 - I also use SLT WiFi, so I use their Zoom package as well. It also like Rs.200. Just activate it through the SLT app or https://myslt.slt.lk/. It's also good and works well with this tunneling method. I use this mainly for my PC, but you can use it on Android as well.
 - Don't use Mobitel, on Mobitel, you need to have money on your sim to activate Data and if you tunnel, you have the risk of being charged in money instead of the package. So don't try this.
 - Airtel is fine. I used it. There is a learn from home package, but I believe it has a speed restriction.
 - There's also Dialog, some of their packages are limited or doesn't allow tunneling.

	So, to go the safer route, find yourself a Hutch Sim and proceed with the rest of this tutorial. Or else, join this [Telegram group](https://t.me/ehi_podda) and ask for more details. (it's not mine)
	
 **2. Downloading a Tunneling App**
	 

 - For Android, we are going to use TLS Tunnel. This doesn't require **STEP 03** - (so it's easier)
 - For Windows we will use TCP Over SSL Tunnel - This does require **STEP 03**
	
	There are other methods also, but this is the easiest route for beginners.

 **3. Creating an SSH server - It's FREE! (Only for Windows)**
 
**4. Start your Tunnel and enjoy "FREE" Internet!**

*The tutorial below consists of a detailed explanation of each of above steps.*

## On Android
1. **Activate your Data Package.** On Hutch just reload Rs.219 and your Learn from Home package will be activated. You can also use the Hutch app and activate the package if you have enough balance on your account or reload through the app as well. You know the drill, just refer to your network's website if you don't know.
2. **Download TLS Tunnel**

![Download this](https://i.imgur.com/ut19Nyn.png)

After downloading, open the app. Agree to whatever they say and then you will be greeted with this screen.

<img src="https://i.imgur.com/FfuIeJQ.jpeg" width="400px">

**3. There is no STEP 03 for Android, skip to Step 04  😆** 

**4. Starting the Tunnel** 

Tap on the pencil Icon in "Connection Method"

![enter image description here](https://i.imgur.com/7q24lcO.png)

Change the settings like this:  
**NOTE: Since I am using a Zoom Package, the SNI Host is zoom.us . If you are using something else, ask in that Telegram group I told earlier.** 

![enter image description here](https://i.imgur.com/AOWdxLw.png)

Now tap the Save icon:

![enter image description here](https://i.imgur.com/24fREXa.png)

Now tap "Start"

![enter image description here](https://i.imgur.com/KQML3Gq.png)

Tap here to see the connection details/log:

![enter image description here](https://i.imgur.com/WDQAFxt.png)

If you see this, then we are successful! 

![enter image description here](https://i.imgur.com/E6qOQwR.png)

If you get this: 

![enter image description here](https://i.imgur.com/V1EGdsn.png)

don't worry, just wait a few seconds (or a minute, the app sucks) and then that "Loading Ad.." button will turn into a Watch Button and tap that and watch an add of 30 seconds and you will be gifted with about 4 or more hours of usage. What this means is that, for the developers of this app to make money, since they are offering a free service, they will show you ads and they will earn some money from it. Don't worry about it. Just watch the ad and you can then enjoy internet for a few hours. After that, the app will tell you to Renew the time, then just click on the Watch button and you are good to go!

### Yeah! you are ready to surf the internet freely. 

## On Windows
1. **Activate your Data Package.** As usual, you need to have something like a Zoom package, either on your phone or your wifi or dongle. Activate the package and connect your PC to the internet. If you are using a phone, then just connect your PC to the phone's Mobile Hotspot or USB Tethering. Or just connect to your Wifi or dongle as usual.
2. **Download the TCP over SSL Tunnel App**
Go to [this website](https://sourceforge.net/projects/tcpoverssltunnel/files/latest/download) and the download will start automatically after 5 seconds.
Extract the ZIP archive to a desired place. You should get a folder with these files:

![enter image description here](https://i.imgur.com/bF0VKO6.png)

Open that TCP  Over SSL Tunnel Application.

3. **Create an SSH Server** 
Go to [this website.](https://www.fastssh.com/page/ssh-account-creator-stunnel/server/1001007/ssh-stunnel-singapore-zxc/) 
Scroll down to this area.

![enter image description here](https://i.imgur.com/WeMBZLZ.png)

Enter a username and password. These do not have to be secure like you other passwords, just put something like your name and numbers.  	eg: *kasun123* for both username and password
Now check that **I'm not a robot** and after that click **Create Account**.

The site is full of ads, it might be cluttered, just install an adblock if you don't have one already. It's a good thing to have in general when browsing the web.

![enter image description here](https://i.imgur.com/dzJRWix.png)

After that, you will see the details of your account.

![enter image description here](https://i.imgur.com/2Gm1ELJ.png)

Don't close this website, you see the username and password, these are the stuff we need to tunnel on PC.

**4. Start the Tunnel**
Now open that app (you have it opened already just go to it)
Go to **Configurations->SSH Profile**:

![enter image description here](https://i.imgur.com/Kh7uBXP.png)

Now Enter the details from that website in the following sections:

![enter image description here](https://i.imgur.com/nyliK0f.png)

Take note of the following fields:
1. **SNI Host**: this needs to be **zoom.us** It is the sames as it was in android, it depends on the package you activated.
2. **Host** : this needs to be **ssl-sg2.hostip.co**. This comes from that website. I gave you the website link so that this will be the one to put in *host*. You must enter that **443** things as well.
3. **Login and Password** : Copy them from that website, remember from earlier?
		![enter image description here](https://i.imgur.com/ZIJewPz.png)
		
Also, as you can see this account expires in 7 days. So you need to go this website in 7 days and then create this account with the same details. So if  you made the account using "kasun123" then create and account with username and password *kasun123* every 7days.

Now after that, click on the Add to IE button. This will ask for admin rights 3 times, just press **YES** for all of them, don't worry nothing harmful is done 🤗.

![enter image description here](https://i.imgur.com/XBORzFU.png)

**Remember** this step. This is vital. This is telling Windows, that it should tunnel all traffic through this app. If you ever want to access the internet without this app, you need to go to Windows Search and search Proxy settings and then disable proxy from there. 

Now you are ready to tunnel. Just click on the **Start** Button.

![enter image description here](https://i.imgur.com/rq4bMFO.png)

Check the **log** checkbox to see a status/log of the connection process.

![enter image description here](https://i.imgur.com/k8LTX0M.png)

After a few seconds you should see the **[#] Successfully connected to server!** message. This means we did it!

Additionally, to save us from the trouble of setting all these everytime, just click on **File->Save Default** and it will save everything and will load automatically when you open this app.
To start the ap automatically when you boot up your PC, go to the place where you extracted the app and right click on the Application and click **Create Shortcut**. Copy this shortcut. Now in the address bar of the File Explorer type **Startup** and hit enter. Now paste that shortcut there.

![enter image description here](https://i.imgur.com/RLJjWIX.gif)

Good luck! You have enabled tunnel on your PC. 

## Ending Notes
Congratulations! You are ready to surf internet freely. Here are some tips I gathered through my experience.

 - I recommend getting a Hutch Sim if you have Signal in your area. This just works! Don't use this sim for any other purpose. Just use it for this tunneling process. Don't recharge this sim with additional money. Just recharge it with the amount needed for the package. Then if the tunnel fails, you don't risk any money being consumed for your internet usage. I think you have enough experience on this. LOL.
 - Tunneling kills battery life. Make sure to have your phone plugged in if you are using it's hotspot. It's pretty commonsense.
 - You will get angry a lot because of this tunnel. Sometimes it is painful. Be patient. If the tunnel fails on Windows, wait a few minutes. In fact, I had to wait for like *one day* for the tunnel to work as usual. I had no internet for that day.
 - TLS Tunnel works almost all the time. Just keep renewing the time by watching ads. There is also this app called *HTTP Injector* which is like the one we used on PC and there is an option in it to share the tunnel to PC as well. This will eleminate the use of TCP Tunnel on Windows and all you have to do is just connect to your phone's hotspot and change a few settings in Windows and you are good to go. But I find my method more easier and saves some battery for your phone if you are not using internet on it. If you want to know about that method send me a message.

## That's it. 
 Hopefully now you can surf the internet without being charged thousands of Rupees.
If you think this article was useful, considering giving it a star and share this with your friends. 

Thank you.
 
