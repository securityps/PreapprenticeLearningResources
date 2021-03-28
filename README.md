# Learning Materials for Security PS's Cyber Security Pre-Apprenticeship
Security PS's [Cyber Apprentice Program](https://www.securityps.com/cyber_apprentice.html) is designed to provide a pathway for individuals to obtain a cybersecurity penetration testing job at Security PS and its partners in the Kansas City area. This resource helps candidates acquire key skills to qualify for the program. Our program requires students to be able to build web applications, be familiar with using Linux, and have some foundational understanding of networking, HTTP, and security concepts. This resource is intended to help indviduals self-study these topics so they can qualify for the apprenticeship program. Of the tracks below, our top priority for students is software development. Your goal is to be able to build a web application that includes the following features:
* Login process with multiple steps. For example, Username + Password and one of the following:
   * TOTP Token (like Google/Microsoft Authenticator)
   * Hardware Tokens (Like a Yubikey)
   * Email or SMS based one-time tokens
* Forgot password process that allows users to recover their account if they forget the credentials or are locked out
* Registration or user invitiation process that allows users to register for a new accounts or invites them to set up an account
* User Administration including creating, deleting, and modifying users as well as assigning and managing roles, resetting passwords and their secondary login factor
* Features that require that require different levels of role-based or claims-based authorization controls
* "My Profile" feature that allows a user update his or her own personal information, password, and secondary login factor

The application must also satisfy the following technical requirements
* Stores data in a database (SQL or NoSQL). Examples include SQLite, Microsoft SQL Server, Mysql, Postgres, and Mongodb
* Project hosted on GitHub, GitLab, or other public repository including instructions for cloning and running the web application locally
* No secrets, encryption keys, or passwords stored in that repository*  

You can be creative in choosing the purpose for your application. If you need ideas, students in the past have built an HR portal, sports management application, online store, digital wallet, or peer-to-peer payment system. As you work through each learning track, document and demonstrate what you have learned through GitHub repositories and write ups. The Software Development Track below provides resources to learn to write such an application in Microsoft's ASP.NET Core, MVC framework or Node.js the React Framework. There are many other high quality languages and frameworks out there.

When applying for Security PS's Cyber Apprentice Program, Security PS will use the application you build and the artifacts you record as part of the learning process as part of the interview process. You can apply as a high school student, college student, or professional. If you are interested in participating in our program and you live in the Kansas City, Lawrence, Topeka, or surrounding areas, please visit our website and use the [Contact Us](https://www.securityps.com/contact.html) form to request more information.

# Learning Tracks
## Software Development Track
There are many web development languages, frameworks, platforms, and libraries. ASP.NET Core and Node.js are just two; however we have found them quite popular at Kansas City Area companies. The following tutorials are a great starting point for beginning your software development journey.

### C#, ASP.NET Core
*Note: I will gradually replace the .NET Core 3 content with .NET 5 as I identify good tutorials.*

