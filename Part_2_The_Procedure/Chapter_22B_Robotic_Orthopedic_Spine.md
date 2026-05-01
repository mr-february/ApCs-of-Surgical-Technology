# Chapter 22B: Robotic Surgery — Orthopedic & Spine

---

## Navigation vs. Robotics: Know the Difference

These two terms are often used interchangeably in the OR. They are not the same thing.

**Surgical navigation** is a real-time GPS system for the OR. It tracks the position of instruments and anatomy in three-dimensional space and displays them on a screen. The surgeon uses navigation to confirm where they are — but their hands do all the cutting.

**Surgical robotics** uses a powered mechanical arm to physically position, guide, or constrain an instrument. Some systems (Mako, ROSA) use a haptic boundary that physically prevents the surgeon from cutting outside the planned zone. Others (Mazor X, ExcelsiusGPS) use the robotic arm to lock a drill guide at a pre-planned trajectory — then the surgeon drills manually through the guide.

**Hybrid systems** (ExcelsiusGPS, Stealth Autopilot with O-arm) combine real-time navigation with robotic arm guidance in one platform.

**Why it matters at the back table:** Navigation cases require patient and instrument tracker arrays to stay mounted and undisturbed throughout the case. Robotic arm cases require registration steps before implants are placed. Understanding which phase you're in determines what you should and should not be doing at any given moment.

---

## Mako SmartRobotics (Stryker)

**Procedures:** Total Hip Arthroplasty (THA), Total Knee Arthroplasty (TKA), Unicompartmental Knee Arthroplasty (UKA)

**How it works:** A pre-operative CT scan is used to create a 3D model of the patient's anatomy. The surgeon creates a personalized implant plan pre-op. In the OR, the patient's anatomy is registered to the CT model using bone-mounted tracker arrays. The Mako robotic arm holds the burr and enforces **haptic boundaries** — the arm physically resists if the surgeon attempts to cut outside the planned resection zone. The surgeon guides the arm; the arm constrains where the burr can go.

**Key concept:** Mako uses a **burr**, not a saw, for bone resection. This is different from standard THA/TKA technique. Know this before you scrub.

### Mako TKA

> **QUICK FACTS**
> Wound Class: I (Clean) · Position: Supine, tourniquet · Avg time: 90–120 min · Implant system: Stryker Triathlon or Resection System

> **BEFORE YOU SCRUB**
> - [ ] Confirm the pre-op CT plan has been completed and loaded on the Mako system; if no CT plan, the case cannot proceed as a Mako case
> - [ ] Tibial and femoral tracker arrays: sterile; placed via bone pins intraoperatively — have the pin driver and array hardware on the field
> - [ ] Mako burr (RIO burr): confirm it is loaded and sterile; have a backup burr
> - [ ] Implant system: Stryker Triathlon components — confirm templated sizes; have 2 above and below ready; trials in order
> - [ ] Standard TKA instruments for the non-robotic steps (arthrotomy, exposure, final implant seating): these are still manual
> - [ ] Cement: mixing supplies ready; tracking the burr cut does NOT cement anything; cementing is still manual at the end
> - [ ] The Mako cart is positioned by the circulator; confirm its screen is visible to the surgeon before draping

**Registration sequence (intraoperative):**
1. Bone pins placed into the distal femur and proximal tibia (4 pins total; 2 per bone)
2. Tracker arrays mounted onto the pins
3. A registration probe is used to digitize anatomical landmarks on the actual patient's bone
4. The system compares the digitized points to the CT model and creates the registration — the virtual bone and the actual bone are now aligned
5. Surgeon verifies the registration accuracy on the Mako screen
6. The robot arm is unlocked; the haptic-guided resection begins

**Your role during registration:**
- Do not disturb the tracker arrays once they are mounted — any movement of the arrays (bumping the table, leaning on the drape near a pin) breaks the registration and forces a re-registration
- Have the registration probe sterile and immediately available when the surgeon calls for it
- When the surgeon is digitizing landmarks, the field must be still and quiet

