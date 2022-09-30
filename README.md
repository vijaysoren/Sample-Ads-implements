# Sample-Ads-impliments
code sample for sample ads. Admob Ads



# Implement AdMob banner ad

here's the link for peice of code to implement admob banner ad [sample code](https://github.com/vijaysoren/Sample-Ads-impliments/commit/9b77b159a6c3c6efa1ccb2f7d08033167da6beef?diff=unified)

![](https://github.com/vijaysoren/Sample-Ads-impliments/blob/f4b501d1f6abcf2e4ad524a134128d0bba864f02/screenshots/Screenshot_20220930-101551_SampleAds.jpg)



# Implement AdMob interstitial ad
  ---------------------------------
                
                
## step 1. create new project

-- I'm going to implement into existing android studio projrect

## step 2. Add admob librabry dependency-

    implementation 'com.google.android.gms:play-services-ads:21.2.0'
    
    Add above line in your app level build.gradle file in dependencies
    
    
## Step 3. Add AdMob App ID in your manifest file -
 
        I've already added in my manifest file
        
        <!-- Sample AdMob app ID: ca-app-pub-3940256099942544~3347511713 -->
        <meta-data
            android:name="com.google.android.gms.ads.APPLICATION_ID"
            android:value="ca-app-pub-3940256099942544~3347511713"/>
            
            
## Step 4. Initialize Google Mobile Ads SDK
     
     impliment code
     
Here's the link to peice of code to implement [admob intertitial ad](https://github.com/vijaysoren/Sample-Ads-impliments/blob/main/Android/AdMob/SampleAds/app/src/main/java/com/vijaysoren/sampleads/MainActivity.java)
     
let's test
     
run the code on your device

     wooooo! our interstitial ad has successfully loaded
     
     ---------------------------------------------------------------------------------------
     
     
     
# Implement Admob native ad

 To configure AdMob SDK in your project,
             
             1. Add Admob SDk dependency in your project's app level build.gradle file and then click sync.
             
             2. Add Admob APP ID in your androidmanifest file
             
             3. Initialize Google Mobile Ads SDK in your launcher activity or once in your app.
             
             
Let's write some code.
             
I've some codes that I've already written to save time those I'll copy and paste in my app.
             
#### step 1. Create a native ad container. This container will hold a native ad.
             
#### step 2. Create a native ad layout.
             
#### step 3. Create a style widget for ad attribution.
              
              
     Run your app. Native app mostly work on physical. To show on virtual device you need to add extra settings.
              
              

     
![](https://github.com/vijaysoren/Sample-Ads-impliments/blob/4790d23963179daf20c4b56ecc6ea6276b0bb080/screenshots/Screenshot_20220930-093824_SampleAds.jpg)
     
   
