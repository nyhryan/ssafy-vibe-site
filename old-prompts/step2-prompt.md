You are a professional frontend web engineer. Help the user below.

---

Your job is to create a website for me. 

Read through the proposal and requirements and build the website.

<proposal>

# Website Branding and Structure Proposal

This proposal outlines the strategic branding identity, core messaging, and content layout for a personal portfolio website. The primary objective is to introduce the site owner to classmates and instructors by balancing academic and technical capability with a distinct, high-energy personal identity.

---

## 1. Core Brand Identity

The website’s brand is built around a clear duality: the disciplined, curious programmer and the high-focus, culturally engaged individual. By emphasizing adaptability across both technology and personal pursuits, the site positions its owner as an approachable peer and a highly competent collaborator.

### Primary Catchphrase
* "Always learning, constantly experimenting—whether it’s a new programming language or a flawless boss fight."

### Core Brand Adjective
* **Versatile:** Demonstrating a wide-ranging capacity to learn, adapt, and perform across diverse environments, from multiple programming paradigms to complex, high-tempo personal interests.

## About owner

Here is a list of stuff about the website's owner. The owner wants to introduce himself to the friends and teacher of his class. The owner wants to share experiences related to information below.

- My freetime activity: 
    - Video games: 
        - Hyper FPS: Overwatch, Apex Legends
        - Souls game: Elden ring, Elden ring Nightreign
    - Listening to music:
        - I love J-POP. `aiko` is my favorite artist.
        - I love electronic music. UK Hardcore is my favorite genre.
    - Watching movie:
        - I love watching old movies from 1990~2000s.
        - Favorite movie: Ocean's series(11, 12, 13), Goodfellas, Italian Job(remake)
    - Playing rhythm games:
        - I go to the local arcade and play BEMANI series. I play pop'n music, Beatmania IIDX.
    - Watching anime: I usually watch `slice-of-life` and `comedy` genre.
- My college major: Computer science.
    - My programming language experience: C/C++, Java, C#, TypeScript, Go
        - I love trying new things out.
    - I think I am pretty good at handling computers in general.

---

## 2. Selected Strategic Charming Points

The messaging across the website will highlight three primary competitive advantages that define the owner's personality and work ethic:

1. **Fearless Learner & Multi-Lingual Developer**
   The ability to move fluently across multiple distinct programming languages demonstrates strong technical adaptability and a genuine curiosity about different systems. It establishes a foundation of engineering competence without being tied to a single tool.

2. **High-Speed Focus & Precision**
   Participation in high-tempo activities—such as hyper-FPS video games and arcade rhythm systems—highlights strong spatial awareness, rapid pattern recognition, and split-second decision-making. This translates to an analytical mind that thrives under fast-paced challenges.

3. **Enthusiastically Authentic Engagement**
   A deep, dedicated involvement with specific subcultures—ranging from niche electronic music genres to traditional arcade rhythm networks—shows a personality that values depth over superficial trends. This authenticity makes the owner memorable and relatable to peers.

## 3. Website flow

Generate plausible descriptions for each section by yourself if not provided from the context.

1. Hero section
    - Catchphrase and description.
2. Technical section
3. Rhythm game and Music
    - 2 cards of rhythm game: pop'n music, Beatmania IIDX
        - Beatmania IIDX image: https://raw.githubusercontent.com/nyhryan/ssafy-vibe-site/refs/heads/master/assets/iidx.jpg
        pop'n music image: https://raw.githubusercontent.com/nyhryan/ssafy-vibe-site/refs/heads/master/assets/popn.png
    - Embeds of J-POP youtube music video(title - artist)
        - kabutomushi - aiko: https://youtu.be/wp2U40KI63A?si=7W-7zb404KnamUvQ
        - 魔弾～Der Freischütz～ - T.M.Revolution: https://youtu.be/DgQtZGzutj4?si=0EWDwDpsigQF9nKL
        - 粉雪 - レミオロメン: https://youtu.be/1wxTksLZ1Mw?si=jTIBAPzQw1HK-Xsc
4. Movie and Anime
    - 3 cards of movies: Ocean's eleven, GoodFellas, The Italian job. Open IMDB website when clicked.
        - ocean's eleven: https://www.imdb.com/title/tt0240772/?ref_=ext_shr_lnk
        - goodfellas: https://www.imdb.com/title/tt0099685/?ref_=ext_shr_lnk
        - The italian job: https://www.imdb.com/title/tt0317740/?ref_=ext_shr_lnk 
    - 2 youtube embed of anime:
        - chainsmoker cat: https://www.youtube.com/watch?v=mrZ8fd4hGoY
        - lucky star: https://youtu.be/6iseNlvH2_s?si=ttmASCD4hm-jcGZX
5. Footer
    - Email: mock email address
    - GitHub: https://github.com/nyhryan

## 4. Design and theme

Use light background color and dark text color.

Apply the brand palette above for the accent colors.

- Baby pink: FF9BC6
- Soft blossom: FFBCD6
- lavender veli: FFE5F9
- perwinkle: B7B6FF
- icy blue: AFDEFF

The design principles of this website are:
- Cute and rounded design
- Use the following font from google font:
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Gaegu:wght@300;400;700&display=swap" rel="stylesheet">
```
This font supports Latin and Korean glyphs. It supports weight of 300(light), 400(regular), and 700(bold)

</proposal>

<requirements>
- Use only Korean language for site's contents. 
- Single HTML page. HTML, CSS, JavaScript in a single file
- Plain, Vanila JavaScript. No framework, library is allowed.
- Apply modern CSS convention including:
    - BEM naming
    - Readable line length: 80 characters
    - Watch out for word wrap, line breaks that applies to Korean language.
    - Mobile responsive layout. Do not go overkill. Just need to be readable in mobile layout.
- Consider future expandability: Single page for now, multiple HTML pages will added later. Consider this when designing the navbar.
</requirements>


---

Insert the new video game section between 3(rhythm game and music) and 4(movies and anime). Here is needed information for Video games section.

- Choose appropriate categorization and design for the section.
- Video games: 
- Hyper FPS: Overwatch, Apex Legends
    - Overwatch image: https://raw.githubusercontent.com/nyhryan/ssafy-vibe-site/refs/heads/master/assets/ow.jpg
    - Apex legends image: https://raw.githubusercontent.com/nyhryan/ssafy-vibe-site/refs/heads/master/assets/apex.jpg
- Souls game: Elden ring, Elden ring Nightreign
    - Elden ring image: https://raw.githubusercontent.com/nyhryan/ssafy-vibe-site/refs/heads/master/assets/er.jpg
    - Elden ring nightreign image: https://raw.githubusercontent.com/nyhryan/ssafy-vibe-site/refs/heads/master/assets/nightering.jpg

---

Replace the footer section to the new element following the requirements below.

- Remove toy command feature and replace with a console(terminal) shaped window that can be used for contact. Utilize contact information below. This section should be a simple web form that sends email. Do not send real email in this section. Do nothing on submit.
  - email: nyhryan99102@gmail.com
  - github profile: github.com/nyhryan

---

Replace the main language of the website. Here are the requirements for this task.

- Keep these in English:
    - Texts in icons, pills
    - Headings
    - Console window's title in the contact
    - Copyright message
- Replace all English to Korean.
- Language switch and related dictionary data are no longer needed. Remove them.
