# Proofreading Report: Triumph 2025 Yearbook Website

**Date:** March 18, 2026  
**Spreadsheet graduates:** 928  
**Database posts (portfolio/publish):** 936  
**Matched by name:** 919  
**Missing from DB (in SS only):** 9  
**Extra in DB (not in SS):** 0  
**Duplicate names in DB:** 17  
**Total issues found:** 117 (HIGH: 117, LOW: 0)  

---

## Important Notes for Encoders

1. **Spreadsheet as source of truth**: In most cases, the spreadsheet value should be used as the authoritative source. Update the DB to match the spreadsheet.
2. **SS typo cases (verify before fixing)**: Some quote mismatches occur because the *spreadsheet* contains a typo that was corrected in the DB. In these cases, the DB is likely correct. Verify both sides before making changes:
   - `Borreta, Meabel L.` — SS has "peacefull" (double-l), DB has "peaceful" (correct spelling)
   - `Garza, Jasmine Amelia M.` — SS has "deafing", DB has "deafening" (correct spelling)
   - `Bernales, Jaye Anne P.` — SS has "sleeplness", DB has "sleepless" (correct spelling)
   - `Consuelo, Neil Christian V.` — SS has "perservered" and "thats", DB has "persevered" and "that's" (correct)
   - `Orasa, Ronel P.` — SS has "Univeristy" (typo), DB has "University" (correct)
   - `Sabularse, Melgar B.` — SS has "Philipine", should be "Philippine"
3. **'x' placeholder quotes** (`Ibe, John Emmanuel R.` and `Sabularse, Melgar B.`): The SS revised quote column has 'x' as a placeholder — these graduates have not yet submitted their final quote. No action needed unless a quote is later provided.
4. **Duplicate records**: For all DUPLICATE_RECORD issues, review both posts in WordPress. Keep the post with correct and complete content; delete the other.
5. **Missing records (MISSING_RECORD)**: These graduates need new portfolio posts created from scratch using data from the spreadsheet.

---

## Issue Type Key

| Type | Description |
|------|-------------|
| `MISSING_RECORD` | Graduate in spreadsheet has no post in DB |
| `EXTRA_RECORD` | Post in DB not found in spreadsheet |
| `DUPLICATE_RECORD` | Same graduate appears multiple times in DB |
| `TITLE_MISMATCH` | Post title in DB differs from spreadsheet name |
| `QUOTE_MISMATCH` | Tagline/quote differs between DB and spreadsheet |
| `ACHIEVEMENT_MISMATCH` | An achievement item wording differs |
| `ACHIEVEMENT_MISSING_FROM_DB` | Achievement in spreadsheet missing from DB |
| `ACHIEVEMENT_EXTRA_IN_DB` | Achievement in DB not present in spreadsheet |
| `ACHIEVEMENTS_MISSING` | DB has no achievements but spreadsheet has some |
| `AFFILIATION_MISMATCH` | An affiliation item wording differs |
| `AFFILIATION_MISSING_FROM_DB` | Affiliation in spreadsheet missing from DB |
| `AFFILIATION_EXTRA_IN_DB` | Affiliation in DB not present in spreadsheet |
| `AFFILIATIONS_MISSING` | DB has no affiliations but spreadsheet has some |
| `COURSE_MISMATCH` | Course field differs between DB and spreadsheet |
| `COLLEGE_MISMATCH` | College field in DB doesn't match expected college |
| `SPURIOUS_QUOTES` | List item has stray double-quote character |

---

## College of Business and Accountancy (CBA)

### Abejero, Vince Michael T.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 2037, 2041. Keep the correct one and delete the rest.
  - **Database:** `2037, 2041`

### Alcober, Kylydia B.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Alcober, Kylydia B.' (CBA, row 285) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Alcober, Kylydia B.`

### Basilla, Maxine Louise N.

- **[HIGH]** `SPURIOUS_QUOTES` — **Affiliations**: Affiliation item has spurious quote character: "RAC AdNU - Member (2022-2023)""
  - **Database:** `RAC AdNU - Member (2022-2023)"`

### Borreta, Meabel L.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: Minor diff (sim=0.71): DB="Leading through quiet scenes is about embracing the silence as a powerful tool. I create a peaceful mind, appreciating a" | SS="Leading through quiet scenes is about embracing the silence as a powerful tool. I create a peacefull mind, appreciating "
  - **Spreadsheet:** `Leading through quiet scenes is about embracing the silence as a powerful tool. I create a peacefull mind, appreciating and realizing things.`
  - **Database:** `Leading through quiet scenes is about embracing the silence as a powerful tool. I create a peaceful mind, appreciating and realizing things.`

