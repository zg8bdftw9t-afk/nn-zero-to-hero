# Legenda Malin Kundang — Prompt Animasi 4D (9:16, 576×1024)

"4D" di sini = animasi 3D bergaya film + lapisan efek sensorik ala bioskop 4D
(kedalaman stereoskopik, parallax, partikel hujan/angin/percikan, kilat, getaran kamera).
Semua prompt di bawah memakai rasio **9:16 vertikal** (ekspor akhir 576×1024).

## Cara pakai
1. Buat *character sheet* tiap tokoh dari blok Character Bible (salin persis, jangan diparafrasekan).
2. Pakai sheet sebagai referensi wajah (Midjourney `--cref`/`--oref`, Flux/Ideogram reference image, atau Kling Elements).
3. Per adegan: buat keyframe (Text-to-Image) → klip (Image-to-Video, mulai 5 dtk lalu *extend*).
4. Tempel **Lapisan 4D** ke motion prompt. Jika generator tidak mendukung semua efek, tambahkan hujan/petir/getaran di editor video.
5. Susun klip, tambah dubbing, suara, musik. Transisi adegan 2→3: *fade through black*.

## Blok global (tempel di awal semua prompt gambar)

**Style anchor 4D**
```
3D animated feature-film style, Pixar and Disney quality, stylized appealing proportions with slightly large expressive eyes, soft subsurface scattering skin, detailed songket and cotton cloth texture, cinematic volumetric lighting, stereoscopic 3D depth with strong foreground-midground-background separation, shallow depth of field, rich warm color grading, ultra detailed, 8K, vertical 9:16 composition
```

**Negative prompt (semua adegan)**
```
realistic photo, flat 2D, different face, changed outfit, extra fingers, deformed hands, extra limbs, text, watermark, logo, modern objects, blurry, low quality
```

**Lapisan 4D umum (tempel di akhir motion prompt)**
```
4D cinema feel: true parallax between foreground, subject and background layers, floating particles passing close to the lens (sea spray, dust, petals, rain), depth-of-field rack focus, wind-driven cloth and hair, subtle handheld camera shake on dramatic beats. Keep faces, outfits and proportions identical to the keyframe. Smooth natural character motion, no morphing, no sudden camera cuts.
```

## Character Bible (salin persis)

```
MALIN-KECIL: a 9-year-old Minangkabau boy, slim small build, warm tan-brown skin, round face, large round dark-brown eyes with long lashes, small button nose, one small dark mole on his left cheek, messy short black hair with a cowlick sticking up at the crown, wearing a faded cream-beige loose collarless shirt with a frayed hem, patched dark-brown knee-length trousers held by a rope belt, barefoot, a thin braided red-and-black cord bracelet on his right wrist
```
```
MALIN-DEWASA: a 28-year-old Minangkabau merchant, tall lean athletic build, warm tan-brown skin, the same large round dark-brown eyes now confident and sharp, one small dark mole on his left cheek, a thin neat mustache, wearing a crimson-and-gold songket deta headcloth, a black baju taluak balango jacket with gold embroidered collar and cuffs, black wide-legged sarawa galembong trousers, a gold-and-maroon songket sisampiang sash at the waist, a gold ring with a red ruby on his right index finger, leather sandals
```
```
MANDE-RUBAYAH: a 70-year-old Minangkabau mother, frail and slightly hunched, deeply wrinkled warm brown skin, large round dark-brown eyes with soft crow's feet (the same eye shape as Malin), a few silver-white wisps of hair, wearing a faded maroon tingkuluak headcloth, a faded indigo baju kuruang basiba long tunic with visible hand-sewn patches, a brown checkered sarung, an ochre thin selendang over her shoulder, holding a bent wooden walking stick, a gentle tired expression
```
```
MANDE-RUBAYAH-MUDA: the same woman at about 38 years old: upright posture, fewer wrinkles, jet-black hair visible under the same faded maroon tingkuluak headcloth, the same indigo baju kuruang basiba tunic with hand-sewn patches, the same brown checkered sarung, the same ochre selendang, no walking stick, the same large round dark-brown eyes as her son, a warm loving smile
```
```
ISTRI-MALIN: a 24-year-old Minangkabau noblewoman, elegant slender build, fair light-brown skin, oval face, almond-shaped dark eyes, delicate nose, a small beauty mark above the right corner of her lips, wearing a red-and-gold songket tingkuluak tanduak horn-shaped headcloth with a small gold suntiang ornament, an emerald-green velvet baju kuruang with a gold embroidered hem, a deep maroon songket sarung with gold motifs, a layered gold necklace, dangling gold earrings with red gems
```

