# Clustering in Social Media Networks  

## Dataset  
**Students' Social Network Profile Clustering**  
A sample of 15,000 high school students who maintained profiles on a popular social networking platform during the period 2006-2009.  

🔗 [Dataset Link](https://www.kaggle.com/datasets/zabihullah18/students-social-network-profile-clustering)  

## Dataset Description  
This dataset features a randomly selected group of 15,000 high school students who had profiles on a well-known social networking site between 2006 and 2009. The data was collected consistently throughout those years and sheds light on the digital behaviors and interests of teenagers during that era.  

Information was gathered by crawling the social network profiles and applying text mining techniques to identify student interests. The dataset includes frequency counts of the 37 most common terms appearing in the profiles—such as *“football”* and *“shopping”*—highlighting the popularity of different topics among the students.  

Alongside interest data, the dataset contains key demographic details for each student, including:  
- Graduation year (`gradyear`)  
- Gender (`gender`)  
- Age at the time of data collection (`age`)  
- Number of friends or connections (`NumberOfFriends`)  

### Headers  
`gradyear`, `gender`, `age`, `NumberOfFriends`, `basketball`, `football`, `soccer`, `softball`, `volleyball`, `swimming`, `cheerleading`, `baseball`, `tennis`, `sports`, `cute`, `sex`, `sexy`, `hot`, `kissed`, `dance`, `band`, `marching`, `music`, `rock`, `god`, `church`, `jesus`, `bible`, `hair`, `dress`, `blonde`, `mall`, `shopping`, `clothes`, `hollister`, `abercrombie`, `die`, `death`, `drunk`, `drugs`  

## Methodology  
1. **Clean and filter data**  
2. **Create data frame**  
3. **Create a bipartite graph** to show clusters of students and their interests  
4. **Create network graphs by gender and age** to observe how the network structure changes  
5. **Analyze results**

🔗 [Data Analysis Link (accesible with a Sciences Po account)](https://colab.research.google.com/drive/1h4HpIRK5QdVGurWRlkdDkzGSBSb4L-mM?usp=sharing)  

## Main Findings  
- The categories related to *‘music’* are prevalent in **⅔ of the profiles**.  
- The categories related to *‘religion’* are present in **about half of all profiles**.  
- **Females** tend to mention **appearance/social attributes** (e.g., *‘cute’*, *‘dress’*) and **artistic activities** (e.g., *‘dancing’*) more often than males.  
- **Risk behavior terms** (e.g., *‘drugs’*, *‘drunk’*) peak in the **17–19 age range** and appear more prominent among **males**.  
- The **top interests skew heavily towards the female demographic**.  
- Interests like *"music"*, *"sports"*, and *"dance"* tend to **associate strongly with each other**, suggesting high connectivity.  
- **No strong age-based segregation**—indicating that homophily based on age is weak for the top interests.  

---  
This project explores clustering patterns in social media networks, revealing insights into teenage interests and behaviors during the late 2000s.

