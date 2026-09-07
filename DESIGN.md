# Tripnoria — DESIGN.md

## 1. Brand Overview

**Brand Name:** Tripnoria

**Website Type:** Travel Editorial / Destination Guide / Travel Magazine

**Tagline:**

```text
Explore More. Travel Better.
```

**Primary Content Categories:**

* Destinations
* Travel Guides
* Travel Tips
* Road Trips & Outdoors

Tripnoria should feel like a modern independent travel publication focused on useful destination information, practical planning advice, and visual travel inspiration.

The website should feel:

* fresh
* open
* trustworthy
* adventurous
* modern
* informative
* easy to explore
* visually driven

It should not feel like:

* a booking platform
* a travel agency
* a SaaS product
* a corporate website
* a generic WordPress blog
* a luxury hotel website
* an AI-generated template

---

# 2. Design Direction

Use a:

**Modern Scenic Travel Journal**

visual direction.

The design should combine:

* large travel photography
* spacious layouts
* clean modern typography
* cool white backgrounds
* deep navy branding
* soft blue accents
* simple editorial grids
* lightweight UI
* minimal decoration

The visual identity should communicate:

```text
Sky
Ocean
Road
Mountains
Cities
Exploration
Freedom
Movement
```

Tripnoria should feel noticeably different from Savory Scope.

Savory Scope is warm, paper-like and culinary editorial.

Tripnoria should be:

```text
Cooler
Brighter
Cleaner
More Spacious
More Image-Driven
More Contemporary
```

---

# 3. Color Palette

## Main Background

```css
--color-background: #F7FAFC;
```

Use for:

* main page background
* article pages
* category pages
* large reading areas

This should feel slightly cooler than pure white.

---

## Pure White

```css
--color-surface: #FFFFFF;
```

Use for:

* cards
* navigation
* feature sections
* article blocks

---

## Primary Brand Color

Deep Navy:

```css
--color-primary: #17324D;
```

Use for:

* logo
* headings
* navigation
* footer
* major buttons
* strong UI accents

This is the main Tripnoria brand color.

---

## Secondary Brand Color

Sky Blue:

```css
--color-secondary: #4D94C4;
```

Use for:

* links
* category labels
* hover states
* subtle icons
* highlights
* decorative elements

Do not overuse it.

---

## Accent Color

Sunset Coral:

```css
--color-accent: #E9785D;
```

Use sparingly for:

* Featured labels
* map pin icons
* special highlights
* small callouts
* important interactive accents

Accent color should not become a dominant page color.

---

## Sand Accent

```css
--color-sand: #EDE7DC;
```

Use occasionally for:

* small editorial sections
* quote areas
* highlighted guide sections

Avoid using sand as the main site background.

---

## Main Text

```css
--color-text: #1E2A35;
```

---

## Secondary Text

```css
--color-text-muted: #6D7882;
```

Use for:

* dates
* author information
* descriptions
* metadata
* captions

---

## Borders

```css
--color-border: #DDE5EB;
```

Borders should be subtle.

---

# 4. Typography

Tripnoria should primarily use Sans Serif typography.

Do not use editorial Serif fonts as the dominant visual style.

## Main Heading Font

Preferred:

```text
Manrope
```

Alternative:

```text
Plus Jakarta Sans
```

Use for:

* H1
* H2
* H3
* Hero text
* card titles
* navigation emphasis

Headlines should feel:

* modern
* confident
* clean
* slightly bold

---

## Body Font

Preferred:

```text
Inter
```

Use for:

* body copy
* metadata
* buttons
* navigation
* captions
* forms

---

# 5. Typography Scale

Desktop:

```text
Hero H1: 56–68px
Page H1: 46–56px
Section H2: 34–42px
Article Card H3: 21–26px
Small Card Title: 17–20px
Body Text: 17–18px
Metadata: 13–14px
Navigation: 14–15px
Category Label: 12–13px
```

Mobile:

```text
Hero H1: 38–44px
Page H1: 34–40px
Section H2: 28–32px
Card H3: 20–23px
Body Text: 16–17px
```

Body text:

```css
line-height: 1.7;
```

---

# 6. Layout Principles

The site should feel open and visually calm.

Use:

* large horizontal spacing
* generous whitespace
* wide photography
* clear content hierarchy
* strong grid alignment

Avoid tightly packed layouts.

