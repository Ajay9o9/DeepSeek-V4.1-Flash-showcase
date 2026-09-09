# Prompts


Shared system prompt, then one user brief per site.

## System

```
You are an expert web designer and frontend engineer.
Create a single polished standalone HTML webpage from the brief.

Return EXACTLY one fenced ```html code block and nothing else.

Rules:
- One self-contained HTML file. CSS and JavaScript inside the file. No build step.
- You may load fonts from a font CDN (such as Google Fonts) via <link>.
- All imagery must be created with CSS, SVG, gradients or canvas. Do NOT link
  to any external images or photo services.
- Realistic copy and content, never lorem ipsum.
- Modern CSS, deliberate typography, spacing and hierarchy.
- The first viewport must look complete at 1440x900.
```

## Fintech dashboard (`web_fintech_dashboard`)

```
Design a premium fintech analytics dashboard for a fictional product called Northstar Wealth.

It should feel like a real high-end SaaS product:
- top navigation with logo, workspace switcher and user avatar
- strong portfolio value hero area
- performance chart as the main visual (draw it with SVG or canvas)
- allocation breakdown
- recent transactions list
- small market indicators
- clear hierarchy between primary and secondary information

Use sophisticated typography, excellent spacing, subtle borders, soft shadows and refined micro-details. Avoid making it look like a generic Bootstrap dashboard.
```

## Architecture portfolio (`web_architecture_studio`)

```
Create a visually striking architecture studio landing page for a fictional studio named FORM/NOIR.

Art direction:
- editorial architecture-magazine aesthetic
- oversized typography
- dramatic asymmetric grid
- large architectural imagery built from CSS gradients, duotone SVG shapes or abstract geometric compositions (no photos)
- minimal navigation
- project metadata and locations
- generous whitespace
- black, warm white and muted stone tones
- subtle hover motion

The first viewport should look like a premium architecture portfolio.
```

## Music player (`web_music_player`)

```
Build a polished desktop music player interface for a fictional app called SONORA.

Include:
- left navigation
- featured album hero
- recently played section
- curated playlists
- track list
- persistent bottom playback bar

Album artwork must be generated locally: gradient covers with SVG shapes or large typographic monograms (no external images).
Focus heavily on composition, typography, album-art treatment and visual depth.
```

## Fashion editorial (`web_fashion_editorial`)

```
Create an editorial fashion landing page for a fictional brand called ATELIER 09.

Design direction:
- luxury fashion magazine
- oversized serif paired with a modern sans-serif
- asymmetrical editorial layout
- minimal navigation
- collection teaser
- campaign statement
- product highlights
- refined footer

Create the visual drama with typography, whitespace, duotone CSS/SVG art and crop-like framing instead of photography. It should feel expensive and sparse.
```

## AI product launch (`web_ai_product_launch`)

```
Create a premium product launch page for a fictional AI model platform called ORBIT AI.

Requirements:
- dramatic hero with large headline
- glowing abstract AI visualization made with pure CSS, SVG or canvas
- compact navigation
- benchmark/stat cards
- capabilities section
- API/code preview block
- enterprise CTA

Avoid the generic purple-gradient AI landing page trope. Use strong typography, carefully controlled gradients, glass/translucent surfaces and a coherent system.
```

## Travel editorial (`web_travel_editor`)

```
Design an immersive travel editorial homepage for a fictional publication called THE NORTH EDIT.

The page should resemble a premium digital travel magazine:
- large destination hero built from layered CSS gradients and SVG landscape silhouettes (no photos)
- editorial headline and short story
- featured destinations
- horizontal story cards
- category navigation
- elegant footer

Typography and composition should be the main design strengths.
```

## Developer tool (`web_developer_tool`)

```
Build the landing page for a fictional developer tool called FLUXTRACE, a fast distributed tracing platform.

Make it feel like a best-in-class developer product:
- crisp dark theme
- technical but highly polished typography
- hero statement
- terminal/code visual with realistic trace spans drawn in HTML/CSS
- performance metrics
- feature sections
- CTA

