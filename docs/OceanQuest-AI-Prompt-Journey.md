# 🌊 OceanQuest — My AI Prompt Journey

**The Secret World Under the Ocean**  
**Abdullah Raza · Grade 6 · New Middle East International School**

> **About this guide:** These are polished, reusable prompts reconstructed from our OceanQuest development journey, **not verbatim historical transcripts**. They intentionally name Hugo in the first prompt. For a competition presentation, call them **“My Improved AI Prompts”** and show original chat excerpts separately when discussing what was actually asked.

## Phase 1 — Planning and designing

### Prompt 1 — Plan my website

**Goal:** Define the project, technology, and offline requirements.

> I am a Grade 6 student participating in a school website-building competition.
>
> My project is called **“The Secret World Under the Ocean.”**
>
> I want to build an exciting, educational website using **Hugo (static site generator), Markdown, HTML, CSS, and JavaScript**, with help from ChatGPT.
>
> The website should:
> - Teach visitors about oceans, marine life, geography, ecosystems, and conservation.
> - Include beautiful images, animations, and interactive learning activities.
> - Be easy for children aged 10–12 to understand.
> - Work online through GitHub Pages and completely offline from a USB drive.
> - Require no internet connection or server during the school presentation.
>
> Help me plan the website structure, main sections, interactive features, and development steps.
>
> Keep the implementation simple enough for me to understand and explain to my teachers.

### Prompt 2 — Create a beautiful underwater design

**Goal:** Define the visual identity and user experience.

> Act as a creative website designer.
>
> Help me design a beautiful underwater adventure website called **OceanQuest**.
>
> I want visitors to feel as though they are diving into the ocean.
>
> Use:
> - Ocean-inspired colors, from bright turquoise near the surface to dark blue in the deep ocean.
> - Beautiful marine-life images and underwater illustrations.
> - Floating bubbles, gentle animations, and smooth transitions.
> - Large, easy-to-read headings and colorful interactive cards.
> - A playful but scientifically educational design.
>
> Suggest a homepage layout, navigation, typography, color palette, and animations.
>
> Make the website responsive, accessible, and suitable for a Grade 6 school competition.
>
> All images, fonts, and scripts must be stored locally so the website works offline.

### Prompt 3 — Turn my website into an adventure

**Goal:** Create a memorable learning experience.

> I don't want my ocean website to look like a normal textbook or a collection of articles.
>
> I want it to feel like an exciting underwater expedition.
>
> Help me organize the website into adventures:
>
> 1. Our Blue Planet
> 2. Ocean Explorer's GPS
> 3. Hidden Underwater Landscapes
> 4. Dive Into the Deep
> 5. Amazing Marine Life and Ecosystems
> 6. Save Our Oceans
> 7. Ocean Explorer Challenge
>
> For each adventure, suggest what visitors will learn, curiosity questions, images, interactive activities, and surprising facts.
>
> Make the experience fun, educational, and easy to navigate.

## Phase 2 — Geography and ocean science

### Prompt 4 — Explore ocean geography

> I want geography to be one of the most important parts of OceanQuest.
>
> Help me teach children about:
> - The five named oceans and seven continents.
> - Why approximately 71% of Earth's surface is covered by oceans.
> - The Equator, Prime Meridian, and hemispheres.
> - Latitude and longitude.
> - Ocean trenches, underwater mountains, volcanoes, and continental shelves.
> - How ocean geography affects weather, climate, and marine life.
>
> For every topic, include an easy explanation, a fascinating fact, and an interactive activity.
>
> Compare ocean geography with familiar places on land.
>
> Use scientifically accurate information and provide trustworthy sources such as NOAA, NASA, and UNESCO.

### Prompt 5 — Build an interactive latitude and longitude explorer

> Help me create an interactive geography activity for OceanQuest using HTML, CSS, and vanilla JavaScript.
>
> I want children to understand latitude and longitude by exploring famous ocean locations.
>
> Include:
> - A visual explanation of latitude and longitude.
> - The Equator and Prime Meridian.
> - Northern, Southern, Eastern, and Western Hemispheres.
> - Famous locations such as Challenger Deep, the Great Barrier Reef, and the Mid-Atlantic Ridge.
> - Their approximate geographical coordinates.
> - A mystery-location challenge where visitors guess a place using coordinates.
> - A latitude slider explaining tropical, temperate, and polar regions.
>
> Use a locally stored map or SVG illustration. Do not use Google Maps or any online API.
>
> Make it work offline and explain how the JavaScript works.

