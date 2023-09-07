# Hospyta Mobile APP (UI Implementation)

# STACKS
1. Typescript
2. Javascript
# Package Manager
1. expo
2. Yarn(primarily)


# Documentation
1. Folder Structure: The design follow a readable and simple structural pattern

   ## FOLDER STRUCTURE
```
/ 
├───src
│   ├───assets      
│   │   └───fonts, icons, images, animations
│   |
│   ├───modules
|       └───Auth
|       └───Main    
|
│   ├───navigation     
│   ├───context
│   ├───constants    
│   ├───conponents
|        └───Common 
|              └───Text, Button, Header  
│   ├───services   
│   ├───core   
│        
│
│        
└───App.tsx
```

# GET STARTED
Note: This a a React-Native Mobile app that will run on Expo Go

1. Clone Repo
2. Run yarn or expo start to intall Node modules
3. Download Expo Go or (enable download prompt will come up after run yarn is successful)
4. App will launch automatically on expo GO

# Development Build
1. Download Expo Go add
2. Use the following links to get the buils
   Android
   ```
    exp://u.expo.dev/update/2ed74897-adb0-49dd-aaca-df12afacb1fa
   ```
   IOS
   ```
  
     exp://u.expo.dev/update/cd5c2b34-5885-4e1d-92f5-d2ba07f0aac2
   ```
3. Scan the following depending on your Mobile platform of Choice

   
   
# ScreenShots
![simulator_screenshot_564CD006-F2E4-44B2-824B-32E3F66AFBCA](https://github.com/cosmascj/hospyta-mobile/assets/88615113/36708f71-eaa4-49

![Simulator Screen Shot - iPhone 14 Pro - 2023-09-07 at 08 01 00](https://github.com/cosmascj/hospyta-mobile/assets/88615113/9a000de1-a00e-4d93-8bcb-a378e0b87487)
89-8f0f-249d9b262c9d)
![simulator_screenshot_19F4DF1F-5262-4D1B-96E1-9B2CF88ECEEB](https://github.com/cosmascj/hospyta-mobile/assets/88615113/d77d3909-5e3e-48ca-b6b6-5b9551c24306)

# UI Guide
1. Reuseable components like button, Text and Input field were design for the application and can be found the Common file inside the components folder

2. Three different Text Fonts have also been Loaded and used in different sections of the Application design



# ISSUES

1. Finding compatible react-native-reanimated version for expo 49 sdk on android devices
   
