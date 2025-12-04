| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Final Project: Part 2

## Project Pivots & New Proposal

Before we dive deeper into developing the narrative of the project for Part II, including the wireframe and user research, I would like to share the major updates I've made in my project scope based on my initial data exploration and feedback from Part I. 

### Recap of Part I - Idea A: From Vinyl to Viral
In my initial project proposal, I wanted to explore the trend of music consumption over time based on the **Music Industry Sales from RIAA (Recording Industry Association of America)**, accessed via [Kaggle](https://www.kaggle.com/datasets/andrewmvd/music-sales). This dataset provides a comprehensive historical record of revenue and unit volumes by media format from 1973 to 2019.

As a rough outline, I planned to analyze over 13,000 data points in this set and visualize the trend that reflects the "Format Wars" in the music industry over the last 50 years. My goal was to deliver a core narrative centered on the industry's unsettling journey from the **Era of Ownership** (physical sales, such as vinyl and CDs) through the **Age of Digital Disruption** (piracy and downloads) to the modern **Era of Platform Wars** (digital streaming platforms). As a data visualization project aimed to be exploratory, I found the general music consumer to be the key target audience to demonstrate how their listening behavior, along with that of millions of others, influenced the industry to change its entire business model.

For my initial visualization sketch, shown below, I used a stacked area chart to represent the shifts in music revenue. The visualization highlighted the magnitude of physical sales until its collapse, followed by a brief boom in piracy/downloads and the emergence of digital streaming platforms.

<img width="668" height="712" alt="Screenshot 2025-11-30 at 6 30 46 PM" src="https://github.com/user-attachments/assets/dcc8ea33-1006-46e9-8651-c3a6abe32774" />

### Why am I Pivoting Project Proposal?

After reflecting on my initial proposal and doing further research, I decided to pivot from Idea A to a new topic. While the RIAA's music sales data effectively illustrates the macro-level history of music consumption and sales trends, it struggles to have thoughtful analysis and doesn't provide much insights/story that the readers can take away from the project. The story of format wars can be discussed to provide necessary historical background on the music industry, but I felt my initial approach was too broad to offer a unique interpretation beyond surface-level information that most already know. It works more like a history lesson than a compelling data story with a clear takeaway.

Furthermore, heavily relying on the single RIAA dataset limited the depth of my project. I realized that a project focused solely on industry revenue lacks a meaningful "call to action" or "next steps" for the target audience. To create a more impactful narrative, I want to look beyond sales figures and explore any chain reactions (cause-and-effect analysis) that drive those numbers or are affected by the format wars. As a result, I will be able to contextualize my story with more layered stories, rather than an obvious trend, by leveraging additional resources and a more specific dataset.

## The New Direction
## Idea B - The Attention Economy: How Streaming Changed the Songwriting

I have decided to elevate the project topic without throwing away the entire concept related to the trend in the music industry by shifting the main focus from the **macro** perspective(Industry Revenue) to the **micro** analysis (Songwriting Behavior). Instead of a general overview of physical to streaming, I will now concentrate on how we, as general music consumers, and the medium forced artists to change their behavior and strategy in songwriting. This will allow the project to move beyond exploring what happened (shift in music consumption/sales) to inform why it matters (incentives and behavior of songwriting).

My new proposal transforms the project from a surface-level exploratory analysis into an explanatory/informative story that answers a question: **How have the financial incentives of streaming changed the songwriting behavior?**

### Narrative Arc

The music industry has shifted from ownership (buying a CD or downloading an MP3 file) to streaming (paid-for access), which requires much more attention from listeners to be incentivized. In this new model, platforms like Spotify or Apple Music do not pay the artists and songwriters for the sale of a song. Instead, they pay for retention.

The music industry has a complicated system of monetization that cannot be explained in simple terms. Still, even though the financial models of each digital streaming platform are slightly different and ever-changing, I will focus on two key metrics that are relevant to my narrative: the 30‑second rule and the pro‑rata pool. In the simplest definition, the financial incentive works only after 30 seconds of listening, and artists are paid based on their share of total platform streams within a certain period (Trolley, 2024). This monetization system, driven by the shift in music consumption, forces artists to adopt new strategies in their songwriting; songs get shorter, faster, and optimized to maximize revenue in the modern music listening system.

In conclusion, I aim to inform the target audience (general music consumers) of the impact of their behavior. From this project, the audience will understand that "listening to music isn't simply listening to music"; rather, the listening behavior throughout the period influences the market, financial models, and the music itself.  Furthermore, my goal is to leave several insights or next steps, such as 'what the next trend in music consumption will be' or 'how to support artists when listening to music'.

* **Merging the Ideas:** I plan to not ignore Idea A (From Vinyl to Viral) entirely since the music sales data can serve as the foundational context to set the stage by showing the shift from physical to digital dominance. However, the core narrative and visualizations of this project will focus on Idea B and its data.

### Data

To support my narrative arc, I will be using a new dataset, "Spotify Dataset 1921-2020, 160k+ Tracks" via [Kaggle](https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-1921-2020-160k-tracks). This dataset includes comprehensive information about audio features, popularity scores, and duration data for over 160,000 songs. From this data, I plan to visualize the shift in song duration over time, and key examples (Top Hits) that explain that shift more easily to the audience.

| Name | URL | Description |
|------|-----|-------------|
| Spotify Dataset 1921-2020, 160k+ Tracks     | [https://www.kaggle.com/datasets/andrewmvd/music-sales?resource=download](https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-1921-2020-160k-tracks)    | A comprehensive Spotify music data over 100 years. There are several datasets that are pre-filtered, and I will be the master file, called "data.csv"            |

### Sketches

**Line graph:** Visualizing the steep decline in average song duration over the last decade.

![IMG_3248](https://github.com/user-attachments/assets/22e47b64-a63d-4f5f-84e4-f9d44d4a93f8)

**Waveform Comparison:** Comparison of a waveform of a popular song in the physical era (long flat intro) vs. a waveform of a song in the modern streaming era (immediately loud and skips the intro). This example will illustrate the difference in the structure of songwriting.

![IMG_3249](https://github.com/user-attachments/assets/eb1bb861-1e4a-48d7-961a-89de590b41b3)

**Table:** Although I haven't decided whether to use this data visualization, I want to illustrate the song duration of popular music in each time period, showing that song times are shrinking even faster as streaming emerges as a dominant medium. Showing the most successful songs in each period and their song duration will help the audience understand better.

![IMG_3250](https://github.com/user-attachments/assets/2602239e-b4eb-4270-83d1-89fba085c98b)

## Wireframes / Storyboards

This part further develops the newly revised story outline and any relevant components visually by using wireframes or storyboards. I built this directly in Shorthand and will continue to modify it to use as a final presentation. The final presentation will be pitched in class.

**Shorthand: [click here to access](https://preview.shorthand.com/9QFgIR3ghCmvhkwO)**

## User Research 

### Target Audience

The primary target audience for this project is the general music consumer, specifically music enthusiasts or regular listeners with an interest in the industry but unaware of the financial structures behind the music they enjoy, such as pro-rata or the 30-second rule. Another audience segment I can consider is artists themselves — musicians, songwriters, and other creators — who lack detailed knowledge about industry financial models. I do not expect this segment to be significant, but it may include aspiring or outdated artists. While smaller in size, this group can benefit from this project by gaining insights to maximize their financial incentives in an ever-evolving complex ecosystem.

While some might argue that the key target should be those in the industry, I disagree because most, if not all, are involved in the music market and are well-aware of the key contexts of this project, as it is the core foundation of monetization. For instance, industry professionals or executives may not be the right fit, as they often design and work for the system. Most pro-musicians (or even semi-pro level) already know this as well, since they are living it. The consumer is the one who is unaware of this story. They might think music is changing naturally, not realizing they are being influenced by their consumption behavior and manipulated by an algorithm.

### Identifying Interviewees

Finding my target audience (general music consumer) wasn't very difficult since most people enjoy listening to music. However, I wanted to conduct interviews with three individuals who have varying levels of interest in and involvement with music and still fit the demographic profile. I thought this would provide unbiased and comprehensive feedback compared to selecting interviewees who share the same level of musical engagement. Below are the general descriptions of three interviewees.

1. Interview A (Power User): CMU Master of Entertainment Industry Management student. Heavily interested in the music/entertainment industry. Listens to 4+ hours of music daily and curates playlists.
2. Interview B (Passive Listener): UCLA master's student studying data analytics. Listens to music while working/commuting, relies on algorithmic playlists. Considered the least involved in music consumption out of all interviewees.
3. Interview C (Casual Listener): CMU master student pursuing a project management career path. Listens to music occasionally and has a moderate amount of interest in the market. Attends concerts sometimes with friends. 

### Interview Script

While not strictly limited to these, below are the questions I planned to ask three interviewees, along with the goal behind each question.

| Goal | Questions to Ask |
|------|------------------|
| Validate the consumer behavior. I want to confirm if listeners actually skip songs either consciously or unconsciously. | "Try to think of the recent time you listened to a random playlist. How quickly do you skip a song if you aren't feeling it? How often do you skip songs? What are the reasons you chose to skip a certain song?" |
| Check whether the 30-second rule is common knowledge to my target audience. If most people already know this, my narrative will likely have little impact and will not offer insights. | "Did you know that streaming platforms like Spotify pay an artist only if you listen to the song for at least 30 seconds?" |
| Ask about the visualizations and their formats to check that they communicate the trend clearly without additional explanation. |  "Take a look at the charts/sketches. What is the first thing you notice? Can you understand the context it's trying to convey without any other explanations?" |
| Check the overall storyline/narrative arc of the project | "Do you find the overall project proposal to be understandable and interesting to you? What would be your takeaways?" |

### Interview Findings

| Questions               | Interview A (Power User) | Interview B (Passive Listener) | Interview C (Casual Listener) |
|-------------------------|--------------------------------|-------------|-------------|
| "Try to think of the recent time you listened to a random playlist. How quickly do you skip a song if you aren't feeling it? How often do you skip songs? What are the reasons you chose to skip a certain song?" | "If I'm checking out new releases, I have zero patience. If the beat doesn't hit in the first 7-8 seconds of the intro, I usually skip. Every song is different, but I think I skip 3 or 4 songs out of 5 when listening to a playlist that isn't mine." | Usually listens to music when doing work, driving, or cleaning the house, etc., rather than investing time in music listening. Therefore, she rarely skips songs unless a song is really bad or distracting. "I often use playlists as a background soundtrack." | It depends on the mood, but if a song has a really lengthy intro with a slow start, he skips more often. |
| "Did you know that streaming platforms like Spotify pay an artist only if you listen to the song for at least 30 seconds?" | She is more invested in the entertainment industry, so she is not well-aware of the system. However, she knows that streaming doesn't support much for many artists financially, other than the superstars. She knew that the song needed to be heard for a certain time for credit from watching some YouTubers, but didn't know about the 30-second rule. | She assumed they got paid just by listening to the music, regardless of playtime, like YouTube views. That rule seems really harsh. | He also had no clue. When the question was asked, he assumed that it was calculated based on how much you listened. However, he was surprised that listening to a song for 25 seconds wouldn't incentivize the artist. |
| "Take a look at the charts/sketches. What is the first thing you notice? Can you understand the context it's trying to convey without any other explanations?" | She thinks the line chart of song duration trend is clear and dramatic. The single line helps to emphasize the drop around 2015. Moreover, she found the waveform comparison to be the best part because it is creative and instantly matches the trend of selling songs for social media. Overall, she likes the charts and thinks they explain that songs are focusing more on catchy hooks now.| From a data perspective, the line chart trend is clear, but the sketch needs to include more details and visual improvements. For example, the line chart of song duration should specify years on the X-axis. Maybe add some annotations so I know exactly when the 'drop' happens. Adding colors would definitely help to emphasize key points on the charts. Lastly, she thinks that the table of the top song's duration in each period is direct but not very visually appealing, so it can use a different format. It can be a vertical bar chart, but instead of a bar, write the song title that has the same length as the bar to reflect the duration | Overall, the sketches are clear and easy to understand. He thought the waveform one is cool because I can literally see how drastically different it is in the intro part. |
| "Do you find the overall project proposal to be understandable and interesting to you? What would be your takeaways?" | The story holds up. It explains well why the songs are getting shorter. However, she thinks that additional context explaining the 30-second rule and pro-rata might be helpful for my target audience. | Overall, she sees the project to be understandable. The table can be illustrated more effectively, and additional data visualization might be helpful if I can find more information. The biggest confusion is what the final message is if she is the audience for this presentation. | He likes the visualizations I created. However, he sees that the conclusion needs to be developed because he wasn't quite sure what general consumers, like himself, should take as a call-to-action. "It delivers solid in-depth information, but what is the next step you want to tell?" |


## Identified Changes for Part III

Based on the feedback from my interviews, I have identified three key areas that need refinement in the final presentation. While each synthesis discusses different elements of my project, they ultimately suggest that I need to improve the narrative/story so that it resonates with my target audience, the general music consumer.

| Research Synthesis                       | Anticipated Changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Find the best way to link IDEA A & B, and how the streaming platforms incentivize the artists. | Until I verbally explained, interviewees struggled to see the connection between the stacked bar chart for IDEA A and the other charts for IDEA B. Although my final presentation will provide more details for the audience to understand why those two topics connect, the writings on Shorthand should be self-explanatory for readers to fully grasp the project. Moreover, it took me the most time to explain how the 30-second rule and pro-rata work. Therefore, finding a more effective way to help the audience understand the system is necessary. It may be helpful to find a simple and intuitive image that explains the monetization system. |
| Improving the visual elements of the charts. | While most of the feedback said the visualizations are clear and self-explanatory, they also suggested adding more visual elements to highlight the key context I want to deliver from each chart.  I will refine the charts using Tableau (or Datawrapper/RawGraphs) by adding specific design elements. Many recommended using text annotations directly on the canvas. For instance, I can add a note on the line chart that directly shows "Streaming Emerges" at the point where the line declines drastically. I will also use color to highlight the drop or increase since my two main charts (music sales and music duration) are reflecting a trend that I want to emphasize. Lastly, I will need to explore alternative format options for the table sketch, as I was able to relate to the feedback that the table is too general and not very intuitive at first sight. |
| Clarifying the conclusion (call to action, takeaway, insights) | The revised project adds more depth to the story and has a better narrative that I want to deliver compared to the initial IDEA A. However, interviewees critiqued that it still lacks a conclusion, making it unclear what the final message I want to tell the audience is. Instead of just summarizing the findings, I will add a direct "Call to Action/Takeaway" section that provides some final messages that the audience can reflect on. |

### References
Ay, Y. E. (2020). Spotify Dataset 1921-2020, 160k+ Tracks. Kaggle. https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-1921-2020-160k-tracks<br/>

McIver, A. (2020). Music Industry Sales (1973 - 2019). Kaggle. https://www.kaggle.com/datasets/andrewmvd/music-sales<br/>

Recording Industry Association of America. (2023). Music Industry Facts. RIAA. https://www.riaa.com/facts/<br/>

Spotify. (2025). Loud & Clear: Annual Music Economics Report. https://loudandclear.byspotify.com/#takeaway-2<br/>

Trolley. (2024, May 2). So, how exactly do streaming services calculate royalties? Trolley Learning Center. https://trolley.com/learning-center/so-how-exactly-do-streaming-services-calculate-royalties/

### AI acknowledgements
No AI use for Final Project: Part Two.
