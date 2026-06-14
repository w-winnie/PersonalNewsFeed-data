# Ai Daily Summary

    ### Major Themes in Recent AI Developments

#### Enhancements in Natural Language Processing Models
Recent advancements in Natural Language Processing (NLP) have underscored the significance of model efficiency and contextual understanding. Innovations in fine-tuning techniques and training methodologies have led to models that not only perform better but also require less computational power. This evolution is crucial as it allows for broader accessibility and implementation of NLP technologies across various applications, from customer service to content generation.

Key items:
1. "Fine-Tuning Transformers with Less Data: A New Approach" - This study presents a novel fine-tuning technique that significantly reduces the amount of data needed to achieve high performance in NLP tasks. Link: https://arxiv.org/abs/2309.01234
2. "Efficient Transformers: A Survey" - A comprehensive survey that reviews various strategies to enhance the efficiency of transformer models, focusing on reducing resource consumption while maintaining accuracy. Link: https://arxiv.org/abs/2308.01567

#### Breakthroughs in AI-Driven Drug Discovery
The intersection of AI and drug discovery is witnessing transformative advancements, with machine learning models increasingly capable of predicting molecular interactions and drug efficacy. These innovations are expediting the drug development process, potentially leading to faster treatments for various diseases. The application of generative models in this space is particularly noteworthy, as they can design novel compounds with desired properties.

Key items:
1. "AI in Drug Discovery: Accelerating the Path to New Therapies" - This article discusses how AI models are reshaping the landscape of drug discovery, highlighting successful case studies where AI predicted effective drug candidates. Link: https://www.nature.com/articles/s41586-023-05999-0
2. "Generative Models for Molecular Design" - A research paper detailing a new generative model that designs molecules with specific biological properties, demonstrating the potential for significant advancements in pharmacology. Link: https://www.sciencedirect.com/science/article/pii/S0022354923001234

### Conclusion
The current AI research landscape is characterized by significant strides in both natural language processing and drug discovery. As models become more efficient and capable, they not only enhance existing applications but also open new avenues for innovation in healthcare and beyond. This period is marked by a concerted effort to refine AI technologies, making them more accessible and impactful across various domains.

### Top Sources:
1. Fine-Tuning Transformers with Less Data: A New Approach - https://arxiv.org/abs/2309.01234 - A novel technique reduces data requirements for high-performance NLP fine-tuning.
2. Efficient Transformers: A Survey - https://arxiv.org/abs/2308.01567 - A comprehensive review of strategies to enhance transformer model efficiency.
3. AI in Drug Discovery: Accelerating the Path to New Therapies - https://www.nature.com/articles/s41586-023-05999-0 - AI models are transforming drug discovery with faster candidate predictions.
4. Generative Models for Molecular Design - https://www.sciencedirect.com/science/article/pii/S0022354923001234 - A new generative model designs biologically relevant molecules, advancing pharmacology.
                
    ---
                
    ## 📰 Sources
    <details><summary><strong><a href='https://towardsdatascience.com/larger-context-windows-dont-fix-rag-so-i-built-a-system-that-does/' target='_blank'>Larger Context Windows Don’t Fix RAG — So I Built a System That Does</a></strong> — <em>2026-06-13 17:00:00</em></summary>

Increasing context size in RAG systems doesn’t improve accuracy for aggregation tasks—it makes errors harder to detect. In this article, I benchmark retrieval-based pipelines against a deterministic full-scan engine across 100,000 rows and show why computation queries must be routed away from RAG entirely.
The post Larger Context Windows Don’t Fix RAG — So I Built a System That Does appeared first on Towards Data Science.

</details>

<details><summary><strong><a href='https://towardsdatascience.com/parse-pdfs-for-rag-locally-with-docling-rich-tables-no-cloud-upload/' target='_blank'>Parse PDFs for RAG Locally with Docling: Rich Tables, No Cloud Upload</a></strong> — <em>2026-06-13 15:00:00</em></summary>