### Brecio, Erika Nicole A.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="I kept moving forward, often unsure but always with hope. After all, "you're on your own, kid… you always have been," an" | SS="I kept moving forward—often unsure, but always with hope. After all, "you're on your own, kid… you always have been", an"
  - **Spreadsheet:** `I kept moving forward—often unsure, but always with hope. After all, "you're on your own, kid… you always have been", and still, I made it.`
  - **Database:** `I kept moving forward, often unsure but always with hope. After all, "you're on your own, kid… you always have been," and still, I made it.`

### Bulao, Ana Mae P.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="In my quietest scenes, I led with one big heart—serving in silence, shooting with purpose, and trusting God beyond the s" | SS="In quiet moments, I leaned into calm-listening to the whispers of faith and wisdom, allowing gentle courage and trust to"
  - **Spreadsheet:** `In quiet moments, I leaned into calm-listening to the whispers of faith and wisdom, allowing gentle courage and trust to guide each unseen journey.`
  - **Database:** `In my quietest scenes, I led with one big heart—serving in silence, shooting with purpose, and trusting God beyond the scoreboard.`

### Cilo, Maxine M.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="To survive quietly is to cultivate a deep well of inner peace, drawing strength from within to navigate the challenges l" | SS="I've listened carefully, absorbed differences, creating thoughtful responses that prioritized clarity and comprehension "
  - **Spreadsheet:** `I've listened carefully, absorbed differences, creating thoughtful responses that prioritized clarity and comprehension above fast action.`
  - **Database:** `To survive quietly is to cultivate a deep well of inner peace, drawing strength from within to navigate the challenges life throws my way.`

### Clacio, Kathleen Ann C.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="In silence, I wasn't lost. It led me to choose what's right, what's worthy, and which battles to fight—letting go of dis" | SS=""In silence, I listened, learned, and grew—proving that strength isn't always loud, but it's always present.""
  - **Spreadsheet:** `"In silence, I listened, learned, and grew—proving that strength isn't always loud, but it's always present."`
  - **Database:** `In silence, I wasn't lost. It led me to choose what's right, what's worthy, and which battles to fight—letting go of distractions that didn't serve me`

### Dacuya, Aileen, H.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="During moments of silence, I step away from social media, connect more to nature, and draw closer to God.This is the tim" | SS="During moments of silence, I step away from social media, connect with nature, and draw closer to God. It is a time for "
  - **Spreadsheet:** `During moments of silence, I step away from social media, connect with nature, and draw closer to God. It is a time for prayer and contemplation.`
  - **Database:** `During moments of silence, I step away from social media, connect more to nature, and draw closer to God.This is the time to pray and contemplate.`

### Dado, Mark Anthony SA.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['AdN-L Season 1 Battle of the bands - Champion']
  - **Spreadsheet:** `AdN-L Season 1 Battle of the bands - Champion`

### Falogme, Ron Stevens S.P.

- **[HIGH]** `COURSE_MISMATCH` — **Course**: DB: "BS Tourism Management" | SS: "BS Tourism major in Development Tourism Management"
  - **Spreadsheet:** `BS Tourism major in Development Tourism Management`
  - **Database:** `BS Tourism Management`

### Gonzales, Dawn F.

- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "PCSKV - Kaabay Volunteer (2022-2025)" is in SS but missing from DB
  - **Spreadsheet:** `PCSKV - Kaabay Volunteer (2022-2025)`
- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "AFS - Member (2022-2025)" is in SS but missing from DB
  - **Spreadsheet:** `AFS - Member (2022-2025)`
- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "RAC AdNU - Member (2024-2025" is in SS but missing from DB
  - **Spreadsheet:** `RAC AdNU - Member (2024-2025`
- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "CMSV - Member (2024-2025)" is in SS but missing from DB
  - **Spreadsheet:** `CMSV - Member (2024-2025)`
- **[HIGH]** `AFFILIATION_EXTRA_IN_DB` — **Affiliations**: "LMIANS - Year Level Representative (2022-2023), Auditor (2023-2024)" is in DB but NOT in SS
  - **Database:** `LMIANS - Year Level Representative (2022-2023), Auditor (2023-2024)`

