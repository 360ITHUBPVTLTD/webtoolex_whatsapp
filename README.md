Webtoolex Whatsapp

In this whatsApp we can able to send the messages,files and images using API

Prerequsities:-

1. WhatsApp Instance ID provided by the webtoolex.
2. Instance having credits


Installation of App in your bench ------------------------

$ cd /home/frappe/frappe-bench
$ bench get-app git@github.com:360ITHUBPVTLTD/webtoolex_whatsapp.git
$ bench --site site-name.local install-app webtoolex_whatsapp

Steps to Add the Instance in the App -------------------------

1. webtoolex_whatsapp having a Doctype "WhatsApp Instance"
2. Go to that doctype click on Add WhatsApp Instance
3. After clicking on that It will open a form view having fields
               i) Instance ID
               ii) Module
               iii) Base URL (https://wts.vision360solutions.co.in/api/) 
               iv) Assigned Mobile Number
               v) Active(check field)
               vi) Default(check field)

4. Fill the Instance Id provided by the service provide(webtoolex)
5. Choose the Module which you want
6. Base URL is https://wts.vision360solutions.co.in/api/
7. Assigned Mobile Number (The Assigned Number is nothing but whatsapp number that you want to connect. Include 91 while adding the number)
8. Active (This field should be checked when you want to send the messages.If it is uncheck means the messages will not be sent.)
9. Default (This field is when you are having multiple instances then it will take a default instance to send the message.)
10. After Saving the form

  The Form view having button "Connect Now" 
11. After clicking on the Connect Now Button It will prompt the QR code.
12. Take the Mobile and open whatsapp click on the Linked devices 
13. Click on Link Device then scan the QR code with you mobile.
14. After succefully connected
15. we can able to see the Sync Instance and Disconnect Buttons in the form view
16. when you click on the Sync Instance button.It will sync the Instance with the Latest updated data having credits,connection status..etc
17. If you click on the Disconnect the whatsapp will be logout succesfully.


Steps to send the whatsApp Message -----------------

Prerequisites:-
Instance ID having Credits

Sending Custom Message:-
 Sending Custom message we need three parameters 
          i) Instance ID
          ii) Custom message (the message which we want to send to the receipent)
          iii) Mobile Number(  Receipent Mobile Number) 

Sending PDF Message:-
 Sending Custom message we need three parameters 
          i) Instance ID
          ii) Custom Message (this message will go along with the PDF)
          iii) PDF link (The PDF URL we want to pass) Note:- If you are using local use pdflink as "https://tourism.gov.in/sites/default/files/2019-04/dummy-pdf_2.pdf"
          iv) Mobile Number(Receipent Mobile Number) 

          
