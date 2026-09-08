# PaisaPlan

Salary ko char hisson mein baanto, kharcha track karo, aur chhe mahine ka emergency fund
khada karo. Windows aur Android — dono ke liye, ek hi app.

**[Latest version download karo →](https://github.com/Akus0ni/PaisaPlanR/releases/latest)**

Ye repo sirf releases ke liye hai. Har release mein dono files hoti hain: Windows ka `.msi`
aur Android ka `.apk`.

---

## Formula

Har mahine ki salary char hisson mein jaati hai:

| Hissa | Kitna | Kis liye |
| --- | --- | --- |
| **Zaroorat** | 50% | Ghar, khana, bill, travel — jo rukega nahi |
| **Invest** | 25% | SIP, stocks, jo paisa kaam pe lagta hai |
| **Emergency** | 15% | Chhe mahine ka backup, alag rakha hua |
| **Mauj-Masti** | 10% | Bina guilt ke kharch karne wala hissa |

₹70,000 ki salary par ye 35,000 / 17,500 / 10,500 / 7,000 banta hai. Apna plan badalna ho
to Salary screen se badal lo — app default formula par chalta hai, zabardasti nahi karta.

## Kya-kya hai

- **Ghar** — mahine ka poora hisaab ek nazar mein, split bar ke saath.
- **Kharcha** — kya kahan gaya, category ke hisaab se.
- **Salary** — aayi kitni, baant kaise.
- **Emergency** — chhe mahine ka backup kitna ban chuka hai.
- **Invest** — paisa kaam pe laga ya nahi.
- **Insights** — paanch aam galtiyan, jab hone lagein tab batata hai.
- **Seekho** — poora tareeka, shuru se.
- **Settings** — currency, theme, aur backup.

---

## Windows par kaise lagayein

1. Latest release se `PaisaPlan-<version>-win-x64.msi` download karo.
2. File par double-click karo.
3. Windows "protected your PC" dikhaye to **More info → Run anyway** dabao. Installer signed
   nahi hai, isliye Windows pehli baar sawal karta hai.
4. Next, next, install. Admin ki zaroorat nahi — app tumhare apne user ke liye lagta hai
   (`%LocalAppData%\Programs\PaisaPlan`).

Start menu mein PaisaPlan mil jayega.

**Windows 10 (1809 ya uske baad) aur Windows 11 chahiye, 64-bit.**

### Upgrade

Naya `.msi` chala do. Purana version apne aap hat ke naya lag jata hai — pehle uninstall
karne ki zaroorat nahi. Data waise ka waisa rehta hai.

### Uninstall

Settings → Apps → PaisaPlan → Uninstall.

Tumhara data **nahi** mitta — wo install folder ke bahar rehta hai, isliye uninstall usko
haath nahi lagata. Poori tarah safai chahiye to `%LocalAppData%\User Name\com.paisaplan.app`
khud delete kar do.

---

## Android par kaise lagayein

1. Latest release se `PaisaPlan-<version>.apk` phone par download karo.
2. File par tap karo.
3. Android "unknown apps" ki permission maangega — jis app se download kiya (Chrome, Files),
   usko allow kar do.
4. Install.

**Android 7.0 (API 24) ya uske baad chahiye.**

### Upgrade

Naya `.apk` purane ke upar install kar do. Data rehta hai.

**2.4.0 se pehle ke versions se aa rahe ho to ek baar ye karna padega.** Us waqt tak har
release apni alag signing key ke saath ban raha tha, isliye naya APK purane ke upar chadhta
hi nahi tha — **"App not installed"** wahi tha. 2.4.0 se key fix hai, aur uske baad ke
saare upgrade seedhe upar lag jate hain.

Sirf ek baar, isi kram mein:

1. Purana app kholo → **Settings → Backup nikalo**, aur file safe jagah rakho.
2. Purana app **uninstall** karo.
3. Naya `.apk` install karo.
4. **Settings → Import** → wahi file wapas le aao.

Step 1 chhoda to hisaab chala jayega — uninstall data ke saath jata hai.

Iske baad bhi kabhi "App not installed" aaye to yahi chaar step phir se chalte hain, par
aisa hona ab nahi chahiye.

---

## Tumhara data tumhare paas rehta hai

Na koi account, na login, na server. Sab kuch device ke andar hi likha jata hai, aur app
ko internet ki zaroorat hi nahi padti.

Iska matlab ye bhi hai ki **backup tumhari zimmedari hai**.

### Backup aur transfer

Settings screen se ek `.smt` file export hoti hai — usmein poora hisaab hota hai. Chaho to
passphrase laga do; tab file AES-GCM se encrypt hoti hai aur bina passphrase ke khulti hi
nahi.

Doosre device par wahi file import kar lo. Do tarike hain:

- **Merge** — jo naya hai wo add hota hai, jo pehle se hai wo chhoota nahi. Ek hi file do
  baar import kar do to kuch double nahi hota.
- **Sab replace karo** — file ki baat aakhri maani jaati hai. Ye eklauta destructive kaam
  hai app mein, isliye import se pehle app dikhata hai ki file mein hai kya.

Phone se laptop par, ya laptop se naye phone par — dono taraf ek jaisa chalta hai.

---

## Disclaimer

Ye app aur iska content sirf seekhne ke liye hai — ye professional financial advice nahi
hai. Invest karne se pehle apni research karo ya kisi qualified financial advisor se baat
karo.

---

Made by [AkuS0ni](https://akus0ni.github.io/)