> **⚠ WATCH FOR**
> - **Array disturbance:** if anyone bumps the tracker array during the case, the registration is lost; the surgeon must re-register; alert the team to array locations before the case begins; mark them with a towel clip on the drape if needed
> - **Burr overheating:** the Mako burr generates heat; continuous irrigation is required during resection; confirm the irrigation cannula is running before the burr is activated
> - **Haptic boundary override:** the robot can be switched to manual mode if the surgeon needs to work outside the planned zone; know this is a deliberate action and confirm it is intentional before proceeding
> - **Implant size change after registration:** if the surgeon changes the implant size intraoperatively, the cut plan changes; the Mako system must be updated before any additional resection; confirm with the surgeon before handing the burr

**Closure:** Same as standard TKA (see Chapter 14) — arthrotomy with #1 Vicryl, subcutaneous 2-0 Vicryl, staples or 3-0 Monocryl for skin.

---

### Mako THA

> **QUICK FACTS**
> Wound Class: I (Clean) · Position: Lateral decubitus (posterior approach) · Avg time: 75–105 min · Implant system: Stryker Accolade/Secur-Fit stem + Trident acetabular shell

> **BEFORE YOU SCRUB**
> - [ ] Pre-op CT plan loaded on Mako system; confirm before prepping
> - [ ] Pelvis and femur tracker arrays: sterile; placed via bone pins
> - [ ] Mako burr for acetabular reaming (replaces the standard manual reamer — or is used in conjunction)
> - [ ] Standard THA instruments still required: femoral broaches, femoral stem, Hohmann retractors, trial components

**Key difference from standard THA:** The Mako robotic arm guides the **acetabular reamer** and controls the **cup impactor trajectory**, ensuring the cup is placed at the planned inclination and anteversion angles. Femoral preparation is still largely manual (broaching).

> **⚠ WATCH FOR**
> - Same array disturbance concerns as Mako TKA
> - Acetabular registration: the surgeon will digitize landmarks on the acetabular rim; have the registration probe available and do not handle the pelvis array until registration is complete

---

## ROSA (Zimmer Biomet)

**Procedures:** ROSA Knee (TKA), ROSA Hip (THA)

**How it works:** ROSA is a robotic arm system similar in concept to Mako. ROSA Knee is **imageless** — no pre-op CT is required; the system uses intraoperative bone morphing and landmark registration to build a virtual model during the case. ROSA Hip uses image-based planning (pre-op CT).

**Key difference from Mako:** ROSA uses a **saw** (like standard TKA technique), not a burr. The robotic arm positions and holds a cutting guide at the planned angle; the surgeon then makes cuts manually through the robotic-guided positioning jig.

### ROSA Knee

> **QUICK FACTS**
> Wound Class: I (Clean) · Position: Supine, tourniquet · Avg time: 90–120 min · Implant system: Zimmer Biomet (Persona, NexGen, or OrthoSensor-compatible systems)

> **BEFORE YOU SCRUB**
> - [ ] ROSA system positioned in the room and powered on; sterile arm drape applied before use
> - [ ] Bone pins and tracker arrays: sterile; will be placed in the distal femur and proximal tibia
> - [ ] Intraoperative registration probe: sterile; on the field
> - [ ] ROSA saw adapter: the robotic arm holds a cutting guide jig; confirm the jig is compatible with the implant system in use
> - [ ] Standard TKA cutting instruments and trials: still required for manual steps
> - [ ] No pre-op CT required for ROSA Knee; confirm with surgeon whether CT-based or imageless workflow is being used

**Registration sequence:** Since ROSA Knee is imageless, the surgeon digitizes bone landmarks directly during the case (similar to Mako) and the system builds the surgical plan intraoperatively from those landmarks plus an anatomical database model. Plan adjustments can be made in real time on the ROSA screen.