**Setting anchor (Pantai Air Manis, Padang)**
```
Air Manis beach in Padang, West Sumatra: dark gray rocks, a small rocky islet offshore, coconut palms, wooden fishing boats, a stilt fishing hut with a thatched ijuk roof, and a distant Minangkabau rumah gadang with horn-shaped gonjong roofs
```

---

## Adegan 1 — Pantai Air Manis, masa kecil (8 dtk)
Narasi: Narator "Di Pantai Air Manis, Padang, hiduplah Malin kecil dan ibunya." — Malin kecil "Ibu, kalau Malin sudah besar, kita tidak akan miskin lagi!"

**Keyframe**
```
[Style anchor 4D]. Golden-hour sunrise at the [Setting anchor]. Foreground: palm fronds and wet rocks framing the shot. Midground left, MALIN-KECIL sitting on a rock gazing at a big wooden trading ship on the horizon, hopeful sparkling eyes. Midground right at the hut doorway, MANDE-RUBAYAH-MUDA mending a fishing net with a warm loving smile. Warm golden rim light, soft sea mist, volumetric god rays, gentle waves, seagulls --ar 9:16
```
**Motion**
```
Slow dolly-in with parallax from the palm fronds in the foreground. The boy turns his head toward his mother, breaks into a hopeful smile and points at the horizon. The mother looks up from the net, smiles softly and shakes her head with affection. Waves roll onto the sand, palm fronds sway, seagulls glide. [Lapisan 4D umum]
```
**Efek 4D:** percikan air halus melewati lensa, angin laut menggoyang kain dan rambut.
**Suara:** ombak pelan, camar, saluang lembut + petikan rabab tipis.

## Adegan 2 — Pamit merantau (10 dtk)
Narasi: Narator "Dengan berat hati, sang ibu melepas anak tunggalnya merantau." — Mande "Pergilah, Nak. Jaga dirimu baik-baik, dan jangan lupakan Ibu." — Malin kecil "Malin janji, Ibu. Malin akan pulang membawa kebanggaan."

**Keyframe**
```
[Style anchor 4D]. Emotional medium two-shot on a weathered wooden pier at [Setting anchor], early morning, a large merchant sailing ship with cream sails moored behind them, rope and wooden bollard in the foreground. MANDE-RUBAYAH-MUDA kneeling on one knee with tearful loving eyes, handing a rice bundle wrapped in a banana leaf to her son. MALIN-KECIL holding a small cloth bundle over his shoulder, brave but teary-eyed. Soft golden backlight, gentle sea mist --ar 9:16
```
**Motion**
```
Slow push-in. The mother straightens the boy's collar, places the rice bundle in his hands, strokes his hair; a tear rolls down. The boy nods bravely, wipes his nose, turns and walks toward the gangplank, glancing back once. The mother's raised hand trembles. Camera tracks the boy, then pulls back with parallax to reveal the mother alone on the pier. [Lapisan 4D umum]
```
**Efek 4D:** angin menarik layar dan kain; partikel debu keemasan melayang di depan lensa.
**Suara:** derit kayu dermaga, saluang melankolis; musik mengecil saat Malin menoleh.

## Adegan 3 — Berlayar dan menjadi saudagar (8 dtk)
Narasi: Narator "Bertahun-tahun berlalu. Dengan kerja keras, Malin menjadi saudagar kaya dan menikahi putri bangsawan."

