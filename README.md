
# open-integrity-check

---
**Open, EU located, hardware-backed attestation for Android & later Linux phones without Google Play Services required.**

## What is this about?

What is maybe the biggest hurdles for adoption of a new phone OS? Blackberry and Microsoft had to learn it the hard way. **Users will not use a phone that does not provide their favorite apps.**
Nowadays, for most Europeans, there are only two options to choose from for a phone OS.
Maybe three, but two of these would be controlled by American companies and one by a Chinese one. No real European alternative for the casual user.
There are good alternatives to googles Android, that make use of the same Open Source Code that powers the core of all Android phones.
/e/OS is an excellent open source alternative, that is can even be shipped directly with a European phone, the Fairphone. But a glaring problem remains, most banking apps do currently not support this operating system. Many security focused apps rely on Googles Integrity API.
This means that without google services, they do not work. So you buy a phone, with an European operating system, just to install google Services on your phone, to make it work properly, "whats the point?", many people would ask.

I think it is time for an alternative to Google. And this inherits an alternative to the **Google Integrity API** on Android.

## What is the Plan? (very rough overview)

* This project is still in an early planning phase, so before diving too deep into technical details or implementation I will gather information and speak to users, banks, and OS Devs like /e/OS. And gather information, potential problems and wishes.
* Go deeper into the development plan and create a detailed road map
* Apply for EU funding
* Develop & conducts pendents to provide a robust secure solution

## Technical High level Overview

Currently the Integrity checks run through googles servers.
![Overview of the current setup with the google integrity API](/assets/Overview-Current-Setup.png? "Overview of the current setup with the google integrity API")

I propose an alternative version with a European open source Platform instead.

![Overview of the planned setup, replacing the google integrity API](/assets/Overview-Future-Setup.png)