> **⚠ WATCH FOR**
> - **Intraoperative plan building:** the surgeon may spend 5–10 minutes at the ROSA screen adjusting the cutting plan before making any cuts; this is normal; do not pass instruments during this time unless asked
> - **ROSA arm sterile drape:** if the robotic arm drape is breached, the arm cannot contact the sterile field; have a spare arm drape in the room
> - **Saw blade seating in the jig:** confirm the saw blade is fully seated in the robotic-guided jig before the surgeon activates the saw; a partially seated blade vibrates out of the guide and produces an inaccurate cut

---

## Mazor X (Medtronic)

**Procedures:** Pedicle screw placement in lumbar, thoracic, and cervical spine surgery (fusion, deformity correction, revision)

**How it works:** A pre-operative CT scan is used to plan the exact trajectory for every pedicle screw. In the OR, the robot arm positions a **cannula/drill guide** at each planned screw trajectory. The surgeon then drills and taps manually through the guide, and places the screw. The robot does not drill or tap — it only positions the guide.

**Mazor X works with Stealth Navigation** (Medtronic's navigation platform) and the **O-arm** (Medtronic's intraoperative CT scanner) for registration and real-time verification.

### Mazor X Spinal Fusion with Pedicle Screws

> **QUICK FACTS**
> Wound Class: I (Clean) · Position: Prone on Wilson frame or Jackson table · Avg time: 2–5 hrs depending on levels · Implants: Medtronic pedicle screw system (CD Horizon, Solera, or equivalent)

> **BEFORE YOU SCRUB**
> - [ ] Pre-op CT plan loaded on Mazor system; confirm before the patient is positioned
> - [ ] O-arm sterile drape: the intraoperative O-arm CT scanner will be used for registration; confirm the sterile drape is available
> - [ ] Spine reference array (patient tracker): clamp-mounted on the spinous process or iliac crest; sterile; on the field
> - [ ] Mazor robotic arm sterile drape: the arm must be draped before it enters the sterile field
> - [ ] Drill guides / cannulas specific to the Mazor system: confirm they match the Mazor X platform in use
> - [ ] Medtronic screw system: pedicle screws, rods, set screws in templated sizes; full trauma-style set available
> - [ ] Fluoroscopy or O-arm shots will be taken at multiple steps — confirm C-arm or O-arm is in the room

**Workflow sequence:**
1. Patient positioned; spine reference array mounted
2. O-arm spin obtained; image transferred to Mazor system; registration completed automatically
3. Surgeon verifies registration accuracy
4. For each screw: the Mazor arm moves to the planned trajectory; locks in position; the surgeon makes a small stab incision or uses the existing open incision; the drill guide is seated on the bone through the robotic cannula; surgeon drills, taps, and places the screw manually
5. After each screw, the O-arm may spin again for verification (or a spot fluoroscopic image is taken)

> **⚠ WATCH FOR**
> - **Reference array movement:** if the spine reference array is bumped or loosened during the case, the registration is invalidated; every screw placed after that point is using a corrupted map; alert the surgeon immediately if the array moves
> - **O-arm spin warning:** when the O-arm rotates around the patient, everyone must step back and remove their hands from the field; alert the team when you hear the spin initiated
> - **Drill guide seating:** the Mazor drill guide must be fully seated on bone before the surgeon drills; if the guide is floating on soft tissue, the trajectory is off; the guide must contact cortical bone
> - **Pedicle breach:** if the surgeon encounters sudden loss of resistance while drilling (breakthrough), stop drilling; assess with fluoroscopy; a breached pedicle may threaten the spinal cord or nerve root
> - **Set screw count:** pedicle screw set screws are tiny; they are counted items; never leave one unsupported on the field; keep them in their designated rack

**Closure:** Spine fusion closure per standard layered technique. Fascia: 1-0 Vicryl figure-of-eight. Subcutaneous: 2-0 Vicryl. Skin: staples or 3-0 Monocryl. JP drain if multilevel fusion.

---

## ExcelsiusGPS (Globus Medical)

**Procedures:** Pedicle screw placement; lateral and posterior spine approaches

