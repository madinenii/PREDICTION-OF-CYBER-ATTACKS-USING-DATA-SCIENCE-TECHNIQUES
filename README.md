# PREDICTION-OF-CYBER-ATTACKS-USING-DATA-SCIENCE-TECHNIQUES

Cyber-attacks are a growing hazard to cyber physical systems, and firms that
handle sensitive data must be able to identify and anticipate these attacks. Because
the types of Cyber Attacks are becoming more diverse, anti-virus scanners alone
are no longer adequate to offer protection. The growth of Internet of Things (IoT)
devices has led to significant increases in cyber security vulnerabilities, and the
market for software is growing as more software is used in more aspects of daily
life. Hackers launch cyber-attacks in a variety of ways, including Phishing, Dos,
R2L, Probing, Malware, and U2R. Large data sets can occasionally be
compromised without the affected parties' knowledge, which can cause serious
interruptions to business continuity and large financial losses. By examining
security data, Machine Learning technology is essential for providing an
automated, dynamically improved, and up to security system. Large datasets may
be handled by Machine Learning technology, which also provides greater
visualization capabilities. Due to built-in weaknesses and threats that can be used
at any stage in the system, supply chain security is difficult. Our study's findings
demonstrate that the majority of rules exhibit steady support and confidence
values, enabling the prediction of Cyber Attacks over a period of days without the
need for daily rule updates. 

Recommendation, the researchers present the suggested methodology as well as the tools and methods used. The
diagram below displays the Spark Chi SVM algorithm. The
steps of the proposed version can be summarized as follows.
Fresh expressions are infused throughout the ensemble. An
attack detection model with learning capabilities developed
specifically for ICS setups. To detect instances of
cyberattacks, the latest version of this system combines a
Deep Neural Network with a Decision Tree classifier. Using
authentic ICS datasets and 10-fold cross-validation, the
efficacy of this strategy is assessed and compared to the
standard method, indicating that the updated version performs
better. For this evaluation, classifiers including AdaBoost,
DNN, and Random Forest were used (RF). 

INSTRUCTIONS TO RUN THE CODE
Step 1: Install Anaconda and Jupyter Notebook

Download and install the latest version of Anaconda from the official website (https://www.anaconda.com/products/individual).
During the installation process, make sure to select the option to add Anaconda to your system's PATH.
After installing Anaconda, open the Anaconda Navigator, and from there, install Jupyter Notebook.

Step 2: Save the Files

Save the "dataset_sdn.csv" and "CYBER ATTACK PREDICTION.py" files in the same directory or folder on your computer.

Step 3: Open Jupyter Notebook

Launch Jupyter Notebook from the Anaconda Navigator. This will open a web browser with the Jupyter Notebook interface.

Step 4: Import the Python Script

In Jupyter Notebook, navigate to the directory where you saved the "CYBER ATTACK PREDICTION.py" file.
Click on the "Upload" button or drag and drop the file into the Jupyter Notebook interface to import it.

Step 5: Set the File Path

Open the Python script ("CYBER ATTACK PREDICTION.py") in Jupyter Notebook.
Locate the line of code where the dataset file is read, which should look like this:
bash
Copy code
df = pd.read_csv('C:/Users/madin/OneDrive/Desktop/MONISH/cyber/dataset_sdn.csv')
Replace the file path 'C:/Users/madin/OneDrive/Desktop/MONISH/cyber/dataset_sdn.csv' 
with the actual path to the "dataset_sdn.csv" file on your computer.

Step 6: Run the Code Cells

Once you have set the correct file path, you can run the code cells by clicking the "Run" button or using the keyboard shortcut Shift+Enter.
Run all the code cells in the notebook in sequential order.

Step 7: View the Output

After running all the cells, the output of the code will be displayed in the notebook.
The output will indicate whether the system is classified as being cyber attacked or not.

Please note that the provided instructions assume you have a basic understanding of Python, Jupyter Notebook, and the necessary dependencies such as pandas. If you encounter any errors or issues, double-check the file paths, ensure the required libraries are installed, and review the code for any potential mistakes.
