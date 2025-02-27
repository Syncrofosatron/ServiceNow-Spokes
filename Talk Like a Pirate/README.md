# Turn Into a Pirate
This spoke make use of REST API in IntegrationHub, connecting it to https://pirate.monkeyness.com/api.html and utilizing its API.

This spoke will turn the incident record's short description, description, work notes and additional comments field text into pirate-like vocabulary.

You can utilize this by following the tutorial as shown.

![touchofapirate0](https://github.com/user-attachments/assets/b02950c6-8ff2-4476-b918-1df38dddaaf6)


![touchofapirate1](https://github.com/user-attachments/assets/3f5062a1-bb87-4c0d-b724-5f56a88f601a)


![touchofapirate2](https://github.com/user-attachments/assets/7dc252a8-355b-4a57-8950-dec744c7ba75)


![touchofapirate3](https://github.com/user-attachments/assets/dccfa443-2298-485e-84dd-b14043355fce)


As a whole, it will look like this:

![touchofapirate](https://github.com/user-attachments/assets/2c80c4af-5710-4c16-b895-cc97c4e4780e)



Here you will see how the text changes as per the functionality of the spoke:

![touchofapirate4](https://github.com/user-attachments/assets/f8ca4f63-9618-4594-9dbb-3b380b755ed1)


![touchofapirate5](https://github.com/user-attachments/assets/dac9dbf4-d36d-4800-bbfd-9a25fb685c29)


![touchofapirate6](https://github.com/user-attachments/assets/0f4bf757-d1df-4cf7-8b29-7ffd057044a2)


![touchofapirate7](https://github.com/user-attachments/assets/2232985a-c3f2-4d36-b262-42edf5c13d1a)


![touchofapirate8](https://github.com/user-attachments/assets/9e269ff8-1967-4e5a-9be3-58422ad2d7c4)


Steps to publish this application:

    In Application Navigation, search for "update sets".
    Then go to: System Update Sets -> Retrieved Update Sets.
    Scroll to the bottom and click on "Import Update Set from XML".
    Browse for the file in this repository and upload.
    You will see "Touch of a Pirate" in the list view of records now, click on the application in "Name" column.
    On top-right, click on "Preview Update Set", once it finishes and reaches 100%, click on "Close".
    A new option will be available on top-right as "Commit Update Set", click on it and your application will be installed and available as a spoke which can be utilized in Flow Designer as shown in above pictures.

