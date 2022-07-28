# Pewlett-Hackard-Analysis

## Overview

Pewlett Hackard has a large number of employees that will be retiring soon, calling it the "silver tsunami". Retirement plans will be offered to those who meet certain criteria. Positions will need to be filled as well. We have been asked to find out who will be retiring in the next couple years and how many positions need to be filled. I built an SQL database, with CSV files provided by Human Resources. Using this database we were able to show the number of retiring employees per title and the employees that are elgibile to be in the mentorship program. 

Below see Chart that shows the relations between the datasets provided. 


![EmployeeDB](https://user-images.githubusercontent.com/106033535/181636097-a27f200e-4cc5-4a46-a122-e91c8b624395.png)



## Results

* The first deliverable starts by evaluating the number of retiring employees by title. This data shows the retiring employees, the position they started in, and the position they are retiring from. 


![Retirement Titles](https://user-images.githubusercontent.com/106033535/181637047-fb05ed83-912e-4141-b62e-828e47dd33d6.png)


* Then we narrowed down the data set to get a unique set of titles to show employees retiring from their most recent title and excludes those no longer working. Doing this reduced the data set by over 40,000.


![Unique Titles](https://user-images.githubusercontent.com/106033535/181637415-ae0da210-13c1-441c-8ba9-8b016eb578a9.png)


* The final part of Deliverable 1 determines the total number of employees by count retiring from each title. 


![Retiring Titles](https://user-images.githubusercontent.com/106033535/181637568-469c253f-1bca-4d64-afb9-b294a8f34281.png)


* In the second deliverable a query was built to determine the employees eligible for the mentorshp program based on birth date. Current retiring employees born between January 1, 1965 and December 31, 1965 are eligible. Based on birth year there are 1549 employees eligible for the mentorship program. 


![Mentorship Eligibility](https://user-images.githubusercontent.com/106033535/181637906-d837b5d0-fa23-4800-9a44-fea6294b52c4.png)


## Summary

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
* How many roles will need to be filled as the "silver tsunami" begins to make an impact?

  - The total number of retiring employees is 90,398.  

* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

  - Out of 1,940 potential mentors, 458 of them have been with the company since between 1985 and 1989. 
  
  
  ![mentorship employees by dept](https://user-images.githubusercontent.com/106033535/181641533-702880e7-6acf-41c4-8f11-28ffc30b125b.png)
