| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


## Snowbound: How a Pittsburgh Winter Makes the Trip to Campus Harder for Graduate Students

# Outline
> Every graduate student in Pittsburgh knows the feeling. The bus that came every ten minutes in October is now twenty minutes late. The hill to campus is covered in ice. The car parked on the street overnight is buried by a plough. Many graduate students do not own a car, live in neighbourhoods such as Oakland, Shadyside, Squirrel Hill, and Bloomfield, and travel to campus early in the morning or late at night for teaching and lab work. For them, winter does not just make the trip uncomfortable. It makes it slower, less reliable, and sometimes unsafe.

> This project uses public transit, weather, city service, and crash data to show what happens to the three main ways graduate students get to campus (bus, car, and walking) when winter arrives. I will compare warm months with winter months on bus on-time performance for routes that serve the university area, look at 311 requests about snow, ice, and unshovelled sidewalks, and examine how crashes change on snowy and icy roads. The story will close with practical steps that graduate students, universities, and the city can take to make winter travel more dependable.

The topic is deliberately narrow: one group (graduate students), one place (the routes and neighbourhoods around the university area), one season (winter), and one question (how does winter change the trip to campus?).


> A project structure that outlines the major elements of your story.  Your Good Charts text talks about story structure in Chapter 8 - you should describe what you hope to achieve.  Make sure the outline is detailed enough that we can see how you anticipate your story unfolding.  You can incorporate your Story Arc from the in-class exercise along with your user stories and one sentence summary to make the topic even more clear. 

One-sentence summary: When winter comes to Pittsburgh, every way of getting to campus becomes less reliable at the same time, and graduate students, who depend most on buses and their own feet, feel it most.

Audience: Graduate students in Pittsburgh, especially new and international students facing their first Pittsburgh winter. A secondary audience is university graduate offices, student government, and transportation staff who make decisions about shuttles, class policies, and winter communication.

## User Stories
| As a... | I want to...  | So that I can... |
|------|-----|-------------|
|  New graduate student    |  Know how much less reliable my bus becomes in winter   |  Plan extra travel time and back-up routes           |
|  Graduate student who drives   |  See when and where snowy and icy crashes happen   | Decide when to leave the car at home            |
|  Graduate student who walks    |  See which areas generate the most snow and ice complaints   | Choose safer walking routes and report problems            |


## Story Arc
The story follows a three-act structure and is told through a "commute" frame: the reader follows one composite graduate student on a winter morning.

1. Act I: An easy commute in October (setup). The story opens with a scenario: "It is 7:40 a.m. You teach a recitation at 8:30. In October, this trip takes 20 minutes." It then shows how people in university-area neighbourhoods get to campus, by bus, on foot, or by car, with a simple map of the main bus routes into Oakland.
2. Act II: Then the snow comes (rising tension). Three short sections, one for each way of travelling:
        By bus: monthly on-time performance for university-area routes, shown against monthly snowfall.
        By car: crashes on snowy, slushy, and icy roads by month and hour of day, highlighting winter mornings.
        On foot: 311 requests about snow, ice, and sidewalks, by month and by neighbourhood.
3. Act III: Everything fails at once (climax). On the heaviest snow days, all three options become harder at the same time, so there is no easy back-up. A side-by-side comparison sets a heavy snow day against a normal day for bus reliability, crash counts, and 311 snow requests.
4. Resolution: Getting through the winter. Practical tips for students (check real-time tracking, allow extra time, report icy sidewalks to 311), ideas for universities (winter shuttles, a clear severe-weather policy, flexible attendance), and an interactive tool where readers choose their bus route and see how its reliability changes month by month.

## Initial sketches
> The sketches below follow the story arc in order. The numbers in them are placeholders that show the shape of each chart; real values will come from the datasets listed below.

Sketch 1: Title screen and hook (Act I). A full-width photo of a snowy bus stop, the title, and the 7:40 a.m. scenario that starts the commute.

Sketch 1

Sketch 2: How people near campus get there (Act I). Commuting mode for university-area census tracts, next to a simple map of bus corridors into Oakland.

Sketch 2

Sketch 3: The bus in winter (Act II). Monthly on-time percentage for university-area routes, with monthly snowfall shown as bars behind the line. A dropdown will let readers pick a route.

Sketch 3

Sketch 4: The car in winter (Act II). A heat map of crashes on snowy, slushy, or icy roads by month and hour, with the winter morning commute highlighted.

Sketch 4

Sketch 5: Walking in winter (Act II). A neighbourhood map of 311 snow and ice requests and a monthly bar chart showing when they peak.

Sketch 5

Sketch 6: The bad day and what to do (Act III and resolution). A heavy snow day compared with a normal day, followed by the route explorer and winter tips.

Sketch 6

