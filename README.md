EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1. Accuracy
ChatGPT produces accurate summaries that capture the main idea of the text clearly.

2. Coherence
The summaries are well-structured and logically connected, making them easy to understand.

3. Simplicity
ChatGPT usually uses simple and clear language suitable for general users.

4. Speed
Responses are generated quickly with very little delay.

5. User Experience
The interface is simple and interactive, making it easy for users to input prompts and receive results.

Google Gemini

1. Accuracy
Gemini provides fairly accurate summaries and focuses on the key points of the text.

2. Coherence
The responses are logically organized and maintain a clear flow of ideas.

3. Simplicity
Gemini often gives concise summaries using straightforward language.

4. Speed
Gemini generates responses quickly and efficiently.

5. User Experience
Its integration with Google services provides a smooth and convenient user experience.

Claude

1. Accuracy
Claude produces detailed and accurate summaries with good understanding of context.

2. Coherence
The summaries are very coherent and structured in a logical manner.

3. Simplicity
Claude tends to use clear and readable language, though sometimes slightly more descriptive.

4. Speed
Response speed is generally fast and reliable.

5. User Experience
Claude offers a clean interface and provides helpful and informative responses.


OUTPUT:

Input Text

Artificial Intelligence (AI) is transforming many industries by enabling machines to learn from data and perform tasks that usually require human intelligence. AI technologies such as machine learning, natural language processing, and computer vision are widely used in healthcare, finance, education, and transportation. These technologies improve efficiency, accuracy, and decision-making but also raise concerns about privacy, ethics, and job displacement.

1. Zero-Shot Prompting
Prompt

Summarize the following text in 2 sentences.

ChatGPT Response

Artificial Intelligence enables machines to perform tasks that require human intelligence across various industries. While it improves efficiency and decision-making, it also raises concerns about privacy, ethics, and job displacement.

Gemini Response

AI helps machines learn from data and perform intelligent tasks in sectors such as healthcare, finance, and education. Although it increases efficiency and accuracy, it also introduces ethical and privacy challenges.

Claude Response

Artificial Intelligence technologies like machine learning and computer vision are widely used to improve efficiency in many industries. However, the growth of AI also raises concerns about privacy, ethics, and employment.

2. Few-Shot Prompting
Prompt

Summarize the text.

Example:
Text: Cloud computing allows users to store and access data over the internet.
Summary: Cloud computing provides online data storage and access.

Now summarize this text:
(Insert AI paragraph)

ChatGPT Response

Artificial Intelligence allows machines to analyze data and perform intelligent tasks across industries. It increases efficiency and accuracy but raises concerns about ethics and privacy.

Gemini Response

AI technologies such as machine learning and natural language processing help industries automate tasks and improve decision-making. However, they also bring challenges related to privacy and job displacement.

Claude Response

Artificial Intelligence enables machines to perform complex tasks using data-driven technologies. While it benefits many sectors, it also raises ethical and privacy concerns.

3. Chain-of-Thought Prompting
Prompt

Read the text carefully.
Step 1: Identify the main idea.
Step 2: Identify benefits.
Step 3: Identify concerns.
Step 4: Write a short summary.

ChatGPT Response

Main Idea: AI is transforming industries.
Benefits: Improved efficiency and decision-making.
Concerns: Privacy, ethics, job loss.

Summary: Artificial Intelligence is transforming industries by improving efficiency and decision-making. However, it also raises concerns about privacy, ethics, and job displacement.

Gemini Response

Main Idea: AI adoption in many sectors.
Benefits: Automation, accuracy, better decisions.
Concerns: Ethical and privacy issues.

Summary: AI technologies help industries automate processes and improve productivity. At the same time, they raise important concerns about privacy and ethics.

Claude Response

Main Idea: AI technologies enable machines to perform intelligent tasks.
Benefits: Increased productivity and efficiency.
Concerns: Privacy risks and workforce impact.

Summary: Artificial Intelligence supports industries by enabling machines to analyze data and perform tasks efficiently. However, its growth introduces concerns about privacy and employment.

4. Role-Based Prompting
Prompt

You are a technology journalist. Write a short summary of the text.

ChatGPT Response

Artificial Intelligence is rapidly reshaping industries by enabling machines to analyze data and perform complex tasks. While it improves efficiency and innovation, experts warn about privacy, ethics, and job displacement.

Gemini Response

AI is transforming sectors such as healthcare, finance, and education by improving automation and decision-making. However, its expansion raises debates around privacy and ethical concerns.

Claude Response

Artificial Intelligence is becoming central to modern industries, enhancing productivity and data-driven decision-making. Yet its rapid growth has also sparked concerns regarding privacy and workforce impact.

result:

Different prompting techniques affect the quality and structure of summaries:

Zero-shot: Simple prompt, quick results

Few-shot: Example improves accuracy

Chain-of-thought: Structured reasoning before summarizing

Role-based: Changes tone and writing style

Across ChatGPT, Gemini, and Claude, the summaries are similar but differ slightly in style, wording, and emphasis.



