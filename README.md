# Google_Places

Copy code from Place_auto_complete

#DEPENDENCIES

    compile 'com.google.android.gms:play-services:9.0.0'
    compile 'com.google.android.gms:play-services-location:9.0.0'
    
    
Add following lines in android manifest inside application tag

    <meta-data
            android:name="com.google.android.geo.API_KEY"
            android:value="AIzaSyCoACGzF9Lu5-wyl7_gWyuYyedA4P7wUz0" />
            
Add following permission in manifest
    
     <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
