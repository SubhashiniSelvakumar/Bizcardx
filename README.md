**BizCardX: Extracting Business Card Data with OCR**

*BizCardX is a Streamlit web application that allows you to upload an image of a business card and extract relevant information from it using the easyOCR library.
*You can also view, modify, or delete the extracted data within the app and save the extracted information into a MySQL database, along with the uploaded business card image. 
*The database can store multiple entries, each with its own business card image and extracted information.

**What is EasyOCR?**
EasyOCR, as the name suggests, is a Python package that allows computer vision developers to effortlessly perform Optical Character Recognition.It is a Python library for Optical Character Recognition (OCR) that allows you to easily extract text from images and scanned documents. In my project I am using easyOCR to extract text from business cards.

When it comes to OCR, EasyOCR is by far the most straightforward way to apply Optical Character Recognition:

The EasyOCR package can be installed with a single pip command.
The dependencies on the EasyOCR package are minimal, making it easy to configure your OCR development environment.
Once EasyOCR is installed, only one import statement is required to import the package into your project.
From there, all you need is two lines of code to perform OCR — one to initialize the Reader class and then another to OCR the image via the readtext function.

**Technologies Used**
1)Python
2)easyOCR
3)Streamlit
4)MySQL
5)Pandas

**Getting Started**
Install the required Python libraries:
pip install streamlit easyocr pymysql pillow opencv-python matplotlib pandas
**MySQL server** set up with the following configurations:

Host: localhost
User: root
Password: Teddy756
Port: 3306

**Project Overview**
In this Streamlit web app, you can perform various tasks related to business cards:

**Home:** Provides an overview of the application, its features, and technologies used.

**Upload & Extract:** 

1)Click on "Upload & Extract" from the sidebar.

2)Upload a business card image (in PNG, JPEG, or JPG format).

3)The application will automatically extract information from it using OCR.

4)You can view the extracted data, and if desired, click the "Upload to Database" button to store the data in the MySQL database.


**Modify:** Provides functionality to alter or delete existing business card data in the database. 

1)Click on "Modify" from the sidebar.

2)You can select a card holder name to update their information. Make changes as needed, and click the "Commit changes to DB" button to update the database.

3)You can also choose to delete a business card by selecting a card holder name and clicking the "Yes Delete Business Card" button.

4)Click "View updated data" to see the updated business card data.

**Run the Streamlit app:**
streamlit run Bizcardx.py

**Acknowledgments**
Thanks to the developers of the libraries and tools used in this application.
Icon source: Image Source