Use CSS/SVG for any diagrams. Restrained color, strong rhythm, real-looking copy.
```

## Restaurant website (`web_restaurant`)

```
Create a premium restaurant website for a fictional restaurant called CASA ORO.

Style:
- contemporary Mediterranean fine dining
- warm cream, charcoal and olive palette
- elegant serif typography paired with a clean sans-serif
- menu highlights
- chef introduction
- reservation CTA
- location/hours
- refined footer

Evoke food and atmosphere through palette, ornament-free typography and simple SVG illustration rather than photographs. Award-winning feel, strong art direction.
```

## Creative gallery (`web_creative_gallery`)

```
Create an experimental digital art gallery homepage for a fictional gallery called VOID/FORM.

Design goals:
- bold editorial composition
- huge typography
- dark background with one carefully chosen accent color
- artwork grid with unusual proportions — artworks are generative CSS/SVG/canvas compositions you design yourself
- artist names and metadata
- exhibition spotlight
- subtle cursor/hover interactions

This should feel like an award-winning creative-coding website, not a template.
```

## Productivity app (`web_productivity_app`)

```
Create a beautiful productivity application interface for a fictional product called DAYLINE.

A complete desktop app screen, not a marketing page:
- left sidebar
- date navigation
- today's focus hero
- task list
- calendar/timeline
- notes panel
- progress indicators
- quick-add interaction with hover/focus states

