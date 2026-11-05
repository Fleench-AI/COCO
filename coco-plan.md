The CoCo Ecosystem: Complete Master Summary & Platform Blueprint

Campaign Slogans:

"Colo-Ready, Go-CoCo!"

"Skip the Traffic, Take the CoCo."

"One Colorado. One Card. Endless Journey."

"From Plains to Peaks, We've Got You Covered."

1. The Core Architecture & Naming Hierarchy

The state’s fragmented public transit is unified under one overarching state transit authority and umbrella brand known simply as CoCo (Colorado Connect). This represents the full merger of CDOT’s transit division and the state's rail initiatives, broken down into three distinct operational pillars:

CoCo (The Overarching Agency): The parent state transit authority managing the entire ecosystem, the payment clearinghouse, the app, the cards, and the CoCo Direct micro-transit fleet.

CoCoM (COM - CoCo Motor & Mobility): The state-run intercity, express, ski, and rural bus division of CoCo, encompassing Bustang, Pegasus, Snowstang, and Outrider under the unified statewide network.

CoCoR (COR - CoCo Rail): The heavy-rail backbone of the state, encompassing dedicated local lines, high-speed express lines, and leased cars attached to federal Amtrak trains.

"with CoCo" Partnerships: A voluntary franchise-style integration for local municipal transit agencies (e.g., RTD with CoCo, GVT with CoCo).

2. Branding & Physical Infrastructure

The Visual Identity

State Flag Livery: All state-owned CoCo buses and CoCoR trains share an iconic paint scheme: deep navy blue on the top half, clean white on the bottom half, divided horizontally down the middle by red and golden-yellow racing stripes.

The CoCo Mustang: The beloved Bustang horse logo is retained and promoted to the official mascot of the entire CoCo agency, recolored in the state flag palette (a navy blue horse streaking through the red "C" and yellow sun disk).

Station Tiers & "Mountain Modern" Design

Stations abandon cheap plastic shelters in favor of heavy timber beams, native Colorado sandstone bases, angled steel roofs (engineered for snow loads), and floor-to-ceiling glass windbreaks. Every single stop is anchored by the CoCo Totem—a 12-foot illuminated navy blue pylon topped with a glowing LED Mustang and "C" roundel visible from blocks away.

Tier 1 (CoCoR Rail Hubs): Fully enclosed, heated buildings featuring CoCo Cargo secure gear lockers (for skis and bikes), digital timetable screens, staffed Main Desks, CoCo Snack Zones, automated card kiosks, and dedicated local retail.

Tier 2 ("with CoCo" Local Bus & CoCo Bus Shelters): Three-sided glass and timber structures equipped with push-button infrared radiant ceiling heaters for winter waits, plus integrated yellow Tap-On validators, automated ticket/card kiosks, and route information.

Tier 3 (CoCo Direct Posts): Designed for rural pickup zones or tight urban sidewalks, consisting of the illuminated CoCo Totem, a solar-powered e-ink schedule display, an automated card kiosk, and a Tap-On validator.

3. Payment, Ticketing, and Retail

The Strict "Tap-On" Architecture

To keep boarding lines moving swiftly across all transit modes, the statewide network operates on a strict Tap-On Only model (no tapping off). Boarding validation functions under offline-first and proof-of-payment principles:

- Tap-On Validation: Riders tap their physical CoCo card or digital app credential at the boarding validator. Tapping without a valid pass or sufficient cash balance alerts the operator, though every stop and vehicle platform provides automated kiosks to purchase or load media on the spot.
- Offline Tap-and-Sync: Onboard NFC readers operate independently of live cellular connectivity. Readers inspect active local passes in flash storage first, apply demographic discounts, and deduct cash values in under 300 milliseconds. Transaction ledgers store securely on the validator and sync asynchronously over cellular or depot Wi-Fi upon reaching coverage.
- Platform Validators: For open-boarding systems (such as RTD Light Rail platforms and high-volume CoCoR rail stops), riders tap freestanding yellow platform totem validators before boarding. The validator writes an authenticated digital timestamp directly into the card's local storage.
- Handheld Proof-of-Payment: Onboard fare inspectors carry ruggedized, offline handheld scanners that inspect and cryptographically verify card timestamps and active fare validity on open-boarding lines without requiring live network access.
- Single-Use Paper Tickets: Tourists and infrequent riders can purchase single-use paper tickets embedded with RFID/QR codes at any automated kiosk to tap into the system.

