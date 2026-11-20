TOPPER TRACKER - CGBSE (Offline Version)
=========================================

Files
-----
index.html            -> pura app (sab kuch is ek file me hai)
sw.js                 -> offline engine (service worker)
manifest.webmanifest  -> "Install app" ke liye
icons/                -> app icons

Offline kaise chalayein
-----------------------
OPTION 1 (sabse aasaan, bina internet)
  Zip extract karke index.html ko Chrome me kholein. Ye offline chalta hai.
  (Is mode me "Install app" nahi milta.)

OPTION 2 (phone par proper app ki tarah - recommended)
  Folder ko ek baar free hosting par daal dein (GitHub Pages / Netlify Drop / Cloudflare Pages).
  Phir phone ke Chrome me link kholein -> menu -> "Add to Home screen" / "Install app".
  Ek baar khulne ke baad internet ki zarurat nahi.
  iPhone: Safari -> Share -> "Add to Home Screen".

Halka timetable (v8)
--------------------
- Aaj ka plan Subah / Shaam me bata hai.
- Sona, khana, school, khel, break "routine" me halke dikhte hain; progress, streak aur ring me count nahi hote.
  "Routine chhupao" button se inhe poora hata sakte hain.
- Subah ke Skill A, B, C ek "Daily Skills" card me hain (Sunday par "Skill Tests").
- Calculation / Formula / Periodic Table tests ab Saturday subah (Skill A, B ki jagah) hote hain.
  Sunday ab 10 ki jagah 7 lines ka hai.
- Agar aapne Settings me timetable khud badla tha, to Sunday ka naya plan lene ke liye
  Settings -> "Reset CGBSE Default" dabayein. (Naye default se pehle backup le lein.)

Time (v9)
---------
- Har task ab START–END time aur kitne minute ka hai, ye dikhata hai (jaise 6:00–6:15 AM, 15 min).
- Settings me line ka format: 06:00-06:15 | Kaam | Subject (END optional). Save par time takrane ki warning aati hai.
- "Abhi ka Focus" ab sirf tab dikhta hai jab task ka time chal raha ho; school ke samay agla task dikhta hai.
- Purane saved timetable (jo aapne khud nahi badle) apne aap naye time-wale plan me badal jaate hain.

Look (v10)
----------
Sunrise theme (hero card pehle jaisa gold hi hai): raat ka neela aasmaan -> subah ka coral. Bada hero card, har task alag tile, tick karne par hara.
Purane colour themes (Sapphire/Violet/Rose/Emerald) Settings me ab bhi hain.

Backup & Restore (More -> Settings -> Data Backup & Restore)
------------------------------------------------------------
- Backup file : poora data .json file me download hota hai.
- Share       : (jahan phone support kare) seedha Drive / WhatsApp par bhejein.
- Restore file: pehle wali backup .json chunein. Purani v6 backups bhi chalti hain.
                Restore se pehle abhi ke data ki safety copy banti hai -> "Undo" button.
- Auto snapshots: roz ka ek snapshot phone me khud banta hai (last 7 din).
- Agar browser ne localStorage clear kar diya par snapshot bacha ho, to data khud wapas aa jata hai.
- Har hafte ek backup file Drive / WhatsApp par zarur rakhein.

Note: Data usi browser/app me save hota hai jisme aap use karte hain.
Browser data clear karne se pehle backup le lein.
