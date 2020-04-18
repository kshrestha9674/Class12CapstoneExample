Automation to add owner using Katalon Studio

    1. Download latest version of Katalon Studio
    2. Click File located top left corner and select new project.
    3. Type Filename (Final Capstone) and click OK
    4. Click Record Web and web recorder will open
    5. Type https://clinic.doveryai-no-proveryai.com/ in URL box and select the browser of your choice (I used chrome)
    6. Web will open in chrome browser and select owners
    7. Select add new and enter information
       First name: Mike
       Last name: Dean
       Address: 8456 Wall St
       City: Austin
       Phone: 1234567890
    8. Click add owner
    9. Pop up window will appear for log in
    10. Enter username (admin) and password (admin) and click Sign in
    11. Close window
    12. Select Run to test the code
    13. Test appeared to be failed
    14. In web recorder Click on Item 1
    15. Select drop down menu next to Add and select Web UI Keyboard
    16. Select drop down menu from item to select navigate to URL
    17. Double click on input and enter http://admin:admin@clinic.doveryai-no-proveryai.com:9966/petclinic/swagger-ui.html" in input box
    18. Select Run to test 
    19. Test Pass