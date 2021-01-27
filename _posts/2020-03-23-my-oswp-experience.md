---
title: 'My OSWP experience'
date: 2020-03-23 21:00:00 +0100
categories: certifications
tags: offsec oswp
published: true
---

![](/assets/images/oswp/oswp.png)

After I started looking at OSCP, I also noticed OSWP - which seemed like a much shorter, and simpler, course. I knew it was old, but it was still interesting enough that I wanted to give it a go.

## My advice

### Pre-WiFu advice

Make sure to purchase the correct equipment. I recommend sticking to the recommended hardware (see what I used further down).

### WiFu advice

-   Read all of the PDF, even the highly technical boring stuff
-   Take notes ([I recommend Markdown in VS Code](/using-vs-code-for-note-taking))
-   Do the exercises and write down your steps (good training for the exam report, and nice to have later)
-   Use the latest Kali, or whatever Linux distro you prefer (no need to use the provided image)

### Exam advice

-   Schedule your exam a couple days in advance
-   Schedule the exam for a time slot that best fits you
-   Use the provided report template
-   Keep it simple
-   Take notes and screenshots

## My background

I've been a hobby coder since I was 10, and a professional developer for a long time, so I know my way around a computer. I have also in depth networking knowledge (but not much Wireless), and have been using tools like Wireshark and Fiddler for many years (for testing and development work).

## Pre-WiFu

I didn't do anything to prepare for this, other than purchasing the necessary equipment. The routers OffSec recommends, D-Link DIR-601 and Netgear WNR1000v2 are hard to find now, but I managed to find both used on eBay. The recommended network adapters are much easier to find.

My equipment:

-   D-Link DIR-601
-   Netgear WNR1000v2
-   Netgear WN111v2 (didn't use this one at all)
-   [Alfa AC1900](https://www.amazon.com/gp/product/B01MZD7Z76)
-   [Alfa AWUS036NHA](https://www.amazon.com/gp/product/B004Y6MIXS)

I also had various Windows and Linux clients, some of the exercises was impossible to do with the Windows clients (might have been the hardware that was the issue).

## WiFu

The material starts with a lot of theory. A lot. But I decided to read through all of it, and I'm glad I did, as it made the rest so much easier to understand. It's a great feeling when you fully understand _why_ the attack you're doing works so well. I didn't actually watch all of the videos, but I did read through all of the PDF. And I did all of the exercises, even though WEP is very old and outdated now (Windows 10 almost wouldn't let me connect to it). Some of the exercises are hard to get to work, but it was mostly a lot of fun.

I ended up doing all of the exercises with the **D-Link DIR-601** and the **Alfa AC1900**. I was able to do all of them, except for the fragmentation attack, I couldn't get that to work at all.

The course is a bit old now (and maybe a bit expensive for being so old), but there is still a lot of relevant things to learn. I had fun doing this, and spent a lot more time than I really had to. I took the time I needed to make a lot of notes, and document all the exercises. I've read that a lot of people do this in a weekend, and I think that is doable. But I decided to spend a couple weeks instead, and take it a bit slower.

## OSWP Exam

The OSWP exam is very straight forward, and everything you need to know is in the exam guidelines. I used the provided exam report template, and made sure I documented all my steps along the way.

The exam machine (you SSH into a remote machine to do the attack) worked without any issues, and I was able to do all I had to do within 40 minutes. I didn't use Screen, like some recommend, I just used multiple SSH sessions when I needed it.

I finished my report, submitted it, and got the receipt confirmation within a couple hours.

## The long wait

Then came the long wait again. I was used to this now, after the brutal wait for the OSCP result, and I was pretty confident that I had passed. Four days later, I finally got the confirmation.

![](/assets/images/oswp/result.png)

## Time spent

I decided that I wanted to track all the time I spent doing the course and the exam, so I have very accurate numbers of how much time I used.

Total hours spent: **59**

| Task                     | Hours spent        |
| ------------------------ | ------------------ |
| Notes, preparation, etc. | 2 hours            |
| Study (PDF)              | 27 hours           |
| Study (Videos)           | 1 hour 30 minutes  |
| Exercises/Labs           | 23 hours           |
| Exam                     | 40 minutes         |
| Exam Report              | 1 hour, 30 minutes |

## My timeline

-   **January 23rd, 2020**: WiFu Ordered
-   **January 26th, 2020**: Course material received
-   **March 2nd, 2020**: Course started
-   **March 10th, 2020**: Exam scheduled (March 15th 17:00)
-   **March 15th, 2020**: Exercises done
-   **March 15th, 2020**: Exam done and report submitted
-   **March 19th, 2020**: Exam result received, delivery address submitted
