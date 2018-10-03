---
layout: home
title: Home
---

# Jeff Meyerhoff

Mobile application developer working in Xamarin C# .NET, with experience in iOS Objective-C, Android Java, and JavaScript-based applications.

**Resume:** <a href="/assets/documents/Jeff Meyerhoff Resume October 2018.pdf"><img src="/assets/images/icons8-pdf-100.png" style="height: 22px; width: 22px;"/> Adobe PDF</a> <a href="/assets/documents/Jeff Meyerhoff Resume October 2018.docx"><img src="/assets/images/icons8-microsoft-word-100.png" style="height: 22px; width: 22px"/> Microsoft Word .docx</a> <a href="/assets/documents/Jeff Meyerhoff Resume October 2018.doc"><img src="/assets/images/icons8-word-100.png" style="height: 22px; width: 22px;"/> Word Legacy .doc</a>

**GitHub:** <a href="https://github.com/jeffington">jeffington</a>

**Email:** <a href="mailto:jeff@jdmlabs.org">jeff@jdmlabs.org</a>

## About Me
<figure class="figure float-right" style="margin-left: 10px;">
  <img src="/assets/images/jeff-torrey-pines18.jpg" class="figure-img img-fluid rounded" alt="Torrey Pines State Park. I'm on the right trying not to drop my phone while taking a picture.">
  <figcaption class="figure-caption">Me on the right, also taking the photo @ Torrey Pines State Park</figcaption>
</figure>

Hi, I'm Jeff Meyerhoff and I'm a mobile application developer living and working in Chicago, IL. Since graduating with a B.S. in Computer Science from Grand Valley State University in 2010, I have been working as a contractor and consultant developing consumer-facing mobile apps for a variety of clients.

For the last five years I've worked with Elite Electronic Engineering in Downers Grove, IL. We created an app for iPad called C-130J preTOLD (or just preTOLD). We used Visual Studio for Mac and the Xamarin tools to re-use code from a legacy Windows C# .NET application and build a completely new user interface on top of it.

## Projects

---

### C-130J preTOLD™ for iPad

_Elite Electronic Engineering (2014 - Present)_

<img class="icon-img float-left" src="/assets/images/projects/pretold/pretold-app-icon-96.png" />

C-130J preTOLD is a flight planning application for U.S. Air Force pilots of the Lockheed Martin C-130J cargo airplane.

I worked with Elite to design the user interface for preTOLD. The main goal of the application is for pilots to think through flight scenarios that have varying weather or runway conditions. It is important that pilots are able to quickly switch between these scenarios and compare them to each other. Our interface has dedicated buttons to create, save, and view saved flight scenarios. By putting this functionality at the top-left of the screen, users of preTOLD don't have to dig into menus or browse files to open, modify, and save their flight plans. As a result, the user feedback we get from pilots and flight instructors is overwhelmingly positive.


I implemented our design using the Xamarin.iOS tools. We chose Xamarin because Elite had an existing Windows .NET codebase. Xamarin enabled us to re-use the exact same calculation code across both Windows and iOS. To facilitate even more code sharing, we designed the data model using the ViewModel design pattern. This enabled us to share some UI logic (such as input validation) and has made testing and general maintenance much easier.

One of the major features of preTOLD is the ability to export your flight plans as a PDF "TOLD Card". The TOLD Card is a standardized way of displaying and sharing flight information. Using the application <a href="https://www.paintcodeapp.com">PaintCode</a>, I created the TOLD Card as a custom view. This enabled us to easily switch between light and dark color schemes, export the TOLD Card to PDF without a third party library, as well as enable other custom interactions.

Developed with C#, .NET, and Xamarin iOS tools.

