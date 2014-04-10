pemrogmobile
============
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.example.tictoc"
    android:versionCode="1"
    android:versionName="1.0" >

    <uses-sdk
        android:minSdkVersion="15"
        android:targetSdkVersion="17" />

    <application
        android:allowBackup="true"
        android:icon="@drawable/ic_launcher"
        android:label="@string/app_name"
        android:theme="@style/AppTheme" >
        <activity
            android:name="com.example.tictoc.MainActivity"
            android:label="@string/app_name" >
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />
                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
        <activity 
            android:name="com.example.tictoc.App2Activity"
            android:label="@string/app_name">
            
        </activity>
        <activity
            android:name="com.example.tictoc.Kamera2"
            android:label="@string/app_name" 
            android:screenOrientation="landscape"
            android:theme="@android:style/Theme.NoTitleBar.Fullscreen"
            android:configChanges="keyboardHidden|orientation">
        </activity>
        
    </application>
	<uses-permission android:name="android.permission.CAMERA"/>
	<uses-feature android:name="android.hardware.camera"/>
	<uses-feature android:name="android.hardware.camera.autofocus" />
	<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
</manifest>
