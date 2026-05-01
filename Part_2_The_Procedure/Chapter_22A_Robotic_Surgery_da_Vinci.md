# Chapter 22A: Robotic Surgery — da Vinci

---

## What Robotic Surgery Actually Is at the Back Table

The da Vinci surgical system (Intuitive Surgical) is a master-slave telemanipulation platform. The **surgeon sits at a console** and controls robotic arms in real time using hand and foot controls. The surgeon is not scrubbed. The robotic arms are scrubbed.

**Your job as the scrub tech changes fundamentally:**
- You are not handing instruments to a surgeon standing across the table from you
- You are standing at the **patient cart** (the robot), exchanging instruments on the robotic arms and passing everything through the **assistant port**
- The console surgeon cannot hand anything to themselves — they depend entirely on you for sutures, clips, staplers, irrigation, and retraction through that port
- You are the surgeon's hands at the bedside

Understanding this shift is the foundation of working robotic cases.

---

## The da Vinci Platform Family

| System | Arms | Notes |
|--------|------|-------|
| **da Vinci Xi** | 4 arms | Current flagship; overhead boom; rotatable patient cart; most versatile |
| **da Vinci X** | 4 arms | Similar to Xi; fixed boom; cost-positioned system |
| **da Vinci SP** | 1 arm (3 instruments + camera through 1 port) | Single-port; 25 mm cannula; ideal for urologic and GYN single-incision cases |
| **da Vinci Si** | 4 arms | Older generation; still in service at many institutions |

Most of what follows applies to the **Xi**, which is the predominant system in active use.

---

## System Architecture: Know Your Station

```
PATIENT CART (your station)
├── 4 robotic arms docked to trocars
├── Camera arm (Arm 1): holds the 3D endoscope
├── Instrument arms (Arms 2–4): hold EndoWrist instruments
└── Assistant port: your working channel

VISION CART
├── Camera/light source
├── Insufflator
└── Energy generator (for monopolar/bipolar)

SURGEON'S CONSOLE (non-sterile)
└── Surgeon sits here; controls all arm movements remotely
```

---

## EndoWrist Instruments — What They Are and How to Exchange Them

EndoWrist instruments attach to the robotic arm cannulas. They have a **instrument life counter** — each instrument has a limited number of uses (typically 10). The system tracks this and will not allow an expired instrument to be used.

**Common EndoWrist instruments:**

| Instrument | Use |
|-----------|-----|
| **Maryland Bipolar Forceps** | Dissection + bipolar coagulation |
| **Monopolar Curved Scissors** | Sharp dissection + cut-mode cautery |
| **ProGrasp Forceps** | Tissue retraction; strong grasping |
| **Cadiere Forceps** | Gentle tissue grasping |
| **Large Needle Driver** | Suturing; most common needle driver |
| **Mega Needle Driver** | Heavy suturing; fascia closure |
| **Fenestrated Bipolar Forceps** | Atraumatic tissue grasping + bipolar |
| **Vessel Sealer Extend** | Vessel sealing (energy device equivalent) |
| **Tip-Up Fenestrated Grasper** | Bowel/delicate tissue handling |
| **da Vinci SureForm Stapler** | Robotic-controlled endoscopic stapler |

**Exchanging instruments on the robotic arm:**
1. Confirm the console surgeon has released control (foot pedal off the instrument clutch)
2. Press the instrument release button on the arm
3. Pull the instrument straight out along the arm axis — do not twist
4. Seat the new instrument until the locking click is felt
5. Confirm the instrument name appears on the vision cart monitor

---

## Robotic Arm Draping

The robotic arms must be draped with dedicated sterile arm drapes before the robot is docked to the patient's ports. This happens **after port placement, before docking**.

**Sequence:**
1. The circulator holds the arm drape from the outside; the scrub tech receives the sterile portion
2. The arm drape rolls over the arm from the instrument attachment point toward the base
3. Snap the drape attachment point onto the arm; confirm it is locked
4. Repeat for all four arms
5. The sterile camera is inserted into the camera arm's sterile adapter
6. The robot is then docked — the arms swing over the patient and lock onto the trocars