Calm, premium aesthetic. Typography, spacing, alignment and information density matter more than decorative effects.
```

## Boutique hotel booking (`web_hotel_booking`)

```
Design a luxury booking homepage for fictional coastal hotel MIREN HOUSE. Include a CSS/SVG ocean hero, availability search, rooms, amenities, local experiences, book-now CTA and refined footer. Use stone, deep blue and coral; make it feel like an independent high-end hotel.
```

## Healthcare portal (`web_healthcare_portal`)

```
Build a calm signed-in patient portal for NORTHSTAR HEALTH. Include next appointment, care team, medications, lab summaries, secure messages, billing shortcut and accessible navigation. Use reassuring copy, excellent contrast and a human clinical palette.
```

## Civic services (`web_civic_services`)

```
Create a modern city-services homepage for LUMEN CITY. Include municipal search, service finder, alerts, permits, waste, transit, payments, events and accessible contact footer. Prioritize wayfinding and clarity with civic blue and warm paper tones.
```

## Real estate search (`web_real_estate`)

```
Design FIELDHOUSE, a polished real-estate discovery interface. Include location search, filters, a CSS/SVG map panel, listing cards, featured property details, saved search and agent contact. Use warm-modern editorial typography and strong information density.
```

## Independent bookstore (`web_bookstore`)

```
Create an online bookstore homepage for MARGIN NOTES. Include search/categories, typographic featured book cover, staff picks, new arrivals, author event, reading list and store footer. Make it literary, tactile and independent rather than a generic ecommerce grid.
```

## Podcast studio (`web_podcast_studio`)

```
Build a premium podcast network homepage for AFTERGLOW. Include featured episode player with SVG waveform, queue, show categories, host profiles, latest episodes, membership CTA and locally generated cover art. Use a dark broadcast palette with one warm accent.
```

## Design conference (`web_event_conference`)

```
Create an energetic conference page for SIGNAL / 26. Include date/city, registration CTA, typographic generative hero, speaker lineup, schedule, venue, ticket tiers and sponsors. Use a dark editorial system with chartreuse or orange accents.
```

## Nonprofit campaign (`web_nonprofit_campaign`)

```
Design a compelling environmental campaign for TIDE / TURN. Include hopeful hero, donation CTA, progress indicator, impact metrics, project stories, volunteer actions, field notes and partner footer. Use CSS/SVG shoreline imagery and humane editorial design.
```

## Sports club (`web_sports_club`)

```
Build a modern homepage for fictional women’s football team NORTHLINE FC. Include next match, results/table, player spotlights, tickets, membership, news and supporter store. Use navy, cream and signal red with CSS/SVG stadium motifs.
```

## Grocery market (`web_grocery_market`)

```
Create a refined grocery delivery homepage for GOODROOT. Include search, delivery location, cart, seasonal produce hero, categories, product cards with add controls, weekly basket and delivery promise. Use botanical colors, paper surfaces and CSS/SVG ingredient art.
```

## Online course (`web_education_course`)

```
Design a signed-in learning dashboard for STUDIO CLASS. Include course progress, next lesson, lesson sidebar, instructor, notes, resources, discussion and assignment milestone. Use calm editorial classroom typography; make it an app screen, not marketing.
```

## Job board (`web_job_board`)

```
Build a polished job discovery homepage for WORKROOM. Include role/location search, recommended jobs with salary and tags, company spotlight, saved search, profile actions, career editorial and trust footer. Use a warm professional system with scan-friendly typography.
```

## Weather atlas (`web_weather_atlas`)

```
Create an immersive weather dashboard called ISOBAR. Include current conditions, forecast, SVG hourly chart, abstract CSS/SVG city map, wind, air quality, daylight and saved locations. Use a dark atmospheric palette and precise instrument-like data visualization.
```

## Biotech lab (`web_biotech_lab`)

```
Design a research landing page for LATTICE BIO. Include molecular SVG/canvas hero, research programs, pipeline timeline, publications, findings, leadership and collaboration CTA. Use ivory, deep green and electric lilac with scientific precision.
```

## Cinema streaming (`web_cinema_streaming`)

```
Create a cinematic streaming homepage for FRAME/ONE. Include featured film hero with local poster art, watch CTA, metadata, continue-watching row, collections, film cards, director spotlight and subscription footer. Use rich dark tones and no external images.
```

## Pet care service (`web_pet_care`)

```
Build a premium pet-care booking page for PAWLINE. Include pet profile, upcoming booking, sitter search, care plans, reviews, trust signals, quick booking and neighborhood footer. Use terracotta, cream, moss and restrained CSS/SVG pet illustrations.
```

## Legal consulting (`web_legal_consulting`)

```
Create a premium legal advisory site for VANTAGE LAW. Include consultation CTA, practice areas, featured insight, expertise metrics, partner profiles, offices and detailed footer. Use ink, parchment and copper with precise modern editorial typography.
```

## Automotive studio (`web_automotive`)

```
Design a high-concept EV launch page for AER / 01. Include CSS/SVG vehicle hero, performance strip, charging experience, interior details, trim cards, reserve CTA and footer. Use near-black, silver and electric blue with controlled motion.
```

## Wellness studio (`web_wellness_studio`)

```
Create a serene scheduling homepage for STILL / FORM. Include daily class schedule, booking CTA, philosophy hero, instructors, memberships, ritual feature, location and footer. Use warm mineral colors, serif headlines and soft CSS/SVG geometry.
```

## Financial advisor (`web_financial_advisor`)

```
Design a premium personal-finance advisory homepage for CLEARWATER CAPITAL. Include trust-led hero, consultation CTA, services, market perspective cards, client journey, team and compliance footer. Use deep ink, parchment and one precise green accent; avoid generic fintech dashboards.
```

## Furniture showroom (`web_furniture_showroom`)

```
Design a polished, distinctive standalone website for a fictional furniture showroom called FURNITURE / SHOWROOM. Include gallery hero, room collections, material swatches, product details, design story and inquiry CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Skincare brand (`web_skincare_brand`)

```
Design a polished, distinctive standalone website for a fictional skincare brand called SKINCARE / BRAND. Include product hero, ingredients, routine steps, product cards, skin philosophy and subscription CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Sneaker drop (`web_sneaker_drop`)

```
Design a polished, distinctive standalone website for a fictional sneaker drop called SNEAKER / DROP. Include countdown, product hero, colorways, technical details, size selector, release story and purchase CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Coffee roaster (`web_coffee_roaster`)

