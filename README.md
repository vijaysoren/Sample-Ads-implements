# Sample-Ads-implements
code sample for sample ads. Admob Ads



# Implement AdMob banner ad

To implement AdMob banner ad you configure your app -

step 1. Add the dependencies for Google Mobile Ads SDK to your module's app-level Gradle file - app/build.gradle:

           dependencies {
             implementation 'com.google.android.gms:play-services-ads:21.2.0'
           }

step 2. Add your AdMob APP ID in your AndroidManifest.xml file -

           <manifest>
               <application>
                   <!-- Sample AdMob app ID: ca-app-pub-3940256099942544~3347511713 -->
                   <meta-data
                       android:name="com.google.android.gms.ads.APPLICATION_ID"
                       android:value="ca-app-pub-3940256099942544~3347511713"/>
               </application>
           </manifest>

step 3. Initialize the Google Mobile Ads SDK -

              import com.google.android.gms.ads.MobileAds;
              import com.google.android.gms.ads.initialization.InitializationStatus;
              import com.google.android.gms.ads.initialization.OnInitializationCompleteListener;

              public class MainActivity extends AppCompatActivity {
                  protected void onCreate(Bundle savedInstanceState) {
                      super.onCreate(savedInstanceState);
                      setContentView(R.layout.activity_main);

                      MobileAds.initialize(this, new OnInitializationCompleteListener() {
                          @Override
                          public void onInitializationComplete(InitializationStatus initializationStatus) {
                          }
                      });
                  }
               }


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
        
        <!-- Sample AdMob app ID: ca-app-pub-3940256099942544~3347511713 -->
        <meta-data
            android:name="com.google.android.gms.ads.APPLICATION_ID"
            android:value="ca-app-pub-3940256099942544~3347511713"/>
            
            
## Step 4. Initialize Google Mobile Ads SDK
     
     implement code
     
Here's the link to peice of code to implement [admob intertitial ad](https://github.com/vijaysoren/Sample-Ads-impliments/blob/main/Android/AdMob/SampleAds/app/src/main/java/com/vijaysoren/sampleads/MainActivity.java)
     
let's test
     
run the code on your device

     wooooo! our interstitial ad has successfully loaded
     
     
![](https://github.com/vijaysoren/Sample-Ads-impliments/blob/03cf5a245ca416cd88eb4738ff8d16d7efbc767e/screenshots/Screenshot_20220930-101547_SampleAds.jpg)
     
     ---------------------------------------------------------------------------------------
     
     
     
# Implement Admob native ad

 To configure AdMob SDK in your project,
             
             1. Add Admob SDk dependency in your project's app level build.gradle file and then click sync.
             
             2. Add Admob APP ID in your androidmanifest file
             
             3. Initialize Google Mobile Ads SDK in your launcher activity or once in your app.
             
             
Let's write some code.
             
Here is the link to code to [admob native ad](https://github.com/vijaysoren/Sample-Ads-impliments/blob/5e9dce4c5e0cf7ede8873450af2c052c80ec970a/Android/AdMob/SampleAds/app/src/main/java/com/vijaysoren/sampleads/NativeAdActivity.java)
             
#### step 1. Create a [native ad container](Android/AdMob/SampleAds/app/src/main/res/layout/activity_native_ad.xml). This container will hold a native ad.
             
#### step 2. Create a [native ad layout](Android/AdMob/SampleAds/app/src/main/res/layout/native_ad_layout.xml).
             
#### step 3. Create a [style widget](Android/AdMob/SampleAds/app/src/main/res/values/themes.xml) for ad attribution.
              
              
     Run your app. Native app mostly work on physical. To show on virtual device you need to add extra settings.
              
              

     
![](https://github.com/vijaysoren/Sample-Ads-impliments/blob/4790d23963179daf20c4b56ecc6ea6276b0bb080/screenshots/Screenshot_20220930-093824_SampleAds.jpg)
     
   
# Implement AdMob Rewarded Ad

![](https://github.com/vijaysoren/Sample-Ads-implements/blob/2aad0af6e71cd2ebac60ed3e7a0e8a894547bc32/screenshots/Screenshot_20221019_155331.png)

Full code to [Rewarded Ad](https://github.com/vijaysoren/Sample-Ads-implements/blob/c3ff71a562226efcad3dbbf283395be35eb5b06a/Android/AdMob/SampleAds/app/src/main/java/com/vijaysoren/sampleads/RewardedAdActivity.java)