# The data
All of my data sources are public and free to download. Most come from the Western Pennsylvania Regional Data Center (WPRDC), the regional open data portal run by the University of Pittsburgh with the City of Pittsburgh and Allegheny County. For the bus, I will use Pittsburgh Regional Transit's monthly on-time performance and monthly ridership by route, filtered to routes that serve the university area, and compare winter months (December to February) with the rest of the academic year. For driving, I will use the Allegheny County crash data, which records the date, hour, location, weather, and road surface condition (for example, snow-covered, slush, or ice) of every reported crash, and count crashes on snowy and icy roads by month and hour. For walking, I will use City of Pittsburgh 311 data to count requests about snow, ice, and sidewalks by month and neighbourhood.

To connect these to the weather, I will use NOAA daily summaries for Pittsburgh International Airport (snowfall, snow depth, and temperature) to identify snow days and monthly snowfall totals, and join them to the other datasets by month and by day. American Community Survey data from the U.S. Census Bureau will show how residents of university-area census tracts travel to work or school and confirm that these tracts have large graduate student populations. None of these datasets identify graduate students directly, so I will use the routes and neighbourhoods around the university area as a stand-in and state this clearly in the story. If my instructor approves, I may add a short anonymous survey of classmates about their winter commute to bring in graduate students' own voices. Cleaned copies of the data will be stored in the data/ folder of this repository.

> A link to the publicly-accessible datasets you plan on using, or a link to a copy of the data you've uploaded to your Github repository, Box account or other publicly-accessible location. Using a datasource that is already publicly accessible is highly encouraged.  If you anticipate using a data source other than something that would be publicly available please talk to me first. 

| Name | URL | Description |
|------|-----|-------------|
|  PRT Monthly On-Time Performance by Route    | https://data.wprdc.org/dataset/port-authority-monthly-average-on-time-performance-by-route    | Monthly on-time percentage for each bus and rail route, by weekday, Saturday, and Sunday service. Used for the bus section.            |
|  PRT Monthly Average Ridership by Route    | https://data.wprdc.org/dataset/prt-monthly-average-ridership-by-route    | Average daily riders by route and month since January 2017. Used to show how winter affects use of university-area routes.            |
|  Allegheny County Crash Data    | https://data.wprdc.org/dataset/allegheny-county-crash-data    | One record per reported crash (from PennDOT) with date, hour, location, weather, and road surface condition. Used for the car section.            |
|  Pittsburgh 311 Data    | https://data.wprdc.org/dataset/pittsburgh-311-data    | City service requests with type, date, and location, including snow, ice, and sidewalk requests. Used for the walking section.            |
|  NOAA Climate Data Online (Pittsburgh International Airport)    | https://www.ncei.noaa.gov/cdo-web/    | Daily snowfall, snow depth, and temperature. Used to identify snow days and monthly snowfall.            |
|  American Community Survey 5-year estimates    | https://data.census.gov/    | Means of transport to work and school enrolment by census tract. Used for context in Act I.            |

## Method and medium
The final story will be built in Shorthand, using a scrolling "commute" format that moves the reader through one winter morning. All charts and maps will be built in Tableau Public and embedded in the Shorthand story, including an interactive route explorer. Data will be downloaded from WPRDC, NOAA, and the Census Bureau, then cleaned and joined by month (and by day for the "bad day" comparison) in Tableau Prep or Python, with cleaned files kept in this repository. All photographs will be my own or openly licensed and credited, and I will not use university logos or transit agency branding. 

## References
_Allegheny County. (2025). Allegheny County crash data [Data set]. Western Pennsylvania Regional Data Center. https://data.wprdc.org/dataset/allegheny-county-crash-data._

_Berinato, S. (2016). Good charts: The HBR guide to making smarter, more persuasive data visualizations. Harvard Business Review Press.._

_City of Pittsburgh. (2025). Pittsburgh 311 data [Data set]. Western Pennsylvania Regional Data Center. https://data.wprdc.org/dataset/pittsburgh-311-data._

_National Oceanic and Atmospheric Administration, National Centers for Environmental Information. (n.d.). Climate data online: Daily summaries, Pittsburgh International Airport [Data set]. https://www.ncei.noaa.gov/cdo-web/._

_Pittsburgh Regional Transit. (2024). Monthly average ridership by route [Data set]. Western Pennsylvania Regional Data Center. https://data.wprdc.org/dataset/prt-monthly-average-ridership-by-route._

_Pittsburgh Regional Transit. (2024). Monthly on time performance by route [Data set]. Western Pennsylvania Regional Data Center. https://data.wprdc.org/dataset/port-authority-monthly-average-on-time-performance-by-route._

_U.S. Census Bureau. (n.d.). American Community Survey 5-year estimates [Data set]. https://data.census.gov/._

## AI acknowledgements
_Utilized AI(Claude) to refine and finalize topic idea for final project part one._
