<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:id="@+id/header"
        android:layout_width="0dp"
        android:layout_height="60dp"
        android:background="#8A2BE2"
        android:gravity="center_vertical"
        android:paddingStart="16dp"
        android:paddingEnd="16dp"
        android:elevation="4dp"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="PRAK.PEMOGRAMAN MOBILE"
            android:textColor="#FFFFFF"
            android:textSize="20dp"
            android:textStyle="bold" />

    </LinearLayout>

    <ScrollView
        android:layout_width="0dp"
        android:layout_height="0dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/header">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="vertical">

            <ImageView
                android:id="@+id/imageView1"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:src="@drawable/bandaNeira"
                app:layout_constraintBottom_toTopOf="@+id/textView"
                app:layout_constraintEnd_toEndOf="parent"
                app:layout_constraintStart_toStartOf="parent"
                app:layout_constraintTop_toTopOf="parent"
                android:scaleType="centerCrop"
                />

            <TextView
                android:id="@+id/textView11"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginVertical="0dp"
                android:text="BANDA NEIRA"
                android:textSize="30dp"
                android:textStyle="bold"
                />

            <TextView
                android:id="@+id/textView2"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Banda Naira adalah kepulauan di Maluku Tengah yang memiliki keindahan alam dan berbagai objek bersejarah. "
                android:layout_marginVertical="0dp"
                android:justificationMode="inter_word"
                />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:gravity="center"
                android:layout_marginVertical="10dp">

                <Button
                    android:id="@+id/button11"
                    android:layout_width="0dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="sudah kesini?" />

                <Button
                    android:id="@+id/button22"
                    android:layout_width="0dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="belum kesini?" />

            </LinearLayout>

            <ImageView
                android:id="@+id/imageView2"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:src="@drawable/lawu"
                app:layout_constraintBottom_toTopOf="@+id/textView"
                app:layout_constraintEnd_toEndOf="parent"
                app:layout_constraintStart_toStartOf="parent"
                app:layout_constraintTop_toTopOf="parent"
                android:scaleType="centerCrop" />

            <TextView
                android:id="@+id/textView12"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginVertical="0dp"
                android:text="GUNUNG LAWU"
                android:textSize="30dp"
                android:textStyle="bold"
                />

            <TextView
                android:id="@+id/textView3"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginVertical="0dp"
                android:text="unung Lawu (Hanacaraka: ꦒꦸꦤꦸꦁꦭꦮꦸ) adalah sebuah gunung berapi aktif yang terletak di Pulau Jawa, tepatnya di perbatasan Jawa Tengah dan Jawa Timur, Indonesia. Gunung Lawu memiliki ketinggian sekitar 3.265 mdpl. Gunung Lawu terletak di antara tiga kabupaten, yaitu Karanganyar di Jawa Tengah, Ngawi, dan Magetan di Jawa Timur. Status gunung ini adalah gunung api "istirahat", yang diperkirakan terakhir meletus pada tanggal 28 November 1885 dan telah lama tidak aktif"
            android:justificationMode="inter_word"
            />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:gravity="center"
                android:layout_marginVertical="10dp">

                <Button
                    android:id="@+id/button3"
                    android:layout_width="0dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="sudah kesini?" />

                <Button
                    android:id="@+id/button4"
                    android:layout_width="0dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="belum kesini?" />

            </LinearLayout>

            <ImageView
                android:id="@+id/imageView3"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:src="@drawable/laut"
                app:layout_constraintBottom_toTopOf="@+id/textView"
                app:layout_constraintEnd_toEndOf="parent"
                app:layout_constraintStart_toStartOf="parent"
                app:layout_constraintTop_toTopOf="parent"
                android:scaleType="centerCrop"
                />

            <TextView
                android:id="@+id/textView13"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginVertical="0dp"
                android:text="LAUT"
                android:textSize="30dp"
                android:textStyle="bold"
                />

            <TextView
                android:id="@+id/textView4"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="  Laut atau segara[1] adalah sebuah perairan asin besar yang dikelilingi secara menyeluruh atau sebagian oleh daratan.[2][3][a] Dalam arti yang lebih luas, "laut" adalah sistem perairan samudra berair asin yang saling terhubung di Bumi yang dianggap sebagai satu samudra global atau sebagai beberapa samudra utama. Laut memengaruhi iklim Bumi dan memiliki peran penting dalam siklus air, siklus karbon, dan siklus nitrogen. "
            android:layout_marginVertical="0dp"
            android:justificationMode="inter_word"
            />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:gravity="center"
                android:layout_marginVertical="10dp">

                <Button
                    android:id="@+id/button5"
                    android:layout_width="0dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="sudah kesini?" />

                <Button
                    android:id="@+id/button6"
                    android:layout_width="0dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="belum kesini?" />

            </LinearLayout>

            <ImageView
                android:id="@+id/imageView4"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:src="@drawable/ranukumbolo"
                app:layout_constraintBottom_toTopOf="@+id/textView"
                app:layout_constraintEnd_toEndOf="parent"
                app:layout_constraintStart_toStartOf="parent"
                app:layout_constraintTop_toTopOf="parent"
                android:scaleType="centerCrop"
                />

            <TextView
                android:id="@+id/textView14"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginVertical="0dp"
                android:text="KUMBOLO"
                android:textSize="30dp"
                android:textStyle="bold"
                />

            <TextView
                android:id="@+id/textView5"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Ranu Kumbolo (bahasa Indonesia: Danau Kumbolo) adalah sebuah danau kawah (maar) yang terletak di dalam Taman Nasional Bromo Tengger Semeru (TNBTS), Jawa Timur, Indonesia. Danau ini merupakan bagian dari rute termudah pendakian yang berawal dari Ranu Pani menuju puncak Gunung Semeru. Dengan luas 12 hektare, Ranu Kumbolo menjadi danau terbesar dan terindah dari semua danau dalam kawasan TNBTS."
                android:justificationMode="inter_word"
                />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:gravity="center"
                android:layout_marginVertical="10dp">

                <Button
                    android:id="@+id/button1"
                    android:layout_width="0dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="sudah kesini?" />

                <Button
                    android:id="@+id/button2"
                    android:layout_width="0dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="belum kesini?" />

            </LinearLayout>



            <Button
                android:id="@+id/button111"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="MARI KITA JELAJAH ALAM"
                tools:ignore="MissingConstraints" />

        </LinearLayout>

    </ScrollView>

    <Button
        android:id="@+id/fixedButton"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="MARI KITA JELAJAH ALAM"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        />

</androidx.constraintlayout.widget.ConstraintLayout>
