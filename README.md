# WhatsApp Chat Analyzer

## Introduction
This Streamlit app analyzes WhatsApp chat data. It provides insights such as total messages, word count, media shared, links shared, monthly timeline, daily timeline, activity map, word cloud, most common words, and emoji analysis.

## Analysis Results
To view the analysis results, please run the Streamlit app and click on the "Show Analysis" button.

## Usage
1. Download or clone this repository.
2. Install the required dependencies by running:
3. Ensure you have the additional file `preprocessor.py` in the same directory.
4. Run the Streamlit app using the following command:
5. Upload your WhatsApp chat data file and select the user for analysis.
6. Click on the "Show Analysis" button to generate insights.

## Dependencies
- streamlit
- pandas
- matplotlib
- seaborn

## Additional File: `preprocessor.py`
This file contains a preprocessing function `preprocess(data)` to clean and organize WhatsApp chat data before analysis.
## File Structure
- `app.py`: Main Streamlit application code.
- `preprocessor.py`: Preprocessing functions for WhatsApp chat data.
- `helper.py`: Helper functions for analysis and visualization.
  
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
