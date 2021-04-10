# Timeline-heatmap
The code is all programmed by Python, and the Folium library is mainly used to dynamically display the donation heat chart of the states during the US presidential election. The purpose is to enhance the understanding and application of the Floium library.<br/>
- The data consists of two parts<br/>
  sum.csv:Total state donations during the presidential election.<br/>
  US-states.json: U.S. geographic boundary data.<br/>
  CCL. TXT, weball20. TXT, itcont_2020_20200722_20200820: some data about the presidential election.See Problem Introduction.ipynb for more details<br/>
  Keep the data in the same directory as the code.<br/>
- The code consists of two parts:<br/>
  Part 1: Timeline.ipynb<br/>
  A dynamic display of cumulative contributions from each state over time, day to day.<br/>
  Part 2: Heatmap.ipynb<br/>
  Show the final state total and mark the states with the highest total contributions by a flow curve.<br/>
Note that when running these two sections of code, install the corresponding libraries ahead of time.<br/>

When the first part of the code runs, it looks like this:<br/>

When the second part of the code runs, it looks like this:<br/>
![image](https://user-images.githubusercontent.com/81458165/114260879-063ddc80-9a0a-11eb-8db0-6ec79b239b82.png)





Note: the project background and data based on tian-chi yu series: https://tianchi.aliyun.com/competition/entrance/531837/introduction<br/>
Folium library source code:https://nbviewer.jupyter.org/github/python-visualization/folium<br/>
Folium library personal experience:https://blog.csdn.net/xxxxxbai/article/details/115222847?spm=1001.2014.3001.5501<br/>