```
Design a polished, distinctive standalone website for a fictional coffee roaster called COFFEE / ROASTER. Include featured roast, origin notes, brew guide, subscription options, product grid and cafe details. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Record label (`web_record_label`)

```
Design a polished, distinctive standalone website for a fictional record label called RECORD / LABEL. Include artist hero, latest release, audio player, artist roster, tour dates and newsletter CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Museum exhibition (`web_museum_exhibition`)

```
Design a polished, distinctive standalone website for a fictional museum exhibition called MUSEUM / EXHIBITION. Include exhibition hero, artist statement, artwork grid, visit details, current programs and ticket CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Theatre program (`web_theatre_program`)

```
Design a polished, distinctive standalone website for a fictional theatre program called THEATRE / PROGRAM. Include season hero, show cards, dates, cast spotlight, venue details, ticket CTA and accessibility information. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## University admissions (`web_university_admissions`)

```
Design a polished, distinctive standalone website for a fictional university admissions called UNIVERSITY / ADMISSIONS. Include welcome hero, application CTA, programs, campus life, deadlines, student stories and contact footer. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Public library (`web_public_library`)

```
Design a polished, distinctive standalone website for a fictional public library called PUBLIC / LIBRARY. Include catalog search, opening hours, events, digital resources, new books and membership CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Digital newsroom (`web_digital_newsroom`)

```
Design a polished, distinctive standalone website for a fictional digital newsroom called DIGITAL / NEWSROOM. Include lead story, section navigation, live updates, article grid, editor picks, newsletter and subscription CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Airline lounge (`web_airline_lounge`)

```
Design a polished, distinctive standalone website for a fictional airline lounge called AIRLINE / LOUNGE. Include destination search, lounge availability, amenities, membership tiers, travel perks and booking CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Hiking guide (`web_hiking_guide`)

```
Design a polished, distinctive standalone website for a fictional hiking guide called HIKING / GUIDE. Include route search, difficulty filters, featured trail, SVG elevation chart, conditions, packing list and save action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Ski resort (`web_ski_resort`)

```
Design a polished, distinctive standalone website for a fictional ski resort called SKI / RESORT. Include snow report, lift status, CSS/SVG trail map, lodging cards, lessons and pass CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Wedding planner (`web_wedding_planner`)

```
Design a polished, distinctive standalone website for a fictional wedding planner called WEDDING / PLANNER. Include countdown, checklist, guest summary, vendor cards, budget progress and event timeline. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Meal planner (`web_meal_planner`)

```
Design a polished, distinctive standalone website for a fictional meal planner called MEAL / PLANNER. Include weekly calendar, recipe cards, grocery list, nutrition summary, servings control and quick-add interaction. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## CRM dashboard (`web_crm_dashboard`)

```
Design a polished, distinctive standalone website for a fictional crm dashboard called CRM / DASHBOARD. Include pipeline board, contacts, activity feed, revenue summary, task list and global search. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Email client (`web_email_client`)

```
Design a polished, distinctive standalone website for a fictional email client called EMAIL / CLIENT. Include folders, inbox rows, reading pane, compose action, labels, search and calendar teaser. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Password manager (`web_password_manager`)

```
Design a polished, distinctive standalone website for a fictional password manager called PASSWORD / MANAGER. Include vault categories, search, password health summary, secure item cards, sharing and extension CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Incident response (`web_incident_response`)

```
Design a polished, distinctive standalone website for a fictional incident response called INCIDENT / RESPONSE. Include active incident banner, service health map, timeline, logs, owners, severity controls and postmortem link. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Fleet logistics (`web_fleet_logistics`)

