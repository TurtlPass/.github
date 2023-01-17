<p align="center">
<img src="https://raw.githubusercontent.com/TurtlPass/turtlpass-firmware-arduino/main/assets/icon.png" alt="logo" width=128>
<h1 align="center">TurtlPass</h1>
<p align="center">
<a href="https://github.com/TurtlPass/turtlpass-firmware-arduino"><img src="https://img.shields.io/github/v/release/TurtlPass/turtlpass-firmware-arduino?color=blue&label=Arduino%20Firmware&logo=arduino" alt="Firmware Repo"/></a>
<a href="https://github.com/TurtlPass/turtlpass-android"><img src="https://img.shields.io/github/v/release/TurtlPass/turtlpass-android?color=blue&label=Android%20App&logo=android" alt="Android Repo"/></a>
<a href="https://github.com/TurtlPass/turtlpass-chrome-extension"><img src="https://img.shields.io/github/v/release/TurtlPass/turtlpass-chrome-extension?color=blue&label=Chrome%20Extension&logo=googlechrome" alt="Chrome Extension Repo"/></a>
<a href="https://www.patreon.com/turtlpass"><img src="https://img.shields.io/badge/Patreon-F96854?logo=patreon&logoColor=white" alt="Patreon"/></a>
</p>
<br/>
<p align="center">
With TurtlPass, you can easily and securely generate unique passwords for all of your accounts. Using the client app (Android / Chrome Extension) select the app/domain you want to generate a password for, enter your Account ID, and choose a PIN. A hash of the inputs are sent via USB serial to the TurtlPass device that then uses a deterministic key derivation function (HKDF) to generate a 100-character password that includes a combination of lowercase and uppercase letters, as well as numbers.</p>
<p align="center">
For added security, TurtlPass uses a seed stored in flash memory to generate your passwords. And to protect against possible attack vectors, the generated password is not transmitted back via USB. Instead, it is typed by emulating an external keyboard when you click the physical button on the TurtlPass firmware device.</p>
<p align="center">
To use TurtlPass, you'll need a widely available RP2040 microcontroller flashed with TurtlPass Firmware. Then simply connect the device to your phone/computer via USB and start generating strong, unique passwords today.</p>


## 💪 Motivation for Creating TurtlPass

One of the main motivations for creating TurtlPass was the recognition of the importance of strong and unique passwords in today's digital world. With so many high-profile cases of hacking in the news, it is clear that online security is more important than ever. At the same time, I also recognized that it can be difficult for individuals, including myself, to come up with and remember strong passwords for all of the different services we use.

I wanted to address these issues with TurtlPass. By creating a tool that generates strong, unique passwords using a secure algorithm, I hoped to provide users with a solution that would give them peace of mind and protect their accounts from online attacks. Additionally, by making it easy for users to generate and store passwords, I hoped to alleviate the burden of having to remember multiple complex passwords.

Ultimately, my motivation for creating TurtlPass was to help protect individuals and businesses from online attacks by offering a password solution that is both secure and easy to use.


## 🐢 Meaning Behind the TurtlPass Name

I was inspired by the turtle when creating TurtlPass - these wise, resilient creatures have been around for centuries, enduring through all types of challenges and obstacles. That's exactly why I chose the turtle as the inspiration for our powerful password generator.

With TurtlPass, you'll get the strongest and most secure passwords possible, just like the turtle's enduring strength and wisdom. Our tool is designed to withstand even the most determined attacks, giving you the peace of mind you deserve. So don't just settle for any old password - choose TurtlPass and let the might of the turtle protect your accounts.


## 💚 Supporting Turtle Conservation and Software Development

As the creator of TurtlPass, I am dedicated to making a positive impact on both the digital and physical world. That's why I have decided to use 50% of the donations received via Patreon to adopt turtles in nature reserves across the world, starting with a specific one in Mauritius that I have personally visited. I believe that it is important to give back to the natural world and support the conservation efforts of these amazing animals.

The other 50% of donations will go towards the development and improvement of TurtlPass. Your support enables me to dedicate resources towards the creation of new features and the testing of new hardware devices.

Thank you for considering a donation to TurtlPass. Your support means the world to me, and I am grateful for the opportunity to make a difference for both the digital and physical world with your help.