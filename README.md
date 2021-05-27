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
- Refer
  - https://uksouth.dev.cognitive.microsoft.com/docs/services/computer-vision-v3-2/operations/5d986960601faab4bf452005/console
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
  - https://dl.fujifilm-x.com/global/products/cameras/x-t3/sample-images/ff_x_t3_002.JPG
  - https://www.fujifilm.com/products/digital_cameras/x/fujifilm_x_t1/sample_images/img/index/pic_01.jpg
  - https://www.isixsigma.com/wp-content/uploads/2019/09/The-Importance-of-Sample-Size.jpg
  - https://www.cameraegg.org/wp-content/uploads/2013/02/Leica-M-Sample-Image.jpg
  - http://www.esa.int/var/esa/storage/images/esa_multimedia/videos/2018/05/mars_sample_return/17493376-1-eng-GB/Mars_sample_return_pillars.jpg
  - https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Diamond_Core.jpeg/1200px-Diamond_Core.jpeg
  - OCR: https://images.indianexpress.com/2020/04/coronavirus-testing.jpg
  - https://the-sample-room.com/assets/images/062617sample082ret.png
  - OCR: https://blog-images.pharmeasy.in/2020/10/31170828/blog-new-size-1.jpg
- Click on button - 'Send'


## Using Natural Language Processing Services
- Text Analytics
- Speech Recognition and Synthesis
- Translation
- LUIS Service

### Hands-On - Text Analytics
- Refer:
  - https://westus.dev.cognitive.microsoft.com/docs/services/TextAnalytics-v3-0/operations/Languages
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