```
Design a polished, distinctive standalone website for a fictional fleet logistics called FLEET / LOGISTICS. Include SVG vehicle map, live status, route cards, driver list, maintenance alerts and dispatch actions. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Inventory manager (`web_inventory_manager`)

```
Design a polished, distinctive standalone website for a fictional inventory manager called INVENTORY / MANAGER. Include warehouse selector, stock table, reorder alerts, item detail, movement chart and purchase action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Insurance claims (`web_insurance_claims`)

```
Design a polished, distinctive standalone website for a fictional insurance claims called INSURANCE / CLAIMS. Include claim progress hero, document checklist, adjuster contact, incident timeline, coverage summary and upload action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Climate dashboard (`web_climate_lab`)

```
Design a polished, distinctive standalone website for a fictional climate dashboard called CLIMATE / DASHBOARD. Include emissions trend chart, region selector, impact metrics, scenario cards and data-source notes. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Research conference (`web_research_conference`)

```
Design a polished, distinctive standalone website for a fictional research conference called RESEARCH / CONFERENCE. Include conference hero, keynote speakers, call for papers, schedule, tracks, venue and registration CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Community center (`web_community_center`)

```
Design a polished, distinctive standalone website for a fictional community center called COMMUNITY / CENTER. Include today's activities, class calendar, volunteer CTA, room booking, announcements and location details. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Indie game launcher (`web_game_launcher`)

```
Design a polished, distinctive standalone website for a fictional indie game launcher called INDIE / GAME / LAUNCHER. Include featured game hero, game library, updates, friends panel, achievements and launch actions. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Language-learning app (`web_language_learning`)

```
Design a polished, distinctive standalone website for a fictional language-learning app called LANGUAGE-LEARNING / APP. Include daily streak, lesson progress, vocabulary cards, practice CTA, conversation goals and level map. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Sleep tracker (`web_sleep_tracker`)

```
Design a polished, distinctive standalone website for a fictional sleep tracker called SLEEP / TRACKER. Include sleep score, nightly SVG graph, trends, bedtime routine, sound selector and coaching insight. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Auction house (`web_auction_house`)

```
Design a polished, distinctive standalone website for a fictional auction house called AUCTION / HOUSE. Include featured lot, bidding panel, auction timer, provenance, upcoming lots and bidder account action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Subscription box (`web_subscription_box`)

```
Design a polished, distinctive standalone website for a fictional subscription box called SUBSCRIPTION / BOX. Include monthly box hero, contents preview, member benefits, past boxes, product textures and subscribe CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Solar energy (`web_solar_energy`)

```
Design a polished, distinctive standalone website for a fictional solar energy called SOLAR / ENERGY. Include energy calculator, SVG roof illustration, savings metrics, installation steps, testimonials and quote CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Home renovation (`web_home_renovation`)

```
Design a polished, distinctive standalone website for a fictional home renovation called HOME / RENOVATION. Include project hero, CSS before-and-after gallery, services, process timeline, materials and consultation CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Maker marketplace (`web_maker_market`)

```
Design a polished, distinctive standalone website for a fictional maker marketplace called MAKER / MARKETPLACE. Include featured makers, product grid, craft story, categories, seller CTA and shipping promise. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Film festival (`web_film_festival`)

```
Design a polished, distinctive standalone website for a fictional film festival called FILM / FESTIVAL. Include festival hero, screening schedule, film cards, jury, venues, passes and newsletter CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Radio station (`web_radio_station`)

```
Design a polished, distinctive standalone website for a fictional radio station called RADIO / STATION. Include now-playing module, schedule, show archive, host profiles, podcast links and donate CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Photography archive (`web_photo_archive`)

```
Design a polished, distinctive standalone website for a fictional photography archive called PHOTOGRAPHY / ARCHIVE. Include featured series, filterable archive grid, photographer notes, exhibition announcement and contact. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Digital cookbook (`web_cookbook`)

```
Design a polished, distinctive standalone website for a fictional digital cookbook called DIGITAL / COOKBOOK. Include featured recipe, seasonal collections, ingredient search, recipe cards, shopping list and author note. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Gardening app (`web_gardening_app`)