---

## Main Container

```css
max-width: 1320px;
```

Centered horizontally.

---

## Article Content Width

```css
max-width: 760px;
```

---

## Wide Editorial Blocks

```css
max-width: 1120px;
```

---

# 7. Page Padding

Desktop:

```text
36–48px
```

Tablet:

```text
24–32px
```

Mobile:

```text
18–20px
```

---

# 8. Section Spacing

Desktop:

```text
80–110px vertical spacing
```

Mobile:

```text
52–68px
```

Tripnoria should feel more spacious than Savory Scope.

---

# 9. Header

Header should be simple and modern.

Suggested structure:

```text
TRIPNORIA

Home
Destinations
Travel Guides
Travel Tips
Road Trips & Outdoors
About

Search
```

Desktop layout:

```text
[ TRIPNORIA ]    Navigation                         Search
```

Header guidelines:

* white background
* thin lower border
* no large shadow
* no oversized buttons
* approximately 72–84px high
* logo should remain simple
* navigation should feel spacious

---

# 10. Logo Style

Use text logo initially.

```text
TRIPNORIA
```

Logo style:

* uppercase
* Manrope or similar
* medium-bold
* slightly increased letter spacing
* deep navy

Example:

```css
font-weight: 700;
letter-spacing: 0.12em;
```

Optional small symbol:

* compass
* location pin
* horizon line

But the logo should remain primarily typographic.

Do not create a complicated travel icon logo.

---

# 11. Hero Section

The homepage Hero should be one of the strongest visual elements.

Use a large scenic image.

Good Hero subjects:

* Mediterranean coastline
* mountain road
* European city
* tropical island
* coastal village
* scenic landscape

Preferred image ratio:

```text
16:9
```

or wider.

Recommended desktop layout:

```text
------------------------------------------
|                                        |
|                                        |
|            LARGE TRAVEL IMAGE          |
|                                        |
|                                        |
------------------------------------------

DESTINATIONS

Discover Places Worth the Journey

Explore inspiring destinations, practical travel
guides and ideas for your next adventure.

Explore Destinations →
```

Alternative:

Overlay text on image only if readability remains strong.

Avoid dark full-screen Hero sections.

---

# 12. Homepage Structure

Recommended homepage order:

## Hero

Primary featured story.

---

## Trending Destinations

Display four destination cards.

Example:

```text
Kyoto
Portugal
Vancouver
Bali
```

Card design:

```text
Large Image
Destination Name
Country / Region
```

Do not add unnecessary descriptions.

Destination cards should feel visual and exploratory.

---

## Plan Your Next Trip

Display 3 primary Travel Guides.

Desktop:

```text
3-column grid
```

Cards include:

```text
Image
Category
Title
Short Description
```

---

## Travel Smarter

Use a different layout to avoid repetitive card grids.

Recommended:

```text
Large Featured Article | Three smaller article rows
```

or:

```text
Text List | Feature Image
```

This section should feel practical.

---

## Road Trips & Outdoors

Use one large scenic banner image.

Below it:

3 or 4 article cards.

This section can use a pale blue or light gray background.

---

## Latest Stories

Use a magazine-style list:

```text
Image | Category
      | Title
      | Short Description
      | Date
```

Avoid making every homepage section look identical.

---

# 13. Destination Cards

Destination cards are an important Tripnoria visual component.

Preferred style:

```text
IMAGE

KYOTO
Japan
```

Image should dominate.

Card style:

* very minimal
* no heavy container
* small radius
* no large shadow

Preferred radius:

```css
border-radius: 6px;
```

---

# 14. Article Cards

Standard article card:

```text
IMAGE

CATEGORY

Article Title

Short Description

DATE
```

Cards should usually have:

```css
background: transparent;
```

or white surface when placed on colored sections.

Avoid:

* heavy shadow
* floating glass cards
* thick border
* large rounded corners
* gradient overlays everywhere

---

# 15. Image Style

Photography is one of Tripnoria’s most important brand elements.

Use:

* city streets
* scenic roads
* beaches
* coastlines
* architecture
* landscapes
* mountains
* national parks
* hotels
* cafés
* local markets
* cultural scenes

Images should feel:

```text
Natural
Bright
Realistic
Open
Immersive
Editorial
```

Avoid:

