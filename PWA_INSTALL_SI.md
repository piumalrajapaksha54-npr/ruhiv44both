# RUHI MOBILE V44 PWA install කිරීම

PWA එක install කිරීමට app files HTTPS සහිත website hosting එකක තිබිය යුතුය (උදා: GitHub Pages හෝ වෙනත් static HTTPS hosting). ZIP එක extract කර `index.html` file එක `file://` ලෙස open කිරීමෙන් PWA install/offline caching සම්පූර්ණයෙන් ක්‍රියා නොකරයි.

## Android Chrome
1. HTTPS website URL එක Chrome වල open කරන්න.
2. Menu (⋮) > Install app හෝ Add to Home screen තෝරන්න.
3. Install කරන්න.

## iPhone Safari
1. HTTPS website URL එක Safari වල open කරන්න.
2. Share > Add to Home Screen තෝරන්න.
3. Add කරන්න.

පළමු වරට app එක online තිබියදී open කර assets cache වීමට ඉඩ දෙන්න. පසුව cached app shell එක offline open කළ හැක. Cloud sync/online server functions internet නැතිවිට ක්‍රියා නොකරයි.
