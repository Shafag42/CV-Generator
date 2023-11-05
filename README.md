# CV-Generator

CV-Generator is a web application that allows users to create and generate professional resumes (CVs) online. This project is built using [Django](https://www.djangoproject.com/) and [pdfkit](https://github.com/JazzCore/python-pdfkit), and it enables users to input their personal information, education, work experience, and skills to generate a downloadable PDF resume.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Features

- Create a user profile with personal information.
- Input education and work experience details.
- List your skills.
- Generate a professional PDF resume with user-provided information.
- Download the generated PDF resume.
  

## Prerequisites

Before you get started, make sure you have the following prerequisites installed on your system:

- [Python](https://www.python.org/) (3.x recommended)
- [Django](https://www.djangoproject.com/) (installed via pip)
- [pdfkit](https://github.com/JazzCore/python-pdfkit) (installed via pip)
- [wkhtmltopdf](https://wkhtmltopdf.org/) (installed on your system)

## Installation

1. Clone this repository to your local machine:

    ```
    git clone https://github.com/Shafag42/cv-generator.git
    ```

2. Change to the project directory:

    ```
    cd cv-generator
    ```

3. Install the project dependencies:
   
   ```
   pip install -r requirements.txt
   ```

4. Configure wkhtmltopdf in your Django settings, as explained here.

5. Run the development server:

   ```
   python manage.py runserver
   ```


### Usage

  ```markdown


  1. Visit the CV Generator website at [http://localhost:8000/](http://localhost:8000/) in your web browser.

  2. Sign up or log in to create your user profile.

  3. Fill in your personal information, education, work experience, and skills.

  4. Click the "Generate CV" button to generate your resume.

  5. Download the generated PDF resume to your computer.

  ```
