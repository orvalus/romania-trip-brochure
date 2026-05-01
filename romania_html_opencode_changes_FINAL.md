# Romania Luxury Journey HTML – FINAL Combined Changes (OpenCode)

Apply all changes to `romania_luxury_journey.html`.

This file combines:
- restaurant description shortening (1 line)
- removal of hotel slide
- moving hotels into each day
- final spacing/layout polish
- final text polish

DO NOT change images in this pass.

---

## 1. Shorten restaurant descriptions (single line)

Replace all descriptions with:

Kuib (Sinaia) -> Light seasonal lunch — a perfect reset after arrival  
Dei Frati (Brașov) -> Elegant first dinner — one of Brașov’s best tables  
Sub Tâmpa (Brașov) -> Relaxed lunch with panoramic views  
Bistro de l’Arte (Brașov) -> Intimate evening with an artistic local feel  
Rural guesthouse (Viscri) -> Traditional village lunch — authentic and local  
Joseph Haydn House (Sighișoara) -> Intimate dinner within the medieval citadel  
Casa Terra (Biertan area) -> Countryside lunch — simple and local  
Kombinat (Sibiu) -> Contemporary, lively — a modern contrast  
Lumina (Sibiu) -> Polished, central — relaxed lunch  
Kulinarium (Sibiu) -> Refined final dinner — quiet closing moment  
Bâlea Lac -> Scenic mountain lunch with alpine views  

---

## 2. Remove hotel slide completely

Delete:

<!-- ACCOMMODATIONS -->
<div class="slide" data-slide="...">
...
</div>

---

## 3. Add “Stay” block in each day

Insert after meals:

```html
<div class="text-[0.86rem]">
  <div class="text-text-muted uppercase tracking-wide text-[0.72rem] mb-1">Stay</div>
  <div class="text-text-secondary font-medium">[Hotel]</div>
</div>
```

Hotels:

Day 1 → Radisson Blu Aurum (Brașov)  
Day 2 → Radisson Blu Aurum (Brașov)  
Day 3 → Fronius Residence (Sighișoara)  
Day 4 → Noblesse Boutique (Sibiu)  
Day 5 → Noblesse Boutique (Sibiu)  
Day 6 → Hilton Garden Inn (Otopeni)  

---

## 4. Compact layout spacing

Replace:

```html
space-y-3
```

with:

```html
space-y-2
```

Replace:

```html
text-[0.9rem]
```

with:

```html
text-[0.82rem] leading-snug
```

---

## 5. Fix slide numbering

Ensure:

Transport → data-slide="10"  
Closing → data-slide="11"  

Counter:

```html
1 / 11
```

---

## 6. Text polish

### Why Romania

Replace with:

True luxury here isn’t excess. It’s access, rhythm, real culture, and the rare feeling of discovery.

---

### Day 3 fix

Ensure ONLY:

Dinner at Joseph Haydn House — an intimate, refined setting within the medieval citadel.

---

### Day 6

Replace with:

Final night near the airport — calm, effortless, and ready for a smooth departure the next morning.

---

### Closing CTA

Ensure:

Ready when you are.

---

## 7. Transport tone

Private van text:

“The most seamless and relaxed way to experience the journey.”

Self-drive:

“Best suited for travelers who specifically enjoy driving.”

---

## 8. Final check

Verify:
- no wrapping restaurant text
- clean spacing
- no duplicate restaurants
- no leftover hotel slide
- each day has Stay block

---

END
