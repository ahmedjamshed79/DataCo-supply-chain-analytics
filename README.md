<img src="media/image1.jpeg" style="width:3.12583in;height:1.56291in"
alt="A logo of a university Description automatically generated" />

MSc Business Analytics  
School of Business and Management  
Royal Holloway, University of London

Europe’s Adoption of Sustainable Energy

CANDIDATE NUMBER:

101061173

22 March 2024

<span id="_Toc518393710" class="anchor"></span>Declaration of
Authenticity

The linked submission has been prepared on the basis of my own work and
that where other published and unpublished source materials have been
used, these have been acknowledged.

I give permission for the School of Business and Management to retain a
copy of my submission to embed into future versions of the MN5813 Moodle
page. I understand that my submission will be viewable by future module
participants.

**Signed:** \[101061173

**Date:** \[11 January 2024\]

\[The page is left intentionally blank.\]

<span id="_Toc155866135" class="anchor"></span>Jupyter notebook

<figure>
<img src="media/image2.png" style="width:3.86111in;height:3.86111in" />
<figcaption><p>1. Scan QR Code for Jupyter Notebook</p></figcaption>
</figure>

Or

Click
Here:<https://github.com/ahmedjamshed79/Europe-Adoption-of-Sustainable-Energy>

<span id="_Toc155866136" class="anchor"></span>Table of content

[Declaration of Authenticity [ii](#_Toc518393710)](#_Toc518393710)

[Jupyter notebook [iv](#_Toc155866135)](#_Toc155866135)

[Table of content [v](#_Toc155866136)](#_Toc155866136)

[Europe’s Adoption of Sustainable Energy
[vi](#_Toc155866137)](#_Toc155866137)

[1 Introduction [vi](#introduction)](#introduction)

[1.1 Problem Background [vi](#problem-background)](#problem-background)

[1.2 Aim and Objectives [vi](#aim-and-objectives)](#aim-and-objectives)

[2 Previous Work [vii](#previous-work)](#previous-work)

[3 Methodology [viii](#methodology)](#methodology)

[3.1 Data Collection [viii](#data-collection)](#data-collection)

[3.2 Tools [ix](#tools)](#tools)

[3.3 Data Pre-Processing
[ix](#data-pre-processing)](#data-pre-processing)

[3.4 Analysis and Techniques
[xi](#analysis-and-techniques)](#analysis-and-techniques)

[4 Results and Findings
[xiii](#results-and-findings)](#results-and-findings)

[5 Conclusion [xvii](#conclusion)](#conclusion)

[References [xvii](#_Toc155866149)](#_Toc155866149)

[Appendix: [xix](#_Toc155866150)](#_Toc155866150)

<span id="_Toc155866137" class="anchor"></span>Europe’s Adoption of
Sustainable Energy

# Introduction

## Problem Background

Since its inception in 2009, the European Union has implemented
strategies aimed at augmenting the proportion of Renewable Energy Share
(RES) in the EU's total energy consumption. This initiative is part of a
broader objective to diminish the EU's carbon emissions by the year 2030
(Knopf, Nahmmacher, & Schmid, 2015). Central to this strategy are the
objectives encapsulated in the widely recognized "20/20/20" targets,
which encompass three primary goals pertaining to climate change and
energy:

1.  20% reduction in CO2.

2.  20% increase in RE

3.  S

4.  20% increase in energy efficiency (European Commission, 2010).

Over the years, numerous studies have analyzed the performance of the
EU-28 member countries in relation to the benchmarks established by this
strategy. However, there exists a shortage of comprehensive analyses
focusing on the adoption rates of renewable energy within the broader
European Region.

## Aim and Objectives

A comprehensive analysis which encompasses all European nations can
provide an expanded perspective on the sustainability endeavours of the
EU-28, compared with other regions. Accordingly, the primary objective
of this research is to conduct a detailed examination and comparative
assessment of renewable energy consumption and the adoption across
various European countries. To fulfil this objective, this study is
designed to address the following research questions:

1.  What is the historical trajectory of low-carbon energy consumption
    and CO2 emissions within Europe from the year 2000 to 2020?

2.  Among the European nations, which have been the forerunners in
    adopting renewable energy, and which countries have shown
    comparatively less progress in this regard?

# Previous Work

Over the course of recent years, a multitude of scholarly inquiries have
been conducted to evaluate the extent to which the EU-28 countries have
actualized the objectives set forth in the Europe 2020 strategies. These
studies encompass a range of analyses, including the categorization and
ranking of member states in relation to the collective EU 2020 targets,
which cover a broad spectrum of areas (Fura, Wojnar, & Kasprzyk, 2017).
Several investigations have concentrated on a subset of the EU-28
members for more focused assessment (Bonsinetto & Falco, 2013). While
others have delved into the feasibility and cost-effectiveness of
attaining the objective of deriving 27% of electricity from renewable
sources (Knopf, Nahmmacher, & Schmid, 2015). Further, there exists a
discourse on the sufficiency of relying solely on renewable energy
sources without the inclusion of nuclear power plants in meeting CO2
reduction goals (Samseth, 2013).

A notably recent study by (Gontkovičová & Duľová Spišáková, 2023) has
undertaken a detailed analysis of the sustainable energy adoption rate
and performance of EU-28 countries. This study employed a multifaceted
approach to rank each member state against various indicators, data for
which were collected in 2020. Utilizing multivariate comparison
methods - including the ranking method, scoring method, and distance
method - the study discerned that Croatia and Greece were the most
successful in achieving their national targets as per the Europe 2020
Strategy, fulfilling or surpassing all monitored indicators. Other
countries displaying notable performance included Romania, Estonia, and
the Czech Republic. Conversely, Ireland, Belgium, Austria, and France
were identified as consistently underperforming, failing to meet any of
the target values in the four monitored areas.

While these studies offer a comparative analysis of all EU-28 members, a
detailed examination that incorporates other European regions has not
been as prominent. Such a comparative analysis is imperative as it could
provide a benchmark for further research into the performance of non-EU
members in terms of sustainable energy and contextualize the standing of
EU members relative to their non-EU counterparts.

# Methodology

## Data Collection

Numerous reputable institutions compile extensive datasets on global
energy consumption and production. Among these, the World Bank stands as
a prominent entity renowned for its comprehensive data collection and
storage about the global energy and mining statistics (The World Bank,
2023). Furthermore, OurWorldInData is another organization dedicated to
offering data-driven insights into various global challenges, including
climate change (Max Roser, n.d.). Their extensive dataset on energy
consumption draws from a multitude of sources from across the globe, all
of which are meticulously documented in their GitHub repository (owid,
n.d.)

For the specific purposes of this research, however, the dataset
utilized was obtained from Kaggle (ANSH TANWAR, 2023). The decision to
utilize Kaggle as the data source was motivated by its blend of
information from three distinct sources, namely, The World Bank, the
International Energy Agency, and OurWorldInData.org. This dataset
encompasses all the requisite key variables essential for the successful
accomplishment of the research objectives. These variables include:

1.  Year (YYYY)

2.  Country

3.  Renewable energy share in total energy consumption \[%\]

4.  Low-carbon electricity sources (nuclear and renewables) \[%\]

5.  Value CO2 emissions \[Metric tons per person\].

## Tools

For the analytical component of this study, Python was selected as the
primary computational tool. Python, because of it’s robust ecosystem of
libraries and tools tailored for data analysis and scientific computing.
Two key Python libraries, Pandas and NumPy, were employed for data
manipulation and cleansing. Pandas is acclaimed for its powerful data
structures that facilitate efficient data manipulation and analysis,
whereas NumPy specializes in numerical operations on large
multi-dimensional arrays and matrices.

In addition, the study utilized Matplotlib and Seaborn for data
visualization purposes. Matplotlib stands as a foundational and highly
adaptable 2D plotting library in the Python landscape. On the other
hand, Seaborn, a statistical data visualization library that builds upon
Matplotlib, was chosen primarily for creating aesthetically pleasing
graphs. Furthermore, seaborn is particularly valued for its built-in
statistical functions, such as the ability to compute confidence
intervals and plot regression lines, making it a fitting choice for this
study.

Moreover, the Scipy.stats library, an open-source Python library widely
recognized for scientific and technical computing, was utilized for
conducting statistical analyses.

## Data Pre-Processing

The initial step involved filtering the dataset to focus solely on
European countries. This refined dataset encompassed two decades of data
spanning across 39 European countries. Subsequently, a careful
examination revealed the absence of data for eight countries, namely,
Vatican City, San Marino, Russia, Monaco, Moldova, Liechtenstein, Czech
Republic, and Andorra. Additionally, countries for which limited data
was available were also excluded namely Turkey, Albania and Slovakia. To
enhance data quality and reliability, a thorough assessment of null
values within the dataset was conducted. Variables exhibiting null
values constituting 50% or more of their data points were excluded.
Subsequently, the essential variables of interest were extracted for
further analysis.

A visual representation of null value occurrences within these essential
variables was generated via a heatmap, as depicted in Figure 2. In this
graphical representation, null values are denoted by yellow boxes. It is
discernible from the heatmap that the dataset demonstrates a high degree
of cleanliness, with only minor instances of null values for most
variables. Additionally, to ensure data integrity, a comprehensive
analysis of data distribution for each essential variable was performed
utilizing statistical measures such as mean and standard deviation, as
illustrated in Figure 3. This step further reinforces the credibility
and reliability of the dataset.

Since this dataset spans over 20 years, it was identified that the
occurrences of 0.00 as the minimum value for some variables was due to
the fact that some countries didn’t have renewable energy sources in the
previous years.

<figure>
<img src="media/image3.png" style="width:6.43522in;height:3.0031in" />
<figcaption><blockquote>
<p>Figure 2: Heatmap Visualization of Null Values</p>
</blockquote></figcaption>
</figure>

<figure>
<img src="media/image4.png" style="width:6.29583in;height:1.79028in"
alt="A table with numbers and text Description automatically generated" />
<figcaption><p>Figure 3: Summary table with statistical
measures</p></figcaption>
</figure>

## Analysis and Techniques

In this research, the dataset encompassed a longitudinal span of 20
years for each country under examination. This temporal range implies
that for each variable *X<sub>i,</sub>* there existed a corresponding
time-series data comprising 20 time periods, denoted as *T<sub>1</sub>,
T<sub>2</sub>,…… ,T<sub>20</sub>.* To facilitate a coherent analysis, a
two-step data processing method was employed.

Initially, each variable *X<sub>i</sub>*​ was aggregated based on the
time period *T*. This involved computing the mean value of
*X<sub>i</sub>*​ for each discrete time period *T<sub>i</sub>* resulting
in a consolidated mean value of *X<sub>i</sub>* for each corresponding
*T<sub>i</sub>*. This step was crucial for reducing the granularity of
the data and ensuring that the analysis could meaningfully interpret
trends over time.

Subsequently, the mean values of each variable *X<sub>i</sub>* were
organized chronologically according to *T*. This ordering facilitated
the creation of a continuous time series dataset, thereby enabling a
more nuanced and interpretable analysis of temporal trends. The
resultant time series data were then utilized to generate line graphs
for each variable, providing a visual representation of the variable's
evolution over the specified 20-year period. This approach not only
enhanced the clarity and interpretability of the temporal data but also
aligned with established methodologies in longitudinal data analysis,
allowing for a comprehensive understanding of trends and patterns over
the two-decade span.

The methodology for ranking and classification of countries was adopted
from Gontkovičová and Duľová Spišáková (2023). The method entailed an
evaluation of each country based on two distinct variables. The first
variable, representing the percentage of RES, was designated as a
stimulator, indicative of positive sustainability efforts. In contrast,
the second variable, Net CO2 emission, was labelled as a destimulator,
reflecting adverse environmental impact.

Given the scope of analysis extending to the entire European region, it
was determined that benchmarking these countries against the Europe 2020
objectives would not be practicable. Nevertheless, a comparative
assessment based on the mean value of variable *X<sub>i</sub>* for the
year 2019 was posited as a viable alternative to gauge the overall
sustainability standing of the region. To elaborate, for each variable
*X<sub>i</sub>*, the mean value was calculated to establish a baseline.
Following this, the standard deviation from the mean, known as the
z-score, was computed for each variable *X<sub>i</sub>*​ relative to each
country. For stimulatory variables, the z-score was denoted as
*Z<sub>s</sub>*​, whereas for destimulatory variables, it was indicated
as *Z<sub>d</sub>*​. The z-score metric is pivotal as it normalizes the
data, enabling cross-country comparisons irrespective of the absolute
values of the variables.

A higher *Z<sub>s</sub>*​ score suggests a commendable performance in
RES, earning a superior ranking. Conversely, a higher *Z<sub>d</sub>*​
score suggests greater environmental detriment, resulting in a
diminished ranking. The final ranking for each country was ascertained
by the differential *Z<sub>s</sub>*​−*Z<sub>d</sub>*, with a higher
resultant value indicating a more favourable sustainability ranking. And
lastly, the final ranking was divided into quartiles (4 equal parts) to
categorize countries into High, Medium high, Medium low, Low adoption.

This methodology underscores the multifaceted approach to sustainability
assessment, taking into account both the promotion of clean energy and
the reduction of carbon emissions. It allows for a nuanced analysis that
captures the complexity of environmental performance across the European
landscape.

# Results and Findings

The graph, illustrating RES and low-carbon electricity (renewables,
nuclear) production, indicates a steady rise in both areas. Notably, the
growth in low-carbon production reflects significant nuclear capacity in
several countries. Nonetheless, the EU 2020 strategy prioritizes
exclusively renewable energy sources (RES), eschewing nuclear options.
Given nuclear energy's high investment costs and risks (Samseth, 2013)
this analysis henceforth concentrates on RES.

<figure>
<img src="media/image5.png" style="width:6.29583in;height:3.14792in" />
<figcaption><p>Figure 4: Combined Time-Series Graph</p></figcaption>
</figure>

Europe's RES growth from 15% to 23% ostensibly signifies the EU 2020
strategy's success. However, this includes non-EU nations' independent
sustainability efforts, suggesting a need for comparative analysis for
accurate evaluation. Additionally, Figure 5's depiction of Europe's
substantial CO2 emission reduction necessitates a nuanced
interpretation, considering the multifaceted determinants of CO2
emission trends. Consequently, a multivariate analysis encompassing both
RES and CO2 emissions can elucidate leading nations in sustainability.

<figure>
<img src="media/image6.png" style="width:6.29583in;height:3.14792in"
alt="A graph showing the growth of the co2 emission Description automatically generated" />
<figcaption><p>Figure 5: CO2 Emissions Trend</p></figcaption>
</figure>

Figure 6 reveals the Scandinavian region as a leading adopter of
sustainable energy, with a notable 81.7% RES in Iceland, surpassing
Norway by 19%. This positions Iceland among Europe's most sustainable
countries. However, this study's limitation lies in excluding several
European regions due to data scarcity. Gontkovičová and Duľová Spišáková
(2023) note that while countries like the United Kingdom (EU member in
2019), France, and Germany met their RES targets, they rank low in this
study. A critical omission here is the lack of population data, a
potential key factor in higher CO2 emissions.

<figure>
<img src="media/image7.png" style="width:6.20342in;height:9.30514in"
alt="A graph of different colored bars Description automatically generated" />
<figcaption><p>Figure 6: Ranking and Classification</p></figcaption>
</figure>

# Conclusion

This study shows a high demand for sustainability in the future.
Managers in both public and private sectors should integrate
sustainability into their strategic planning. This includes investing in
renewable energy, sustainable practices, and technologies that reduce
carbon footprints. Furthermore, the benchmarks set by this study can
guide managers, especially in public sectors, to develop sustainability
focused policies.

As discussed, the limitations of the research paper include the
exclusion of several European regions due to data scarcity and the
omission of population data, which is a potential key factor in higher
CO2 emissions. Therefore, future studies can be expanded by sourcing
data from these excluded regions. Moreover, including variables like
population density and total power consumption can give a more
comprehensive analysis.

<span id="_Toc155866149" class="anchor"></span>References

ANSH TANWAR. (2023). *Global Data on Sustainable Energy (2000-2020)*.
https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy

Max Roser. (n.d.). *About OurWorldInData*. Retrieved January 8, 2024,
from https://ourworldindata.org/about

owid. (n.d.). *energy-data*. Retrieved January 8, 2024, from
https://github.com/owid/energy-data

Samseth, J. (2013). Will the introduction of renewable energy in Europe
lead to CO2 reduction without nuclear energy? *Environmental
Development*, *6*(1), 130–132.

The World Bank. (2023). *Energy and Mining*.
https://data.worldbank.org/topic/energy-and-mining

 

Bonsinetto, F., & Falco, E. (2013). Analysing italian regional patterns
in green economy and climate change. can italy leverage on europe 2020
strategy to face sustainable growth challenges? *Journal of Urban and
Regional Analysis, 5*(2), 123-142. doi:10.37043/JURA.2013.5.2.2

European Commission. (2010). *EUROPE 2020. A strategy for smart,
sustainable and inclusive growth.*

Fura, B., Wojnar, J., & Kasprzyk, B. (2017). Ranking and classification
of EU countries regarding their levels of implementation of the europe
2020 strategy. *Journal of Cleaner Production, 165*, 968-979.
doi:10.1016/j.jclepro.2017.07.088

Gontkovičová, B., & Duľová Spišáková, E. (2023). Climate and energy
targets under europe 2020 strategy and their fulfillment by member
states. *Frontiers in Environmental Science, 11*
doi:10.3389/fenvs.2023.1264770

Knopf, B., Nahmmacher, P., & Schmid, E. (2015). The european renewable
energy target for 2030 – an impact assessment of the electricity sector.
*Energy Policy, 85*, 50-60. doi:10.1016/j.enpol.2015.05.010

<span id="_Toc155866150" class="anchor"></span>Appendix:

**Data:**

<img src="media/image8.png" style="width:6.29583in;height:1.38194in"
alt="A table with numbers and symbols Description automatically generated" />

**Statistical Measures**

<img src="media/image9.png" style="width:6.19444in;height:3.41667in"
alt="A screenshot of a computer Description automatically generated" />

**Top 10 Countries which consumes high energy per capita:**

<img src="media/image10.png" style="width:6.29583in;height:4.19722in"
alt="A graph of different colored bars Description automatically generated" />

**Regression analysis**

<img src="media/image11.png" style="width:6.29583in;height:4.19722in"
alt="A graph with a red line Description automatically generated" />
