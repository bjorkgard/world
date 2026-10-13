# Build your own World
All pages: https://bjorkgard.github.io/world/


Fill the yellow blanks with any place you can imagine. A library, a zoo, a shipyard, your own city.

### Blank template
Build a single-file interactive web app (HTML, CSS and JS) using Three.js from a CDN: a live 3D <span style="background-color:yellow;color:#000;">**WHAT IT RUNS**</span> dashboard called "<span style="background-color:yellow;color:#000;">**NAME**</span>" that feels like a strategy game.

WORLD: a low-poly isometric <span style="background-color:yellow;color:#000;">**PLACE**</span> built entirely in code, no external models. <span style="background-color:yellow;color:#000;">**8 to 12 landmarks, buildings and vehicles**</span>. Clean toy-like clay look, soft shadows, one accent colour (<span style="background-color:yellow;color:#000;">**HEX**</span>) on <span style="background-color:yellow;color:#000;">**BACKGROUND**</span>.

LIFE: <span style="background-color:yellow;color:#000;">**the main loop, step by step**</span>. <span style="background-color:yellow;color:#000;">**Other things that move**</span>. Everything gives way so nothing ever overlaps.

INTERACTION: drag to pan, right-drag to rotate, scroll or pinch to zoom. Click any
<span style="background-color:yellow;color:#000;">**OBJECTS**</span> : the camera glides to it and follows if it moves, a ring and label mark it,
and a glass panel shows live stats. An area switcher flies between <span style="background-color:yellow;color:#000;">**4 TO 5 AREAS**</span>.

DASHBOARD: frosted glass panels: top bar (logo, search, area switcher, weather
menu, live clock, alerts, day/night toggle, user), 3 KPI cards ( <span style="background-color:yellow;color:#000;">**KPI 1**</span>, <span style="background-color:yellow;color:#000;">**KPI 2**</span>, <span style="background-color:yellow;color:#000;">**KPI 3**</span>), a right detail panel, a bottom-left <span style="background-color:yellow;color:#000;">**PROCESS**</span> tracker (<span style="background-color:yellow;color:#000;">**6 STEPS**</span>) and a tabbed table (<span style="background-color:yellow;color:#000;">**3 TABS**</span>). Realistic data: <span style="background-color:yellow;color:#000;">**UNITS**</span>.

EXTRAS: seasons (<span style="background-color:yellow;color:#000;">**4 WEATHER MODES**</span>); animated day/night; works on mobile.

### Follow-ups that level it up
- "Add a cinematic mode where the camera slowly glides between the most interesting"
- "Some vehicles still overlap at junctions. Fix the give-way logic so they queue instead."
- "Add a sandstorm weather mode with orange haze, low visibility and blowing particles."
- "Make it run smoothly on a mid-range phone. Use instancing and cut draw calls."

## EXAMPLES
### Railgrid (Opus 5.5 High)
Live: https://bjorkgard.github.io/world/railgrid/

Build a single-file interactive web app (HTML, CSS and JS) using Three.js from a CDN: a live 3D metro rail control dashboard called "Railgrid" that feels like a strategy game.

