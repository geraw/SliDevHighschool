---
theme: apple-basic
infoLine: true # on by default, can be turned off
author: "גרא וייס" # shows in infoLine
htmlAttrs:
  dir: rtl
  lang: heb
mdc: true
download: true

layout: intro-image

image: https://hips.hearstapps.com/pop.h-cdn.co/assets/16/17/980x556/gallery-1461684156-rotem-l-1021.jpg?resize=1200:*&output-quality=80
---

<div class="absolute left-10 " style="text-align: center;">
  <span class="font-700">
    גרא וייס<br>
    המחלקה למדעי המחשב <br>
    אוניברסיטת בן גוריון
  </span>
</div>

<div class="absolute bottom-10" style="text-align: center;">
  <h1 style="color:rgb(238, 234, 209);">איך פועל רובוט מעופף?</h1>
  <h2>פתרון משוואות בשמיים</h2>
</div>

---

# האם זה רובוט?

<div style="position: absolute; left: 50%; transform: translateX(-50%); top: 100px;">
  <iframe
    width="660"  
    height="440"  
    src="https://www.youtube.com/embed/3G1KBu6H6BM?si=QaHIR9SXLH5DZuCO"
    frameborder="0"  
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"  
    allowfullscreen>
  </iframe>
</div>

<div v-click="1" style="position: absolute; left: 50%; transform: translateX(-50%); top: 100px;">
  <iframe
    width="660"  
    height="440"  
    src="https://www.youtube.com/embed/adPqagG1dc0"
    frameborder="0"  
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"  
    allowfullscreen>
  </iframe>
</div>

<div v-click="2" style="position: absolute; left: 50%; transform: translateX(-50%); top: 100px;">
  <iframe
    width="660"  
    height="440"  
    src="https://www.youtube.com/embed/3CR5y8qZf0Y?start=7"
    frameborder="0"  
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"  
    allowfullscreen>
  </iframe>
</div>


---

# סיכום ביניים

## לא כל מה שנראה כמו רובוט הוא באמת כזה

<div style="position: absolute; left: 20px; top: 120px; text-align: center;">
  <img src="https://i5.walmartimages.com/asr/250f8986-ddce-49d1-8225-97780786e876.3508638f711964a10d66e872cbed5f44.jpeg?odnHeight=768&odnWidth=768&odnBg=FFFFFF" width="300">
  <h2>מכונה המבצעת פעולה אחת</h2>
  <h2 style="color: red;">אינה רובוט</h2>
</div>

<div style="position: absolute; left: 390px; top: 180px; text-align: center;'">
  <img src="https://media.hswstatic.com/eyJidWNrZXQiOiJjb250ZW50Lmhzd3N0YXRpYy5jb20iLCJrZXkiOiJnaWZcL3JhZGlvLWNvbnRyb2xsZWQtdG95LmpwZyIsImVkaXRzIjp7InJlc2l6ZSI6eyJ3aWR0aCI6ODI4fSwidG9Gb3JtYXQiOiJhdmlmIn19"  width="300" >
  <h2>מכונה המופעלת בשלט רחוק</h2>
  <h2 style="color: red;">אינה רובוט</h2>
</div>

<div style="position: absolute; left: 760px; top: 180px; text-align: center;'">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Valkyrie-robot-3.jpg/800px-Valkyrie-robot-3.jpg" width="200" >
  <h2>מכונה בצורת אדם</h2>
  <h2 style="color: red;">אינה בהכרח רובוט</h2>
</div>

---

# למה צריך רובוטים מעופפים?

<div style="position: absolute; left: 100px; top: 120px; text-align: center;">
  <img src="https://images1.ynet.co.il/PicServer4/2016/05/10/6995350/01.jpg" alt="צילום אווירי" width="250">
  <h2>חקלאות</h2>
</div>

<div style="position: absolute; left: 100px; top: 350px; text-align: center;">
  <img src="https://www.israelhayom.co.il/wp-content/uploads/2023/12/19/19/MEK22.jpg" width="250">
  <h2>צבא</h2>
