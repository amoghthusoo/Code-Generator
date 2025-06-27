#### 🤖 AI-Powered Code Generator
This project provides a simple Python script (in Jupyter Notebook format) that leverages the Gemini API to generate code snippets based on natural language prompts. You describe what you want the code to do and in which language, and the AI generates the corresponding code.

#### ✨ Features

- Natural Language to Code: Translate your ideas into executable code by simply describing them.

- Language Agnostic: Specify the programming language for the generated code (e.g., Python, JavaScript, Java).

- Secure API Key Handling: Utilizes environment variables (`.env` file) to keep your Gemini API key secure.

#### 🚀 Prerequisites
Before you begin, ensure you have the following installed:

- Python 3.7+

- pip (Python package installer)

- Jupyter Notebook or JupyterLab (for running `.ipynb` files)

- An API Key from Google Gemini API. You can obtain one from the Google AI Studio.

#### 🛠️ Installation
1. Clone this repository (or copy the content of the `.ipynb` file).

    ```
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install the required Python packages using the `requirements.txt` file:

    ```
    pip install -r requirements.txt
    ```

#### 🔑 API Key Setup
1. Create a `.env` file in the root directory of your project (where your `.ipynb` file is located).

2. Add your Gemini API key to this `.env` file in the following format:
    ```
    GEMINI_API_KEY="YOUR_GEMINI_API_KEY_HERE"
    ```
    Replace `"YOUR_GEMINI_API_KEY_HERE"` with your actual API key.

#### 🎮 Usage
1. Open the Jupyter Notebook:
    ```
    jupyter notebook
    ```
    or
    ```
    jupyter lab
    ```
    Navigate to and open the `your_notebook_name.ipynb` file in your browser.

2. Run the cells sequentially: Execute each cell in the notebook.

3. The notebook will prompt you for two inputs:

    - `Enter the language in which you want the code to be generated :` (e.g., Python, JavaScript, Java, C++)

    - `Describe what you want the code to do :` (e.g., a function that calculates the factorial of a number, a simple web server using Flask, a React component for a counter)

4. After you provide the inputs, the generated code snippet will be displayed in the output of the last cell under the `🔧 Generated Code:` label.

Example Interaction:
```
Enter the language in which you want the code to be generated : Python
Describe what you want the code to do : a function to reverse a string

🔧 Generated Code:

def reverse_string(s):
    return s[::-1]
```

#### 📄 License
This project is open-sourced under the MIT License.