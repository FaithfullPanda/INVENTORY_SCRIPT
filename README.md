# INVENTORY_SCRIPT
Powershell Script to create a GUI for hardware inventory purposes


This script was created to ease a manual hardware inventory. 

BEFORE USE:

- Not asking for much if you use the script, just wouldn't mind being quoted/mentionned/credited for the work even if it isn't much 
- No selling/reselling of the code for your own benefit
- Free to use/modify => I don't mind getting the changes you do, out of curiosity ! =)

- Be sure to have all the correct rights to use powershell on the computer you're using otherwise the script may not work properly
- Don't forget to sign it if you're using it in a company

- The code should mostly be plug&play , but the elements for each hardware pieces i included in the code are those I needed. 
- If you need more/less/to change those existing, you have to do so at 3 places:
    - Variables (to get and return the data you enter) 
    - Textboxes (to add/remove textboxes for you to fill)
    - GUI (to add/remove/resize the GUI to your needs.)
    - Data Return (ADDELEM Function : you will have to change some parts to make them reflect the changes you made above)
- Default location of the file is meant to be the current user desktop. You may modify this through the $INVENTORYFILE variable at the beginning of the script. Don't forget to put a full location ( ex "C:\users\XXXX\desktop\FILE.TXT" ) to easily find your file.






