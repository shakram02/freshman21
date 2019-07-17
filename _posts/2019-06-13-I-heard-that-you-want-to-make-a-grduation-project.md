---
published: true
title: I heard that you want to make a graduation project
layout: post
author: Shakram02
category: tech
tags: engineering
comments: true
---
![intro-image]({{site.baseurl}}/images/grad-proj/tunnel-end.jpg)
Congratulations!, you're almost there. That's your final college project but you have no clue what to do, most of us (me included) want to make something fancy and cool, some of us just want to get the hell out of here.
<!-- end_excerpt -->

Okay, let me be clear about this topic, I'll just state things in a straight forward manner, truth might be cold and unbelievable, I thought this way when my older friends told me that my graduation project is a **YACP** (yet another college project). But I was really short on idea and to be honest, I was one of those who wanted to get the hell out of here, I took the easy path and joined a group of nerds (my friends) and planned to do the least amount of effort possible (since they're smart enough to get everything done on their own, I can be less proactive, do less work and don't really seem like a lazy person)

Hmm, now I think "Opps!, I could've done better" but it's too late for me anyways, but it's not for you.

This is my point of view, after 1 year of graduation. the graduation project is really a YACP, but I think that if you do something that's really interesting to you, you can get things going smoothly while gaining lots of goodies by the end of the year, we all know that grades are guaranteed in the graduation project, so what's left?

Everyone of us wants to make the coolest graduation project or make something that never existed, tbh this is impossible at our technical level, because the truth is that if you want to make something that never existed you must already be on the edge of the tech. field you're going into, which is almost impossible if you're just about to graduate, so hopefully we're on the same page by now.

Instead of making something super fancy, why not focus on building a system that's manageable but complex at the same time, something that already exists, but you know (or at least you should) that if you want to learn how something works you must make it yourself. So, this is my main point for the rest of this article, but before going away saying that I'm just boring, why don't you read along for just a while, I'll put a list of ideas right in front of you.

Yes, one more thing. I'm not really into ML and trendy stuff, so pardon than I probably won't mention anything heavy regarding those, if something is hot that doesn't meant hat it'll fit you, be wise when choosing.

## Don't start too early
Counterintuitive? yes, I know. But that's like getting excited for something so early that by the time when the real work starts you'll have already lost interest. Make sure that everything is settled first, pick a team and an idea then contact the professor, it's true that many people contact them early, this happens every year but those teams just fail (for whatever reason), so just relax, get a good idea and make a good project.

## What should the professor do?
No, not help you with technical knowledge. The professor's main job (from my point of view) is just to make sure that you're on schedule.

## Do it small but with an "industrial grade quality"
It doesn't matter how cool your project looks, but will it "just work" in the toughest situations? is it well-designed? is it complete? is it fully tested?
That's what will give you an edge, you can provide just the core functionality but with industrial grade quality, I think that's much better than delivering something with lots of additions but none of them is perfect. *Make something that does only one thing in the best possible way*, that's a core part in Linux philosophy.

## Augmented Reality (AR) Applications

![AR-Routing](/images/grad-proj/ar-routing.jpg)

AR is currently a hot topic, Snapchat is an AR application as it places masks on your face and Pokemon Go was an AR game, Google the concept, personally, I don't think Virtual Reality will go anywhere but AR is a game changer. For example, imagine that you make an app that uses Google Maps to guide car drivers using AR, the phone will be fixed towards the road and using GPS and Maps routing you'll display an arrow to tell the driver where to go.

You can make something for example to project some decoration on a given object like changing a wall painting or adding some furniture to an existing room.
You can mix AR with IoT and let the user control a device once it's pointed at by the screen without having a built in device on that screen. This idea is already implemented by MIT in their [Reality Editor](http://realityeditor.org/) the videos are more than enough to show you how cool is that.

![Reality-editor](/images/grad-proj/reality-editor.jpg)

One last idea is that you can make a shared 3D painting canvas, so you and a couple of people will join the same AR session and draw or do something together. If you're doing it on Android, checkout [ARCore](https://developers.google.com/ar/) for iOS checkout ARKit.

