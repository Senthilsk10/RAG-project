# RAG-project

### download the codes as zip and extract the file

### Project Structure:
- **Static files**: Stored in the `static` directory.
- **Templates**: Contain HTML files (`index.html` and `data.html`) used by the Flask app.
- **Python Scripts**:
  - `app.py`: Runs the Flask application. Run it using `python app.py` and  Navigate to `http://localhost:5000` to access the website in any browser.
  - `rag_final.py`: Monitors PDFs. Run it directly using `python rag_final.py` (no arguments needed).
  - `credentials.py`: stores sensitive data (e.g., API keys)
  - `playground-1.mongodb.js`: Possibly contains MongoDB setup or sample queries.
- **HTML Files**:
  - `index.html`: The main template for your website.
  - `data.html`: Likely a secondary page/template for the Flask app.


#### **Website Features and Usage Instructions**

##### **1. Voice Query**
- **Action**: Click the **Listen** button.
- **Command**: Say your query, e.g., "Hey, <some query>".
- **Process**: The system fetches relevant data based on the query.  
  

##### **2. Translation of Selected Text**
- **Action**: After the data is fetched:
  - Click on the text result to select it.
  - A **Translate** button will appear. Click it to translate the selected text into any desired language.  
  *(Image placeholder: [Add Image Here])*

##### **3. Text-to-Speech**
- **Action**: After selecting the text, say:
  - **"Read"** to enable text-to-speech for the selected text.
  - **"Stop"** to stop text-to-speech.

##### **4. Limit the Results**
- **Action**: To limit the number of results displayed, say:
  - **"Show n results"** (replace `n` with your desired number).  
  *(Image placeholder: [Add Image Here])*

##### **5. MongoDB Data Management**
- At the top of the website, there are two links:
  1. **Show Extracted Data**: Displays data stored in the MongoDB database.
  2. **Delete Data**: Provides an option to delete specific entries from the database.  
  *(Image placeholder: [Add Image Here])*

---

#### **Setup and Running Instructions**

1. **Prerequisites**:
   - Python 3.x installed on your system.
   - Install dependencies using:
     ```bash
     pip install -r requirements.txt
     ```
   - MongoDB should be set up and running.

2. **Running the Application**:
   - Start the PDF monitoring process:
     ```bash
     python rag_final.py
     ```
   - Run the Flask app:
     ```bash
     python app.py
     ```
   - Open your browser and navigate to `http://localhost:5000`.

3. **Environment Variables**:
   - Ensure sensitive information like database credentials is stored in environment variables or a `.env` file.

---

#### **Additional Notes**
- Add images or screenshots to illustrate the steps in the placeholders above.
- Ensure that the voice commands are clear and the UI is intuitive for all users.

---

Would you like help integrating the voice commands into your app or refining specific features?
