<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <ImageView

        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="fitStart"
        android:src="@drawable/courses" />

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="match_parent"
        android:layout_marginTop="30dp">

        <ImageView
            android:src="@drawable/android_1"
            android:layout_width="130dp"
            android:layout_height="wrap_content" />

        <ImageView
            android:src="@drawable/programming"
            android:layout_width="130dp"
            android:layout_height="wrap_content" />

        <ImageView
            android:src="@drawable/development"
            android:layout_width="130dp"
            android:layout_height="wrap_content" />

    </LinearLayout>

    <TextView
        android:id="@+id/tel_text_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:fontFamily="sans-serif-condensed"
        android:textSize="18sp"
        android:paddingLeft="20dp"
        android:paddingBottom="30dp"
        android:text="650-555-5555" />

    <TextView
        android:id="@+id/adress_text_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/tel_text_view"
        android:fontFamily="sans-serif-condensed"
        android:textSize="18sp"
        android:paddingLeft="20dp"
        android:layout_marginBottom="2dp"
        android:text="Mountain View, CA 94043" />

    <TextView
        android:id="@+id/latham_text_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/adress_text_view"
        android:fontFamily="sans-serif-condensed"
        android:textSize="18sp"
        android:paddingLeft="20dp"
        android:layout_marginBottom="2dp"
        android:text="2465 Latham St." />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/latham_text_view"
        android:fontFamily="sans-serif"
        android:textSize="26sp"
        android:paddingLeft="20dp"
        android:layout_marginBottom="2dp"
        android:text="UDACITY" />

</RelativeLayout>
