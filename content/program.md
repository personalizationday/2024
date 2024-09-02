---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: features
    id: program
    content:
      title: Program
      text: '
      <p class="text-gray-500 sm:text-xl dark:text-gray-400 text-center"><b>Monday</b><br></p>
      <br>

      <table class="tg"><thead>
        <tr>
          <th class="tg-0pky">Time</th>
          <th class="tg-0pky">Title</th>
        </tr>
      </thead>
      <tbody>
        {{< program-row time="11:00-12:00" content="Registration desk opens" modalId="deskOpens">}}
        {{< program-row time="12:00-13:00" content="Lunch" modalId="lunch" >}}
        {{< program-row time="13:00-13:15" content="Opening and introduction" modalId="introduction" >}}
        {{< program-row time="13:15-14:05" content="Peter Knees - AI needs ethics, but we need to change the game." modalId="bioPeterKnees" keynote="true" >}}
        {{< program-row time="14:05-14:25" content="Toine Bogers - FairMatch: A Multi-stakeholder Approach to Responsible Algorithmic Hiring " modalId="bogers" >}}

        {{< program-row time="14:25-14:45" content="Jia-Hua Jeng - Multi-Modal Affective Reframing of a News Service with Large Language Models" modalId="jeng" >}}

        {{< program-row time="14:45-15:05" content="Benjamin Kille - Large Language Models and their Potential for Personalization" modalId="kille" >}}

        {{< program-row time="15:15-15:45" content="Coffee break" >}}

        {{< program-row time="15:45-16:00" content="Poster Madness" >}}
        {{< program-row time="16:00-17:00" content="Poster Session" >}}
        {{< program-row time="17:00-19:00" content="Reception" modalId="reception" >}}

      </tbody>
      </table>
      <br><br>

      <p class="text-gray-500 sm:text-xl dark:text-gray-400 text-center"><b>Tuesday</b><br></p>
      <br>

      <table class="tg"><thead>
        <tr>
          <th class="tg-0pky">Time</th>
          <th class="tg-0pky">Title</th>
        </tr>
      </thead>
      <tbody>

        {{< program-row time="09:00-09:10" content="Welcome" >}} 
        
        {{< program-row time="09:10-09:30" content="Dietmar Jannach - Understanding longitudinal effects of recommender systems." modalId="jannach" >}}

        {{< program-row time="09:30-09:50" content="Alan Said - The Carbon Footprint of Recommender Systems." modalId="said" >}}

        {{< program-row time="09:50-10:10" content="Lovisa Annerwall - Recommender systems and firm performance: A systematic review of the past to prepare for future developments" modalId="annerwall" >}}

        {{< program-row time="10:10-10:30" content="Alain Starke - A Primer on Normative Design and Thinking in Recommender Systems: A Brief Research Agenda for the Food Domain." modalId="starke" >}}


        {{< program-row time="10:30-11:00" content="Coffee break" >}}

        {{< program-row time="11:00-11:50" content="Martin Tegner - Keynote: TBD." modalId="bioMartinTegner" keynote="true" >}}
 
        {{< program-row time="11:50-12:10" content="Mehdi Elahi - Recommender Systems and the Challenge of Popularity Bias: An Overview." modalId="elahi" >}}

        {{< program-row time="12:10-12:30" content="--"  >}}

        {{< program-row time="12:30-13:30" content="Lunch" modalId="lunch" >}}

        {{< program-row time="13:30-15:00" content="Panel" modalId="panel" >}}

        {{< program-row time="15:00-15:30" content="Closing"  >}}

        {{< program-row time="15:30-16:00" content="Coffee break and good bye" >}}

      </tbody>
      </table>
      <br><br>

      {{< modal id="deskOpens" content="The registration desk opens. Attendees are welcome to arrive from 11:00. Lunch is served at 12:00. The program starts at 13:00" >}}
      
      {{< modal id="lunch" content="Lunch is served at restaurant Lyktan, at Walleberg Conference Center" >}}

      {{< modal id="introduction" content="Introduction to the Nordic Personalization Days" >}}

      {{< modal id="reception" content="Food and drinks" >}}


      {{< modal id="bioPeterKnees" title="Peter Knees" image="../knees.webp" abstract="The recent hype of AI and its apparently unavoidable permeation of all areas of life has gone hand in hand with calls for establishing regulatory measures to enforce ethical use. Given the present and foreseen threats of unregulated use of AI, it is clear that guardrails, international agreements, and policies to protect the rights and interests of citizens are needed. However, the ongoing power shift away from publicly funded AI research towards industrial R&D could effectively result in self-regulation of industry rather than transparency of systems and accountability. Academic research not tied to commercial interests therefore needs to play a much stronger role in this process. In the talk, I will argue that academia for this reason also needs to define clear and stronger policies for research and industry cooperations and needs to invest considerable resources to keep their level of expertise and believably act in the public interest. Furthermore, universities need to take their mission seriously by properly valuing ethical research over amplifying the industry&#39;s agenda." bio="Peter Knees is Associate Professor at the Faculty of Informatics at TU Wien. He has been conducting research at the interface of artificial intelligence and music for two decades, including applications in the field of music recommendation algorithms. As UNESCO Chair for Digital Humanism, he deals with social challenges resulting from the digital transformation, in particular with issues relating to the responsible use of AI, the teaching of digital skills and a global perspective on these developments." >}}

      {{< modal id="bogers" title="Toine Bogers" image="../organizers/toine.png" abstract="In my talk I will introduce our progress and future plans in the FairMatch project: a multi-stakeholder aware approach to responsible algorithmic hiring. The main goal of the project is to develop fairness-aware job and candidate recommendations for Jobindex, Denmark&#39;s largest job portal. To make this process inclusive, we have taken a multi-stakeholder approach in the first phase of the project by interviewing all relevant stakeholders and mapping their needs and insights to relevant fairness metrics. I will present our preliminary findings from this phase as well as our plans for the remainder of the project." bio="Associate Professor, IT University Copenhagen. Chief Scientific Officer, AI Pioneer Centre (DK)" >}}

      {{< modal id="jeng" title="Jia-Hua Jeng" abstract="Recent developments in artificial intelligence allow newsrooms to automate journalistic choices and processes. In doing so, news framing can impacts people&#39;s engagement with news media, as well as their willingness to pay for news articles. Large Language Models (LLMs) can be used as a framing tool, aligning headlines with a user&#39;s preferences or state. It is however unknown how people perceive and experience the use of a platform with such LLM-reframed news headlines. We present the results of work-in-progress study with a news recommender system. Users (N = 300) were asked to read three news articles from The Washington Post from a preferred category (abortion, economics, gun control), with headlines that were rewritten by an LLM (ChatGPT-4) in specific emotional languages. We compared six framing conditions in a 2 (positive vs negative headlines) x 3 (positive or negative image, or no image) between-subject design, examining the effects on emotional states, engagement and intention to pay for a news service. We found that negative images and text elicited negative emotions, while positive framing had little effect. Users were also more willing to pay for a news service when facing negatively framed headlines and images. Surprisingly, the congruency between text and image (i.e., being both positive or negative) did not significantly impact engagement. We discuss how this study can shape further research design." bio="PhD Candidate, MediaFutures, University of Bergen (NO)" >}}

      {{< modal id="kille" title="Benjamin Kille" image="../organizers/benny.jpg" abstract="Large Language Models (LLMs) have emerged as powerful tools for tasks involving generating texts. We can identify a multitude of use case that involve personalized texts. The talk will discuss the challenges in building LLMs and using them for personalization tasks." bio="Associate Professor, Norwegian University of Science and Technology (NO)" >}}
      
      {{< modal id="annerwall" title="Lovisa Annerwall" abstract="People worldwide are increasingly exposed to personalized recommendations influencing the movies you watch, the products you purchase, the news you read, and so forth. During the last decade, firms of different sizes, countries, and industries, have increasingly adopted recommender systems (RS) to improve their business offerings (Jannach & Bauer, 2020). The more widespread application of RS in business has grown substantially in recent years (Fayyaz et al., 2020; Jannach et al., 2021; Roy & Dutta, 2022). RS are information processing tools assisting customers in decision-making. RS also helps firms to influence customers’ decisions and must therefore be seen as a tool to enhance firm performance. RS is therefore supporting customers by personalizing suggestions about items while simultaneously supporting firms to augment business value (Jannach & Jugovac, 2019). That RS contributes to business value is in general undisputed, but how to portray this value is in its infancy (Jannach & Zanker, 2022). Oesterreich et al. (2022) explicitly call for researchers to focus on the business value of advanced analytics concepts, and both Jannach and Bauer (2020) and Jannach and Jugovac (2019) express the need for a better understanding of how RS impact firm performance. We conduct a systematic literature review of papers published up until early 2023 to examine current insight on RS impact on firm performance. The purpose is to address and discuss future research opportunities and contribute with input into the development of the next generation of RS. Connecting to contemporary expectations on firms we take a multifaceted perspective of firm performance that besides the financial dimension also emphasize the social and ecological implications (Elkington, 1998). Adhering to the perspective of multi-stakeholder impact of RS (e.g., Abdollahpouri et al. (2020)) and complementing the extensive reviews by De Biasio et al. (2023) and De Biasio et al. (2024), we contribute by introducing this multifaceted view on firm performance acknowledging intended and unintended consequences. We also introduce nontraditional theoretical perspectives offering novel concepts that can offer tools to re-think RS consequences in and on organizations. In line with De Biasio et al. (2023), Jannach and Zanker (2022) and Jannach and Jugovac (2019), our review shows an overall one-dimensional emphasis on sales, focusing on volume or diversity. We find a dominant user-centric mindset where RS is related to measurement of views and clicks, which are presumed to impact sales. Our review exposes a gap in the literature regarding a more full-fledged understanding of the impact of RS on economic firm performance, in terms of cost and profit. We suggest that RS research studying firm performance also needs to incorporate short and long-term bottom-line thinking, and impact on social and ecological outcomes. We encourage researchers to explicitly connect to a multifaceted perspective on business value in studies of RS. Such a view is essential for uncovering dilemmas and paradoxes associated with RS implementation and development. We therefore advocate that developers of RS adopt an equivalent perspective to ensure that technology and algorithms are as aligned as possible with stakeholders’ contemporary expectations of firms." bio="PhD Student, Mälardalen University (SE)" >}}

      {{< modal id="starke" title="Alain Starke" image="../starke.jpg" abstract="Most recommender systems are designed to optimize for user preferences based on utilitarian criteria. Clicks and positive ratings reinforce content, often without further adaptation or intervention by a recommender designer. In this talk, I will present an alternative perspective for the design and evaluation of recommender system, using normative thinking. Building upon recent research, among others the workshop NORMalize at RecSys, I explain what normative thinking is, how it can be used in recommender systems, and how I propose to use it in the domain of healthy eating. This future work goes beyond the typical application of normative thinking, which is the news domain. The main aim of this talk is to introduce the concepts to a broader audience." bio="Associate Professor, University of Bergen (NO), Assistant Professor, University of Amsterdam (NL)" >}}

      {{< modal id="jannach" title="Dietmar Jannach" image="../jannach.png" abstract="On most platforms, recommendations are continuously and repeatedly served to consumers. It is thus important to measure in a longitudinal way if the recommendations are leading to the desired long-term effects, both in terms of customer-related quality aspects as well as in terms of business metrics. In academic settings, longitudinal effects are however barely examined. Most of the published research is based on one-time measurements, and this applies both to offline evaluation settings and in user studies. To overcome current limitations, researchers need to explore alternative methodological approaches. In this talk, we will outline the importance and existing challenges of longitudinal recommender research and review the potential value of simulation approaches in this context." bio="Professor, University of Bergen (NO), Professor, Univerität Klagenfurt (AT)" >}}

      {{< modal id="said" title="Alan Said" image="../organizers/alan.jpg" abstract="As global warming intensifies, the environmental impact of research is increasingly scrutinized, yet the carbon footprint of recommender systems remains largely unexplored. This talk delves into our recent analysis presented at ACM RecSys 2024, where we measured the carbon emissions of 79 papers from RecSys 2013 and 2023. By reproducing typical experimental pipelines, we found that deep learning-based recommender systems emit, on average, 42 times more CO2 equivalents than traditional algorithms, contributing significantly to the field&#39;s overall environmental toll. We advocate for greater awareness and adoption of sustainable practices in recommender systems research to mitigate this impact." bio="Associate Professor, University of Gothenburg (SE)" >}}

      {{< modal id="elahi" title="Mehdi Elahi" image="../elahi.jpg" abstract="Recommender systems are tools that empower media applications to support users in discovering relevant and fresh content online, namely news articles and videos. However, these systems can introduce or intensify undesired effects, such as Popularity Bias, where popular content becomes disproportionately emphasized. This can lead to further issues, including the lack of diversity in the content presented to users.In this talk, I will address this challenge, providing an overview of the impact of different recommendation approaches across various domains and scenarios, and share our latest research findings on this challenge." bio="Associate Professor, University of Bergen (NO)" >}}


      {{< modal id="bogers" title="Toine Bogers" image="../organizers/toine.png" abstract="Talk." bio="affil" >}}
      {{< modal id="bogers" title="Toine Bogers" image="../organizers/toine.png" abstract="Talk." bio="affil" >}}
      {{< modal id="bogers" title="Toine Bogers" image="../organizers/toine.png" abstract="Talk." bio="affil" >}}
      {{< modal id="bogers" title="Toine Bogers" image="../organizers/toine.png" abstract="Talk." bio="affil" >}}
      {{< modal id="bogers" title="Toine Bogers" image="../organizers/toine.png" abstract="Talk." bio="affil" >}}


      {{< modal id="bioMartinTegner" title="Martin Tegner" image="../tegner.jpg" abstract="TBD" bio="Martin Tegner is Principal Data Scientist at IKEA." >}}

      '
---
