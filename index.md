# App Store Metadata — FoodScan

## General

| Field | Value |
|---|---|
| Bundle ID | (set in Xcode project settings) |
| Primary language | Norwegian Bokmål |
| Secondary language | English |
| Category | Food & Drink |
| Age rating | 4+ (no objectionable content) |
| Price | Free (with one-time in-app purchase: FoodScan Pro) |

---

## English

### Name (30 chars max)
```
FoodScan
```

### Subtitle (30 chars max)
```
Ingredient scanner & checker
```

### Description (4000 chars max)
```
FoodScan helps you understand what's in your food — before you buy it.

Scan a barcode, point the camera at an ingredient label, or paste a list manually. FoodScan instantly checks every ingredient against your personal rules and flags anything you want to avoid.

SCAN THREE WAYS
• Barcode scanner — looks up products from Open Food Facts and analyses the ingredient list
• Camera scan — point at any ingredient text and let on-device OCR read it for you
• Manual entry — paste or type an ingredient list for immediate analysis

PERSONAL PROFILES
Create a profile for each family member with their own rules. One person avoids gluten, another is lactose intolerant, a third watches for ultra-processed additives — FoodScan tracks each profile separately.

BUILT-IN RULE PACKAGES
Ready-to-use rule sets cover the most common food concerns:
• Gluten (wheat, rye, barley, oats, spelt, malt, seitan)
• Lactose (milk, cream, whey, casein, yogurt)
• Added sugars (sucrose, glucose, fructose, HFCS, syrups, and more)
• Sweeteners (aspartame, sucralose, acesulfame K, stevia, sugar alcohols)
• Ultra-processed indicators (maltodextrin, emulsifiers, modified starch, flavourings)

COMPLETELY PRIVATE
Everything stays on your device. No account, no cloud sync, no scan history sent anywhere. Barcode lookups contact Open Food Facts (non-profit, open data) — no personal data is included.

FOODSCAN PRO (ONE-TIME PURCHASE)
• Multiple profiles for the whole family
• Unlimited personal avoid-list entries
• Custom rule packages you build yourself
• Import and export rules as JSON

No subscription. Pay once, yours forever.
```

### Keywords (100 chars max, comma-separated)
```
food,ingredients,scanner,gluten,lactose,allergen,additives,barcode,labels,diet
```

### What's New (4000 chars max) — Version 1.0
```
Welcome to FoodScan! Scan barcodes, ingredient labels, or paste text to instantly check against your personal rules. Supports Norwegian and English.
```

### Support URL
```
https://github.com/kjand/FoodScan
```

### Privacy Policy URL
```
https://kjand.github.io/foodscan-support/privacy
```

---

## Norwegian Bokmål

### Navn (maks 30 tegn)
```
FoodScan
```

### Undertittel (maks 30 tegn)
```
Ingrediensscanner og -sjekker
```

### Beskrivelse (maks 4000 tegn)
```
FoodScan hjelper deg å forstå hva som er i maten – før du kjøper den.

Skann en strekkode, pek kameraet mot en ingrediensliste, eller lim inn teksten manuelt. FoodScan sjekker øyeblikkelig alle ingredienser mot dine personlige regler og markerer alt du vil unngå.

TRE MÅTER Å SKANNE PÅ
• Strekkodesanner – slår opp produkter fra Open Food Facts og analyserer ingredienslisten
• Kameraskann – pek mot ingredienstekst og la enhetsbasert tekstgjenkjenning lese den for deg
• Manuell innskriving – lim inn eller skriv en ingrediensliste for umiddelbar analyse

PERSONLIGE PROFILER
Opprett en profil for hvert familiemedlem med egne regler. Én unngår gluten, en annen er laktoseintolerant, en tredje er opptatt av ultraprosesserte tilsetningsstoffer – FoodScan holder styr på hver profil separat.

INNEBYGDE REGELPAKKER
Ferdige regelset dekker de vanligste matkostnadene:
• Gluten (hvete, rug, bygg, havre, spelt, malt, seitan)
• Laktose (melk, fløte, myse, kasein, yoghurt)
• Tilsatt sukker (sakkarose, glukose, fruktose, fruktose-glukosesirup og mer)
• Søtstoffer (aspartam, sukralose, acesulfam K, stevia, sukkeralkoholer)
• Ultraprosesseringsmarkører (maltodekstrin, emulgatorer, modifisert stivelse, aroma)

FULLSTENDIG PRIVAT
Alt lagres på enheten din. Ingen konto, ingen skysynkronisering og ingen skannehistorikk sendes noe sted. Strekkodesøk kontakter Open Food Facts (ideell organisasjon, åpne data) – ingen personopplysninger er inkludert.

FOODSCAN PRO (ENGANGSBELØP)
• Flere profiler for hele familien
• Ubegrenset antall personlige unngå-listeoppføringer
• Egendefinerte regelpakker du bygger selv
• Importer og eksporter regler som JSON

Ikke abonnement. Betal én gang, ditt for alltid.
```

### Nøkkelord (maks 100 tegn, kommaseparert)
```
mat,ingredienser,scanner,gluten,laktose,allergen,tilsetningsstoffer,strekkode,diett
```

### Hva er nytt — Versjon 1.0
```
Velkommen til FoodScan! Skann strekkoder, ingredienslister eller lim inn tekst for å sjekke mot dine personlige regler. Støtter norsk og engelsk.
```

---

## Screenshots needed

Required sizes (iPhone):
- **6.9"** (iPhone 16 Pro Max): 1320 × 2868 px — need at least 3, up to 10
- **6.1"** (iPhone 16): 1179 × 2556 px — (can use same images as 6.9" if aspect ratio matches)

Suggested screens to capture (in Norwegian AND English):
1. Home / scan method selection screen
2. Barcode scan result with flagged ingredients
3. OCR scan result
4. Profile/rules setup screen
5. Ingredient rule package detail

Simulator: Use iPhone 17 (`platform=iOS Simulator,name=iPhone 17`)

To capture: File → Export Screenshot in Xcode, or `xcrun simctl io booted screenshot screenshot.png`

---

## App Store Connect checklist

- [ ] Create app record in App Store Connect
- [ ] Set bundle ID to match Xcode project
- [ ] Upload screenshots for 6.9" and 6.1"
- [ ] Fill in English and Norwegian metadata above
- [ ] Set Privacy Policy URL: `https://kjand.github.io/FoodScan/privacy`
- [ ] Set Support URL: `https://github.com/kjand/FoodScan`
- [ ] Configure In-App Purchase: FoodScan Pro (product ID: `foodscan_pro_001`)
- [ ] Set age rating (4+)
- [ ] Upload build via TestFlight
- [ ] Submit for review
