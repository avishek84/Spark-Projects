Fire Department Calls for Service:

https://data.sfgov.org/Public-Safety/Fire-Department-Calls-for-Service/nuek-vuh3

Fire Calls-For-Service includes all fire units responses to calls. Each record includes the call number, incident number, address, unit identifier, call type, and disposition. All relevant time intervals are also included. Because this dataset is based on responses, and since most calls involved multiple units, there are multiple records for each call number. Addresses are associated with a block number, intersection or call box, not a specific address.



Fire Incidents:

https://data.sfgov.org/Public-Safety/Fire-Incidents/wr8u-xric

Fire Incidents includes a summary of each (non-medical) incident to which the SF Fire Department responded. Each incident record includes the call number, incident number, address, number and type of each unit responding, call type (as determined by dispatch), prime situation (field observation), actions taken, and property loss.




The entire project is implemented in PySpark. This project deals with reading a .csv file with an user defined schema. Specific questions related to the dataset has been answered. Many PySpark functions has been used to manipulate the data in order to answer the question set.

<p>Main Spark tasks performed here are:</span></p>
<ul>
    <li>Reading a .csv file to a dataframe.</li>
    <li>Defining a user defined schema along with the appropriate data types.</li>
    <li>A bit of exploratory data analysis.</li>
    <li>Renaming the column names.</li>
    <li>Various Spark functions have been used for data manipulation.</li>
    <li>Data time manipulations along with dropping non required columns.</li>
    <li>Repartitioning has also been performed for optimization.</li>
    <li>Spark SQL has also been implemented in some places.</li>
    <li>Joining of two datasets - Fire_Incidents.csv and Fire_Department_Calls_for_Service.csv has been performed to answer few more questions related to the dataset.</li>
</ul>

<br>

The entire project has been done with Jupyter Notebook and PySpark in a local machine.