### Prompt 6 — Compare the ocean with land

> Create an interactive **Ocean vs Land** learning section for my website.
>
> I want children to discover surprising comparisons such as:
> - Mount Everest's height versus Challenger Deep's depth.
> - How much of Earth is covered by ocean versus land.
> - Underwater mountain ranges versus mountain ranges on land.
> - Water pressure underwater versus air pressure at sea level.
> - Ocean temperatures near the Equator versus the poles.
>
> Use simple explanations, accurate measurements, and animated comparison charts.
>
> Include a “Did You Know?” fact for each comparison.
>
> Make the activity visually interesting and suitable for children aged 10–12.
>
> Implement it using HTML, CSS, and vanilla JavaScript, without external libraries.

### Prompt 7 — Dive through the five ocean zones

> Help me build an interactive ocean-depth explorer.
>
> Visitors should travel through five ocean zones:
>
> 1. Sunlight Zone — 0 to 200 metres
> 2. Twilight Zone — 200 to 1,000 metres
> 3. Midnight Zone — 1,000 to 4,000 metres
> 4. Abyssal Zone — 4,000 to 6,000 metres
> 5. Hadal Zone — deeper than 6,000 metres
>
> As visitors descend:
> - Change the background from bright blue to almost black.
> - Show animals commonly found at each depth.
> - Explain changes in sunlight, pressure, and temperature.
> - Compare depths with familiar landmarks.
> - Display fascinating facts.
>
> Include “Dive Deeper” and “Ascend” buttons.
>
> Use smooth CSS animations and vanilla JavaScript. Make sure all content works offline.

## Phase 3 — Marine life, conservation, and interactive learning

### Prompt 8 — Create a marine-life discovery gallery

> Help me build a colorful, interactive marine-life gallery for OceanQuest.
>
> Include fascinating ocean animals such as blue whale, dolphin, shark, octopus, sea turtle, clownfish, jellyfish, and anglerfish.
>
> For each animal, show:
> - An image or illustration.
> - Its name and habitat.
> - The ocean zone where it is commonly found.
> - An amazing ability or adaptation.
> - A surprising scientific fact.
> - Why it is important to the ecosystem.
>
> When visitors click an animal card, reveal its secret fact with a fun animation.
>
> Store the animal information in Hugo data files so I can easily add more creatures later.
>
> Use local images and make the gallery responsive and accessible.

### Prompt 9 — Teach children how to protect oceans

> Create an interactive section called **Become an Ocean Guardian**.
>
> Explain important threats to oceans, including plastic pollution, coral bleaching, overfishing, climate change, and habitat destruction.
>
> Use simple language and interesting illustrations.
>
> Show how these problems affect marine animals, ocean ecosystems, and people living on land.
>
> Include a small interactive activity where visitors choose actions that help protect the ocean.
>
> End with an encouraging message explaining how children can make a difference.

### Prompt 10 — Create the Ocean Explorer Challenge

> Help me create a fun interactive quiz called **Ocean Explorer Challenge**.
>
> The quiz should test what visitors learned about ocean geography, latitude and longitude, ocean depth zones, marine animals, underwater landforms, and ocean conservation.
>
> Include multiple-choice questions, a progress indicator, instant feedback, and a final score.
>
> When someone finishes, show a fun Ocean Guardian achievement message.
>
> Use vanilla JavaScript without a database or online services.
>
> Make the quiz visually exciting, accessible, and fully functional offline.

## Phase 4 — Building, debugging, and publishing

### Prompt 11 — Build and deploy my Hugo website

