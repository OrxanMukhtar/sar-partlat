# Onlayn duel quraşdırması (Firebase, pulsuz)

1. https://console.firebase.google.com → Add project (Analytics söndürülə bilər).
2. Build → Realtime Database → Create database → region seç → **Locked mode** ilə başlat.
3. Rules tabına `database.rules.json` faylının məzmununu yapışdır → Publish.
4. Data tabının yuxarısındakı URL-i kopyala (məs. `https://XXXX-default-rtdb.europe-west1.firebasedatabase.app`).
5. `index.html`-də `var NET_URL = '';` sətrinə həmin URL-i yaz.

URL boş qalarsa onlayn söndürülür, "İki nəfər" yalnız eyni cihazda işləyir.