**How it works:** ExcelsiusGPS is a combined navigation + robotics platform on a single workstation. Like Mazor X, it uses CT-based pre-op planning and places a drill guide at the planned pedicle screw trajectory. Unlike Mazor X, it does not require a separate navigation system — navigation and robotics are integrated.

**Can work with or without pre-op CT:** The system can use an intraoperative O-arm (or compatible intraoperative CT) for registration when a pre-op CT plan is not available, making it more flexible for urgent or add-on cases.

> **QUICK FACTS**
> Wound Class: I (Clean) · Position: Prone · Avg time: 2–5 hrs · Implant system: Globus Medical (CREO, REVOLVE, or equivalent)

> **BEFORE YOU SCRUB**
> - [ ] Pre-op CT or intraoperative O-arm spin planned; confirm workflow with surgeon
> - [ ] ExcelsiusGPS arm sterile drape: applied before the arm enters the field
> - [ ] Reference array (patient tracker): Globus-specific clamp; sterile; on the field
> - [ ] Globus screw system: confirm which system and sizes are templated; full screw set available
> - [ ] Drill bits, taps, and cannulas specific to the ExcelsiusGPS platform
> - [ ] Fluoroscopy or O-arm for intraoperative verification

**Key difference from Mazor X:** ExcelsiusGPS uses a **locking arm** that clamps rigidly at the planned trajectory. The surgeon does not guide the arm to each position manually; the system moves and locks automatically. The scrub tech role is otherwise similar — passing drills, taps, and screws through the robotic guide.

> **⚠ WATCH FOR**
> - Same reference array concerns as Mazor X — any movement invalidates the registration
> - **Arm lock confirmation:** the ExcelsiusGPS arm must be fully locked before the surgeon drills; a partially locked arm can shift under drilling force; confirm the locked indicator is displayed before passing the drill
> - **Globus screw system specifics:** Globus screws, rods, and reduction instruments are system-specific; standard Medtronic or DePuy instruments are NOT interchangeable; confirm you have the correct set before the case begins

---

## Stealth Navigation + Autopilot (Medtronic)

**Stealth Navigation** is Medtronic's standalone surgical navigation platform — used in spine, cranial, and ENT cases. It tracks instruments and patient anatomy in real time using optical or electromagnetic sensors.

**Stealth Autopilot** is Medtronic's robotic spine arm, designed to work with the Stealth Navigation system and the O-arm for a fully integrated Medtronic ecosystem. Think of it as Mazor X's successor platform — navigation + robotics in one cart.

**Stealth-only cases (no Mazor/Autopilot):**
Some surgeons use Stealth Navigation without any robotic arm — the navigation screen guides them, but they cut and place screws freehand. In these cases, your role as scrub tech focuses on maintaining the instrument tracker arrays (the small optical trackers attached to instruments that the Stealth cameras track).

> **BEFORE YOU SCRUB (Stealth Navigation Case)**
> - [ ] Stealth reference array: sterile; confirm it will be mounted before the O-arm spin
> - [ ] Instrument trackers: sterile trackers that attach to the drill, awl, and pedicle probe; confirm all are on the field and clean (blood on tracker balls = tracking failure)
> - [ ] O-arm sterile drape: if an intraoperative spin is planned
> - [ ] Stealth-compatible instruments: confirm the drill, pedicle probe, and tap all have their Stealth tracker attachment points; non-tracked instruments will not show on the navigation screen
> - [ ] O-arm spin protocol: clear the field, step back, hands off the patient — call it every time

**Stealth Autopilot (robotic arm):**
The Autopilot arm docks to the patient's spine via a rigid clamp and reference frame — it is more stable than a floor-mounted system like Mazor X because it is mounted directly on the patient. The workflow is otherwise comparable: plan → registration → robotic guide → manual screw placement.

