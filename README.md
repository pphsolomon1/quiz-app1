<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"

    android:id= "@+id/activity_quiz"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="16dp"
    android:paddingLeft="16dp"
    android:paddingRight="16dp"
    android:paddingTop="16dp"
    android:orientation="vertical"
    tools:context=".QuizActivity">


    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:padding="8dp">

        <TextView
            android:id="@+id/score_text"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignParentTop="true"
            android:text="Score"
            android:textSize="25sp" />

        <TextView
            android:id="@+id/score"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignParentRight="true"
            android:text="0"
            android:textSize="25dp" />
    </RelativeLayout>

    <TextView
        android:id="@+id/question"
        android:layout_width="351dp"
        android:layout_height="81dp"
        android:layout_alignParentTop="true"
        android:layout_marginTop="59dp"
        android:padding="8dp"
        android:text="Which thing is alive ?"
        android:textSize="20dp" />

    <Button
        android:id="@+id/choice1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_centerInParent="true"
        android:background="#0091EA"
        android:padding="8dp"
        android:text="bird"
        android:textColor="#fff" />


    <Button
        android:id="@+id/choice2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="167dp"
        android:background="#0091EA"
        android:padding="8dp"
        android:text="door"
        android:textColor="#fff" />

    <Button
        android:id="@+id/choice3"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_marginBottom="122dp"
        android:background="#0091EA"
        android:padding="8dp"
        android:text="rock"
        android:textColor="#fff" />

    <Button
        android:id="@+id/quiz"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@+id/choice3"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="-110dp"
        android:background="#B71C1C"
        android:padding="8dp"
        android:text="quiz"
        android:textColor="#fff" />

</RelativeLayout>
