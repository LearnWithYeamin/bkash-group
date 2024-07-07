<p align="center">
<h1 align='center'>Bkash Section Item</h1>
<h3 align='center'>
   Visit my youtube channel <a href="https://www.youtube.com/@CodeCraftArena">CodeCraft Arena</a>
</h3>
</p>

## Step 1: Here is `activity_main.xml` code.
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp"
    tools:context=".MainActivity">

    <GridLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:alignmentMode="alignMargins"
        android:columnCount="4"
        android:rowCount="2"
        android:columnOrderPreserved="false"
        android:layout_gravity="center">

        <!-- Send Money -->
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_columnWeight="1"
            android:layout_rowWeight="1"
            android:orientation="vertical"
            android:gravity="center"
            android:padding="8dp">
            <ImageView
                android:layout_width="48dp"
                android:layout_height="48dp"
                android:src="@drawable/send_money_icon" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="সেন্ড মানি"
                android:textSize="14sp"
                android:gravity="center"
                android:textColor="#000000"/>
        </LinearLayout>

        <!-- Mobile Recharge -->
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_columnWeight="1"
            android:layout_rowWeight="1"
            android:orientation="vertical"
            android:gravity="center"
            android:padding="8dp">
            <ImageView
                android:layout_width="48dp"
                android:layout_height="48dp"
                android:src="@drawable/mobile_recharge_icon" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="মোবাইল রিচার্জ"
                android:textSize="14sp"
                android:gravity="center"
                android:textColor="#000000"/>
        </LinearLayout>

        <!-- Cash Out -->
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_columnWeight="1"
            android:layout_rowWeight="1"
            android:orientation="vertical"
            android:gravity="center"
            android:padding="8dp">
            <ImageView
                android:layout_width="48dp"
                android:layout_height="48dp"
                android:src="@drawable/cash_out_icon" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="ক্যাশ আউট"
                android:textSize="14sp"
                android:gravity="center"
                android:textColor="#000000"/>
        </LinearLayout>

        <!-- Payment -->
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_columnWeight="1"
            android:layout_rowWeight="1"
            android:orientation="vertical"
            android:gravity="center"
            android:padding="8dp">
            <ImageView
                android:layout_width="48dp"
                android:layout_height="48dp"
                android:src="@drawable/payment_icon" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="পেমেন্ট"
                android:textSize="14sp"
                android:gravity="center"
                android:textColor="#000000"/>
        </LinearLayout>

        <!-- Add Money -->
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_columnWeight="1"
            android:layout_rowWeight="1"
            android:orientation="vertical"
            android:gravity="center"
            android:padding="8dp">
            <ImageView
                android:layout_width="48dp"
                android:layout_height="48dp"
                android:src="@drawable/add_money_icon" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="অ্যাড মানি"
                android:textSize="14sp"
                android:gravity="center"
                android:textColor="#000000"/>
        </LinearLayout>

        <!-- Pay Bill -->
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_columnWeight="1"
            android:layout_rowWeight="1"
            android:orientation="vertical"
            android:gravity="center"
            android:padding="8dp">
            <ImageView
                android:layout_width="48dp"
                android:layout_height="48dp"
                android:src="@drawable/pay_bill_icon" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="পে বিল"
                android:textSize="14sp"
                android:gravity="center"
                android:textColor="#000000"/>
        </LinearLayout>

        <!-- Savings -->
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_columnWeight="1"
            android:layout_rowWeight="1"
            android:orientation="vertical"
            android:gravity="center"
            android:padding="8dp">
            <ImageView
                android:layout_width="48dp"
                android:layout_height="48dp"
                android:src="@drawable/savings_icon" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="সেভিংস"
                android:textSize="14sp"
                android:gravity="center"
                android:textColor="#000000"/>
        </LinearLayout>

        <!-- Loan -->
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_columnWeight="1"
            android:layout_rowWeight="1"
            android:orientation="vertical"
            android:gravity="center"
            android:padding="8dp">
            <ImageView
                android:layout_width="48dp"
                android:layout_height="48dp"
                android:src="@drawable/loan_icon" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="লোন"
                android:textSize="14sp"
                android:gravity="center"
                android:textColor="#000000"/>
        </LinearLayout>

    </GridLayout>

</LinearLayout>
```
<img src="https://raw.githubusercontent.com/learn-with-yeamin/bkash-group/main/preview-img.png" alt="preview-img">

## Authors
**MD YEAMIN** - *Android Software Developer* - <a href="https://github.com/i-rin-eam">MD YEAMIN</a> - *Learn with Ease*
<h1 align="center">Thank You ❤️</h1>
