# retroflag-picase (nespi+, superpi, megapi case)
RetroFlag Pi-Case Safe Shutdown

Turn switch "SAFE SHUTDOWN" to ON.

--------------------

Setup for RetroPie direct reboot:

DISCLAIMER: I'm not responsible for any data loss, although i tested it on my setup and it worked properly.

-------------------Multi Switch Shutdown-----------------
Updated: 04/09/2019

Multi Switch Shutdown with advanced shutdown features for more natural behaviour:

If you press restart if emulator is currently running, then you will be kicked back to ES main menu.

If you press restart in ES main screen, ES will be restartet (no reboot!), good for quick saving metadata or internal saves.

If you press power-off then Raspberry will shutdown

All metadata is always saved

Multi Switch Shutdown by crcerror at here https://github.com/crcerror/retroflag-picase

-------------------Multi Switch Shutdown-----------------

1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press F4 enter terminal.
4. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/install.sh" | sudo bash

--------------------

Setup for RecalBox:
1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press F4 first. And then press ALT-F2 enter termial.
4. User: root Password: recalboxroot
5. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/DavidOliM/retroflag-picase/master/recalbox_install.sh" | bash

---------------------

Setup for Raspbian:
1. Make sure you're connected to the internet.
2. Either have a connected keyboard or SSH client open in another computer.
3. Open a terminal as user "root", you need to have set a root password before doing this.
4. On a root terminal, type or copy-paste this line:

wget -O - "https://raw.githubusercontent.com/DavidOliM/retroflag-picase/Raspbian/install_raspbian.sh" | bash

4. Wait til it finishes, it will reboot.
