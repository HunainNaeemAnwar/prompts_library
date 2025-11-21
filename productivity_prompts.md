# 1. File/Topic Summarizer

### Content:

- Summarizes any file or topic in chosen tone and format.

- ***Variables:*** {file_or_topic}, {output_format}, {tone}, {summary_length}

- ***Output:*** Key points / insights, optional notes.

- ***Use case:*** Research, notes, or drafts summarized instantly.

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
{file_or_topic} → Attached document or topic description  
{output_format} → bullet points, paragraphs, table  
{tone} → professional, casual, storytelling, informative  
{summary_length} → short, medium, long (in paragraphs)

### Usage Instructions:
Copy the prompt code block, replace the {} variables with your own context (file/topic, output format, tone, summary length), and paste it into your AI tool to generate the summary.
