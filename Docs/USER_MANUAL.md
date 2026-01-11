# 🏒 Hockey GM Simulator - User Manual

**Version 1.0** | Last Updated: January 2026

---

## 📋 Table of Contents

1. [Getting Started](#getting-started)
2. [Navigation Guide](#navigation-guide)
3. [Core Features](#core-features)
4. [Team Management](#team-management)
5. [Transactions](#transactions)
6. [Statistics & Standings](#statistics--standings)
7. [Season Flow](#season-flow)
8. [Advanced Features](#advanced-features)
9. [Tips & Strategies](#tips--strategies)
10. [Troubleshooting](#troubleshooting)

---

## 🎮 Getting Started

### First Launch
1. **Select Your Team** - Choose from 32 NHL teams
2. **Auto-Generated Season** - Full 82-game schedule created instantly
3. **Ready to Play** - Start managing immediately

### Main Interface
The game opens to **Team Hub** - your command center showing:
- Current record and standings
- Upcoming games
- Team alerts (injuries, expiring contracts, trade deadline)
- Quick actions (simulate, trades, lineup changes)

---

## 🧭 Navigation Guide

### Main Tabs

#### 1. 🎮 Play Game
**One-click simulation** - Simulates the next game instantly
- Green button for quick access
- Most-used action in the game

#### 2. 🏒 My Team
Team management and roster control:
- **Team Hub** - Overview dashboard
- **Roster** - View all players with stats and contracts
- **Lines & Scratches** - Set forward lines, defense pairs, special teams
- **Injuries** - Track injured players and recovery timelines
- **Call-Ups / Send-Downs** - Manage farm team players

#### 3. 📝 Transactions
All player movement and contracts:
- **Trades** - Propose and complete trades with AI teams
- **Re-Sign Players** - Negotiate contract extensions
- **Draft Picks** - View owned picks for upcoming drafts
- **Free Agents** - *(Coming Soon)*

#### 4. 📊 Stats & Standings
Performance tracking:
- **Standings** - Division and conference rankings
- **Player Stats** - League-wide statistics (sortable)
- **Team Stats** - Your team's performance metrics
- **League Leaders** - Top performers by category
- **Team History** - Season-by-season records

#### 5. 🌐 League
League-wide information:
- **Schedule** - Full league schedule
- **Key Dates** - Important deadlines and events
- **League Transactions** - All trades across the league
- **Awards** - End-of-season honors
- **Draft Lottery** - Post-playoffs (if eligible)
- **Entry Draft** - Annual draft event

---

## 🎯 Core Features

### Simulation System
- **Single Game** - Simulate one day at a time
- **Realistic Outcomes** - Based on player ratings, matchups, home/away
- **Detailed Stats** - Goals, assists, shots, saves tracked
- **Special Teams** - Power play and penalty kill simulation

### Player Ratings
- **Overall (OVR)** - Player's current skill level (60-99)
- **Potential (POT)** - Maximum possible rating (60-99)
- **Position-Specific** - Forwards, defensemen, goalies rated differently

### Contract System
- **Salary Cap** - $88M ceiling, $65M floor
- **Contract Types** - Entry-level and standard contracts
- **Years Remaining** - Tracks contract length
- **Cap Hit** - Annual salary against cap
- **UFA Status** - Unrestricted free agent when contract expires

---

## 🏒 Team Management

### Setting Your Lineup

#### Forward Lines (4 lines)
- **Line 1** - Top scorers (18-20 min ice time)
- **Line 2** - Secondary scoring (16-18 min)
- **Line 3** - Two-way players (14-16 min)
- **Line 4** - Energy/checking line (10-12 min)

**Positions per line:**
- LW (Left Wing)
- C (Center)
- RW (Right Wing)

#### Defense Pairs (3 pairs)
- **Pair 1** - Top defenders (22-24 min ice time)
- **Pair 2** - Second pairing (18-20 min)
- **Pair 3** - Third pairing (14-16 min)

**Positions per pair:**
- LD (Left Defense)
- RD (Right Defense)

#### Goalies
- **Starter** - Plays majority of games
- **Backup** - Rest games and back-to-backs
- **Third String** - Farm team callup if needed

#### Special Teams
- **PP1 (Power Play 1)** - 5 players, first unit
- **PP2 (Power Play 2)** - 5 players, second unit
- **PK1 (Penalty Kill 1)** - 4 players, top unit
- **PK2 (Penalty Kill 2)** - 4 players, second unit

### Auto-Set Best Lineup
Click the button to automatically:
- Sort players by overall rating
- Assign optimal positions
- Set special teams units
- Dress 12F, 6D, 2G (13th forward scratched)

### Lineup Validation
The game checks for:
- ✅ All positions filled
- ✅ No duplicate assignments
- ✅ Exactly 4 players per PK unit
- ✅ Exactly 5 players per PP unit
- ❌ Blocks simulation if invalid

---

## 💼 Transactions

### Making Trades

#### Trade Interface
1. **Your Side** - Add players/picks to offer
2. **Their Side** - Add players/picks you want
3. **AI Evaluation** - Instant feedback on fairness
4. **Accept/Reject** - AI decides based on value

#### Trade Rules
- ✅ Trades allowed until Day 56 (Trade Deadline)
- ❌ Cannot trade injured players
- ✅ Can trade draft picks (up to 3 years future)
- ✅ Must stay under salary cap after trade

#### Trade Tips
- AI values young players with high potential
- Overpaying slightly increases acceptance chance
- Adding draft picks sweetens deals
- Check cap space before proposing

### Re-Signing Players

#### Contract Negotiation
Available for players in their **final contract year**:

1. **Access** - Transactions → Re-Sign Players
2. **View Demands** - See player's asking price
3. **Make Offer** - Adjust salary ($775K - $13.2M) and years (1-8)
4. **Acceptance Likelihood** - Real-time feedback
5. **Cap Projections** - See future cap impact

#### Player Demands
Based on:
- **Overall Rating** - Higher OVR = higher salary
- **Age** - Younger players want longer terms
- **Market Value** - ±10% variance per player

#### Acceptance Criteria
Players accept if:
- Salary within **15% of market value**
- Term within **2 years of preference**

**Example:**
- Player wants: $5.0M × 6 years
- Will accept: $4.25M-$5.75M, 4-8 years
- Won't accept: $3.5M or 2 years

#### Cap Projections
Shows **3 future seasons**:
- Total salary committed
- Available cap space
- All active contracts listed
- New contract highlighted

---

## 📊 Statistics & Standings

### Standings
**Division View:**
- 8 teams per division
- Sorted by points
- Shows W-L-OTL record
- Points calculation: Win=2pts, OTL=1pt

**Conference View:**
- 16 teams per conference
- Playoff picture (top 8 make playoffs)
- Wild card positions

**League View:**
- All 32 teams
- Cross-conference comparison

### Player Stats

#### Skater Stats
- **GP** - Games Played
- **G** - Goals
- **A** - Assists
- **PTS** - Points (Goals + Assists)
- **+/-** - Plus/Minus rating
- **PIM** - Penalty Minutes
- **SOG** - Shots on Goal
- **S%** - Shooting Percentage

#### Goalie Stats
- **GP** - Games Played
- **W-L** - Wins-Losses
- **SV%** - Save Percentage
- **GAA** - Goals Against Average
- **SO** - Shutouts
- **SA** - Shots Against
- **SV** - Saves

#### Advanced Stats
- **Corsi** - Shot attempt differential
- **Fenwick** - Unblocked shot differential
- **PDO** - Shooting % + Save % (luck indicator)

### Team Stats
Track your team's:
- Goals for/against per game
- Power play percentage
- Penalty kill percentage
- Shot differential
- Special teams rankings

---

## 🗓️ Season Flow

### Regular Season (Days 1-82)
1. **Early Season** (Days 1-20)
   - Find chemistry
   - Test lineups
   - Monitor injuries

2. **Mid-Season** (Days 21-56)
   - Identify weaknesses
   - Make trades (before deadline)
   - Re-sign expiring players

3. **Trade Deadline** (Day 56)
   - Final day for trades
   - Push for playoffs or sell assets

4. **Late Season** (Days 57-82)
   - Playoff push
   - Rest key players if eliminated
   - Development time for prospects

### Playoffs (Best-of-7 series)
1. **First Round** - 1v8, 2v7, 3v6, 4v5 seeds
2. **Second Round** - Conference semifinals
3. **Conference Finals** - Top 2 per conference
4. **Stanley Cup Finals** - Conference winners

### Offseason
1. **Awards Ceremony** - League honors
2. **Draft Lottery** - Bottom 16 teams (if missed playoffs)
3. **Entry Draft** - 7 rounds, 224 prospects
4. **Free Agency** - Sign UFAs *(Coming Soon)*
5. **Player Development** - Age-based progression
6. **Next Season** - New schedule generated

---

## 🎓 Advanced Features

### Player Development System
**Age-Based Progression:**
- **18-21** - Rapid growth (+3 to +5 OVR)
- **22-24** - Strong development (+1 to +3 OVR)
- **25-27** - Entering prime (+0 to +1 OVR)
- **28-30** - Peak years (maintain rating)
- **31-32** - Early decline (30% chance -1)
- **33-35** - Decline years (-1 to -2 OVR)
- **36+** - Rapid decline (-2 to -3 OVR)

**Factors:**
- Potential rating (won't exceed POT)
- Age curve
- Random variance

### Injury System
**Injury Types:**
- **Day-to-Day** - 1-3 games
- **Week-to-Week** - 4-7 games
- **Month-to-Month** - 15-30 games
- **Season-Ending** - Remainder of season

**When Injured:**
- Player unavailable for lineup
- Farm player auto-called up
- Contract still counts vs cap
- Recovery countdown shown

### Salary Cap Management
**Cap Basics:**
- **Ceiling**: $88M (cannot exceed)
- **Floor**: $65M (minimum spending)
- **Cap Hit**: Annual salary per player

**Cap Strategies:**
- Front-load contracts for contenders
- Keep space for deadline acquisitions
- Bridge contracts for young players
- Buyouts for bad contracts *(Coming Soon)*

### Draft System
**Entry Draft (Post-Playoffs):**
- **7 Rounds** - 224 total picks (32 per round)
- **Prospect Pool** - Randomly generated each year
- **Ratings** - Current OVR + Potential shown
- **Positions** - Mix of F, D, G
- **Draft Order** - Reverse standings + lottery

**Draft Strategy:**
- High picks = high potential
- Balance position needs
- POT > OVR for young players
- Trade picks for win-now pieces

---

## 💡 Tips & Strategies

### Building a Winner

#### Contender Strategy
- Trade picks for proven talent
- Re-sign core players long-term
- Focus on top-6 forwards and top-4 defense
- Prioritize playoff experience

#### Rebuild Strategy
- Trade veterans for picks/prospects
- Develop young talent
- Tank for high draft picks
- Sign short-term deals

#### Balanced Approach
- Keep core, trade depth
- Draft well
- Smart cap management
- Mix of young and veteran players

### Line Optimization

**Forward Chemistry:**
- Pair playmakers with snipers
- Balance scoring across lines
- Speed on 1st/3rd lines
- Physicality on 4th line

**Defense Pairings:**
- Mobile + Stay-at-home
- Offensive + Defensive
- Right/Left balance
- PK specialists on 2nd/3rd pairs

**Special Teams:**
- PP1: Best offensive players
- PK1: Defensively responsible
- Rotate to manage ice time

### Cap Management Tips
1. **Leave 5-10% buffer** - For emergencies
2. **Bridge contracts** - 2-3 years for young stars
3. **Trade before UFA** - Don't lose for nothing
4. **Avoid long deals to 30+** - Decline risk

---

## 🔧 Troubleshooting

### Common Issues

#### "Cannot simulate - invalid lineup"
**Fix:**
- Check all positions filled
- Verify PK units have exactly 4 players
- Verify PP units have exactly 5 players
- Use "Auto-Set Best Lineup" button

#### "Trade rejected"
**Fix:**
- Add more value to your side
- Include draft picks
- Check if player is injured
- Ensure AI has cap space

#### Contract won't be accepted
**Fix:**
- Increase salary offer
- Adjust contract length closer to preference
- Check acceptance likelihood indicator
- Player may want 10-15% more than shown

#### Game running slowly
**Fix:**
- Clear browser cache
- Close other tabs
- Use "Emergency Clear" if needed (loses save)
- Game auto-saves to IndexedDB

### Save System
- **Auto-Save** - After every simulation
- **IndexedDB Storage** - Browser-based (persists)
- **No Account Required** - All local
- **Emergency Clear** - Bottom of page if errors

---

## 🎮 Keyboard Shortcuts
*(None currently - all click-based)*

---

## 📞 Support & Feedback

### Report Bugs
Discord: https://discord.gg/zxhezDxfFm

### Suggest Features
Discord: https://discord.gg/zxhezDxfFm

### Ko-fi Support
Support development: [Ko-fi link]

---

## 📝 Version History

### v1.0 (January 2026)
**Initial Release:**
- Full 82-game season simulation
- 32 NHL teams
- Complete roster management
- Trade system
- Contract re-signing
- Playoffs (4 rounds)
- Entry Draft (7 rounds)
- Player development
- Injury system
- Advanced stats
- Google Analytics integration

---

## 🔮 Coming Soon

### Planned Features
- Free Agency system
- Contract buyouts
- Waiver wire
- Training camp
- Preseason games
- All-Star Game
- Trade deadline acquisitions
- Multiple save files
- Import/Export saves
- Difficulty settings
- Custom league settings

---

**Enjoy managing your team! 🏒**

© 2026 Hockey GM Simulator | Free Forever
