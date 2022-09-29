# Sample-Ads-impliments
code sample for sample ads. Admob Ads



# Implement AdMob banner ad

here's the link for peice of code to implement admob banner ad [sample code](https://github.com/vijaysoren/Sample-Ads-impliments/commit/9b77b159a6c3c6efa1ccb2f7d08033167da6beef?diff=unified)



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
     
     let's test
     
     wooooo! our interstitial ad has successfully loaded
     
     ---------------------------------------------------------------------------------------
     
     
     
   
