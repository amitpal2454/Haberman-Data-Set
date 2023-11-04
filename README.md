# Haberman-Data-Set 
the Haberman's Survival Dataset is a famous dataset in the field of survival analysis. It contains data from a study conducted at the University of Chicago's Billings Hospital between 1958 and 1970, which focused on the survival of patients who had undergone surgery for breast cancer.

The dataset includes the following attributes:

Age: The age of the patient at the time of the operation.
Year: The year of the operation (ranging from 1958 to 1970).
Nodes: The number of positive axillary nodes detected. Axillary nodes are lymph nodes located in the armpit region.
Survival Status: This attribute has two classes: 1 (the patient survived for more than 5 years after the operation) and 2 (the patient died within 5 years).
I have performed data analysis of this dataset and there are below observation :
1.Given dataset have 306 rows and 4 columns
2.Columns are [age,year,nodes,status]
3.we are considering 1 as Yes and 2 as No
4.Data collects 73.52% as Yes and 26.74 as No
5.Age lies between 30-78
6.75% Patient have 4 nodes
7. Patient year of Opertaion lies between 1958-1969
8.Based on the 3 varying parameter our total number of plot will be 3C2 which is 3
9. from all three 2D scatter plot we are not able to seprate one paremeter which can determine the status of patient
10.Huge overlapping can be observed among the classes. Thus the classes are linearly separable.
11. Patient which have age in between 41-58 have less chance of survival.
12. More number of Patient survived having age in the range of 30-40
13.1958-1960 there are more failed operation.
14.Patient which have 4 or less nodes have more chance of survival
15.Pateint which have less than 4 nodes have more chance of survial
There are more overlap in various parameter configuration So it's not easy to point one parameter which determine survival of patients
Patient's age and year is not only important parameter in determining the survival of a patient.
The objective of classifying the survival status of a new patient based on the given features is a difficult task.




