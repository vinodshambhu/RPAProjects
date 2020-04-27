# RPAProjects
Collection of Uipath automation projects developer during my learning process. Some of the project ideas are from trainigs, youtube or RPA whitepapers.

# Project 1: EmailProcessor
Project 1 deals with processing of emails from outlook. The project involves Ortchestrator and hence we have 2 bots one as dispatcher 
and other as Performer. 
BOT1: EmailDispatcher  traverses through emails, Saves attachments and extracts necessary data and pushes it to QUeue.
BOT2: EmailPerformer built on REFramework reads the transaction items from Queue, and generated a unique number using 
inputs from Queue and updates the transaction

# Project 2 : Customer Registration
Project 2 is a simple automation which involves adding new customers to your website. The customer details will be available in excel so the process basically reads the excel and Logs in to the website --> create cutomer section and adds the details fetched from excel and saves the data.

# Project 3 : Image Labeler
Project 3 deals with Recognizing type of image based on Image content. The project uses Google Cloud Vision API for Analyzing.
