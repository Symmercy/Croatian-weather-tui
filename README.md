# Croatian-weather-tui
This is a small tui program that can display weather stats from dhmz (Croatia only) in your terminal, there is one executable for dmenu and one for terminal

in the code change the PLACEHOLDER with the name of your city, for example if you are in Zagreb replace PLACEHOLDER with Zagreb
if you want to check names of weather stations you can download the file im pulling info from with the following command: wget https://vrijeme.hr/hrvatska1_n.xml.

after you change the PLACEHOLDER to the name of your city, you should run chmod +x weather && chmod +x weather-dmenu
you should put this program into /usr/bin, /bin or ~/.local/bin up to you!

DHMZ is the source of this data!