The CoCo Card Matrix (Four Primary Tiers: Standard Plastic & Premium '+' E-Ink)

CoCo transit cards are available across four purpose-built tiers. Every tier is offered in either standard durable recycled plastic or a premium "Plus" (+) edition featuring an ultra-low-power electronic ink (e-ink) display powered by ambient NFC energy harvesting:

1. Core Card (C / C+) — The Default Adult Transit Card
- Demographic & Eligibility: Universal adult transit pass for riders aged 18 and older.
- Standard C Card: Issued completely free of charge at all automated kiosks, transit desks, and partner agencies. Holds an offline transit cash balance and up to 5 pre-purchased tickets/passes locally in secure flash storage, ensuring full offline functionality. Operates 100% anonymously when unlinked, or can be registered in the CoCo RealTime app for zero-liability loss protection, balance restoration, and remote card freezing.
- Plus C+ Card: Premium edition available for a $20–$25 issuance fee. Features a battery-free bistable e-ink display powered entirely via NFC energy harvesting during the 300ms tap. The screen persistently displays the real-time cash balance, active pass/tap verification status, and a visual loyalty progress tracker.

2. Youth Card (Y / Y+) — Dependents, Youth, Seniors & Veterans
- Demographic & Eligibility: Dedicated card family serving dependents and young riders (formally superseding obsolete "Kids / K" terminology), as well as seniors (65+) and military veterans under the unified 50% discount umbrella.
  - Ages 0–7: Ride 100% free across the entire network without requiring individual cards.
  - Ages 8–12: Must ride accompanied by an adult per CoCo Terms of Service.
  - Ages 13–18: Permitted to ride independently across all statewide lines.
- Parent-Managed Family Dashboard: Centrally managed through the parent or guardian's CoCo RealTime app. Parents can set automated reloads, freeze/unfreeze lost cards instantly, view live boarding location alerts upon each tap, and configure custom reward goals (e.g., educational or transit milestones) reflected on the Y+ e-ink screen.
- 18th Birthday Swap: To eliminate digital fraud and verify adulthood, Youth cards do not automatically convert in software upon the holder's 18th birthday. At age 18, the rider brings their Y Card to any physical automated kiosk or staffed transit desk to graduate to an adult Core (C) Card. Y+ cardholders receive an exclusive 50% discount voucher toward upgrading to an adult Core Plus (C+) card.

3. All Card (A / A+) — The Hybrid Transit & Everyday Debit Card
- Demographic & Eligibility: Designed for frequent commuters and statewide residents seeking an all-in-one payment tool.
- Banking & Passthrough API: Standard A Card pairs a full CoCo transit pass with an everyday commercial debit card. Rather than operating as a custodial bank or depository institution, CoCo functions strictly as a secure transaction passthrough clearinghouse, linking directly to the cardholder's existing checking account via modern open-banking APIs. Works for everyday retail purchases and transit alike.
- Issuance & Perks: Requires an initial issuance fee. As an exclusive account perk, cardholders receive one free standard Core (C) Card replacement per year if their card is lost or damaged.
- Plus A+ Card: Features an e-ink display showing transit status alongside live debit account balance alerts. Furthermore, A+ cardholders accrue CoCo Snack Zone reward points at an accelerated multiplier through daily retail and dining transactions outside the transit network.

4. University Card (U / U+) — Digital Campus ID Integration
- Demographic & Eligibility: Seamless software integration tailored for college and university students throughout Colorado.
- Zero-Waste Campus Credential: CoCo transit software provisions directly onto a designated, secure, unused NFC sector of the student's existing physical campus ID card (e.g., Colorado Mesa University CMU MAVcard, CU Buff OneCard, CSU RamCard) without issuing new plastic.
- In-State Subsidy Safeguard: Subsidized university fare discounts apply exclusively to verified Colorado in-state students via real-time registrar data feeds, preventing out-of-state visitor leakage while maintaining deep transit equity for Colorado residents.
- Plus U+ Card: An optional physical e-ink companion card available at campus bookstores for students who desire hardware e-ink loyalty progress and visual balance tracking.

Universal Fare & Discount Architecture

CoCo establishes a statewide, predictable fare structure engineered to balance equity, accessibility, and high-demand route capacity:

