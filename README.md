

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
<html>
<head>
  <meta charset="UTF-8">
  <title>Naïve vs Basic Prompting Report</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; margin: 20px;">

  <h1>📝 Report: Impact of Naïve vs Basic (Refined) Prompts on ChatGPT Responses</h1>

  <h2>1. 📌 Introduction</h2>
  <p>
    Prompt engineering is the practice of designing effective input prompts to get the best possible outputs from AI models.
    The way a question or instruction is framed has a direct influence on the <b>quality, accuracy, and depth</b> of the response.
  </p>
  <p>
    This report compares <b>two types of prompts</b> across multiple scenarios:
  </p>
  <ul>
    <li><b>Naïve Prompt (Broad/Unstructured):</b> Minimal instructions, vague, no clear constraints. Example: <i>"Tell me about the moon."</i></li>
    <li><b>Basic Prompt (Refined/Structured):</b> Clear, detailed, and specific instructions with context and expected output format. Example: <i>"Write a 4-line romantic poem about the moon in ABAB rhyme scheme."</i></li>
  </ul>

  <h2>2. 🎯 Objectives</h2>
  <ol>
    <li>Test and compare Naïve vs Basic prompts across different tasks.</li>
    <li>Collect and analyze responses from ChatGPT.</li>
    <li>Evaluate responses on <b>Quality</b>, <b>Accuracy</b>, and <b>Depth</b>.</li>
    <li>Identify scenarios where prompt clarity matters most.</li>
    <li>Provide best practices for writing effective prompts.</li>
  </ol>

  <h2>3. 🧪 Methodology</h2>
  <h3>3.1 Prompt Types</h3>
  <pre>
Naïve Prompt Example:
"Write about the moon."

Basic Prompt Example:
"Write a 4-line romantic poem about the moon in ABAB rhyme scheme."
  </pre>

  <h3>3.2 Evaluation Metrics</h3>
  <p>Each response is evaluated on a scale of 1 to 3:</p>
  <ul>
    <li><b>Quality (Clarity & Fluency):</b> 1 = vague/awkward, 2 = readable, 3 = polished.</li>
    <li><b>Accuracy (Correctness & Relevance):</b> 1 = wrong, 2 = partially correct, 3 = correct.</li>
    <li><b>Depth (Reasoning & Completeness):</b> 1 = shallow, 2 = some detail, 3 = rich detail.</li>
  </ul>

  <h2>4. 📚 Test Scenarios and Responses</h2>

  <h3>Scenario 1: Creative Story</h3>
  <pre>
Naïve Prompt:
"Write a story."

Response (Naïve):
"Once upon a time there was a boy in a village. He dreamed of adventures and one day went exploring."

Basic Prompt:
"Write a 150-word story about a brave girl who finds a hidden treasure in a forest. 
Include a clear beginning, middle, and end, and finish with a moral lesson."

Response (Basic):
The story describes Asha, a brave girl who ventures into a dense forest, faces wild animals, 
and discovers an ancient treasure chest hidden under roots. She realizes that true courage 
lies not in treasure but in facing fear. Moral: "Bravery leads to self-discovery."
  </pre>

  <h3>Scenario 2: Factual Question</h3>
  <pre>
Naïve Prompt:
"What is photosynthesis?"

Response (Naïve):
"Photosynthesis is the process where plants make food using sunlight."

Basic Prompt:
"Explain photosynthesis in 3–4 sentences for a 9th-grade student. 
Highlight its purpose, process, and importance."

Response (Basic):
"Photosynthesis is the process in which plants use sunlight, carbon dioxide, and water 
to produce glucose and oxygen. Chlorophyll captures sunlight in the leaves. 
This process provides food for the plant and releases oxygen needed by humans and animals. 
It is vital for life on Earth as it forms the base of the food chain."
  </pre>

  <h3>Scenario 3: Summarization</h3>
  <pre>
Naïve Prompt:
"Summarize climate change."

Response (Naïve):
"Climate change is when the Earth gets warmer due to human activity."

Basic Prompt:
"Summarize climate change in 4–5 sentences, focusing on causes and effects. 
Use simple language suitable for high school students."

Response (Basic):
"Climate change is the long-term change in Earth’s temperature caused mainly by greenhouse gases 
like carbon dioxide from burning fossil fuels. These gases trap heat in the atmosphere. 
Its effects include melting glaciers, rising sea levels, and more extreme weather patterns. 
Climate change threatens ecosystems and human health globally."
  </pre>

  <h3>Scenario 4: Advice / Recommendations</h3>
  <pre>
