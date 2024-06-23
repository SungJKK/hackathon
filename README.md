## Tagline

"Experience and Learn through Debate: Bring History to Life"


## Inspiration

The inspiration for HistoricaDialogue stems from the high entry barriers young students often face in subjects like literature and philosophy. Despite having a keen interest in these fields, the complexity and density of traditional texts can deter many from pursuing deeper understanding. Our goal was to create a tool that not only captures the attention of learners but also provides a comprehensive understanding of historical contexts by introducing various aspects of notable figures. By simulating individuals from different eras, we enable debates that were previously only possible in our imagination, making learning more engaging and accessible.

## What it does

LegacyConverse is an educational tool designed to facilitate a deeper understanding of historical and well-known figures through interactive conversations and debates. By simulating individuals from various eras, the application allows users to engage in discussions with AI-generated personas of notable figures such as Socrates, Plato, Warren Buffet, and Bill Gates. 

- Users can observe debates between historical figures or engage in conversations with them.
- Users can discuss any topic they choose, with figures investigating big data to simulate accurate responses.
- Provides comprehensive insights into the contexts and ideologies of historical personalities.
- Makes learning engaging and accessible by transforming traditional educational methods.

## How we built it

We used the CrewAI framework to create an environment where multiple AI specialized agents can analyze data and discuss with other agents to derive the simulated responses of historical figures. 

- **AI Specialization:** Each agent captures important characteristics such as historical, rhetorical, and psychological aspects.
- **AWS Integration:** Developed primarily on the AWS environment for seamless connections between services like OpenSearch and Lambda.
- **MVP Development:** Agents are currently prompt-engineered in the OpenAI GPT model.
- **Speech Capabilities:** Implementing AWS Polly and Textract for text-to-speech and speech-to-text transformations, with voice files stored in S3 buckets for future use.

## Challenges we ran into

- **Data Quality and Availability:** Acquiring and cleaning data was a significant challenge, as historical texts often contain unnecessary information.
- **Realistic Simulation:** Ensuring that AI-generated conversations were both realistic and educational required continuous refinement.
- **Balancing Engagement and Education:** Maintaining a balance between engaging content and educational value was challenging.

## Accomplishments that we're proud of

- **Prompt Engineering:** Successfully tuned prompts provided to the LLM model to achieve the desired goals despite initial unfamiliarity with the technique.
- **Interdisciplinary Collaboration:** Effectively combined expertise from history, AI, and education to create a robust and effective tool.
- **User-Centered Design:** Developed an engaging and intuitive user interface that enhances the learning experience.

## What we learned

- **Interdisciplinary Collaboration:** The importance of working with experts from various fields to ensure accuracy and engagement.
- **Balancing Engagement and Education:** Effective strategies for integrating gamification elements without compromising educational depth.
- **User Feedback:** The value of continuous iteration based on real user experiences.
- **AI for Education:** Insights into leveraging AI for educational purposes, particularly in simulating complex historical contexts and debates.
- **Data Management:** Strategies for sourcing, verifying, and processing large datasets to ensure authenticity and accuracy.
- **Technological Integration:** Expertise in integrating various AWS services for a seamless and efficient backend.

## What's next for LegacyConverse

- **Transition to RAG AI Agents:** Replace current agents with RAG AI agents developed on Bedrock using summaries of specialized AI crews, books, and theses scraped from the web.
- **GUI Development:** Implement a graphical user interface to create a web application.
- **Enhanced Voice Features:** Use AWS Polly-generated voice files with new GUI features in future patches.
- **Expanding the Historical Database:** Continuously add more historical figures and expand the range of conversations and debates available.
- **Educational Partnerships:** Collaborate with more educational institutions to integrate LegacyConverse into curriculums and reach a wider audience.
- **New Interactive Features:** Introduce additional elements like virtual classrooms and collaborative learning modules to further enrich the user experience.

