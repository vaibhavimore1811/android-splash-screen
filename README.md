# Android Splash Screen 🚀📱

A Splash Screen is the first screen displayed when an Android application launches. It provides a smooth and professional user experience while the application loads and initializes background resources.

This project demonstrates how to create a modern Android Splash Screen using Java and XML.

---

# 🚀 Features

✅ Modern Splash Screen UI  
✅ Smooth App Launch Experience  
✅ Logo & Branding Support  
✅ Full-Screen Splash Screen  
✅ Automatic Navigation  
✅ Beginner Friendly  
✅ Android Java Implementation  

---

# 📚 What is a Splash Screen?

A Splash Screen is a graphical screen shown while the application is starting.

It helps to:
- Improve user experience
- Display app branding
- Hide loading delays
- Initialize app resources
- Create a professional app feel

---

# 📂 Splash Screen Layout Example

```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:gravity="center"
    android:background="@color/primaryColor">

    <ImageView
        android:layout_width="120dp"
        android:layout_height="120dp"
        android:src="@drawable/app_logo"
        android:layout_centerInParent="true"/>

</RelativeLayout>
```

---

# 💻 Java Example

```java
public class SplashActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_splash);

        new Handler().postDelayed(() -> {

            Intent intent = new Intent(
                    SplashActivity.this,
                    MainActivity.class);

            startActivity(intent);
            finish();

        }, 3000);
    }
}
```

---

# ⏱ Splash Screen Delay

You can customize the splash duration:

```java
3000 // 3 Seconds
```

---

# 🛠 Technologies Used

- Java
- Android SDK
- XML Layout
- Android Studio

---

# 📱 Use Cases

- Mobile Applications
- Startup Branding
- App Initialization
- Loading Screen
- Authentication Flow

---

# 🎯 Advantages

- Professional UI Experience
- Better Branding
- Smooth Application Startup
- Improved User Perception
- Easy Resource Loading

---

# 👨‍💻 Developed By

## QuickCodeFix 🚀

### Connect With Me

- GitHub: https://github.com/vaibhavimore1811
- LinkedIn: https://linkedin.com/in/vaibhavi-more-9774a1196
- Instagram: https://instagram.com/quickcodefix

---

# ⭐ Support

If you found this project useful, give it a ⭐ on GitHub and share it with other Android developers.

---

# 📜 License

This project is open-source and free to use.