### Habala, Lizlyn May S.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="Grit & Grace— My grit and grace sustained, led, and strengthened me through the quietest scenes of my purposeful college" | SS="Grit and Grace—My grit and grace sustained me, guided me, and gave me strength through the quietest scenes of my purpose"
  - **Spreadsheet:** `Grit and Grace—My grit and grace sustained me, guided me, and gave me strength through the quietest scenes of my purposeful college journey.`
  - **Database:** `Grit & Grace— My grit and grace sustained, led, and strengthened me through the quietest scenes of my purposeful college journey.`

### Illo, Laurence Jemina M.

- **[HIGH]** `SPURIOUS_QUOTES` — **Achievements**: Achievement item has spurious quote character: "Best Research Presentation - 19th Global Business Conference ""AI Meets Global B"
  - **Database:** `Best Research Presentation - 19th Global Business Conference ""AI Meets Global Business""`

### Luares, Aliyah Jellai P.

- **[HIGH]** `AFFILIATION_MISMATCH` — **Affiliations**: SS: "TA - Volunteer (2022-2023), Business Manager (2023-2025)" | DB: "TA - Volunteer (2022-2023), B usiness Manager (2023-2025)"
  - **Spreadsheet:** `TA - Volunteer (2022-2023), Business Manager (2023-2025)`
  - **Database:** `TA - Volunteer (2022-2023), B usiness Manager (2023-2025)`

### Neverio, Neazylle Karen S.

- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "ABBS ADNU Chapter - Safe Space Officer (2024-2025)," is in SS but missing from DB
  - **Spreadsheet:** `ABBS ADNU Chapter - Safe Space Officer (2024-2025),`
- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "TADA - Treasurer (2024-2025)," is in SS but missing from DB
  - **Spreadsheet:** `TADA - Treasurer (2024-2025),`
- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "AFS - External Vice President (2025)" is in SS but missing from DB
  - **Spreadsheet:** `AFS - External Vice President (2025)`
- **[HIGH]** `AFFILIATION_EXTRA_IN_DB` — **Affiliations**: "ADNU Gabay Scholars' Organization - Member (2023-2025)" is in DB but NOT in SS
  - **Database:** `ADNU Gabay Scholars' Organization - Member (2023-2025)`
- **[HIGH]** `AFFILIATION_EXTRA_IN_DB` — **Affiliations**: "LMIANS - Member (2021-2025)" is in DB but NOT in SS
  - **Database:** `LMIANS - Member (2021-2025)`

### Ramos, Maria Katrina O.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="In silence, I explore deeply and act boldly, creating moments that speak louder than noise—privately building the life I" | SS="With gratitude and appreciation for the much preferred environment"
  - **Spreadsheet:** `With gratitude and appreciation for the much preferred environment`
  - **Database:** `In silence, I explore deeply and act boldly, creating moments that speak louder than noise—privately building the life I dare to live without limits.`

### Rosales, Nicolle S.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="In my quietest moments, I doubted a lot but I believed a little louder. They said, "Believe you can.." so I did. One ste" | SS="In my quietest moments, I doubted a lot—but I believed a little louder. They said, "Believe you can," so I did. One step"
  - **Spreadsheet:** `In my quietest moments, I doubted a lot—but I believed a little louder. They said, "Believe you can," so I did. One step, one yap at a time.`
  - **Database:** `In my quietest moments, I doubted a lot but I believed a little louder. They said, "Believe you can.." so I did. One step, one yap at a time.`

### Saludes, Ella Mae

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="In silence, I find wisdom— for it is in the quiet that I learn to hear the voice within and rise above the noise." | SS="In silence, I find wisdom—for it is in the quiet that I learn to hear the voice within and rise above the noise."
  - **Spreadsheet:** `In silence, I find wisdom—for it is in the quiet that I learn to hear the voice within and rise above the noise.`
  - **Database:** `In silence, I find wisdom— for it is in the quiet that I learn to hear the voice within and rise above the noise.`

### Santiago, Kayle Rae C.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['Honorable Mention']
  - **Spreadsheet:** `Honorable Mention`

### Sio, Justine S.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 2971, 2977. Keep the correct one and delete the rest.
  - **Database:** `2971, 2977`
- **[HIGH]** `SPURIOUS_QUOTES` — **Affiliations**: Affiliation item has spurious quote character: "LMIANS - Treasurer (2022-2023)""
  - **Database:** `LMIANS - Treasurer (2022-2023)"`

