# student-app

## Environment Setup

1. Open a terminal in this directory:
   ```sh
   cd ML/SupervisedLearning/LinearRegression/student-app
   ```

2. Create a virtual environment (recommended name: `.venv`):
   ```sh
   python3 -m venv .venv
   ```

3. Activate the environment:
   - On macOS/Linux:
     ```sh
     source .venv/bin/activate
     ```
   - On Windows:
     ```sh
     .venv\Scripts\activate
     ```

4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

After these steps, your environment will be ready and all required packages will be installed.

## Running the App with Streamlit

To run the `stud-per.py` app using Streamlit, make sure your environment is activated, then execute:

```sh
streamlit run stud-per.py
```

This will start the Streamlit server and open the app in your default web browser.