> **⚠ WATCH FOR**
> - **Tracker ball contamination:** the optical tracking balls on instrument trackers must be clean and dry; blood or fluids on the balls cause the Stealth camera to lose the instrument; wipe tracker balls with a dry sponge whenever the instrument is off the field
> - **Line of sight to the Stealth camera:** the Stealth optical camera must have an unobstructed view of both the patient reference array and the instrument tracker; if the surgeon, an assistant, or your hand crosses between the camera and the trackers, the instrument disappears from the screen; stay aware of the camera's line of sight
> - **O-arm spin during the case:** any spin requires a full room clear; hands and bodies off the patient; do not touch the instruments on the field during the spin — any movement will corrupt the new registration

---

## Navigation and Robotic Cases: Universal Rules

These apply regardless of the specific platform:

| Rule | Why |
|------|-----|
| **Never disturb the reference array** | Moving the array invalidates the registration; every decision made after that is based on wrong data |
| **Clean tracker balls frequently** | Contaminated tracking balls drop off the navigation screen silently; the surgeon may not notice for several steps |
| **Step back for every O-arm spin** | Radiation exposure; also movement during the spin corrupts the new image |
| **Do not lean on the robotic arm drape** | Pressure on the drape can transmit force to the arm and shift its position |
| **Know the manual backup** | If the robot fails, navigation fails, or the O-arm is unavailable, the case may continue with standard fluoroscopy; have C-arm sterile drape and standard instruments ready in every robotic spine case |
| **Confirm implant system before opening** | Mako uses Stryker implants. ROSA uses Zimmer Biomet. Mazor X uses Medtronic. ExcelsiusGPS uses Globus. These systems are NOT cross-compatible. Opening the wrong implant set at any point in the case is an avoidable error. |

---

## Platform Quick-Reference

| System | Manufacturer | Procedure | Robot Does | Surgeon Does |
|--------|-------------|-----------|-----------|-------------|
| **da Vinci Xi/SP** | Intuitive Surgical | Soft tissue (urology, GYN, thoracic, general) | Holds and moves instruments | All operative decisions; controls arms from console |
| **Mako** | Stryker | THA, TKA, UKA | Haptic boundary enforcement; guides burr | Guides the arm; makes all cuts within the boundary |
| **ROSA Knee/Hip** | Zimmer Biomet | TKA, THA | Positions cutting jig | Makes manual cuts through the robotic-guided jig |
| **Mazor X** | Medtronic | Spine pedicle screws | Positions drill guide at planned trajectory | Drills, taps, and places screws manually |
| **ExcelsiusGPS** | Globus Medical | Spine pedicle screws | Locks drill guide at planned trajectory | Drills, taps, and places screws manually |
| **Stealth Navigation** | Medtronic | Spine, cranial, ENT | Real-time instrument tracking on screen | All cutting; navigation is guidance only |
| **Stealth Autopilot** | Medtronic | Spine pedicle screws | Positions drill guide (patient-mounted arm) | Drills, taps, and places screws manually |

---

## Clinical Pearls

> "Robots don't operate. Surgeons operate. The robot gives the surgeon more precision or more dexterity. Your job as the scrub tech doesn't change in principle — anticipate what's needed and have it ready — but the tools change entirely."

- In every robotic or navigation case, the reference array is the most important thing on the field after the patient. Protect it. Announce its location to everyone at the table. If it moves, say so immediately.
- Mako uses a burr; ROSA uses a saw. If you pull the standard oscillating saw for a Mako case, you have the wrong instrument. Know the system before you pull your instrumentation.
- In a da Vinci case, silence during the anastomosis means you're doing your job. The console surgeon cannot stop to ask questions while suturing. Have the next instrument loaded and your hand on the assistant port before they finish the current step.
- Navigation tracker balls fall off the Stealth screen the moment they get bloody. Make wiping them part of your routine — every time an instrument comes back to the back table.
- If a robotic case converts to open or laparoscopic, have a complete conventional instrument set available in the room. Conversion happens. The room should be ready for it before the case starts.

---

*[Proceed to Part III: The Closure — Chapter 23](../Part_3_The_Closure/Chapter_23_Wound_Closure_Techniques.md)*
