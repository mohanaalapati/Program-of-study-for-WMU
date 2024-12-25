# WMU Program of Study Automation

This project helps students at WMU (Western Michigan University) easily create a Program of Study document for the Data Science department. It pulls information from the university website, organizes it, and makes a professional PDF using LaTeX.

## What It Does

- Gets Course Data: Automatically fetches course info and your transcript from WMU’s website.
- Organizes Data: Combines the data to show your completed and remaining courses.
- Makes a PDF: Generates a clean and professional PDF document.

## How to Use

1. Clone this project:
   ```bash
   git clone [https://github.com/yourusername/wmu-program-of-study.git](https://github.com/mohanaalapati/Program-of-study-for-WMU)
   cd wmu-program-of-study
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the program:
   ```bash
   python main.py
   ```

4. Follow the steps on the screen, and your PDF will be saved in the `output/` folder.

## Files in This Project

- `main.py`: Runs the program.
- `scraper.py`: Collects data from the WMU website.
- `data_processing.py`: Organizes and merges the data.
- `template.tex`: The LaTeX template for the PDF.
- `output/`: Where the final PDF is saved.


