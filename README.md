# MyCurrentLocation

Get current location in Android with google maps api.
# Setup 
Visit https://developers.google.com/maps/documentation/android/start to obtain your API Key and config the android project.

# Usage 
in AndroidManifest.xml These are permission for application for using Location,INTERNET.

uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"
uses-permission android:name="android.permission.INTERNET"

# Insert your API key:

meta-data android:name="com.google.android.maps.v2.API_KEY"
android:value="INSERT HERE YOUR API KEY"


