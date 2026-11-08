# Hi, I'm Felippe Meirelles 👋

**Technical Coordinator at [Tecnosul](https://www.grupotecnosul.com.br)**, an authorized service center for Tecnomotor automotive diagnostic equipment in Rio Grande do Sul, Brazil.

I work where **automotive electronics meets software**: I diagnose and repair diesel common rail test benches and diagnostic scanners on the bench and in the field, and I build the tools that take manual work out of that process.

- 🔧 Electronics diagnostics: oscilloscope measurement, board-level fault finding, root-cause reports for manufacturer escalation
- ⛽ Diesel common rail: injector and bench testing, cross-bench measurement correlation
- 💻 Software for technical operations: web systems, offline field apps, bench automation
- 📍 Montenegro, RS, Brazil · 🇧🇷 Portuguese (native) · 🇺🇸 English (learning)

---

## 🛠️ What I build

### Technical service platform
Company web system for an equipment repair center: a public portal where customers fill out equipment shipment forms, a restricted technical area with access controlled per authorized user, and internal tools for the service and sales teams. A local server pushes a daily update to the cloud, with no open ports on the office network.
`Cloudflare Workers` `JavaScript` `HTML/CSS`

### Offline field service report app
Installable PWA used by field technicians with no signal. It builds standardized service reports, imports service order PDFs, sequences photos and flags labor limits per equipment family.
`PWA` `Service Worker` `JavaScript` `PDF generation`

### Bench maintenance checklist
Offline step-by-step checklist for test bench maintenance, designed for greasy hands: one step per screen, large buttons, a photo per step and an automatic PDF report at the end.
`PWA` `Camera API` `PDF generation`

### Diagnostic scanner board tester
In-house desktop tool for hardware testing of automotive diagnostic scanner boards during repair.
`Desktop` `Hardware testing`

### Injector bench durability automation
Automation that repeats the same injector test on a common rail bench to detect leaks or drift over many cycles. It detects the end of each test by screen stability, with no OCR and no pixel coordinates, so it is independent of the PC and screen resolution. A standalone Python app is in progress.
`AutoHotkey` `PowerShell` `Python (in progress)`

### Warranty report generator
Standalone web app that turns service data into warranty reports following the manufacturer's labor and parts pricing rules.
`JavaScript` `jsPDF`

### 🚧 In progress
- **Test plan coverage lookup:** keeps the injector/valve test catalog updated automatically and publishes it so the sales team can check coverage from their phones.
- **AI diagnostic assistant:** voice-driven assistant for bench technicians that turns solved cases into a searchable knowledge base.

---

## 🧰 Tools & stack

| Area | Tools |
|---|---|
| Electronics | Oscilloscope, bench power supply, board-level repair |
| Diesel | Common rail test benches, injector testing and correlation |
| Web & cloud | JavaScript, HTML/CSS, PWA, Cloudflare Workers / D1 / R2 |
| Automation | PowerShell, AutoHotkey, Python |
| Workflow | Git, AI-assisted development (Claude, OpenCode) |

---

## 📫 Contact
Open to talking about automotive diagnostics, test equipment integration and tools for technical service teams.
Company: [grupotecnosul.com.br](https://www.grupotecnosul.com.br)
