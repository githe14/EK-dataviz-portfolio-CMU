| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Final Project: Part 3

## The Final Data Story

Please click **[The Attention Economy: How Streaming Changed the Pop Song](https://carnegiemellon.shorthandstories.com/the-attention-economy-of-the-music-industry/index.html)** or copy and paste the link below to see my presentation of the final project!

**Link:** https://carnegiemellon.shorthandstories.com/the-attention-economy-of-the-music-industry/index.html

## Changes Made Since Part 2

### What Happened in Part 2?
In **[Part II](https://githe14.github.io/EK-dataviz-portfolio-CMU/final-project-part-two)**, I made a significant pivot in the project's scope. Initially, my goal was merely to explore general music consumption trends using U.S. music sales data (IDEA A). However, I realized that this macro-level view was too broad and lacked a specific, actionable story. Therefore, I decided to narrow my focus to IDEA B: The Attention Economy. I merged the original sales data with a new dataset (Spotify data, 1921–2020) to tell a deeper story.

- The Macro Context: First, I used the sales data to confirm the shift in listener behavior. The data shows that while physical formats (CDs, Vinyl) and digital downloads dominated the past, streaming emerged in the early 2010s and became the dominant revenue source by 2015.
- The Micro Consequence: I then focused on the impact of this shift. Since the industry now relies on streaming, artists were forced to adapt to a new financial system defined by the 30-second rule and pro-rata payouts. As a consequence, music got shorter, and song structures changed to capture attention immediately. 

### Refinements based on User Research
My user research in Part 2 highlighted two areas for improvement: the visual consistency of the data and the clarity of the conclusion (CTA).

**1. Visualizing the "Dark Mode" Aesthetic:**

I learned that for the story to feel native to the subject matter, the visualizations needed to mimic the interface of a streaming platform (specifically Spotify). While I initially experimented with Tableau, I found it difficult to create the specific high-contrast dark theme I wanted. My overall presentation had to be in a dark background to highlight the visualizations, which I aimed to focus on the trend lines of data on a stacked area chart and a line chart. I moved my visualization workflow to Google Colab and utilized Python (Pandas/Matplotlib). To create the visualization on Google Colab, I utilized the AI (Gemini) to help write the Python syntax required to customize the background and accent colors to match the Shorthand theme.

** **Detailed AI Acknowledgement is explained on my [Final Shorthand Story](https://carnegiemellon.shorthandstories.com/the-attention-economy-of-the-music-industry/index.html).**

<img width="1453" height="702" alt="image" src="https://github.com/user-attachments/assets/b7ac1f5a-c1f3-4e0e-8834-0edc93ccb4af" />

Once I created the Python syntax with Gemini, I used Google Colab to generate images.

<img width="1541" height="988" alt="Code_Generated_Image (3)" src="https://github.com/user-attachments/assets/62725aaa-5aad-4f9b-8ef8-db77faee6157" />
<img width="1541" height="988" alt="Code_Generated_Image (2)" src="https://github.com/user-attachments/assets/5946ee90-51e9-48ab-a30f-a0513dac06b5" />
<img width="1584" height="988" alt="Code_Generated_Image (1)" src="https://github.com/user-attachments/assets/bbff56bc-2ffc-45db-a1fc-934f88461533" />

**The Stacked Area Chart (Context):** A visualization of RIAA data showing the transition from Physical to Streaming dominance. Each chart highlights each era using the scrolling feature on Shorthand.

<img width="1600" height="976" alt="Code_Generated_Image (9)" src="https://github.com/user-attachments/assets/fe71ba83-66db-4e32-9bfd-bac824263dec" />
<img width="1600" height="976" alt="Code_Generated_Image (8)" src="https://github.com/user-attachments/assets/81b91cd4-623a-496f-98a7-e733d30fe72f" />
<img width="1547" height="988" alt="Code_Generated_Image (7)" src="https://github.com/user-attachments/assets/d87f16e8-3d34-4467-914a-9de1fb7c923c" />
<img width="1547" height="988" alt="Code_Generated_Image (6)" src="https://github.com/user-attachments/assets/d0c3c7c2-2391-41e1-897f-1b00a0b50b81" />
<img width="1547" height="988" alt="Code_Generated_Image (5)" src="https://github.com/user-attachments/assets/56885232-2f7d-4bdb-9cc6-5f816ecf074d" />
<img width="1547" height="988" alt="Code_Generated_Image (4)" src="https://github.com/user-attachments/assets/726fe00c-5863-4dc7-b032-efd68a17d8d9" />

**The "Progressive" Line Chart (The Trend):** Rather than showing the Spotify duration drop as a static image, I generated six progressive versions of the chart (1995, 2000, 2005, etc.) and linked them to the scroll in Shorthand. The intention was to allow the reader to experience the timeline of the data. Following the trend line for 15 years (the CD era) makes the sudden drop in 2015 feel much more dramatic and consequential.

![3](https://github.com/user-attachments/assets/ef47dfe5-dd37-4a4c-a59a-cfa38a8d537a)
![2](https://github.com/user-attachments/assets/b38864ad-3971-46a0-8aba-ede961018f3e)
![1](https://github.com/user-attachments/assets/edba974f-6683-429f-8f82-b3da8128a28d)

**The Waveform Comparison (Song Structure):**
To visualize the structural shift in songwriting, I used **WaveVisual** to generate real waveforms directly from Spotify track data. I selected two iconic songs representing distinct eras—one from the Physical era (featuring a dynamic, traditional song structure with an intro) and one from the Streaming era (featuring an immediate hook and loudness). Comparing these visual forms as examples can provide a clearer understanding to the audience and demonstrate how the incentive system of streaming has physically influenced the shape of modern music.

**2. Defining the Call to Action:**

The second major lesson from my user research was that my conclusion felt incomplete to three interviewees, who are general music consumers (the target audience). My interviewees understood the data and main narrative, but they didn't know what to do with it.

Since my primary target audience is the General Music Consumer, I developed a more detailed conclusion with specific "Next Steps/Call-to-Action":
- Support with Streaming: I added a clear explanation of the "30-second rule" so consumers understand that skipping a song denies the artist payment. I also included resources like Spotify 'Loud & Clear' and Last.fm for users to check their own listening habits.
- Support Outside Streaming: I clarified that since streaming pays fractions of a penny, true support comes from buying merchandise, concert tickets, or physical media (Vinyl/CDs).
- Exploratory Reflection: I still wanted to keep some exploratory conclusions, asking the audience to consider if these financial incentives caused by music consumption are actually good for the industry overall, along with other questions they can take away after the presentation.

### Completing the Final Story (Shorthand)

The final step involved integrating all these finalized visualizations and refined narratives into Shorthand. To ensure a cohesive narrative flow before building the site, I drafted a comprehensive presentation outline that served as the blueprint for the story. This outline structured the narrative arc into distinct sections:

**1. Title: The Attention Economy**
* **Subtitle:** How Streaming Changed the Song.
* **Goal:** Throw the hook (30-Second Rule).

**2. The Context: The Medium Shift (Idea A)**
* **Narrative:** Tracing the shift from ownership to access.
* **Visualization:** Stacked Area Chart (US Sales data) showing the decline of physical sales and the rise of streaming.

**3. The Mechanism: The Financial Incentive**
* **Narrative:** Explaining why the shift matters. Artists are no longer paid for the sale. They are paid for attention/retention.
* Define the 30-Second Rule and Pro-Rata.

**4. The Evidence: The Shrinking Song (Idea B)**
* **Narrative:** The consequence of the financial incentive. To survive, artists adapted by making songs shorter.
* **Visualization:** Progressive Line Chart (Spotify Data) showing the average song duration decreased drastically after 2015.

**5. The Illustration: Structure Change**
* **Narrative:** It's not just length but the structure that got influenced. Intros are disappearing to prevent early skips.
* **Visualization:** Waveform Comparison (1980s: Slow & Intro vs. 2020s: Hook & Louder).

**6. Conclusion: Call-to-Action**
* **Narrative:** Shifting from analysis to action for general music consumers.
* **Call to Action:** Support artists by listening past 30 seconds, buying merch, and collecting physical media.

## The Audience

My primary audience for this story is the General Music Consumer, specifically Gen Z and Millennials, who use streaming platforms daily but are unaware of the backend economics. While this group is actively using streaming services, they are mostly unaware of the financial mechanisms, such as the 30-Second Rule, that influence the content they consume. Therefore, I found that general music consumers have more insights to take away from this informative project compared to industry professionals or artists who live within this system.

Insights from my user research helped develop the final story, particularly regarding the project's conclusion. My interviewees commonly expressed a feeling of loss after seeing the data. Fortunately, they understood the problem and the main context, but didn't know what to do with the information. Therefore, I shifted the conclusion from a summary of plain information to creating broader suggestions for different areas where consumers can take actual, immediate next steps. First, I provided actionable suggestions for using Streaming, explaining how listening past the 30-second mark supports artist payment. Second, I emphasized support for outside of streaming, encouraging the power of merchandise and physical media that aren't impacted by the pro-rata system. Finally, I included some exploratory reflections, asking the audience some questions to consider after the presentation regarding the system, trend, and industry. This would make the presentation end with meaningful reflections rather than just data points.

## Final thoughts

Reflecting on the entire process, the biggest takeaway was learning that effective data storytelling often requires skills in narrowing the scope rather than broadening it. My initial concept (Idea A) was a broad history lesson on music sales, which provided context but lacked impact. By focusing on the specific effects of consumption behavior, I learned that stories that provides layer of are often more compelling than narrating  ones. Zooming in on a single, granular metric—Song Duration—allowed me to unravel a much larger, complex narrative about how financial incentives invisibly shape our culture and art. This project confirmed that the strongest data stories answer "Why?" rather than just showing "What."

Technically, stepping outside of standard visualization tools to generate custom charts in Python was a rewarding challenge. While it required a steeper learning curve than using Tableau templates, it allowed me to achieve the specific "Dark Mode" aesthetic that was crucial for my storytelling. If I had more time or resources, I would have loved to incorporate an interactive audio element into the Shorthand story, allowing users to hear the structural difference between a 1980s intro and a 2024 hook while looking at the waveforms. However, I am proud that the visual data alone is strong enough to make the point, effectively transforming abstract economic concepts into a tangible reality for the general music consumer.

### References
Ay, Y. E. (2020). Spotify Dataset 1921-2020, 160k+ Tracks. Kaggle. https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-1921-2020-160k-tracks<br/>

McIver, A. (2020). Music Industry Sales (1973 - 2019). Kaggle. https://www.kaggle.com/datasets/andrewmvd/music-sales<br/>

** Above are the references for Part 3. Please check the detailed references of the entire project in my Shorthand story.

## AI acknowledgements
No AI use for Final Project: Part 3.
