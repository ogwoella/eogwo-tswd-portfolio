| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

## Wireframes / storyboards

In Part I, I sketched the story by hand. This week I turned those sketches into an eight-part storyboard, downloaded the real data, built high-fidelity versions of the charts that carry the story, and started building the story directly in Shorthand (linked above). I also acted on the Part I feedback: I removed the leftover template text, made the ending a concrete winter commute plan with real university and city resources, and planned the photographs the story needs.

<img width="1760" height="2090" alt="storyboard" src="https://github.com/user-attachments/assets/b2d7a395-d1d8-47be-9af5-a1160618eabe" />


| # | Section | Story role | What the reader sees | Interaction |
|---|---|---|---|---|
| 1 | Title | Act I: setup | Full-width photo of a snowy bus stop and the title | Title fades as the reader scrolls |
| 2 | The 7:40 a.m. hook | Act I: setup | "It is 7:40 a.m. You teach a recitation at 8:30. In October, this trip takes 20 minutes." | Text over a blurred October street photo |
| 3 | How people get to campus | Act I: setup | Commute mode bar chart and map of bus corridors into Oakland | One corridor highlighted at a time as the reader scrolls |
| 4 | By bus | Act II: rising tension | Snowfall above bus on-time performance; campus routes trail the system all year, and winter is not their worst season | Tableau embed with a route dropdown |
| 5 | By car | Act II: rising tension | Heat map of snowy and icy road crashes by month and hour | Boxes draw in around the morning and evening commutes |
| 6 | On foot | Act II: rising tension | 311 snow and ice requests by month, then the 10 busiest storm days | Hover to see the most common request types |
| 7 | The real winter problem | Act III: climax | October compared with January: roads and sidewalks get much worse, the bus holds steady | Numbers count up on scroll |
| 8 | Your winter commute plan | Resolution and call to action | A five-step routine from the night before to after the storm, with a resource and a data fact for each step | Each step links to its resource |


### The draft in Shorthand

