# Opening Tkinter GUI on RaspberryPi Startup <br><br>
1) Open Terminal in Raspberry PI. <br>
2) Write the following commands: <br>
```
sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
```
You will see a text file. <br>

3) At the end add a line: <br>
```
@lxterminal -e python3 /home/pi/<your_directory>/<your_file>.py
```

4) Press ***"ctrl+x"*** and then press ***"y"*** and press ***"Enter Key"*** twice. <br>
5) Type ***"sudo reboot"*** to reboot your pi. <br>
Note: Use your own directory and program replacing <your_directory> and <your_file> respectively. <br>
