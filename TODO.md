# Shut the Box - Development TODO

## Phase 1: Project Setup
- [x] Initialize Expo project with TypeScript template
- [ ] Configure app.json (name, slug, icons, splash)
- [ ] Set up EAS project (`eas init`)

## Phase 2: Core Screens
- [ ] Home Screen
  - [ ] App title/logo
  - [ ] "New Game" button
- [ ] Player Setup Screen
  - [ ] Number of players selector (1-4)
  - [ ] Player name inputs
  - [ ] "Start Game" button
- [ ] Game Screen
  - [ ] Current player indicator
  - [ ] Tile board (1-9 tiles)
  - [ ] Dice display and roll button
  - [ ] Score display
  - [ ] "End Turn" / "Next Player" button
- [ ] Results Screen
  - [ ] Final leaderboard
  - [ ] Winner announcement
  - [ ] "Play Again" / "New Game" buttons

## Phase 3: Game Logic
- [ ] Dice rolling (random 1-6 for each die)
- [ ] Valid move calculation
  - [ ] Find all tile combinations that sum to dice total
  - [ ] Handle single die rule (tiles sum ≤ 6)
- [ ] Tile state management (up/down)
- [ ] Turn end detection (no valid moves)
- [ ] Score calculation (sum of remaining tiles)
- [ ] Winner determination (lowest score)

## Phase 4: UI Components
- [ ] Animated dice component
- [ ] Interactive tile board
  - [ ] Tap to select tiles
  - [ ] Visual feedback for valid/invalid selections
  - [ ] Flip animation when shutting tiles
- [ ] Player turn indicator
- [ ] Scoreboard component
- [ ] Game over modal

## Phase 5: Polish
- [ ] Sound effects (dice roll, tile flip, win/lose)
- [ ] Haptic feedback on interactions
- [ ] Loading states and transitions
- [ ] Responsive design for various screen sizes

## Phase 6: App Store Preparation
- [ ] Design app icon (1024x1024)
- [ ] Create splash screen
- [ ] Write app store descriptions
- [ ] Take screenshots for listings
- [ ] Create privacy policy page
- [ ] Set up developer accounts
  - [ ] Apple Developer Program ($99/year)
  - [ ] Google Play Console ($25 one-time)

## Phase 7: Build & Deploy
- [ ] Configure EAS Build (eas.json)
- [ ] Create development builds for testing
- [ ] Test on physical iOS device
- [ ] Test on physical Android device
- [ ] Create production builds
- [ ] Submit to Apple App Store
  - [ ] App Store Connect setup
  - [ ] TestFlight beta testing
  - [ ] App Review submission
- [ ] Submit to Google Play Store
  - [ ] Play Console setup
  - [ ] Internal testing track
  - [ ] Production release

## Future Enhancements (Post-MVP)
- [ ] Multiple round scoring mode
- [ ] Battle Royale mode (elimination rounds)
- [ ] Local high scores persistence
- [ ] Sound/haptic settings toggle
- [ ] Custom themes
- [ ] Online multiplayer
- [ ] Achievements system
