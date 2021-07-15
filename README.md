# hackrx-Hackathon

## FINSERV OCR
#### Overview of The Solution
 An open source app that enables users to scan hardcopies of documents convert it to a PDF file.As the documents move from physical to digital medium in today's world where Scanned docs are much required than handwritten ones, a document scanner is much needed.Now the twist is as the Scanner app is based on utility use,people either delete it or it stays in the device,thus consuming the very useful memory . So we Team Naive Creators are here with a solution to tackle this issue and came with the Finserv Scanner, a on browser web app that does not requires space on the device.
 The main/key features of our App includes-
 * Grey scales reduction in case of scanned images with grey hue or ink tome issues
 * Document Scanning using device viewfinder
 * Auto-cropping of images
 * Border identification(Live) & correction
 * Upload file to Cloud (requires Google Auth)
 * Download the scanned file in the local storage
 * Can generate a QR code for the document, so that whoever scans it, can have the document. (react-native-qrcode-generator)
 * OCR for images with printed text
 * Download Pdfs on Device
 * Camera permission and capabilities detection
 * Fully customizable UI(User can Choose theme According to his/her Convinience)
 * Flash
 * Live camera filters (brightness, saturation, contrast)
 * Easy to use base64 image
 * Turn upside down images or images in landscape format in the right sense.
 * support password protected pdf (react-native-pdf)
 * jump to a specific page in the pdf (react-native-pdf)



####  Process Flow Diagram
      Tech Stack
      MERN- dependencies(React Native Camera,React Native SVG)
          - Modules(react-native-document-scanner,react-native-image-zoom-viewer,expo-image-picker)
          
       https://app.diagrams.net/
          

#### How is our Solution different????
* Document Tracking- The user on Uploading the Scanned Documents will be able to track the furthur processing (Document Category will be Assigned+Will be Assigned either to a Machine or will be handled by any Executive)
* Handling Metadata-From the Scanned documents,We can extract the metadata and store this image data along with the metadata in a storage backend or serverless cloud(Most probably we will be using AWS) So no manual handling is required, The data from the image is directly into the predefined entries
* Specifically the insurance, banking and medical services deals with a huge amount of unstructured scanned documents which just behave as a spam directory.In any part of policy life the scanned documents such as KYC, Bank statements , important letters can be needed this becomes a very tedious job to verify and authenticate a doc from the very huge folder. 
 ##### Solution---> What we can do is , we can make a DLL model specifically a CNN model to classify the Scanned Images.For this we will be using Ryerson Vision Lab Complex Document Information Processing which is available on Kaggle
 Link: https://www.cs.cmu.edu/~aharley/rvl-cdip/
       




