---
layout: default
title: DREAM Project Site
---

* TOC
{:toc}

## About Me

Hey! I'm Joe. I used to work as an international tax consultant, and now I'm a current computer science master’s student at Columbia University with an expected graduation of May 2023. I also have a bachelor’s degree in international economics with a concentration that dealt with financial economics. My prior work dealt with a lot of Excel and financial reporting data, which got me interested in how computer science could help make my job more efficient.

After doing some work around VBA automation, I decided to go back to school to improve my formal computer science training. Studying computer science, I have grown curious how business and society can bridge the gap between things like databases and machine learning and people working in other areas who could benefit from such tools but who might be hesitant to give them a try. Outside of computer science, you can probably find me trying every single coffee shop in New York, trying to pick up a bit of a new language here or there, and learning how to be a better cook and baker.
## About My Advisor

Eugene Wu is an Associate Professor of Computer Science at Fu Foundation School of Engineering and Applied Science at Columbia University. He develops systems and algorithms for modern interactive data analysis. His research focuses on the full interactive data analysis stack: from data cleaning and preparation, to scalable systems for interactive exploration interfaces, to automatic interface generation, to explanation tools that help explain anomalies encountered during data analysis.  His current project is the Data Visualization Management System, which integrates concepts from database research, such as declarative languages, query optimization, and lineage, with interactive visualizations, making it easier to design, architecture, build, and scale rich visual data exploration systems.

Professor Wu’s research spans the areas of core database optimization, stream processing systems, crowdsourcing, data visualization, data cleaning, and HCI.  His work includes SASE, one of the first high performance complex event processing systems for high throughput data streams; Scorpion, which introduced a novel analysis feedback system that explains anomalies that analysts find in data visualizations; ActiveClean, the first interactive data cleaning algorithm designed for data science; and Precision Interfaces, the first large-scale automatic interface generation system.  His current work in data visualization management systems draws connections between data visualizations and data processing systems and unifies them under a single system abstraction. The interdisciplinary nature of his research leads Wu to work closely with researchers in information visualization, perception, theory, and machine learning.
Professor Wu received a BS in electrical engineering and computer science from UC Berkeley in 2006, a PhD in electrical engineering and computer science from MIT in 2015, and was a Postdoctoral Fellow at UC Berkeley in 2015.

See here for the WuLab [Website](https://cudbg.github.io/lab/) & [Blog](https://medium.com/thewulab).

## About My Project

Billions of dollars of crops are lost each decade to disasters [(link)](https://www.fao.org/resources/digital-reports/disasters-in-agriculture/en/), and climate change may impact where and how much of different crops can be produced [(link)](https://climate.nasa.gov/news/3124/global-climate-change-impact-on-crops-expected-within-10-years-nasa-study-finds/). To counter the ever-present and growing risk to crops, insurance programs have been created to help farmers all over the world. 

Some of these programs employ index insurance (i.e., insurance that provides a payout at a trigger reached on some index). Index insurance creates a clear way to provide payouts, but it also simplifies the complexity of the world. This creates a dilemma; how do you design a good trigger so no one is left behind while also incentivizing people to produce as much as possible? One approach is to try and adjust your quantitative index for feedback from in-person assessments.  

In partnership with the Financial Instruments Sector Team (FIST) of the International Research Institute for Climate and Society at the Columbia Climate School, the team I work on under Professor Wu works to develop an open-source toolkit for index insurance. That means we can easily deploy a database and corresponding visualizations that allow people to tweak the parameters that go into the payout trigger. The database can execute queries against satellite and other data in an efficient manner allowing for rapid data visualizations. The end objective is to create an interface where end-users can tweak their parameter choices based on how the visuals change. 

In the case of farming, the tool helps to ensure that a trigger can be reached in which both insurance providers and farming communities believe fair. In short, it helps make a trigger that encourages the adoption of farm insurance, lessening the greater risk to crops that we live with today. More generally, the work we are doing will allow others to deploy low-cost index insurance schemes that take into account both quantitative and qualitative data. 

Our toolkit runs on open source technologies including Svelte, DBT, Flask, and duckDB web assembly among others.

[My Final Report](files/finalreport.pdf)

## My Blog

[My Blog](blog.html)
