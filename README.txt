========================================================
 MISHRA JI AMBULANCE SERVICE — WEBSITE
 Ise apne DOMAIN par LIVE kaise karein (Netlify ke bina)
========================================================

Is folder me aapki poori website hai:

  index.html    <-- ye hi aapki website hai
  og-image.png  <-- WhatsApp/Facebook par link share karne ki image
  README.txt    <-- ye file


--------------------------------------------------------
 PEHLE EK ZAROORI BAAT (2 minute me samajh lein)
--------------------------------------------------------

Duniya ki HAR website (Google, Facebook, IRCTC) HTML se hi banti hai.
Aapki yeh file bhi ek asli, poori website hai.

"Live" karne ke liye usko ek HOSTING par daalna padta hai — jaise kisi
dukaan ko chalane ke liye ek jagah (shop) chahiye hoti hai. Hosting
bas wohi "jagah" hai. Netlify sirf EK free option tha — uske alawa
bahut options hain. Aap koi bhi chunein, website wahi rahegi.


========================================================
 TARIKA 1  —  APNA DOMAIN + HOSTING   (SABSE "REAL")
 (Recommended: professional look, apna naam, jaise
  mishrajiambulance.in — netlify.app jaisa kuch nahi)
========================================================

Kya chahiye: ek hosting plan + ek domain naam.
India me sasta plan: approx Rs.70-200 / mahina (ya Rs.1,500-2,500 / saal,
jisme domain free mil jata hai aksar).

Popular Indian providers:
   * Hostinger      — hostinger.in     (sabse sasta, aasan)
   * BigRock        — bigrock.in
   * GoDaddy        — godaddy.com/en-in
   * HostGator India— hostgator.in

STEPS (Hostinger ke example se; baaki me bhi same hai):

  1. hostinger.in par "Premium" ya "Single" hosting plan lein.
  2. Domain chunein — jaise:  mishrajiambulance.in  ya
     mishrajiambulance.com  (agar available ho).
  3. hPanel login karein  ->  "Files"  ->  "File Manager"  ->  "public_html"
     folder kholein.
  4. Us folder me jo default "index.html" (ya default.php) hai use
     DELETE kar dein.
  5. Is folder ki apni "index.html" aur "og-image.png" ko
     public_html me UPLOAD kar dein.
  6. Browser me apna domain kholein:  https://mishrajiambulance.in
     BAS! Website LIVE ho gayi.  ✅

  * SSL (https / taala icon) hosting me free milta hai — hPanel me
    "SSL" section se ek click me enable ho jata hai.
  * Domain ko hosting se jodna ho to hPanel ke "DNS" steps follow karein
    (provider khud guide karta hai, ya support se madad lein).


========================================================
 TARIKA 2  —  FREE HOSTING (Netlify ke bina)
========================================================

Agar paisa kharch nahi karna, to yeh free options hain. (Link me
unka naam aayega, jaise abc.pages.dev — lekin baad me apna domain
bhi jod sakte hain.)

  * CLOUDFLARE PAGES   ->  pages.cloudflare.com
        Account banayein -> "Create project" -> "Upload assets"
        -> folder upload karein -> Deploy. Live link mil jayega.

  * VERCEL             ->  vercel.com
        "Add New Project" -> folder/zip upload -> Deploy.

  * GITHUB PAGES       ->  github.com
        Naya repository -> index.html upload -> Settings -> Pages
        -> Branch: main -> Save. Link: username.github.io/repo

  Teeno free hain aur teeno par aap baad me apna domain
  (mishrajiambulance.in) jod sakte hain.


========================================================
 TARIKA 3  —  HOSTING KISI SE KARWANA (aapko kuch nahi karna)
========================================================

Agar aap khud yeh sab nahi karna chahte, to koi bhi local
web-developer / cyber cafe / IT shop se keh dein:
   "Yeh folder mere domain par upload kar do."
Woh 15 minute me kar dega. Is folder ko pen-drive me de dein.
(Yeh folder apne aap me poori website hai — kisi extra kaam ki
zaroorat nahi.)


--------------------------------------------------------
 PHONE / ADDRESS BADALNI HO TO
--------------------------------------------------------

index.html ko Notepad me kholein. Sabse upar "EDIT-ME" comment
block hai — wahan phone, WhatsApp aur address hai. Wahi badal
kar save karein, poori website update ho jayegi.

Phone:    +91 96486 97991
Address:  Gate No. 2, Medical College, Jhansi, Uttar Pradesh


--------------------------------------------------------
 GOOGLE PAR KAISE DIKHEGI (search karne par aaye)
--------------------------------------------------------

Website live hone ke BAAD, Google me dikhne ke liye 2 kaam karein:

A) GOOGLE BUSINESS PROFILE  (sabse zaroori)
   Aapki "Mishra Ji Ambulance Service" ki Google listing already hai
   (wahi link jo aapne bheja tha). Usme jaakar:
     - "Website" field me apna domain daalein (mishrajiambulance.in)
     - Phone, address, timing, photos check karein
     - Customers se "Reviews" maangein
   Isse "ambulance near me Jhansi" jaisi search me aap upar aayenge.

B) GOOGLE SEARCH CONSOLE  (website ko Google me submit karna)
   1. search.google.com/search-console kholein (Google account se login).
   2. "Add property" -> apna domain daalein.
   3. Verify ke liye "HTML tag" method chunein -> jo code mile, use
      index.html ke <head> me "google-site-verification" line me paste
      karein (wahan abhi "PASTE-YOUR-CODE-HERE" likha hai).
   4. Verify karein -> phir "Sitemaps" me sitemap.xml add karein.
   5. 1-2 hafte me Google par dikhne lagegi.

IS FOLDER ME PEHLE SE ADD KIYA HAI:
   - robots.txt   -> Google ko batata hai site scan karne ke liye
   - sitemap.xml  -> Google ko site ke pages batata hai
   - Structured data (LocalBusiness + FAQ) -> Google me address, phone
     aur sawal-jawab dikh sakte hain
   Inme "mishrajiambulance.in" ki jagah apna asli domain likh dein.

SACH BAAT: Google par aane me 1-2 hafte lag sakte hain. "Mishra Ji
Ambulance Service" naam se search karne par jaldi aayegi (naam unique
hai). "ambulance Jhansi" jaise general words me aane me thoda zyada
time aur reviews lagte hain.


--------------------------------------------------------
 AAGE KYA ADD KAR SAKTE HAIN
--------------------------------------------------------
[ ] Apni ambulance aur team ki ASLI photos (sabse zaroori)
[ ] Google Business Profile ka link + reviews
[ ] Alag pages: Services, About Us, Contact (multi-page site)
[ ] Online payment / advance booking
[ ] Google Analytics (kitne log visit kar rahe hain)

Koi bhi help chahiye to bata dein.

========================================================
