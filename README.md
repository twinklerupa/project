<!DOCTYPE html>
<html lang="en">

<body>
    <h1>PDS Project</h1>
    
  <h2>Project 1: Data Manipulation, Handling Missing Data, Data Visualization</h2>
  <p>This project focuses on loading, cleaning, and visualizing the Titanic dataset.</p>
    
  <h3>Steps:</h3>
  <ol>
        <li>Load the dataset from: <a href="https://raw.githubusercontent.com/PulockDas/pd-12-resources/refs/heads/master/titanic.csv">Titanic Dataset</a></li>
        <li>Identify columns with null values.</li>
        <li>Fill null values in 'Age' with the mean and in 'Cabin' with 'Unknown'.</li>
        <li>Create bar plots for Survived vs. Dead, categorized by Gender and Pclass.</li>
        <li>Create an 'AgeClass' column based on age groups.</li>
        <li>Drop the 'Age' column.</li>
        <li>Visualize Survived vs. Dead counts using 'AgeClass'.</li>
  </ol>
    
  <h3>Assignments:</h3>
    
   Create 'Number of Relatives' column and scatter plot (Relatives vs. Fare for Alive).
    
  <h3>Project 2: Dataset Merging, Data Manipulation, K-Means Clustering</h3>
  <p>This project involves merging datasets, data manipulation, and clustering.</p>
  <h3>Steps:</h3>
  <ol>
        <li>Create two CSV files: 'term-test-1-result.csv' and 'term-test-2-result.csv' with student scores.</li>
        <li>Load both files into Pandas and merge them based on 'Registration Number'.</li>
        <li>Compute best and average term test marks for each student.</li>
        <li>Drop original test columns and merge with attendance and final marks data.</li>
        <li>Calculate Final Marks: <code>Final Marks = (Term Final * 0.7) + Average Test + Attendance</code></li>
        <li>Save the final dataframe to 'final-result.csv'.</li>
        <li>Apply K-Means clustering (1&lt;K&lt;6) to categorize student performance.</li>
        <li>Visualize the final clusters.</li>    </ol>
    
   <h2>Technologies Used</h2>
  <ul>
        <li>Python</li>
        <li>Pandas</li>
        <li>Matplotlib</li>
        <li>Seaborn</li>
        <li>Scikit-Learn</li>
   </ul>  <h2>How to Run</h2>
  <ol>
        <li>Install dependencies: <code>pip install pandas matplotlib seaborn scikit-learn</code></li>
        <li>Run the script to clean and visualize the Titanic dataset.</li>
        <li>Generate CSV files for student marks and perform clustering.</li>
        <li>Analyze and interpret the clustering results.</li>
  </ol>    
  <h2>Contributors</h2>
  <p>Mahfuja Rahman - <a href="mahfujarahman8689@gmail.com">mahfujarahman8689@gmail.com</a></p>
    
</body>
</html>