**Keyframe**
```
[Style anchor 4D]. Majestic wide shot at sunset on the open sea, the deck of a huge ornate wooden merchant ship with carved red-and-gold bow, full cream sails, crates of spices, sacks of cloves and chests of gold coins in the foreground. MALIN-DEWASA standing proudly at the bow looking at the horizon. Beside him ISTRI-MALIN resting her hand lightly on his arm. Orange-pink sunset sky, golden rim light, sparkling sea --ar 9:16
```
**Motion**
```
Crane shot rising slowly from deck level up and back to reveal the whole ship on a glittering sea. The man lifts his chin and looks at the horizon with a determined smile; his sash and headcloth tail flutter. The woman turns to him with a gentle smile and leans her head against his shoulder. Sails billow, ropes sway, sea spray sparkles. [Lapisan 4D umum]
```
**Efek 4D:** percikan laut dan kilau koin emas melewati lensa.
**Suara:** ombak besar tenang, tali dan kayu berderit; talempong dan gandang megah.

## Adegan 4 — Kapal megah berlabuh (8 dtk)
Narasi: Narator "Suatu hari, kapal megah itu berlabuh di kampung halaman Malin." — Istri "Suamiku, inikah kampung halamanmu?" — Malin "Iya... sudah lama sekali aku tinggalkan."

**Keyframe**
```
[Style anchor 4D]. Bright midday shot of the huge ornate merchant ship arriving at [Setting anchor], small crowds of curious villagers gathering on the shore. Foreground on the ship's carved railing: MALIN-DEWASA gazing at the shore with a tense, unreadable expression, and beside him ISTRI-MALIN looking at him curiously. Crisp sunlight, sparkling turquoise water, light cloud shadows --ar 9:16
```
**Motion**
```
Slow tracking shot along the railing, settling into a medium two-shot. The man grips the railing, his jaw tightens; he does not smile. The woman tilts her head and asks a question, then follows his gaze. In the background the ship glides toward the beach, villagers wave and point, fishing boats rock on the wake. [Lapisan 4D umum]
```
**Efek 4D:** percikan lambung kapal menabrak ombak; hening sesaat sebelum dialog Malin.
**Suara:** kerumunan jauh, camar; gandang tunggal berdetak pelan, saluang bernada rendah.

## Adegan 5 — Mande menyambut (10 dtk)
Narasi: Narator "Kabar itu sampai ke telinga Mande Rubayah. Ia berlari menyongsong anaknya." — Mande "Malin! Anakku! Ibu rindu sekali padamu, Nak!"

**Keyframe**
```
[Style anchor 4D]. Emotional wide-to-medium shot on a wooden pier at [Setting anchor], bright afternoon, the ornate merchant ship moored behind, villagers watching from a distance. Foreground: MANDE-RUBAYAH hurrying forward with both arms stretched out and tears of joy. At the foot of the gangplank: MALIN-DEWASA frozen in surprise and discomfort. Behind him ISTRI-MALIN watching with a puzzled look. Warm backlight on the mother, soft contrast between her faded clothes and their rich silks --ar 9:16
```
**Motion**
```
Low tracking shot in front of the old woman as she hurries along the pier leaning on her stick, steps unsteady but eager; her arms reach out, lips tremble. Cut-in: slow push-in on the man's face, his smile never comes, shoulders stiffen. The wife looks from the old woman to her husband, confused. Wind lifts the old woman's selendang and sparse white hair. [Lapisan 4D umum]
```
**Efek 4D:** angin menerbangkan selendang; papan dermaga bergetar tiap langkah (getaran kamera ringan).
**Suara:** langkah di papan, tongkat berketuk, bisik warga; saluang hangat turun menjadi satu nada bergetar.

## Adegan 6 — Penolakan di dermaga (10 dtk)
Narasi: Istri "Suamiku, siapa perempuan tua ini?" — Malin "Bukan siapa-siapa! Hanya pengemis. Aku tidak mengenalnya! Usir dia!" — Mande "Malin... ini Ibu, Nak." — Narator "Karena malu, Malin menyangkal ibunya sendiri."

