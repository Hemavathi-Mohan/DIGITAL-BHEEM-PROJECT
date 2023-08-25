# DIGITAL-BHEEM-PROJECT
<?xml version="1.0" encoding="utf-8"?>
<!-- Parent layout as linear layout-->
<LinearLayout
	xmlns:android="http://schemas.android.com/apk/res/android"
	xmlns:tools="http://schemas.android.com/tools"
	android:layout_width="match_parent"
	android:layout_height="match_parent"
	android:gravity="center"
	android:orientation="vertical"
	android:padding="10dp"
	tools:context=".MainActivity">

	<!-- linear layout to show datepickers-->
	<LinearLayout
		android:layout_width="match_parent"
		android:layout_height="wrap_content">

		<!-- to select the first date-->
		<Button
			android:id="@+id/bt_birth"
			android:layout_width="150dp"
			android:layout_height="50dp"
			android:background="@android:color/transparent"
			android:drawableRight="@drawable/ic_baseline"
			android:text="01/01/2021"
			android:textColor="@color/black"
			android:textSize="13sp" />

		<!-- displaying message as "to"-->
		<TextView
			android:layout_width="100dp"
			android:layout_height="50dp"
			android:gravity="center_horizontal"
			android:text="To"
			android:textColor="@color/black"
			android:textSize="20sp"
			android:textStyle="bold" />

		<!-- to display date number 2-->
		<Button
			android:id="@+id/bt_today"
			android:layout_width="145dp"
			android:layout_height="50dp"
			android:background="@android:color/transparent"
			android:drawableRight="@drawable/ic_baseline"
			android:textColor="@color/black"
			android:textSize="13sp" />
		
	</LinearLayout>
	<!-- to perform the calculation-->
	<Button
		android:id="@+id/btn_calculate"
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_marginTop="10dp"
		android:text="calculate" />

	<!-- to display the message "Result"-->
	<TextView
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_marginTop="50dp"
		android:text="Result"
		android:textColor="@android:color/holo_blue_bright"
		android:textSize="30sp"
		android:textStyle="bold" />

	<!-- To show the final output(age)-->
	<TextView
		android:id="@+id/tv_result"
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_marginTop="10dp"
		android:text="0 Years | 0 Months | 0 Days"
		android:textSize="25sp"
		android:textStyle="bold" />

</LinearLayout>
