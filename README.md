# -program2 ()
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/놀이동산 예약시스템"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingBottom="@dimen/activity_vertical_margin"
    tools:context="com.example.a403.myapplication.MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="예약시작" />

    <RadioButton
        android:text="시간 설정"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignTop="@+id/radioButton"
        android:layout_toRightOf="@+id/radioButton"
        android:layout_toEndOf="@+id/radioButton"
        android:layout_marginLeft="42dp"
        android:layout_marginStart="42dp"
        android:id="@+id/radioButton2" />

    <RadioButton
        android:text="일자 설정"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="64dp"
        android:id="@+id/radioButton"
        android:layout_below="@+id/button"
        android:layout_alignRight="@+id/textView"
        android:layout_alignEnd="@+id/textView" />

    <Button
        android:text="시간예약"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/button"
        android:layout_below="@+id/textView"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_marginTop="34dp" />

    <CalendarView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/calendarView"
        android:layout_alignParentBottom="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <Button
        android:text="예약완료"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_toRightOf="@+id/textView"
        android:layout_toEndOf="@+id/textView"
        android:layout_marginLeft="16dp"
        android:layout_marginStart="16dp"
        android:id="@+id/button2" />

    <Button
        android:text="Button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignTop="@+id/button2"
        android:layout_toRightOf="@+id/radioButton2"
        android:layout_toEndOf="@+id/radioButton2"
        android:layout_marginLeft="22dp"
        android:layout_marginStart="22dp"
        android:id="@+id/button3" />

</RelativeLayout>