</div>

<div style="position: absolute; left: 670px; top: 350px; text-align: center;">
  <img src="https://res.cloudinary.com/tbmg/c_scale,w_400,f_auto,q_auto/v1702586265/sites/tb/articles/2023/briefs/TB-0323-p28_fig1.jpg" width="250">
  <h2>חקר הסביבה</h2>
</div>

<div style="position: absolute; left: 670px; top: 120px; text-align: center;">
  <img src="https://cdn.5280.com/2018/05/search-rescue-drone_Jason-Hatfield-960x640.jpg" width="250">
  <h2>חיפוש והצלה</h2>
</div>

<div style="position: absolute; left: 390px; top: 200px; text-align: center;">
  <v-click>
    <img src="/flying-robots.webp" width="250">
    <h2>רעיונות נוספים?</h2>
  </v-click>
</div>

---

# מה עושים כשהטיסן נוטה יותר מדי ימינה?

<div style="position: absolute; left: 50%; transform: translateX(-50%); top: 120px;">
  <img src="/lean-right-drone.jpg" width="600">
</div>

<div v-click>
<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 637px; top: 240px; font-size: 38px;"
>
  👆
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 540px; top: 235px; font-size: 38px;"
>
  👆
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 463px; top: 160px; font-size: 38px;"
>
👇
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 328px; top: 123px; font-size: 38px;"
>
👇
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 80px; top: 450px; font-size: 25px;"
>

מגבירים את שני המדחפים הימניים ומחלישים את שני המדחפים השמאליים

</div>

</div>

---

# מה עושים כשהטיסן נוטה יותר מדי קדימה?

<div style="position: absolute; left: 50%; transform: translateX(-50%); top: 130px;">
  <img src="/lean-forward-drone.jpg" width="600">
</div>

<div v-click>
<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 622px; top: 115px; font-size: 38px;"
>
  👇
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 485px; top: 230px; font-size: 38px;"
>
  👆
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 418px; top: 138px; font-size: 38px;"
>
👇
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 263px; top: 220px; font-size: 38px;"
>
👆
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 80px; top: 450px; font-size: 25px;"
>

מגבירים את שני המדחפים הקדמיים ומחלישים את שני המדחפים האחוריים

</div>

</div>

---

# מה יקרה אם כל המדחפים יפעלו באותו הכיוון?

<div v-click>
<div style="position: absolute; left: 50%; top: 50%; transform: translate(-50%, -50%);">
<div class="sketchfab-embed-wrapper"> <iframe title="flying-drone" 
width="640" height="200"  
frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/671aa2d9139040d5995896f33a9d7a3a/embed?autospin=1&autostart=1&preload=1&transparent=1&ui_hint=0"> </iframe> </div>
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 380px; top: 450px; font-size: 25px;"
>

הרחפן יכנס לסבסוב 

</div>

</div>

---

# למה להליקופטר רגיל יש מדחף בזנב?

<div style="position: absolute; left: 50%; top: 60%; transform: translate(-50%, -50%);">
<div class="sketchfab-embed-wrapper"> <iframe title="Trotter Fly chopper copter" frameborder="0" 
width="800" height="400"  
allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/e79a07b4d48e49009d8ade1df7abc109/embed?autostart=1&preload=1&transparent=1"> </iframe> 
</div>

</div>


---

# פתרון: שני מדחפים יפעלו עם כיוון השעון ושניים נגד

<div style="position: absolute; left: 50%; transform: translateX(-50%); top: 130px;">
  <img src="/rotation-dirs.svg" width="400">
</div>

---

# איך נסובב את הרחפן סביב צירו?

<div style="position: absolute; left: 50%; transform: translateX(-50%); top: 50px;">
  <img src="/rotation-target.svg" width="700">
</div>

---

#  איך נסובב את הרחפן סביב צירו?

<div style="position: absolute; left: 50%; transform: translateX(-50%); top: 130px;">
  <img src="/rotation-dirs.svg" width="400">
