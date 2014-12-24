---
layout: article
permalink: /setup/
title: "Setup"
toc: true
share: false
noindex: true
---

Setting up the workflow is easy, you just need to follow these steps:-


## Create a Spotify Application

* Create an [Application on Spotify](https://developer.spotify.com/my-applications) (this is for both free and premium users)
    * You can set Application Name and Description to whatever you want
    * ***Redirect URI must be set to*** `http://localhost:15298/callback.php`
    
**Warning:** Make sure to click 'Save' button once you set the Redirect URI 
{: .notice-danger}

<figure>
	<a href="http://cl.ly/image/0h2F1z232Q2p/Capture_d%E2%80%99e%CC%81cran_2014-11-04_a%CC%80_11_13_50.png"><img src="{{ site.url }}/images/setup1.png"></a>
	<figcaption>Example of Spotify Application (click to enlarge).</figcaption>
</figure>


## Create the library

* Invoke the workflow (with keyword `spot_mini`, or with an [hotkey]({{ site.url }}/articles/hotkeys) ) and follow the steps as below by copy/pasting the Client ID and Client Secret into Alfred window when asked:

<figure>
	<a href="{{ site.url }}/images/setup.gif"><img src="{{ site.url }}/images/setup.gif"></a>
	<figcaption>Paste Client ID and Client Secret (click to enlarge).</figcaption>
</figure>


* Invoke the workflow again and select Authenticate with Spotify, your web browser will open and you'll be prompted to login with Spotify and allow access to your application. 
At the end you should see a message like this:-

>Hello <your name here> ! You are now successfully logged and you can close this window.

* Invoke the workflow again and Create the library.

* You can check progress by invoking the workflow again:-

<figure>
	<img src="{{ site.url }}/images/setup2.jpg"></a>
	<figcaption>See progress by invoking workflow.</figcaption>
</figure>


* After some time, you should get a notification saying that library has been created.

<figure>
	<img src="{{ site.url }}/images/setup3.jpg"></a>
	<figcaption>Library created (43 seconds for 2500 tracks).</figcaption>
</figure>

* Then you can use and enjoy the workflow. The artworks are downloaded in the background, you should get a notification when background download starts:-

<figure>
	<img src="{{ site.url }}/images/setup4.jpg"></a>
	<figcaption>Notification for the start of background download of artworks.</figcaption>
</figure>

* During that time, you can use the workflow (you'll see the progress at the top of main menu), and you can see some blank artworks:-

<figure>
	<img src="{{ site.url }}/images/setup5.jpg"></a>
	<figcaption>Example of blank artworks until the end of background download is over.</figcaption>
</figure>



