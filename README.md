# Christmas 2019

A set of Christmasified openSUSE packages.

SUSE Prague packagers prepared a Christmas surprise for you! Check out the video for a magical quest of an openSUSE user for a hidden message.

See the demo at https://youtu.be/vVvd--APxj4

Created by Package Ninjas (Kristyna Streitova, Vitezslav Cizek and Marketa Calabkova).

**DISCLAIMER**: These packages are just for Christmas fun. You should better not use them on your production system.

For the brave and curious, here's how to experience it yourself:

    # zypper ar -f http://download.opensuse.org/repositories/home:/christmas/openSUSE_Factory/home:christmas.repo
    # zypper in --allow-vendor-change --allow-unsigned-rpm --allow-downgrade christmas

Should you install it on your real workstation, and be unhappy with it (we told you so), then uninstall it via the following steps:

(1) Pity your own frivolity

(2) Remove the christmas repository

    # zypper rr home_christmas

(3) Perform a distribution upgrade with your original repositories (and confirm vendor change for the christmas packages back to openSUSE)

    # zypper dup 

(4) Remove any leftovers

    # zypper rm xsnow cowsay htop

 
