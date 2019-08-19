---
layout: post
title:  "Mengganti Ukuran TextView di Android"
date:   2019-08-19 +0700
categories: android
---
Untuk mengganti ukuran `TextView` kita tinggal menggunakan `android:textSize` seperti berikut

{% highlight xml %}
<TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:text="Hello World!"/>
{% endhighlight %}

Hasilnya seperti berikut

![Tampilan widget textView di design layout](/assets/2019-08-19-mengganti-ukuran-textview-di-android-textsize.png)