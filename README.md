

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Naïve vs Basic Prompting - Detailed Comparative Report</title>
  <style>
    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.7;
      margin: 20px;
      background-color: #f9fafc;
      color: #333;
    }
    h1, h2, h3 {
      color: #1e3a8a;
    }
    h1 {
      text-align: center;
      border-bottom: 3px solid #2563eb;
      padding-bottom: 10px;
      margin-bottom: 30px;
    }
    p {
      margin-bottom: 12px;
    }
    code, pre {
      background: #f1f5f9;
      padding: 10px;
      border-radius: 6px;
      display: block;
      margin: 10px 0;
      border-left: 5px solid #2563eb;
      font-size: 14px;
    }
    ul, ol {
      margin: 12px 0 12px 20px;
    }
    table {
      border-collapse: collapse;
      width: 100%;
      margin: 20px 0;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    th, td {
      border: 1px solid #d1d5db;
      padding: 10px;
      text-align: center;
    }
    th {
      background-color: #2563eb;
      color: white;
    }
    tr:nth-child(even) {
      background-color: #f3f4f6;
    }
    .highlight {
      background: #e0f2fe;
      padding: 6px;
      border-radius: 6px;
      border-left: 4px solid #0ea5e9;
      margin: 10px 0;
    }
    .conclusion {
      background: #ecfdf5;
      padding: 15px;
      border: 2px solid #10b981;
      border-radius: 8px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <h1>📊 Comparative Report: Naïve vs Basic (Refined) Prompting in ChatGPT</h1>

  <h2>1. Introduction</h2>
  <p>
    Prompting is the foundation of interaction with AI models. The way a query is structured 
    can dramatically affect the <b>clarity, accuracy, and depth</b> of AI-generated responses.  
    In this study, we compare two prompt types:
  </p>
  <ul>
    <li><b>Naïve Prompt:</b> Broad, vague, and unstructured instructions (e.g., <i>"Tell me about space."</i>).</li>
    <li><b>Basic Prompt (Refined):</b> Clear, detailed, and structured instructions with constraints 
    (e.g., <i>"Explain space exploration in 3 paragraphs focusing on history, technology, and future possibilities."</i>).</li>
  </ul>

  <h2>2. Objectives</h2>
  <ol>
    <li>Design and test prompts across multiple scenarios.</li>
    <li>Compare how Naïve vs Basic prompts influence AI responses.</li>
    <li>Evaluate performance based on <b>Quality, Accuracy, and Depth</b>.</li>
    <li>Provide insights and best practices for effective prompt engineering.</li>
  </ol>

  <h2>3. Methodology</h2>
  <div class="highlight">
    <b>Evaluation Metrics:</b> Each response is rated on a 1–3 scale:
    <ul>
      <li>Quality → Clarity, grammar, fluency.</li>
      <li>Accuracy → Correctness and relevance.</li>
      <li>Depth → Completeness, reasoning, richness of content.</li>
    </ul>
  </div>

  <h2>4. Test Scenarios and Responses</h2>

  <h3>Scenario 1: Creative Story</h3>
  <pre>
Naïve Prompt:
"Write a story."

Response (Naïve):
"A boy lived in a small village. He wanted adventure and went to the forest."

Basic Prompt:
"Write a 200-word story about a brave girl who discovers a hidden treasure 
in the forest. Include a clear beginning, conflict, climax, and moral."

Response (Basic):
A detailed adventure story about a girl named Asha, who overcomes fear, 
finds treasure, but realizes that courage and wisdom are the true treasures.
Moral: "Courage unlocks inner strength."
  </pre>

  <h3>Scenario 2: Factual Question</h3>
  <pre>
Naïve Prompt:
"What is gravity?"

Response (Naïve):
"Gravity pulls things down."

Basic Prompt:
"Explain gravity in 3–4 sentences for a high school student, 
including its definition, cause, and real-life examples."

Response (Basic):
"Gravity is a force of attraction between objects with mass. 
On Earth, it keeps us grounded and makes objects fall when dropped. 
It is caused by the curvature of space-time due to mass. 
For example, gravity keeps the Moon orbiting the Earth."
  </pre>

  <h3>Scenario 3: Summarization</h3>
  <pre>
Naïve Prompt:
"Summarize World War II."

Response (Naïve):
"World War II was a global war from 1939 to 1945."

Basic Prompt:
"Summarize World War II in 5 sentences covering causes, 
major events, key leaders, and its impact on the world."

Response (Basic):
"World War II (1939–1945) was triggered by the rise of fascism 
and Germany’s invasion of Poland. Major battles included 
Stalingrad, Midway, and D-Day. Leaders like Churchill, Roosevelt, 
Hitler, and Stalin played central roles. The war ended with the 
surrender of Germany and Japan. Its impact included the creation 
of the United Nations and the beginning of the Cold War."
  </pre>

  <h3>Scenario 4: Advice / Recommendations</h3>
  <pre>
Naïve Prompt:
"How to stay healthy?"

Response (Naïve):
"Eat good food and exercise."

Basic Prompt:
"Give 7 practical daily health tips for working professionals. 
Each tip should be actionable and concise."

Response (Basic):
1. Drink at least 2 liters of water daily.  
2. Take 5–10 minute stretch breaks every hour.  
3. Eat balanced meals with vegetables and protein.  
4. Sleep 7–8 hours consistently.  
5. Limit processed foods and sugar.  
6. Meditate or breathe deeply for stress relief.  
7. Schedule regular health check-ups.  
  </pre>

  <h3>Scenario 5: Technical Explanation (Chain-of-Thought)</h3>
  <pre>
Naïve Prompt:
"Explain Ohm’s Law."

Response (Naïve):
"Ohm’s Law says voltage = current x resistance."

Basic Prompt:
"Explain Ohm’s Law step by step as if teaching a beginner. 
Include the formula, meaning of each term, a real-world example, 
and why it is important in electronics."

Response (Basic):
Step 1: The formula is V = I × R, where V = Voltage, I = Current, R = Resistance.  
Step 2: Voltage is the pushing force, current is the flow of electrons, resistance is the opposition.  
Step 3: Example: A 9V battery pushing current through a 3Ω resistor produces 3A current.  
Step 4: Importance: It helps engineers design safe circuits and predict current flow in devices.  
  </pre>

  <h2>5. Comparative Evaluation Table</h2>
  <table>
    <tr>
      <th>Scenario</th>
      <th>Prompt Type</th>
      <th>Quality</th>
      <th>Accuracy</th>
      <th>Depth</th>
      <th>Remarks</th>
    </tr>
    <tr>
      <td rowspan="2">Creative Story</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td><td>Short and plain</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>3</td><td>Well-structured, moral lesson</td>
    </tr>
    <tr>
      <td rowspan="2">Factual Question</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td><td>Too vague</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>2</td><td>Clear, with examples</td>
    </tr>
    <tr>
      <td rowspan="2">Summarization</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td><td>Oversimplified</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>3</td><td>Comprehensive, balanced</td>
    </tr>
    <tr>
      <td rowspan="2">Advice</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td><td>Generic tips</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>3</td><td>Actionable and practical</td>
    </tr>
    <tr>
      <td rowspan="2">Technical Explanation</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td><td>Minimal explanation</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>3</td><td>Step-by-step with example</td>
    </tr>
  </table>

  <h2>6. Extended Analysis</h2>
  <table>
    <tr>
      <th>Aspect</th>
      <th>Naïve Prompts</th>
      <th>Basic Prompts</th>
    </tr>
    <tr>
      <td>Clarity</td>
      <td>Ambiguous, under-specified</td>
      <td>Explicit, structured</td>
    </tr>
    <tr>
      <td>Accuracy</td>
      <td>Partial correctness</td>
      <td>More precise and relevant</td>
    </tr>
    <tr>
      <td>Depth</td>
      <td>Shallow content</td>
      <td>Detailed with reasoning</td>
    </tr>
    <tr>
      <td>Consistency</td>
      <td>Varies per run</td>
      <td>Stable outputs</td>
    </tr>
    <tr>
      <td>Use Cases</td>
      <td>Casual, trivial queries</td>
      <td>Academic, technical, creative tasks</td>
    </tr>
  </table>

  <div class="conclusion">
    <h2>7. Conclusion & Best Practices</h2>
    <ul>
      <li><b>Basic prompts consistently outperform Naïve prompts</b> across all scenarios.</li>
      <li>Refined prompts deliver more structured, accurate, and insightful responses.</li>
      <li>Naïve prompts may suffice for casual queries, but not for professional or educational use.</li>
      <li><b>Best Practices:</b>
        <ol>
          <li>Specify the task clearly (story, explanation, summary, etc.).</li>
          <li>Define output format (bullets, steps, paragraphs).</li>
          <li>Provide context (audience level, purpose).</li>
          <li>Set boundaries (word count, style, tone).</li>
          <li>Use Chain-of-Thought style for technical/analytical queries.</li>
        </ol>
      </li>
    </ul>
    <p>
      👉 In short, <b>the clearer the prompt, the better the AI output</b>. 
      Refined prompts ensure ChatGPT delivers results that are useful, reliable, and deep.
    </p>
  </div>

</body>
</html>

# RESULT: The prompt for the above said problem executed successfully
