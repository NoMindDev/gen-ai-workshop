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

### Asking for an output structure that can be directly pasted into Excel
_Asking for a "code block"_

10:
```txt
Give me a list of all 20 dzongkhags in Bhutan and their area in square kilometres.
Return the result as a code block that I can paste directly into Excel.

Use exactly two columns:
- Dzongkhag
- Area (sq km)

Use reliable sources, verify the figures, and do not include any extra explanation outside the code block.
```

### MS Excel document
11:
```txt
Create an Excel spreadsheet comparing the Toyota Land Cruiser generations over time.
Include only the mainline Land Cruiser series, exclude Prado and other models.

Use each generation/series as a row label, and include exactly two price columns:

- Original launch price, converted to Bhutanese Ngultrum (BTN)
- That launch price adjusted for inflation to today's value, also in BTN

Use reliable historical pricing and inflation data, and include the launch year for each generation in the row label.
```

### MS Word document
12:
```txt
Create a short Microsoft Word document explaining what each major Toyota Land Cruiser generation
introduced compared with the generation before it.

For each generation, briefly cover the most important new technology, mechanical improvements,
safety features, comfort features, and major design changes. Focus only on the main Land Cruiser series
and exclude Prado models and special one-off variants
```

### MS PowerPoint document
13:
```txt
Create a Microsoft PowerPoint presentation showing the evolution of the Toyota Land Cruiser through its major generations.

Use one slide per major generation. For each, include the years it was produced, a short description of how it
changed from the previous generation, and the most important new features or technologies it introduced.

Keep the slides visual and concise, and focus only on the main Land Cruiser series,
excluding Prado models and special one-off variants.
```


## Deep Research
14:
```txt
Conduct deep research on the current state and future of hydropower in Bhutan.

Cover the following:
- Bhutan's current hydropower capacity and major operational projects
- Projects under construction or planned
- Hydropower's contribution to government revenue, exports, and the wider economy
- Bhutan's electricity trade with India
- Seasonal generation and domestic energy-security challenges
- Environmental and climate-related risks
- Financing and implementation challenges
- Bhutan's long-term hydropower and energy targets
- Opportunities from regional power trade, storage, and diversification into solar or other renewables

Use recent, authoritative sources such as Bhutanese government agencies, project authorities,
multilateral institutions, and reputable research organizations.

Clearly distinguish between current facts, announced plans, and projections.
Include citations for important claims, compare conflicting figures where necessary,
and end with a concise summary of the key opportunities and risks for Bhutan over the next 10 to 15 years.
```

## Image generation (using ChatGPT)
15:
```txt
Generate a realistic image of a hydropower plant in Bhutan, set in a Himalayan valley with steep green mountains,
a fast-flowing river, and Bhutanese landscape features.
Show the plant integrated into the natural environment, with a dam, transmission lines,
and cloudy mountain scenery. Make the image detailed, natural, and visually striking
```


## Image generation (using Gemini)

Log into Gemini
> https://gemini.google.com/

16:
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


## External Document
>https://drive.google.com/file/d/1YOWi-Gfs9spo4kVXoUXJbaA3uadXL432/view?usp=sharing

## Link to paste your image
>https://padlet.com/kuenzangnamyel01/my-fearless-padlet-y7gvnjtefbfg3ekl

## Hallucination

> https://chatgpt.com/

``` txt
Give me 5 quick facts about NRDCL: when it was established, where its headquarters is, its main business activities, how many regional offices it has, and one major project it has carried out.
```

## Gemini Notebook

> https://notebook.google.com/

### Setup Prompt
```text
Imagine I am new to NRDCL. I know very little about the organization, and I want to understand it quickly using the company website.
```

### Audio Prompt
```text
Create a short, podcast-style introduction to NRDCL for someone who has just joined the organization and knows very little about it.
```

### video Prompt
```text
Create a short video overview titled “Understanding NRDCL.
```

### Mind Map Prompt
```text
Create a mind map showing the organizational structure and hierarchy of NRDCL based only on the sources in this notebook.
```

<br> <br>



# Day 2

## Working with Gmail using plugin
```txt
Go to my Gmail account and search my Sent emails for messages where I applied for leave.

Identify each leave application and return a table with these columns:

- Date of leave
- Leave category
- Subject or brief reason

Classify the leave category as either:
- Casual Leave
- Sick Leave

Use the actual leave date mentioned in the email, not just the date the email was sent.

If the leave category is unclear, mark it as 'Unclear' rather than guessing.
Ignore unrelated emails and duplicate applications.
```

## Working with Data in Google Drive using the plugin

### Working with tables in Google Sheets
17:
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
18:
```txt
Go to my Google Drive folder named "Generative AI Workshop" and open the Google Sheet
named "data analysis using plugins" and work with the "dzongkhag electricity" sheet.

Create a grouped bar chart comparing Electricity Consumption (GWh) and Renewable Generation (GWh) for each dzongkhag.

Use Dzongkhag on the horizontal axis and GWh on the vertical axis. Give the chart a clear title and legend,
and place the chart neatly below the data table.
```

---

### Creating reports/documents in Google Docs
19:
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
20:
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



## Gamma 

> https://gamma.app/


### Using Gamma to create presentations

21:
```txt
Create a presentation on the disappointing evolution of the Toyota RAV4 from a cute little fun car
to a monstrous huge SUV that is nearly as big as a Prado, but not really a Prado.
```