### Ubaldo, Kaila Pauline V.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="With those quiet steps, I slowly took the path to success. No one to guide me, I was on my own. Yet here I am, I made it" | SS="With quiet steps, I slowly walked the path to success. There was no one to guide me—I was on my own. Yet here I am; I ma"
  - **Spreadsheet:** `With quiet steps, I slowly walked the path to success. There was no one to guide me—I was on my own. Yet here I am; I made it.`
  - **Database:** `With those quiet steps, I slowly took the path to success. No one to guide me, I was on my own. Yet here I am, I made it on my own.`

### Valencia, Lois Avril N.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="In my quietest moments, I learned to trust myself, reflect on my journey, and find peace in knowing I'm on the right pat" | SS="In silence, I listened, learned, and found strength—letting stillness shape the loudest parts of who I've become."
  - **Spreadsheet:** `In silence, I listened, learned, and found strength—letting stillness shape the loudest parts of who I've become.`
  - **Database:** `In my quietest moments, I learned to trust myself, reflect on my journey, and find peace in knowing I'm on the right path.`

### Villanueva, Ira Marie I.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Villanueva, Ira Marie I.' (CBA, row 244) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Villanueva, Ira Marie I.`

---

## College of Humanities and Social Sciences (CHSS)

### Casilihan, Jet J.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['CCD Voltz - Member (2023-2025)']
  - **Spreadsheet:** `CCD Voltz - Member (2023-2025)`

### Caymo, Angelica Mae G.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['APSA COO - Member (2022-2025), CCD VOLTZ - Member (2023-2025), TAG - Member (2024-2025)']
  - **Spreadsheet:** `APSA COO - Member (2022-2025), CCD VOLTZ - Member (2023-2025), TAG - Member (2024-2025)`

### Chan, Laurenz Winsor P.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['ACHSS - APSA Representative (2023-2024)', 'APSA - Member (2021-Present)', 'APSA COO - Member (2021-2024)']
  - **Spreadsheet:** `ACHSS - APSA Representative (2023-2024)
APSA - Member (2021-Present)
APSA COO - Member (2021-2024)`

### Garza, Jasmine Amelia M.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="Sometimes silence could also be deafening. In my moments of silence I learned to produce my own sound composing of patie" | SS="Sometimes silence could also be deafing. In my moments of silence i Iearned to produce my own sound composing of patienc"
  - **Spreadsheet:** `Sometimes silence could also be deafing. In my moments of silence i Iearned to produce my own sound composing of patience and self awareness.`
  - **Database:** `Sometimes silence could also be deafening. In my moments of silence I learned to produce my own sound composing of patience and self awareness.`

### Hernandez, Mary Joshelle C.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Hernandez, Mary Joshelle C.' (CHSS, row 103) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Hernandez, Mary Joshelle C.`

### Marquez, Alynna Kyla A.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['College Honors']
  - **Spreadsheet:** `College Honors`

### Mendioro, Salee Ann B.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['College Honors, Honorable Mention']
  - **Spreadsheet:** `College Honors, Honorable Mention`

### Nievares, Andrine Sofia C.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Nievares, Andrine Sofia C.' (CHSS, row 121) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Nievares, Andrine Sofia C.`

### Osea, Manuel Jose G.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Osea, Manuel Jose G.' (CHSS, row 128) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Osea, Manuel Jose G.`

### Pagar, Angela Millen M.

- **[HIGH]** `COURSE_MISMATCH` — **Course**: DB: "AB PHI Teaching and Research" | SS: "AB Philosophy"
  - **Spreadsheet:** `AB Philosophy`
  - **Database:** `AB PHI Teaching and Research`

### Panganiban, Mia E.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Panganiban, Mia E.' (CHSS, row 129) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Panganiban, Mia E.`

### Peña, Jhonna M.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['Honorable Mention']
  - **Spreadsheet:** `Honorable Mention`

### Peñales, Rina Angela L.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['College Honors, University Honors']
  - **Spreadsheet:** `College Honors, University Honors`

---

## College of Education (COE)

### Nieves, Julien Dominiq

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['College Honors']
  - **Spreadsheet:** `College Honors`

### Orasa, Ronel P.

- **[HIGH]** `ACHIEVEMENT_MISMATCH` — **Achievements**: SS: "Cum Laude, Univeristy Honors, College Honors" | DB: "Cum Laude"
  - **Spreadsheet:** `Cum Laude, Univeristy Honors, College Honors`
  - **Database:** `Cum Laude`
