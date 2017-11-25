# HelloAndroid
first single screen app
<?xml version="1.0" encoding="utf-8"?>

<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.android.helloandroid.MainActivity"
    >
    <ImageView
       android:layout_width="match_parent"
       android:layout_height="match_parent"
       android:src = "@drawable/udacity"
       android:scaleType="centerCrop"
       />
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="200dp"
        android:orientation="vertical"
        android:layout_alignParentBottom="true"
        >
        <TextView
              android:layout_width="wrap_content"
              android:layout_height="wrap_content"
              android:text="Udacity"
              android:textColor="#FFFFFF"
              android:textStyle="bold"
              android:fontFamily="casual"
              android:textSize="40dp"
              android:padding="8dp"
          />
        <TextView
              android:layout_width="wrap_content"
              android:layout_height="wrap_content"
              android:text="650-555-5555"
              android:textColor="#FFFFFF"
              android:textStyle="bold"
              android:fontFamily="casual"
              android:padding="8dp"
            />
        <TextView
            android:id="@+id/linkid"
            android:text="http://www.udacity.com"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:autoLink="all"
            android:clickable="true"
            />
        <TextView
              android:layout_width="wrap_content"
              android:layout_height="wrap_content"
              android:text="2465 Latham St Mountain View,CA 94043"
              android:textColor="#FFFFFF"
              android:textStyle="bold"
              android:fontFamily="casual"
               android:padding="8dp"
            />
    </LinearLayout>

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content">
        <ImageView
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:src = "@drawable/one"
            android:layout_marginRight="30dp"
            android:layout_marginLeft="15dp"
            />
        <ImageView
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:src = "@drawable/two"
            android:layout_marginRight="30dp"
            />
        <ImageView
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:src = "@drawable/three"
            />
    </LinearLayout>
</RelativeLayout>