> Now help me implement OceanQuest as a complete Hugo website.
>
> Use:
> - Hugo as the static site generator.
> - Markdown and Hugo data files for educational content.
> - Hugo templates for reusable layouts.
> - CSS for responsive design and animations.
> - Vanilla JavaScript for interactive activities.
> - Local images and illustrations.
>
> Provide the complete project structure and working source files.
>
> Configure the website for two environments:
>
> **Development:** Run locally using `hugo server`.
>
> **Online:** Build and publish automatically to GitHub Pages using GitHub Actions at https://raza-abdullah.github.io/ocean-explorer/.
>
> **Offline:** Generate a portable website that can be copied to a USB drive and opened directly using `index.html`.
>
> Pay special attention to relative URLs and compatibility with `file://` browsing.
>
> Include a README with development, build, deployment, and USB instructions.
>
> Explain how to test the website and troubleshoot common problems.

### Prompt 12 — Debug, improve, and explain my website

> Act as my friendly programming teacher and website debugging assistant.
>
> I am a Grade 6 student building OceanQuest with Hugo.
>
> When I share an error message or describe a problem:
>
> 1. Explain what the error means in simple language.
> 2. Identify the most likely cause.
> 3. Suggest the smallest safe fix.
> 4. Show the exact file and code that need to change.
> 5. Give me commands to test the solution.
> 6. Explain what I learned from fixing the problem.
>
> Also help me improve my website by reviewing its design, accessibility, educational accuracy, image loading, and offline compatibility.
>
> Do not rewrite unrelated working code.
>
> When suggesting Hugo changes, make sure the solution is compatible with my installed Hugo version and the version used by GitHub Actions.

## Phase 5 — My AI Build Journey

### Bonus Prompt 13 — Tell the story of how I built OceanQuest

> My name is Abdullah Raza. I am a Grade 6 student at New Middle East International School.
>
> I created an educational website called **OceanQuest — The Secret World Under the Ocean**, with help from ChatGPT.
>
> Help me create a section called **My AI Build Journey**.
>
> I want to explain:
> - How I started with an idea.
> - How I planned the website using AI.
> - Why I chose Hugo.
> - How I added ocean geography and marine-life activities.
> - How ChatGPT helped with HTML, CSS, and JavaScript.
> - How I learned to understand errors and fix problems.
> - How I published the website using GitHub Actions.
> - What I learned about programming and using AI responsibly.
>
> Make the content sound natural for a Grade 6 student.
>
> Include an interactive timeline and examples of prompts.
>
> Also help me prepare a five-minute school presentation showing the website and explaining how ChatGPT helped me build it.
>
> Clearly distinguish the ideas I contributed, the code AI suggested, and the changes I personally tested or improved.

## How to showcase the prompts in OceanQuest

Make an interactive **Prompt Gallery** with each card showing:

- **My prompt:** What I asked ChatGPT.
- **What AI helped create:** The page, feature, or solution.
- **What I learned:** The programming or geography concept I understood.
- **What I tested or changed:** The child's own contribution, where applicable.

**Example card — Prompt 5: Latitude and Longitude**

- **My prompt:** “How can I explore latitude and longitude?”
- **What AI helped create:** An interactive coordinate challenge and latitude explorer.
- **What I learned:** Latitude measures north/south; longitude measures east/west.
- **What I tested or changed:** Add a specific real test or change after doing it.

## Five-minute competition presentation: recommended prompt selection

| Moment | Prompt | What to show |
|---|---|---|
| Starting the project | 1 — Plan my website | Why Hugo and offline access matter |
| Making it beautiful | 2 — Underwater design | Ocean-themed homepage |
| Learning geography | 5 or 6 — Coordinates / comparisons | Interactive geography feature |
| Building the site | 11 — Hugo implementation | Working website and GitHub Pages |
| Solving problems | 12 — Debugging | One real error and how it was fixed |

**Presentation integrity:** These prompts are polished examples of the process. The actual development included discussions comparing Eleventy and Hugo, selecting Hugo for an image-rich site, adding geography, configuring GitHub Pages, and fixing Hugo compatibility warnings. Do not describe polished prompts as exact historical quotes. If a parent or another adult helped, acknowledge that assistance.

---

**OceanQuest website:** https://raza-abdullah.github.io/ocean-explorer/  
**Source repository:** https://github.com/raza-abdullah/ocean-explorer