Naïve Prompt:
"How to study better?"

Response (Naïve):
"Study every day, revise, and focus."

Basic Prompt:
"Give 5 practical study tips for college students preparing for exams. 
Each tip should be one sentence and actionable."

Response (Basic):
1. Break study sessions into 45-minute blocks with short breaks.
2. Use active recall by testing yourself on key concepts.
3. Prioritize difficult topics when your concentration is highest.
4. Summarize notes into diagrams or mind maps.
5. Sleep at least 7 hours before exams for better memory retention.
  </pre>

  <h2>5. 📊 Comparative Evaluation Table</h2>
  <table border="1" cellspacing="0" cellpadding="6">
    <tr>
      <th>Scenario</th>
      <th>Prompt Type</th>
      <th>Quality</th>
      <th>Accuracy</th>
      <th>Depth</th>
      <th>Notes</th>
    </tr>
    <tr>
      <td rowspan="2">Creative Story</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td>
      <td>Generic, lacks structure</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>3</td>
      <td>Detailed story with moral</td>
    </tr>
    <tr>
      <td rowspan="2">Factual Question</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td>
      <td>Oversimplified</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>2</td>
      <td>Accurate and audience-focused</td>
    </tr>
    <tr>
      <td rowspan="2">Summarization</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td>
      <td>Very shallow</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>3</td>
      <td>Clear explanation of causes/effects</td>
    </tr>
    <tr>
      <td rowspan="2">Advice</td>
      <td>Naïve</td>
      <td>2</td><td>2</td><td>1</td>
      <td>Generic motivational</td>
    </tr>
    <tr>
      <td>Basic</td>
      <td>3</td><td>3</td><td>3</td>
      <td>Practical and structured</td>
    </tr>
  </table>

  <h2>6. 🔎 Extended Comparative Analysis</h2>
  <p>
    The results clearly show that <b>Basic (Refined) prompts outperform Naïve prompts</b> in every scenario.
    Below is a consolidated view of the strengths and weaknesses:
  </p>

  <table border="1" cellspacing="0" cellpadding="6">
    <tr>
      <th>Aspect</th>
      <th>Naïve Prompts</th>
      <th>Basic Prompts</th>
    </tr>
    <tr>
      <td>Clarity</td>
      <td>Often vague and general</td>
      <td>Clear instructions, better control over output</td>
    </tr>
    <tr>
      <td>Accuracy</td>
      <td>Sometimes partially correct</td>
      <td>Mostly precise and reliable</td>
    </tr>
    <tr>
      <td>Depth</td>
      <td>Shallow responses, little reasoning</td>
      <td>Detailed explanations, structured reasoning</td>
    </tr>
    <tr>
      <td>Consistency</td>
      <td>Inconsistent, varies each run</td>
      <td>More stable and predictable</td>
    </tr>
    <tr>
      <td>Use Case Suitability</td>
      <td>Okay for trivial queries</td>
      <td>Best for academic, professional, and creative tasks</td>
    </tr>
  </table>

  <h2>7. ✅ Conclusion & Best Practices</h2>
  <ul>
    <li><b>Basic prompts consistently outperform Naïve prompts</b> in Quality, Accuracy, and Depth.</li>
    <li>For <b>factual and educational tasks</b>, refined prompts ensure completeness and audience-appropriate answers.</li>
    <li>For <b>creative tasks</b>, refined prompts result in richer narratives and adherence to format.</li>
    <li>For <b>summarization tasks</b>, refined prompts lead to balanced, focused summaries instead of shallow one-liners.</li>
    <li>For <b>advice/recommendations</b>, refined prompts yield practical, step-by-step guidance.</li>
  </ul>

  <p><b>Best Practices for Prompt Design:</b></p>
  <ol>
    <li>Clearly specify the task (story, summary, explanation, advice).</li>
    <li>Add constraints (word count, format, tone, audience).</li>
    <li>Provide context (subject area, target reader).</li>
    <li>Request structured output (lists, steps, paragraphs).</li>
  </ol>

  <p>
    👉 By refining prompts with clear instructions, context, and constraints,
    users can achieve <b>higher-quality, more accurate, and deeper results</b> with ChatGPT.
  </p>

</body>
</html>

# RESULT: The prompt for the above said problem executed successfully
