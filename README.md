# Restaurant_Reviews_Analysis
This GitHub repository focuses on sentiment analysis of restaurant reviews, utilizing natural language processing techniques to determine the sentiment expressed in the reviews. The aim of this project is to develop a robust and accurate model that can effectively classify restaurant reviews as positive, or negative, providing valuable insights for both restaurant owners and customers.

## Usage

To use this Django project, follow the instructions below.

### Prerequisites

Before getting started, ensure that you have the following prerequisites installed on your machine:

- Python (version 3.7 or higher)

### Installation

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/Anandvunnam/Restaurant_Reviews_Analysis.git
   ```

2. Change into the project directory:
   ```
   cd your-repository
   ```

3. (Optional) It is recommended to create a virtual environment to isolate the project dependencies. Run the following command to create a virtual environment named "venv":
   ```
   python -m venv venv
   ```

4. Activate the virtual environment. The command may vary depending on your operating system:
   - For Windows:
     ```
     venv\Scripts\activate
     ```
   - For macOS and Linux:
     ```
     source venv/bin/activate
     ```

5. Install the project dependencies:
   ```
   pip install -r requirements.txt
   ```

### Configuration

1. Update the project settings:
   - Open the `settings.py` file located in the `your-repository/your_project/` directory.
   - Modify the database settings according to your environment (e.g., database engine, credentials, etc.).

2. Apply database migrations:
   ```
   python manage.py migrate
   ```

### Running the Development Server

Start the development server by running the following command:
```
python manage.py runserver
```

The development server will start, and you should see output indicating that the server is running. You can access the Django project by visiting `http://localhost:8000` in your web browser.