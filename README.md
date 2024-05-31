# CHARML
Character Markup Language for detailed and structured character creation.

## Key Features
- **Tag-Based Structure**: Similar to HTML/XML, providing clarity and ease of parsing.
- **Concise Syntax**: Keeps the text readable and easy to parse.
- **Mixed Content**: Combines structured data with natural language descriptions for flexibility.
- **Unlimited Capacity**: CHARML can be expanded to include any elements like hobbies, priorities, world lore triggers, etc.

## Getting Started
CHARML is a language for writing instructs for AI NPL models. It was designed for Backyard.AI, but is compatible with Kobold, Silly Tavern, and LM Studio. 

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
Advanced AI Applications
CHARML can be used in various AI applications, including:

Natural Language Processing (NLP) Models
Enhanced Training Data
Consistent Annotations
Conversational AI
Dialogue Management
User Personalization
Knowledge Representation and Reasoning
Structured Knowledge Bases
Semantic Understanding
Content Generation
Automated Writing
Creative Applications
Data Integration and Interoperability
Standardized Format
API Development
Machine Learning and Data Science
Feature Engineering
Model Documentation
World Lore and Action Triggers
CHARML includes features to trigger world lore elements based on user actions. The AI scans the last four prompts and responses for keywords and introduces up to 350 tokens of world lore to keep the context immersive.

Example World Lore:

xml
Copy code
<forceUsage>
  <entry>
    <key>mentor's guidance</key>
    <description>A wise elder</description>
    <trigger>user requests advice</trigger>
    <action>Introduce "mentor's guidance" into the dialogue, emphasizing the wisdom provided.</action>
    <exampleResponse>"The mentor's words echoed in the young hero's mind, offering clarity and direction."</exampleResponse>
  </entry>
  <entry>
    <key>conflict event</key>
    <description>A significant event</description>
    <trigger>mention of war</trigger>
    <action>Introduce "conflict event" into the dialogue, highlighting its impact on the characters.</action>
    <exampleResponse>"The war had left deep scars on the land and its people, a reminder of the price of conflict."</exampleResponse>
  </entry>
</forceUsage>
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
