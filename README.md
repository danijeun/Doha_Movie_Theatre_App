# Doha_Movie_Theatre_App
## Development Environment

1. Ensure Python 3.x is installed

2. It's recommended to create a virtual environment:

   ```bash
   # Create virtual environment
   python -m venv venv
   
   # Activate virtual environment
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run Chainlit:
```
chainlit run app.py -w
```

5. Start LM Studio's dev server with a model of your choice that supports tool calls (https://lmstudio.ai/docs/app/api/tools)

6. Connect an MCP server and try it out in the Chainlit UI
