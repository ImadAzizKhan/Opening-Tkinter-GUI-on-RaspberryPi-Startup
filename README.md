# Opening Tkinter GUI on RaspberryPi Startup <br>
Open Terminal from top menu in Raspberry pi. <br>
Write the following commands: <br>

```
sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
```

You will see a text file, in the end add: <br>

```
@lxterminal -e python3 /home/pi/<your_directory>/<your_file>.py
```

Note: Use your own directory and program name here <br>
Press ctrl+x and then "Y" and enter twice. <br>
Type "sudo reboot" to reboot your pi.
