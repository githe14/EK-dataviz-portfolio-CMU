| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Final Project: Part 2

## Project Pivots & The New Proposal

Before we dive deeper into developing the narrative of the project for Part II, including the wireframe and user research, I would like to share the major updates I've made in my project scope based on my initial data exploration and feedback from Part I. 

### Recap of Part I - Idea A: From Vinyl to Viral
In my initial project proposal, I wanted to explore the trend of music consumption over time based on the **Music Industry Sales from RIAA (Recording Industry Association of America)**, accessed via [Kaggle](https://www.kaggle.com/datasets/andrewmvd/music-sales). This dataset provides a comprehensive historical record of revenue and unit volumes by media format from 1973 to 2019.

As a rough outline, I planned to analyze over 13,000 data points in this set and visualize the trend that reflects the "Format Wars" in the music industry over the last 50 years. My goal was to deliver a core narrative centered on the industry's unsettling journey from the **Era of Ownership** (physical sales, such as vinyl and CDs) through the **Age of Digital Disruption** (piracy and downloads) to the modern **Era of Platform Wars** (digital streaming platforms). As a data visualization project aimed to be exploratory, I found the general music consumer to be the key target audience to demonstrate how their listening behavior, along with that of millions of others, influenced the industry to change its entire business model.

For my initial visualization sketch, shown below, I used a stacked area chart to represent the shifts in music revenue. The visualization highlighted the magnitude of physical sales until its collapse, followed by a brief boom in piracy/downloads and the emergence of digital streaming platforms.

<img width="1843" height="1970" alt="image" src="https://github.com/user-attachments/assets/011950b4-a3f4-4dc2-9735-7049664e7b17" />

### Why am I Pivoting Project Proposal?

After reflecting on my initial proposal and doing further research, I decided to pivot from Idea A to a new topic. While the RIAA's music sales data effectively illustrates the macro-level history of the music consumption and sales trends, it struggles to have the the thoughtful analysis and doesn't provide much insights/story that the readers can take away from the project. The story of format wars can be discussed to provide necessary historical background on the music industry, but I felt my initial approach was too broad to offer a unique interpretation beyond surface-level information that most already know. It works more like a history lesson than a compelling data story with a clear takeaway.

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

Shorthand: [link](https://preview.shorthand.com/fK2rfgIjuiaeQc)

## User Research 

### Target Audience

The primary target audience for this project is the general music consumer, specifically music enthusiasts or regular listeners with an interest in the industry but unaware of the financial structures behind the music they enjoy, such as pro-rata or the 30-second rule. Another audience segment I can consider is artists themselves — musicians, songwriters, and other creators — who lack detailed knowledge about industry financial models. I do not expect this segment to be significant, but it may include aspiring or outdated artists. While smaller in size, this group can benefit from this project by gaining insights to maximize their financial incentives in an ever-evolving complex ecosystem.

While some might argue that the key target should be those in the industry, I disagree because most, if not all, are involved in the music market and are well-aware of the key contexts of this project, as it is the core foundation of monetization. For instance, industry professionals or executives may not be the right fit, as they often design and work for the system. Most pro-musicians (or even semi-pro level) already know this as well, since they are living it. The consumer is the one who is unaware of this story. They might think music is changing naturally, not realizing they are being influenced by their consumption behavior and manipulated by an algorithm.

> Recruitment Approach:
> Finding my target audience (general music consumer) wasn't very difficult. However, I wanted to conduct interviews with three individuals who have varying levels of interest in and involvement with music and still fit the demographic profile. I thought this would provide unbiased and comprehensive feedback compared to selecting interviewees who share the same level of musical engagement. Below are the general descriptions of three interviewees.
> 1. Interview A (Power User): CMU Master of Entertainment Industry Management student. Heavily interested in the music/entertainment industry. Listens to 4+ hours of music daily and curates playlists.
> 2. Interview B (Passive Listener): UCLA master's student studying data analytics. Listens to music while working/commuting, relies on algorithmic playlists. Considered the least involved in music consumption out of all interviewees.
> 3. Interview C (Casual Listeners): CMU master student pursuing a project management career path. Listens to music occasionally and has a moderate amount of interest in the market. Attends concerts sometimes with friends. 

### Interview script
> List the goals from your research, and the questions you intend to ask.

Validate the Hook: Do users actually know about the "30-second rule"? (If they already know, the story lacks impact).

Test the Visualization: Is the drop in song duration obvious in the line chart, or does it need more annotation?

Check the Narrative: Does the connection between "Financial Incentives" and "Shorter Songs" make sense to a layperson?

Text here!

Question 1: "When you listen to a spotify playlist or other DSP, how long do you listen to a song before you decide to skip it?"

Question 2: "Does this chart surprise you? Did you notice songs were getting shorter?"

Question 3: "If I told you artists get paid the same for a 30-second play as a 10-minute play, does this trend make sense to you?"

| Goal | Questions to Ask |
|------|------------------|
|      |                  |
|      |                  |
|      |                  |


Text here!

### Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

Text here!

| Questions               | Interview 1 (briefly describe) | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| Question you asked here | Insightful feedback            |             |             |
|                         |                                |             |             |
|                         |                                |             |             |


## Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

Text here!

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Findings or observations from interviews | Describe what, if any changes you anticipate making to address the observation. |
| Still lacks in Call-to-action.... |                                                                                 |
| Few more graphs                                         |                                                                                 |
|                                          |                                                                                 |
| ...add more rows as necessary            |                                                                                 |

> ...include any final thoughts you have here. 

Text here!


### References
Ay, Y. E. (2020). Spotify Dataset 1921-2020, 160k+ Tracks. Kaggle. https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-1921-2020-160k-tracks
McIver, A. (2020). Music Industry Sales (1973 - 2019). Kaggle. https://www.kaggle.com/datasets/andrewmvd/music-sales
Recording Industry Association of America. (2023). Music Industry Facts. RIAA. https://www.riaa.com/facts/
Spotify. (2025). Loud & Clear: Annual Music Economics Report. https://loudandclear.byspotify.com/#takeaway-2
Trolley. (2024, May 2). So, how exactly do streaming services calculate royalties? Trolley Learning Center. https://trolley.com/learning-center/so-how-exactly-do-streaming-services-calculate-royalties/

### AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

