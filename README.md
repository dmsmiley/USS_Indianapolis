![alt text](https://upload.wikimedia.org/wikipedia/commons/a/a9/USS_Indianapolis_%28CA-35%29_underway_at_sea_on_27_September_1939_%2880-G-425615%29.jpg "USS Indianapolis c.1939")

# Machine Learning: USS Indianapolis Survival Exploration

Tasked with the top secret mission of delivering what would become the most important package of ending WWII, the USS Indianapolis left San Francisco on July 16, 1945. Traveling through Pearl Harbor, the very symbol of America's involvement of the conflict, the ship and its nearly 1200 personnel arrived on the small Mariana Island of Tinian supplying the Enola Gay with the "Little Boy": the atomic weapon that would be dropped on Hiroshima in a mere weeks time. Unbeknownst to anyone, the USS Indianapolis too would suffer its own catastrophic demise.         

### Software and Libraries
This project utilizes the following software and Python libraries:
* Python 3.7
* NumPY
* Pandas
* Matplotlib
* Jupyter Notebook/Google Colab

### Introduction:
This project attempts to predict the survival outcomes from the sinking of the USS Indianapolis in 1945. The data that I was able to obtain will allow the study to focus on the rank, pay grade, and status of a soldier based on their enlistment or commission. 

I would like to thank USSIndianapolis.org for preserving the memory of all the servicemembers who were aboard the USS Indianapolis. Their detailed dataset allowed for this project to happen.

Definitions:
* LAST: The last name of the individual
* FIRST: The first name of the individual
* ROLE: The abbreviated specific role of the servicemember
* PAY GRADE: The level of pay according to each person's role
  * An E-grade was for servicemembers in the enlisted rank
  * An O-grade was for servicemembers in the commissioned rank
  * According to Navy.com, E-1 represents the highest paid rank for enlisted members, while O-1 is the lowest for commissioned members.
* RANK: The general category for enlisted vs commissioned personnel
* SURVIVAL: Outcome of survival (0 = Not Survived, 1 = Survived)
