# pemrograman-mobile-tugas1
Hasil pembuatan project pembuatan design XML QR Code Scanner.
p<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin">

    <Button
        android:id="@+id/buttonScan"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Scan QR Code"
        android:layout_alignParentBottom="true"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:layout_centerVertical="true" >

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Nama" />

        <TextView
            android:id="@+id/textViewNama"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="xyz"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Kelas" />

        <TextView
            android:id="@+id/textViewKelas"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="xyz"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="NIM" />

        <TextView
            android:id="@+id/textViewNIM"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="xyz"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>
    </LinearLayout>


</RelativeLayout>
    <?xml version="1.0" encoding="utf-8"?>
<resources>
<dimen name="activity_vertical_margin">30dp</dimen>
<dimen name="activity_horizontal_margin">30dp</dimen>
</resources>