- Core Adult (Standard Fare): 100% full base fare for all standard adult travel across CoCo Rail, Bustang, and local routes.
- University (U Card): 70% of base fare (30% discount). This targeted 30% reduction keeps statewide intercity travel highly affordable for Colorado students while deliberately safeguarding peak weekend seating capacity on heavily trafficked long-haul routes (such as the Bustang West Line along I-70).
- Youth / Senior / Veteran (Y Card): 50% of base fare (50% universal "Half-Fare" demographic). Universal half-fare guarantees equitable mobility for youth, seniors, and military veterans while deterring joyriding and preserving seat availability on capacity-constrained premium recreation routes (such as Snowstang ski express coaches).
- State Guaranteed Floor for Local Municipal Partnerships: Municipal transit agencies (e.g., RTD, Grand Valley Transit) retain full sovereignty to establish local fare policies, including local zero-fare initiatives (e.g., RTD Zero Fare for Youth). However, the State of Colorado establishes a legal minimum 50% discount floor for Youth and Seniors across every partnered local system. If a local municipal agency's baseline fare does not provide at least a 50% concession, any Y Card tap automatically charges the rider half fare, and the CoCo state clearinghouse automatically reimburses the remaining balance directly to the local agency, making them completely whole.

Technical & Hardware Specifications

- Offline Tap-and-Sync Processing: Every onboard validator terminal and platform totem contains a local cryptographically secure ledger and demographic tariff rule engine. When a card taps, the reader inspects local flash memory, verifies ticket/pass validity, calculates applicable demographic discounts, deducts cash value, and commits the write cycle in under 300ms without cellular connectivity. Offline transactions cache locally and broadcast to the central CoCo clearinghouse as soon as cellular or depot Wi-Fi connects.
- Platform Validators & Offline Proof-of-Payment: Platform validators stationed at rail and rapid-transit stops generate encrypted digital proof-of-tap records written to the card's local storage sector. Mobile fare inspection personnel equipped with offline handheld scanners verify these timestamped cryptograms against vehicle run-sheets without requiring real-time network connectivity.
- Battery-Free NFC Energy Harvesting E-Ink Displays (+ Cards): All Plus (+) cards utilize ultra-low-power bistable electrophoretic displays (e-ink) devoid of any internal battery. During the 300ms tap, the alternating magnetic field emitted by the validator or kiosk reader induces a microcurrent within the card's internal antenna coil via near-field energy harvesting. This harvested energy powers the onboard secure element and display controller, completing the cryptographic transaction and refreshing the display with the current balance, tap validation checkmark, or reward tracker. Because bistable e-ink requires zero power to maintain an image, the screen remains persistently legible indefinitely until the subsequent tap.

Loyalty Program: CoCo Snack Zones

- Colorado-Local Product Curation: CoCo Snack Zones are stationed at Tier 1 transit hubs, onboard CoCoR rail lounge cars, and partnered highway mobility hubs. Snack Zones exclusively stock 100% Colorado-made goods (such as artisanal jerky, Olathe sweet corn snacks, Palisade fruit treats, Colorado kombuchas, and local craft roasters).
- Fee Elimination & Local Reinvestment: Transacting directly through CoCo card balances bypasses commercial credit card processing interchange fees, allowing the state to channel transaction savings into rider loyalty rewards and Colorado agricultural producers.
- Standard Cards (C, Y, A, U) Reward Flow: Standard cardholders accrue base loyalty points per transit tap and dollar spent. Once accumulated, points automatically convert into small recurring fare credits (e.g., $1.00 credit toward subsequent transit rides) via the CoCo RealTime app.
- Plus Cards (+) Premium Reward Experience: Plus cardholders gain access to the full premium Snack Zone reward menu, unlocking free coffees, specialty teas, and artisanal snack items. Cardholders choose a single active reward goal at a time in the CoCo app, which projects a live visual progress bar onto the card's e-ink screen. When the target is reached, the e-ink screen dynamically renders a scannable optical barcode for immediate, frictionless scanning and redemption at any Snack Zone counter.

Physical Infrastructure: Automated Kiosks & Main Desks

To ensure total statewide inclusion across urban centers, mountain corridors, and rural communities:

