# Ricoh-Aficio-SP100-Linux-Driver

Install:

*Terminal:*

1) sudo pacman -Syu
2) sudo pacman -S cups ghostcript jbigkit
3) sudo cp -rf pstoricohddst-gdi /usr/lib/cups/filter/
4) sudo chmod 0555 /usr/lib/cups/filter/pstoricohddst-gdi
5) sudo chown root:root /usr/lib/cups/filter/pstoricohddst-gdi

*Browser:*

1) http:localhost:631
   - Administration -> Add Printer
   - Install Printers -> RICOH Aficio SP 100 (RICOH Aficio SP 100)
   - Use file pdd -> Ricoh_Aficio_SP_100.pdd

Done.


<img width="393" height="167" alt="изображение" src="https://github.com/user-attachments/assets/a7b5f49f-9d52-4b96-973d-cef4b9a09ef2" />
