# Pynguin Visualization

## How to Run Pynguin:

1. **Set up the Virtual Environment**:  
   Create a new virtual environment with Python version 3.10 and activate it.

2. **Install Pynguin**:  
   Run the following command to install Pynguin:  
   `pip install pynguin`

3. **Run Pynguin**:  
   Use the following command in the console to run Pynguin:  
   `pynguin --project-path <your-input-path> --output-path <your-output-path> --module-name <your-module-name>`  
   Replace `<your-input-path>`, `<your-output-path>`, and `<your-module-name>` with your respective values.

4. **Access the Generated Tests**:  
   The generated tests will be available in the specified `output-path` location.

5. **Generate Logs (Optional)**:  
   To generate logs alongside the tests, use this command:  
   `pynguin --project-path /Users/seva/Pynguin_input --output-path /Users/seva/Pynguin_output --module-name triangle -v`

6. **Extended Logs and Debug Information**:  
   For extended logs and detailed DEBUG information, run:  
   `pynguin --project-path /Users/seva/Pynguin_input --output-path /Users/seva/Pynguin_output --module-name triangle -vv`