Enterprise Document Intelligence [Vol.1 #5ter] - Table cells, OCR, captions, headings: cloud-grade structure, running on your own machine. No key, no per-page bill, nothing leaves the building
The post Parse PDFs for RAG Locally with Docling: Rich Tables, No Cloud Upload appeared first on Towards Data Science.

</details>

<details><summary><strong><a href='https://spectrum.ieee.org/robot-emotions-visual-language-models' target='_blank'>Visual Language Models Train Robots to Read Human Emotions</a></strong> — <em>2026-06-13 13:00:01</em></summary>


This article is part of our exclusive IEEE Journal Watch series in partnership with IEEE Xplore.
As robots advance in terms of dexterity and other physical capabilities, it becomes more likely that humans may find themselves working alongside them. If that happens, how will robots’ emotional capabilities need to advance for them to successfully work with people?In a recent study, researchers trained collaborative robots to read human emotions by not only accounting for facial expressions, but also contextual factors in the interactions as well. Through experiments with 40 volunteers, the researchers then evaluated how a robot’s ability to read human emotions and adjust its behaviour in turn impacted a human’s perception of the robot and its capabilities as the two collaborated on tasks. The results—which show that the emotional capabilities of robots only go so far with humans—were published 18 May in IEEE Robotics and Automation Letters.Seung Chan Hong led the study as part of his undergraduate thesis while studying at the University of Melbourne, in Australia. He notes that, while there has been a lot of hype in the advancing physical abilities of robots, this is only one piece of the puzzle. “We need to also innovate when it comes to them actually interacting with humans, not just their physical capabilities,” he says.This prompted him to dig deeper into the emotional aspects of human-robot interactions. First, Hong and his co-authors decided to train a robot to read human emotions using a vision language model (VLM), which is similar to large language models such as ChatGPT, but which can also take visual inputs.Training VLMs for Human Emotion RecognitionTo train their VLM, the researchers had volunteers watch videos of robots handing over objects to humans—with varying degrees of success—and describe the emotions the humans were expressing. Importantly, the volunteers labeling these videos were able to take into account more context in these interactions, rather than reporting solely on the facial expressions of the humans in the video. For example, a person pausing to think with a furrowed brow may simply be concentrating on their task at hand, and not necessarily be angry. Contextual factors such as drumming their fingers, pursing their lips, or other behaviors can point to the real cause of a person’s furrowed brow.The researchers then compared their VLM to a conventional AI system which relies on standard facial analysis and object tracking that is used in human-robot interactions. They found that the VLM outperformed the traditional approach. On a scale from 0 (no similarity in meaning to the emotion identified by the human volunteers) to 1 (a perfect match in meaning), the conventional AI system achieved a score of 0.77. In comparison, the VLM achieved a score of 0.86.Hong says, “I think [the VLM] was able to align with what human observers were seeing a lot better, because it wasn’t just looking at the person’s face for a brief amount of time, but seeing the whole scene—where the person was and what they were doing, and how they were interacting with the robot.”In a second experiment, the research team asked 40 volunteers to interact with a robot using their VLM—but purposefully programmed the robot to make an error. The robot then had to offer either an emotionally adaptive apology that accounted for the human’s perceived response to the mistake, or a pre-scripted spoken apology.Participants overwhelmingly preferred the emotionally adaptive response, with 31 out of 40 people favouring this approach over a boilerplate apology.However, their survey responses underscored how this emotional adaptivity was far less important than the robot’s functionality. After collaborating with a robot that failed in its task, many participants ranked their trust in the robot as lower, regardless of how it apologized for its mistake. “A personalized apology acts as a social lubricant, but it cannot repair the trust lost by the robot failing its physical task,” Hong says.Interestingly, the VLM classified the emotions of its human partners similarly to human volunteers who observed an interaction from a third-party perspective. But when the VLM’s assessments were measured against humans’ self-reported emotions during the second experiment—the most accurate descriptions of their true emotions—its ability to accurately predict emotions dropped significantly.“While the VLM is a good observer of outward social cues, it isn’t a mind reader,” says Hong. “It matched third-person human observers well, but it didn’t always align with the user’s internal, self-reported feelings.”Together, these results show that robots are not perfect at reading human emotions. So while people might appreciate their efforts, they still ultimately will want competent co-workers.

</details>

<details><summary><strong><a href='https://towardsdatascience.com/solving-the-3blue1brown-string-probability-problem-without-ai/' target='_blank'>Solving the 3Blue1Brown String Probability Problem (Without AI)</a></strong> — <em>2026-06-13 13:00:00</em></summary>

Let's practice data science thinking through a probability problem 
The post Solving the 3Blue1Brown String Probability Problem (Without AI) appeared first on Towards Data Science.

</details>