Only available on the Apple B2B Store. Product demos available upon request. Learn more at [C-130J preTOLD™ Product Page](https://www.elitetest.com/engineering-services/aviation-software-services/c-130-pretold), [Elite Homepage](www.elitetest.com/)


<a href="/assets/images/projects/pretold/screenshot-port-1.png"><img src="/assets/images/projects/pretold/screenshot-port-1.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-2.png"><img src="/assets/images/projects/pretold/screenshot-port-2.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-3.png"><img src="/assets/images/projects/pretold/screenshot-port-3.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-4.png"><img src="/assets/images/projects/pretold/screenshot-port-4.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-5.png"><img src="/assets/images/projects/pretold/screenshot-port-5.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-6.png"><img src="/assets/images/projects/pretold/screenshot-port-6.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-7.png"><img src="/assets/images/projects/pretold/screenshot-port-7.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-8.png"><img src="/assets/images/projects/pretold/screenshot-port-8.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-9.png"><img src="/assets/images/projects/pretold/screenshot-port-9.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-10.png"><img src="/assets/images/projects/pretold/screenshot-port-10.png" alt="" class="img-thumbnail img-ipad-port"></a>

_The main page of preTOLD, left panel is input, right panel is output_

<a href="/assets/images/projects/pretold/screenshot-port-11.png"><img src="/assets/images/projects/pretold/screenshot-port-11.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-12.png"><img src="/assets/images/projects/pretold/screenshot-port-12.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-13.png"><img src="/assets/images/projects/pretold/screenshot-port-13.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-14.png"><img src="/assets/images/projects/pretold/screenshot-port-14.png" alt="" class="img-thumbnail img-ipad-port"></a>
<a href="/assets/images/projects/pretold/screenshot-port-15.png"><img src="/assets/images/projects/pretold/screenshot-port-15.png" alt="" class="img-thumbnail img-ipad-port"></a>

_TOLD Card Page in preTOLD, light and dark modes, and magnified sections_

### Cardley

_Tidal Commerce formerly Cardley (2015)_

<img class="icon-img float-left" src="/assets/images/projects/cardley/cardley-app-icon-96.png">

Cardley was a customer loyalty program for restaurants and merchants.

I was hired to develop Cardley as a kiosk-style Android app. It replaced the host device's default Android Launcher (home screen) and guided users through the Cardley account sign up process. It integrated with an external credit card reader that connected through the 3.5mm audio port. It then used the card data to create an account with a third party PCI compliant API provided by [Linkable Networks](https://linkablenetworks.com). After registering the user, future credit card transactions would automatically receive discounts and rewards.

Shortly after completing the application, Cardley was unable to secure funding for continued development and a production release.

Developed with Java and the Android Development Tools.

<a href="/assets/images/projects/cardley/cardley-screenshot-1.png"><img src="/assets/images/projects/cardley/cardley-screenshot-1.png" alt="" class="img-thumbnail img-kiosk-land"></a><a href="/assets/images/projects/cardley/cardley-screenshot-2.png"><img src="/assets/images/projects/cardley/cardley-screenshot-2.png" alt="" class="img-thumbnail img-kiosk-land"></a><a href="/assets/images/projects/cardley/cardley-screenshot-3.png"><img src="/assets/images/projects/cardley/cardley-screenshot-3.png" alt="" class="img-thumbnail img-kiosk-land"></a><a href="/assets/images/projects/cardley/cardley-screenshot-4.png"><img src="/assets/images/projects/cardley/cardley-screenshot-4.png" alt="" class="img-thumbnail img-kiosk-land"></a><a href="/assets/images/projects/cardley/cardley-screenshot-5.png"><img src="/assets/images/projects/cardley/cardley-screenshot-5.png" alt="" class="img-thumbnail img-kiosk-land"></a><a href="/assets/images/projects/cardley/cardley-screenshot-6.png"><img src="/assets/images/projects/cardley/cardley-screenshot-6.png" alt="" class="img-thumbnail img-kiosk-land"></a>

_The application guided the user through signing up, reading their credit card from the reader, and creating an account_


### PlayTunes for Android 

_Independently Released (2010 - 2015)_

<img class="icon-img float-left" src="/assets/images/projects/playtunes/playtunes3-app-icon-96.png"/>

PlayTunes was originally written for Android 1.5 Cupcake in 2010. It was released as a completely free app and it accrued over 100 thousand downloads over its lifetime. In that time, I kept it up-to-date with the rapidly evolving platform standards of Android.

Even though the application is no longer under active development, the user interface has aged pretty well and resembles other modern music applications such as Spotify and Pandora.

Developed with Java and the Android Development Tools.

Source code available at <a href="https://github.com/jeffington/PlayTunes">GitHub jeffington/PlayTunes</a>

<a href="/assets/images/projects/playtunes/screenshot-1.png"><img src="/assets/images/projects/playtunes/screenshot-1.png" alt="" class="img-thumbnail img-android-port"></a><a href="/assets/images/projects/playtunes/screenshot-2.png"><img src="/assets/images/projects/playtunes/screenshot-2.png" alt="" class="img-thumbnail img-android-port"></a><a href="/assets/images/projects/playtunes/screenshot-3.png"><img src="/assets/images/projects/playtunes/screenshot-3.png" alt="" class="img-thumbnail img-android-port"></a><a href="/assets/images/projects/playtunes/screenshot-4.png"><img src="/assets/images/projects/playtunes/screenshot-4.png" alt="" class="img-thumbnail img-android-port"></a><a href="/assets/images/projects/playtunes/screenshot-5.png"><img src="/assets/images/projects/playtunes/screenshot-5.png" alt="" class="img-thumbnail img-android-port"></a><a href="/assets/images/projects/playtunes/screenshot-6.png"><img src="/assets/images/projects/playtunes/screenshot-6.png" alt="" class="img-thumbnail img-android-port"></a><a href="/assets/images/projects/playtunes/screenshot-7.png"><img src="/assets/images/projects/playtunes/screenshot-7.png" alt="" class="img-thumbnail img-android-port"></a><a href="/assets/images/projects/playtunes/screenshot-8.png"><img src="/assets/images/projects/playtunes/screenshot-8.png" alt="" class="img-thumbnail img-android-port"></a>


### Savor for iPad

_Tidal Commerce formerly Savor (2014)_

<img class="icon-img float-left" src="/assets/images/projects/savor-app-icon-96.png">

Savor was a retail offer and deal website.

I was hired to create an iPad app that presented a version of the Savor website that was customized with a Flipboard-style page layout for iPad. The iPad app used the (Card.io)[https://www.card.io] library to let users register for accounts using their credit card. I coordinated with the remote Savor web development team in Hyderabad to make sure that our native code and web code worked together.

Savor was unable to secure funding for continued development.

Developed with Objective-C, iOS's UIWebView, JavaScript, HTML, and CSS.


<a href="/assets/images/projects/savor/savor-screenshot-1.jpg" data-gallery="#gallery-savor"><img src="/assets/images/projects/savor/savor-screenshot-1.jpg" alt="" class="img-thumbnail img-ipad-land"></a>
<a href="/assets/images/projects/savor/savor-screenshot-2.jpg" data-gallery="#gallery-savor"><img src="/assets/images/projects/savor/savor-screenshot-2.jpg" alt="" class="img-thumbnail img-ipad-land"></a>
<a href="/assets/images/projects/savor/savor-screenshot-3.jpg" data-gallery="#gallery-savor"><img src="/assets/images/projects/savor/savor-screenshot-3.jpg" alt="" class="img-thumbnail img-ipad-land"></a>
<a href="/assets/images/projects/savor/savor-screenshot-4.jpg" data-gallery="#gallery-savor"><img src="/assets/images/projects/savor/savor-screenshot-4.jpg" alt="" class="img-thumbnail img-ipad-land"></a>
<a href="/assets/images/projects/savor/savor-screenshot-5.jpg" data-gallery="#gallery-savor"><img src="/assets/images/projects/savor/savor-screenshot-5.jpg" alt="" class="img-thumbnail img-ipad-land"></a>
<a href="/assets/images/projects/savor/savor-screenshot-6.jpg" data-gallery="#gallery-savor"><img src="/assets/images/projects/savor/savor-screenshot-6.jpg" alt="" class="img-thumbnail img-ipad-land"></a>
<a href="/assets/images/projects/savor/savor-screenshot-7.jpg" data-gallery="#gallery-savor"><img src="/assets/images/projects/savor/savor-screenshot-7.jpg" alt="" class="img-thumbnail img-ipad-land"></a>


### Notepad RT for Windows 8

_Independently Released (2012)_

<img class="icon-img float-left" src="/assets/images/projects/notepadrt/notepadrt-app-icon-96.png">

Notepad RT is the missing code editor for developers and geeks for Windows 8 with rich support for text manipulation and syntax highlighting. Built specifically for Windows 8, Notepad RT matches the features and performance of desktop-class editors. Notepad RT is compatible with x86, x64, and ARM. It features syntax highlighting for HTML, CSS, JavaScript, PHP, Python, Ruby, C/C++, C#, Java, and Markdown, several popular Dark and Light Syntax highlighting themes to choose from, live syntax checking for JavaScript and CSS, automatic indention, Line wrapping, and Code folding, highlighting of matching parentheses and selected line, find and replace using regular expressions, use the Share Charm to send code via IM or Mail, and toggle invisible characters.

Developed with JavaScript, HTML, and CSS.

Source code available at <a href="https://github.com/jeffington/Notepad-RT">GitHub jeffington/Notepad-RT</a>

<a href="/assets/images/projects/notepadrt/notepadrt-screenshot1.jpg"><img src="/assets/images/projects/notepadrt/notepadrt-screenshot1.jpg" alt="" class="img-thumbnail img-windows-land"></a><a href="/assets/images/projects/notepadrt/notepadrt-screenshot2.jpg"><img src="/assets/images/projects/notepadrt/notepadrt-screenshot2.jpg" alt="" class="img-thumbnail img-windows-land"></a>


### SparkHire Mobile for iOS and Android

_SparkHire (2011-2013)_

SparkHire is a job search and video interviewing service. I worked alongside with the SparkHire web development team to design and create an iOS and Android application that mirrored the functionality of the website. The app allowed users to sign up with SparkHire, edit their profile, record videos and post them from within the app.

[SparkHire Homepage](https://sparkhire.com)