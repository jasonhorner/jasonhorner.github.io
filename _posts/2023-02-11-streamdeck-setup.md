# Streamlining Your Streamdeck Setup with the Edge User Profile Number

As consultant that uses streamdeck to help manage the pain of multiple clients, we all know the frustration of setting up a new menu itemsin Streamdeck. One particular challenge is finding the elusive Edge user profile number. But fear not, for we have a solution that will make your next profile setup in Streamdeck a breeze. 

## Finding the Edge User Profile Number

For those unfamiliar, the profile number is a crucial component when setting up new browser based Edge applications. This number allows Streamdeck to know which profile to access and use. 

To find your Edge user profile number, simply enter the following URL into your browser: 

[edge://version/#profile_path](edge://version/#profile_path)

This will take you to a page that display the profile path, which usually looks something like this: 

**C:\Users<username>\AppData\Local\Microsoft\Edge\User Data\*Profile 17***
  
Now when createing a streamdeck   
  
 you can use soemething like this example below which  
  
```
C:\Program Files (x86)\Microsoft\Edge\Application\msedge_proxy.exe"  --profile-directory="Profile 17" --app-id= --app-url=https://portal.azure.com/#home
```  
 in the above snippet **Profile 17** is the profile id
**foo** is the application id
 and  **https://portal.azure.com/#home** is the application url
  

With this handy tip, finding your Edge user profile number is now a hassle-free process. Happy Streamdecking.