22:
```txt
Create a visually engaging 6-slide presentation titled "Mountain Biking in Bhutan."
Cover why Bhutan is well suited for mountain biking, the types of terrain and riding experiences available,
and popular destinations such as Thimphu, Paro, Haa, Punakha, Phobjikha, and Bumthang.
Include examples of forest trails, mountain passes, village routes, and scenic descents.
Highlight the combination of adventure, Himalayan landscapes, local culture, and relatively low-traffic roads.
```

23:
```txt
Create a visually engaging 6-slide presentation titled "Hydropower in Bhutan."
Explain why hydropower is important to Bhutan, how the country's rivers and geography support hydropower development,
and highlight major projects such as Chhukha, Tala, Mangdechhu, and Punatsangchhu-II.
Include Bhutan's role as an electricity exporter, the economic importance of hydropower, current installed capacity,
future expansion plans, and key challenges such as seasonal generation, climate risks, and environmental considerations.
Keep the text concise, use maps, river and dam imagery, and use a clean blue-and-green energy theme.
Use current, reliable information and do not invent statistics. 
Bhutan's installed hydropower capacity is now about 3,500 MW,
and the National Energy Policy 2025 targets 20,000 MW of hydropower capacity by 2040.
```

## AI Automation

### Sample Incoming Email
```txt
Subject: Football Match Tonight at 9:00 PM

Hi Deepshik,

We are planning to have a friendly football match tonight, 18 August, at 9:00 PM.

A few of us will be playing, and we would be happy if you could join us. Please let me know if you are available so that we can confirm the number of players.

Looking forward to the game!

Best regards,
Sonam
```

### n8n Prompt 
```txt
Create an automation that triggers when a new email is received. Use OpenAI to analyze the email and generate a suitable reply, then save that reply as a draft in my email account. Do not send the email automatically.
```

### OpenAI Key
Use the code shared through the WhatsApp.

### Hackathon Submission
>https://padlet.com/kuenzangnamyel01/hackathon-presentation-39wbk74u2oekzwmu

## Lovable

### Website Generation Prompt
```txt
# Personal Portfolio Website

## Build Your Professional Identity with AI

Create a modern personal portfolio website for me.

The website should feel **professional, minimal, and confident**, with a clean layout and subtle modern animations.

---

## 1. Hero Section

Create a strong introduction that includes:

- My name
- A short professional headline
- A one-line description of what I do
- Two buttons:
  - **View My Work**
  - **Contact Me**

### Example Headline

> I build practical AI solutions and digital experiences.

### Example Introduction

> I work at the intersection of AI, automation, software, and digital transformation—turning ideas into useful tools and real-world solutions.

---

## 2. About Me

Create a short personal introduction explaining:

- My background
- My interests
- The type of work I enjoy

Keep the writing **natural and human rather than overly corporate**.

---

## 3. What I Do

Show **3–4 cards** representing my main areas of work:

- Artificial Intelligence
- Automation & AI Workflows
- Software / Product Development
- AI Training & Digital Transformation

Add a short explanation under each area.

---

## 4. Projects

Create a portfolio section containing project cards.

Each project card should include:

- **Project title**
- Short description
- Technologies or tools used
- Image placeholder
- **View Project** button

### Example Projects

- AI Chatbot Assistant
- Smart Email Reply Automation
- AI-powered workflow using n8n
- Generative AI workshop and training materials

---

## 5. Experience / Journey

Create a simple visual timeline showing important:

- Professional milestones
- Projects
- Roles
- Achievements

Keep the timeline clean and easy to understand.

---

## 6. Skills & Tools

Display the technologies and tools I work with in a clean visual grid.

### Examples

- ChatGPT
- OpenAI
- Gemini
- Claude
- n8n
- Python
- JavaScript
- GitHub
- Google Workspace
- APIs
- Automation tools

---

## 7. Contact

Create a simple contact section that includes:

- Email
- LinkedIn
- GitHub
- Contact form

End the section with:

> Have an idea or project in mind? Let’s build something useful.

---

# Visual Style

The website should have the following visual style:

- Modern and minimal
- Premium but approachable
- Dark navy and white color palette
- Subtle green or orange accents
- Large typography
- Plenty of whitespace
- Rounded cards
- Smooth scrolling
- Subtle animations on hover and scroll
- Responsive on both desktop and mobile

### Avoid

- Excessive gradients
- Flashy animations
- Overly futuristic AI imagery
- Cluttered layouts

---

# Navigation

Keep the navigation simple:

`Home | About | Projects | Experience | Contact`

Add:

- A sticky navigation bar
- Smooth scrolling between sections

---

# Important

The website should feel like the **portfolio of a real person working in AI and technology**, not like a startup landing page.

Make the design polished enough for:

- Professional networking
- Job opportunities
- Client work
- Showcasing projects

---

# Suggested Hero Content

## Hi, I’m [Your Name].

### I build AI-powered solutions, automations, and digital products.
```
### Output of the prompt above
> https://auecool.lovable.app/

### Inspiration
> https://yigzin.vercel.app/

> https://www.ugyentech.xyz/

> https://anup-pc.vercel.app/

> https://knthinley.vercel.app/

> https://www.siteinspire.com/websites/

### Link to submit your website
> https://padlet.com/kuenzangnamyel01/website-tyy94ta1kous2ui0

### Voice Prompt
```txt
Kuzuzangpo la. Bhutan’s forests are one of our most valuable natural resources. Protecting them is not only about conserving trees — it is about protecting our environment, communities, and future generations. Together, through responsible management and innovation, we can ensure that Bhutan’s natural resources continue to benefit generations to come.
```
