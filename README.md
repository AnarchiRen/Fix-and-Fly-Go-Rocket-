# Fix-and-Fly-Go-Rocket- 🚀

A retro space mission design game made for the NASA Space Apps Challenge 2026
(challenge: *Space Mission Design Game*).

## Mission and Role 🌟
You are the pilot of a repair mission. Space weather has damaged three real-world-inspired
spacecraft. Design a rocket on a budget, fly out, diagnose each spacecraft, choose the right
repair, survive an unknown solar event, and report your findings to Mission Control.

**Play:** open `index.html` in any modern browser. No install or internet needed
(the pixel font falls back to a system font offline).

## How to play 🕹️

1. **Mission brief:** read the need, goals, segments and requirements.
2. **Design:** choose a body, engine and interior within a $100M budget. Every part has a
   cost, mass and real trade-off.
3. **Fly:** fly from Earth to the damaged spacecraft (arrow and mini map show the way).
4. **Diagnose:** stay close for 3 seconds to collect telemetry, magnetic-field and radiation
   readings.
5. **Repair:** press Fix and choose the repair that matches the diagnosis. Two wrong
   repairs fail the mission.
6. **Survive the event:** repairing triggers an unknown solar event. Read the clue and buy
   upgrades. Keep your hull above 25%.
7. **Report:** fly into the Earth safe zone (it also restores hull and fuel) to transmit
   the data. Collect stars on the way for extra budget.
8. Two more random events strike on the way: **galactic cosmic radiation** (on the way to the second spacecraft) and **extreme temperature swings** (on the way back to Earth after the third repair). Choose upgrades to protect your rocket.
9. Finish all three to unlock a harder level.

Controls: arrows or WASD to fly, X to scan/fix, R repairs hull (+8, $6), F refuels ($5).
On-screen buttons work on touch devices.

## Educational Value 📚

**It teaches why,** not just right or wrong. Wrong repairs explain the mistake, events give clues instead of answers, and the final report shows which part of your design caused the damage.
**It rewards trying again.** Failure is part of the loop, and players can redesign and compare builds. There’s no single perfect rocket.
**It teaches you consequences** Every option needs to be considered for survival. Sometimes long-term option is expensive
**Facts appear when they’re useful.** A NASA fact shows up right when the matching problem hits.

## How it follows NASA’s mission design process ☄️

The structure is based on NASA’s *Design and Develop Science Missions* webinar
(Systems Engineering Series, March 2025): identify need and goals, define the concept,
define requirements, design, build and verify, implement.

| NASA step | In the game |
|---|---|
| Need and goals | Mission brief |
| Segments (launch, space, ground, user) | Rocket, spacecraft, Earth safe zone, findings |
| Requirements | R1 to R4 shown in the brief |
| Design | Body, engine and interior choice under budget |
| Implement | The flight and repair |
| Verify | End report checks each requirement as MET or NOT MET |

The pilot handles four jobs at once: navigation, spacecraft integrity and repair,
data analysis, and communications with Earth.

## Real data and events behind the game 📊

| Game element | Real basis | Source |
|---|---|---|
| Deep-space radiation rises to about 1.84 mSv/day | Curiosity’s RAD instrument measured about 1.8 mSv/day (1.84 in the detailed data) inside its cruise vehicle on the way to Mars | [1], [2] |
| Safe zone about 0.7 mSv/day | ISS crews receive roughly 0.65 to 0.73 mSv/day, about 100 mSv per six-month stay | [3], [4] |
| Basic shell does almost nothing against cosmic rays; polyethylene is about 15% better, and 50% better against flares | NASA research on plastic shielding versus aluminum | [5], [6] |
| Hydrogen-rich materials shield best; metal can create secondary particles; cosmic rays are stronger when the Sun is quiet; solar particle events cannot be predicted | Review of space radiation research | [3] |
| Sunlight strength rises with 1 / distance² | Inverse-square law of solar flux (standard physics) | none |
| Earth turns once per day and the Sun about once per 25 days, both west to east, with tilts of 23.4° and 7.25° | Standard values. In the game one Earth day is 20 seconds | none |
| The Moon orbits Earth once per 27.3 days and always shows Earth the same face | Standard values. Game orbit is 546 seconds and the distance is shrunk | none |
| Earth observer: failure in October 2003 during a powerful geomagnetic storm; investigators believe charge buildup and an electrical discharge damaged the solar array connectors | Midori-II (ADEOS-II) | [8], [9], [10] |
| Comms constellation: February 2022 geomagnetic storm, 38 of 49 new satellites lost | Starlink | [11] |
| Data relay: temporary shutdown during the October 2003 storms | Kodama relay satellite. The Earth-sensor diagnosis is a game simplification | [9] |
| Galactic cosmic radiation event; extreme temperature swing event | Cosmic rays are too energetic to stop fully; Apollo’s slow “barbecue roll” and multilayer insulation manage temperature swings | [3], general knowledge |
| Mission brief, requirements and verification report | NASA mission design process | [12] |

