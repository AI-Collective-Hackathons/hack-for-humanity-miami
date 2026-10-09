# Hack for Humanity Miami: Challenge Guide

Oct 9, 2026 · @Aman

Build what Miami needs next. On Saturday, Oct 10, 2026, 10 AM to 5 PM at The LAB Miami, you'll build for nearly five hours, demo a working answer to a real Miami problem, and compete in three challenges at once.

Hack for Humanity is [The AI Collective's global civic hackathon](https://fortune.com/press-releases/ai-collective-hack-for-humanity-global-civic-hackathon-2026-08-17/), running in 120 chapters across 50 countries this fall. Miami's edition is also an [MLH Hacktoberfest](https://hacktoberfest-handbook.mlh.com/) Hack Day, so two MLH challenges run alongside our Build for Miami theme: Best Open-Source AI Project and Best Use of Gemma 4.

## The three challenges

Every team enters **Build for Miami** by picking one of its four tracks. The same project can also enter **Best Open-Source AI Project** and **Best Use of Gemma 4** if it meets their requirements, so one build can win in all three.

| Challenge | What it rewards | Prize |
| --- | --- | --- |
| **1. Build for Miami** (theme challenge, 4 tracks) | The strongest answer to a real Miami problem, scored on the judging rubric below | Grand Champion and four Track Champions |
| **2. Best Open-Source AI Project** (MLH Hacktoberfest) | Open-source or open-weight AI as an important part of how the project works | Exclusive Hacktoberfest 2026 Winner DEV Badge & MLH Swag Bag |
| **3. Best Use of Gemma 4** (Google DeepMind) | The most compelling build with Gemma 4 through the Gemini API | MLH partner prize |

## Challenge 1 - Build for Miami

Our theme challenge: pick one of four tracks and build for the people who live here. Every team enters with one primary track.

| Track | The question | You might build |
| --- | --- | --- |
| **01 Four Forces, One City** | How does Miami stay safe and livable as water, air, land and fire push back? | Street-level flood alerts, heat-safety copilots for job sites, storm-ready offline info hubs |
| **02 Wild Miami** | How do we protect the animals we share Miami with, and keep neighbors safe too? | Injured-wildlife reporting agents, roadkill hotspot maps, shelter adoption matchers |
| **03 Brain Gain** | How does Miami keep the talent it attracts? | Career pathway navigators, AI reskilling coaches, newcomer onboarding guides |
| **04 Data to Action** | What does the data say, and what should Miami do about it? | Dashboards, maps, alerts or agents built on open city data |

### Track 01 - Four Forces, One City

Miami lives with four forces - water, air, land and fire - and each one lands hardest on the neighbors with the fewest options. Pick one force, or combine them, and build for the people living with it.

Start from a person, not a technology: "construction crews in Brickell on a heat-advisory day" beats "a heat app." Climate disaster readiness can cut across all four forces.

![Four forces, one city: Water, Air, Land and Fire, with the problems under each](assets/four-forces.png)

Each force lists problems worth solving; the build ideas below show where to start.

**Build ideas by force**

| Force | Build ideas |
| --- | --- |
| **Water** | Street-level flood alerts from tide and rain data; flood-safe routing for commuters and ambulances; a water-quality checker for beaches and canals |
| **Air** | A hurricane-prep copilot in English, Spanish and Haitian Creole; an offline-first info hub for when cell networks go down; air-quality alerts for people with asthma |
| **Land** | A benefits navigator that matches families to the programs they qualify for; a live shelter-bed and food-pantry finder; a traffic-and-flood commute planner |
| **Fire** | Heat-risk alerts for outdoor and construction crews; a cooling-center finder; a climate-risk and home-insurance explainer for homeowners |

**Guidelines**

- Name your force (or forces) and the specific people you serve, in your README and your demo.
- Ground it in Miami: local data, real neighborhoods, and the languages people here speak.
- Show the moment of use: who opens it, when, and what they do next.

### Track 02 - Wild Miami

Miami shares its streets with iguanas, ducks, chickens and Everglades wildlife, and too many of them end up hurt, lost or hit by cars. Build tools that protect animals and the people around them.

| Challenge | Build ideas |
| --- | --- |
| **Urban wildlife and invasive species** (iguanas, pythons) | A photo-to-species agent that tells residents what the animal is, whether it's dangerous, and who to call |
| **Roadkill** | A hotspot map from crash and sighting reports that recommends crossing signs or speed changes |
| **Everglades and endangered species** (Florida panthers, manatees, sea turtles) | A sighting and injury reporting tool that routes each case to the right rescue group |
| **Rescue and shelters** | A lost-and-found pet matcher, a foster and adoption matchmaker, or a hurricane pet-evacuation planner |
| **Cruelty and neglect** | A fast, anonymous reporting flow that captures location, photos and urgency |

**Guidelines**

- Animal welfare comes first: never encourage people to chase, handle or harm wild animals themselves - route them to professionals.
- Know who acts on your output (a rescue group, animal services or a resident) and design that handoff.
- Public health counts: projects that reduce human-wildlife conflict are in scope.

### Track 03 - Brain Gain

Miami attracts talent; keeping it is the hard part. Build tools that help people grow a career here and stay. This track ties into Hack for Humanity's [global themes](https://fortune.com/press-releases/ai-collective-hack-for-humanity-global-civic-hackathon-2026-08-17/): job displacement, technical literacy and accessibility.

| Challenge | Build ideas |
| --- | --- |
| **Graduates leaving after school** | A career pathway navigator that maps a student's skills to Miami employers, internships and mentors |
| **AI reshaping jobs** | A reskilling coach that shows a worker which skills transfer and the shortest path to a growing role |
| **Cost of living** | An affordability planner that weighs salary, rent, commute and flood risk by neighborhood |
| **Newcomers without a network** | An onboarding guide to Miami's communities, meetups and mentors, matched to someone's goals |
| **Access for everyone** | Career tools that work for non-English speakers, people with disabilities, and people without a degree |

**Guidelines**

- Design for one specific person: a graduating senior, a hospitality worker, a relocated engineer.
- Show what would make them stay, and how your tool moves that needle.
- Skip generic job boards: the value is in Miami-specific matching, guidance or community.

### Track 04 - Data to Action

Turn data into a decision: find one insight Miami can act on, make it visible, and show the action it unlocks. You don't need a full app - a sharp analysis, a clear visual and a recommended action is a complete submission.

**What a complete entry shows**

1. **The question** - one Miami problem, stated plainly.
2. **The insight** - one sentence with the number that matters.
3. **The visual** - a chart, map or dashboard anyone can read in 10 seconds.
4. **The action** - who should do what, based on your finding.
5. **The pipeline** - data sources and code in your repo, so judges can reproduce it.

**Recommended tools** (optional - use what you know)

- **Snowflake** - the [CoCo AI coding agent](https://docs.snowflake.com/en/user-guide/cortex-code/cortex-code) for exploring data and writing queries, plus free [Marketplace](https://docs.snowflake.com/en/collaboration/consumer-listings-exploring) and [sample](https://docs.snowflake.com/en/user-guide/sample-data) datasets ([free trial](https://signup.snowflake.com/cortex-code/)).
- **Gemini API** - including [Gemma 4](https://mlh.link/gemma), Google's open-weight model, which can also enter you in Best Use of Gemma 4 and Best Open-Source AI Project.
- **MCP servers and agents** that let people question data in plain language.

Any topic works: flooding, wildlife, housing, talent. Cite every dataset in your README. City partner datasets, if they land, are optional.

## Challenge 2 - Best Open-Source AI Project

**Prize: Exclusive Hacktoberfest 2026 Winner DEV Badge & MLH Swag Bag** (MLH Hacktoberfest)

Build an original project that uses open-source or open-weight AI as an important part of how it works. Teams could create an agent skill, build with an open-weight large or small language model, or build or adapt an open-source model harness. These are examples within one challenge, and teams may combine them.

**Requirements**

- Open-source or open-weight AI must be an important part of the project.
- The project must be published in a public GitHub repository and use an open-source license.
- An agent skill must comply with the [Agent Skill Open Standard](https://agentskills.io/).
- A model-harness entry must include an original implementation or meaningful changes to an existing open-source harness.

**What strong entries show:** substantial technical work, clear value for users, a working demo, and source code, licensing and model details judges can verify. Name the model and link its license or terms in your README ([MLH rules](https://hacktoberfest-handbook.mlh.com/fest-planning-guide/open-source-prize-categories)).

## Challenge 3 - Best Use of Gemma 4

**Presented by Google DeepMind** · Prize: MLH partner prize

It's time to see how much you can build with a lightweight, open model. Gemma 4 packs multimodal intelligence into an open-weights model that you can access through the Gemini API. So, what can Gemma 4 bring to your project?

- **Multimodal Experience:** Work with text and images to create an assistant that understands more of what users share.
- **Focused AI Tools:** Build a focused AI tool for learning, creativity, productivity, or your community.
- **Rapid Prototyping:** Experiment with an open model while using the Gemini API to move quickly from an idea to a working prototype.

Bring your idea to life… what will you build with Gemma 4 today?

**To qualify:** use a Gemma 4 model through the Gemini API, name the model in your README, and show the integration in your code and demo. Gemma 4 is open-weight, so the same project can also enter Best Open-Source AI Project if it meets those requirements.

**Get started:** [Gemma 4 resources](https://mlh.link/gemma) · [Quickstart](https://mlh.link/gemma-quickstart) · [API docs](https://mlh.link/gemma-docs) · [Beginner guide](https://mlh.link/gemma-beginnerguide)

## Build requirements

Build it on the day, ship it in public, and demo it live.

**Teams**

- Solo to 4 people. Solo builders are welcome.
- Want teammates? Say so in your registration, or find the team-matching whiteboard in the lounge at check-in.
- Teams can change until build time starts at 10:45 AM. After that, teams are locked.

**What you can bring**

- Ideas, research and sketches from before the event: yes.
- Libraries, frameworks, APIs and open-source code: yes.
- Any AI tools, including coding agents: yes. List the ones you used.
- Code or project materials written before the event: no. All project work happens during build time, per the [MLH Standard Hackathon Rules](https://github.com/MLH/mlh-policies/blob/main/standard-hackathon-rules.md).

**Open source**

- Your code lives in a public GitHub repo with an open-source license (MIT or Apache-2.0 work well) and stays public after the event to remain prize-eligible.
- Entering Best Open-Source AI Project or Best Use of Gemma 4? Meet their requirements above, and name every model you use in your README.

**Submission checklist** (in OrganizerHQ, by 3:45 PM)

- [ ] Checked in through OrganizerHQ at the door - required to submit and to win
- [ ] Project name and a short description: the problem, who it helps, how it works
- [ ] Public GitHub repo link with an open-source license
- [ ] Technologies used, including AI models
- [ ] Build for Miami track selected, plus any MLH challenges you qualify for
- [ ] Demo URL or video (optional)
- [ ] README with your track, data sources, models used, how to run it, and team members

**Demo**

- 2 minutes per team plus 1 minute of questions. Show the working product, not slides.
- Every team that demos earns an "I Demoed" sticker.

**Code of Conduct**

- The [MLH Code of Conduct](https://github.com/MLH/mlh-policies/blob/main/code-of-conduct.md) applies throughout the venue and every event activity. Harassment is not tolerated; find any organizer if you have a concern.

## Judging rubric

Build for Miami is scored on this rubric: judges score every demo from 1 to 5 on five criteria, and the weighted total decides the winners. Community impact carries the most weight, because that's the point of the day.

| Criterion | Weight | What judges look for |
| --- | --- | --- |
| **Community impact** | 30% | A real Miami problem, a specific group of people, and a believable path to helping them |
| **Working build** | 25% | It runs live and the core flow works end to end. For Data to Action: a reproducible analysis and a visual that answers the question |
| **Use of AI and data** | 20% | AI and data do real work, not decoration, and judges can verify how |
| **Originality and craft** | 15% | A fresh angle or thoughtful technical work, built today |
| **Demo clarity** | 10% | Problem, solution and proof in 2 minutes |

**How winners are picked**

- **Grand Champion (Build for Miami):** the highest weighted score overall.
- **Track Champions (Build for Miami):** the highest score in each track, excluding the Grand Champion, so five different teams win.
- **Best Open-Source AI Project and Best Use of Gemma 4:** judged separately on their own requirements, and stackable with any Build for Miami prize.
- **Ties** go to the higher Community impact score. Organizers verify submissions before demos, and rule or Code of Conduct breaks can mean disqualification.

## Prize categories

Build for Miami crowns five teams, each MLH challenge crowns its own winner, and every builder leaves with swag.

| Prize | Who wins | What you get |
| --- | --- | --- |
| **Build for Miami: Grand Champion** | Highest overall score across all tracks | Arduino boards for the team |
| **Build for Miami: Track Champion** (x4) | Top team in each track | MLH Hacktoberfest swag and a spotlight on our community channels |
| **[Best Open-Source AI Project](https://hacktoberfest-handbook.mlh.com/fest-planning-guide/open-source-prize-categories)** | Best project with open-source or open-weight AI as an important part of how it works | Exclusive Hacktoberfest 2026 Winner DEV Badge & MLH Swag Bag |
| **[Best Use of Gemma 4](https://mlh.link/gemma)** | Best build with Gemma 4 through the Gemini API | MLH partner prize |
| **Every builder** | Everyone who checks in | Hacktoberfest swag (T-shirts, stickers, postcards while supplies last), plus an "I Demoed" sticker when your team presents |

All winning teams may be invited to join a grant-funded project to commercialize what they built, and may be showcased in The AI Collective's global newsletter to 300k+ subscribers ([event page](https://luma.com/h4h-miami)).

## Schedule

Build time runs 10:45 AM to 3:30 PM, and submissions close at 3:45 PM sharp, so submit early. All times Eastern, per the [event page](https://luma.com/h4h-miami).

| Time | What happens |
| --- | --- |
| 10:00-10:20 AM | Check-in through OrganizerHQ, swag, team matching in the lounge |
| 10:20-10:45 AM | Welcome, challenge briefing and MLH Hacktoberfest intro |
| 10:45 AM | Build time starts and teams lock |
| 12:30-2:00 PM | Food available - eat when it suits your team |
| 3:30 PM | Build time ends |
| 3:30-3:45 PM | Submit in OrganizerHQ (deadline 3:45 PM) |
| 3:45-4:30 PM | Demos |
| 4:30-4:45 PM | Judging |
| 4:45-5:00 PM | Winners and closing |

## Resources

Optional starting points, gathered so you spend build time building, not searching. Bring your own data too.

| Resource | Use it for | Tracks |
| --- | --- | --- |
| [Miami-Dade County Open Data Hub](https://gis-mdc.opendata.arcgis.com) | County-wide datasets and maps | All |
| [City of Miami Data Explorer](https://www.miami.gov/Data-Explorer) | City-level datasets and maps | All |
| [NOAA Tides & Currents](https://tidesandcurrents.noaa.gov/) | Tide levels and sea level trends | 01, 04 |
| [National Hurricane Center](https://www.nhc.noaa.gov/) | Storm tracks, advisories and past storms | 01, 04 |
| [AirNow API](https://docs.airnowapi.org/) | Current and forecast air quality | 01, 04 |
| [OpenFEMA](https://www.fema.gov/about/openfema/data-sets) | Disaster declarations, flood insurance claims, assistance data | 01, 04 |
| [U.S. Census data](https://data.census.gov/) | Income, housing, language and demographics by area | 01, 03, 04 |
| [BLS data](https://www.bls.gov/data/) | Jobs, wages and employment trends by metro area | 03, 04 |
| [O\*NET OnLine](https://www.onetonline.org/) | Skills, tasks and career paths by occupation | 03 |
| [iNaturalist](https://www.inaturalist.org/) | Community wildlife sightings with photos and locations | 02, 04 |
| [GBIF](https://www.gbif.org/) | Species occurrence data | 02, 04 |
| [Gemma 4 on the Gemini API](https://mlh.link/gemma) | Open-weight multimodal model ([quickstart](https://mlh.link/gemma-quickstart)) | All |
| [Snowflake CoCo](https://docs.snowflake.com/en/user-guide/cortex-code/cortex-code) | AI coding agent for data work ([free trial](https://signup.snowflake.com/cortex-code/)) | 04 |
| [Hugging Face](https://huggingface.co/models) and [Ollama](https://ollama.com/) | Open-weight models in the cloud or on your laptop | All |
| [Agent Skills standard](https://agentskills.io/) | The spec for packaging open agent skills | All |

**Official links:** [Event page](https://luma.com/h4h-miami) · [MLH Code of Conduct](https://github.com/MLH/mlh-policies/blob/main/code-of-conduct.md) · [MLH Standard Hackathon Rules](https://github.com/MLH/mlh-policies/blob/main/standard-hackathon-rules.md) · [MLH Best Open-Source AI Project rules](https://hacktoberfest-handbook.mlh.com/fest-planning-guide/open-source-prize-categories) · [Hack for Humanity announcement](https://fortune.com/press-releases/ai-collective-hack-for-humanity-global-civic-hackathon-2026-08-17/)