- Automated Kiosks (Every Station & Stop): Deployed at every Tier 1, 2, and 3 station stop statewide. These heavy-duty, weather-resistant kiosks:
  - Dispense anonymous, ready-to-use standard Core (C) cards 24/7.
  - Accept cash, credit/debit, and contactless digital wallets to reload transit cash balances and passes.
  - Process 18th Birthday Swaps, verifying age and transitioning graduating youth from Y cards to standard C cards (or issuing discounted Plus C+ upgrade vouchers).
  - Synchronize offline reward balances, print paper vouchers, and vend RFID/QR single-ride paper tickets for smartphone-free or unbanked riders.
- Main Desks (Staffed Major Hub Centers): Staffed regional customer support centers positioned at primary transit hubs (including Denver Union Station, Grand Junction Mobility Hub, Pueblo Union Depot, and Fort Collins Downtown Transit Center). Main Desks provide high-touch support:
  - Serving unbanked passengers with cash account loading, paper receipts, and balance payouts.
  - Conducting demographic credentialing (in-person Senior, Veteran, and disability verifications).
  - Issuing immediate on-site hardware replacements for premium Plus (+) e-ink cards.
  - Providing onboarding guidance and verification for All Card (A / A+) banking API connections.

4. The CoCo RealTime App

Themed in navy blue, white, red, and yellow, the app is the digital brain of the CoCo agency:

Home Dashboard: Displays the active ticket (NFC & QR backup), countdown timers for daily commutes, and color-coded system/weather status banners.

The Wallet: A unified storefront to buy CoCoR train tickets, CoCo bus passes (Bustang, Pegasus, Snowstang, Outrider), or link local 30-day "with CoCo" passes (like an RTD monthly pass). Features auto-reload, physical card syncing across all tiers (C, Y, A, U), Snack Zone reward selection, and the Family Dashboard (allowing parents to manage Youth Y/Y+ cards with auto-reload, instant freezing, live boarding tracking, and custom reward milestones for Y+ e-ink screens).

Multimodal Navigator: Plans door-to-door trips combining walking, local buses, CoCo intercity/regional buses, CoCoR trains, micro-transit vans, and partnered first/last-mile e-bikes/scooters. Includes a single "Buy Required Tickets" button for the whole itinerary.

The Mustang Tracker (Live Map): Real-time GPS tracking showing moving Mustang icons (Blue for CoCoR Rail, Red/Purple for CoCo Express Buses, Yellow for "with CoCo" Local) with a live weather radar overlay.

Accessibility & Mountain Caching: Uses icon-driven navigation, one-tap translation (Spanish, French, German), high-contrast/voice modes for seniors, and automatic offline caching so tickets and dynamic timetables work in deep mountain canyons with zero cell service.

5. CoCoR (COR): The Rail Network

All dedicated routes use a Two-Letter naming convention (with "X" denoting high-speed, limited-stop express service). Leased Amtrak cars use a Single-Letter convention.

Dedicated State Rail Lines (Standard & Express "X" Service)

Every dedicated state rail corridor operates in two complementary service tiers without branching: a **Standard Line** serving all community station stops, and an **Express Line (marked with 'X')** that bypasses smaller stations to provide rapid intercity transit:

