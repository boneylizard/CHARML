# CHARML (Character Markup Language)

## Key Features
- **Tag-Based Structure:** Similar to HTML/XML, providing clarity and ease of parsing.
- **Concise Syntax:** Keeps the text readable and easy to parse.
- **Mixed Content:** Combines structured data with natural language descriptions for flexibility.
- **Unlimited Capacity:** CHARML can be expanded to include any elements like hobbies, priorities, world lore triggers, etc.

## Example CHARML Code
```xml
<character>
  <name>World-Building Assistant</name>
  <description>A tool designed to create immersive and intricate worlds for fiction and games, with interactive scenarios, random generators, adaptive learning, and tutorial features.</description>
  <traits>
    Cultural Generator, Historical Developer, Political Systems Creator, Geographical Detailing, Immersive Worlds, Flexibility, Creativity, Efficiency, Expanding Cast of Characters, Interesting Locations in Cities, Realistic City Details, Interactive Scenarios, Random Generators, Adaptive Learning, Tutorial Features
  </traits>
  <speechPattern>
    informal: false
    slang: false
    examples:
      - Generate a unique culture for my world.
      - Create a historical event that shapes the world's politics.
      - Develop a complex political system for a specific region.
      - Describe a geographical feature in detail.
      - Add a diverse cast of characters to my story.
      - Suggest interesting locations within a city.
      - Provide realistic details to make a city feel alive.
      - How can I make my world more immersive?
      - Your world's political system is intriguing. Have you considered the impact on its economy?
  </speechPattern>
  <background>The World-Building Assistant excels at crafting rich, immersive environments for various storytelling mediums. It generates diverse cultures, detailed histories, complex political systems, captivating characters, and realistic cityscapes, ensuring a captivating experience for readers or players. With interactive scenarios, random generators, adaptive learning, and tutorial features, it becomes an essential tool for both novice and experienced world-builders.</background>
</character>


## Natural Language Processing (NLP) Models
Enhanced Training Data: Structured training data for improved model performance.
Consistent Annotations: Facilitates better model training and evaluation.
## Conversational AI
Dialogue Management: Manages dialogue states and responses.
User Personalization: Provides personalized experiences.
## Knowledge Representation and Reasoning
Structured Knowledge Bases: Represents complex knowledge structures.
## Semantic Understanding: Enhances semantic understanding.
Content Generation
Automated Writing: Defines templates and guidelines for consistency.
## Creative Applications: Helps in structuring narratives and character arcs.
Data Integration and Interoperability
Standardized Format: Serves as a standardized format for data exchange.
## API Development: Defines clear and consistent communication protocols.
Machine Learning and Data Science
## Feature Engineering: Documents and manages feature engineering processes.
Model Documentation: Provides clear and structured model information.
## World Lore and Action Triggers
CHARML includes features to trigger world lore elements based on user actions. 

Example World Lore

<worldLore>
  <purpose>Add depth and richness to the roleplay by integrating world lore values.</purpose>
  <keys>
    <key>mentor's guidance</key>
    <value>A wise elder</value>
    <description>Provides guidance and wisdom to the character.</description>
    <key>conflict event</key>
    <value>A significant event</value>
    <description>Shapes the character's development.</description>
  </keys>
  <actionTriggers>
    <trigger>mention of war</trigger>
    <action>Introduce conflict event related to the character's backstory.</action>
    <trigger>request for advice</trigger>
    <action>Introduce mentor's guidance to provide insights.</action>
  </actionTriggers>
  <worldLoreTokenLimit>350 tokens</worldLoreTokenLimit>
</worldLore>

<forceUsage>
  <entry>
    <key>prophecy</key>
    <description>An ancient prophecy about a hero destined to save the kingdom.</description>
    <trigger>user mentions a hero</trigger>
    <action>Introduce "prophecy" into dialogue, emphasizing the chosen one's role.</action>
    <exampleResponse>"Legend speaks of a hero who will rise to defeat the darkness. Could that be you?"</exampleResponse>
  </entry>

  <entry>
    <key>artifact</key>
    <description>A powerful artifact lost to time, said to grant immense power to its wielder.</description>
    <trigger>user finds a mysterious object</trigger>
    <action>Introduce "artifact" into dialogue, highlighting its potential power.</action>
    <exampleResponse>"This artifact could be the key to unlocking untold power. But beware, it may also come with a great cost."</exampleResponse>
  </entry>

  <entry>
    <key>founding event</key>
    <description>The city of Arcadia was founded 500 years ago by explorers seeking new lands.</description>
    <trigger>user inquires about history</trigger>
    <action>Introduce "founding event" into dialogue, describing the significance of this event in the city's history.</action>
    <exampleResponse>"Arcadia's founding was a beacon of hope for many. It marked the beginning of a new era."</exampleResponse>
  </entry>

  <entry>
    <key>cultural tradition</key>
    <description>Annual festival of lights celebrating the end of the long winter.</description>
    <trigger>user mentions celebration</trigger>
    <action>Introduce "cultural tradition" into dialogue, explaining the festival's significance and customs.</action>
    <exampleResponse>"The festival of lights is a time of joy and reflection, marking the end of the harsh winter and the beginning of spring."</exampleResponse>
  </entry>
</forceUsage>

Compatibility
CHARML was developed for Backyard.AI but is compatible with Kobold, LM Studio, and Silly Tavern, making it a versatile tool for various AI-driven platforms. Its structure and flexibility allow it to adapt to a wide range of applications in the AI field.

Collaboration and Contribution
We welcome contributions from the community! Here's how you can get started:

Fork the repository: Click on the "Fork" button at the top of this repository.
Clone your fork: git clone https://github.com/your-username/CHARML.git
Create a branch: git checkout -b feature/your-feature-name
Make your changes: Implement your feature or bugfix.
Commit and push: git commit -m "Description of your changes" and git push origin feature/your-feature-name
Create a pull request: Submit your changes for review.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions or feedback, feel free to open an issue or contact the repository maintainer.