**Keyframe**
```
[Style anchor 4D]. Dramatic medium shot on the wooden pier at [Setting anchor], sky turning overcast and gray-gold, villagers silent in soft-focus background. MALIN-DEWASA with cold and ashamed eyes, turning his face away and raising one hand to push the old woman back. MANDE-RUBAYAH stumbling to her knees with a heartbroken tearful face, her walking stick dropped on the planks. In the background ISTRI-MALIN covering her mouth in shock. Cold side light on Malin, warm tender light on Mande, strong emotional contrast --ar 9:16
```
**Motion**
```
Slow dolly-in between the two characters. The man's face hardens, he looks away, then pushes the old woman's shoulder back with one outstretched hand and says his line sharply. The old woman stumbles, drops her stick, sinks to her knees, hands trembling toward him as tears fall. Cut to a close-up of her eyes as she whispers her line. The wife steps back with a hand over her mouth. Clouds thicken, wind picks up. [Lapisan 4D umum]
```
**Efek 4D:** hentakan kamera singkat saat tongkat jatuh; angin dingin mengibaskan kain.
**Suara:** hening tegang, tongkat jatuh ke papan, isak tertahan; saluang rendah bergetar, satu dentuman gandang saat Malin mendorong.

## Adegan 7 — Doa kutukan dan badai (10 dtk)
Narasi: Narator "Dengan hati hancur, Mande menengadahkan tangan ke langit." — Mande (bergetar, lirih) "Ya Allah... jika dia benar anakku, kutuklah dia menjadi batu!"

**Keyframe**
```
[Style anchor 4D]. Powerful low-angle shot on the rocky shore of Air Manis beach in Padang, West Sumatra, at dusk. Foreground: MANDE-RUBAYAH kneeling on wet sand with both hands raised to the sky and tears running down her face, eyes full of grief and anguish. Far behind her, the ornate merchant ship with cream sails leaving the shore under a huge dark swirling storm cloud, jagged lightning in the distance, violet and steel-blue sky with a narrow orange glow on the horizon, rough waves crashing against dark rocks, spray in the air. Dramatic rim light on her face, volumetric rain beginning to fall --ar 9:16
```
**Motion**
```
Slow crane-up and push-in toward the kneeling old woman. She lifts her trembling hands higher, lips moving as she prays, tears mix with the first raindrops. Wind whips her selendang and white hair. In the background storm clouds churn, lightning silhouettes her, waves slam the rocks, the distant ship starts to rock violently. End with a close-up of her tearful eyes lit by a lightning flash. [Lapisan 4D umum]
```
**Efek 4D:** hujan makin deras menembus lensa, kilat putih ke seluruh layar, getaran kamera saat petir.
**Suara:** angin kencang, gerimis lalu hujan lebat, petir menggelegar tepat setelah kata "batu".

## Adegan 8 — Malin menjadi batu (8 dtk)
Narasi: Malin "Ibu... ampun, Ibu!" — Narator "Badai menghancurkan kapal itu, dan Malin membatu selamanya. Hormatilah ibumu."

**Keyframe**
```
[Style anchor 4D]. Epic wide shot on the stormy rocky shore of Air Manis beach, the splintered wreck of an ornate merchant ship with torn cream sails lying broken among huge crashing waves, lightning splitting a dark violet sky, rain and sea spray. Foreground: MALIN-DEWASA with the same large round dark-brown eyes wide with terror, kneeling on wet rocks with one hand stretched out pleading, his legs, waist and one arm already turned to gray cracked stone creeping up toward his chest, the stone texture rough and mossy. Cold blue lightning rim light, small pale glow at the edge of the stone, dramatic tragic mood --ar 9:16
```
**Motion**
```
Start on the kneeling man screaming silently, then a slow orbiting camera move around him as gray stone spreads quickly and smoothly up from his legs over torso, arm, neck and finally his face, which freezes in a frame of regret. His outstretched hand turns to stone last. A lightning flash lights the finished statue, then the camera pulls back and rises to reveal the wrecked ship slowly turning into black rocks as the waves calm. Rain softens to drizzle and the clouds begin to part. Keep face, outfit and proportions identical until the transformation covers them. [Lapisan 4D umum]
```
**Efek 4D:** petir terakhir sangat keras lalu hening tiba-tiba; retakan batu dan gemuruh rendah; hujan mereda.
**Suara:** saluang tunggal panjang dan pilu, ditutup satu denting talempong. Tambahkan kartu judul "Hormatilah ibumu" di editor.
