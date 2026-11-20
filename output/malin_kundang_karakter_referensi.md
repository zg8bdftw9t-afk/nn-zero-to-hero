# Prompt Karakter dari Gambar Referensi (gaya 3D Pixar)

Saya tidak bisa membuat gambar 3D seperti referensi di sini (tidak ada generator gambar AI).
Di bawah ini prompt untuk membuatnya di Midjourney / Flux / Ideogram / Leonardo / Kling Elements.
Unggah gambar referensi Anda sebagai *image reference* (Midjourney: `--sref` untuk gaya, `--cref` untuk wajah).

## Gaya (tempel di awal)
```
3D animated feature-film style, Pixar and Disney quality, stylized appealing proportions, large expressive eyes, soft subsurface scattering skin, detailed cotton and songket cloth texture, warm golden-hour cinematic lighting, misty green tropical karst mountains and a calm lake with wooden stilt houses in the background, shallow depth of field, ultra detailed, 8K
```

## Malin muda (dari gambar: pemuda di perahu)
```
MALIN-MUDA: a Minangkabau teenage boy about 16, slim build, warm tan skin, tousled messy dark-brown hair sticking up, large round dark-brown eyes with a gentle hopeful look, one small dark mole on his left cheek, wearing a loose cream-beige open-collar shirt with rolled sleeves, a red-and-maroon woven sash at the waist, patched dark-brown knee-length trousers, barefoot, a thin braided red-and-black cord bracelet on his right wrist, sitting on the edge of a wooden boat holding a small carving tool
```

## Gadis/istri bangsawan (dari gambar: perempuan berdiri)
```
ISTRI-MALIN: a young Minangkabau noblewoman about 22, elegant slender build, fair light-brown skin, long straight glossy black hair worn down, large almond-shaped dark eyes with a gentle smile, a small beauty mark above the right corner of her lips, wearing a small gold tiara-style suntiang crown, a teal-turquoise fitted top with a gold embroidered band, a layered gold necklace, a gold-and-maroon songket sash at the waist, a long dusty-rose and maroon songket sarung with gold motifs, barefoot with simple sandals, standing with her hands behind her back
```

## Prompt adegan (keyframe, `--ar 9:16`)
```
[Gaya]. Medium shot, MALIN-MUDA sitting on the edge of a wooden boat in the foreground, ISTRI-MALIN standing behind him on the shore smiling shyly, stilt houses and green mountains in the misty golden background --ar 9:16
```

## Character sheet (buat dulu, pakai sebagai referensi)
```
[Gaya]. Character turnaround sheet of [blok tokoh], front view, side view and back view, neutral pose, plain light-gray background, consistent proportions, full body --ar 16:9
```

Negative prompt: `realistic photo, flat 2D, different face, changed outfit, extra fingers, deformed hands, text, watermark, logo, modern objects, blurry, low quality`