These tutorials focus on a foundational understanding of C#, ASP.NET Core, MVC, WebApi, Entity Framework, and ASP.NET Identity.
1. [Microsoft Learn](https://dotnet.microsoft.com/learn/videos)
    * Intro to Visual Studio
    * C# 101
    * C# Advanced
    * Nuget 101
    * .NET Core 101
    * ASP.NET Core 101        
    * Entity Framework Core 101
1. [FreeCodeCamp: C# Tutorial - Full Course for Beginners](https://www.youtube.com/watch?app=desktop&v=GhQdlIFylQ8)
1. [FreeCodeCamp: ASP.NET 5](https://www.youtube.com/watch?v=Pi46L7UYP8I&lc=Ugy20ltmTAEYwUVAu6t4AaABAg)
1. The following playlist contains older videos covering ASP.NET Core 2.1. However, it has the best explanation of using ASP.NET Identity for login, authorization, roles, and more. Here's a subset of videos to get started, but look through any videos related to ASP.NET Identity, Registration, Login, Roles, UserManager, SignInManager, and more. They will not 100% match up with the latest version of ASP.NET or MVC, but they will be pretty similar.
    * [ASP NET Core Identity tutorial from scratch](https://www.youtube.com/watch?v=egITMrwMOPU&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU)
    * [Register new user using asp net core identity](https://www.youtube.com/watch?v=sPbDrqpme_w&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU)
    * [ASP NET Core Identity UserManager and SignInManager](https://www.youtube.com/watch?v=TfarnVqnhX0&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU)
    * [ASP NET core identity password complexity](https://www.youtube.com/watch?v=kC9qrUcy2Js&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU)
    * [Show or hide login and logout links based on login status in asp net core](https://www.youtube.com/watch?v=YLAHIZmO2PI&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=69)
    * [Implementing login functionality in asp net core](https://www.youtube.com/watch?v=9d8DXXc71RI&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=70)
    * [Authorization in ASP NET Core](https://www.youtube.com/watch?v=uET7MjhUeY4&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=71)
    * [Extend IdentityUser in ASP NET Core](https://www.youtube.com/watch?v=NV734cJdZts&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=77)
    * [Creating roles in asp net core](https://www.youtube.com/watch?v=TuJd2Ez9i3I&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=78)
    * [Get list of roles in asp net core](https://www.youtube.com/watch?v=KGIT8P29jf4&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=79)
    * [Edit role in asp net core](https://www.youtube.com/watch?v=7ikyZk5fGzk&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=80)
    * [Add or remove users from role in asp net core](https://www.youtube.com/watch?v=TzhqymQm5kw&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=81)
    * [ASP NET Core role based authorization](https://www.youtube.com/watch?v=DXVe6skc42k&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=82)
    * [Show or hide navigation menu based on user role in asp net core](https://www.youtube.com/watch?v=IPjK65ehQBg&list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU&index=83)  * 
3. [Bootstrap Tutorial For Beginners by kudvenkat](https://www.youtube.com/playlist?app=desktop&list=PL6n9fhu94yhXd4xnk-j5FGhHjUv1LsF0V)
4. [WebApi Tutorial for Beginners by kudvenkat](https://www.youtube.com/playlist?app=desktop&list=PL6n9fhu94yhW7yoUOGNOfHurUE6bpOO2b)
5. [.NET Core 3.1VC REST API - Full Course
 by Les Jackson](https://www.youtube.com/watch?app=desktop&v=fmvcAzHpsk8)
1. [Design Patterns Tutorial for Beginners](https://www.youtube.com/playlist?app=desktop&list=PL6n9fhu94yhUbctIoxoVTrklN3LMwTCmd)


### Node.js, JavaScript, MongoDB
1. [FreeCodeCamp: Responisve Web Design](https://www.freecodecamp.org/learn/responsive-web-design/)
1. [FreeCodeCamp: JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/)
1. [FreeCodeCamp: Front End Development Libraries
](https://www.freecodecamp.org/learn/front-end-libraries/)
1. [FreeCodeCamp: APIs and Microservices](https://www.freecodecamp.org/learn/apis-and-microservices/)
1. [FreeCodeCamp: Information Security
](https://www.freecodecamp.org/learn/information-security/)

### Related Skills
Consider learning to use Git and GitHub early on in the programming track so you can place your code in your own personal repository. You can then show it off to future employers.
1. [FreeCodeCamp: Git and GitHub for Beginners - Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk)

## Linux Track
Learn Linux by installing it in a virtual machine such as Virtual Box or Hyper-V, and then try to use it. These tutorials can help, but using it is the best way to learn Linux. If you are unsure which distribution to choose, start with either Ubuntu or Kali Linux.
1. [Linux Journey](https://linuxjourney.com)
2. [TryHackMe: Linux Fundamentals](https://www.youtube.com/playlist?list=PL0iJrrpaWpyW9FQqI_TMJiuGpLJrXGVvA)
   * Try Their Free Course: [Linux Fundamentals](https://tryhackme.com/module/linux-fundamentals)
   * Try Their Free Course: [Linux Modules](https://tryhackme.com/room/linuxmodules)
3. [Geek's Lessons: Linux Command Line Full course: Beginners to Experts. Bash Command Line Tutorials](https://www.youtube.com/watch?v=2PGnYjbYuUo&feature=youtu.be)
4. [Linux for Ethical Hackers (Kali Linux Tutorial)](https://www.youtube.com/watch?v=lZAoFs75_cs&feature=youtu.be)
5. [edureka!: Linux Administration Tutorial](https://www.youtube.com/playlist?app=desktop&list=PL9ooVrP1hQOH3SvcgkC4Qv2cyCebvs0Ik)


## Computer Science Track and How Things Work
### Computer Science
1. [Khan Academy AP Computer Science Principles](https://www.khanacademy.org/computing/ap-computer-science-principles)
    * Digital Information
    * The Internet
    * Online Data Security
### TLS
1. [25 Years of SSL - Secure(ish) Sockets Layer - Scott Helme](https://www.youtube.com/watch?v=Do0RfWqXtvw)

### General Networking
1. Try Hack Me: [Introductory Networking](https://tryhackme.com/room/introtonetworking)
 
### HTTP
1. [The Tangled Web: Chapter 3 HTTP](https://nostarch.com/download/tangledweb_ch3.pdf)
1. [OdeToCode: A Software Developer's Guide to HTTP](https://odetocode.com/articles/741.aspx)
1. [HTTP Crash Course](https://www.youtube.com/watch?v=iYM2zFP3Zn0&feature=emb_logo) (Just the first 17 minutes)2. 

## Foundational Certifications
While earning certifications may not be your goal, these provide a foundational knowledge of networking and security concepts.
### A+
1. [Professor Messer A+](https://www.youtube.com/playlist?list=PLG49S3nxzAnmwkCAdWUgCFvVK4IxMBTmb) (Focus on Operating Systems)
### Network+
1. [Professor Messer Network+](https://www.youtube.com/playlist?list=PLG49S3nxzAnmpdmX7RoTOyuNJQAb-r-gd)
1. [FreeCodeCamp: Network+](https://www.youtube.com/watch?v=qiQR5rTSshw&feature=youtu.be)
### Security+
1. [Professor Messer Security+](https://www.youtube.com/playlist?list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8)
1. [My CS - Security+](https://www.youtube.com/watch?v=O4pJeXgOJDs&feature=youtu.be)
