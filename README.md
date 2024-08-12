## Background

The United Kingdom experienced one of its harshest winters in decades at the end of 2010, with temperatures dropping below -10°C (14°F) in some areas and persistent snowfalls across the country, including London. This unprecedented cold spell led to major disruptions in the London Underground network due to the accumulation of snow and ice on tracks, affecting both the trains and stations. The most severe period, with widespread closures and disruptions occured in December 13-20, 2010. Approximately 70-80 million passenger journeys were affected during the disruption. In response to the severe winter disruption, the government and Transport for London (TfL) implemented various measures to mitigate the impact and restore normal services.

While it’s challenging to predict future events, experts believe that severe winter conditions like those experienced in 2010 could occur again in the near future, with climate change contributing to weather extremes. Therefore, it is essential to evaluate the past event and measures being taken and prepare the worst case scneario and plan in the future the in order to minimize possible disruption.

## Aim and Objectives

This study aims to analyze the London Underground network's performance during Business-as-Usual (BAU) and disruption scenarios in December 2010 using the latest data (2024). The output of this study will evaluate the effectiveness of government measures during the 2010 disruption and provide actionable insights to improve resilience against future winter disruptions.

This objectives of this study:

- Develop network analysis on underground network during BAU (business-as-usual) on 2024.
- Simulate network analysis on underground network during winter disruption on 2024, using 2010 December scenario
- Evaluate past government’s measure on the 2010 December travel disruption using 2024 travel data
- Suggesting action to be taken to to alleviate congestion and minimize delays within Underground network

## Data

1. Underground station and lines in 2024
2. Underground trips in 2024

## Scenario

### 2010

#### Disrupted line and station:

**Central Line:**
- Closed from West Ruislip to Hanger Lane
- Those who terminated at the closed stations would alight at North Acton
- Those who departed from those closed station would take the nearest open station to continue their trip:
-     West Ruislip, Ruislip Garden, and South Ruislip passengers would depart from Ruislip st (Metropolitan line).
-     Northole and Greenford passengers would depart from Sudburry Hill (Piccadilly line)
-     Perivale and Hanger Lane passengers would depart from Park Royal (Piccadilly line)

**Metropolitan Line:**
    - Closed from Harrow-on-the-Hill to the Chesam Station
    - Those who terminated at the closed stations would alight at Northwick Park
    - Those who departed from those closed station would depart at Northwick Park
      
**Northern Line:**
- Closed from Finchley Central to upnorth
- Those who terminated at the closed stations would alight at East Finchley
- Those who departed from those closed station would depart at East Finchley

No clear information on disruption on the other lines, let's assume other lines worked normally.
Other assumptions includes bus worked normally and no severe traffic on the road, thus passengers can use alternative road-based transport to reach the stations.

Although in the real situation road might be busier and had severe traffic due to icy surface, this study will limit the scope of analysis only for TfL Underground network analysis. 
    
#### Government intevention:

**Victoria Line:**
Passengers intended to take/depart at Northern Line from High Barnet to Finchley Central (Northern line) were advsised to take/depart at Highbury Islington (Victoria line).
Let's assume:
- 50% passenger departed from the closed stations went to East Finchley st, and 50% went to Highbury Islington st
- 50% passenger terminated to the closed stations alight at East Finchley st, and 50% alight to Highbury Islington st

**Bakerloo Line:**
Passengers intended to take/depart at Northwick Park (Metropolitan line) were advsised to take/depart at Kenton st (Bakerloo line)
Let's assume:
- 50% passenger departed from the closed stations went to Northwick Park st, and 50% went to Kenton st
- 50% passenger terminated to the closed stations alight at Northwick Park st, and 50% alight to Kenton st

## Performance Metrices

- Average Path Length: The average distance between the origin and destination for all the trips
  
## Workflow Chart

