# 🌍 **Global Education Dashboard Analysis**  
---
<br><br>

## INTRODUCTION
Education is a fundamental right that everyone should have access to. It enables individuals to build their futures, achieve their goals, and connect with the world. However, many people, particularly in low-income regions and among certain demographics, still lack access to quality education. These disparities, based on income and even gender, prevent progress toward a more equitable education system.

Over the centuries, education has evolved significantly. What was once a privilege reserved for the few is now considered essential for most. This shift is evident in the increasing number of students enrolling in schools and rising global literacy rates. However, mere enrollment is not enough; the quality of education matters just as much.

In many low-income countries, a large percentage of students complete primary school without acquiring fundamental literacy and numeracy skills. This educational deficiency limits their potential and perpetuates cycles of poverty. Addressing these disparities is crucial to ensuring that education serves as a powerful tool for positive change.

On the following analysis we will emerge into a deeper analysis of Global Education, so get ready for the journey 🚀📊.
<br><br>
<br><br>


## OBJECTIVE
The objective of this analysis is to examine a dataset containing global education information. The goal is to gain insights into how well current education systems provide access to learning opportunities for all. This analysis will help identify areas for improvement and better understand the global state of education.

You can find the detailed information about the dataset at <a href="https://www.kaggle.com/datasets/imtkaggleteam/global-education">Kaggle</a>, which sources are <a href=https://data.worldbank.org/>World Bank Open Data</a> and <a href="https://databrowser.uis.unesco.org/">Unesco</a>.
<br><br>
<br><br> 
 
## DATASETS
🏫 Share of the World Population with at Least Basic Education - This dataset contains information about the share of adult population (older than 15) that has received at least basic education (primary and lower secondary education). 

🧑‍🏫 Learning-Adjusted Years of Schooling - This dataset measures the number of years of schooling adjusted for education quality, providing an estimate of actual years of effective learning.

🎒 Number of Out-of-School Children - This dataset reports the number of children who are not enrolled in primary or secondary education, highlighting dropout rates and enrollment gaps. 

👨‍🤝‍👩 Gender Gap in Education Levels - This dataset tracks enrollment across different education levels based on gender.
<br><br>
<br><br>
 