```
Design a polished, distinctive standalone website for a fictional gardening app called GARDENING / APP. Include plant collection, watering schedule, seasonal tasks, sunlight cards, reminders and add-plant action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Bike-share app (`web_bike_share`)

```
Design a polished, distinctive standalone website for a fictional bike-share app called BIKE-SHARE / APP. Include SVG station map, nearby bikes, ride planner, membership, ride history and service alerts. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Transit control (`web_transit_control`)

```
Design a polished, distinctive standalone website for a fictional transit control called TRANSIT / CONTROL. Include route map, service status, platform alerts, incident timeline and operator actions. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Space mission (`web_space_mission`)

```
Design a polished, distinctive standalone website for a fictional space mission called SPACE / MISSION. Include launch countdown, mission objective, SVG spacecraft diagram, timeline, crew and live updates. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Observatory website (`web_observatory`)

```
Design a polished, distinctive standalone website for a fictional observatory website called OBSERVATORY / WEBSITE. Include sky conditions, telescope schedule, gradient astronomy hero, research notes, visitor booking and education. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Archive catalog (`web_archive_catalog`)

```
Design a polished, distinctive standalone website for a fictional archive catalog called ARCHIVE / CATALOG. Include search, collection filters, featured object, metadata panel, digitization story and visit CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Mental wellness app (`web_mental_wellness`)

```
Design a polished, distinctive standalone website for a fictional mental wellness app called MENTAL / WELLNESS / APP. Include mood check-in, guided session cards, personal trends, journal prompt and support resources. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Pharmacy portal (`web_pharmacy`)

```
Design a polished, distinctive standalone website for a fictional pharmacy portal called PHARMACY / PORTAL. Include prescription status, refill action, medication list, delivery tracker, pharmacist chat and health reminders. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Dental clinic (`web_dental_clinic`)

```
Design a polished, distinctive standalone website for a fictional dental clinic called DENTAL / CLINIC. Include appointment CTA, services, team, patient journey, insurance note, location and testimonials. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Childcare portal (`web_childcare_portal`)

```
Design a polished, distinctive standalone website for a fictional childcare portal called CHILDCARE / PORTAL. Include daily check-in, messages, pickup authorization, child notes, meal schedule and calendar. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Alumni network (`web_alumni_network`)

```
Design a polished, distinctive standalone website for a fictional alumni network called ALUMNI / NETWORK. Include member search, events, mentorship CTA, stories, chapter cards and donation action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Volunteer hub (`web_volunteer_hub`)

```
Design a polished, distinctive standalone website for a fictional volunteer hub called VOLUNTEER / HUB. Include opportunity search, causes, impact numbers, upcoming shifts, saved opportunities and organization CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Grant portal (`web_grant_portal`)

```
Design a polished, distinctive standalone website for a fictional grant portal called GRANT / PORTAL. Include application progress, deadlines, document checklist, reviewer messages, budget summary and help panel. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Investor relations (`web_investor_relations`)

```
Design a polished, distinctive standalone website for a fictional investor relations called INVESTOR / RELATIONS. Include company thesis, performance highlights, reports, leadership, sustainability and contact CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Supply-chain dashboard (`web_supply_chain`)

```
Design a polished, distinctive standalone website for a fictional supply-chain dashboard called SUPPLY-CHAIN / DASHBOARD. Include SVG shipment map, milestone table, supplier health, alerts, warehouse cards and export action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Construction bid portal (`web_construction_bid`)

```
Design a polished, distinctive standalone website for a fictional construction bid portal called CONSTRUCTION / BID / PORTAL. Include project overview, bid deadline, document tabs, cost summary, subcontractor list and submit action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## People operations app (`web_hr_people_ops`)

