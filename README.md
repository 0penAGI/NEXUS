# NEXUS AGI 

**CHRONICLES OF THE SLIDE TRAGEDY**

🌐 **Play mini game [NOW](https://0penagi.github.io/NEXUS/)** 
🌐 **USE AI NOW in [TELEGRAM](https://t.me/pshtxkbot)** 
⸻

# CHRONICLES OF THE SLIDE TRAGEDY 

## Overview
**CHRONICLES OF THE SLIDE TRAGEDY - ENHANCED** is a mobile-first bullet-hell narrative experience that explores themes of reality, existence, and cyclical time. Built with pure HTML/CSS/JavaScript, this game offers a unique blend of bullet-hell combat, philosophical dialogue choices, and reality-bending mechanics.

## Features

### Core Gameplay
- **Touch-Optimized Controls**: Designed specifically for mobile devices and Telegram Web Apps
- **Bullet Hell Combat**: Dodge intricate bullet patterns while making narrative choices
- **Multiple Endings**: Your choices determine the outcome and reality state
- **Cycle System**: Each playthrough introduces variations and new challenges

### Reality Systems
- **Determination Mode**: Enhanced abilities through meta-awareness
- **VOID Corruption**: Reality-distorting effects and mechanics
- **Resonance Awakening**: Timeline synchronization powers
- **Chaos Manifestation**: Pattern-breaking madness and abilities

### Technical Features
- **Pure Client-Side**: No external dependencies or server requirements
- **Web Audio API**: Dynamic sound generation
- **SVG Graphics**: Embedded character sprites
- **Responsive Design**: Optimized for various screen sizes
- **Telegram WebApp Integration**: Full support for Telegram Mini Apps

## How to Play

### Controls
- **Movement**: Touch and drag in the battle area to move your soul
- **Dialogue**: Tap choices to progress the story
- **Abilities**: Use the ability buttons (D/S/T/R) during combat
- **Sound**: Toggle audio with the 🔊 button

### Game Mechanics
- **HP Management**: Avoid bullets to preserve your existence points
- **Choice System**: Dialogue choices affect story progression and character stats
- **Phase System**: Combat intensifies as you advance through phases
- **Reality Modifiers**: Random effects that alter bullet behavior each cycle

## Character Stats
- **LV**: Level indicator
- **HP**: Health points
- **DT**: Determination (meta-awareness)
- **VOID**: Reality corruption level
- **RS**: Resonance with alternate timelines
- **DE**: Dark Energy accumulation
- **XDUST**: Reality particles
- **CHAOS**: Entropy and pattern-breaking potential

## Installation & Deployment

### Local Development
1. Clone or download the HTML file
2. Open in any modern web browser
3. For mobile testing, use browser developer tools or deploy to a web server

### Telegram WebApp
1. The game automatically detects Telegram WebApp environment
2. Deploy to any web hosting service
3. Configure your Telegram bot to point to the game URL

### Progressive Web App
The game is PWA-ready and can be installed on mobile devices for app-like experience.

## Browser Compatibility
- Chrome/Chromium (mobile & desktop)
- Safari (iOS)
- Firefox
- Edge
- Telegram in-app browser

## Technical Details

### Architecture
- Single HTML file containing all CSS, JavaScript, and SVG assets
- Modular JavaScript with clear separation of game systems
- CSS animations and transitions for visual effects
- Touch event handling with proper prevention

### Performance Considerations
- Efficient bullet management with object pooling
- Limited DOM manipulations for smooth animations
- Audio context management for mobile performance
- Memory-efficient cycle system

## Customization

### Difficulty Adjustment
Modify these variables in the JavaScript:
- `bulletInterval` timing
- `phaseDuration` values
- Damage values in `takeDamage()`
- Bullet speed multipliers

### Content Expansion
- Add new characters to the `sprites` object
- Create new bullet patterns following existing templates
- Extend dialogue trees in the `scenes` array
- Add new reality modifiers to the `realityModifiers` array

## Credits & Licensing

### Credits
- Created by 0penAGI
- Inspired by Undertale/Deltarune (fan project)
- All original Undertale concepts belong to Toby Fox

### License
This is a non-commercial fan project. Please respect the original creator's rights and share responsibly.

## Support
For issues, suggestions, or contributions:
1. Check browser console for errors
2. Ensure mobile touch events are not being blocked
3. Verify audio autoplay policies on your device
4. Test in multiple environments for compatibility
# Chronicles of the Slide Tragedy - Complete Guide

## 🎮 Game Overview

This is an UNDERTALE-inspired bullet hell game with existential themes, featuring procedural generation, cycle-based progression, and reality-bending mechanics.

---

## 📊 Core Systems

### 1. Player Stats
- **HP**: Health points (starts at 20)
- **LV**: Level (starts at 1)
- **DT**: Determination (gained by questioning reality)
- **VOID**: Void level (increases with wrong choices)
- **RS**: Resonance (multiplier for abilities)
- **DE**: Dark Energy (corruption metric)
- **XDUST**: Special currency from "Night" phase
- **CHAOS**: Chaos level (final phase metric)

### 2. Abilities (Keyboard & Touch)
- **D - Dash**: Quick movement (Cooldown: 120 frames)
- **S - Shield**: Block bullets for 2s (Cooldown: 300 frames)
- **T - Time Slow**: Slow time to 50% (Cooldown: 480 frames)
- **R - Resonance Burst**: Clear all bullets (Cooldown: 600 frames)

---

## 🎯 Gameplay Loop

### Phases
1. **Dialogue Phase**: Read character story, make choices
2. **Choice Phase**: Select from 3 options (Arrow keys + Enter, or tap)
3. **Bullet Hell Phase**: Dodge projectiles (WASD/Arrows or touch)
4. **Progression**: Advance through 8+ encounters

### Choice System
Each scene has 3 choices:
- **Choice 1**: Usually "safe" but boring
- **Choice 2**: ✅ CORRECT - Questions reality, gains DT
- **Choice 3**: Attack - Takes damage, gains VOID

---

## 👾 Enemies & Encounters

### 1. Flowey
- **Pattern**: Existential Circle (6 bullets, radial)
- **Correct Choice**: "Question existence"
- **Effect**: Unlocks meta-awareness

### 2. Toriel
- **Pattern**: Void Wave (4 horizontal waves)
- **Correct Choice**: "Seek continuity"
- **Effect**: Memory recognition

### 3. Papyrus
- **Pattern**: Chaos Bones (falling bones)
- **Correct Choice**: "Acknowledge the reset"
- **Effect**: +5 Determination

### 4. Undyne
- **Pattern**: Determination Spears (horizontal volleys)
- **Correct Choice**: "Resist entropy"
- **Effect**: Soul burns brighter

### 5. Sans
- **Pattern**: Void Bones (orbiting bullets)
- **Correct Choice**: "Accept impermanence"
- **Effect**: Fundamental shift

### 6. Ocean
- **Pattern**: Resonance Waves (upward waves)
- **Correct Choice**: "Dive into the lagoon"
- **Effect**: +Resonance

### 7. Night
- **Pattern**: Explosion Pattern (radial explosions)
- **Correct Choice**: "Reorganize the dust"
- **Effect**: +10 XDUST

### 8. Chaos
- **Pattern**: Chaos Storm (random movements)
- **Correct Choice**: "Embrace chaos"
- **Effect**: +15 Chaos

---

## 🌀 Advanced Mechanics

### Phase System
- Automatic progression every **1200 frames** (~20 seconds)
- Each phase adds:
  - +3-6 Max HP
  - New bullet patterns
  - Increased difficulty

### Cycle Memory
The game tracks across deaths:
- Total choices made
- Deaths & victories
- Unique reality modifiers encountered
- Phases reached

### Reality Modifiers (30% chance)
1. **Inverted Gravity**: Bullets reverse direction
2. **Time Spiral**: Random speed changes
3. **Quantum Entanglement**: Bullets move together
4. **Psychedelic Shift**: Color changes
5. **Void Attraction**: Bullets seek player
6. **Chaos Mirror**: Bullets reflect from walls

### Random Events (20% chance)
- **Reality Glitch**: Screen distortion
- **Time Dilation**: Speed fluctuation
- **Void Whisper**: Existential messages
- **Dimensional Shift**: Color filter

---

## 🔫 Bullet Types

### Basic Bullets
- **White**: Standard (1 damage)
- **Purple (Void)**: Heavy (2 damage)
- **Yellow (Chaos)**: Unpredictable movement
- **Orange (Wave)**: Sine wave motion

### Advanced Bullets (Phase 2+)
- **Pink (Homing)**: Tracks player position
- **Cyan (Splitter)**: Splits on wall impact
- **Orange (Wave)**: Sine wave patterns

---

## 🎨 Visual Modes

### Meta Mode
- Activated by questioning reality
- Green text on black background
- Reality glitches
- Existential border color

### Night Mode
- Activated in Ocean/Night phases
- Blue tint (#001022)
- Pulsing animation
- +XDUST mechanic

### Chaos Mode
- Activated in final phase
- Purple/pink color scheme
- Rotating enemy sprite
- Hue-shifting effects

---

## 🏆 Victory Conditions

### Standard Victory
- Complete all 8 encounters
- Survive bullet patterns
- Make enough correct choices

### True Ending
- **DT ≥ 15**
- **questionedReality = true**
- Shows resonance metrics
- Unlocks cycle continuation

---

## 🛠️ Modification Guide

### Easy Tweaks

#### Adjust Difficulty
```javascript
// Line ~1089 - Change HP/Damage
player.hp = 30; // Start with more HP
function takeDamage(d) { 
  player.hp = Math.max(0, player.hp - d/2); // Half damage
}
```

#### Change Bullet Speed
```javascript
// In any bullet pattern function
vx: Math.cos(angle) * 3, // Change multiplier (currently 2-3)
```

#### Modify Cooldowns
```javascript
// Line ~257
abilities: {
  dash: { cooldown: 0, maxCooldown: 60 }, // Half cooldown
  shield: { cooldown: 0, maxCooldown: 150 }, // Half cooldown
}
```

### Advanced Modifications

#### Add New Bullet Pattern
```javascript
function createMyPattern() {
  spawnRealityText("MY PATTERN", battleBox.offsetWidth/2, 30);
  for (let i = 0; i < 8; i++) {
    setTimeout(() => {
      const b = document.createElement('div');
      b.className = 'bullet';
      b.style.width = b.style.height = '15px';
      // Position and velocity logic here
      battleBox.appendChild(b);
      bullets.push({el: b, x: x, y: y, vx: vx, vy: vy});
    }, i * 500);
  }
}
```

#### Add New Character
```javascript
const newChar = {
  enemy: "MyChar",
  sprite: `<svg viewBox="0 0 100 100">...</svg>`,
  intro: "* My dialogue...",
  choices: ["* Choice 1", "* Choice 2", "* Choice 3"],
  correct: 1,
  actSuccess: "* Success text...",
  bulletPattern: () => createMyPattern()
};
baseScenes.push(newChar);
```

#### Change Colors
```javascript
// Line ~9 - CSS
.bullet{background:#F00;} // Red bullets
#heart{background:#0F0;} // Green heart
```

---

## 🎵 Audio System

- Uses Web Audio API
- `soundEnabled` toggle (speaker icon)
- Background music = cycling sine wave tones
- Sound effects for: dialogue, bullets, hits, abilities, phase changes

### Disable Sounds
```javascript
soundEnabled = false; // Line ~235
```

---

## 📱 Telegram Web App Support

The game includes Telegram integration:
```javascript
if (window.Telegram?.WebApp) {
  Telegram.WebApp.ready();
  Telegram.WebApp.expand();
}
```

Remove if not needed or for standalone use.

---

## 🐛 Debugging Tips

### Show Hitboxes
```javascript
// Add to CSS
.bullet, #heart {
  outline: 1px solid red !important;
}
```

### Invincibility Mode
```javascript
function takeDamage(d) { 
  // Comment out this line:
  // player.hp = Math.max(0, player.hp - d); 
}
```

### Skip to Specific Scene
```javascript
// In startGame()
currentScene = 5; // Start at Ocean (0-7)
```

### View Collision Detection
```javascript
// In updateBullets(), add:
console.log('Bullet:', r, 'Heart:', hR);
```

---

## 🎮 Controls Summary

### Keyboard
- **Arrow Keys / WASD**: Move heart
- **Enter / Space**: Select choice
- **D/S/T/R**: Activate abilities

### Touch
- **Tap & Drag**: Move heart in battle
- **Tap Choices**: Select option
- **Tap Ability Icons**: Activate

---

## 💡 Pro Tips

1. **Correct choices** (option 2) give +5 DT without damage
2. **Shield** is best used when overwhelmed
3. **Time Slow** makes complex patterns manageable
4. **Resonance Burst** has longest cooldown - save for emergencies
5. Death isn't permanent - cycles add variety
6. Higher phases = more HP but harder patterns
7. Reality modifiers reset each cycle
8. Chaos mode (final phase) is intentionally unpredictable

---

## 📝 Version Notes

**Current Version**: Enhanced Edition
- 8 base encounters
- 4 abilities
- Phase progression system
- Cycle memory
- Reality modifiers
- Multiple endings
- Persistent storage support (commented out)

---

## 🔗 Key Variables Reference

| Variable | Purpose | Initial Value |
|----------|---------|---------------|
| `player.hp` | Health | 20 |
| `player.maxHp` | Max health | 20 |
| `player.determination` | Meta-awareness | 0 |
| `currentPhase` | Phase counter | 1 |
| `cycleCount` | Reset counter | 0 |
| `timeSlowFactor` | Speed multiplier | 1.0 |
| `phaseDuration` | Frames per phase | 1200 |

---

---

Happy modding! 🎮✨
---

*"How many cycles will it take to understand the pattern? Or will you break it first?"*
