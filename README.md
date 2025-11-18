# TASK4-WEB
# Responsive Website (HTML + CSS)

This project is a simple **Responsive Webpage** created using **HTML**
and **CSS media queries**.\
It automatically adjusts layout for **desktop**, **tablet**, and
**mobile** screens.

------------------------------------------------------------------------

## 🚀 Features

-   Fully responsive layout\
-   Mobile-friendly navigation\
-   Flexible content sections\
-   Clean and modern design

------------------------------------------------------------------------

## 📁 Files Included

    index.html   # Main responsive webpage
    README.md    # Documentation

------------------------------------------------------------------------

## 🖥 Desktop View

-   Navigation displayed horizontally\
-   Three content boxes displayed in a row\
-   Larger headings and wider layout

------------------------------------------------------------------------

## 📱 Mobile View (max-width: 768px)

-   Navigation stacked vertically\
-   Content boxes stacked vertically\
-   Reduced padding and text sizes\
-   More compact layout for small screens

------------------------------------------------------------------------

## 📌 How It Works

The responsiveness is achieved using this media query:

``` css
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
    }

    .content {
        flex-direction: column;
        align-items: center;
    }

    .box {
        width: 90%;
    }
}
```

------------------------------------------------------------------------

## ▶️ How to Use

1.  Create a file named **index.html**\
2.  Paste the provided HTML + CSS code\
3.  Open the file in any browser\
4.  Resize the window to observe the responsive behavior

------------------------------------------------------------------------

## ⭐ Contact

Need more features? Want animation? Just ask! 😊