</div>


<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 520px; top: 160px; font-size: 38px;"
>
  👇
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 660px; top: 390px; font-size: 38px;"
>
  👆
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 295px; top: 400px; font-size: 38px;"
>
👇
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 395px; top: 180px; font-size: 38px;"
>
👆
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 100px; top: 480px; font-size: 25px;"
>

נגביר את שני המדחפים המסתובבים בכיוון השעון ונחליש את שני האחרים

</div>

---

# מה אם הרחפן סוטה בכל הכיוונים בבת אחת? 😱

<div style="position: absolute; left: 50%; transform: translateX(-50%); top: 130px;">
  <img src="/fix-all-dirs.svg" width="800">
</div>

<div v-motion v-click
  :initial="{ y: 550, opacity: 0 }"
  :enter="{ y: 350, opacity: 1 }"
  style="font-size: 25px; text-align: center;"
>
  ננצל את דרגות החופש שלנו כדי לשלוט בכל כיוון בנפרד
</div>

--- 

# הגיע זמן לקצת מתמטיקה 🧮➗

<div style="position: absolute; left: 50%; transform: translateX(-50%); top: 110px;">
  <img src="/variables.svg" width="400">
</div>


<div v-motion v-click
  :initial="{ y: 550, opacity: 0 }"
  :enter="{ y: 390, opacity: 1 }"
  style="font-size: 25px; text-align: center;"
>

  נסמן את מהירויות המנועים ב- 
  $v_1, v_2, v_3$ 
  ו-
  $v_4$.

</div>

---

# משוואות תנועה

<div style="position: absolute; left: 20%; transform: translate(-50%, -50%); top: 50%;">
  <img src="/variables.svg" width="250">
</div>


<div style="position: absolute; left: 70%; top: 50%; transform: translate(-50%, -50%) scale(1.7);">

  $$ \begin{aligned}
    v_1 + v_2 - (v_3 + v_4) &= \text{נטיה קדימה} \\
    v_2 + v_3 - (v_1 + v_4) &= \text{נטיה ימינה} \\
    v_1 + v_3 - (v_2 + v_4) &= \text{סבסוב} \\
    v_1 + v_2 + \phantom{(}v_3 + v_4\phantom{)} &= \text{עליה למעלה}
  \end{aligned} $$
</div>

---
 
# דוגמה מספרית

<div style="position: absolute; left: 70%; top: 50%; transform: translate(-50%, -50%) scale(1.7);">

  $$ \begin{aligned}
    v_1 + v_2 - (v_3 + v_4) &= -1 \\
    v_2 + v_3 - (v_1 + v_4) &= 2  \\
    v_1 + v_3 - (v_2 + v_4) &= 1 \\
    v_1 + v_2 + \phantom{(}v_3 + v_4\phantom{)} &= -3
  \end{aligned} $$
</div>

<div style="position: absolute; left: 20%; top: 50%; transform: translate(-50%, -50%);">
  <img src="/fix-all-dirs.svg" width="300">
</div>

<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
  style="position: absolute; left: 175px; top: 315px; font-size: 20px;color:  #0077cc; "
>

$-3$
</div>


<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
 style="position: absolute; left: 220px; top: 290px; font-size: 20px;color:  #0077cc; "
>

$-1$
</div>


<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
 style="position: absolute; left: 300px; top: 220px; font-size: 20px;color:  #0077cc; "
>

$2$
</div>


<div v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1 }"
 style="position: absolute; left: 210px; top: 160px; font-size: 20px;color:  #0077cc; "
>

$1$
</div>

---

# נסדר את המשתנים לפי הסדר

<div style="position: absolute; left: 25%; top: 50%; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">

  $$\begin{aligned}v_1 + v_2 - (v_3 + v_4) &= -1 \\
  v_2 + v_3 - (v_1 + v_4) &= 2  \\
  v_1 + v_3 - (v_2 + v_4) &= 1 \\
  v_1 + v_2 + \phantom{(}v_3 + v_4\phantom{)} &= -3\end{aligned}$$