## ANALYSIS
![image](https://github.com/user-attachments/assets/6a777036-b9aa-42f7-b325-337f504a5547)
<br><br>

### Ribbon Filter
![image](https://github.com/user-attachments/assets/a8c8aee0-6bef-49e6-9ccc-ca8bc8d4d4fb)
At the top of the dashboard, a ribbon filter allows users to refine the data by continent and country for a more detailed and focused analysis. The data has been sourced from World Bank Open Data, but some countries may have missing data due to resource constraints, government restrictions, or other factors.
<br><br>

### First Section
Below the ribbon, the first section provides key insights into global education trends through essential KPIs and visualizations. It highlights the distribution and accessibility of education worldwide (or in selected regions based on applied filters). The metrics showcase adjusted years of schooling, adult education levels, out-of-school students, and enrollment trends across different education levels, offering a clear picture of progress and challenges in education over time.

DISCLAIMER: Some inconsistencies in the data happen for the already explained reasons of countries not showing or taking part of the surveys to get Educational information.

![image](https://github.com/user-attachments/assets/03436e8f-df5d-4e86-85e6-4c0465d48955)


* The top KPI shows the Learning Adjusted Years of School (LAYS) during 2020, a measure that combines the quantity and quality of education across countries, in which there is a trend where poor or less developed countries have lower LAYS, between 2 and 6 points, whereas richer and more developed countries have LAYS above 10 points. For example, the bottom countries with less AYS points are Liberia (2.2), followed by South Sudan (2.5), Mali (2.6), Central African Republic, Niger (2.7) and Chad (2.8). On the other hand the top countries are Singapore (12.8), followed by Hong Kong (11.9), Canada, Estonia, Finland, Japan and South Korea (11.7). Across most countries in South Asia and Sub-Saharan Africa – where the largest share of children live – the average years of quality schooling are less than 7.
  
![image](https://github.com/user-attachments/assets/8f90aa1c-864c-4e37-8a58-2947b95de875) ![image](https://github.com/user-attachments/assets/efcf329c-dec3-45ec-98ca-546d4fb6017f)


* The pie chart below, represents the percentage of Adult people (+15 years old) with some basic education in 2020, we can also see a similar trend where rich countries with high LAYS have bigger rates of population with basic education. Nevertheless, in recent years the amount of people with basic education is about 9 of 10 people, which has been a great increase compared to past results where only 1 out of 5 could get basic education.
  
![image](https://github.com/user-attachments/assets/836a4eac-2206-4d1b-9e24-4590f90f135f)


* To the right we have a line chart showing the amount of out of school students by gender from 2000 to 2020, we can see that there has been a decresed in the total number of out of school students closign the gap between males and females. One interesting fact is that in 2013 there is a peak on the amount of out of school students, because India's report on this matter has been meassured only once in 2013, hence without India the 2013 peak would get smoother. The same happens when looking at some continents such as Oceania where Papua New Guinea has registed out of school students once on 2016.
Many children who attend primary school drop out and do not attend secondary school. That means many more children or adolescents are missing from secondary school than primary education.


* Finally on the right we have a line-area chart showing the enrollment of students on each education level. From this graph we can see a pattern which is that every education level has increased throughout the years, specially tertiary education that has been growing with high speed on recent years. Inconsistencies on the graph might occur when looking at specific regions, specially if throuogth the years some countries have shared data or not, making this rates vary a lot if rich or poorer countries shared their data.
<br><br>


### Second Section
This section focuses on enrollment trends across primary, secondary, and tertiary education, analyzing gender and income disparities, where users can analyze how enrollment rates have evolved over time, comparing male and female participation as well as variations across different income levels. These insights help highlight progress in educational access and persistent gaps that still need to be addressed. 
DISCALIMER: The income filter does not filter income in an specific region or country, it takes all countries in account for the disparity in income, so the income groups countries in their overall income.

![image](https://github.com/user-attachments/assets/ad251b13-9ca3-4829-96e1-836ffff3af07)

* The first (left) chart of this section shows the ratio of enrolments in the 3 education levels, the main interesting fact that aroses from this visualization is how the gap between females and males have been closing over the years, before males have ease at enrolling for education, now it is quite similar, except for tertiary level where we can see an overcome of females enrolled for education, this might represent that females get higger levels of education than males, this trend is due to a number of factors, including academic preparation, personal choices, and social factors, one of the main reasons is that most men start working, leaving their education in a background plane, <a href ="https://www.pewresearch.org/short-reads/2021/11/08/whats-behind-the-growing-gap-between-men-and-women-in-college-completion/"> "Non-college-educated men are also more likely than their female counterparts to say a major reason they don’t have a four-year degree is that they didn’t need more education for the job or career they wanted (26% of men say this vs. 20% of women)." </a>. Other interesting articles related to these could be found here: <a href="https://onlinelibrary.wiley.com/doi/full/10.1002/ejsp.3109">Do women only apply when they are 100% qualified, whereas men already apply when they are 60% qualified?</a>.

* The second (right) chart shows how the enrolment varies by income and gender. Through this graphs we can see that countries with low incomes get less enducation that their contraparties that get more education, specially in tertiary levels we can see that poorer countries get an 8% enrolment, whereas richer countries get up to 80%, ten times higher. Another intersting thing to point out is that in low-income countries the enrolment from primary education to secondary level has a 40% decreased, showing that most kids have to quit out of school to help their parents with financial tasks Low-income countries often have very low secondary enrollment rates primarily due to poverty, which forces families to prioritize basic needs like food and shelter over education costs like tuition, uniforms, and supplies, making it difficult for children to attend secondary school; additionally, factors like lack of access to quality schools, inadequate infrastructure, and the need for children to work to contribute to household income can further contribute to low enrollment rates. Finally, another thing to point out is that between middle-low to high income countries the difference or gap between females and males is quite similar or with more females than males enrolled, but for low income countries males get more education than females, In low-income countries, there are typically more male students than female students due to a combination of factors including cultural norms favoring boys' education, poverty forcing families to prioritize boys when making educational decisions, early marriage for girls, lack of access to proper sanitation facilities for girls in schools, and gender-based violence, which can deter girls from attending school. <a href="https://www.sciencedirect.com/science/article/abs/pii/S014759672200083X#:~:text=For%20example%2C%20poor%20maternal%20health,years%20(Jayachandran%2C%202015).">The gender education gap in developing countries</a> 
<br><br>


### Third Section
This section examines the distribution of basic education among adults (15+) across different regions. By tracking historical trends, it highlights disparities in educational attainment worldwide, showcasing regions that have made significant progress and those still facing challenges. These insights provide a broader perspective on long-term access to education and its regional variations.

![image](https://github.com/user-attachments/assets/445c1958-4627-4e05-a159-dd15f2420890)

The regions given are from the <a href="https://pbs.twimg.com/media/DoIqABUXgAAj9Tx?format=jpg&name=4096x4096"> World Regions according to Maddison, 2010 </a>.

* The line chart graph delves into the distribution of basic education among adults aged 15 and above across various regions, highlighting both progress and persistent disparities. Despite global advancements in educational access, significant challenges remain. These educational deficiencies during youth often translate into lower educational attainment in adulthood, perpetuating cycles of poverty and limiting economic opportunities. Moreover, the impact of climate change has exacerbated these challenges; in 2024 alone, extreme weather events disrupted the education of at least 242 million children across 85 countries, predominantly in low-income nations in Asia and sub-Saharan Africa.  By analyzing historical trends and regional data, this section aims to provide a comprehensive understanding of where educational initiatives have succeeded and where intensified efforts are needed to ensure that all adults possess fundamental educational skills.
<br><br>
<br><br>

## CONCLUSION
This analysis highlights significant progress in global education while identifying persistent disparities. Key findings include:

* Education access has improved significantly, with rising enrollment rates and a closing gender gap.
* Quality remains a major issue, particularly in low-income regions where learning outcomes are poor despite years of schooling.
* Economic status remains a crucial determinant of education access, with tertiary education being largely inaccessible to lower-income populations.

Addressing these issues requires continued investment in education infrastructure, targeted policies to reduce dropouts, and efforts to ensure equitable access to high-quality education worldwide. By leveraging data insights, policymakers and stakeholders can make informed decisions to bridge the education gap and foster inclusive growth for future generations.