<small>Photo [source](http://www.iphonehacks.com/2017/05/apple-bosch-ar-experience-iphone-8.html)</small>

## PiFloor

![PiFloor](/images/grad-proj/pifloor.png)

PiFloor started with my professor Dr. Shaimaa Lazem, she had an older version that wasn't reliable in real world. She told me about it when I asked her if there's any project I can work on that's related to education.
PiFloor is some sort of smart floor for students to gamify MCQ questions. PiFloor is mainly aimed to underprivileged communities that don't have enough resources to access high quality education, tech solutions are always the answer to problems like that.
The new version of [PiFloor](https://github.com/shakram02/PiFloor) uses Google mobile vision API. It has both an Android and a Web applications, that communicate together. 

The main missing part for a functioning prototype to get into sun light is the UI of the Android application and a making the embedded web server able to serve media file in chunks. If you select this project you'll be warmly welcomed by Dr. Shaimaa if you want her to be your mentor (as she's the owner of the idea) and mentoring by me, the required work is mainly Android and if you want to add more features you can do whatever or if you want to check the current [issues](https://github.com/shakram02/PiFloor/issues), one suggestion might be that we take the app into AR and let alone mobile vision API.

## Make a custom input device

![HID-Keyboard](/images/grad-proj/hid-keyboard.jpg)

Huh? what's that? okay let me tell you, we all know the keyboard and mouse in their traditional ways, but actually those devices work based on a protocol called the Human Interface Device (HID), you can do really cool stuff, think about making a mouse that uses an ultrasonic sensor to move to a certain location on the screen, this guy made a tiny custom [keyboard](https://youtu.be/Uf9FsZj-DzE) check full instructions in the description.

It's also a challenge to make "new" input devices for computers, people say that mouse and keyboard are now old fashion and it's time for some new input devices, stuff like the pen for example, something newer and better.

<small>Image [source](https://www.sparkfun.com/tutorials/337)</small>

## Make an autonomous robot / drone

![Robot](/images/grad-proj/rpi-robot.jpg)

You're into embedded systems? why not make a robot that can avoid obstacles using some computer vision (not ultrasonic FGS), maybe you can add a speaker to it so the robot says "I found X in front of me and I'm turning Y", to make it more fun. I suggest that you find a way to plug in a PID controller and better, a Kalman filter, those will put you in front of many other people. If you want to do more, why not make it a delivery robot? make it explore some space and tell it to move from room X to room Y.

For the drone, you can use [AirSim](https://github.com/microsoft/AirSim), here is a [video](https://youtu.be/-WfTr1-OBGQ) to implement it, this is a vehicle simulator that runs on Unreal game engine, you might need [ROS](https://www.google.com/search?client=firefox-b-d&q=ros)

<small>Image [source](https://maker.pro/raspberry-pi/projects/build-raspberry-pi-rover-robot-smartphone-control)</small>

## Port a programming language to a platform

This might seem a bit wierd; C runs on almost every micro controller simply because there's a way to transform C code into the microcontroller's binary executable. This can happen with any language, some guy on the internet [ported Rust to AVR](http://jakegoulding.com/), you don't need to port everything you might want to port just a subset of the language or its features.

## Make an Operating system

Why would anyone need to do that again? Okay, good question. but in tech when it's really techy we need to make custom stuff that's fully customizable to a certain use case. that's why people [still](https://github.com/topics/operating-system) make operating systems. The operating system get hardware dependent at some points, you can choose to do one of those targets

- Your PC (a.k.a intel processors)
- A Raspberry PI (ARM intel processors) [tutorial](https://github.com/s-matyukevich/raspberry-pi-os)

Here is a good tutorial in [Rust](https://os.phil-opp.com/), you can follow this YouTube [playlist](https://www.youtube.com/playlist?list=PLHh55M_Kq4OApWScZyPl5HhgsTJS9MZ6M) or [this](https://github.com/tuhdo/os01/) book

Something that's worth noting that if you choose to work with ARM, you can think about making about an operating system for your mobile phone or modify android (maybe your first smartphone) to be a [touch pad](https://forum.xda-developers.com/desire-816/orig-development/hid-compliant-tp-kb-kernel-a5ul-t3705817) or something more worthy that just letting it collect dust.

## Grade management through Google Drive
Let me tell you a secret, your grades are almost always at mess when us (TAs) put them in sheets, anything can just go wrong since the sheet is fully editable by all the teaching team. 

The suggested solution is that you make some program to track your grades lab by lab and base it on Google Drive APIs (Sheets, Mail, Sites, Forms,..etc). Google APIs can be consumed using Google App Script (Javascript-ish language) or using some of the more native languages that run on your PC (Java, Python, ...etc)

For example, this solution should be able to import an excel sheet containing the students and their IDs, then the TA will hit a button to create a new assignment or a new lab or project, whatever. 

Then in delivery time a Google form will be displayed to the TA that they'll use to enter the grades, instead of searching for the student in the sheet each time, you might want to get fancy and make the application send email notifications to students before their deadline, remove duplicate submissions and so on. Google didn't make those APIs without knowing that there's a whole lot of money behind them, so this project might be your first step to create business solutions using Google's APIs, it'll also get you introduced to Google Cloud Platform, which is nice to know.

## Mass file transfer

Problem: I have say 10 people that I want to share some files with in a course, how can I do that an acceptable way with no-setup.

 This can be used in a course where the instructor wants to install software for the audience or just whatever. You can think about hosting a web server and using WebsSockets to distribute the data with a nice web interface and then you should also make whoever gets the file transmit it to their neighbors, 
 
 Can you make all that processes automated?

## Make Blynk

![Blynk-im](/images/grad-proj/Blynk_logo_diamond.png)

[Blynk](https://blynk.io/) is a platform to control IoT devices over the internet, in its essence it's a hashmap that relates your Android phone to your device and sends commands to it. You can do lots of [stuff](https://www.hackster.io/blynk) with it.
If you finished your prototype early, try implementing a version on MQTT on your server

## Make an Arduino-ish platform

![IOIO-Robot](/images/grad-proj/ioio-robot.jpg)

Software today is all about abstractions, Arduino abstracted the AVR API that is closely related to hardware, [IOIO](https://github.com/ytai/ioio) also does the same but it's Android enabled, Google has a cool [experiment](https://experiments.withgoogle.com/android-ioio) with IOIO, why don't you make something like that for a given microcontroller family? provide the libraries necessary and a VSCode plugin to support your platform

## Make an Arduino IDE on Android

It already exists also, maybe you can find some opensource project and improve it or make your own so you can get more familiar with Android internals (the Linux underneath) and maybe some USB stuff. 

If you want to do more, you can add a [scratch-](https://scratch.mit.edu/)like interface. If you want to simplify things you can checkout the [Firmata](https://www.arduino.cc/en/reference/firmata) protocol and build on top of it to make your IDE.

## You want to make an Android application?

Okay, there are a few things that you should be using; Unit testing, [MVP](https://github.com/MindorksOpenSource/android-kotlin-mvp-architecture)/MVVM design pattern, Kotlin, Gradle and dependency injection (using [Dagger](https://github.com/google/dagger)).

You'll probably need all of those once you land your Android job

## Make a 3D printer (or start with a plotter -2D-)

![3d-print](/images/grad-proj/3d_printer.png)

3D printers are much fun to do, don't worry about the hardware, you can find it in [Robota](https://www.google.com/maps/place/ROBOTA/@31.207743,29.9248163,17z/data=!3m1!4b1!4m5!3m4!1s0x14f5c47e31255bfb:0x26dd916269dda54f!8m2!3d31.207743!4d29.927005) and ask them for help. For academic content check out [How To Make (almost) Anything - MIT](http://fab.cba.mit.edu/classes/863.14/) and [Rapid-Prototyping of Rapid-Prototyping Machines - MIT](http://fab.cba.mit.edu/classes/865.15/)

Start small, then grow backwards; start with the program that moves the motors to the correct locations then walk backwards to parsing the input files yourself. You can Google for more resources.

<small>Image [source](https://www.earthmagazine.org/article/changing-landscape-geoscientists-embrace-3-d-printing)</small>

## Final words

You can use those ideas as just a source for inspiration or mix and match them, it's also good to find ways to mix technology with art. Make something that you'd like to be on your CV and that will give you an edge. I tried choosing the easy way and regretted it afterwards, don't repeat my mistake. best of luck.

## Explorables
- Nearby [API](https://developers.google.com/nearby/)
- [WiFi Direct](https://developer.android.com/guide/topics/connectivity/wifip2p)
- [NFC](https://developer.android.com/guide/topics/connectivity/nfc)
- [Bluetooth Low Energy](https://developer.android.com/guide/topics/connectivity/bluetooth-le)
- [Firebase](https://firebase.google.com/)
- [Kickstarter](https://www.kickstarter.com/design-tech?ref=section-homepage-nav-click-design-tech), [Google experiments](https://experiments.withgoogle.com/collections) you can find some good ideas there and [Hackster](https://www.hackster.io) don't forget to checkout the contests and their winners
- Bump [Wikipedia](https://en.wikipedia.org/wiki/Bump_(application)) [video from 2010](https://www.youtube.com/watch?v=N3iWG8qcA70)
- That might be the least interesting thing to do but you can check [my stars](https://github.com/shakram02?tab=stars) on Github