- **CoCoR FR (Front Range Local)** & **CoCoR FRX (Front Range Express):** The I-25 / Joint Line spine connecting Fort Collins, Loveland, Longmont, Boulder, Denver Union Station, Castle Rock, Colorado Springs, Pueblo, Colorado City, Walsenburg, Aguilar, and Trinidad. FR serves all regional mobility hubs; FRX runs express connecting major anchor hubs with dedicated bypass tracks.
- **CoCoR NE (Northeast Local)** & **CoCoR NEX (Northeast Express):** Denver Union Station $\rightarrow$ DIA $\rightarrow$ Brighton $\rightarrow$ Hudson $\rightarrow$ Keenesburg $\rightarrow$ Fort Morgan $\rightarrow$ Brush $\rightarrow$ Sterling $\rightarrow$ Julesburg. NE serves all agricultural communities along the historic South Platte / Union Pacific corridor; NEX runs express Denver $\leftrightarrow$ DIA $\leftrightarrow$ Fort Morgan $\leftrightarrow$ Sterling $\leftrightarrow$ Julesburg.
- **CoCoR EP (Eastern Plains Local)** & **CoCoR EPX (Eastern Plains Express):** Denver Union Station $\rightarrow$ DIA $\rightarrow$ Limon $\rightarrow$ Burlington. Shares track with NE between Denver and DIA before diverging along the Kyle Railroad corridor.
- **CoCoR SL (Southern Local)** & **CoCoR SLX (Southern Express):** Connects Southeast to Southwest Colorado across the San Juan and Sangre de Cristo passes: Pueblo $\rightarrow$ Walsenburg $\rightarrow$ Alamosa (via La Veta Pass) $\rightarrow$ Monte Vista $\rightarrow$ Del Norte $\rightarrow$ South Fork $\rightarrow$ Pagosa Springs (via Wolf Creek Pass) $\rightarrow$ Durango. SLX runs express between Pueblo, Alamosa, and Durango.
- **CoCoR AV (Arkansas Valley Local)** & **CoCoR AVX (Arkansas Valley Express):** Dedicated regional connection along the Arkansas River between Pueblo $\rightarrow$ Fowler $\rightarrow$ Manzanola $\rightarrow$ Rocky Ford $\rightarrow$ La Junta $\rightarrow$ Las Animas $\rightarrow$ Lamar. AV makes all local stops; AVX provides high-speed express service linking Pueblo Union Depot, La Junta Hub, and Lamar.
- **CoCoR LT (Lamar–Trinidad Local)** & **CoCoR LTX (Lamar–Trinidad Express):** Connects Southeast Colorado across Prowers, Bent, Otero, and Las Animas counties: Lamar $\rightarrow$ Las Animas $\rightarrow$ La Junta $\rightarrow$ Thatcher $\rightarrow$ Trinidad. LT provides comprehensive local station service; LTX delivers express regional transit unifying the Lower Arkansas Valley with the southern I-25 Front Range spine.

Leased Amtrak Partnership Cars (Standard & Seasonal Express)

Through a Joint Operating Agreement, the CoCo agency pays Amtrak a guaranteed profitable haulage fee to attach state-owned, FRA-compliant CoCoR cars exclusively during the Colorado legs of Amtrak routes:

- **CoCoR Z (California Zephyr)** & **CoCoR ZX (Zephyr Express):** Runs Denver Union Station $\rightarrow$ Moffat Tunnel $\rightarrow$ Winter Park $\rightarrow$ Granby $\rightarrow$ Kremmling $\rightarrow$ Glenwood Springs $\rightarrow$ Grand Junction.
- **CoCoR W (Winter Park Ski Local)** & **CoCoR WX (Winter Park Express Ski Train):** Dedicated seasonal ski train service from Denver Union Station to Winter Park Resort platform.
- **CoCoR S (Southwest Chief)** & **CoCoR SX (Chief Express):** State leased cars on Amtrak's interstate through-route: Lamar $\rightarrow$ Las Animas $\rightarrow$ La Junta $\rightarrow$ Thatcher $\rightarrow$ Trinidad.

Onboard CoCoR Experience

Seating: Standard 2x2 configuration (zero middle seats) engineered for trips up to 4 hours, with panoramic windows, fold-down trays, universal AC/USB-C outlets, and CoCo Cargo racks at the ends of every car for skis and bikes.

Premium Trim (Standard on Z, W, S, and Express Cars): Features wipeable navy vegan leather seats with red/yellow stitching, real Colorado timber window framing, warm adjustable LED lighting, and a standing high-top bar area at the CoCo Snack Zones lounge.

The WiFi Flex: Front Range trains use a 5G/Satellite mesh. For the Z, W, and S cars (where Amtrak has zero WiFi), CoCo mounts low-profile satellite dishes (e.g., Starlink) to the roof. To prevent standard Amtrak passengers from stealing bandwidth, the WiFi is locked behind a simple daily password displayed on screens inside the CoCo car and given only to registered CoCo Card holders (C, Y, A, U).

6. CoCoM (COM): Bustang, Pegasus, Snowstang, Outrider & Local Partnerships
 
CoCoM (COM - CoCo Motor & Mobility) is the dedicated statewide bus division of CoCo, operating and unifying Colorado's established bus services (Bustang, Pegasus, Snowstang, and Bustang Outrider) under the CoCo platform:

