| [home page](https://tstum-wq.github.io/tstum-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The 13 Biggest Roller Coaster Drops in the World - DataViz Analysis
  

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

![Original Data Visualization](Original_dataviz.png)

*Source: [TripSavvy - Tallest Roller Coasters in the World](https://www.tripsavvy.com/tallest-roller-coasters-in-the-world-3226411)*

I selected this visualization to critique because of its illustrative design. It initially presents an overall pleasing illustration that uses color and theme to mimic the fun nature of an amusement park. It seemed clear from the article that the content and presentation align with the target audience of teens or thrill-seekers. Plus, I have always loved riding roller coasters - the wilder, the better!

This choice allowed me to reflect on the entire scope of this design. For example, who was this visual for? Other questions included:
Beyond general thrill-seekers, who is the specific intended audience?
What specific narrative or trend does the data demonstrate? 
Is the visualization declarative (stating a fact) or exploratory (inviting the user to find their own insights)?
Is the approach primarily conceptual (metaphor-heavy) or data-driven (focused on precise values)? 
Ultimately, what is the visualization attempting to communicate?

## Step two: the critique
![Untitled_Artwork 5](https://github.com/user-attachments/assets/1b2aca75-f5f4-4782-92a8-6626fd7fa70b)

## Usefulness: 
I'd give this a 5 out of 10 score. While the visualization successfully attracts its target demographic through niche content, the presentation is not fully optimized. Although it identifies the largest roller coaster drops, the viewer encounters excessive visual noise and a lack of clarity. While the underlying data is sound, the delivery hinders the user's ability to extract value efficiently.

## Completeness: 
The visualization is "complete" in terms of data density, yet this abundance creates a significant distraction. Much of the included information feels arbitrary; for instance, inconsistent color application creates more confusion than insight, detracting from the chart’s primary purpose.

## Perceptibility: 
While a bar chart is a logical choice for this data, the specific selection and orientation of the bars hinder a clear narrative. The piece functions more as a thematic illustration than a clear example of data storytelling. For example, while the coaster graphic slopes downward from left to right to mirror the rankings, it serves as a decorative element rather than a functional aid to data interpretation.

## Truthfulness: 
The visualization provides a generally accurate representation of operating roller coasters. Notably, the source article includes two coasters that are not yet fully constructed; excluding these from the visual was an appropriate editorial choice. However, the title is somewhat ambiguous, suggesting the "10 Tallest Roller Coasters" when the data actually focuses on the "Biggest Drop." The relationship between total height and drop height remains unclear to the viewer. 

## Intuitiveness: 
The chart lacks immediate clarity; deeper analysis reveals increasing discrepancies. The flow follows a standard left-to-right hierarchy, but the central illustration—featuring a large "hump"—contradicts the intended "high-to-low" visual logic. Furthermore, the text's vertical orientation makes reading difficult, and the numbering system uses a non-consistent color palette without a corresponding legend. 

## Aesthetics: 
The design is over-saturated with competing colors, shapes, and random assignments. These choices push the project into the realm of illustration rather than functional data visualization. Labeling is also redundant; the repetitive use of "FT. DROP" is unnecessary if the title is properly defined. Additionally, coasters with tied heights are implied rather than explicitly labeled. Alternating colors on the bars, with two side-by-side being the same color, is inconsistent and unnecessary. 

## Engagement: 
The visualization is likely effective for its primary audience of teenagers and thrill-seekers. The bright, stylized theme and "fun" aesthetic align well with the interests of a younger demographic. 

## Overall observations: 
My primary takeaway is that simplifying the design by removing distracting elements will clarify the data story. Currently, excessive color distribution, unnecessary illustrations, and awkward labeling are in direct conflict with an otherwise straightforward narrative. 

## Who is the primary audience for this tool? 
Younger thrill-seeker audiences. 
## Do you think this visualization is effective for reaching that audience? 
Moderate. It successfully reaches its audience through a colorful, albeit busy, pop-style theme that highlights top-ranked coasters.

In my redesign, I intend to prioritize the data over the artwork. Using the Visual Vocabulary guide, I will explore more effective design options for ranked content, specifically bar or lollipop charts. I look forward to iterating on these concepts in Tableau and Datawrapper to create a cleaner, more intuitive user experience. 


## Step three: Sketch a solution
I initially used sketching, then proceeded to both Datawrapper and Tableau to create the two charts below. <br> I used a horizontal bar chart to orient text for legibility. The number values were moved to the right of the bars, and the names of roller coasters are easily read when placed to the left of the bars. I also changed the title so that the measurement value was clear and indicated what the data actually recorded: the largest drops (in feet) of the world's top 13 roller coasters. <br> I tried a horizontal lollipop chart to add some playfulness to the data, knowing that a younger audience would likely be interested in this information.

![initial_sketches](https://github.com/user-attachments/assets/9c065b9e-7d49-4d21-acd2-e17f6bae93b9)
 
<img width="1240" height="846" alt="VJ7ua-the-13-biggest-roller-coaster-drops-in-the-world-" src="https://github.com/user-attachments/assets/1bc4db1b-e158-49c5-addb-9335411b95ec" />

![Test2_Lollipop_Tableau](https://github.com/user-attachments/assets/52c59f57-b681-40dd-9ecf-5433134d3f32)


## Step four: Test the solution

Results: 

| Question | Interviewees - MSPPM student, MISM student, MSISPM student | 
| :--- | :--- | 
| **Can you describe to me what this is telling you?** | Yes, it's about the 13 Biggest Roller Coasters in the World | 
| **Is there anything you find surprising or confusing?** | It says 'in the World', but which countries are represented? <br> We'd like to know where they are located. | 
| **Who do you think is the intended audience?** | We think it's teens, thrill-seekers, and engineers. | 
| **Is there anything you would change or do differently?** | Use color to indicate coasters not in the U.S. Maybe the ties <br> could be alphabetized. We like the use of a different, brighter color to highlight the coaster ranked #1.|


Synthesis: 

Several concerns arose for this design, as well as for the others we were critiquing in the group. 
We discussed how best to represent multiple variables in a chart. Which ones to include and which to omit.
The group also discussed who the audience was and whether the data correlated with that audience. Identifying and including relevant data missing would add a layer of information to tell a better story. Labeling was discussed, and, interestingly, personal preferences differed regarding the font weight for the coaster names. The most significant discussion revolved around references to specific countries missing from the chart. The idea is that a viewer interested in this chart would also want to know where to ride these coasters. Color was discussed as a way to highlight this omission. 

Based on the feedback, overall, the first round of designs was considered a vast improvement on the original. The bar chart was preferred over the lollipop chart by all three interviewees. Clarity and simplicity were noted. The redesign will incorporate color considerations for the countries represented to see if that works! 

## Step five: build the solution

<img width="1240" height="906" alt="mjg4W-the-13-biggest-roller-coaster-drops-in-the-world-nbsp-" src="https://github.com/user-attachments/assets/77ed59a7-5e77-4fc2-8fd5-440ec6cc9705" />

The final design adapts the horizontal bar chart to highlight the global locations of the world’s top 13 roller coasters. Following a positive critique of the initial framework, my focus shifted to refining the color palette. Color assignments were iterated to ensure a rational distribution, while font colors were kept consistent within categories for better legibility.

The resulting color-coded country legend introduces a playful, brighter quality suited to the subject matter, appealing to younger or adventurous audiences without distracting from the primary ranking data. While the original design did not prioritize geographic distribution, emphasizing these countries ultimately proved valuable in supporting the data's content.


## References
* [Chart Selection](https://makeovermonday.co.uk/) - Used to select the chart I analyzed.
* [DataViz](https://www.datawrapper.de/) - Used to generate the data visualization chart 1.
* [Tableau Desktop (v2023.2) – Used for generating the data visualization chart 2.
* [Coolors.co](https://coolors.co) - Color palette generation.
* [Visual Vocabulary (ft.com/vocabulary) - Used to help identify appropriate chart selections for the problem.
* **Berinato, Scott (2016).** *Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations*. Harvard Business Review Press. 
>   * Used **Chapter 3 ("Two Questions")** to define the chart's purpose.
>   * Used **Chapter 4 ("How To Build A Chart")** for the design workflow.

## AI acknowledgements
Google Gemini was employed to tutor me in code related to specific functions within GitHub. Grammarly was accessed for corrections in grammar and punctuation. 

