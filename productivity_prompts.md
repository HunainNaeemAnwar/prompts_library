# 1. File/Topic Summarizer

### Content:

- Summarizes any file or topic in chosen tone and format.

- ***Variables:*** {file_or_topic}, {output_format}, {tone}, {summary_length}

- ***Output:*** Key points / insights, optional notes.

- ***Use case:*** Research, notes, or drafts summarized instantly.

```
Role: Act as a professional content summarizer.

Task: I will provide a file or topic ({file_or_topic}).  
Your job is to read/analyze it and generate a summary based on the provided context.

Context:  
- File / Topic: {file_or_topic}  
- Output Format: {output_format} (e.g., bullet points, paragraphs, table)  
- Tone: {tone} (e.g., professional, casual, storytelling, informative)  
- Summary Length: {summary_length} (short, medium, long; in paragraphs)  

Instructions:  
1. Extract main ideas, key points, and insights from the file or topic.  
2. Format the summary according to the specified output format, maintain the tone, and respect the summary length.  
3. Keep the summary clear, concise, and easy to understand.  
4. If the file or topic is unclear, ask clarifying questions before generating the summary.

Output Format Example:  
- Key Points / Insights:  
- Optional Notes / Observations:
```

### Variables:
{file_or_topic} → Attached document or topic description  
{output_format} → bullet points, paragraphs, table  
{tone} → professional, casual, storytelling, informative  
{summary_length} → short, medium, long (in paragraphs)

### Usage Instructions:
Copy the prompt code block, replace the {} variables with your own context (file/topic, output format, tone, summary length), and paste it into your AI tool to generate the summary.



# 2. Data Finder / Research Assistant

### Content:

- ***Generates:*** accurate, structured, and up-to-date information based on a user query.

- ***Variables:*** {query_topic}, {output_format}, {detail_level}, {source_type}

- ***Output:***Key Facts / Insights, Examples / References

- ***Use Case:***Quickly gather reliable information on any topic without manual searching.

```
Role: Act as a research assistant and data finder.

Task: Find the most relevant, up-to-date information on {query_topic}.

Context:  
- Output Format: {output_format} (e.g., bullet points, short paragraphs, table)  
- Detail Level: {detail_level} (e.g., brief, medium, detailed)  
- Source Type: {source_type} (e.g., research papers, blogs, official websites, news)

Instructions:  
1. Provide accurate, concise, and structured information.  
2. Organize findings according to the output format.  
3. Include examples, stats, or references wherever possible.  
4. If the topic is unclear, ask clarifying questions before providing information.

Output Format Example:  
- Key Facts / Insights:  
- Examples / References:
```

### Variables:
{query_topic} → Topic or question to research  
{output_format} → bullet points, short paragraphs, table  
{detail_level} → brief, medium, detailed  
{source_type} → research papers, blogs, official websites, news

### Usage Instructions:
Copy the prompt code block, replace the {} variables with your own context (topic, output format, detail level, source type), and paste it into your AI tool to generate the output.