</div>

<div v-motion
  :initial="{ x: -20, opacity: 0 }"
  :enter="{ x: 0, opacity: 1 }"
  style="position: absolute; left: 47.5%; top: 47.5%; transform: translate(-50%, -50%); font-size: 60px;">

  ➭
</div>


<div v-motion
  :initial="{ x: 600, opacity: 0 }"
  :enter="{ x: -600, opacity: 1 }" >

  <div style="position: absolute; right: -400px; top: 190px; transform: translate(50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">

  $$\begin{aligned}
        v_1 + v_2 - v_3 - v_4 &= -1 \\
        -v_1 + v_2 + v_3 - v_4 &= 2  \\
        v_1 - v_2 + v_3 - v_4 &= 1 \\
        v_1 + v_2 + v_3 + v_4 &= -3
    \end{aligned}$$
  </div>
</div>


---

# נחסר ונחבר שורות

<div style="position: absolute; left: 20%; top: 160px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">

  $$\begin{aligned}
        v_1 + v_2 - v_3 - v_4 &= -1 \\
        -v_1 + v_2 + v_3 - v_4 &= 2  \\
        v_1 - v_2 + v_3 - v_4 &= 1 \\
        v_1 + v_2 + v_3 + v_4 &= -3
  \end{aligned}$$
</div>

<div v-motion
  :initial="{ x: -20, opacity: 0 }"
  :enter="{ x: 0, opacity: 1 }"
  style="position: absolute; left: 350px; top: 320px; transform: translate(-50%, -50%); font-size: 100px;">

  ↳
</div>


<div v-motion
  :initial="{ x: 600, opacity: 0 }"
  :enter="{ x: -600, opacity: 1 }" >

  <div style="position: absolute; right: -730px; top: 290px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">
  
  $$\begin{aligned}
  &\text{\tiny שורה 1} && 1v_1 + 1v_2 - 1v_3 - 1v_4 = -1 \\
  &\text{\tiny שורה 1 + שורה 2} && \color{blue}{0v_1 + 2v_2 + 0v_3 - 2v_4 = 1} \\
  &\text{\tiny שורה 1 - שורה 3} && \color{blue}{0v_1  - 2v_2 + 2v_3 + 0v_1 = 2} \\
  &\text{\tiny שורה 1 - שורה 4} && \color{blue}{0v_1 + 0v_2 + 2v_3 + 2v_4 = -2}
  \end{aligned}$$
  </div>
</div>

---

# נכפיל שורות בחצי 

<div style="position: absolute; left: 21%; top: 160px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 1px 4px;">

  $$\begin{aligned}
        1v_1 + 1v_2 - 1v_3 - 1v_4 &= -1 \\
        0v_1 + 2v_2 + 0v_3 - 2v_4 &= 1  \\
        0v_1 - 2v_2 + 2v_3 + 0v_4 &= 2 \\
        0v_1 + 0v_2 + 2v_3 + 2v_4 &= -2
  \end{aligned}$$
</div>

<div v-motion
  :initial="{ x: -20, opacity: 0 }"
  :enter="{ x: 0, opacity: 1 }"
  style="position: absolute; left: 350px; top: 320px; transform: translate(-50%, -50%); font-size: 100px;">

  ↳
</div>


<div v-motion
  :initial="{ x: 600, opacity: 0 }"
  :enter="{ x: -600, opacity: 1 }" >

  <div style="position: absolute; right: -730px; top: 290px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">
  
  $$\begin{aligned}
  &\text{\tiny שורה 1}             &&             {1v_1 + 1v_2 - 1v_3 - 1v_4 = -1 } \\
  &\text{\tiny  שורה 2 כפול 1/2  } && \color{blue}{0v_1 + 1v_2 + 0v_3 - 1v_4 = 1/2} \\
  &\text{\tiny  שורה 3 כפול 1/2  } && \color{blue}{0v_1  - 1v_2 + 1v_3 + 0v_1 = 1} \\
  &\text{\tiny  שורה 4 כפול 1/2  } && \color{blue}{0v_1 + 0v_2 + 1v_3 + 1v_4 = -1}
  \end{aligned}$$
  </div>
