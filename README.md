# Data_Vis_Challenge
Module 5 Data Visualization Challenge

Module 5 was challenging but rewarding upon completion. 

The first small challenge was finding the duplicates and removing the duplicates. I had to use df.drop and specify which Mouse ID I wanted to drop. From the following website I learned how to use the df.drop method:https://saturncloud.io/blog/how-to-remove-rows-with-specific-values-in-pandas-dataframe/

The second small challenged I faced was creating the bar chart. I was having labeling issues and realized that I was using double brackets around "Sex" which, when printed, labeled the name inside a paranthesis and a comma. I remmoved one bracket [["Sex]] and that solved the labeling issue I was having when printing the graph. 

I found it challenging when creating a dataframe that matched the max Timepoint with the appropriate Tumor Volume. I was able to create a dataframe with the max timepooint but without the corresponding Tumor Volume. I sought out help from BCS and they informed me that I had to reset the index. That clarified the situation I was having. 

The next challenging encounter was creating a loop. I contacted CBS once again becuase I needed to talk my thought process out, and online forums were only giving me information but not allowing me to ask questions. CBS was of great when listening to my thought process and they were able to lead me in the right direction when creating a loop. CBS and I discussed the variouse methods we could use to approach this issue and so we used one that I felt most comfortable with. 

The following websites helped me color and enlarge the in the outlier: https://python-charts.com/distribution/box-plot-matplotlib/ , https://stackoverflow.com/questions/65648502/how-to-change-outlier-point-symbol-in-python-matplotlib-pyplot 


I was using the wrong dataframe when creating the line plot. Instead of the cleaned data frame I had created I was using the dataframe that only contained the max timepoints. I contactd CBS and they helped me realize that my issue was the dataframe that I was using. 

When creating the line regression I would recieve an error message that said "'float' object has no attribute 'shape'". I searched the internet until encountering the following video which helped me create my line:https://youtu.be/Uwpk-WcnPG4?si=pZZpxlCaAa4ue14W