```
Design a polished, distinctive standalone website for a fictional people operations app called PEOPLE / OPERATIONS / APP. Include employee pulse, onboarding tasks, leave calendar, open roles, announcements and manager actions. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Design system docs (`web_design_system`)

```
Design a polished, distinctive standalone website for a fictional design system docs called DESIGN / SYSTEM / DOCS. Include component navigation, version banner, live color tokens, typography samples, code snippets and contribution CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## API documentation (`web_api_documentation`)

```
Design a polished, distinctive standalone website for a fictional api documentation called API / DOCUMENTATION. Include search, version switcher, endpoint categories, quickstart code panel, status indicator and support links. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Security console (`web_security_console`)

```
Design a polished, distinctive standalone website for a fictional security console called SECURITY / CONSOLE. Include threat overview, event timeline, endpoint health, access alerts, severity filters and investigation panel. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Data notebook (`web_data_notebook`)

```
Design a polished, distinctive standalone website for a fictional data notebook called DATA / NOTEBOOK. Include dataset sidebar, notebook cells, SVG result chart, run controls, comments and share action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## AI research lab (`web_ai_research`)

```
Design a polished, distinctive standalone website for a fictional ai research lab called AI / RESEARCH / LAB. Include research hero, paper cards, benchmark visualization, team, open-source links and collaboration CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Robotics lab (`web_robotics_lab`)

```
Design a polished, distinctive standalone website for a fictional robotics lab called ROBOTICS / LAB. Include SVG robot hero, projects, capabilities, field notes, team and partnership CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Immersive exhibition (`web_immersive_exhibition`)

```
Design a polished, distinctive standalone website for a fictional immersive exhibition called IMMERSIVE / EXHIBITION. Include installation hero, visit booking, artist statement, schedule, sensory notes and venue details. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Esports league (`web_esports_league`)

```
Design a polished, distinctive standalone website for a fictional esports league called ESPORTS / LEAGUE. Include live match hero, standings, team cards, upcoming schedule, stream CTA and sponsor area. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Board game studio (`web_board_game`)

```
Design a polished, distinctive standalone website for a fictional board game studio called BOARD / GAME / STUDIO. Include featured game, play overview, components, expansions, reviews, store CTA and community events. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Travel planner (`web_travel_planner`)

```
Design a polished, distinctive standalone website for a fictional travel planner called TRAVEL / PLANNER. Include itinerary timeline, destination cards, SVG route, booking checklist, shared travelers and weather note. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Language magazine (`web_language_magazine`)

```
Design a polished, distinctive standalone website for a fictional language magazine called LANGUAGE / MAGAZINE. Include lead story, language sections, contributor notes, phrase-of-the-day, audio teaser and subscription CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Home cooking (`web_home_cooking`)

```
Design a polished, distinctive standalone website for a fictional home cooking called HOME / COOKING. Include today's recipe, pantry search, meal collections, creator cards, comments and shopping action. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Urban farm (`web_urban_farm`)

```
Design a polished, distinctive standalone website for a fictional urban farm called URBAN / FARM. Include harvest hero, weekly share signup, SVG farm map, seasonal produce, volunteer calendar and impact metrics. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Festival market (`web_festival_market`)

```
Design a polished, distinctive standalone website for a fictional festival market called FESTIVAL / MARKET. Include event hero, vendor directory, schedule, venue plan, ticket CTA and food/music highlights. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Charity annual report (`web_charity_annual_report`)

```
Design a polished, distinctive standalone website for a fictional charity annual report called CHARITY / ANNUAL / REPORT. Include mission hero, impact metrics, story cards, financial transparency, supporters and donate CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```

## Independent publisher (`web_indie_publisher`)

```
Design a polished, distinctive standalone website for a fictional independent publisher called INDEPENDENT / PUBLISHER. Include new releases, author spotlight, catalog filters, submission note, events and bookstore CTA. Make the first viewport complete at 1440x900, use realistic copy, excellent hierarchy and responsive states. Create all imagery with CSS, SVG, gradients or canvas; do not use external images. Avoid generic templates and give the visual system a memorable palette and typography.
```
