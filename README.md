# AI in Azure

## Computer Vision in Azure
- AI application resources in an Azure subscription:
   - Standalone resources for specific services
   - General Cognitive Services resource for multiple services

- Consumed by applications via:
  - A REST endpoint (https:// address)
  - An authentication key

### Computer Vision Capabilities
- Image Analysis with the Computer Vision Service
- Training Models with the Custom Vision Service
- Analyzing Faces with the Face Service
- Reading Text with the Computer Vision Service
- Analyzing Forms with the Form Recognizer Service

### Hands-On
- Refer [Computer Vision Console](https://uksouth.dev.cognitive.microsoft.com/docs/services/computer-vision-v3-2/operations/5d986960601faab4bf452005/console)
  - From Left, Select the Computer Vision Service we want to use. We will try below services:
    - Analyze Image
    - Describe Image
    - Detect Objects
    - OCR
    - Tag Image

  - Select Location - UK South
- Copy 'API key' from the 'Computer Vision' resource we created in Azure.
- Specify that key value in - 'Ocp-Apim-Subscription-Key' input field
- Specify URL to any image in 'Request Body'
```
https://www.isixsigma.com/wp-content/uploads/2019/09/The-Importance-of-Sample-Size.jpg
```

  ```
  https://www.cameraegg.org/wp-content/uploads/2013/02/Leica-M-Sample-Image.jpg
  ```

  ```
  http://www.esa.int/var/esa/storage/images/esa_multimedia/videos/2018/05/mars_sample_return/17493376-1-eng-GB/Mars_sample_return_pillars.jpg
  ```

  ```
  https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Diamond_Core.jpeg/1200px-Diamond_Core.jpeg
  ```

  - OCR
```
https://images.indianexpress.com/2020/04/coronavirus-testing.jpg
```
```
https://blog-images.pharmeasy.in/2020/10/31170828/blog-new-size-1.jpg
```

  ```
  https://the-sample-room.com/assets/images/062617sample082ret.png
  ```



- Click on button - 'Send'


## Using Natural Language Processing Services
- Text Analytics
- Speech Recognition and Synthesis
- Translation
- LUIS Service

### Hands-On - Text Analytics
- Refer [Text Analytics Services Console](https://westus.dev.cognitive.microsoft.com/docs/services/TextAnalytics-v3-0/operations/Languages)
- Select the desired service from Left Menu
- Select location - UK South
- Specify that key value in - 'Ocp-Apim-Subscription-Key' input field
- Do desired changes in - 'Request body'
- Click - 'Send'
- Review the Response

- Try other services from Left Menu
  - Detect Language
  - Key Phrases
  - Linked entities from a well known knowledge base
  - Named Entity Recognition
  - Sentiment

## Azure Bot Service
- Create a resource - Web App Bot
- Chose template - Basic Bot
- Open Resource
- From left Menu click - "Test in Web Chat"

## QnA Maker
- A replacement to FAQ
- Can be enabled with AI
- Create a resource in Azure - QnA Maker. Name - agqna21
- Goto Resource
- Copy API key
- Open [QnA Maker Portal](https://www.qnamaker.ai/Create)
- Complete Step 2, 3, 4
  - For Knowledge Base generation [Refer](https://www.microsoft.com/en-in/software-download/faq)
- Click - 'Save and Train'
- Click Test
  - Sample Questions
    - How to find Product key?
    - Difference in different version of Windows
    - Is it bootable?
    - I need windows 10. Where is it?
- Click - Publish
- Click - Create Bot named - agkbboat1
-  Test the Bot
- Integrate Bot
  - Click - Channels
  - Click Get Embed Codes
  - Click - "Click here to open the Web Chat configuration page"
  - Copy 'Embed Code'
  - Create a simple html file and paste the code there
    - [myknowledgebase.html](myknowledgebase.html)
  - Also put the Secret keys in HTML file
  - Open HTML file in any browser
  - Ask questions from Bot
