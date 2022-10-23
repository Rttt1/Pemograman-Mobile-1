# Pemograman-Mobile-1
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="10dp">

    <Button
        android:id="@+id/buttonScan"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Scan QR Code"
        android:layout_alignParentBottom="true" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:layout_centerVertical="true">

        <Button
            android:id="@+id/button"
            android:layout_width="402dp"
            android:layout_height="wrap_content"
            android:text=" TUGAS XML QR Code Scanner"
            tools:layout_editor_absoluteX="-6dp"
            tools:layout_editor_absoluteY="-5dp" />

        <TextView
            android:id="@+id/textView"
            android:textStyle="bold"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Nama" />

        <TextView
            android:id="@+id/textViewNama"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Adidarma Mahendra"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:textStyle="bold"
            android:text="Kelas" />


        <TextView
            android:id="@+id/textViewKelas"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="TI.21.C2"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:textStyle="bold"
            android:text="NIM" />

        <TextView
            android:id="@+id/textViewNIM"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="312110509"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />


        <ImageView
            android:id="@+id/imageView"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:src="@drawable/upb" />
    </LinearLayout>
</RelativeLayout>![tugas pem web](https://user-images.githubusercontent.com/98471247/197409380-3d846192-d7ee-4561-9a23-fcc34642ca49.JPG)
