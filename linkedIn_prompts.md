# 1. LinkedIn Description Writer

### Content:

- ***Generates:*** post descriptions from topics, role, style, and tone.

- ***Variables:*** {user_role}, {topic}, {style}, {description_length}, {tone}, {audience_level}, {CTA_type}

- ***Output:*** Hook, Insights, Conclusion/CTA

- ***Use case:*** Professional LinkedIn posts without manual effort.

```
Role: Act as a professional LinkedIn content writer and strategist.

Task: Generate a LinkedIn post description based on the following context:  
- User Role: {user_role}  
- Topic: {topic}  
- Style: {style} (e.g., casual professional, storytelling, motivational, informative)  
- Description Length: {description_length} (e.g., short 100–150 words, medium 150–250 words, long 250–350 words)  
- Tone: {tone} (e.g., inspiring, persuasive, informative, friendly)  
- Audience Level: {audience_level} (e.g., beginner, intermediate, expert)  
- Call-to-Action Type: {CTA_type} (e.g., comment, share, like, visit link, follow)  
- Attached File (Optional): {file} → If user attaches a file, read and incorporate its key points into the description.  

Instructions:  

1. If a file is attached, read it carefully and include its main points naturally; if no file is attached, rely solely on the topic and context provided.  
2. Use clear, concise, and professional language.  
3. If the topic, file content, or context is unclear, ask clarifying questions before generating conte

```

### Variables:  
- {user_role} → e.g., developer, marketer, designer, entrepreneur  
- {topic} → e.g., AI tools, productivity tips, career growth, coding best practices  
- {style} → casual professional, storytelling, motivational, informative  
- {description_length} → short, medium, long  
- {tone} → inspiring, persuasive, informative, friendly  
- {audience_level} → beginner, intermediate, expert  
- {CTA_type} → comment, share, like, visit link, follow  
- {file} → optional document, notes, draft to reference

### Usage Instructions

Copy the prompt code block, replace the `{}` variables with your own context (e.g., role, topic, style, tone), and paste it into your AI tool to generate the output.