</div>

--- 

# נחבר ונחסר שורות


<div style="position: absolute; left: 21%; top: 160px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 1px 4px;">

  $$\begin{aligned}
    &{1v_1 + 1v_2 - 1v_3 - 1v_4 = -1 } \\
    &{0v_1 + 1v_2 + 0v_3 - 1v_4 = 1/2} \\
    &{0v_1  - 1v_2 + 1v_3 + 0v_1 = 1} \\
    &{0v_1 + 0v_2 + 1v_3 + 1v_4 = -1}
  \end{aligned}$$  
</div>



<div v-motion
  :initial="{ x: -20, opacity: 0 }"
  :enter="{ x: 0, opacity: 1 }"
  style="position: absolute; left: 330px; top: 320px; transform: translate(-50%, -50%); font-size: 100px;">

  ↳
</div>


<div v-motion
  :initial="{ x: 600, opacity: 0 }"
  :enter="{ x: -600, opacity: 1 }" >

  <div style="position: absolute; right: -740px; top: 300px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">
  
  $$\begin{aligned}
  &\text{\tiny שורה 2 - שורה 1}     && \color{blue}{1v_1 + 0v_2 - 1v_3 + 0v_4 = -3/2} \\
  &\text{\tiny שורה 2}              &&             {0v_1 + 1v_2 + 0v_3 - 1v_4 = 1/2} \\
  &\text{\tiny שורה 2 + שורה 3  }   && \color{blue}{0v_1 + 0v_2 + 1v_3 - 1v_1 = 3/2} \\
  &\text{\tiny שורה 4 }             &&             {0v_1 + 0v_2 + 1v_3 + 1v_4 = -1}
  \end{aligned}$$
  </div>
</div>

---

# נחבר ונחסר שורות


<div style="position: absolute; left: 22%; top: 160px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 1px 4px;">

  $$\begin{aligned}
    &{1v_1 + 0v_2 - 1v_3 + 0v_4 = -3/2} \\
    &{0v_1 + 1v_2 + 0v_3 - 1v_4 = 1/2} \\
    &{0v_1 + 0v_2 + 1v_3 - 1v_1 = 3/2} \\
    &{0v_1 + 0v_2 + 1v_3 + 1v_4 = -1}
  \end{aligned}$$  
</div>



<div v-motion
  :initial="{ x: -20, opacity: 0 }"
  :enter="{ x: 0, opacity: 1 }"
  style="position: absolute; left: 320px; top: 320px; transform: translate(-50%, -50%); font-size: 100px;">

  ↳
</div>


<div v-motion
  :initial="{ x: 600, opacity: 0 }"
  :enter="{ x: -600, opacity: 1 }" >

  <div style="position: absolute; right: -730px; top: 290px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">
  
  $$\begin{aligned}
  &\text{\tiny שורה 3 + שורה 1}     && \color{blue}{1v_1 + 0v_2 - 0v_3 - 1v_4 = 0} \\
  &\text{\tiny שורה 2}              &&             {0v_1 + 1v_2 + 0v_3 - 1v_4 = 1/2} \\
  &\text{\tiny שורה 3  }            &&             {0v_1 + 0v_2 + 1v_3 - 1v_1 = 3/2} \\
  &\text{\tiny שורה 3 - שורה 4 }    && \color{blue}{0v_1 + 0v_2 + 0v_3 + 2v_4 = -5/2}
  \end{aligned}$$
  </div>
</div>

---

# נכפיל שורה ב-1/2

<div style="position: absolute; left: 22%; top: 160px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 1px 4px;">

  $$\begin{aligned}
    &{1v_1 + 0v_2 - 0v_3 - 1v_4 = 0} \\
    &{0v_1 + 1v_2 + 0v_3 - 1v_4 = 1/2} \\
    &{0v_1 + 0v_2 + 1v_3 - 1v_1 = 3/2} \\
    &{0v_1 + 0v_2 + 0v_3 + 2v_4 = -5/2}
  \end{aligned}$$  
