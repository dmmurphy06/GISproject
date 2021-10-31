# <hl> UP 206A Midterm
  Member Name: Demetria Murphy
# <hl> Research Question
  In this assignment, I will be analyzing location data from the Green Book, a Jim-crow era Black travel guide created by former postal worker Victor Green.  The guide ran from 1936 - 1966 and 21 guides were recently digitized and open source data was released by the Schomburg Center for Research in Black Culture at the New York Public Library. 

* *What was the Black urban ecology of safety in post-WWII Los Angeles?* Through analyzing Green Book location data from 1947 and 1956, before and after the outlaw of racially restrictive covenants, in Los Angeles, I seek to reveal a local landscape of safety and interrogate how shifts in discriminatory policies governing private and public space may have impacted this temporal network. 

* *What was the impact of shifts in neighborhood socioeconomic demographics on this ecology of safety?* I'd like to compare this with race and economic indicators such as blue or white collar work, leve of education, home values and rents by Census tract adjacent to these years to better understand both shifts and the spatial composition in these landscapes of safety amidst complex urban neighborhood changes.
 # <hl> Why This Matters and What's at Stake
  The data dive was inspired by Ethan Bottone's critical GIS analysis of New Orleans in "'Please Mention the Green Book:' The *Negro Motorist* Green Book as Critical GIS." Using the *Green Book* as a critical mapping tool, we can learn more about both the spatial geography of Jim Crow America and the landscapes of safety therein. While vehicles themselves had a "twin symbolism of mobility and freedom," (Piercy 2) this era of black mobility and the Great Migration offer a glimpse of what Harriet Jacobs calls a "loophole of retreat," a strategic site where one can safely surveil and be shielded from the world's dangers while offering power to shift one's fate. While the effectiveness of this network is hard to singularly quantify, one could view the Great Migration’s relocation of over 6 million Blacks from the rural South to the urban North, Midwest, and West and the subsequent economic and political benefits as a measure of its efficacy. Further, centering black epistemology in this project can empower Black self-determination and further what Katherine McKittrick calls "black geographies," preventing further enclosure, dispossession, and displacement. 
 # <hl> Spatial Scope
  The spatial scope is limited to the city of Los Angeles given that I’m interested in understanding neighborhood change and black geographies in this city more deeply.    
 # <hl> Data Sources
* [Green Book locations by type for SoCal, 1947](https://github.com/NYPL-publicdomain/greenbook-map/tree/master/data) (Schomburg Center for Research in Black Culture at the New York Public Library)
* [Green Book locations by type for SoCal, 1956](https://github.com/NYPL-publicdomain/greenbook-map/tree/master/data) (Schomburg Center for Research in Black Culture at the New York Public Library)
* [Los Angeles County Union Census Tract Data Series, 1940-1990](https://drive.google.com/drive/folders/1KiflC3DOQJoo_DTiZGzbr3-_QhvTh1nl?usp=sharing) from Ethington, Kooistra, and DeYoung (add official citation here) (*Note:I will consult 1950 as an informative datapoint, but this project is focused on the change explicitly before and after racially restrictive covenants were struck down in the 1948 Shelley v. Kramer decision.*)
    * From this dataset, I am interested in the following variables and years that will help me better understand the **racial demographics** of the area in both 1940 and 1960 (where yy = year):
        * **PyyB:** Population Black non-White
            * **PyyT** used to calculate percentage of Black non-white population.
    * Median household income data is not available until 1970 in this dataset, so I will explore  a few of the following variables to better understand the surrounding **socioeconomic context** in both 1940 and 1960 (where yy = year)::
        * **EyyH:**	Education completed high school 
        * **EyyC:**	Education completed college 
        * **OyyWC:**	Occupation White Collar
        * **OyyBC:**	Occupation Blue Collar
        * **HyyMVL:**	Median value of dwelling/housing units
        * **HyyMRN:**	Housing Median Rent of Unit
 # <hl> Intended Analysis and Resulting Visualizations
*What was the Black urban ecology of safety in post-WWII Los Angeles? What was the impact of shifts in neighborhood racial demographics on this ecology of safety?*
I seek to reveal a local landscape of safety and interrogate how shifts in discriminatory policies governing private and public space may have impacted this temporal network. I will first analyze Green book locations in both 1947 Los Angeles, a year prior to the outlaw of racially restrictive covenants, and the neighborhood racial demographics in which they are embedded and 1956, almost a decade after WWII. 
  * Visualizations: Green Book Location Types, 1947 x Race by Census tract; Green Book Locations Types, 1956 x Race by Census tract (How did location types shift?)

Further, are there spatial relationships between the HOLC ratings that were part in parcel to discriminatory red-lining policies and the GreenBook safety ecology?
    * Visualization: Green Book Location Types, 1947 x Race by Census tract x HOLC Ratings; Green Book Location Types, 1956 x Race by Census tract x HOLC Ratings

Then, I will compare the change in both Green Book locations and neighborhood socioeconomic demographics to characterize and hypothesize what this means for an ecology of safety and Black belonging in urban space. Specifically, what spatial relationships are there between Green Book location types and type of collar work? education levels? For example, was housing in predominantly Black tracts more expensive than in other areas, holding the education or job status constant?
  * Visualization: Green Book Locations from 1956 x Race by Census tract, 1960 x Economic indicator (ex. Collar Work, Education Level, Home Value/Rent)
    
  # <hl> Conclusion
What implications are there for federal investments to a so-called infrastructure of care? This nascent investigation is limited in both its ability to account for the influence of Black interior spatial practices on safety and how tourist travel and permanent relocation together account for increased black mobility. However, what can we learn from these temporal, organic networks of safety and the shifting urban contexts around them that can inform current discourse on the infrastructure of care? In particular, the care crisis hit a breaking point during the Covid-19 pandemic with disproportionate amounts of BIPOC women leaving the workforce at the end of 2020 due to increased care responsibilities. Insufficient care infrastructure constrains women’s long term earning potential and the US economy through lost productivity, wages, and benefits further hampering BIPOC women’s social mobility. The combination fo this dynamic with generational barriers to economic mobility, Black women have felt the brunt of this burden. What can be learned from this Black urban ecology of safety in a system predisposed to reproducing modes of gender inequity and racial capitalism? Lessons learned may be instructive to the $425 billion in federal care infrastructure investments within the American Families and Jobs Plans. 