+++
title = "Yunpeng Wu_Final Presentation"
outputs = ["Reveal"]
[reveal_hugo]
theme = "black"

+++

<style>
    .reveal section p {
    display: inline-block;
    font-size: 0.6em;
    line-height: 1.2em;
    vertical-align: top;
  }
</style>


<style>
.reveal section img { background:none; border:none; box-shadow:none; }
</style>


Location Intelligence Final Report

## <font color="#F9B5B2">RETAIL DISPLACEMENT</font> WITH <font color="#A2DBD5">REZONING</font> IN NYC


MSAUD | Yunpeng Wu<br/>
Instructor | Carlo Bailey<br/>
04/15/2021

---
### overview
<font color="#F9B5B2">**How does the rezoning affect the retail displacement in New York City?** 
<br/>
</font>
This research investigates the impact of spatial zoning on retail displacement in New York City. With longitudinal datasets of retail establishments and land use, the research explores the zoning and retail in the following aspects: First, the overall change in number and density of retail stores in NYC. Second, whether the presence of zoning affects the change of retail. Finally, study how zoning's effect performs differently on retail with different types.


---
#### Retail As Social Infrastructure
<img src="https://media.cntraveler.com/photos/5e8236a6a32d290008f50959/16:9/w_2991,h_1682,c_limit/RussDaughters-PD2WJP.jpg" width="80%" height="80%">

"Local small businesses are not
only good for services and access to jobs,
but are critical to the vitality of <font color="#F9B5B2">community
life.</font> " - Jane Jacobs

---
#### Retail Displacement With Zoning
<style>
.container{
    display: flex;
}
.col{
    flex: 1;
}
</style>

<div class="container">

<div class="column" style="float:left; width: 50%">


<img src="image/typology.png" width=500px height=400px>