**WORLD:** a low-poly isometric city slice built entirely in code, no external models. An elevated metro line with pillars, a curved junction, four stations with platforms, escalators and canopies, a depot with maintenance sheds, a river bridge, roads below with traffic, and city blocks. Clean toy-like clay look, one accent colour (#00A86B green) on light grey.

**LIFE:** trains run both directions on a timetable, slow into stations, open doors while passengers board and alight, then depart. Signals change colour ahead of each train. A train enters the depot for washing. Road traffic flows under the viaduct. Nothing ever overlaps.

**INTERACTION:** drag to pan, right-drag to rotate, scroll or pinch to zoom. Click any train, station or signal: the camera glides to it and follows a moving train, a ring and label mark it, and a glass panel shows live stats. An area switcher flies between stations and the depot.

**DASHBOARD:** frosted glass panels: top bar (logo, search, area switcher, weather menu, live clock, alerts, day/night toggle, user), 3 KPI cards (Trains in service, On-time %, Riders today), a right detail panel, a bottom-left journey tracker for the selected train (Depart, In section, Arriving, Doors open, Boarding, Depart) and a tabbed table (Trains, Stations, Signals). Realistic data: train numbers, headway in seconds, platform crowding.

**EXTRAS:** seasons (Clear, Monsoon with wet tracks and slower speeds, Fog, Festival rush), animated day/night with lit carriages and station glow; works on mobile.

### Parkline (Opus 5.5 Medium)
Live: https://bjorkgard.github.io/world/parkline/

Build a single-file interactive web app (HTML, CSS and JS) using Three.js from a CDN: a live 3D theme park dashboard called "Parkline" that feels like a theme park tycoon game.

**WORLD:** a low-poly isometric theme park built entirely in code, no external models. An entrance plaza, a roller coaster with loops, a Ferris wheel, a log flume with a splash drop, a carousel, food courts, a lake with paddle boats, a parade route, a monorail and parking. Clean toy-like clay look, one accent colour (#F43F5E candy pink) on warm cream.

**LIFE:** coaster trains climb, drop and loop; the Ferris wheel turns; logs splash down. Guests walk paths, join queues that grow and shrink, buy food and leave with balloons. A parade moves along its route at set times. The monorail loops above. Guests and service carts never overlap.

**INTERACTION:** drag to pan, right-drag to rotate, scroll or pinch to zoom. Click any ride, queue, food stall or the parade: the camera glides to it and follows if it moves, a ring and label mark it, and a glass panel shows live stats. An area switcher flies between Entrance, Thrill zone, Water zone, Kids zone and Lake.

**DASHBOARD:** frosted glass panels: top bar (logo, search, area switcher, weather menu, live clock, alerts, day/night toggle, user), 3 KPI cards (Guests in park, Average wait, Revenue today), a right detail panel, a bottom-left ride cycle tracker (Loading, Dispatch, Lift, Ride, Brake, Unload) and a tabbed table (Rides, Queues, Stalls). Realistic data: riders per hour, wait minutes, ticket sales.

**EXTRAS:** weather (Sunny, Rain with umbrellas and closed water rides, Windy with coaster holds, Festive night with fireworks); animated day/night with ride lights; works on mobile.

### Apex (Opus 5.5 Max)
Live: https://bjorkgard.github.io/world/apex/

Build a single-file interactive web app (HTML, CSS and JS) using Three.js from a CDN: a live 3D race control dashboard called "Apex" that feels like a strategy game.

**WORLD:** a low-poly isometric racing circuit built entirely in code, no external models. A twisting track with kerbs, run-off areas and barriers, a pit lane with team garages, a race control tower, grandstands full of fans, a paddock with team trucks, a marina section and a tunnel. Clean toy-like clay look, one accent colour (#E10600 racing red) on warm grey.

**LIFE:** twenty cars race on smooth racing lines with overtakes, slipstream and braking into corners. Cars pit and crews change tyres in a quick animated stop. Marshals wave flags at corners. A safety car appears when a car spins into the gravel. Pit lane traffic never overlaps.

**INTERACTION:** drag to pan, right-drag to rotate, scroll or pinch to zoom. Click any car, corner, garage or grandstand: the camera glides to it and follows a moving car, a ring and label mark it, and a glass panel shows live stats. An area switcher flies between Start/finish, Pit lane, Hairpin, Tunnel and Paddock.

**DASHBOARD:** frosted glass panels: top bar (logo, search, area switcher, weather menu, live lap clock, alerts, day/night toggle, user), 3 KPI cards (Lap, Fastest lap, Track temperature), a right detail panel with a mini speed trace, a bottom-left race tracker (Formation, Start, Stint 1, Pit window, Stint 2, Chequered flag) and a tabbed live timing table (Positions, Pit stops, Incidents). Use fictional teams and drivers only.

**EXTRAS:** weather (Dry, Light rain with spray behind cars, Heavy rain with a red flag, Sunset); animated night race with floodlights; works on mobile.