* obviously AI-generated people
* extreme HDR
* overly saturated skies
* fake luxury imagery
* stock-photo business poses
* excessive filters
* text inside images

---

# 16. Image Ratios

Hero:

```text
16:9
```

Feature stories:

```text
16:9
```

Standard article cards:

```text
3:2
```

Destination cards:

```text
4:5
```

or:

```text
3:4
```

Use:

```css
object-fit: cover;
```

for all editorial images.

---

# 17. Category Labels

Examples:

```text
DESTINATIONS
TRAVEL GUIDES
TRAVEL TIPS
ROAD TRIPS & OUTDOORS
```

Style:

```css
font-size: 12px;
font-weight: 600;
letter-spacing: 0.08em;
text-transform: uppercase;
```

Primary color:

```css
color: #4D94C4;
```

Featured labels can use coral.

---

# 18. Buttons

Buttons should be modern but restrained.

Primary:

```text
Explore Destinations →
```

Style:

```css
background: #17324D;
color: #FFFFFF;
border-radius: 5px;
padding: 12px 20px;
```

Secondary:

```text
View All Guides →
```

Can be text-only with arrow.

Avoid pill buttons.

Do not use:

```text
border-radius: 999px;
```

unless used for a very small tag.

---

# 19. Category Pages

Each category page should contain:

```text
CATEGORY NAME

Short category introduction

Featured Story

Latest Articles
```

Example:

```text
DESTINATIONS

Explore cities, coastlines and unforgettable places
around the world.
```

Article grid:

Desktop:

```text
3 columns
```

Tablet:

```text
2 columns
```

Mobile:

```text
1 column
```

---

# 20. Article Page

Recommended article layout:

```text
CATEGORY

Article Title

Short Introduction

By Author Name
Published Date

Featured Image

Article Content
```

The article header should have a lot of whitespace.

Do not place the article H1 inside a heavy card.

---

# 21. Article Body

Article width:

```css
max-width: 760px;
```

Body:

```css
font-size: 18px;
line-height: 1.75;
```

Paragraph spacing:

```text
20–26px
```

H2:

```text
30–36px
```

H3:

```text
23–27px
```

---

# 22. Travel Guide Content Blocks

Travel articles can use structured information blocks.

Example:

```text
QUICK GUIDE

Best Time to Visit
April to June

Recommended Stay
3–4 Days

Getting Around
Metro, walking and local buses
```

Design:

* light blue-gray background
* thin border
* no heavy shadow
* clean icon usage

---

# 23. Itinerary Blocks

For itinerary articles:

```text
DAY 1

Morning
Visit the historic center.

Afternoon
Explore local neighborhoods.

Evening
Dinner and sunset viewpoint.
```

Day labels can use navy background or blue text.

Keep layout simple.

---

# 24. Travel Tips Blocks

For practical articles, allow small callout boxes:

```text
TRAVEL TIP

Book popular attractions in advance during peak season.
```

Style:

```css
background: #F0F6FA;
border-left: 3px solid #4D94C4;
```

Do not overuse callouts.

---

# 25. Related Articles

End each article with:

```text
Continue Exploring
```

Display:

```text
3 related articles
```

Use:

* image
* category
* title

No large description required.

---

# 26. Author Block

Simple design:

```text
Written by

Daniel Brooks

Travel writer covering destinations, city guides
and practical trip planning.
```

Use:

* small avatar
* short bio
* subtle border-top

Avoid large promotional author boxes.

---

# 27. Breadcrumbs

Article pages may use:

```text
Home / Travel Guides / Paris
```

Style:

* small
* muted
* simple

Do not make breadcrumbs visually dominant.

---

# 28. Footer

Footer should be visually stronger than Savory Scope.

Background:

```css
#17324D
```

Text:

```css
#F7FAFC
```

Suggested layout:

```text
TRIPNORIA

Explore More. Travel Better.


EXPLORE
Destinations
Travel Guides
Travel Tips
Road Trips & Outdoors


ABOUT
About Us
Contact Us
Privacy Policy
Terms of Use


© Tripnoria
```

Footer should have generous spacing.

---

# 29. Responsive Design

Must support:

* desktop
* tablet
* mobile

Mobile priorities:

* readable H1
* stacked content
* full-width images
* no horizontal overflow
* simple navigation
* clear spacing
* easy tap targets

Mobile menu:

* hamburger icon
* slide-down or simple overlay navigation