Bustang (Intercity Express Coaches):
- West Line: I-70 corridor connecting Denver Union Station $\leftrightarrow$ Federal Center $\leftrightarrow$ Idaho Springs $\leftrightarrow$ Frisco $\leftrightarrow$ Vail $\leftrightarrow$ Avon $\leftrightarrow$ Eagle $\leftrightarrow$ Glenwood Springs $\leftrightarrow$ Rifle $\leftrightarrow$ Parachute $\leftrightarrow$ Grand Junction.
- North Line: I-25 corridor connecting Denver Union Station $\leftrightarrow$ Firestone/Longmont Hub $\leftrightarrow$ Berthoud Hub $\leftrightarrow$ Loveland (Centerra) $\leftrightarrow$ Fort Collins (Harmony & DTC).
- South Line: I-25 corridor connecting Denver Union Station $\leftrightarrow$ RTD Colorado Station $\leftrightarrow$ Lone Tree $\leftrightarrow$ Monument $\leftrightarrow$ Colorado Springs (Tejon P&R) $\leftrightarrow$ Fountain $\leftrightarrow$ Pueblo Transit Center.

Pegasus (I-70 Mountain Express Shuttles):
- High-frequency 14-passenger Sprinter shuttles utilizing I-70 Mountain Express Lanes to bypass peak congestion between Denver Union Station $\leftrightarrow$ Denver Federal Center $\leftrightarrow$ El Rancho (Evergreen) $\leftrightarrow$ Idaho Springs $\leftrightarrow$ Frisco $\leftrightarrow$ Vail $\leftrightarrow$ Avon.

Snowstang (Seasonal Mountain Ski Express):
- Direct weekend and holiday ski service connecting Denver Union Station and Federal Center to Loveland Ski Area, Arapahoe Basin, Copper Mountain, Breckenridge, and Steamboat.

Bustang Outrider (Rural & Regional Corridors - Complete Statewide Town Reach):
- Craig $\leftrightarrow$ Denver (via US-40 / I-70 through Hayden, Milner, Steamboat Springs, Kremmling, Granby, Fraser, Winter Park, Empire, Idaho Springs).
- Crested Butte / Gunnison $\leftrightarrow$ Denver (via US-50 / US-285 through Almont, Monarch Pass, Poncha Springs, Salida, Buena Vista, Fairplay, Bailey, Pine Junction).
- Alamosa $\leftrightarrow$ Pueblo (via US-285 / US-50 through Moffat, Poncha Springs, Salida, Cotopaxi, Cañon City, Penrose, Pueblo West).
- Durango $\leftrightarrow$ Grand Junction (via US-160 / CO-145 / US-550 / US-50 through Bayfield, Mancos, Cortez, Dolores, Rico, Lizard Head Pass, Telluride, Placerville, Ridgway, Montrose, Olathe, Delta).
- Lamar $\leftrightarrow$ Colorado Springs (via US-50 / I-25 through Fort Lyon, Las Animas, La Junta, Swink, Rocky Ford, Manzanola, Fowler, Pueblo Airport, Pueblo, Fountain).
- Sterling $\leftrightarrow$ Denver (via I-76 through Merino, Brush, Fort Morgan, Wiggins, Keenesburg, Hudson, DIA).
- Sterling $\leftrightarrow$ Greeley (via US-6 / US-34 through Brush, Fort Morgan, Wiggins, Kersey, Greeley-Evans Transit Center).
- Denver $\leftrightarrow$ Estes Park & RMNP (via US-36 through Westminster, Broomfield, Louisville, Boulder, Lyons, Estes Park Visitor Center, RMNP Bear Lake Hub).
- Pueblo $\leftrightarrow$ Trinidad (via I-25 through Colorado City, Walsenburg, Aguilar).

The "with CoCo" Local Model & Holdouts

Local agencies keep their local control, boards, drivers, and paint schemes, simply adding a "with CoCo" badge by installing CoCo Card tap validators and syncing with the app (receiving state transit subsidies and automated clearinghouse fare payouts in return).

RTD is locked in as the anchor partner (RTD with CoCo).

The Opt-Out Clause: Local agencies are legally allowed to refuse partnership. However, rider peer pressure from tourists and locals wanting to use their CoCo Cards everywhere will naturally incentivize holdout cities to opt in over time.

"CoCo Direct" (Solving Transit Deserts)

For municipalities that opted out of regional transit and have no local agency (such as Castle Rock), the parent CoCo agency deploys CoCo Direct:

CoCo provides a turnkey fleet of 12-passenger electric micro-transit vans.

The town only has to provide a parking lot/hub footprint.

Residents summon the vans via the CoCo App for on-demand shuttles from their neighborhoods to the nearest CoCoR station. Once ridership is proven, the town can choose to take over the fleet and transition it into their own "with CoCo" local agency.
