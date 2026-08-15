# Generative AI Workshop - Materials


# Day 1


Log into ChatGPT
> https://chatgpt.com


## Prompting Techniques

### Clarity

1a:
```txt
Help me prepare for a meeting with my manager.
```

1b:
```txt
Create five talking points for a meeting with my manager about balancing my current workload.
```

### Specificity

2a:
```txt
Plan a team lunch.
```

2b:
```txt
Plan a team lunch for 10 people with a budget of 1000 Ngultrum per person,
within a 10-minute walk of the office, and include at least 2 vegetarian options.
```

### Clarity

3a:
```txt
Draft an email reminding employees to complete their training.
```

3b:
```txt
Draft an email reminding employees to complete their mandatory cybersecurity training by Friday.
Several employees have not yet completed it, so the tone should be polite but firm.
```

### Practice prompts
4a:
```txt
Give me some names for an AI training program.
```

4b:
```txt
Suggest 10 names for an internal employee learning program focused on digital skills and AI.
The names should sound professional, modern, and easy to remember.
Avoid overly technical words and explain the idea behind each name in one sentence.
```

---

5a:
```txt
What laptop should I buy?
```

5b:
```txt
Give me laptop options for office work, video calls, Excel, and light photo editing.
My budget is BTN 80,000, I want at least 16 GB RAM, and battery life matters more than performance.
Explain the main trade-off of each option.
```

---

6a:
```txt
Should I get a smartwatch?
```

6b:
```txt
Help me decide whether a smartwatch is worth buying for someone who mainly wants step tracking,
workout tracking, notifications, timers, and sleep tracking.
I do not care about making calls from my watch. Explain which features would actually be useful
and which are probably unnecessary.
```


## Promptly - prompt refinement extension
> https://www.promptly.fyi/


## Structured outputs

### Bullet points
7:
```txt
Give me five things to check before buying a new laptop.
Use one bullet point per item and keep each explanation to one sentence.
```

### Numbered list
8:
```txt
Explain how to prepare for a job interview in six numbered steps,
from researching the company to following up afterward.
```

### Table
9:
```txt
Compare renting versus buying a car.
Return the answer as a table with the rows: Cost, Flexibility, Maintenance, and Long-term Value.
```

### MS Excel document
10:
```txt
Create an Excel spreadsheet comparing the Toyota Land Cruiser generations over time.
Include only the mainline Land Cruiser series, exclude Prado and other models.

Use each generation/series as a row label, and include exactly two price columns:

- Original launch price, converted to Bhutanese Ngultrum (BTN)
- That launch price adjusted for inflation to today's value, also in BTN

Use reliable historical pricing and inflation data, and include the launch year for each generation in the row label.
```

### MS Word document
11:
```txt
Create a short Microsoft Word document explaining what each major Toyota Land Cruiser generation
introduced compared with the generation before it.

For each generation, briefly cover the most important new technology, mechanical improvements,
safety features, comfort features, and major design changes. Focus only on the main Land Cruiser series
and exclude Prado models and special one-off variants
```

### MS PowerPoint document
12:
```txt
Create a Microsoft PowerPoint presentation showing the evolution of the Toyota Land Cruiser through its major generations.

Use one slide per major generation. For each, include the years it was produced, a short description of how it
changed from the previous generation, and the most important new features or technologies it introduced.

Keep the slides visual and concise, and focus only on the main Land Cruiser series,
excluding Prado models and special one-off variants.
```


## Image generation

Log into Gemini
> https://gemini.google.com/

13:
```txt
Create a professional social media recruitment poster for NRDCL inviting university students
and recent graduates to apply for internship opportunities.

Use a clean, modern corporate design with imagery inspired by Bhutan's forests,
natural resources, and young professionals at work.

Include the headline: "Start Your Career With NRDCL"

Include:
- Internship opportunities now open
- Open to university students and recent graduates
- Gain practical workplace experience
- Application deadline: 30 September 2026
- Apply at: careers.nrdcl.bt

Use green and white as the main colors. Make the text easy to read and
leave enough empty space so the design does not feel crowded.

Format it as a square Instagram and Facebook post.
```


## Hallucination

> https://chatgpt.com/



# Day 2

## Working with Data in Google Drive using the plugin

### Working with tables in Google Sheets
14:
```txt
Go to my Google Drive folder named "Generative AI Workshop" and open the Google Sheet
named "data analysis using plugins" and work with the sheet named "factory log".

Add a new column called "Category". Classify every log entry into exactly one of these two categories
based on the Remarks column:
- Routine maintenance
- Equipment in need of replacement

Then reorder the rows so that entries in the same category are grouped together.

Do not change the existing Log ID, Area, or Remarks values.
```

---

### Creating plots
15:
```txt
Go to my Google Drive folder named "Generative AI Workshop" and open the Google Sheet
named "data analysis using plugins" and work with the "dzongkhag electricity" sheet.

Create a grouped bar chart comparing Electricity Consumption (GWh) and Renewable Generation (GWh) for each dzongkhag.

Use Dzongkhag on the horizontal axis and GWh on the vertical axis. Give the chart a clear title and legend,
and place the chart neatly below the data table.
```

---

### Creating reports/documents in Google Docs
16:
```txt
Go to my Google Drive folder named "Generative AI Workshop" and open the Google Sheet
named "data analysis using plugins" and refer the "dzongkhag electricity" sheet,
to create a short Google Docs report titled "Dzongkhag Electricity Overview".

Summarize the electricity data across the 10 dzongkhags. Highlight:
- Dzongkhags with the highest and lowest electricity consumption
- Dzongkhags with the highest renewable generation
- Interesting differences between electricity consumption and renewable generation
- Any notable patterns in the number of connected households

Include a small summary table of the most important figures. Keep the report concise and suitable for a general business audience.

Base the report only on the data in the sheet and do not invent additional statistics.
```

---

### Creating presentations in Google Slides
17:
```txt
Go to my Google Drive folder named "Generative AI Workshop" and open the Google Sheet
named "data analysis using plugins" and refer the "dzongkhag electricity" sheet,
to create a short Google Slides presentation titled "Electricity Across 10 Dzongkhags".

Create 5 slides (exluding the welcome and thank you slides) covering:
- Title and overview
- Electricity consumption by dzongkhag
- Renewable generation by dzongkhag
- Households connected
- Key observations and takeaways

Use charts where appropriate and keep the slides visual and concise.
Highlight the most noticeable differences between dzongkhags rather than filling the slides with text.

Use only the data contained in the sheet.
```
