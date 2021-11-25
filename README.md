Please watch the video to get a clear view [Concern-video-to-fix-kali-linux-update-error](https://youtu.be/pnwy9W4wX9A)

You can also check the video to [update the Kali Linux repositories](https://youtu.be/GRz_fk_Uf5k) with various options


ERROR 
E: Failed to fetch http://http.kali.org/kali/dists/kali-rolling/main/Contents-amd64 | Kali Linux Error Solved

In this video I will give the solution for the following error "Unable to fetch some archives,maybe run apt-get update or try with --fix-missing?".
 
 
Step 1
Run command to edit sources.list
<pre>$ sudo gedit /etc/apt/sources.list</pre>

Step2
Remove every thing from sources.list

Step3
Add lines to sources.list
<pre>#deb https://http.kali.org/kali kali-rolling main non-free contrib</pre>
<pre>deb-src https://http.kali.org/kali kali-rolling main non-free contrib</pre>

Step 4
Update and upgrade
<pre>$ sudo apt-get update; sudo apt-get upgrade</pre>
<pre>$ sudo apt update && sudo apt -y full-upgrade</pre>

Step 5 see Os version and details
<pre>$ cat /etc/os-release</pre>

If you need to ask about such things on google, then Kali Linux is not the right distribution for you.

Kali Linux is a distribution for professional penetration testers who are already very familiar with Linux. It is meant to be used from a USB dongle for penetration testing. It can be installed, but it is not really meant to be. It is not meant for general use (even by professional penetration testers) such as Internet browsing, word processing, gaming, development, etc.

If you aren't already a Linux pro, don't use Kali. Use a distribution for ordinary people, such as Ubuntu, Fedora, elementary OS, Linux Mint, etc.

Even if you want to learn penetration testing, you need to learn the basics first! Do this on a “normal” distribution.

Since Kali is for experts, if you ask about Kali, people assume that you're an expert. If you ask a beginner question about Kali, many people will ignore you. Beginners and Kali are not compatible.


With any distribution, even distributions targeted for beginners, you can learn by looking under the hood. The difference is that with easy-to-use distributions, you can install first, and then explore to learn.

Take care of yours.

---------------------------------------
India :  7503453371@ybl<br />
<a href="https://paypal.me/efxtv"><img src="https://raw.githubusercontent.com/efxtv/efxtv/master/assets/donate-efx-tv.png" alt="Paypal" width="125" height="40"></a>
---------------------------------------
