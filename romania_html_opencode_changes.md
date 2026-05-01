# Romania Luxury Journey HTML – Requested Changes

Apply the following changes to `romania_luxury_journey.html`.

Skip all image-related changes for now.

---

## 1. Fix Day 3 main dinner text

### Find

```html
<p class="mt-5 text-[1.1rem] leading-8 text-text-secondary">Late afternoon in the citadel. Dinner at Joseph T or Casa Georgius Krauss. Medieval setting, unforgettable meal.</p>
```

### Replace with

```html
<p class="mt-5 text-[1.1rem] leading-8 text-text-secondary">Late afternoon in the citadel. Dinner at Joseph Haydn House — an intimate, refined setting within the medieval citadel.</p>
```

---

## 2. Fix hotel nights in accommodation section

The current accommodation section incorrectly lists:
- Sighișoara · 2 nights
- Sibiu · 1 night

It should be:
- Brașov · 2 nights
- Sighișoara · 1 night
- Sibiu · 2 nights
- Otopeni · 1 night

### Find

```html
<div class="mini-label mb-3">Sighișoara · 2 nights</div>
```

### Replace with

```html
<div class="mini-label mb-3">Sighișoara · 1 night</div>
```

### Find

```html
<div class="mini-label mb-3">Sibiu · 1 night</div>
```

### Replace with

```html
<div class="mini-label mb-3">Sibiu · 2 nights</div>
```

---

## 3. Improve Day 1 closing sentence

### Find

```html
<p class="mt-5 text-[1.1rem] leading-8 text-text-secondary">Scenic mountain drive to Brașov. Evening arrival in Old Town. Dinner at Dei Frati. Rest well.</p>
```

### Replace with

```html
<p class="mt-5 text-[1.1rem] leading-8 text-text-secondary">Scenic mountain drive to Brașov. Arrival in Old Town. Dinner at Dei Frati. A confident, elegant start.</p>
```

---

## 4. Improve Day 2 closing sentence

### Find

```html
<p class="mt-5 text-[1.1rem] leading-8 text-text-secondary">Afternoon: Bran Castle visit. Optional Bear Sanctuary for those who want a nature counterpoint. Dinner back in Brașov.</p>
```

### Replace with

```html
<p class="mt-5 text-[1.1rem] leading-8 text-text-secondary">Afternoon: Bran Castle visit. Optional Bear Sanctuary for those who want a nature counterpoint. Return to Brașov for a relaxed, unhurried evening.</p>
```

---

## 5. Improve Day 3 first paragraph wording

### Find

```html
<p class="mt-8 text-[1.1rem] leading-8 text-text-secondary">From authentic Saxon village to medieval citadel. Viscri brings real rural texture. Sighișoara brings theater and color.</p>
```

### Replace with

```html
<p class="mt-8 text-[1.1rem] leading-8 text-text-secondary">From authentic Saxon village to medieval citadel. Viscri brings real rural texture. Sighișoara brings atmosphere, color, and a true sense of place.</p>
```

---

## 6. Improve Day 5 option text

### Find

```html
<p class="mt-8 text-[1.1rem] leading-8 text-text-secondary">Option A: Relaxed day in Sibiu. ASTRA Museum, discreet shopping, terrace time, no pressure.</p>
<p class="mt-5 text-[1.1rem] leading-8 text-text-secondary">Option B: Corvin Castle for a final dramatic moment. Gothic splendor for those wanting another castle impact.</p>
```

### Replace with

```html
<p class="mt-8 text-[1.1rem] leading-8 text-text-secondary">Option A: A relaxed day in Sibiu — culture, terraces, and no pressure.</p>
<p class="mt-5 text-[1.1rem] leading-8 text-text-secondary">Option B: Corvin Castle — a final, dramatic Gothic highlight.</p>
```

---

## 7. Adjust transport slide to subtly favor private van

### Find

```html
<h3 class="font-display text-[1.75rem]">Option 1: Private Van & Driver</h3>
<p class="mt-5 text-text-secondary leading-7">No driving. No parking stress. No compromise on comfort. The focus stays on experience and shared moments.</p>
<p class="mt-4 text-text-muted text-[0.95rem]">Professional driver handles all logistics. Flexible routing accommodates early departures. Premium and calm.</p>
```

### Replace with

```html
<h3 class="font-display text-[1.75rem]">Option 1: Private Van & Driver</h3>
<p class="mt-5 text-text-secondary leading-7">The most seamless and relaxed way to experience the journey. No driving, no parking stress, and no compromise on comfort.</p>
<p class="mt-4 text-text-muted text-[0.95rem]">A professional driver handles the logistics while the group stays focused on the experience, the scenery, and shared moments.</p>
```

### Find

```html
<h3 class="font-display text-[1.75rem]">Option 2: Self-Drive</h3>
<p class="mt-5 text-text-secondary leading-7">Rent a premium vehicle and drive at your own pace. Experience the freedom of the open road through Romania's most scenic routes.</p>
<p class="mt-4 text-text-muted text-[0.95rem]">All rental logistics arranged. Full flexibility on timing and stops. Your journey, your rhythm.</p>
```

### Replace with

```html
<h3 class="font-display text-[1.75rem]">Option 2: Self-Drive</h3>
<p class="mt-5 text-text-secondary leading-7">Best suited for travelers who specifically enjoy driving and want full control over timing and stops.</p>
<p class="mt-4 text-text-muted text-[0.95rem]">A flexible alternative, but less seamless for a group journey with multiple couples and luggage.</p>
```

### Find

```html
<div class="reveal mt-8 max-w-[820px] text-[1.08rem] leading-8 text-text-secondary">Choose your style: relax and be driven through luxury landscapes, or take the wheel and explore at your own rhythm. Both approaches deliver the same curated experience.</div>
```

### Replace with

```html
<div class="reveal mt-8 max-w-[820px] text-[1.08rem] leading-8 text-text-secondary">Recommended approach: private van with driver. It keeps the trip calm, social, and effortless while preserving flexibility for scenic stops and early departures.</div>
```

---

## 8. Improve closing call-to-action

### Find

```html
<p class="reveal mt-10 text-[0.95rem] tracking-[0.18em] text-text-muted uppercase">Ready to explore?</p>
```

### Replace with

```html
<p class="reveal mt-10 text-[0.95rem] tracking-[0.18em] text-text-muted uppercase">Ready when you are.</p>
```

---

## 9. Optional consistency pass

After applying the replacements above, search the file for these terms and review whether they still fit the premium tone:

```text
simple
good
nice
fun
```

Do not remove them blindly. Only replace if they feel generic or low-end in context.

---

## 10. Do not change images yet

Do not update image URLs in this pass. Image replacement will be handled separately.
