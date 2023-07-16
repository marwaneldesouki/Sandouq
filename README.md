# Project Title
- Sandoquq

## Description
- This my graduation Project.<br>
the idea of this project is
Helping people instead of coming to the government interest to have purposes
When they hand over these items, such as birth certificate papers or identity cards, they will discover that their papers are incomplete.
So we came up with a solution to this problem through a mobile application, and by a way they will choose these items and they will deliver them through the mobile application, and then the artificial intelligence will verify the validity of these papers and when these papers are correct, a qrcode will be sent to the user to make him go to the government department, and then The second phase of the project will come, which is that it will go with a qrcode to the fund, and from that the fund will identify the person and this service that will be delivered Then he will be asked for the required papers
After that, a camera will be present to verify these papers, and through artificial intelligence, they will be verified
If it is correct, it will move to the next page
Upon completion of the delivery and verification of the papers, a picture will be taken of the person who delivered the paper to document the moment of delivery, and then this saves time for the user and the employee.


## DataSet used

<img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/df0853fd-3310-4647-a8dd-586b1f21ab74" data-canonical-src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/df0853fd-3310-4647-a8dd-586b1f21ab74" width="720" height="400" />

    used egyption birth certificate and egyption ID images to make the image processing on it.
    and train the model on 60 epoches
## Results of Dataset
<p align="center">
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/3b1eb96e-cdd8-4540-9954-b02c8cd660a6" alt="Image 1" width="300" />
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/b4dfc95f-1122-4299-9864-4d42135e446a" alt="Image 2" width="300" />
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/25d5eb16-c361-42d1-bf28-46a842e3494f" alt="Image 3" width="300" />
</p>


## Technology used
•	Flutter mobile app for user .<br />
• C# Desktop app for worker.<br />
• Arduino For THe Sandouq.<br />
• Mysql for Database.<br />
• Restful API to connect each system with other one.<br />

## Requirements
  •	Python 3.10.6.<br />
  •	Flutter.<br />
  •	Arduino.<br />
  •	PHP.<br />
  •	C#.<br />
  •	XAMPP.<br />
• Install all libraries.<br />


## Project’s main functions:
 Flask Server:<br />
      •Uploading papers to server and return the classifications of this paper<br />
 Mobile app:<br />
   -for User
      •Get All services.<br />
      •Show All Services.<br />
      •Show All Papers<br />
      •Show All Chosen Services<br />
      •Show All Submitted Papers<br />
      •Upload Papers<br />
      •Show status of submitted Papers<br />
      •Show QRCode<br />
      •Hide QRCode<br />
      •Classify images using flask server<br />
 Arduino Server:<br />
   -for User,Worker:<br />
    -There is 3 cam32.<br />
      •Cam_1 to read the qrcode.<br />
      •Cam_2 to Stream video from the Sandouq to show this camera papers and send it to flask server.<br />
      •Cam_3 to make face detection to the person that submitted the papers.<br />
    -Touchscreen to control the Sandouq.<br />
    -RFID card and reader to read the rfid tag that will need from the worker to access the Sandouq.<br />
    -motors to open the drawer to put papers after submissions is done.<br />
 Restful API:<br />
    -to make every things connected with each other.<br />
 C#:<br />
   -for Worker<br />
    •Add Services.<br />
    •Add Papers to Services.<br />
    •Show all submissions.<br />
    •Accept and reject the submission.<br />
  
  ##
    
  
## Images + ScreenShots
    Sandouq.
<p align="center">
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/d8a04c09-a211-41ed-95ce-c9f97fd5176b" alt="Image 1"  />
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/8c75119c-71e7-49f2-bbf7-9b11419e2c63" alt="Image 3"  />
</p>

    Mobile app.
<p align="center">
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/9b7bc04f-f603-4d1d-a20c-fbb0e40c10f0" alt="Image 1" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/b60c82b7-baeb-4fb8-b7c0-d417b928aa7f" alt="Image 2" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/8c6ced08-f803-402b-8c05-a8c9be5a0b8e" alt="Image 3" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/49912e0f-af1a-4654-9047-677640cd4852" alt="Image 4"  width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/204e49f4-9939-48d2-ba6e-a0263359e15c" alt="Image 5" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/b967e598-6518-4357-8984-ef1a41d982b9" alt="Image 6" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/ea68ecb2-9d5b-4e94-b4ee-825707fd7e83" alt="Image 7" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/93cf5305-ec50-4102-a5bf-6a9e5bd5b0ee" alt="Image 8" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/48238cce-1d2c-49cb-8982-e1289b59dedd" alt="Image 9" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/fce1422e-34d8-49b5-9a2d-b8320ec3a33e" alt="Image 10" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/52d72549-881b-45c6-bd92-f3a894a7d7f6" alt="Image 11" width="100"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/9597ef41-8629-4dfd-8ed8-69822b2c6a39" alt="Image 12" width="100"/>
</p>

    Sandouq.
<p align="center">
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/16e355e4-f0f2-47f1-9ee8-ddfe6f2165ae" alt="Image 1" width="300"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/6c0a9250-a822-4a4e-8dcf-e9bd98dc2984" alt="Image 2" width="300"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/7abc6e21-f289-435f-badf-f39b88ff999b" alt="Image 3" width="300"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/da9c56c0-4f1a-48fc-b814-b274a04f466e" alt="Image 4"  width="300"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/933c7bb6-ac0c-43ec-a226-57c1f4c3dc5f" alt="Image 5" width="300"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/fb7af068-f765-43f0-a7a5-cfd66d8f3a03" alt="Image 6" width="300"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/20b530b9-f856-44cf-b23a-5c7efa100267" alt="Image 7" width="300"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/9a29a4d6-cb33-49d6-b916-3a87eaf78d08" alt="Image 8" width="300"/>
  <img src="https://github.com/marwaneldesouki/Sandouq/assets/37198610/0bc42534-06ff-4d48-a820-ce0eb5fabbc9" alt="Image 8" width="300"/>
</p>


## Developer
marwan eldesouki
