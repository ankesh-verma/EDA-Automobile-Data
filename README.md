# Exploratory Data Analysis - Automobile
![enter image description here](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/HeadImage.jpg?raw=true)
> This project visualizes various features and configuration of vehicles, of different brands, which have impact on the price of vehicle.

#### <u>Objective</u>
  * <b> Analysis</b> of various <b>automobile features and correlation</b> between them
  * <b>Visualizing automobile configuration</b> to keep <b>car's price as low </b>as possible. 

####  <u>Tools Used For Analysis</u>
![EDA TOOLS](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/Tool.PNG?raw=true)
> For doing EDA we have used two type of tools as below:
<table align=center>
<tr><td><b>MANIPULATION</b></td><td><b>VISUALIZATION</b></td></tr>
<tr><td>1. PANDAS</td><td>1. Matplotlib</td></tr>
<tr><td>2. NUMPY</td><td>2.  Seaborn </td></tr>
</table>
<hr>

### <u>About Automobile Dataset</u>
![enter image description here](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/DataSet.PNG?raw=true)
 This automobile dataset consist of data From 1985 Ward's Automotive Yearbook.
<u>**Data Volume**</u>     
![enter image description here](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/rows_cols.PNG?raw=true)
            205 records (rows), 24 variables (columns)
            
 **<u>Attribute Information</u>**
 > * In our Analysis we have used below attributes from dataset
 > 
![Attributes used for EDA](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/attribute_info.PNG?raw=true)

**Visualizations and the Corresponding Insights:**

> 1.  **Aspiration and Fuel-type used**
> 
  If we **Plot** graph for **aspiration** (air-intake) and **fuel-type** used in vehicles we observe that about **~81%** vehicles having **standard (std) aspiration** and **90.24 %** vehicles used **gas** as **fuel-type** as show in below plot:
 
![enter image description here](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/Univariate.PNG?raw=true)
    
> 2. **Price Impact w.r.t. Horsepower**

Below **plot shows** that there is a **positive correlation** between Horsepower and Price of the vehicle, so as we go **higher Horsepower  increases Vehicle Price.**

![enter image description here](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/HP_Price.PNG?raw=true)
Also we observe from **Box Plot** that most of the **vehicles falls in ~80 to 150 HP range**

> 3. **Impact on price due to curb-weight, length, height and width**
> 
Below **Regplot** shows that there is a **positive correlation between Price of vehicle and vehicle's curb-weight, length and width** , so these three have impact on vehicle price, however there is **very less impact** of **Height in Pricing** of vehicle.

![enter image description here](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/BS_CW_HT.PNG?raw=true)

> 4. **Relation Between vehicle Make and Price**

**Prices** of **BMW, Mercedes-Benz and Porsche** are **very high** but **Porsche offers car models** in a **lot pf price ranges**. From premium pricing to pricing comparable to top models of other car manufacturers while **BMW, Mercedes-Benz have only premium segment cars**.

![enter image description here](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/image/make_VS_Price.png?raw=true)

> For Detail Document [Click Here](https://github.com/ankesh-verma/EDA-Automobile-Data/tree/main/PDF)
> For Notebook [Click Here](https://github.com/ankesh-verma/EDA-Automobile-Data/blob/main/ipnb/AutomobileEDA.ipynb)
