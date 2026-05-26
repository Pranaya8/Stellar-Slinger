✨ Stellar Slingers
A cosmic physics-based launcher game for Android

Fling adorable alien creatures across the stars to topple crystal fortresses and defeat the Sentinel army.

Jetpack Compose · Canvas Rendering · Custom Physics Engine · Kotlin

🚀 About
Stellar Slingers is an original physics-based destruction game inspired by the launcher genre — reimagined with a cosmic alien twist. Every visual in the game is rendered procedurally using Jetpack Compose Canvas: parallax starfields, glowing nebulae, crystalline structures, and flashy particle effects — all drawn in code, with zero image assets.

Pull back the slingshot, aim your alien creature, and launch it into enemy fortresses. Each creature has a unique tap-activated ability that can turn the tide of battle. Shatter crystal walls, topple energy barriers, and eliminate every Sentinel to claim victory across 6 handcrafted levels.

🛸 Meet the Creatures
Creature	Element	Ability
🔥 Blazeon	Fire	Tap to explode — sends a shockwave that blasts nearby structures and enemies
🧊 Frostix	Ice	Tap to freeze — slows everything in range and deals cold damage
⚡ Voltara	Plasma	Tap to split — divides into 3 smaller projectiles for spread damage
🌀 Gravix	Gravity	Tap to create a gravity well — pulls surrounding objects inward for 2 seconds

🏰 Levels
#	Name	Theme
1	Crystal Dawn	A gentle introduction — topple a simple crystal tower
2	Frozen Bastion	L-shaped fortress with energy barrier bridges
3	Storm Citadel	A towering pyramid of mixed materials
4	Nebula Gardens	Twin towers connected by a floating bridge
5	Void Fortress	Heavy asteroid-rock walls protecting an inner chamber
6	Cosmic Finale	A multi-section castle with every material and the toughest enemies

✨ Features
Custom 2D Physics Engine — Rigid body simulation with gravity, impulse-based collision response, friction, and sleep detection
Procedural Rendering — Everything drawn on Compose Canvas: parallax stars, glowing nebulae, animated slingshot, creature eyes that track velocity, damage cracks, energy barrier shimmer
Particle Effects — Explosions, ice shatter, electric sparks, gravity swirls, structure debris, flight trails, and victory fireworks
3-Star Rating System — Earn stars based on your score, with bonus points for unused creatures
Persistent Progress — Stars and high scores saved locally via SharedPreferences
Sound Effects — Procedurally generated tones for launches, explosions, ability activations, and victory/defeat
Smooth Camera — Lerp-based camera that follows your creature in flight and pans to the action
3 Structure Materials — Crystal (fragile), Energy Barriers (bouncy, pulsing), Asteroid Rock (heavy, tough)
3 Enemy Types — Scouts (cyclops), Guards (crowned), Commanders (angry eyebrows + extra health)
Landscape Fullscreen — Immersive mode with no system bars

🛠️ Tech Stack
Language: Kotlin
UI Framework: Jetpack Compose (Canvas API for game rendering)
Navigation: Navigation3
Audio: Android ToneGenerator (no audio assets required)
Persistence: SharedPreferences

Min SDK: 24 · Target SDK: 35
📦 Build & Run

# Clone the repo
git clone https://github.com/Pranaya8/stellar-slingers.git
cd stellar-slingers
# Build the debug APK
./gradlew assembleDebug
# Install on a connected device
adb install app/build/outputs/apk/debug/app-debug.apk
Requires JDK 17+ and Android SDK with build-tools 36.
