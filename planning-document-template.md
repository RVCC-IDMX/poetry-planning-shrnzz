# Planning Document Template

**Student Name:** [Sahar Naz]  
**Date Completed:** [2025-09-12]  
**AI Tool Used:** [ChatGPT]

## My chosen poem

**Poem:** "The Lake Isle of Innisfree" by W.B Yeats (1890)

**Public domain verification:**
``` text
This poem is public domain. The author died in 1939 which is over 70+ years ago. The poem was published in 1890.
```

**Why I chose this poem:**
``` text
This poem appeals to me because it aligns with my dream of building a homestead. I love gardening and find a lot of peace in being outdoors. I think it will work well with a project for a website because it's short and would fit well in an HTML structure. My interest of a clean and minimalistic aesthetic fits with this poem and would has potential for visual appeal. 
```

**Brief description for design purposes:**
``` text
The poem's theme reflects the speakers need to get out of the urban lifestyle and escape in to the outdoors. While reading the poem, the reader can imagine and feel the emotions of breaking free from something we're so used to, to a more serene environment when the writer describes the dream. some imagery that would influence my design would be earth tone color palettes, gloomy offgrid cabins, flowing streams in the woods, etc.  
```

## HTML guidelines

Based on my AI conversations, here are my simple guidelines for structuring this poem:

**Document structure:**
- [ ] Main heading: I think I will keep the original title of the poem as my main heading because it's descriptive and provides insight of what the poem is about. 
- [ ] Poem container: wrap the entire poem in article then each stanza in span. This will give me the ability to style either each line or the poem as a whole. 
- [ ] Stanza handling: I will use span with display: block; 
- [ ] Line breaks: I will use br or span inside each stanza for semantic grouping 
- [ ] Author attribution: I will credit the author either at the end or the top depending on what suits my design

**Semantic elements to use:**
- [ ] Header: the title of the poem 
- [ ] Main: containers for the selected poem 
- [ ] Footer: credit to the author 
- [ ] [Any other specific elements your poem needs]

**Accessibility considerations:**
- [ ] Heading hierarchy: [Your planned h1, h2, etc.]
- [ ] [Any other accessibility notes from your AI discussion]

## CSS guidelines

Based on my AI conversations, here are my simple design guidelines:

**Colors:**
- Background: #F5F1EA -Isabelline
- Text: #333333 -Deep charcoal
- Accent color: #88B799 -Cambridge blue (will use if needed)
- Why these colors: This color palette reflects heavily on the poems mood, the colors selected will give the reader a feel of the greenery and water which exists on islands. The palette is very calm and easy on the eyes. The colors will foreshadow how the author speaks about his dream of leaving from a muted grey environment to nature. 

**Typography:**
- Heading font: Merriweather- Why: it looks look like a very classic style of font, im choosing this for the heading to show contrast between the two different lifestyles depicted in the poem 
- Body/poem font: Open sans - Why: a little more subtle and high contrast between heading and body; will foreshadow the inner desires of change to something more calm and peaceful i.e. off-grid living 
- Font sizes: Planned approach - 34-42px for heading and 18px for body

**Layout and spacing:**
- Content width: 700-750px
- Stanza spacing: 2rem-3rem
- Overall feel: spacious, calm, minimalistic and inspired by nature

**Simple responsive plan:**
- Mobile: target smaller screens to keep minimalistic design intact
- Desktop: everything will appear spacious and intact on larger screens because of the centered layout

## Key AI conversations and discoveries

### What worked well
**Best prompt and response:**
``` text
The most effective prompt was when I asked ChatGPT for was my design philosophy. I was able to get specifc color palettes and fonts based off the design philosophy provided. 

Prompt: 
I've chosen ""The Lake Isle of Innisfree" by W.B Yeats(1890) for my website project. Here's what the poem is about: 

envisioning an escape from the urban lifestyle to a more slower life in nature. The author describes a cabin and an environment he hopes to be in while he's still living in the city. He feels like the life off grid is the life he should be living in his heart. 

I need to develop a design philosophy that connects the poem's meaning to visual design choices. 
Help me think through: 
1. What emotions or moods does this poem evoke, and how could those translate to visual design elements? 
2. Are there specific images, colors, or textures mentioned in the poem that could inspire a color palette? 
3. What kind of typography personality would match this poem's voice (elegant, bold, playful, serious, etc.)? 
4. Should the layout feel spacious and contemplative, or intimate and cozy? 
5. How can I balance honoring the poem's character with meeting modern web accessibility standards? 

Can you help me draft a 2-3 paragraph design philosophy that connects these literary elements to specific visual design decisions?


Response:

Design Philosophy
The Lake Isle of Innisfree evokes a sense of longing for peace, simplicity, and harmony with nature. Its imagery of a quiet cabin, buzzing bees, and still waters creates a mood of calm retreat from the noise of city life. To reflect this, the website design will favor a clean, minimal aesthetic with generous white space to echo the spaciousness of the imagined retreat. A cool, natural color palette—soft greens for nature, muted blues for water, and warm earth tones for the cabin—will ground the design in the natural imagery of the poem, while subtle textures or gradients can suggest organic materials like wood or rippling water without overwhelming the text.

Typography will carry a gentle but dignified personality. A serif font for the poem itself can capture the poem’s elegance and literary weight, while a clean sans-serif for navigation and supporting content will provide modern readability and accessibility. The pairing will balance tradition with clarity. The layout should feel contemplative rather than crowded: wide margins, generous line spacing, and careful stanza separation will give each line space to breathe, mirroring the unhurried rhythm of life Yeats describes.

At the same time, the design will remain inclusive and accessible. Strong contrast ratios will ensure legibility, and responsive design will adapt the contemplative feel across all devices, from small mobile screens to large displays. By blending natural tones, balanced typography, and accessible structure, the design honors the poem’s yearning for tranquility while presenting it in a professional, modern web format.

```

**Why this worked:**
``` text
I think the description of the poem I provided and the questions asked in the prompt were effective.
```

### What surprised you
**An AI limitation you discovered:**
``` text
AI was sometimes very generic and repetitive with it's response. Sometimes I had to reword questions often because the response was too similar and didn't provide anything different. Starting a new chat helped.

```

**How you worked around it:**
``` text
I kept asking a similar but different question. I would ask to elaborate more or provide other examples. Sometimes I would also compare the responses to other ideas and ask how that would work with my design. When I did that I received more precise answers for what I was looking for. 
```

## Ready to build?

**Do you feel prepared to start coding your poetry website?** Yes

**What are you most confident about?**
``` text
I think the HTML part I'm really confident about. The styling part has always been a challenge for me but planning it out has made me feel a little more ready to face any challenges. 
```

**What might you need to figure out as you go?**
``` text
I feel uncertain about some of design parts like the fonts and colors, I just want the whole thing to flow together and ensure a nice aethetic design. This is something I feel like is something I will figure out as I go. I have solid plan laid out so any touch ups or tweaks a long the way will bring everything together.
```

**Next step:** Start building your poetry website using these guidelines as your reference!