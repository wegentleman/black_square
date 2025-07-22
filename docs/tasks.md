# Development Tasks

## Stage 1: Project Foundation & Tooling
- [ ] Initialize Nuxt 3 project with pnpm and TypeScript
- [ ] Set up ESLint and Prettier for code quality and formatting
- [ ] Install and configure Tailwind CSS and Inspira UI
- [ ] Set up Vitest for unit testing and Playwright for E2E testing

## Stage 2: Core Architecture & State
- [ ] Create Pinia store for music theory state (current key, mode, chords, scales)
- [ ] Create Pinia store for app settings (theme, MIDI devices, preferences)
- [ ] Implement music theory utility functions using Tonal.js (chord/scale/key helpers)
- [ ] Create composable for music theory logic (useMusic.ts)
- [ ] Create composable for MIDI integration (useMidi.ts)

## Stage 3: Layout & Basic UI Skeleton
- [ ] Build main layout with header, left/right panels, center visual area, and footer
- [ ] Implement header with KeySelector and Settings button
- [ ] Implement left panel for chord/scale lists
- [ ] Implement center panel for Piano/Visual display
- [ ] Implement right panel for MIDI controls and info
- [ ] Implement footer with playback controls

## Stage 4: Key Selection & Display
- [ ] Develop KeySelector dropdown for key selection
- [ ] Add piano keyboard input for key selection
- [ ] Add text input with validation for key selection
- [ ] Add major/minor toggle and key signature visualization
- [ ] Display recently used keys in KeySelector

## Stage 5: Chord & Scale Display
- [ ] Implement ChordDisplay component with grid of chords in key
- [ ] Show chord name, symbol, and Roman numeral in ChordDisplay
- [ ] Add click-to-select and hear chord in ChordDisplay
- [ ] Implement inversion and voicing options in ChordDisplay
- [ ] Implement ScaleDisplay component with list of scales in key
- [ ] Show interval pattern and mode relationships in ScaleDisplay
- [ ] Display scale degree functions in ScaleDisplay

## Stage 6: Interactive Piano & MIDI
- [ ] Develop interactive Piano component with note highlighting
- [ ] Enable click-to-play notes on Piano component
- [ ] Show visual feedback for MIDI input on Piano component
- [ ] Integrate MIDI output for chord playback
- [ ] Integrate MIDI output for scale playback and arpeggios
- [ ] Implement basic MIDI input detection and feedback

## Stage 7: Progressions & Practice Tools
- [ ] Create Chord Progression builder UI
- [ ] Implement playback for custom chord progressions
- [ ] Add chord substitution suggestions in progression builder
- [ ] Add interval training practice tool
- [ ] Add chord recognition quiz practice tool
- [ ] Add scale practice tool with metronome
- [ ] Add ear training exercises

## Stage 8: Advanced Features & Responsiveness
- [ ] Implement advanced chord features: inversions, voicings, extended/altered chords
- [ ] Add export functionality for MIDI files
- [ ] Implement user preferences and settings UI
- [ ] Make app fully responsive for mobile devices
- [ ] Add guitar fretboard visualization (optional)

## Stage 9: Testing, Polish & Deployment
- [ ] Write unit tests for composables and stores
- [ ] Write E2E tests for key user flows
- [ ] Polish UI/UX and apply modern dark minimalist style
- [ ] Improve accessibility (a11y) across all components
- [ ] Optimize performance (code splitting, lazy loading, etc.)
- [ ] Prepare documentation and help system
- [ ] Prepare for deployment (Vercel/Netlify), finalize CI/CD 