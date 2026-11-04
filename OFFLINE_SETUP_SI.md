# RUHI MOBILE V44 Offline Edition

මෙය V44 offline/local edition එකයි. Internet හෝ Railway/PostgreSQL නැතිව එකම device/browser එකක දත්ත save කරගෙන භාවිතා කළ හැක.

## Windows / Mac / Linux
1. Node.js 18 හෝ ඉහළ version එක install කරන්න.
2. ZIP එක extract කරන්න.
3. Extract කළ folder එකේ Terminal / Command Prompt එක open කරන්න.
4. `npm install` run කරන්න.
5. `npm start` run කරන්න.
6. Browser එකෙන් `http://localhost:3000` open කරන්න.
7. Login: username `admin`, password `admin`.

## Important
- Offline login එකේදී local Administrator account එක පමණක් ලබා දී ඇත. Online server users/passwords මෙහි sync නොවේ.
- සියලුම business data browser එකේ localStorage තුළ, එම device/browser එකට පමණක් save වේ.
- වෙනත් phone/computer එකක data ස්වයංක්‍රීයව නොපෙනේ. Devices අතර data share/sync කිරීමට online Railway + PostgreSQL edition එක භාවිතා කරන්න.
- Browser data/site data clear කළොත් local records මැකෙන්න පුළුවන්. නිතර Backup & Sync → Export Backup භාවිතා කර JSON backup එකක් ගන්න.
- Offline mode එකේ Cloud Sync ක්‍රියා නොකරයි. Backup Export/Restore භාවිතා කරන්න.
- iPhone එකක installable offline PWA ලෙස භාවිතා කිරීමට මුලින්ම HTTPS website එක online තිබියදී open කර Safari → Share → Add to Home Screen කරන්න. පළමු වරට assets cache වීමට online connection අවශ්‍යයි. පසුව කලින් load/cache වූ app shell එක offline open කළ හැක.

## Security note
මෙය single-device local/offline use සඳහායි; production multi-user security/server-side permissions සඳහා නොවේ. Default password `admin` වෙනස් කළ හැකි server-backed user management එක offline-only edition එකේ නැත. Device එකට passcode/biometric lock භාවිතා කරන්න.
