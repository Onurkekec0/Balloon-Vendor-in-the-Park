# Balloon-Vendor-in-the-Park
Learn to Count - Educational Game with Unity and Augmented Reality This project is developed with the aim of teaching preschool children how to count in a fun and interactive way using Unity and Augmented Reality technologies.

This Unity project simulates a balloon vendor in a park and is also an Augmented Reality (AR) project. To run this project on your own mobile device or an emulator, you will need to add your own QR code to the project. After uploading the QR code, you can integrate it into the project using [Vuforia](https://github.com/Onurkekec0/Balloon-Vendor-in-the-Park-AR-Project-/#vuforia).

205541008 - Onur Kekeç


![image](https://github.com/Onurkekec0/Balloon-Vendor-in-the-Park-AR-Project-/assets/102962541/596cf13b-2caf-41c2-aaf4-a6926dbdc563)


# Vuforia
1) Import and Set Up Vuforia: After importing the Vuforia SDK, follow the Vuforia setup wizard within Unity. It will guide you through the process of configuring Vuforia for your project.

2) Create a Vuforia Database: In the Vuforia developer portal, create a Vuforia database. This is where you'll configure your target images (which can include QR codes).

3) Upload and Configure the QR Code: Inside the Vuforia database, upload your QR code image as a target. Configure its size, rating, and other details as needed.

4) Download and Import the Database: Once your target is configured, download the database and import it into your Unity project.

5) Add the Image Target: In your Unity scene, add an "Image Target" game object. Configure it to use the database you imported, and select the QR code image as the target.

6) Create AR Content: Now, you can create your AR content that will appear when the QR code is recognized. This content could be 3D models, animations, or any AR elements you want to display.
