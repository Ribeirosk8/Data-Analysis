
---
_Let's start by loading a dataset to work with. We can use the palmer penguins dataset, which contains size measurements for three penguin species that live on the Palmer Archipelago in Antarctica. This includes data on stuff like body mass, flipper length and bill length. The dataset has 344 rows of information sorted into eight columns. The palmer penguins data is popular with analysts and is great for fun exploration, visualization and teaching concepts_.

## 🐧Introduction to R script and example modified palmer penguins dataset

---


<iframe title="Relationship between bill length and depth " aria-label="Interactive area chart" id="datawrapper-chart-6QyX1" src="https://datawrapper.dwcdn.net/6QyX1/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="431" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();
</script>

Contains
Bill dimensions
The culmen is the upper ridge of a bird’s bill. In the simplified penguins data, culmen length and depth are renamed as variables bill_length_mm and bill_depth_mm to be more intuitive.

For this penguin data, the culmen (bill) length and depth are measured as shown below :
![culmen_depth](https://github.com/Ribeirosk8/Data-Analysis/blob/main/culmen_depth.png)



penguins_bill_length.csv - Modified palmer penguins dataset

Meet Penguin species: 
Chinstrap | Gentoo | Adelie 
![Penguin species](https://github.com/Ribeirosk8/Data-Analysis-with-R-Programming/blob/main/lter_penguins.png)

bill_length_mm: Penguin bill length in millimeters
bill_mass_mm: Penguin body mass in grams
Log_bill_length: Log transformed bill_length_mm
