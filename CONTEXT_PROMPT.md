# Context Prompt pentru Proiectul Romania Luxury Brochure

## **Proiect:** Romania: A Private Journey — Interactive HTML Brochure

### **Descriere generală:**
Dezvolt o broșură de lux interactivă în HTML5 care prezintă o călătorie privată de 7 zile prin România și Transilvania (25 iunie - 1 iulie 2026). Broșura este gazduită pe GitHub Pages și conține 13 slide-uri cu design ultra-elegant, tema întuneric cu accente de aur, și o experiență cinematică minimalistă.

---

## **Structura broșurii (13 slide-uri):**

1. **Cover** — Hero image (Peleș Castle)
2. **Why Romania** — Pitch cu imagine Transfăgărășan
3. **Journey Highlights** — 6 carduri (Peleș, Bran, Brașov, Viscri, Sighișoara, Sibiu)
4. **Day 1** — Bucharest → Sinaia → Brașov
5. **Day 2** — Brașov & Bran Castle
6. **Day 3** — Viscri → Sighișoara
7. **Day 4** — Sighișoara → Biertan → Sibiu
8. **Day 5** — Sibiu & Corvin Castle (combinat)
9. **Day 6** — Transfăgărășan → Bucharest (finală)
10. **Transport** — 2 opțiuni (Private Van & Driver / Self-Drive)
11. **Additional Experiences** — 5 carduri individuale + 1 card grupat pentru vinuri
12. **Estimated Costs** — Comparație de costuri pentru 2 opțiuni (Self-Drive vs. Fully Guided Tour)
13. **Closing** — "The Promise"

---

## **Design System:**

- **Culori:**
  - Background: Dark theme (#0d0c0a)
  - Accent: Aur (#d6b17c)
  - Secondary text: #f7f2eb
  - Muted text: #bba488

- **Tipografie:**
  - Display: Cormorant Garamond (serif)
  - Body: Inter (sans-serif)

- **Stil:** Ultra-luxury, minimal, cinematic

- **Efecte:**
  - Ken Burns animation pe imagini
  - Reveal animations pe fiecare slide
  - Mouse spotlight effect
  - Gradient mesh backgrounds cu blob animations

- **Icons:** Font Awesome 6.5.1 solid icons (fără emoji)

---

## **Slide-ul Estimated Costs (Slide 12) — Detalii:**

### **Layout:** 
2 coloane principale (Option A | Option B)

### **Option A: Self-Drive / Shared Van**
- **Descriere:** Flexible · Independent · Premium Experience
- **3 carduri cu costuri:**
  - 🛏️ Accommodation (~$950 Premium | ~$550 4★ Boutique)
  - 🍷 Meals & Wine (~$140–160/day | ~$700–800 total)
  - 🚐 Passenger Van Rental (~$515 total 6 days | ~$130/family)
- **Total estimat:** ~$1,350–1,500 (Boutique) | ~$1,700–1,900 (Premium)
- **Info suplimentară:**
  - ~$250–300 per day per family (average)
  - Zilele pot fi omise flexibil fără a afecta fluxul

### **Option B: Fully Guided Tour (Optional Upgrade)**
- **Descriere:** Structured · Fully Organized · Hands-Off Experience
- **Cost:** ~$1,000–1,500 per person | ~$2,000–3,000 per family
- **Meals & Wine (NOT INCLUDED):** ~$140–160/day | ~$700–800 total
- **What's Included:**
  - ✓ Transport with driver and guide
  - ✓ Accommodation
  - ✓ Entry tickets to main attractions (~$40/day value)
  - ✓ Full itinerary coordination
- **Important:** Fixed itinerary — days cannot be removed or adjusted

### **Bottom Message:**
Comparație cu star accent: "The guided option offers a fully organized experience, while the self-drive option provides greater flexibility and a significantly lower overall cost."

### **Icons utilizate:**
- `fa-bed` — Accommodation
- `fa-wine-glass` — Meals & Wine (Option A)
- `fa-van-shuttle` — Passenger Van Rental
- `fa-calendar-days` — Average Per Day
- `fa-arrows-rotate` — Flexibility
- `fa-users` — Cost (Option B)
- `fa-utensils` — Meals & Wine (Option B)
- `fa-ticket` — What's Included
- `fa-circle-info` — Important Notice
- `fa-check` — Checkmarks

### **Styling icons:**
```css
color: var(--color-accent-1);
font-size: 1.6rem;
opacity: 0.85;
```

---

## **Stack tehnic:**

- **HTML5** + **Tailwind CSS** (CDN v4)
- **Vanilla JavaScript** (navigation keyboard, mouse, touch)
- **Google Fonts** (Cormorant Garamond + Inter)
- **Font Awesome 6.5.1** (solid icons)
- **Fără build process** — rulează direct în browser
- **Imagini locale** în folderul `/images/` (30 fișiere)

---

## **Caracteristici funcționale:**

- ✅ Navigare cu tastele săgeți, Space, click pe dots
- ✅ Touch swipe support pe mobile
- ✅ Lightbox pentru galerii de imagini
- ✅ Reveal animations la fiecare slide
- ✅ Mouse spotlight effect
- ✅ Fully responsive cu mobile scroll support
- ✅ Page numbering și slide counter
- ✅ Ken Burns animation pe hero images

---

## **Status curent:**

- ✅ 13 slide-uri complete și funcționale
- ✅ Toate imaginile locale și optimizate
- ✅ Design system consistent
- ✅ Navigație perfectă
- ✅ Mobile responsive
- ✅ Deployed pe GitHub Pages
- ✅ Estimated Costs slide actualizată cu Font Awesome icons

---

## **Locație GitHub & Resurse:**

- **Repository:** https://github.com/orvalus/romania-trip-brochure
- **GitHub Pages:** https://orvalus.github.io/romania-trip-brochure/
- **Branch:** main
- **Working Directory (local):** `/home/cornel/src/brosura`
- **Main File:** `index.html`

---

## **Fișiere din proiect:**

- `index.html` — File principal cu toate slide-urile și styling
- `PROJECT_CONTEXT.md` — Documentație detaliată a proiectului
- `CONTEXT_PROMPT.md` — Acest fișier (prompt-ul de context)
- `/images/` — Folder cu 30 imagini locale
- `.gitignore` — Exclude *.Zone.Identifier și *.deb

---

## **Cum să folosești acest prompt:**

- 📝 Atunci când lucrezi cu alți developeri la proiect
- 🚀 Când trebuie să explici contextul rapid
- 🆘 Când ceri ajutor pentru feature-uri noi
- 📚 Pentru documentarea schimbărilor
- 🔄 Ca referință pentru QA și testing

---

**Ultima actualizare:** 1 mai 2026  
**Versiune:** 2.0
