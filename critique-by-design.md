| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Engagement Ring Costs Critique
Instructions....

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

_
<img width="983" height="373" alt="image" src="https://github.com/user-attachments/assets/2749478c-d4ac-4991-9944-9a47681299bd" />
Website : https://makeovermonday.vercel.app/dataset/w242024-whats-going-on-in-this-graph-engagement-ring-c

_I found it fascinating to explore how a person's income direct-matches to the actual dollar amount they spend on an engagement ring. When looking at the raw data, there is a surprising dynamic: while ring spending generally increases alongside salary, lower-income individuals spend a dramatically disproportionate share of their annual earnings (~16.7%) compared to higher earners who spend only around 3.1%. Seeing this contrast raises a compelling question about whether lower earners are intentionally splurging or simply navigating a retail market with a fixed minimum price floor for a standard ring._

## Step two: the critique
_Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't work well?
The chart clearly highlights how much heavier ring costs weigh on lower earners, with those making under $23,000 spending a massive 16.7% of their annual income compared to high earners who spend just 3.1%. While the clean layout makes this gap instantly obvious, it leaves out crucial context like actual dollar amounts or sample size, making it hard to tell if lower-income buyers are forced up by base market prices or just feeling cultural pressure to spend big._

_Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not?
The chart effectively reaches students and people wanting to get engaged by breaking spending down into relatable time worked, like "2.2 months" versus "1.6 weeks." This makes the financial contrast obvious without overwhelming them with math. By skipping extra details like total dollar amounts or sample sizes, it naturally gets them thinking about whether lower earners spend more because of baseline market prices or social expectations._

_Based on your critique, what do you think you'll try to focus on in your redesign?   Any ideas or inspiration for how you can make a better data visualization?  What are you excited to try next?
I want to focus on adding actual dollar amounts alongside the percentages so people can immediately see if lower earners are buying budget rings or just getting hit by a high minimum price tag. A niche bubble chart or some type of dual metric chart would be a great way to showcase both the total money spent and the percentage of salary without confusing the viewer._

## Step three: Sketch a Solution

<img width="1787" height="893" alt="IMG_1840" src="https://github.com/user-attachments/assets/af59e50a-497f-4ca2-ade0-9d5d7c7e364f" />

## Step four: Test the Solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Results: 

| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|  Can you tell me what you think this is?        | "It looks like a bar chart showing how many weeks or months of salary different income groups spend on an engagement ring."            |  "This is a simple graphic breaking down the percentage of annual income each salary bracket spends when buying a ring."            |
|  Is there anything you find surprising or confusing?        |  "I was surprised that people making under $23k spend 16.7% of their income, but it's confusing because I can't tell what that actually equals in cash."           | "It’s wild that the top bracket only spends 1.6 weeks of pay, but without showing dollar values, it's hard to tell if lower earners are buying luxury rings or just cheap ones."            |
|  Is there anything you would change or do differently?        | "I would definitely add actual dollar amounts next to the percentages so readers don't have to do the mental math themselves."            | "I'd show both the total price tag and the income percentage side-by-side so you get the full story of what people are actually paying."            |

Synthesis: 

_Looking at the feedback, the main trend was pretty clear which is that people were shocked by how much low earners drop as a percentage, but they were mostly just frustrated that there were not any actual dollar amounts. It made me realize that showing only the salary percentage gives an incomplete picture and that is readers cannot tell if lower earners are splurging on luxury or just getting hit by a standard baseline retail price. To fix this, the best move for the final design is to plot total dollar values right next to the income percentages and add a quick annotation to call out that baseline price floor._

## Step five: Build the Solution

_Include and describe your final solution here. 
<img width="1376" height="768" alt="Gemini_Generated_Image_p68nztp68nztp68n" src="https://github.com/user-attachments/assets/419c2f47-5daf-484d-bfb9-bf3452b63385" />
Working through this data visualization makeover highlighted how dramatically context changes a reader’s perception of data. While the original chart seemed straightforward, applying Stephen Few’s critique framework exposed how visualizing relative income share without absolute dollar values created a misleading narrative. Guided by user feedback, I chose a dual-metric lollipop and bar layout that cleanly compares percentages and total cash outlay side-by-side, turning a story of apparent lower-income extravagance into an honest picture of baseline market realities._

## References
_Few, Stephen. “Data Visualization Effectiveness Profile,” 2017, 11.
http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf_

## AI acknowledgements
_Generative AI tools were utilized to render final visual artifacts, the dual-metric horizontal lollipop._