Do not build a complex animated drawer.

---

# 30. Navigation Mobile

Mobile structure:

```text
TRIPNORIA             Menu
```

Menu:

```text
Home
Destinations
Travel Guides
Travel Tips
Road Trips & Outdoors
About
Search
```

---

# 31. Interaction & Motion

Motion should feel smooth but subtle.

Allowed:

* image scale on hover
* underline animation
* button transition
* card image hover
* subtle opacity change

Example:

```css
transition: all 0.2s ease;
```

Image hover:

```css
transform: scale(1.02);
```

Avoid:

* parallax
* animated map backgrounds
* excessive scrolling effects
* text flying into the viewport
* autoplay videos
* complex page transitions

---

# 32. Shadows

Use shadows rarely.

Preferred:

```css
box-shadow: 0 4px 20px rgba(23, 50, 77, 0.06);
```

Only use when needed.

Most content should rely on:

* whitespace
* borders
* typography
* image hierarchy

instead of shadows.

---

# 33. Border Radius

Tripnoria can use slightly more rounding than Savory Scope.

Recommended:

```text
4–8px
```

Maximum for normal cards:

```text
10px
```

Do not use large 20–30px card rounding.

---

# 34. Section Backgrounds

Main:

```css
#F7FAFC
```

White:

```css
#FFFFFF
```

Optional blue section:

```css
#EFF6FA
```

Optional sand section:

```css
#F5F1EA
```

Avoid switching background color in every section.

Use alternate sections selectively.

---

# 35. Search

Search UI should remain simple.

Desktop:

* magnifying glass icon in header

Search page:

```text
Search Tripnoria

[ Search Input ]

Results
```

Do not create a large search engine-style interface.

---

# 36. SEO & Editorial UX

Design must support:

* one H1 per page
* semantic headings
* visible publication date
* author
* category
* alt text
* related stories
* internal links
* readable URLs
* breadcrumbs
* fast loading
* mobile readability

Important content should remain visible without requiring interaction.

---

# 37. Advertising Compatibility

The website should allow advertising later.

Do not create fake ads in the first version.

Keep natural spacing for possible future placements.

Homepage example:

```text
Trending Destinations

[ future ad space ]

Plan Your Next Trip
```

Article example:

```text
Introduction

[ future ad space ]

Article Content

H2

Paragraphs

[ future ad space ]

More Content
```

Ads should never interfere with:

* navigation
* reading
* buttons
* article images
* itinerary blocks

---

# 38. Accessibility

Requirements:

* sufficient contrast
* keyboard focus states
* semantic HTML
* descriptive image alt text
* accessible navigation
* readable font sizes
* correct button elements
* visible links

Avoid placing important text directly inside images.

---

# 39. Design Keywords

Use these keywords when making design decisions:

```text
Travel
Scenic
Fresh
Airy
Modern
Open
Exploration
Adventure
Clean
Editorial
Practical
Visual
Trustworthy
```

Avoid:

```text
Food Magazine
Vintage
Rustic
Luxury
SaaS
Dashboard
Cyberpunk
Neon
Glassmorphism
Heavy Gradient
Corporate
Overly Rounded
Dark UI
```

---

# 40. Visual Difference From Savory Scope

Tripnoria must not look like Savory Scope with different content.

Savory Scope:

```text
Warm Cream
Olive Green
Serif Headlines
Food Photography
Print Magazine Feeling
4:3 Images
Warm Editorial Mood
```

Tripnoria:

```text
Cool White
Deep Navy
Sky Blue
Sans Serif Headlines
Landscape Photography
16:9 Images
Modern Travel Journal Feeling
Open and Scenic Mood
```

These two sites should clearly appear to be separate brands.

---

# 41. Final Design Goal

Tripnoria should look like a genuine English-language travel publication that could eventually contain hundreds of destination guides and travel articles.

The design should remain:

* scalable
* easy to maintain
* SEO friendly
* advertising friendly
* image driven
* mobile friendly
* fast
* visually consistent

When uncertain, prefer:

```text
Large Photography
+
Strong Typography
+
Whitespace
+
Simple Editorial Layout
```

over decorative UI.

Primary design priority:

```text
Photography > Content > Typography > Decoration
```

Tripnoria should make readers feel like they are discovering somewhere new while still being practical enough to help them plan a real trip.