**Critical:** The arm drapes must not have any wrinkles or caught edges. A drape breach during docking contaminates the field.

---

## The Assistant Port — Your Primary Tool

The assistant port is typically a 10–12 mm trocar placed specifically for the bedside assistant. Everything that cannot be passed through the robotic arms must come through this port.

**What you pass through the assistant port:**
- Sutures (pre-loaded on a laparoscopic needle holder or passed as a suture loop)
- Hem-o-lok clips (laparoscopic clip applier)
- Irrigation (laparoscopic suction-irrigator)
- Additional graspers or retractors
- Specimen extraction bags (endobags)
- SureForm stapler reloads (if not using robotic stapler)
- Laparoscopic energy device (if surgeon switches to a non-robotic energy instrument)

**Passing sutures through the assistant port:**
The most common and technically demanding task. Pre-load the suture on a laparoscopic needle holder with the needle oriented correctly for the surgeon's expected direction of suturing. Pass the needle holder smoothly through the port. The console surgeon grasps the needle with a robotic needle driver and takes control.

---

## Procedure-Specific Setups — See the Specialty Chapters

The full Before You Scrub checklists, procedure steps, Watch For callouts, and closure tables for da Vinci cases live in the specialty chapters alongside their conventional counterparts. Use this chapter for platform mechanics and troubleshooting; go to the specialty chapter for the actual case setup.

| Procedure | Chapter |
|-----------|---------|
| Robotic-Assisted Radical Prostatectomy (RARP) | [Chapter 18 — Urology](Chapter_18_Urology.md) |
| Robotic-Assisted Total Laparoscopic Hysterectomy (da Vinci TLH) | [Chapter 17 — OB/GYN](Chapter_17_OB_GYN.md) |
| Robotic Nissen Fundoplication (adult) | [Chapter 13 — General Surgery](Chapter_13_General_Surgery.md) |
| Robotic Nissen Fundoplication (pediatric) | [Chapter 22 — Pediatric Surgery](Chapter_22_Pediatric_Surgery.md) |
| Robotic VATS Lobectomy | [Chapter 16 — Cardiovascular & Thoracic](Chapter_16_Cardiovascular_Thoracic.md) |

---

## Robotic Case Troubleshooting at the Bedside

| Problem | Your Response |
|---------|--------------|
| Instrument won't release from the arm | Do NOT force it; press the manual release button on the back of the arm; if still stuck, notify the console surgeon to release control |
| Instrument counter expired mid-case | Open a new instrument of the same type; the expired instrument must come off the arm |
| Robotic arm drape tears intraoperatively | The contaminated arm must be re-draped; declare the breach, stop the case momentarily, re-drape the affected arm |
| Console surgeon calls "arm collision" | Both arms must be manually repositioned to clear the collision; console surgeon will direct which arm to move first |
| Smoke/plume at the port | Increase suction through the assistant port; the AirSeal (if in use) handles this automatically |
| Power failure / robot fault | The robot locks in place; the console surgeon will direct manual arm repositioning if needed; laparoscopic backup instruments should be immediately available |

---

## Clinical Pearls

> "In robotic surgery, the scrub tech at the bedside is the surgeon's hands. The console surgeon has complete visual control and zero physical access. You are the only person who can give them what they need."

- Pre-load every suture before it's called. A console surgeon mid-dissection cannot stop and wait 90 seconds for you to find and load a 3-0 Monocryl. Know the case; know when the suture step is coming; have it in your hand.
- Instrument arm crashes are preventable. When the robot is docking, watch for arms that are crossing each other. Alert the circulator before docking begins if a collision path is obvious.
- Never grab a robotic arm to reposition it without confirming the console surgeon has released control. The arms move with significant torque — an arm under power will injure your hand.
- Know the difference between the robotic energy instruments (EndoWrist Vessel Sealer, bipolar Maryland) and what can come through the assistant port. The two systems do not share instruments.

---

*[Next: Chapter 22B — Robotic Surgery: Orthopedic & Spine](Chapter_22B_Robotic_Orthopedic_Spine.md)*
