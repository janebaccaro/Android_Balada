Android_Balada
==============


<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        android:orientation="vertical"
        android:background="#000000"
        tools:context="com.example.baladas.app.Adminstrador">

        <LinearLayout
            android:layout_width="fill_parent"
            android:layout_height="100dp"
            android:gravity="center_horizontal">

            <ImageView
                android:id="@+id/imageView1"
                android:layout_width="fill_parent"
                android:layout_height="fill_parent"
                android:src="@drawable/ic_launcher"/>

        </LinearLayout>

        <EditText
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:text="Choperia Veloso"
            android:textColor="#ffffff"
            android:textSize="20dp"
            android:gravity="center"/>
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="200dp"
            android:orientation="horizontal">

            <LinearLayout
                android:layout_width="150dp"
                android:layout_height="wrap_content"
                android:orientation="vertical">

                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:text="Balada:"
                    android:textColor="#ffffff"
                    android:textSize="20dp"
                    android:layout_gravity="left"/>

                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:text="Data:"
                    android:textColor="#ffffff"
                    android:textSize="20dp"
                    android:gravity="left"/>
                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:text="Inicio:"
                    android:textColor="#ffffff"
                    android:textSize="20dp"
                    android:gravity="left"/>
                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:text="Open Bar:"
                    android:textColor="#ffffff"
                    android:textSize="20dp"
                    android:gravity="left"/>
            </LinearLayout>
            <LinearLayout
                android:layout_width="200dp"
                android:layout_height="wrap_content"
                android:orientation="vertical">
                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:text="Calourada 2014"
                    android:textColor="#ffffff"
                    android:textSize="20dp"
                    android:layout_gravity="left"/>

                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:text="18/04/2014"
                    android:textColor="#ffffff"
                    android:textSize="20dp"
                    android:gravity="left"/>
                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:text="00:01"
                    android:textColor="#ffffff"
                    android:textSize="20dp"
                    android:gravity="left"/>
                <EditText
                    android:layout_width="70dp"
                    android:layout_height="40dp"
                    android:text="On"
                    android:textColor="#ffffff"
                    android:textSize="20dp"
                    android:gravity="center"
                    android:background="#ffa7a7a7"/>

            </LinearLayout>

        </LinearLayout>
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:layout_gravity="center">

            <Button
                android:layout_width="150dp"
                android:layout_height="50dp"
                android:text="Atualizar Dados"
                android:textColor="#ffffff"
                android:background="#ff5ca927"/>

            <LinearLayout
                android:layout_width="1dp"
                android:layout_height="1">

            </LinearLayout>

            <Button
                android:layout_width="150dp"
                android:layout_height="50dp"
                android:padding="10dp"
                android:text="Eu vou!"
                android:textColor="#ffffff"
                android:background="#ff5ca927"/>

        </LinearLayout>
    </LinearLayout>