- **[HIGH]** `ACHIEVEMENT_EXTRA_IN_DB` — **Achievements**: "University Honors" is in DB but NOT in SS
  - **Database:** `University Honors`

### Panga, Peter Dominique I.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['- Silver Achievement Award', '- Cum Laude']
  - **Spreadsheet:** `- Silver Achievement Award
- Cum Laude`

### Valencia, Natan A.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['STEP - Member (2020-2025)']
  - **Spreadsheet:** `STEP - Member (2020-2025)`

---

## College of Science, Engineering and Architecture (CSEA)

### Abarca, Kyla M.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1946, 4367. Keep the correct one and delete the rest.
  - **Database:** `1946, 4367`

### Abay, Marcia Lei D.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1931, 4271. Keep the correct one and delete the rest.
  - **Database:** `1931, 4271`
- **[HIGH]** `SPURIOUS_QUOTES` — **Achievements**: Achievement item has spurious quote character: ""Silver Achievement Award"
  - **Database:** `"Silver Achievement Award`
- **[HIGH]** `SPURIOUS_QUOTES` — **Achievements**: Achievement item has spurious quote character: "National Cheerleading Competition 2024 and 2025 Finalist""
  - **Database:** `National Cheerleading Competition 2024 and 2025 Finalist"`
- **[HIGH]** `SPURIOUS_QUOTES` — **Affiliations**: Affiliation item has spurious quote character: ""Ateneo Golden Cavalry - Member (2022-2024), Public Information Officer (2024-20"
  - **Database:** `"Ateneo Golden Cavalry - Member (2022-2024), Public Information Officer (2024-2025)`
- **[HIGH]** `SPURIOUS_QUOTES` — **Affiliations**: Affiliation item has spurious quote character: "AdNU Association of DOST-SEI Scholars - Committee Member (2024-2025)""
  - **Database:** `AdNU Association of DOST-SEI Scholars - Committee Member (2024-2025)"`

### Abendaño, Tristan M.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1950, 4372. Keep the correct one and delete the rest.
  - **Database:** `1950, 4372`

### Abiog, Carl Ivan F.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1954, 4376. Keep the correct one and delete the rest.
  - **Database:** `1954, 4376`

### Agravante, John Cedric

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1958, 4621. Keep the correct one and delete the rest.
  - **Database:** `1958, 4621`

### Alab, Eugene Rendy S.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1962, 4625. Keep the correct one and delete the rest.
  - **Database:** `1962, 4625`

### Alba, Mikail Yshmael P.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1973, 4732. Keep the correct one and delete the rest.
  - **Database:** `1973, 4732`

### Alegre, Anna Bridget A.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1938, 4275. Keep the correct one and delete the rest.
  - **Database:** `1938, 4275`

### Aman, Antonio Nathaniel C.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1971, 4687. Keep the correct one and delete the rest.
  - **Database:** `1971, 4687`

### Ando, Earl Christian M.

- **[HIGH]** `SPURIOUS_QUOTES` — **Affiliations**: Affiliation item has spurious quote character: "PICE AdNU SC - Public Information Officer (2022), President (2023), USec. to the"
  - **Database:** `PICE AdNU SC - Public Information Officer (2022), President (2023), USec. to the IVP (2024)"`

### Angat, Yna Therese Marie S.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1942, 4279. Keep the correct one and delete the rest.
  - **Database:** `1942, 4279`
- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="Silence, a loud forest of mean disembodied voices that plague me; to hear again, I had to shatter my eardrums and listen" | SS="Learning to be comfortable with silence helped me recognize what truly mattered. It's the quiet scenes that humbled me, "
  - **Spreadsheet:** `Learning to be comfortable with silence helped me recognize what truly mattered. It's the quiet scenes that humbled me, pushing me to keep going.`
  - **Database:** `Silence, a loud forest of mean disembodied voices that plague me; to hear again, I had to shatter my eardrums and listen to the faint hums of hope.`

### Bacerdo, Alliza Reyne P.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1977, 4736. Keep the correct one and delete the rest.
  - **Database:** `1977, 4736`

### Bonita, Salvador Jr., H.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1981, 4752. Keep the correct one and delete the rest.
  - **Database:** `1981, 4752`

### Caceres, Harvey Glen C.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1967, 4629. Keep the correct one and delete the rest.
  - **Database:** `1967, 4629`

### Carmen, Carlo C.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['Cum Laude']
  - **Spreadsheet:** `Cum Laude`

### Cavite, Rica Mae R.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Cavite, Rica Mae R.' (CSEA, row 47) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Cavite, Rica Mae R.`

### Lavadia, Gabrielle Victoria E.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Lavadia, Gabrielle Victoria E.' (CSEA, row 20) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Lavadia, Gabrielle Victoria E.`

### Ng Hua, Jan Paul H.

- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "ACI Philippines AdNU SC - Member (2021- 2025)" is in SS but missing from DB
  - **Spreadsheet:** `ACI Philippines AdNU SC - Member (2021- 2025)`
- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "PICE AdNU SC - Member (2021-2025)" is in SS but missing from DB
  - **Spreadsheet:** `PICE AdNU SC - Member (2021-2025)`
- **[HIGH]** `AFFILIATION_EXTRA_IN_DB` — **Affiliations**: "1st Runner Up - AXI Modern Dance Intramurals 2023" is in DB but NOT in SS
  - **Database:** `1st Runner Up - AXI Modern Dance Intramurals 2023`
- **[HIGH]** `AFFILIATION_EXTRA_IN_DB` — **Affiliations**: "Champion - AXI Javelin Throw Men’s Category Intramurals 2024" is in DB but NOT in SS
  - **Database:** `Champion - AXI Javelin Throw Men’s Category Intramurals 2024`

### Parde, Erika Niña T.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 150, 4748. Keep the correct one and delete the rest.
  - **Database:** `150, 4748`

### Sancha, Hannah Erica SB.

- **[HIGH]** `DUPLICATE_RECORD` — **Record**: Name appears 2 times in DB. Post IDs: 1985, 4756. Keep the correct one and delete the rest.
  - **Database:** `1985, 4756`
- **[HIGH]** `COURSE_MISMATCH` — **Course**: DB: "BS Environmental Management" | SS: "BS Mathematics"
  - **Spreadsheet:** `BS Mathematics`
  - **Database:** `BS Environmental Management`

### Villaraza, Nicole Marie R.

- **[HIGH]** `SPURIOUS_QUOTES` — **Affiliations**: Affiliation item has spurious quote character: "PICE AdNU SC - Member (2021-2025), Volunteer (2021-2022), Core Group Vice Direct"
  - **Database:** `PICE AdNU SC - Member (2021-2025), Volunteer (2021-2022), Core Group Vice Director (2022-2023), 3rd Year Level Representative (2023-2024)"`

---

## College of Computer Studies (CCS)

### Agao, Kim Isaiah R.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['TACTICS - Member (2021-2025)']
  - **Spreadsheet:** `TACTICS - Member (2021-2025)`

### Agapito John Lloyd E.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['TACTICS - 2nd Year Representative (2023-2024)']
  - **Spreadsheet:** `TACTICS - 2nd Year Representative (2023-2024)`

### Antonio, Mark Eric L.

- **[HIGH]** `COURSE_MISMATCH` — **Course**: DB: "BS Information Technology" | SS: "BS Information Systems"
  - **Spreadsheet:** `BS Information Systems`
  - **Database:** `BS Information Technology`

### Basbas, Angeline B.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['Cum Laude']
  - **Spreadsheet:** `Cum Laude`

### Belarmino, Jiankarlo A.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['MIS- Application Developer - Volunteer (2023-2025), BITS - Mentor (2023-2024), TACTICS - Member (2021-2025)']
  - **Spreadsheet:** `MIS- Application Developer - Volunteer (2023-2025), BITS - Mentor (2023-2024), TACTICS - Member (2021-2025)`

### Besmano, Glen M.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['Champions - UNECS Swimming Team']
  - **Spreadsheet:** `Champions - UNECS Swimming Team`

### Dizon, Jamaica P.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['Dulaang Agabaab - Member (2022-2025)']
  - **Spreadsheet:** `Dulaang Agabaab - Member (2022-2025)`
- **[HIGH]** `COURSE_MISMATCH` — **Course**: DB: "BS Information Technology" | SS: "BS Information Systems"
  - **Spreadsheet:** `BS Information Systems`
  - **Database:** `BS Information Technology`

### Emaas, Noel B.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['TACTICS - Member (2021 - 2025), GABAY Scholar - Member (2021 - 2025), MIS Application Developer - Volunteer (2023 - 2025)']
  - **Spreadsheet:** `TACTICS - Member (2021 - 2025), GABAY Scholar - Member (2021 - 2025), MIS Application Developer - Volunteer (2023 - 2025)`

### Espiritu, Mark Joseph C.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['TACTICS - PIO', 'PCSKV - Undersecretary (Student Spirituality)', 'BITS']
  - **Spreadsheet:** `TACTICS - PIO
PCSKV - Undersecretary (Student Spirituality)
BITS`

### Flores, Jerome G.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ["DOST Bicol Scholar's Integrated Governing Council of Organizations - Deputy Director for External Affairs (2024-2025), Liderato kan Nueva Atenista - CCS Representative (2023-2024), TACTICS - Business Manager (2022-2023)"]
  - **Spreadsheet:** `DOST Bicol Scholar's Integrated Governing Council of Organizations - Deputy Director for External Affairs (2024-2025), Liderato kan Nueva Atenista - CCS Representative (2023-2024), TACTICS - Business Manager (2022-2023)`

### Gonzales, Mary Diane M.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="Silent isn't really empty just need to trust the process, I lead by listening, letting the quiet speak and be still. Str" | SS="Silent isnt really empty just need to trust the process, I lead by listening, letting the quiet speak and be still. Stre"
  - **Spreadsheet:** `Silent isnt really empty just need to trust the process, I lead by listening, letting the quiet speak and be still. Strength comes in stillness too`
  - **Database:** `Silent isn't really empty just need to trust the process, I lead by listening, letting the quiet speak and be still. Strength comes in stillness too`
- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['TACTICS - Member (2019-2020)']
  - **Spreadsheet:** `TACTICS - Member (2019-2020)`

### Lastimosa, Ian Peter L.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['TACTICS - Treasurer (2022-2023), SSG - Treasurer (2023-2024)']
  - **Spreadsheet:** `TACTICS - Treasurer (2022-2023), SSG - Treasurer (2023-2024)`

### Maesa, Rae Willies G.

- **[HIGH]** `SPURIOUS_QUOTES` — **Achievements**: Achievement item has spurious quote character: ""Artista nin Bulan ""Artist of the month"" (November 2023), 1st Runner Up Charac"
  - **Database:** `"Artista nin Bulan ""Artist of the month"" (November 2023), 1st Runner Up Character Concept Division`

### Mosna, Marco D.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['TACTICS - Business Manager (2022-2023)']
  - **Spreadsheet:** `TACTICS - Business Manager (2022-2023)`

### Natividad, Justin Ira A.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['SSG - CCS Representative & Speaker Pro Tempore (2021-2023)', 'TACTICS - Internal Vice President - CS (2023-2024)', 'Ateneo Chess Enthusiasts - Co-founder/PIO (2024-2025)']
  - **Spreadsheet:** `SSG - CCS Representative & Speaker Pro Tempore (2021-2023)
TACTICS - Internal Vice President - CS (2023-2024)
Ateneo Chess Enthusiasts - Co-founder/PIO (2024-2025)`

### Navarro, Johnmar L.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['PIXELS (2021-2025)']
  - **Spreadsheet:** `PIXELS (2021-2025)`

### Nieves, Jan Nicole G.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['PIXELS - Member (2021-2025)']
  - **Spreadsheet:** `PIXELS - Member (2021-2025)`

### Papina, Angelo Jude P.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: Minor diff (sim=0.64): DB=""""What do you do when you can't do nothing, but there's nothing you can do?""
""You do what you can."" - The Boondocks"" | SS=""What do you do when you can't do nothing, but there's nothing you can do?"
"You do what you can." - The Boondocks"
  - **Spreadsheet:** `"What do you do when you can't do nothing, but there's nothing you can do?"
"You do what you can." - The Boondocks`
  - **Database:** `"""What do you do when you can't do nothing, but there's nothing you can do?""
""You do what you can."" - The Boondocks"`
- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['University Honors, Cum Laude']
  - **Spreadsheet:** `University Honors, Cum Laude`

### Perez, Albert Elezer B.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: Minor diff (sim=0.84): DB=""I come into the peace of wild things who do not tax their lives with forethought of grief."
- Wendell Berry" | SS="I come into the peace of wild things who do not tax their lives with forethought of grief. 
- Wendell Berry"
  - **Spreadsheet:** `I come into the peace of wild things who do not tax their lives with forethought of grief. 
- Wendell Berry`
  - **Database:** `"I come into the peace of wild things who do not tax their lives with forethought of grief."
- Wendell Berry`

### Regidor, Justine Sheene D.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['TACTICS - Internal Vice President for Information Systems (2022-2024)']
  - **Spreadsheet:** `TACTICS - Internal Vice President for Information Systems (2022-2024)`
- **[HIGH]** `COURSE_MISMATCH` — **Course**: DB: "BS Information Technology" | SS: "BS Information Systems"
  - **Spreadsheet:** `BS Information Systems`
  - **Database:** `BS Information Technology`

### Villarey, Josef Ian T.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['DigitAL - Member (2020-2024), PIXELS - Member (2024-2025)']
  - **Spreadsheet:** `DigitAL - Member (2020-2024), PIXELS - Member (2024-2025)`

---

## College of Nursing (CON)

### Bernales, Jaye Anne P.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: DB="Through breaking points, sleepless nights, and unseen battles, I persevered with purpose- leading with care, learning wi" | SS="Through breaking points, sleeplness nights, and unseen battles, I persevered with purpose- leading with care, learning w"
  - **Spreadsheet:** `Through breaking points, sleeplness nights, and unseen battles, I persevered with purpose- leading with care, learning with heart, and serving quietly`
  - **Database:** `Through breaking points, sleepless nights, and unseen battles, I persevered with purpose- leading with care, learning with heart, and serving quietly`

### Consuelo, Neil Christian V.

- **[HIGH]** `QUOTE_MISMATCH` — **Tagline/Quote**: Minor diff (sim=0.78): DB="I wasn't the fastest nor the steadiest, but I was consistent — that's how I persevered" | SS="I wasn't the fastest nor the steadiest, but I was consistent — thats how I perservered"
  - **Spreadsheet:** `I wasn't the fastest nor the steadiest, but I was consistent — thats how I perservered`
  - **Database:** `I wasn't the fastest nor the steadiest, but I was consistent — that's how I persevered`

### Corpuz, Mark Angelo R.

- **[HIGH]** `MISSING_RECORD` — **Record**: Graduate 'Corpuz, Mark Angelo R.' (CON, row 37) is in spreadsheet but has NO post in DB.
  - **Spreadsheet:** `Corpuz, Mark Angelo R.`

### D'souza, Jennifer Mae P.

- **[HIGH]** `TITLE_MISMATCH` — **Post Title**: DB has "D\'souza, Jennifer Mae P." but spreadsheet says "D'souza, Jennifer Mae P."
  - **Spreadsheet:** `D'souza, Jennifer Mae P.`
  - **Database:** `D\'souza, Jennifer Mae P.`

### Ferrer, Riomay I.

- **[HIGH]** `ACHIEVEMENTS_MISSING` — **Achievements**: SS has achievements but DB has none: ['Cum Laude', 'University Honors', '3rd Place Anastacia Giron Tupas Regional Quiz Bee']
  - **Spreadsheet:** `Cum Laude
University Honors
3rd Place Anastacia Giron Tupas Regional Quiz Bee
4th Place Anastacia Giron Tupas National Olympics`

### Guinguing, Justin Glen Y.

- **[HIGH]** `AFFILIATIONS_MISSING` — **Affiliations**: SS has affiliations but DB has none: ['ANSA - President (2023-2024)', 'SSG - Internal Vice President (2022-2023), Public Information Officer (2021-2022)']
  - **Spreadsheet:** `ANSA - President (2023-2024)
SSG - Internal Vice President (2022-2023), Public Information Officer (2021-2022)`

---

## Graduate School (GRAD SCHOOL)

### Galon-Morino, Ivy B.

- **[HIGH]** `COURSE_MISMATCH` — **Course**: DB: "Doctor of Philosophy Major in Educational Psychology" | SS: "Doctor of Philosophy in Educat major in Educational Psychology"
  - **Spreadsheet:** `Doctor of Philosophy in Educat major in Educational Psychology`
  - **Database:** `Doctor of Philosophy Major in Educational Psychology`

### Sabularse, Melgar B.

- **[HIGH]** `AFFILIATION_MISSING_FROM_DB` — **Affiliations**: "Philipine Nurses Association (Active Member to present)" is in SS but missing from DB
  - **Spreadsheet:** `Philipine Nurses Association (Active Member to present)`

---