</div>



<div v-motion
  :initial="{ x: -20, opacity: 0 }"
  :enter="{ x: 0, opacity: 1 }"
  style="position: absolute; left: 320px; top: 320px; transform: translate(-50%, -50%); font-size: 100px;">

  ↳
</div>


<div v-motion
  :initial="{ x: 600, opacity: 0 }"
  :enter="{ x: -600, opacity: 1 }" >

  <div style="position: absolute; right: -730px; top: 290px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">
  
  $$\begin{aligned}
  &\text{\tiny  שורה 1}     &&                      {1v_1 + 0v_2 - 0v_3 - 1v_4 = 0} \\
  &\text{\tiny שורה 2}              &&              {0v_1 + 1v_2 + 0v_3 - 1v_4 = 1/2} \\
  &\text{\tiny שורה 3  }            &&              {0v_1 + 0v_2 + 1v_3 - 1v_1 = 3/2} \\
  &\text{\tiny  שורה 4 כפול 1/2 }   && \color{blue} {0v_1 + 0v_2 + 0v_3 + 1v_4 = -5/4}
  \end{aligned}$$
  </div>

  
</div>


---

# נחבר ונחסר שורות

<div style="position: absolute; left: 22%; top: 160px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 1px 4px;">

  $$\begin{aligned}
    &{1v_1 + 0v_2 - 0v_3 - 1v_4 = 0} \\
    &{0v_1 + 1v_2 + 0v_3 - 1v_4 = 1/2} \\
    &{0v_1 + 0v_2 + 1v_3 - 1v_1 = 3/2} \\
    &{0v_1 + 0v_2 + 0v_3 + 1v_4 = -5/4}
  \end{aligned}$$  
</div>



<div v-motion
  :initial="{ x: -20, opacity: 0 }"
  :enter="{ x: 0, opacity: 1 }"
  style="position: absolute; left: 330px; top: 320px; transform: translate(-50%, -50%); font-size: 100px;">

  ↳
</div>


<div v-motion
  :initial="{ x: 600, opacity: 0 }"
  :enter="{ x: -600, opacity: 1 }" >

  <div style="position: absolute; right: -740px; top: 290px; transform: translate(-50%, -50%) scale(1.5); background-color:rgb(241, 241, 221); padding: 5px 10px;">
  
  $$\begin{aligned}
  &\text{\tiny  שורה 4 + שורה 1}             && \color{blue} {1v_1 + 0v_2 - 0v_3 + 0 v_4 = -5/4} \\
  &\text{\tiny  שורה 4 + שורה 2}              && \color{blue} {0v_1 + 1v_2 + 0v_3+ 0 v_4 = -3/4} \\
  &\text{\tiny שורה 4 + שורה 3  }            && \color{blue} {0v_1 + 0v_2 + 1v_3 + 0 v_1 =  1/4} \\
  &\text{\tiny  שורה 4  }                     &&              {0v_1 + 0v_2 + 0v_3 + 1v_4 = -5/4}
  \end{aligned}$$
  </div>
</div>

---

# רחפן פותר את המשוואות האלה מאות פעמים בשניה

<div style="position: absolute; left: 50%; top: 60%; transform: translate(-50%, -50%) scale(3);">

```mermaid
graph TB
    classDef sensor fill:#e1f5fe
    classDef rotor fill:#ffecb3
    classDef drone fill:#f8bbd0

    S1[חיישן גובה]:::sensor --> D
    S2[חיישני זווית]:::sensor --> D
    RC[שלט רחוק] --> D
    CAM[מצפן]:::sensor --> D
    
    D[מחשב הטיסה]:::drone --> R1[מנוע 1]:::rotor
    D --> R2[מנוע 2]:::rotor
    D --> R3[מנוע 3]:::rotor
    D --> R4[מנוע 4]:::rotor

    style D font-weight:bold
```
</div>    

