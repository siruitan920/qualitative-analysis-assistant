# qualitative-analysis-assistant
Tool for converting user feedback into structured qualitative analysis outputs

## What it does
- Splits raw text into semantic units  
- Generates concise codes for each unit  
- Clusters similar codes into categories  
- Groups categories into themes  
- Assigns sentiment (positive / neutral / negative)  

## Input
- A `.txt` file  
- One feedback per line  
- No preprocessing required  

## Output
- `analysis.xlsx` containing:
  - unit_text  
  - code  
  - category  
  - theme  
  - sentiment  
  - frequency counts  

## How to run
1. Put your input `.txt` file in the project folder  
2. Update the file path in `main.py`  
3. Run:
   ```bash
   python main.py
