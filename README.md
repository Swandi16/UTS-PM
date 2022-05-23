# UTS-PM
Informasi Geografis Desa Simangumban
<?xml version="1.0" encoding="utf-8"?>
<androidx.coordinatorlayout.widget.CoordinatorLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <org.osmdroid.views.MapView
        android:id="@+id/mapView"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="180dp"
        android:layout_gravity="bottom"
        android:background="/images/branding/googleg/1x/googleg_standard_color_128dp.png"
        android:backgroundTint="@android:color/holo_blue_light"
        android:focusable="true"
        android:orientation="vertical">

        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginStart="20dp"
            android:layout_marginTop="10dp"
            android:layout_marginBottom="10dp">

            <ImageView
                android:id="@+id/imageMap"
                android:layout_width="36dp"
                android:layout_height="30dp"
                android:layout_alignParentStart="true"
                android:layout_centerHorizontal="true"
                android:layout_marginStart="0dp"
                android:src="@drawable/img_1" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginStart="10dp"
                android:layout_toEndOf="@id/imageMap"
                android:orientation="vertical">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Mau melihat informasi geografis desa?"
                    android:textColor="@android:color/white"
                    android:textSize="14sp"
                    android:textStyle="bold" />

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Jangan lupa pakai masker saat berpergian ya!"
                    android:textColor="@android:color/white"
                    android:textSize="12sp" />

            </LinearLayout>

        </RelativeLayout>

        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@drawable/img">

            <ImageView
                android:id="@+id/imageLocation"
                android:layout_width="30dp"
                android:layout_height="30dp"
                android:layout_alignParentStart="true"
                android:layout_centerInParent="true"
                android:layout_marginStart="20dp"
                android:src="@drawable/ic_location"
                app:tint="@android:color/holo_red_light" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_centerInParent="true"
                android:layout_marginStart="10dp"
                android:layout_marginEnd="20dp"
                android:layout_toEndOf="@id/imageLocation"
                android:orientation="vertical">

                <TextView
                    android:id="@+id/tvCurrentLocation"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Desa Aek Nabara Kec. Simangumban"
                    android:textColor="@android:color/black"
                    android:textSize="18sp"
                    android:textStyle="bold" />

                <TextView
                    android:id="@+id/tvAddress"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Jl. Sipirok - Tarutung, Kab.Tapanuli Utara"
                    android:textColor="@android:color/black"
                    android:textSize="12sp" />

            </LinearLayout>

        </RelativeLayout>

    </LinearLayout>

</androidx.coordinatorlayout.widget.CoordinatorLayout>
[UTS PM SWANDY.zip](https://github.com/Swandi16/UTS-PM/files/8754555/UTS.PM.SWANDY.zip)

