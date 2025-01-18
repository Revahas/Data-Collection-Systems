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
-	download the ZIP file and extract its contents.
2.	Verify Installation:
- Launch Jupyter Notebook: 
-	jupyter notebook
-	Open the relevant .ipynb file for the module you want to run and execute the cells.
________________________________________
Usage Instructions
1. Second-Hand Car Valuation
•	Launch the Notebook: 
-	Open car_data_collection.ipynb in Jupyter Notebook.
-	Run the cells sequentially.
•	Features: 
-	Enter search criteria (e.g., car brand, year, mileage).
-	The software uses seleniumbase to scrape data from sahibinden.com website and saves it to a CSV file named car_data.csv.
•	Output: 
-	A CSV file containing car details such as brand, model, year, mileage, price, city, and crash report.
2. Football Match Result Prediction
•	Launch the Notebook: 
-	Open match_ data_collection.ipynb in Jupyter Notebook.
-	Run the cells sequentially.
•	Features: 
-	Input the league name and desired date range.
-	The script collects match results using seleniumbase and saves them to a CSV file named match_results.csv.
-	Predicts the outcomes of upcoming matches based on historical data.
•	Output: 
-	Match prediction results displayed in the Jupyter Notebook.
-	CSV file containing past match results and predictions.
3. Voice Command Database Creation
•	Launch the Notebook: 
-	Open voice_database.ipynb in Jupyter Notebook.
-	Run the cells sequentially.
•	Features: 
-	Follow on-screen prompts to record 50 different voice commands in English and Turkish.
-	Collect data from at least 10 different individuals for each command.
•	Output: 
-	Recorded audio files saved in the audio_data/ directory.
-	A CSV file named voice_data.csv containing metadata about the recordings.

