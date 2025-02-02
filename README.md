# Doccano Project Setup

This README file contains instructions to set up and run the Doccano project on your local computer.

## Prerequisites

Before you begin, make sure you have the following installed on your local computer:
- Python 3.10 or higher
- pip (Python package installer)

## Installation

Follow these steps to set up the project:

1. **Clone the Repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create a Virtual Environment**:
    ```sh
    python -m venv doccano_venv
    source doccano_venv/bin/activate  # On Windows, use `doccano_venv\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Running the Doccano Server

1. **Initialize Doccano**:
    ```sh
    doccano init
    doccano createuser --username admin --password password --email admin@example.com
    ```

2. **Run the Doccano Server**:
    ```sh
    doccano runserver 0.0.0.0:8000
    ```

3. **Access Doccano**:
    - Open your web browser and navigate to `http://localhost:8000`.
    - Log in with the admin credentials you created.

## Creating a Project in Doccano

1. **Create a Project**:
    - Once logged in, click on "Projects" and then "Create Project".
    - Choose "Sequence Labeling" as the project type for word selection tasks.
    - Fill in the project details and create the project.

2. **Upload Dataset**:
    - Go to your project and click on "Upload Data".
    - Upload the dataset containing the quotes (in CSV, JSON, or text format).

3. **Annotate Quotes**:
    - Students can log in to Doccano, access the project, and start selecting words in the quotes.
    - Use the annotation interface to highlight and label the words.

## Exporting Annotations

1. **Export Annotations**:
    - Once the annotations are complete, you can export the annotated data.
    - Go to the project and click "Download" to get the annotated dataset in a desired format (JSONL, CSV).

---

Feel free to reach out if you have any questions or run into any issues. Happy annotating! 😊

---

Let me know if there are any specific details you'd like to add or modify!