## Sources for references 📚

1. NASA, “Radiation Measured by NASA’s Curiosity on Voyage to Mars Has Implications for Future Human Missions,” release 13-165, 30 May 2013. Search the title on nasa.gov. A copy is at https://www.sciencedaily.com/releases/2013/05/130530145930.htm
2. D. Hassler, “Space Weather at Mars,” slides hosted by NOAA SWPC, 2016. https://www.swpc.noaa.gov/sites/default/files/images/u33/Hassler_Space_Weather_at_Mars_SWW_talk_29apr16_FINAL.pdf
3. V. De Micco et al., “Radiation environment in exploration-class space missions and plants’ responses relevant for cultivation in Bioregenerative Life Support Systems,” Frontiers in Plant Science, 2022 (open access). https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2022.1001158/full
4. Spaceflight Now, “Curiosity measures radiation on the way to Mars,” 30 May 2013 (ISS about 100 mSv per six-month stay). https://spaceflightnow.com/mars/msl/130530rad/
5. NASA Science@NASA, “Plastic spaceships” article, 2005 (archived). https://webarchive.library.unt.edu/eot2008/20090826113149/http:/science.nasa.gov/headlines/y2005/25aug_plasticspaceships.htm
6. Lawrence Berkeley National Laboratory, “Polyethylene as a Radiation Shielding Standard in Simulated Cosmic-Ray Environments,” 2006. https://www.osti.gov/biblio/918614
7. Star facts cross-checked against star-facts.com (used only to check explanations, no text copied). https://www.star-facts.com
8. JAXA, ADEOS-II “Midori-II” project page. https://www.jaxa.jp/projects/sat/adeos2/index_j.html
9. S. K. Moore, “Extreme Solar Storm Strikes Earth,” IEEE Spectrum, 1 December 2003. https://spectrum.ieee.org/extreme-solar-storm-strikes-earth
10. N. Ahmad et al., “Revisiting the Midori-II satellite anomaly: evidence of electrostatic discharge from SPENVIS simulations,” Advances in Space Research, 2026. https://www.sciencedirect.com/science/article/abs/pii/S0273117725014334
11. T.-W. Fang et al., “Space Weather Environment During the SpaceX Starlink Satellite Loss in February 2022,” Space Weather, 2022 (CC BY 4.0). https://repository.library.noaa.gov/view/noaa/53091
12. NASA, “Design and Develop Science Missions” webinar, Systems Engineering Series, March 2025. https://www.nasa.gov/wp-content/uploads/2025/04/250323-design-and-develop-science-mission.pdf

## Sound 🎶

Credit for 'star', 'mini', 'scorch','thrust', 'win', 'click', 'hit' by Claude (Anthropic LLM).
Credit for 'Bgm' sound by JonasBlakewood (Pixabay).
Credit for 'lose' sound by alphix (Pixabay).
Credit for 'warning' sound by tithuh (Pixaxbay).

## What is simplified 🔎

This is a game, not a simulator.

- The map is not to scale, and the spacecraft do not orbit.
- Costs, masses, thrust, fuel use, event damage and upgrade effects are invented for
  gameplay. Only the proportions (for example, shielding choices and the 1/d² sunlight rule)
  follow real data.
- Body heat limits (2x to 6x Earth sunlight) are estimates.
- In the real events the spacecraft were lost. In the game they can be repaired.
- Mission data is embedded in the game. It does not call live NASA services.

## Use of AI tools 🦾

Game concept, mechanics, research real events and sources and theme by No Game No Life.

Claude (Anthropic LLM) was used to help refine the game design, write the game code (HTML, CSS and JavaScript), and draft
in-game educational text. 
Real-data values were checked against the sources listed above.

No NASA logos, flags or mission identifiers are used.

## Future work 🫱🏻‍🫲🏼

- Team mode with four roles (navigator, engineer, scientist, communications).
- Orbiting spacecraft, inspired by NASA Mission Viz.
- Trajectory planning with NASA GMAT.
- More scenarios from NASA’s DONKI space weather database.
- Art, sound and a tutorial.

## License 🗒️
This project is part of NASA's SPACE APP CHALLENGE 2026. For license information you can check on the website above 
