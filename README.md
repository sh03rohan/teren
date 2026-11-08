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
Recorded sounds come from [OpenSFX](https://github.com/OpenTTD/OpenSFX) (the OpenTTD sound set), edited (trimmed, looped, re-encoded) for this game and embedded in `index.html`:
- Rail rolling loop: cut from "Train passby (tape stop)" by Metzik, edited by Wuzzy (CC BY 3.0)
- Locomotive horn: "Locomotive 1 Distant horn" by patchen, edited by Janis Lukss (CC BY 3.0)
- Level crossing bell: "RRCrossing" by Mark_Ian, edited by Wuzzy (CC0)
- Car horn (also pitched for buses, trucks, CNGs and motorbikes): "claxon" by han1, edited by Janis Lukss (CC BY 3.0)
- Cow: "Cow - Moan 2" by Jarred Gib, edited by Wuzzy (CC0)
- Birds: "Bird Noise - 1" and "Bird Noise - 12" by SpaceJoe, edited by Wuzzy (CC0)

The edited versions of these sounds are shared under the same licences. The diesel engine and wheel-on-joint thumps are synthesized in the browser.

### Using your own recordings
Put MP3 files in a `sounds/` folder next to `index.html` and they replace the built-in ones automatically:
`sounds/engine.mp3` (seamless diesel engine loop), `sounds/rail.mp3` (seamless running-train loop), `sounds/horn.mp3` (horn), `sounds/traffic.mp3` (not used yet).