The [Shorthand draft](https://preview.shorthand.com/kEjiryIDjh0gdavK/responsive/desktop) turns the storyboard into a scrolling story in a deep winter-blue theme. It follows the storyboard in order:

| Storyboard part | What the reader sees in the Shorthand draft |
|---|---|
| 1. Title | Full-screen winter photo with the title "Snowbound: Winter on the Way to Campus" and the subtitle "How a Pittsburgh winter changes the commute for graduate students" |
| 2. The 7:40 a.m. hook | "You have a recitation at 8:30. In October, the trip from Squirrel Hill to Oakland takes about 20 minutes…", then two photos that slide past as the reader scrolls, ending on "Then the first real snow arrives." |
| 3–4. By bus | A snowy bus photo, the bus text (57% on time in October, 63% in January, about seven points below the system all year), the bus chart, and a second photo slide |
| 5. By car | Full-screen winter road photos behind three big-number cards: "By car" (about 0 crashes on snowy or icy roads in October, about 136 in January), "7 to 9 a.m." (the morning commute cluster), and "6 p.m." (the single worst hour) |
| 6. On foot | Sidewalk photos, the 311 text (about 64 requests in October, about 1,220 in January), a pull quote ("Winter is one of the hardest times to get around Pittsburgh"), the 311 monthly chart, and the storm-days chart |
| 7. The real winter problem | October compared with January in text and in the comparison chart, with the pull quote "The wait is no worse in winter. The walk and the drive are." |
| 8. Your winter commute plan | A bridge ("So what can a graduate student actually do?"), the five steps, the plan graphic, a gallery of winter commute photos, and data credits |

While building it, I found that the template's built-in chart sections are only available on Shorthand's Business and Enterprise plans, so on my plan they would publish as placeholders. I removed them and placed my charts in the story as images; in Part III I will try replacing them with interactive Tableau Public embeds. The photos in the draft are openly licensed images from Unsplash and Pexels, credited in the story and in the References below.

### Draft data visualizations

These charts use the real data, downloaded from the Western Pennsylvania Regional Data Center and NOAA for the winters of 2021–22 to 2024–25. They will be rebuilt in Tableau Public for the final Shorthand story.

**1. By bus: winter is not the worst season for campus buses.**

<img width="1650" height="990" alt="chart1_bus_winter" src="https://github.com/user-attachments/assets/7be68146-dd91-4672-aac5-6abf4a65f29e" />


The real data surprised me. Campus-area buses were on time about 57% of the time in October and about 63% in January, so winter is not their worst season; September and October are. Campus-area routes also trail the system average all year, by about seven percentage points. Monthly averages may hide what happens on individual storm days, and the winter break may reduce crowding in December and January; I plan to check ridership to test this.

*Changes from Part I:* the sketch used a second y-axis for snowfall, which can suggest a link the reader cannot check, so I split it into two panels that share the month axis. I also rewrote the headline so it says what the data shows.

**2. By car: snowy and icy road crashes cluster at commute times in mid-winter.**

<img width="1650" height="990" alt="chart2_crashes_heatmap" src="https://github.com/user-attachments/assets/2c715fde-640c-4cb9-8604-324e57d19ba7" />

</br>
</br>

<img width="1650" height="990" alt="chart2b_crashes_heatmap_nobox" src="https://github.com/user-attachments/assets/8b6e4ac8-9d3a-434b-b179-63b582aa82d1" />


Crashes on snowy or icy roads rise from almost none in a typical October to about 136 in January. They cluster around the morning commute in January and February, and the single busiest hour is 6 p.m. in January.

**3. On foot: requests about snow, ice, and sidewalks jump once winter arrives.**

<img width="1650" height="990" alt="chart3_311_monthly" src="https://github.com/user-attachments/assets/931f1ace-df59-4c37-a244-a966e27b0e38" />


Requests rise from about 64 in a typical October to about 1,220 in January, far more than in December (about 170) or February (about 280).

**4. On foot: the busiest complaint days came in a run of January 2022 storms.**

<img width="1650" height="990" alt="chart5_311_storm_days" src="https://github.com/user-attachments/assets/f597605c-0bbe-4a07-ad4a-19ce78673cff" />


Eight of the ten busiest days fell in January and early February 2022, and four came from a single storm between 17 and 20 January, when the busiest day saw 579 requests. This brings back the "bad day" idea from Part I, using the one dataset that records exact dates. No days from the 2022–23 or 2023–24 winters appear, so I will check whether those winters were milder or whether the 311 data has a gap.

**5. The real winter problem: in January, roads and sidewalks get much worse, but the buses do not.**

<img width="1650" height="780" alt="chart4_october_vs_winter" src="https://github.com/user-attachments/assets/cc769f14-31ec-4e24-84e5-f685dc6a0db2" />


*Change from Part I:* I planned to show that "everything fails at once." The real data does not support that for the bus, so the climax now contrasts the roads and sidewalks with the bus.

**6. Call to action: your winter commute plan.**

<img width="1680" height="1890" alt="chart6_winter_commute_plan" src="https://github.com/user-attachments/assets/6d5829e2-0218-4e5e-9788-0daf3ec15bf1" />


Part I feedback asked for a stronger call to action, such as a planning tool or routine, university resources, and surprising suggestions. The story now ends with a five-step routine. Each step pairs a practical action and a real resource with the data fact behind it:

| Step | What to do | Resource | Why (from the data) |
|---|---|---|---|
| 1. The night before | Check the forecast and plan a bus or shuttle route; sign up for campus emergency alerts | CMU-Alert (CMU); your university's emergency alerts | Snowy-road crashes rise from about 0 in October to about 136 in January |
| 2. Before you leave | Check your bus in real time so you wait indoors; on heavy-snow mornings, take the bus or a shuttle instead of driving | PRT TrueTime | Campus buses are no less punctual in January (63%) than in October (57%) |
| 3. On the way | Use either school's shuttles with your ID; travel before 7 or after 9 a.m. if you can | Pitt and CMU shuttles (TransLoc and Ride Systems apps) | Icy-road crashes cluster from 7 to 9 a.m. in January and February |
| 4. Getting home late | Use the late-night services instead of walking or driving on icy streets | Pitt SafeRider; CMU NightSafe Transit | The worst crash hour is 6 p.m. in January |
| 5. After the storm | If a sidewalk is still not cleared 24 hours after the snow stops, report it | City of Pittsburgh 311 | One storm produced four of the ten busiest 311 days |

**Surprising suggestions the data supports:** on the snowiest days, the bus may be the safer choice than the car; shifting a trip outside the 7 to 9 a.m. window avoids the worst hours for icy-road crashes; and a 311 report helps the city see which streets and sidewalks need attention.

### Imagery

Part I feedback noted that imagery could do a lot for this story. The draft now uses winter photographs throughout: a snowy title image, sliding photos in the hook and bus sections, full-screen winter road photos behind the crash cards, sidewalk photos in the walking section, and a photo gallery at the end. For the draft I used openly licensed photos from Unsplash and Pexels. 

## User research

### Target audience

My story is for **graduate students in Pittsburgh who travel to campus in the university area**, especially students who do not drive and students facing their first or second Pittsburgh winter, including international students. A secondary audience is university staff who make decisions about shuttles, attendance policies, and winter communication.

To find representative interviewees, I looked for three graduate students who differ in **how they get to campus** (bus, walking, or driving) and in **how many Pittsburgh winters they have lived through**. I invited classmates and other graduate students and asked one screening question first: "How do you usually get to campus in the winter, and is this your first Pittsburgh winter?" Each interview took about 20 minutes. I did not record names or other identifying details, so participants are described only by how they commute and how long they have lived in Pittsburgh.

### Interview script

I opened each interview by explaining that I was testing the design, not the participant, that there were no wrong answers, and that I would not record their name. I then showed the storyboard one frame at a time, and showed each chart for about ten seconds before hiding it.

| Goal | Questions to Ask |
|---|---|
| Understand the participant's real winter commute | 1. How do you usually get to campus? Does that change in winter? <br> 2. Tell me about a winter morning when getting to campus was hard. What happened? |
| Check whether the "commute" framing feels true | 3. As you look at this storyboard, what do you think the story is about? <br> 4. Does the 7:40 a.m. opening feel like your own experience? Why or why not? |
| Test whether each chart's main message is clear within about ten seconds | 5. What was the main point of that chart? <br> 6. Was anything confusing or hard to read? |
| Test the surprising bus finding | 7. Does it surprise you that campus buses are not worse in winter? Does that match your experience? |
| Test whether the call to action is useful | 8. Which steps in the winter commute plan would you actually use? <br> 9. Which of these resources (TrueTime, the shuttles, SafeRider or NightSafe, 311) did you already know about? |
| Find what to keep, cut, or add | 10. Which section was most useful to you, and which could I cut? <br> 11. Is there anything about your winter commute that this story does not show? |

### Interview findings

| Questions | Interview 1 ([e.g., bus rider, first Pittsburgh winter]) | Interview 2 ([e.g., walks, third winter]) | Interview 3 ([e.g., drives, second winter]) |
|---|---|---|---|
| Q1–2: Winter commute experience | Takes the 61A/B from Squirrel Hill. During a January ice storm, two consecutive buses passed by full, leaving them waiting 35 minutes in sleet and missing the first 15 minutes of a morning seminar. | Walks 20 minutes from North Oakland. Rarely changes mode in winter, except during heavy slush when unshoveled brick sidewalks and steep hills make walking feel hazardous. | Drives from Shadyside and parks in a campus garage. One snowy morning, black ice on Fifth Avenue caused a fender-bender ahead, turning a 12-minute drive into 45 minutes. |
| Q3: What is the story about? | "How winter weather disrupts getting to campus and which transit options actually hold up." | "Comparing different ways students commute in winter and debunking myths about transit delays." | Why morning commutes feel chaotic in winter and how students can plan around bad weather. |
| Q4: Does the 7:40 a.m. opening ring true? | Yes, for 8:00 or 8:30 a.m. labs/classes, leaving around 7:40 a.m. in the dark and cold matches their exact routine| Partially—their classes start at 10:00 a.m., so 7:40 a.m. is early, though they recognized the rush-hour stress. | Yes, that is the exact window when traffic backs up near campus intersections and garages fill up. |
| Q5–6: Chart messages and confusion |  Understood | Some graphs were unclear.  |  Understood |



**Key quotes**
- Interview 1: "The winter commute is hard!"
- Interview 2: "The main roads get plowed first, so for people walking, it's the unshoveled side streets and icy hills is the hardest part."
- Interview 3: "I always assumed the buses were falling apart in snowstorms, so seeing that they're consistent actually makes me consider leaving my car on bad days."


## Identified changes for Part III

Some changes came from Part I feedback and from building the charts with real data. 

| Research synthesis | Anticipated changes for Part III |
|---|---|
| Part I feedback: leftover assignment prompt text made the pages look unfinished. | Done: removed all prompt boxes from Parts I and II. |
| Part I feedback: the call to action should be stronger, with a planning tool or routine, university resources, and surprising suggestions. | Done: added a five-step winter commute plan with Pitt, CMU, PRT, and City of Pittsburgh resources. Next: link each step to its resource in Shorthand. |
| Part I feedback: imagery could add a lot to the story. | Done: added winter photos throughout the Shorthand draft (Unsplash and Pexels). Next: replace some with my own Pittsburgh photos. |
| The crash heat map is not yet in the Shorthand draft; the "By car" section uses photos and big-number cards only (building the draft). | Add the heat map under the "By car" cards so readers can see the morning and evening clusters. |
| A second y-axis on the bus chart could imply a link the reader cannot check (design review). | Done: split into two stacked panels that share the month axis. |
| Bus and crash data cannot be compared day by day (data review). | Done: compare a typical October with January, and add a daily view of the busiest 311 storm days. |
| The real data shows campus buses are not less reliable in winter; they trail the system all year (data analysis). | Done: revised the bus headline, the climax, and the one-sentence story. Next: check ridership and storm-day bus performance. |
| Shorthand's built-in chart sections require a Business or Enterprise plan, so the template's charts would publish as placeholders (building the draft). | Done: removed the locked chart sections and placed my charts as images.  |
| No 311 storm days from the 2022–23 or 2023–24 winters appear in the top ten (data analysis). | Check the daily 311 counts for gaps; if the data is incomplete, average January over complete winters only. |



## References

Pexels. (n.d.). *Free stock photos* [Photographs used under the Pexels license]. https://www.pexels.com/

Unsplash. (n.d.). *Free images* [Photographs used under the Unsplash license]. https://unsplash.com/

Berinato, S. (2016). *Good charts: The HBR guide to making smarter, more persuasive data visualizations*. Harvard Business Review Press.

Allegheny County. (2025). *Allegheny County crash data* [Data set]. Western Pennsylvania Regional Data Center. https://data.wprdc.org/dataset/allegheny-county-crash-data

Carnegie Mellon University. (2025, August 15). *New name for evening shuttle service: NightSafe Transit*. https://www.cmu.edu/transportation/news/2025/nightsafe-transit.html

Carnegie Mellon University. (n.d.). *Safety resources for graduate students*. https://www.cmu.edu/graduate/current-grad-students/safety-resources/index.html

City of Pittsburgh. (2025). *Pittsburgh 311 data* [Data set]. Western Pennsylvania Regional Data Center. https://data.wprdc.org/dataset/pittsburgh-311-data

City of Pittsburgh. (n.d.). *How long do I have to clear my sidewalk following a snow event?* 311 Knowledge Base. https://pittsburghpa.qscend.com/311/knowledgebase/article/773

City of Pittsburgh. (n.d.). *Snow and ice*. https://pittsburghpa.gov/Resident-Services/Snow-Removal/Snow-Ice

National Oceanic and Atmospheric Administration, National Centers for Environmental Information. (n.d.). *Climate data online: Daily summaries, Pittsburgh International Airport* [Data set]. https://www.ncei.noaa.gov/cdo-web/

Pittsburgh Regional Transit. (2024). *Monthly on time performance by route* [Data set]. Western Pennsylvania Regional Data Center. https://data.wprdc.org/dataset/port-authority-monthly-average-on-time-performance-by-route

Pittsburgh Regional Transit. (n.d.). *TrueTime*. https://truetime.rideprt.org/bustime/home.jsp

University of Pittsburgh, Pitt Mobility. (n.d.). *SafeRider*. https://www.pc.pitt.edu/mobility/shuttle-services/saferider

University of Pittsburgh, Pitt Mobility. (n.d.). *Shuttle services*. https://www.pc.pitt.edu/shuttle-services

## AI acknowledgements

I used Claude (Anthropic) as an assistant for Part II. I ran the data download and chart script myself in Google Colab. Claude helped me to:
- turn my Part I outline and sketches into the eight-section storyboard and draw the storyboard image;
- write a Python script that downloads the data and draws the charts, suggest design changes (for example, replacing the dual-axis chart with two stacked panels), and revise headlines so they match what the real data showed
- respond to my Part I feedback by drafting the winter commute plan, finding university and city resources, and planning the imagery;


