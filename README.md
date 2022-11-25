# CryptoCam
Swift Student Challenge Submission | WWDC 2021

### :zap: [WatchPreview](https://youtu.be/gMEdtcLDdGU) :zap: [ResearchPaper](https://www.ijert.org/cryptocam-an-approach-to-enhance-cryptography-with-machine-learning) :zap:

![wwdcThumb](https://user-images.githubusercontent.com/39642060/115715144-80207f00-a395-11eb-9ee3-b7ba7eeb9088.png)

My Swift Playground aims to introduce & demonstrate a new concept of how Machine Learning can be used with Cryptography to innovate the future of Data Security, Data Confidentiality & Data Integrity.

Introducing CryptoCam! CryptoCam is a cam to encrypt & decrypt your data inside a physical object using Machine Learning.

Let's get started!

CryptoCam uses VisionKit with MobileNetV2 Machine Learning Model to analyze & classify images.

1. Encryption:
Step 1: Click on the "Encrypt" Button & Hold the camera steady focusing on the Object. It will start to analyze & classify the image of the object. After finishing the countdown, it will identify the name of the object in the camera frame using ML Model & VisionKit
Step 2: It will give an alert with the name of the identified object, please confirm the name of the object. If it's not correct, then feel free to scan again.
Step 3: In the Text Field, Add your message that you want to encrypt & tap on the "Save" button. This encrypted message will be saved in CryptoData.
Hurray! Your message is encrypted inside the object.

2. Decryption:
Step 1: Click on the "Decrypt" Button & Hold the camera steady focusing on the Object. It will start to analyze & classify the image of the object. After finishing the countdown, it will identify the name of the object in the camera frame using ML Model & VisionKit
Step 2: If the identified object is found in CryptoData, it will decrypt your message. After decrypting the message successfully, it will play Success sound. Otherwise, it will play Fail sound if the object is not found.
Hurray! The message is decrypted.

Example: 
Try scanning MacBook, add your message & click on the "Save" button to encrypt.
If you want to see the message that you have encrypted by scanning it, scan any MacBook or Desktop, it will identify the object & show you the decrypted message.

Technology Used -
AVFoundation is used for capturing live feed from the camera frame. Also, AVFoundation is used to play Success & Fail Sound.
MobileNetV2 Machine Learning model is used to classify the dominant in the camera frame.
VisionKit is used to analyze & recognize the images of objects.
UserDefaults is used to store CryptoData(Encrypted Data) in CryptoCam.

The purpose behind this Playground was to demonstrate a new concept of how Machine Learning can be used with Cryptography.

Thank you for checking out my playground!

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=cryptocam)
