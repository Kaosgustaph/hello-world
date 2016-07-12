# hello-world
Para el curso de la UNAM
activity_main.xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="com.kaos.holamundo.MainActivity">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/imageView"
        android:src="@drawable/marcianito"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_alignParentBottom="true" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/titulo_app"
        android:id="@+id/textView"
        android:textSize="@dimen/abc_text_size_title_material"
        android:layout_alignParentTop="true"
        android:layout_alignRight="@+id/button"
        android:layout_alignEnd="@+id/button"
        android:layout_marginTop="112dp" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/button"
        android:layout_marginTop="43dp"
        android:layout_below="@+id/textView"
        android:layout_centerHorizontal="true"
        android:text="@string/boton" />

</RelativeLayout>
