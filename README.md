# Dream-House-Finance-Company-Project-on-Crowd-Segregation---Using-K-Mean-Clusters
![image](https://user-images.githubusercontent.com/66888595/113563928-26465800-9626-11eb-8701-8a6e0939ee36.png)

## Table of Contents
<ul>
  <li>
    <a href="#Overview">
      <span>1. Plot</span>
    </a>
  </li>

  <li>
    <a href="#Motivation">
      <span>2. Motivation</span>
    </a>
  </li>
  
  <li>
    <a href="#Aspects">
      <span>3. Technical Aspects</span>
    </a>
  </li>
  <li>
    <a href="#To">
      <span>4. To Do</span>
    </a>
  </li>
  
  <li>
    <a href="#Tech">
      <span>4. Technology Used</span>
    </a>
  </li>
  <li>
    <a href="#Credit">
      <span>4. Credit</span>
    </a>
  </li>
  
 </ul>


<h3>
  <span id="Overview">Overview</span>
</h3>

> In this project of segregating the crowd of customers of **Dream House Finance Company** are divided into some categories/classes/clusters. For this unsupervised problem, K-means Clustering algorithm has been used to divide the crowd in 4 classes.


<h3>
  <span id="Motivation">Motivation</span>
</h3>
> Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban, and rural areas. Customer first applies for a home loan and after that company validates the customer eligibility for the loan. A marketing firm wants to launch a promotional campaign in different regions of the country. So, in order to do that, they need to understand which areas they should focus their resources in order to cover the entire region. We are provided with the population data based on different locations along with the demographics. The objective is to segregate the regions into different groups so that the marketing team can plan their resources accordingly. So, we have to apply classification techniques in order to segregate the regions into different clusters which will help the marketing team. K-means Clustering algorithm will be suitable for this purpose.


<h3>
  <span id="Aspects">Technical Aspects</span>
</h3>
> This project is tecnically divided  into 2 sections. In data preprocessing section, presence of missing values are checked, Intigrity of the data plays a vital role. Using feature generation technique, a new feature has been introduced, which played a important role in explaining the data insights. After applying the model(`n_clusters = 4`), we observed :
>  The scatter plot between Indian and Foreigners is quite linear with a negetive slop. It suggests that , in a certain region with population, the number of Indian increases if the the number of Foreigners decreases and viceversa!
>  An unwanted mixing of dots of different colours. This phenomena can't be describe using only two varibales. It may be explainable using other dimensions.
>  The relationship between Indian Male and Foreigner Male is linear and the slop is negetive!
>  The scatter diagram between female foreigner and female indian isn't obviously classified into 4 classes. This phenomenum can't be explained using this two dimensions.
>  In this way, sctter plot between various features(pair-wise) has been drawn. As follows

<h3>
  <span id="To">To Do</span>
</h3>

<h3>
  <span id="Tech">Technology Used</span>
</h3>

<h3>
  <span id="Credit">Credit</span>
</h3>
