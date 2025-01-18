# Data-Collection-Systems
System Requirements
•	Software Requirements:
- Python 3.10 or higher.
- Required libraries: seleniumbase, pandas, numpy, matplotlib, scikit-learn, pyaudio, speech_recognition.
- A CSV viewer such as Microsoft Excel or LibreOffice Calc.
-	Internet connection for data collection tasks.
- Jupyter Notebook for running and editing the software.
________________________________________
Installation
1.	Download the Software:
o	download the ZIP file and extract its contents.
2.	Verify Installation:
o	Launch Jupyter Notebook: 
o	jupyter notebook
o	Open the relevant .ipynb file for the module you want to run and execute the cells.
________________________________________
Usage Instructions
1. Second-Hand Car Valuation
•	Launch the Notebook: 
o	Open car_data_collection.ipynb in Jupyter Notebook.
o	Run the cells sequentially.
•	Features: 
o	Enter search criteria (e.g., car brand, year, mileage).
o	The software uses seleniumbase to scrape data from sahibinden.com website and saves it to a CSV file named car_data.csv.
•	Output: 
o	A CSV file containing car details such as brand, model, year, mileage, price, city, and crash report.
2. Football Match Result Prediction
•	Launch the Notebook: 
o	Open match_ data_collection.ipynb in Jupyter Notebook.
o	Run the cells sequentially.
•	Features: 
o	Input the league name and desired date range.
o	The script collects match results using seleniumbase and saves them to a CSV file named match_results.csv.
o	Predicts the outcomes of upcoming matches based on historical data.
•	Output: 
o	Match prediction results displayed in the Jupyter Notebook.
o	CSV file containing past match results and predictions.
3. Voice Command Database Creation
•	Launch the Notebook: 
o	Open voice_database.ipynb in Jupyter Notebook.
o	Run the cells sequentially.
•	Features: 
o	Follow on-screen prompts to record 50 different voice commands in English and Turkish.
o	Collect data from at least 10 different individuals for each command.
•	Output: 
o	Recorded audio files saved in the audio_data/ directory.
o	A CSV file named voice_data.csv containing metadata about the recordings.

