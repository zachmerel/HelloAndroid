# HelloAndroid
1st Project Udacity Android for Beginners 

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#416173"
    tools:context="MainActivity">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="5"
        android:src="@drawable/udacity"
        android:layout_marginTop="50dp"
        android:layout_marginBottom="50dp"
        android:scaleType="centerCrop"/>

    <TextView
        android:id="@+id/Company_name"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="0dp"
        android:layout_marginBottom="8dp"
        android:text="Udacity"
        android:textColor="#ffffff"
        android:paddingLeft="16dp"
        android:textSize="13sp"
       />
    <TextView
        android:id="@+id/Phone_number"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="8dp"
        android:text="650-555-5555"
        android:paddingLeft="16dp"
        android:textSize="13sp"
        android:textColor="#ffffff"
        />

    <TextView
        android:id="@+id/website"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:autoLink="all"
        android:clickable="true"
        android:text="www.udacity.com"
        android:layout_marginBottom="8dp"
        android:paddingLeft="16dp"
        android:textSize="13sp"
        />

    <TextView
        android:id="@+id/Address"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="90dp"
        android:paddingLeft="16dp"
        android:text="2465 Latham St. Mountain View, CA 94043 "
        android:textColor="#ffffff"
        android:textSize="13sp"
        />

</LinearLayout>
