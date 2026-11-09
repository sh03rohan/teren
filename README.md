# Tuk Tuk Teren: Bangladesh

A 3D train simulator in a single HTML file (three.js r128 from a CDN). Drive the Padma Express around Bangladesh: Dhaka, Comilla, Chattogram, Cox's Bazar, Sylhet, Mymensingh, Rangpur, Dinajpur, Rajshahi, Jashore and Khulna.

Open `index.html` in a browser to play, or visit the deployed site.

## Features
- River bridges modelled on their real counterparts (Hardinge, Jamuna, Bhairab, Kalurghat, Padma, Surma)
- Station buildings after the real stations (Kamalapur shells, Cox's Bazar oyster, Khulna arcade, ...)
- Roads with moving traffic, ramps from the Padma upper deck to the ground
- Hill tunnel with an automatic cinematic camera
- Passengers alighting and boarding
- Day/night and changing weather: clear, clouds, rain, thunderstorm, fog

## Controls
W/S throttle · Space brake · B emergency brake · H horn · O doors · R reverse · 1–7 camera views · L lights · N night · E weather · M map · U sound

## Sound credits
Running-train sound: `sounds/rail.mp3`, a seamless 64-second loop made from "A Train on the Railways" by kokoreli777 (Pixabay, Pixabay Content License), supplied by the project owner. It replaces the built-in rail loop when the game is served from a web server.

Road traffic sound: `sounds/traffic.mp3`, a seamless 65-second loop made from "Traffic Sound" by timvenu1 (Pixabay, Pixabay Content License), supplied by the project owner. Its volume follows how many vehicles are near the camera; when it is loaded the synthesized traffic sounds are switched off.

Countryside birds: `sounds/birds.mp3`, a seamless 104-second loop made from "Birds" by soundreality (Pixabay, Pixabay Content License), supplied by the project owner. It plays by day, fades at dusk, in rain, inside tunnels and beside busy roads.

Rain and thunder: `sounds/rain.mp3` (seamless 18-second rain loop) and `sounds/thunder1-3.mp3` (three thunderclaps), cut from "Rain and Thunder SFX" by JCI-21 (Pixabay, Pixabay Content License), supplied by the project owner. Rain volume follows how hard it is raining; a random clap follows each lightning flash, delayed and softened with distance.

Other recorded sounds come from [OpenSFX](https://github.com/OpenTTD/OpenSFX) (the OpenTTD sound set), edited (trimmed, looped, re-encoded) for this game and embedded in `index.html`:
- Built-in rail rolling loop (fallback when `sounds/rail.mp3` cannot be loaded, e.g. opening the file directly): cut from "Train passby (tape stop)" by Metzik, edited by Wuzzy (CC BY 3.0)
- Locomotive horn: "Locomotive 1 Distant horn" by patchen, edited by Janis Lukss (CC BY 3.0)
- Level crossing bell: "RRCrossing" by Mark_Ian, edited by Wuzzy (CC0)
- Car horn (also pitched for buses, trucks, CNGs and motorbikes): "claxon" by han1, edited by Janis Lukss (CC BY 3.0)
- Cow: "Cow - Moan 2" by Jarred Gib, edited by Wuzzy (CC0)
- Birds: "Bird Noise - 1" and "Bird Noise - 12" by SpaceJoe, edited by Wuzzy (CC0)

The edited versions of these sounds are shared under the same licences. The diesel engine and wheel-on-joint thumps are synthesized in the browser.

### Using your own recordings
Put MP3 files in a `sounds/` folder next to `index.html` and they replace the built-in ones automatically:
`sounds/engine.mp3` (seamless diesel engine loop), `sounds/rail.mp3` (seamless running-train loop), `sounds/horn.mp3` (horn), `sounds/traffic.mp3` (road traffic loop), `sounds/birds.mp3` (countryside ambience loop), `sounds/rain.mp3` (rain loop), `sounds/thunder1.mp3`–`thunder3.mp3` (thunderclaps).

## Map and data credits
- Bangladesh border, coastline and regional land outline: [Natural Earth](https://www.naturalearthdata.com/) 1:10m (public domain), via the [world-atlas](https://github.com/topojson/world-atlas) package, simplified.
- Dhaka MRT Line-6 station names and design (elevated, standard gauge, ~180 m stations), Bhanga Junction (Padma Rail Link) and the six Bengali seasons are based on Wikipedia and Bangladeshi news reports.
