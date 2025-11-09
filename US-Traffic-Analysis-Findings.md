<p align="center">
  <img src="./Images/dot-traffic-analysis.png" alt="Traffic Analysis Banner" width="60%">
</p>

---

# Traffic Analysis Findings

<p align="center">
  <a href="https://www.youtube.com/watch?v=U90AnBX5_gE">
    <img src="./Images/PlaybackThumbnail.png" alt="Watch on YouTube" width="70%">
  </a>
  <br/>
  <sub><em>Watch: 10‑min walkthrough of the Traffic Analysis Findings</em></sub>
</p>

---

# **Reflection**

1. **Accomplishments:**

The most successful part of this project was uncovering meaningful insights hidden in the data. For example, rush hour has the most accidents but the fastest clearance times, while nighttime has the fewest accidents yet the slowest recovery. The urban–rural divide, infrastructure factors, and weather conditions all told different stories about accident risk and response. Those findings felt genuinely actionable—things a transportation department could use to make changes.

Scatterplots were especially powerful. Seeing multiple dimensions—severity, duration, count, and risk—on one plot made trends stand out immediately. Feature engineering helped too; breaking time into day, month, and hour revealed behavioral patterns you’d never notice in raw timestamps. Creating combined metrics, like the Response Burden Index, was another turning point. It made it easier to see where severity, duration, and frequency intersect, even if the formula itself could be refined further next time.

Working with real-world data was messy but educational. Early years were incomplete, and several columns contained non-normalized data that required bucketing before analysis. That process taught me a lot about how to impose structure on chaos and extract consistent meaning. The cleaning and standardization work turned out to be just as important as the analysis itself.

2. **Opportunity for Growth:**

The project’s biggest challenge was scope. With almost seven million records, I wasn’t sure where to begin. I decided to explore broadly—time, weather, and infrastructure—which gave range but limited depth. Tableau also struggled with the data volume, forcing me to aggregate heavily and lose some interactivity. In hindsight, I could have focused on one or two dimensions and told a deeper story rather than juggling several partial ones.

Another growth area was balancing analysis with communication. I discovered that finding insights and explaining them clearly are two different skills. The technical work took so much time that I didn’t leave enough room to rehearse my presentation, and the result came off more rambly than I wanted. Developing the ability to summarize complex data into a clean, confident narrative is something I plan to practice more.

I also realized how much more I need to grow in statistical analysis. When it came time to validate findings, I had to attempt techniques like ANOVA and chi-square that I hadn’t fully learned yet. Understanding which tests apply to which kinds of data, and how to interpret them responsibly, is an area I want to strengthen. Lastly, I want to get better at building interactive dashboards that balance performance and depth, so users can explore the data without technical barriers.

3. **Future Improvements:**

If I had more time and resources, I’d take a closer look at the long-duration outliers we filtered out—accidents lasting more than 24 hours, especially in rural areas. Those extreme cases might highlight deeper issues in emergency response systems or resource availability. I’d also like to dig into South Carolina’s unusually high accident rate to understand what’s driving it, whether that’s weather, infrastructure, or something cultural or systemic.

Another improvement would be adding geolocation data to pinpoint the country’s top accident hotspots, normalized by population. That level of precision would allow us to identify not just which states face challenges, but which specific locations need intervention. Finally, I’d expand the dataset to include injury and fatality information so that future analysis could focus more directly on preventing loss of life—not just minimizing cost—and work toward a dashboard that feels more dynamic and exploratory, giving end users the power to interact with the data themselves.