<font size="2">[Zoning Regulations](https://www1.nyc.gov/site/planning/zoning/districts-tools/commercial-districts-c1-c8.page)
</font>
<br/>
<font size="4">Influence building typology and urban fabric </font>


</div>

<div class="column" style="float:right; width: 50%">



<img src="image/Cov-Map-Color-superJumbo.jpg" width=300px height=400px>


<font size="2">[Moving deeper into brooklyn for lower prices - James Laish](https://www.nytimes.com/2013/03/10/realestate/moving-deeper-into-brooklyn-for-lower-home-prices.html?searchResultPosition=14)
</font>
<br/>
<font size="4">Increase the rent prices </font>

</div>

</div>

---

### Methodology

<img width=95% height=95% src="image/Method.png">


---

### Retail <font color="#F9B5B2">Decline</font> in New York City

---
#### The Decreasing Number of Retail Stores

<style>
  .p_iframe iframe {
    height:650px;
}
</style>

<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="chart/chart1_number__change.html"></iframe>
</div>

---
#### Percentage Change in <font color="#F9B5B2">number</font> of Retail Stores

<style>
.container{
    display: flex;
}
.col{
    flex: 1;
}
</style>

<div class="container">

<div class="column" style="float:left; width: 70%">


<style>
  .p_iframe iframe {
    width:120%;
    height:650px;
}
</style>

<div class="p_iframe">
    <iframe frameborder="0" seamless='seamless' scrolling=no src="map/map1_count_change.html"></iframe>
</div>

</div>

<div class="column" style="float:right; width: 30%">

<p style = "line-height:0.5">
<font size="0.4">Percentage Change in Number of Retail Stores by Census Tract and Borough, 2009-2017</font></p>

<iframe  width="100%" height="250" name="iframe" src="chart/chart2_number_change_borough.html"></iframe>

</div>

</div>

---

#### Percentage Change in <font color="#F9B5B2">density</font> of Retail Stores

<style>
.container{
    display: flex;
}
.col{
    flex: 1;
}
</style>

<div class="container">

<div class="column" style="float:left; width: 70%">


<style>
  .p_iframe iframe {
    width:80%;
    height:500px;
}
</style>

<div class="p_iframe">
    <iframe frameborder="0" seamless='seamless' scrolling=no src="map/map2_density_change.html"></iframe>
</div>

</div>

<div class="column" style="float:right; width: 30%">


<p style = "line-height:0.8">
<font size="0.4">Percentage Change in Percap Density of Retail Stores by Census Tract and Borough, 2009-2017</font></p>


<iframe  width="100%" height="250" name="iframe" src="chart/chart3_density_change_borough.html"></iframe>


</div>

</div>

---

### The effect of <font color="#A2DBD5">zoning</font>


---


<img width=95% height=95% src="image/Zoning Change.jpg">


---

#### focus on Commercial districts (C1-C6)

<style>
.container{
    display: flex;
}
.col{
    flex: 1;
}
</style>

<div class="container">

<div class="column" style="float:left; width: 50%">

<font size="4">Percentage Change of <font color="#A2DBD5">Retail Floor Area</font>, 2009 & 2017</font></p>

<style>
  .p_iframe iframe {
    width:80%;
    height:500px;
}
</style>

<div class="p_iframe">
    <iframe frameborder="0" seamless='seamless' scrolling=no src="map/map3_retailarea_change.html"></iframe>
</div>

</div>

<div class="column" style="float:right; width: 50%">

<font size="4">Percentage Change of Median <font color="#A2DBD5">Property Value</font>, 2009 & 2017</font></p>

<style>
  .p_iframe iframe {
    width:80%;
    height:500px;
}
</style>

<div class="p_iframe">
    <iframe frameborder="0" seamless='seamless' scrolling=no src="map/map4_value_change.html"></iframe>
</div>

</div>

---

### <font color="#A2DBD5">Regression Analysis </font>
##### in the Commercial Districts by census tract


---
#### <font color="#A2DBD5">Retail Area</font> Change & Retail <font color="#F9B5B2">Number</font> Change

<iframe  width="90%" height="500" name="iframe" src="chart/regression_number_area.html"></iframe>

---

#### <font color="#A2DBD5">Retail Area</font> Change & Retail <font color="#F9B5B2">Density</font> Change

<iframe  width="90%" height="500" name="iframe" src="chart/regression_density_area.html"></iframe>



---
#### Median <font color="#A2DBD5">Property Value</font> Change & Retail <font color="#F9B5B2">Number</font> Change

<iframe  width="90%" height="500" name="iframe" src="chart/regression_number_value.html"></iframe>

---

#### Median <font color="#A2DBD5">Property Value</font> Change & Retail <font color="#F9B5B2">Density</font> Change

<iframe  width="90%" height="500" name="iframe" src="chart/regression_density_value.html"></iframe>


--- 

### Findings
The declining trend of retail stores varies in different locations. In general, the decline in Manhattan and Bronx ara more evident than in the other boroughs. According to the rezoning map, from 2009-2017, the new commercial districts are mainly C4 type. It may suggest the trend of rezoning policy in the next few years.

There is no apparent linear relationship between retail change and the retail floor area change or property value change in the regression analysis. This result is probably due to the datasets are by census tract, limiting the study to a retail store level. Future research will try to zoom in to a smaller scale and consider how the different retail types perform.

---

##### DATASET

<font size="6">

- Retail Establishments by Census Tract, United States, 2003-2017. National Neighborhood Data Archive (NaNDA)

- Primary Land Use Tax Lot Output - Map (MapPLUTO), 2009 & 2017. NYC Department of City Planning (DCP)

- Financial Characteristics for Housing Units by Census Tract, 2010 & 2017. American Community Survey (ACS)

</font>

<br/>
<br/>



##### Reference
<font size="6">

1. [Neighbourhood Differences in Retail Turnover: Evidence from New York City](https://journals.sagepub.com/doi/full/10.1177/0042098016661268?casa_token=sb3ZQ7z6xL4AAAAA%3Af-ry7y2vtMxm5TPrZ2vcfeLVYrUwA52cNMo30xYTnik_kF5zJ_zFJn_qc-P3Ti-hGYgiie82it-C)

2. [Up-Zoning New York City's Mixed-Use Neighborhoods: Property-Led Economic Development and the Anatomy of a Planning Dilemma](https://journals.sagepub.com/doi/pdf/10.1177/0739456X04270125)

</font>


---

#### Selected Types of retail & codes

<font size="4">

1. 442: Furniture and home furnishing stores.
2. 443: Electronics and appliance stores.
3. 444: Building material and garden supply stores, such as hardware and paint stores.
4. 448: Clothing and accessory stores
5. 451: Sporting goods, hobby, musical instrument, and book stores, including yarn shops, toy stores, and newsstands.
6. 452210: Department stores.
7. 453910: Pet and pet food stores.
8. 453310: Used merchandise stores, such as those selling secondhand clothing, furniture, and antiques.
9. 446120: Cosmetics, beauty supply, and perfume stores.
10. 446191: Food (health) supplement stores, i.e. stores selling vitamins and nutritional supplements.
11. 812111: barber shops (men’s hair stylists).
12. 812112: beauty salons (unisex and women’s hair stylists).
13. 812113: nail salons.
14. 812191: diet and weight loss centers.
15. 812199: other personal care services, which include spas, saunas, massage parlors, tattoo parlors, and tanning stations.
16. 812310: coin-operated laundries and dry cleaners (laundromats).
17. 7225: all restaurants and eating places.
18. 722410: drinking places (alcoholic beverages), such as bars, taverns, and cocktail lounges.

</font>