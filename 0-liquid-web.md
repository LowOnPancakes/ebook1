# DAY  - Creating Your Own Server - with Liquid Web

## INTRO
First, you need a server. You can't really learn about administering a remote Linux server without having a one of your own - so today we're going to buy one!

Through the magic of Linux and virtualisation, it's now possible to get a small Internet server setup almost instantly - and at very low cost. Technically, what you'll be doing is creating and renting a VPS  ("Virtual Private Server"). In a datacentre somewhere a single physical server running Linux will be split into a dozen or more Virtual servers using the KVM (Kernel-based Virtual Machine) feature that's been part of Linux since early 2007. There are many hundreds of hosting companies offering low cost VPS deals - and sites like http://lowendbox.com/ that compare them.

As well as a hosting provider, we also need to choose which "flavour" of Linux to install on our server. If you're new to Linux then the range of "distributions" available can be confusing - but the latest LTS ("Long Term Support") version of Ubuntu Server is a popular choice. 
 
These instruction will walk you through using Liquid Web (http://www.liquidweb.com) as your VPS hosting provider. 

## Signing up with Liquid Web.
http://www.liquidweb.com/StormServers/index.html

Under the Box that reads Storm® VPS Servers Fully Managed VPS Hosting click the button that reads from $50/mo.

Set the slider to the 1G option and click the green order now button

Most of Liquid Webs servers run CentOS but this course was written for Ubuntu so choose the most current Ubuntu option. Many of the things you learn in this course will apply across all Linux distributions.

Give your server a unique hostname and a strong password. You should only need the default single IP.

Click next and fill out your personal information. 

Once your server finishes creation you should be ready to go. You now have the IP address for your server which you alone are responsible for administering!

