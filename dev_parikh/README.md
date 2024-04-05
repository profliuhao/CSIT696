
#### 2. Install necessary packages:
   - ```
     pip install -r requirements.txt
     ```

#### 3. Run the `ingest.py` file.

#### 4. Sign up with Together AI 
   - ```python
      os.environ["TOGETHER_API_KEY"] = "YOUR_TOGETHER_API_KEY"
     ```
   - If you are going to host it in Streamlit, Hugging Face, or other platforms:
      - Save it in the secrets variable provided by the hosting with the name `TOGETHER_API_KEY` and key as `YOUR_TOGETHER_API_KEY`.

#### 5. To run the `app.py` file, open the CMD Terminal and type `streamlit run FULL_FILE_PATH_OF_APP.PY`.

