---
title:  "My OSCP experience"
date:   2020-03-06 18:30:00 +0100
categories: offsec oscp
published: true
---

![](/assets/images/oscp/oscp.png)

I hadn't even heard about OSCP until I noticed that a colleague had taken it early in 2019. So I decided that I want to do the same. Fast forward to November 2019, and I decided it was time to do it. So I did. I want to share a bit about my experience (sorry, no spoilers), and my advice on how to succeed.

## My advice

Unless you're already working as a penetration tester, this should be about learning. And the lab is where you'll learn a lot, so make sure you spend as much time as you can there!

### Pre-PWK advice

PWK is a foundational, entry-level, course. If you want to do it - do it! The listed prerequisites are only _Solid understanding of TCP/IP networking_ and _Reasonable Windows and Linux administration experience_.

If you want to do something to prepare, or need a refresher on TCP/IP, I recommend [eLearnSecurity's PTS](https://www.elearnsecurity.com/course/penetration_testing_student/). PTS is a nice introduction to penetration testing, and has a great chapter on networking basics.

The most important thing you should do before you start, is to ensure that you calendar is empty when your lab time starts.

### PWK advice

- Get as much lab time as you can afford
- Schedule your exam
- Read the PDF - all of it
- Watch the videos - all of them
- Watch the videos for a chapter first, then read the chapter (or the other way around)
- Take notes ([I recommend Markdown in VS Code](/using-vs-code-for-note-taking))
- Always revert (respect other students, back off if the machine was recently reverted)
- Do the exercises and write the lab report
- Spend as much time as you can in the lab, aim high - pwn all the machines!
- Make it a goal to pivot to all networks
- Do all the fun stuff (pivoting, client side attacks)
- Take notes! And make a system for note taking ([I recommend Joplin](https://github.com/thomfre/joplin-infosec-templates/))
- Don't forget post-exploitation, you'll need the information later
- Don't put unnecessary restrictions on yourself - use both Metasploit and the Forums when needed (but do also try to understand what Metasploit do, and try to do the same without)

### Exam advice

- Schedule your exam early (at least one month in advance), and change it later if you need to - this way you can get the day/time you want
- Schedule the exam for a time slot that best fits you - for me this was early (but not too early) in the day, on a Thursday (weekend directly after the report was submitted)
- Get proper rest the two days before the exam
- Prepare your [report template](https://github.com/thomfre/OSCP-Exam-Report-Template) before starting the exam
- Start with the right mentality - you're going to nail this!
- Focus on time management, make a plan and stick to it
- Know your own limits - if you know need to sleep, make time for it!
- Use the same VM as you used for the lab
- Sticking to your methodology is key (which is what the lab is meant to teach you)
- Take breaks - stepping away might be exactly what you need to see that problem in a different light when you come back
- Don't sit and look at scans, have them running in the background while doing other things
- Don't get stuck on one target, take a look at another target when you've been stuck long enough
- Stay hydrated, and don't forget to eat
- Enumerate, enumerate, enumerate!
- Take notes! And screenshots!
- Try Harder! (Don't give up!)

### Recommended tools and resources

- [Joplin](https://joplinapp.org/)
- [Basic Linux Privilege Escalation](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/)
- [Windows Privilege Escalation Fundamentals](https://www.fuzzysecurity.com/tutorials/16.html)
- [Windows / Linux Local Privilege Escalation Workshop - sagishahar/lpeworkshop](https://github.com/sagishahar/lpeworkshop)
- [AutoRecon](https://github.com/Tib3rius/AutoRecon)
- [linPEAS](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/blob/master/linPEAS)
- [winPEAS](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/winPEAS)

## My background

I've been a hobby coder since I was 10, and a professional developer for a long time, so I know my way around a computer. I have also in depth networking knowledge, and have been using tools like Wireshark and Fiddler for many years (for testing and development work). I'm certain that my development background helped me a lot during my PWK journey.

## Pre-PWK

I had zero pen-testing knowledge before I started playing with [Hack The Box](https://www.hackthebox.eu/) in October 2019. I did [eLearnSecurity's Penetration Testing Student](https://www.elearnsecurity.com/course/penetration_testing_student/) in October/November, while continuing to do some HTB. That was enough for me to know that I really wanted to continue on this path, and that I was properly motivated to start on the PWK/OSCP journey.

I spent a lot of time, both before and after starting, reading through reviews, watching videos about PWK/OSCP and collecting information I thought could be useful.

## PWK

I got the 90 day lab option, to make sure I had enough time (especially with Christmas in the middle of the lab time).

To make sure I got the slot I wanted, I scheduled the exam the day after I got access to the labs. Knowing myself, I scheduled for a Thursday with 10am starting time. This would give me enough time to get up, wake up and be ready before starting, and it will give me the weekend to relax after the exam.

I followed the advice I had seen a lot of places, and dedicated the first two weeks to reading the material and doing the exercises. I watched the videos first, before reading and doing the exercises. I made sure to take as much notes as I could, both when reading and when doing the exercises.

I used [Markdown in VS Code](/using-vs-code-for-note-taking) both for general notes, and for exercise notes and the lab report. I've published [my report template and report generation tool on GitHub](https://github.com/thomfre/OSCP-Exam-Report-Template).

It took me about two weeks to finish the videos, the PDF and the exercises.

The labs are way more addictive than I thought they would be, so I ended up spending all the time I had working through them. I finished the last machine just a couple days before OffSec launched the updated PWK. I only did a couple machines in the updated labs, and focused mainly on the PrivEsc chapters in the updated course material.

The plan was to document every single lab machine in my report, just to get training in report writing, but when that plan was quickly thrown out the window when the updated lab was announced - figured time was better spent with the new material. That was a wise decision, I still had more than enough machines in my lab report.

I knew privesc could potentially be my weakest point, so I also went through some of the material in [Windows / Linux Local Privilege Escalation Workshop - sagishahar/lpeworkshop](https://github.com/sagishahar/lpeworkshop).

When I finally stopped asking myself if I was ready or not for the exam, I knew I was ready. This was it - time to do it!

## OSCP Exam

After spending every day working in the labs, I took a break the last days before the exam. To minimize all external factors, I also got a clean machine to use for the exam, and set it up in my home office. I made sure I had enough snacks ready.

![](/assets/images/oscp/desk.png)

I got up early, had a nice breakfast and was ready about 30 minutes before my scheduled start time. I made sure to start the proctoring software, and do the pre-exam steps, 15-20 minutes prior to my exam start time. This ensured that I was ready to start when I got the connection pack.

The proctors were both professional and courteous, and the entire proctoring was very unobtrusive. The software was simple to use, and kept working flawless for the entire duration of my exam.

I had my "battle plan" ready, and knew exactly where I wanted to start. All of my preparation paid of very quickly, and allowed me to focus fully on the tasks in front of me.

The first target took me a bit longer than I had hoped, but the first points were mine after about an hour and a half. I got stuck a couple times, but I had a plan for this as well, and jumped to other targets after being stuck for what I considered to be long enough. This trick was what I needed to get the "passing score", which I got around 7 hours in. But my goal was to get 100%, so I still had more work to do.

I made it almost to the end, and got stuck on the last privesc for several hours. I was almost certain I had the correct idea, but I couldn't get it to work. That's when I realized I had to Try Harder, and don't give up. And that was the motivation I needed to finish the last target at 01:42 - 15 hours and 42 minutes after I started. Didn't see the need for Metasploit or Meterpreter, so I ended up not using any of them.

I decided to go back and try to re-run all the commands I had written down in my notes, to make sure I had all of them written down correctly. I did the first couple machines, then decided to get some sleep. I woke up way earlier than I usually do, checked the last targets, and ended the exam at 07:15 - 21 hours and 15 minutes after I started.

I took a quick break, before starting to work on my exam report. With my [report template](https://github.com/thomfre/OSCP-Exam-Report-Template) ready, this was mostly just copying and pasting from Joplin. I submitted my report at 14:15, and got the receipt confirmation at 14:50.

## The long wait

Then came the part most people don't tell you about. The confirmation email said up to 10 business days waiting time - and that wait was brutal! Even though I was sure I had enough points to pass, I constantly kept thinking about things I maybe had done wrong.

![](/assets/images/oscp/result.png)

Turned out in the end that I didn't do anything wrong, and I finally got the message that I passed the exam! This is a huge reward after a lot of hard work.

The best reward however, is all the new knowledge I've got.

## Time spent

I decided that I wanted to track all the time I spent doing PWK and the exam, so I have very accurate numbers of how much time I used.

Total hours spent: **376**

| Task                     | Hours spent                            |
| ------------------------ | -------------------------------------- |
| Notes, preparation, etc. | 24 hours                               |
| Study (PDF)              | 32 hours                               |
| Study (Videos)           | 19 hours                               |
| Exercises                | 50 hours                               |
| Labs                     | 202 hours                              |
| Lab report               | 24 hours                               |
| Exam                     | 17 hours, 30 minutes (excluding sleep) |
| Exam Report              | 7 hours, 30 minutes                    |

## My timeline

- **November 13th, 2019**: PWK Ordered
- **December 8th, 2019**: Lab time starts
- **December 9th, 2019**: Exam scheduled (February 27th, 2020)
- **December 21st, 2019**: First lab machine pwned
- **February 8th, 2020**: PWK Lab v1 fully pwned
- **February 11th, 2020**: New PWK Lab ordered
- **February 13th, 2020**: Updated material received, and PWK Lab v2 active
- **February 27th, 2020**: Exam started
- **February 28th, 2020**: Exam ended, exam report submitted
- **March 5th, 2020**: Exam result received