---

# כתפי ענקים
<br>

<div class="grid grid-cols-3 gap-1">

<div>
  <div v-click>
    <h2 style="width: 250px">תשעת הפרקים של אמנות המתמטיקה</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/%E4%B9%9D%E7%AB%A0%E7%AE%97%E8%A1%93%E7%B4%B0%E8%8D%89%E5%9C%96%E8%AA%AA.jpg/220px-%E4%B9%9D%E7%AB%A0%E7%AE%97%E8%A1%93%E7%B4%B0%E8%8D%89%E5%9C%96%E8%AA%AA.jpg" style="width: 250px; height: 300px">
    <p style="text-align: center; width:250px">כתב סיני עתיק בן 2000 שנה!</p>
  </div>
</div>

<div>
  <div v-click>
    <h2 style="text-align: center;">קרל פרידריך גָּאוּס <br> 1777-1855</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/9b/Carl_Friedrich_Gauss.jpg" style="width: 250px; height: 300px">
    <p style="text-align: center; width:250px"> אלגוריתם החילוץ של גָּאוּס</p>
  </div>
</div>

<div>
  <div v-click>
    <h2 style="text-align: center;">מחשב  <br> ARM Cortex-M3</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/STM32F100C4T6B-HD.jpg/220px-STM32F100C4T6B-HD.jpg" style="width: 250px; height: 300px">
    <p style="text-align: center; width:250px"> 24 מיליון פעולות חשבון בשנייה</p>
  </div>
</div>

</div>

---

# נקודה למחשבה

<div class="flex flex-col items-center justify-center" style="direction: rtl;">
  <div v-click>
    <h2>הפרש המהירויות בין המנועים יוצר כוח</h2>
  </div>

  <div v-click class="my-8">
    <img src="/nadneda.svg" style="width: 350px;">
  </div>

  <div>
    <h2 v-click>האם הכוח פרופורציונאלי ל:</h2>
    <ul class="list-none">
      <p v-click>🤔 זווית?</p>
      <p v-click>🤔 מהירות שבה הזווית משתנה?</p>
      <div v-click>
        <span v-mark="{ at: 8, color: 'red', type: 'circle' }">
          🤔 תאוצה (קצב שינוי המהירות) של הזווית?
        </span>
      </div>
    </ul>
  </div>



</div>

<div v-click style="position: absolute; left: 85%; top: 60%; transform: translate(-50%, -50%); text-align: center;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/39/GodfreyKneller-IsaacNewton-1689.jpg" 
          style="width: 200px;">
    <h2>סר אייזק ניוטון</h2>
</div>
  
---

# סיכום

<br>

## רובוט הוא מכונה המסוגלת להתמודד עם מציאות בלתי ידועה מראש
 
<br>

## רובוטים מעופפים יכולים לשלוט בכיוון ובגובה על ידי שינוי מהירות המנועים
  #### ההפרש בין המנועים הקדמיים לאחוריים מייצר זווית קדימה או אחורה  
  #### ההפרש בין המנועים השמאליים לימיניים מייצר זווית שמאלה או ימינה
  #### ההפרש בין המנועים המסתובבים עם כיוון השעון לשניים האחרים מייצר סיבסוב
  #### סכום מהירויות המנועים יוצר כוח כלפי מעלה או מטה  

<br>

## המחשב של הרחפן פותר משוואות מאות פעמים בשניה
  #### כך הוא מנצל את דרגות החופש כדי לתקן שגיאות בכל הכיוונים בבת אחת


<br>

## הכל בנוי על מתמטיקה שהתפתחה במשך שנים רבות

  #### אם אתם רוצים לעסוק במדע או הנדסה, אני מציע להתרכז במתמטיקה
  #### זה נכון גם בתצחום התוכנה והאלקטרוניקה


<div style="position: absolute; left: 40px; top: 270px; text-align: center;">
    <img src="/public/math-is-fun.webp" width="250">
</div>
