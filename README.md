Customer Identification

Table of Contents

[1 Project Description 2](#_Toc52526696)

[2 Folder structure 2](#_Toc52526697)

[3 Explanation of code 2](#_Toc52526700)

[4 Steps for the execution of the code 3](#_Toc52526701)

[4.1 Technical Stack for running the code 4](#_Toc52526702)

[4.2 Modules used 4](#_Toc52526702)

[5 Tracker 4](#_Toc52526703)

[6 GitHub download 4](#_Toc52526704)

[7 Key Contacts 5](#_Toc52526704)

[8 Revision History 5](#_Toc52526704)

Project Description:

The customer identification effort is to identify key opinion leaders or
treating physicians with a great impact in the specific therapeutic area or
disease state that we can engage with for different objectives. Information is
extracted from different data sources and prioritized on various criteria to get
the interested customer list with the highest impact. Some data sources are
commonly used for multiple identification projects and automation of the data
extraction process can help to reduce the time of data extraction for all
relative projects.

Folder structure:

A folder for all the data sources will be created.

Example: (Folder Structure will be same for all the data sources)

-   Conference

-   Scientific Advisory

-   Patient Advocacy

-   Local Society

-   Guideline

Individually python notebooks (scripts) will be uploaded in the respected
folders.

**Note:** If any other type of input is required a separate folder will be
created for that script.

Explanation of code:

-   For Conferences:

    -   This code will give you the excel file containing Names, Institution,
        Session Title, Presentation title, and other details present on the
        website.

    -   Please refer Conference Template tab from the “Output Template” excel
        file for the output.

-   For Scientific Advisory:

    -   This code will give you the excel file containing Names, Credentials,
        Institution, Role, Biography, Biography link, and other details present
        on the website.

    -   Please refer Scientific Advisory Template tab from the “Output Template”
        excel file for the output.

-   Patient Advocacy:

    -   This code will give you the excel file containing Names, Credentials,
        Institution, Role, Biography, Biography link, and other details present
        on the website.

    -   Please refer Patient Advocacy Template tab from the “Output Template”
        excel file for the output.

-   Local Society:

    -   This code will give you the excel file containing Names, Credentials,
        Institution, Role, Biography, Biography link, and other details present
        on the website.

    -   Please refer Local Society Template tab from the “Output Template” excel
        file for the output.

-   For Guideline:

    -   This code will give you the excel file containing Names, Publication
        topic, Session name, Institution, and other details present on the
        website.

    -   Please refer Guideline Template tab from the “Output Template” excel
        file for the output.

**For all the data source output, we have attached a template accordingly.**

Steps for the execution of the code:

-   Install python’s latest version.

-   In the install setup, select these 2 checkboxes shown in the image below.

    ![](media/ed42228aaa1fd09bcb6f37826387a129.jpg)

-   Install Jupyter notebook through cmd (“**pip install notebook –user**”)

-   Download chromedriver according to your chrome browser version.

-   Chromedriver needs to be saved in the same folder where the ipynb file
    (script file) is present.

-   Open your script folder and in the path section type “cmd” to get into the
    command prompt, in the command prompt type **“jupyter-notebook”**

    ![Graphical user interface, application Description automatically
    generated](media/76496fe858cd288afcefa44eec8b5b28.jpg)

-   Open your python notebook.

-   Change the chrome-driver path according to your path or store it in your
    current folder/Directory and write"chromedriver.exe".

-   Un-comment all things (modules) you want to install which are given along
    with the version of it in the script itself.

-   The versions mentioned are the ones in which the codes were tested.

-   Check the markdown cell of the ipynb file for more comprehensive steps to
    get the final excel file.

-   Specific instructions for each script are given inside the script in the
    markdown.

-   Run the python notebook to get the output.

-   Technical Stack for running the code:

    1.  Python 3.9 (greater than or equal to this version)

        1.  Jupyter notebook

            1.  Chromedriver

-   Modules used:

    -   Unidecode==1.2.0

    -   pandas==1.2.5

    -   selenium==3.141.0

    -   numpy==1.21.0

    -   urllib.robotparser==1.26.6

    -   tld==0.12.6

    -   pdfplumber==0.5.28

    -   openpyxl==3.0.7

-   We have attached the requirement.txt file, please place the requirement.txt
    file in the scripts folder.

-   Open your script folder and in the path section type “cmd” to get into the
    command prompt, in the command prompt type **“pip install -r
    requirements.txt”**

Tracker:

-   Navigate to the tracker file from GitHub to run the required script.

-   For all the data sources we have provided the name of the Source along with
    the website link and script link in the tracker.

-   We have added notes about the script in short as in to understand what all
    details will it be scraping from the website.

GitHub download:

If you want to download the script file from the repository, directly use:

**curl –o \<filename.ipynb\> \<raw script url\>**

raw script url = link will be provided in the tracker.

Open the command prompt in a specific folder and run the above command in cmd to
save the file.

e.g.:

**curl –o qrcode.py
https://raw.githubusercontent.com/geekcomputers/Python/master/QR_code_generator/qrcode.py**

Key Contacts:

| Names              | E-mail                                        | Comments / Remarks                                                                                                    |   |
|--------------------|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|---|
| Alice Chung        | alchung@gene.com                              | Please contact Alice Chung any questions related to the customer identification process, or any escalations required. |   |
| Sharon Cheng       | [chengx23@gene.com](mailto:chengx23@gene.com) | Please contact Sharon Cheng for anything related to Conference URL’s or extraction of data from the website.          |   |
| Soodabeh Sarafrazi | [sarafras@gene.com](mailto:sarafras@gene.com) | Please contact Soodabeh Sarafrazi if you have any queries in understanding or executing these scripts.                |   |

Revision History:

| Current Version | Supersedes | Modifications | Date      |
|-----------------|------------|---------------|-----------|
| 1.0             | N/A        | New           | 1/12/2022 |
|                 |            |               |           |
|                 |            |               |           |
