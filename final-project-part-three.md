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

**Detailed AI Acknowledgement is explained in the later section.**

Once I created the Python syntax with Gemini, I used Google Colab to generate images.

<img width="1453" height="702" alt="image" src="https://github.com/user-attachments/assets/b7ac1f5a-c1f3-4e0e-8834-0edc93ccb4af" />

**The Stacked Area Chart (Context):** A visualization of RIAA data showing the transition from Physical to Streaming dominance. Each chart highlights each era using the scrolling feature on Shorthand.

<img width="1541" height="988" alt="Code_Generated_Image (3)" src="https://github.com/user-attachments/assets/62725aaa-5aad-4f9b-8ef8-db77faee6157" />
<img width="1541" height="988" alt="Code_Generated_Image (2)" src="https://github.com/user-attachments/assets/5946ee90-51e9-48ab-a30f-a0513dac06b5" />
<img width="1584" height="988" alt="Code_Generated_Image (1)" src="https://github.com/user-attachments/assets/bbff56bc-2ffc-45db-a1fc-934f88461533" />

**The "Progressive" Line Chart (The Trend):** Rather than showing the Spotify duration drop as a static image, I generated six progressive versions of the chart (1995, 2000, 2005, etc.) and linked them to the scroll in Shorthand. The intention was to allow the reader to experience the timeline of the data. Following the trend line for 15 years (the CD era) makes the sudden drop in 2015 feel much more dramatic and consequential.

<img width="1600" height="976" alt="Code_Generated_Image (9)" src="https://github.com/user-attachments/assets/fe71ba83-66db-4e32-9bfd-bac824263dec" />
<img width="1600" height="976" alt="Code_Generated_Image (8)" src="https://github.com/user-attachments/assets/81b91cd4-623a-496f-98a7-e733d30fe72f" />
<img width="1547" height="988" alt="Code_Generated_Image (7)" src="https://github.com/user-attachments/assets/d87f16e8-3d34-4467-914a-9de1fb7c923c" />
<img width="1547" height="988" alt="Code_Generated_Image (6)" src="https://github.com/user-attachments/assets/d0c3c7c2-2391-41e1-897f-1b00a0b50b81" />
<img width="1547" height="988" alt="Code_Generated_Image (5)" src="https://github.com/user-attachments/assets/56885232-2f7d-4bdb-9cc6-5f816ecf074d" />
<img width="1547" height="988" alt="Code_Generated_Image (4)" src="https://github.com/user-attachments/assets/726fe00c-5863-4dc7-b032-efd68a17d8d9" />

**The Waveform Comparison (Song Structure):** For creating waveform section, I chose to use a stark, black-and-white contrast for the waveform comparison. While the rest of the project uses green accents, I kept the waveforms monochromatic to emphasize the structural density of modern songs (the "Brick Wall" effect). This visual metaphor was crucial for showing the artistic consequence of the data trend.

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
> Talk about who you identified as the audience for your final data story.  Include any other information you've used that helped you narrow the focus (e.g. insights from your interviews, personas, etc.).  Note any specific adjustments you made to your final project to make it work for your audience.

## References
> **You should have already included detailed references on your Shorthand story** - if so, you do not need to list them twice, unless you used additional references for specific to your writeup. Use this section to capture any additional special notes or information necessary. If there is additional information for your shorthand readers that you've placed on this page, link from Shorthand to this page. Make sure to double-check that you aren't using copyright material and that you have added / updated any citations or other content that you used to create your data story.  Make sure you have cited external sources correctly.

## AI acknowledgements
> If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here.

Text here!

# Final thoughts
> You can summarize any final thoughts / reflections that don't fit well in the previous sections here.  How did it go?  What did you run out of time for, or wish you had a chance to revisit?  What were you most excited about?  Include any final reflections as you think they might help us understand your process.  If you already included such reflections elsewhere, you can delete this section. 

Text here!


