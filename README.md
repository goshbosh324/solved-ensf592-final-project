Download Link: https://assignmentchef.com/product/solved-ensf592-final-project
<br>
5/5 - (1 vote)

<header></header>



 <main></main>



<span style="font-size: 2em;">&#x1f4da; Learning Outcomes</span>

<ul>

 <li>Design and document a terminal-based Python application</li>

 <li>Select, import, and manipulate a set of data</li>

 <li>Merge multiple datasets using Pandas</li>

 <li>Use hierarchical indexing to sort and slice data</li>

 <li>Process data according to user input</li>

 <li>Operate on data in Pandas and NumPy</li>

 <li>Display data using Matplotlib</li>

</ul>

<h2 id="programspecifications">&#x1f4bb; Program Specifications</h2>

For this final project, you have flexibility to design and develop your own terminal-based data analysis program in Python. Your application must meet the following design specifications:

<ul>

 <li>Your final output should match the given examples (see attached screenshots)</li>

 <li>Stage 1: Dataset Selection</li>

 <li>Several suggested datasets are included in the project repository. You may use the provide data or select datasets of your own choosing.</li>

 <li>You must use at least three separate Excel sheets or files that can be related in some way.</li>

 <li>Your final combined dataset (see next stage) must have at least ten columns and 200 rows.</li>

 <li>You may edit the given datasets before you begin coding, but your program should not modify the Excel files directly.</li>

 <li>You may not hard-code/copy-paste any information into your program except for the Excel column names.</li>

 <li>Stage 2: DataFrame Creation</li>

 <li>Import your chosen data into a Pandas DataFrames.</li>

 <li>You must use at least two merge/join operations and you must delete any duplicated columns/rows that result from the merge.</li>

 <li>You must create a hierarchical index of at least two levels (row or column).</li>

 <li>All data should be presented in the correctly sorted order, depending on the index.</li>

 <li>You may not use global variables. You must import the data within your main function.</li>

 <li>Remember to check for null values or data mismatches.</li>

 <li>Stage 3: User Entry</li>

 <li>Your application must return useful information. Design an interface that allows users to search based on some sort of criteria or keywords.</li>

 <li>The user must provide at least two pieces of information/selection (e.g. “school name” and “grade”)</li>

 <li>Give the user clear input instructions. If an invalid entry is given, use try/except statements to handle the error. Your program should not terminate.</li>

 <li>You must not hard-code any data values (the data within your spreadsheets could be changed!).</li>

 <li>Any output information must be clearly defined using printed headers.</li>

 <li>Stage 4: Analysis and Calculations</li>

 <li>You may choose what data trends to presents from your data. However, you must meet the following specifications.</li>

 <li>Use the describe method to print aggregate stats for the entire dataset.</li>

 <li>Add at least two columns to the combined dataset.</li>

 <li>Use an aggregation computation for a subset of the data.</li>

 <li>Use a masking operation.</li>

 <li>Use the groupby operation at least once.</li>

 <li>Create and print a pivot table.</li>

 <li>Include at least two user-defined functions or a class that contains two methods.</li>

 <li>Stage 5: Export and Matplotlib</li>

 <li>Export your entire merged, hierarchical dataset to an Excel file in the working directory. Be sure to include the index and header values. The TAs will use this to verify the structure of your dataset.</li>

 <li>Use your data to create at least one plot using Matplotlib. Save the plot as a <code>.png</code> file and upload to the repository.</li>

 <li>Your code must follow the conventions discussed so far in the course (names<em>with</em>underscores, ClassNames, four spaces for indentations, spaces between variables/operators, comments throughout, etc.)</li>

 <li>All classes, methods, and functions must contain docstring documentation.

  <ul>

   <li>For each class, include a functionality summary and describe any class and/or instance variables (do not include a separate docstring for __init__)</li>

   <li>For each method/function, include a functionality summary and describe parameters and return values (or specify if there are none)</li>

   <li>Main functions do not need a docstring but should be well-commented</li>

  </ul></li>

 <li>You may go beyond the minimum requirements specified here!</li>

 <li>Your code will be run by the TAs as your end user.</li>

 <li>FAQs about the project will be answered on the D2L discussion boards. Please check the boards for any clarifications before submitting.</li>

 <li>The grading rubric is included in this repository and posted to D2L.</li>

</ul>

<h2 id="assignmenttasksanddeliverables">&#x1f4dd; Assignment Tasks and Deliverables</h2>

<ul>

 <li>You must submit the following items within your repository (one repo per team if working with a partner):

  <ul>

   <li>Your Python code files</li>

   <li>Screenshots of successful execution</li>

   <li>Plot output as a <code>.png</code> file</li>

   <li>Your input dataset</li>

   <li>Your exported dataset</li>

   <li>A brief PDF summary of how your project meets the requirements (include a citation for your dataset)</li>

   <li>You do not need to create a new README file- your user input instructions should be clear from your interface, but you may put any introductory information directly in the comments under your code header.</li>

   <li>You will also give a 5 minute presentation during the lab on June 17th. All team members must participate. Be prepared to answer questions about your program. If you are unable to attend the lab, you must make arrangements with Dr. Marasco ahead of the session. Presentations will be recorded for the TA/instructor to view only.</li>

  </ul></li>

 <li>Make sure to watch all video lessons and labs, and review the corresponding Jupyter Notebooks.</li>

 <li>Clone this repository to your local computer.</li>

 <li>Open VSCode and start a new terminal. Make sure that your <code>ensf592</code> environment is activated.</li>

 <li>Create your <code>.py</code> file and remember to place your information in the header.</li>

 <li>Remember to test your program execution via the terminal.</li>

 <li>Take a screenshot of your successful program run and upload it to your assignment repository.</li>

 <li>Commit your screenshot and code.</li>

 <li>Push your local git history to github: <code>git push origin main</code></li>

 <li>One member of your team should submit your repository HTTPS link to the Project dropbox. Please list both members’ names and your group number in the textbox.</li>

 <li>Tip: If you want to learn more about a specific aspect of a Python object or the functionality of imported modules, remember to take a look at the official documentation!</li>