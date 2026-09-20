# AI Fluency (The 4Ds) 

> **Source page:** [AI Fluency: A Crash Course](https://agentfactory.panaversity.org/docs/ai-fluency-crash-course) — The AI Agent Factory (Panaversity)
> **Framework credit:** 

---

## Table of Contents

0. [Poora flow 60 second mein](#0-poora-flow-60-second-mein)
1. [Running example: Sara ka online store](#running-example-sara-ka-online-store)
2. [AI Access ≠ AI Fluency](#1-ai-access--ai-fluency)
3. [Three Modes: Automation, Augmentation, Agency](#2-three-modes-automation-augmentation-agency)
4. [D1: Delegation](#3-d1-delegation--decide)
5. [D2: Description](#4-d2-description--explain)
6. [D3: Discernment](#5-d3-discernment--check)
7. [D4: Diligence](#6-d4-diligence--own)
8. [The 4D Loop + Agent Factory scaling](#7-the-4d-loop--agent-factory-scaling)
9. [Four Beginner Mistakes](#8-four-beginner-mistakes)
10. [MASTER DIAGRAM](#9-master-diagram)
11. [Quick Recall Cheat Sheet](#10-quick-recall-cheat-sheet)

---

## 0. Poora flow 60 second mein

Is page ki poori kahani ek chain hai. Har step agle step ki **wajah** banta hai:

```
 Same AI sab ke paas hai
        |
        v
 Phir results alag kyun?  -------->  Farq "AI Fluency" ka hai        (Sec 1)
        |
        v
 AI ki nature: confident but kabhi galat, har chat fresh start        (Sec 1)
        |
        v
 AI ko kitni freedom dein? ------->  Automation / Augmentation /
                                     Agency                           (Sec 2)
        |
        v
 4 human skills (har mode mein same):
   DELEGATION -> DESCRIPTION -> DISCERNMENT -> DILIGENCE              (Sec 3-6)
        |
        v
 Chaaron ek loop hain, aur chat se Digital FTE / Agent Factory
 tak scale hoti hain                                                  (Sec 7)
        |
        v
 Har beginner mistake = koi ek D missing                              (Sec 8)
```

**Ek line mein:** Pehle tay karo AI kya karega, phir usay clearly samjhao, phir jo aaye usay check karo, aur natije ki zimmedari apni rakho.

---

## Running example: Sara ka online store

Poore notes mein ek hi example chalayenge taake flow connected rahe.

> **Sara** ek online kapron ke store ki owner hai. Wo ek **Customer Support AI agent** banana chahti hai jo tracking, size questions aur refund requests handle kare.

Har D ke section mein dekhna: Sara ka *same* project kaise 4 alag sawal poochta hai.

---

## 1. AI Access ≠ AI Fluency

### Easy samajh

Do log same AI, same plan, same subah use karte hain. Ek ko aisa kaam milta hai jo ship ho sakta hai, dosre ko polished cheez milti hai jo phenkni parti hai. Tool same tha, **istemal alag tha**. Is istemal ki quality ko **AI Fluency** kehte hain.

Fluency ke 4 qualities:

| Quality | Matlab |
|---|---|
| **Effective** | Goal tak pohanchna |
| **Efficient** | Time, effort aur **tokens** waste na karna (token = text ka chhota piece jo AI parhta/likhta hai, aur jiska bill banta hai) |
| **Ethical** | AI ko fairly aur openly use karna |
| **Safe** | People, privacy, security aur important info ko protect karna |

Ye "magic prompts" collect karne ka naam nahi. Ye **achhe human decisions** ka skill-set hai.

### Real example

Bilal aur Sara dono same AI se product descriptions likhwate hain. Bilal likhta hai "kurta ki description likho", jo generic cheez milti hai wo use kar leta hai. Sara pehle apni audience, tone aur length sochti hai, phir jawab check karti hai. Same AI, alag results.

### Technical depth: AI ki 3 baatein jo yaad rakhni hain

```
Fact 1: "Sounds right" != "Is right"
        AI patterns se agla likely text predict karta hai.
        Confident ghalat jawab = HALLUCINATION.

Fact 2: Same request, har baar same answer guaranteed nahi
        (output vary karta hai)

Fact 3: AI sirf wahi info use karta hai jo usay milti hai
        (training knowledge, chat, documents, memory, search, tools).
        Info missing hui to wo GUESS karta hai.
```

Aur ek important farq: **AI ko ek chat se doosri chat tak kuch yaad nahi rehta.** "Memory feature" sirf notes save karke agli chat ke context mein bhej deta hai. Model khud phir bhi zero se start karta hai.

Ek aur farq insaan colleague se: colleague hichkichata hai to bata deta hai. AI ka tone confident hi rehta hai chahe wo sure ho ya na ho.

### Ye 3 facts aagay kaise link hote hain?

```
Fact 3 (info missing = guess)   --->  isliye DESCRIPTION zaroori
Fact 1 (confident but galat)    --->  isliye DISCERNMENT zaroori
Fact 2 (har baar alag)          --->  isliye LOOP (iterate) zaroori
AI kisi ko accountable nahi     --->  isliye DILIGENCE zaroori
Har kaam AI ke liye theek nahi  --->  isliye DELEGATION zaroori
```

---

## 2. Three Modes: Automation, Augmentation, Agency

### Easy samajh

AI ke saath kaam karne ke 3 tareeqay hain. Farq ek hi cheez ka hai: **AI ko agla step khud choose karne ki kitni freedom hai.**

```
AI ki freedom:  KAM ------------------------------------------> ZYADA

 AUTOMATION            AUGMENTATION             AGENCY
 "Ye task karo"        "Mere saath socho"       "Ye goal achieve karo"
 Aap = script writer   Aap = co-creator         Aap = director
 Steps: aap dete hain  Steps: milkar banate      Steps: AI khud choose
                       hain (back-and-forth)     karta hai
 Fail hota hai jab:    Fail hota hai jab:       Fail hota hai jab:
 koi step kharab       baat-cheet bhatak jaye    goal/boundary galat samjha
```

### Real example (Sara)

| Mode | Sara ka kaam |
|---|---|
| Automation | "Ye 50 customer emails ka summary 5 bullets mein do." |
| Augmentation | "Meri refund policy ke loopholes dhoondne mein meri madad karo, main bhi sawal karungi, tum bhi challenge karo." |
| Agency | "Meri support inbox sambhalo: routine sawalon ka jawab do, important flag karo, aur jahan sure nahi ho mujhse poochho." |

Agency mein AI ko khud decide karna parta hai: routine kya hai, important kya hai, aur kab poochna hai.

### Technical depth: Agency ki definition mein 2 ahem lafz

Framework ke mutabiq agency = insaan AI ko **configure** karta hai taake wo **future** tasks independently kare, aur **doosron ke liye** bhi.

- **Future:** Aap somwar ko setup karte hain, AI jumeraat ka kaam aapki ghair-maujoodgi mein karta hai.
- **For others:** Jis se AI baat karta hai wo aap nahi, aapka customer/student/colleague ho sakta hai.

Is ka matlab: automation aur augmentation mein aap "chair mein" baithe hain. Agency mein aap chair se uth jaate hain, isliye **judgment pehle se system mein bana kar dena parta hai.**

| | Automation | Agency |
|---|---|---|
| Aap dete hain | Task / steps | Goal + boundaries |
| AI decide karta hai | Bohat kam | Bohat se agle steps |
| Aap ka role | Script writer | Director |
| Common failure | Ek step kharab | Goal ya boundary galat samjha |

Koi mode "best" nahi. Ek project teeno use kar sakta hai: data extraction **automate**, exceptions par **augmentation**, routine cases par **limited agency**.

### Agent Factory connection

```
Mode 1 (Problem-solving)  -> general agents: automation + augmentation
Mode 2 (Manufacturing)    -> agency ko systematic banana
                             = DIGITAL FTE
```

**Digital FTE** = ek AI worker jo kisi defined job ke liye doosron ke liye set kiya gaya ho (FTE = full-time equivalent, yaani company ek full-time employee ko kaise count karti hai). Ye sirf "AI kuch kar raha hai" nahi, balki **job definition + permissions + rules + governance** ke andar kaam karta hai, aur **System of Record** (business ke official data aur rules ka trusted store) se parhta hai.

---

## 3. D1: Delegation = DECIDE

### Easy samajh

Sab se common beginner mistake pehle prompt se **pehle** hoti hai: log sochay bagair type karna shuru kar dete hain. Delegation ka matlab sirf "kaam AI ko dena" nahi. Ye **workflow design** hai: kaam insaan aur AI mein kaise divide ho.

### Diagram: Delegation ke 3 parts

```
                        DELEGATION
                            |
      +---------------------+----------------------+
      |                     |                      |
PROBLEM AWARENESS    PLATFORM AWARENESS     TASK DELEGATION
"Kya chahiye?"       "Kaunsa tool?"         "Kaun kya karega?"
- goal               - reasoning model      - Human: judgment,
- audience             (mushkil multi-step)     approval, accountability
- success kya hai    - search AI (current   - AI: drafts, mechanical
- risks                info)                    work
- kahan human        - coding agent         - AI + Human: brainstorm,
  zaroori hai        - agent system           options
                       (multi-step, tools)
```

Framework ka apna doosra naam Problem Awareness ke liye "goal and task awareness" hai, dono ek hi cheez hain.

### Real example (Sara)

Sara likh deti hai "support agent bana do" to AI kuch bana dega, lekin asli sawal ye hain, aur ye **prompt ke nahi, business ke sawal hain**:

- Kaun se customers ko agent reply kare?
- Refund kitne din tak?
- Kitni rakam se upar human approval?
- Customer dispute kare to kya?
- Agent kaunsa system parh sakta hai? Sirf draft kare ya send bhi?

Task split ka table:

| Task | Owner | Wajah |
|---|---|---|
| Refund policy tay karna | **Human (Sara)** | Business decision |
| Order tracking status batana | **AI** | Clear, repeatable, tool se data milta hai |
| Size/fabric sawalon ke jawab (catalog se) | **AI** | Documents se grounded |
| Refund approve karna (bari rakam) | **Human** | High impact, wapas nahi hota |
| Gussay wala / legal dhamki wala customer | **Human (escalate)** | Emotion + risk |
| Refund ka total calculate karna | **Code/tool** | AI numbers predict karta hai, compute nahi (Sec 6 numbers rule) |

Sawal badal jata hai: "Kya AI ye kar sakta hai?" se **"Kaunsa hissa AI kare, kaunsa main, aur kyun?"**

### Technical depth

- **Problem awareness -> Specification.** Jab aap agents doosron ke liye banate hain to ye goal, constraints, risks aur *definition of done* ki spec ban jati hai (isi liye Spec-Driven Development agla course hai).
- **Task delegation -> Digital FTE ka boundary.** Kya kar sakta hai, kya insaan ke paas rehta hai, kya escalate hoga. *(General engineering note: ise aksar permissions / least-privilege aur human-in-the-loop gates ke roop mein implement kiya jata hai.)*
- **Platform awareness:** model names yaad karne ki zaroorat nahi (market tez badalti hai), lekin har baar poochne ki aadat: "Kya ye is kaam ke liye sahi tool hai?"
- Page ka principle: **domain expert pehle, AI delegator baad mein.** Jo kaam aap khud nahi samajhte, use delegate karna mushkil hai.

---

## 4. D2: Description = EXPLAIN

### Easy samajh

AI naye colleague ki tarah hai jise aapke context ka kuch pata nahi. Agar aap important cheez chhor dein to wo **guess** karega, aur reasonable guess bhi galat ho sakta hai. Description = AI ko wo info aur guidance dena jo kaam ke liye chahiye. Ye "achha prompt likhne" se **bara** concept hai.

### Diagram: Description ke 3 parts

```
DESCRIPTION
 |
 |-- 1. PRODUCT     "WHAT"  -> mujhe kya chahiye?
 |      output type, audience, format, length, tone, topics, kya nahi chahiye
 |
 |-- 2. PROCESS     "HOW"   -> kaam kaise approach ho?
 |      steps, order, method, examples, finish se pehle checks
 |
 |-- 3. PERFORMANCE "HOW TO WORK WITH ME" -> AI ka behavior kaisa ho?
        concise/detailed, challenge kare ya support, uncertainty flag kare,
        pehle sawal poochhe ya assumption le

Yaad rakho:  What --> How --> How to work with me
Principle:   Best prompt "clever" nahi, "complete" hota hai.
```

### 4.1 Product description

Vague: *"Refund ka reply likho."*

Complete: *"Customer ko refund status ka reply likho: customer ki zaban (Urdu ya English) mein, 80 words se kam, order number aur agla step shamil karo, tone polite ho, aur refund 'guaranteed' kabhi mat likho."*

Dusra prompt zyada intelligent nahi, sirf zyada **complete** hai.

### 4.2 Process description

Jab kaam ke kai stages hon, sab kuch ek request mein mat do. Warna aap sirf **akhri jawab** check kar sakte hain. Kaam ko **order** ke hisaab se todo aur har step ke baad check karo.

```
Step 1: order lookup tool se status lo         --> check: 3-4 orders manually verify
Step 2: policy doc se eligibility dekho        --> check: kya sirf doc ki baat hai?
Step 3: agar clear nahi to escalate flag       --> check: sahi cases escalate hue?
Step 4: reply draft                            --> check: sirf wahi claim jo step 1-3 ne support kiya
```

**Rule:** jis step ki galti sab se door tak phailti hai use **pehle** rakho aur pehle check karo. (Ghalat data step 1 mein ho to comparison, scoring aur draft sab mein "theek dikhne" lagta hai.)

### 4.3 Performance description (do sizes, ek hi skill)

- **Chat scale:** "Meri baat se sirf politeness mein agree mat karo, weak assumptions ko challenge karo, uncertainty flag karo." Ye sirf aap ke liye rule hai.
- **System scale:** Deployed agent ke liye ek rule likhte hain jo hazaron users par lagta hai jo us instruction ko kabhi dekhte bhi nahi. Misal: "Refund khud approve mat karo; agar info na ho to 'mujhe confirm karna hoga' kaho."

> Chat mein buri performance description sirf 10 minute annoy karti hai. Deployed agent mein wahi **product** hai.

### Technical depth: Prompt Engineering -> Context Engineering

```
PROMPT ENGINEERING:   "Ye ek message kaise likhoon?"
CONTEXT ENGINEERING:  "AI ke kamyab hone ke liye kaunsi SAARI info
                       available honi chahiye?"

AI ko jo kuch "dikhta" hai (context):
 |-- System prompt   -> performance description, har chat ke shuru mein, permanent
 |-- SKILL.md        -> process description, reusable tareeqa
 |-- Documents / DB  -> System of Record: facts, rules, governance
 |-- Memory notes    -> purani chats ke saved notes
 |-- Chat history    -> abhi tak ki baat
 |-- Tools           -> search, code run, lookup, email...
 |-- Aap ka prompt   -> product description, ab kya chahiye
```

**Sabaq:** ek khoobsurat prompt us agent ko nahi bacha sakta jiske paas ghalat data, missing rules, kharab examples ya zaroori tool tak access na ho.

Ek tip: agar prompt likhna nahi aa raha to apni situation normal zaban mein bata do aur AI se kaho ise clear instruction bana de.

**Agent Factory link:** Description scale hokar architecture banti hai. Details: [System of Context](https://agentfactory.panaversity.org/docs/ecosystem/system-of-context) aur [System of Record](https://agentfactory.panaversity.org/docs/ecosystem/system-of-record).

---

## 5. D3: Discernment = CHECK

### Easy samajh

Description poochti hai: *"Maine kaam theek se samjhaya?"*
Discernment poochti hai: *"AI ne kaam theek kiya?"*

Masla ye hai ke ghalat jawab pe warning label nahi hota. Wo utna hi polished, detailed aur confident lagta hai. **Automation bias** = automated jawab par zaroorat se zyada bharosa karne ka insani rujhan, khaas kar jab wo professional lage.

### Diagram: Discernment ke 3 parts (Description ke 3 parts ka mirror)

```
DESCRIBE:   product        process          performance
               |              |                 |
               v              v                 v
DISCERN:    product        process          performance
            "Result        "Kya AI ke saath  "Jab AI akela kaam
             achha hai?"    kaam karna        kare, to log
                            faida de raha     achhe se serve ho
                            hai?"             rahe hain?"
```

### 5.1 Product discernment: result achha hai?

6 sawal: Kya factually sahi hai? Har zaroori requirement follow hui? Kuch missing to nahi? Internally consistent hai? Kya expert credible samjhega? Kya main apna naam laga sakta/sakti hoon?

Ye sawal jawab ko 3 cheezon se compare karte hain: **jo aapne maanga, source material, aur aapke field ke standards.** Do pass ho kar ek fail ho sakta hai, aur wahi ek maayne rakhta hai.

**Hallucination ke 4 red flags:**

| Red flag | Misal |
|---|---|
| **Zyada exact specifics** jo aapne diye hi nahi | "Vendor ne pichhle saal 99.97% orders time par diye" (exact number "checked" lagta hai, source kholo) |
| **Confidence jahan expert hichkichata** | "It depends" wale sawal ka seedha "haan" |
| **Lambay output mein contradiction** | Page 2 pe flat fee, page 6 pe per-user fee |
| **Aisa action claim jo hua hi nahi** | "Maine email bhej di", "tests run kar liye" (jab tak tool ka proof na ho, wo sirf ek jumla hai) |

**Justification bhi check karo, sirf conclusion nahi.** Sahi answer ghalat assumption par khara ho to tikta nahi. Isliye AI se kaho: assumptions, evidence, decision criteria, calculations aur alternatives dikhaye. (Ye review ke liye di gayi justification hai, model ki hidden reasoning ka record nahi.)

**Grounding pattern (jab jawab aapke documents se aana chahiye):**

```
1) "Sirf attached documents se jawab do, apni training knowledge se nahi."
2) "Agar document mein na likha ho to kaho 'likha nahi hai', guess mat karo."
3) "Har claim ke saath section heading aur wo sentence do jahan se aaya."
```

Line 1 gap-filling roakti hai, line 2 AI ko "nahi pata" kehne ki ijazat deti hai, line 3 aapko 1 minute ka verify karne layak cheez deti hai.

### 5.2 Process discernment: kya ye tareeqa kaam kar raha hai?

Kabhi jawab theek hota hai magar **working relationship** kharab hoti hai. Session ko judge karo:

- AI feedback se adapt ho raha hai ya wapas purani ghalti par?
- Do baar correct karne ke baad bhi wahi ghalti?
- Itna agreeable ho gaya ke useless?
- Har turn formatting theek karne mein ja raha hai?
- Kya main draft ko itna edit kar raha hoon jitna khud likhne mein lagta?

Bura sach: 20 minute steering jo 15 minute bachaye wo **loss** hai, sirf productive "mehsoos" hota hai.

Jab kaam na kar raha ho, 3 escalation moves: **(1)** performance description badlo, **(2)** tool badlo, **(3)** kaam wapas khud le lo. Teeno fluency hain, sirf teesri "haar" jaisi lagti hai.

### 5.3 Performance discernment: jab aap dekh nahi rahe

Ye tab aata hai jab aap agency use karte hain. Sawal ek jawab ka nahi, balki ye hai: AI ka independent behavior logon ke liye achha nateeja deta hai ya nahi?

Misal: ek AI tutor har sawal ka sahi jawab deta hai, lekin jaise hi student hichkichaye seedha solution de deta hai, to student kuch seekhta nahi. Ye chat window ke andar se nahi dikhta, sirf **bohat se cases** mein dikhta hai (users agla kya karte hain, kis baat ki complaint karte hain, kaun se cases har baar ek tarah se fail hote hain). Hazaar conversations haath se parhna mumkin nahi, isliye ye **infrastructure** ban jata hai.

### Description <-> Discernment Loop

```
   Describe --> AI produces --> Discern --> Refine
   ^                                            |
   +--------------------------------------------+
   (pehla jawab sirf DRAFT hai; loop chalta rehta hai)
```

- Agar Discernment ko problem dikhe, fix **aksar better Description** hoti hai.
- Kabhi kabhi fix **Delegation** hoti hai: tool ghalat tha, ya wo hissa AI ka tha hi nahi.

**Feedback ka pattern:** `Problem -> Why it matters -> Direction`

| | Example |
|---|---|
| Weak | "Galat hai. Dobara karo." |
| Better | "Doosra section enterprise customers assume karta hai. Hamare customers chhote sellers hain, isliye salah mehnga hai. Us section ko limited budget wale ek-aadmi business ke liye dobara likho." |

**Do aur tareeqay:** (1) edit **named passes** mein karo (clarity pass, tone pass, formatting pass), ek general sweep mein nahi. (2) Bade stakes mein 2-3 drafts maango aur sab se mazboot se edit karo.

**Aakhir mein 3 mein se ek faisla:** `Ready to use` / `Needs revision` / `Needs human override`. Aglay message se pehle tay karo, warna "bas ek chhoti si change aur" wala loop poora din kha jata hai.

### Technical depth: Discernment kaise engineering banti hai

```
Manual sawal: "Kya ye achha hai?"
        |
        v
EVAL SUITES (repeatable tests jo AI output ko score karein)
+ monitoring + sampling + release gates
```

Aap wo judgment automate nahi kar sakte jo aapne khud kabhi karna nahi seekha. Isliye pehle chat mein discernment seekho, phir system mein banao. *(Agla padhna: [Trusting the Checker](https://agentfactory.panaversity.org/docs/trusting-the-checker-crash-course) aur [Eval-Driven Development](https://agentfactory.panaversity.org/docs/eval-driven-development-crash-course).)*

**Sara ka discernment plan:** Purane 100 tickets jin ke jawab senior agent ne diye the un par agent chalao. Dekho: kitne match sahi, kitne ghalat-lekin-confident, kaun se cases sahi escalate hue, kitne zaroorat se zyada escalate hue. Sath hi "successful" dikhne wale jawabon ka **sample bhi review** karo, kyunke system chup-chaap fail hokar bhi safe dikh sakta hai.

---

## 6. D4: Diligence = OWN

### Easy samajh

Pehle 3 Ds behtar **result** dilate hain. Diligence poochti hai: *"Kya mujhe AI is tarah use karna bhi chahiye?"*

Misal (Sara): uska staff member customers ke naam, phone numbers, addresses aur complaint history ek free public AI tool mein paste kar deta hai taake jawab jaldi likhe. Jawab shayad behtareen ho, lekin **use** ghalat hai: tool approved nahi, data private, customers ko pata nahi.

**Diligence** = AI ke istemal aur uske output ki zimmedari.

### Diagram: 3 waqt, 3 diligence

```
   PEHLE                  DAURAN                     BAAD
   (Creation)             (Transparency)             (Deployment)
   |----------------------|--------------------------|------------------->
   Tool approved hai?     Jahan AI ka role logon     Facts, sources, numbers
   Data kis ko dikh       ko affect kare wahan       check
   sakta hai?             honest raho                Bias, rights, policy check
   Data redact kiya?                                 High impact = human approval
```

### 6.1 Creation diligence (tool + data)

Share karne se pehle poochho: personal data hai? Confidential company info hai? Is tool mein daalne ki ijazat hai? Kaun access ya store kar sakta hai? Organization ne approve kiya? Koi legal/contract restriction?

Aksar fix "kaam chhor do" nahi, "data strip kar do" hota hai. **Redaction** = pehchan wali details hata dena par task ke liye zaroori pattern rakhna. AI ko pattern chahiye, shakhs nahi.

Redaction 2 taraf se fail hoti hai:
- **Zyada hata di:** feedback mein na grade na incident ho to feedback ban hi nahi sakti.
- **Kam hata di:** "wo akeli customer jis ne teesre din order cancel kiya" naam ki tarah hi pehchan deta hai.

Test: sirf jo aapne paste kiya wo parh kar koi bata sake ke ye kis ke baare mein hai? Aur redaction tool ke sawal ka jawab nahi hai: approved tool phir bhi chahiye.

### 6.2 Transparency diligence (AI ke role ke baare mein honesty)

Har AI-assisted kaam ka ailan zaroori nahi. Lekin jitna zyada result doosron ko affect kare (academic work, hiring, customer communication, medical/financial advice, professional reports, jo "original human work" ke tor par pesh ho), utna disclosure ka case mazboot. Rule context, organization, law aur professional standard par depend karta hai. Transparency ka matlab poora workflow publish karna nahi, sirf ye ke jahan AI ka role maayne rakhta ho wahan logon ko gumrah na karo.

### 6.3 Deployment diligence (jaane se pehle verify)

Publish, send, execute ya kisi decision mein use karne se pehle check karo: facts, sources ka wujood, calculations, bias/unfair outcomes, permissions/rights, organization policy, high-impact actions par human approval.

**Check ki gehrai = kitne log tak pohanchega + kya wapas ho sakta hai.**

| Cheez | Check |
|---|---|
| Apne liye note | Ek nazar |
| Customer ko welcome email | Poora parho |
| Regulator ko report | Dusra reviewer |
| Payment bhejna / folder delete | Act se **pehle** check (baad mein koi reviewer nahi) |

**Numbers Rule (bohat important):** Jis number par decision khara ho (total, percentage) wo **compute** hona chahiye, **generate** nahi. AI total ko spreadsheet ki tarah jama nahi karta, wo "likely dikhne wala" total predict karta hai, is liye har line theek ho kar bhi total ghalat ho sakta hai. Number spreadsheet, calculator ya us code se lo jo AI ne chalaya aur dikhaya, phir sum ke bajaye **inputs** check karo (sahi rows? sahi rate?).

**Sawal jo hamesha poochho:** *"Kya main is par apna naam confidence se laga sakta/sakti hoon?"* Agar nahi, kaam ready nahi.

**Jab case unclear ho** (masalan AI ne applicants ki shortlist bana di, aap nahi jaante ke kisi khaas school ke graduates ko favor to nahi kiya):

1. Kaun affect hoga (wo bhi jo result kabhi nahi dekhenge)?
2. Un ke liye kya ghalat ho sakta hai, aur kya wo bata payenge?
3. Fair outcome kaisa dikhega?
4. Kya disclose hona chahiye, aur kis ko?

Jawab mil jayein to faisla karo aur likh lo. Na milein to us ko **escalate** karo jo decision ka owner hai. Guess karna wo option hai jo unclear case ko aap ki ghalti bana deta hai.

> **AI kaam automate kar sakta hai, accountability nahi.** Harmful decision ho to system chalane wali organization zimmedar hai. Coding assistant ne security flaw daala aur engineer ne ship kiya to engineer aur organization dono owner hain.

### Technical depth: Diligence system mein kaise dikhti hai

| Diligence type | System scale par |
|---|---|
| Creation | Data rules, access control, approved-tool policy |
| Transparency | Disclosure aur user-experience design |
| Deployment | Evaluation gates, audit logs, monitoring, human review |

Ek deep baat: policy tabhi chalti hai jab approved tool utna hi aasan ho jitna wo tool jo log pehle se kholay baithe hain. Agar approved tool ke liye form aur hafta bhar intezar ho to "aasan galat raasta" sirf personal ghalti nahi, **policy ki khaami** hai. Policy owner ko batao ke kahan mushkil thi.

**Sara ka diligence plan:** Customer data approved infrastructure mein rahe, redacted ho jahan ho sake. Agent ke actions ke logs. Customers ko batao ke reply AI-assisted hai. Refund ka aakhri approval insaan ke paas, aur wahi accountable.

Agent Factory isi liye **governance-first** hai. Aagay parho: [System of Record](https://agentfactory.panaversity.org/docs/ecosystem/system-of-record) aur [Designing the Vertical SoR](https://agentfactory.panaversity.org/docs/ecosystem/designing-the-vertical-sor).

---

## 7. The 4D Loop + Agent Factory scaling

### Easy samajh

Asal kaam mein chaaron D mix hote hain. Page ka operating loop:

```
Delegate -> Describe -> Discern -> Be diligent -> Repeat as needed
```

(Authors khud sirf Description <-> Discernment loop sikhate hain; ye book chaaron ko ek loop banati hai.)

### Sara ka poora walk-through

```
1. DELEGATION   Sara tay karti hai: agent tracking/size sawal handle karega,
                refund draft karega; approve, write-off, gussay wale customers
                insaan ke paas; bari rakam wale cases named person ko escalate.

2. DESCRIPTION  Agent ko deti hai: refund policy doc, order-lookup tool,
                past achhe replies ke examples, tone guide, escalation rules,
                aur ye rule: refund khud approve mat karo, customer ko guaranteed
                promise mat do.

3. DISCERNMENT  Purane trusted tickets par test, correct/confident-wrong/
                escalation rates, successful lagne wale replies ka sample review,
                waqt ke saath performance monitor.

4. DILIGENCE    Data approved infra mein, actions logged, AI-assisted disclosure,
                aakhri sign-off aur zimmedari insaan ki.

5. REPEAT       Jo fail hua uske hisaab se pehle Description theek karo,
                zaroorat ho to Delegation (boundary/tool) badlo.
```

### Chat skill -> Factory system

| Competency | Chat mein | Agent Factory mein |
|---|---|---|
| **Delegation** | AI se kya karwana hai tay karna | Digital FTE ka scope aur human/AI boundary |
| **Description** | Instructions aur context dena | System prompts, skills, context engineering, Systems of Record |
| **Discernment** | Jawab review karna | Evals, monitoring, sampling, trusting the checker |
| **Diligence** | Data protect karna, result own karna | Governance, permissions, audit, disclosure, human review |

**Personal skill system property ban jati hai.** Isi liye chat mein practice = bade AI systems banane aur govern karne ki rehearsal.

### 10-80-10 Rule aur Four Survival Skills

Book ke 4 survival skills: **set the direction, orchestrate AI, judge the truth, connect with people.** Pehle 3 mil kar **10-80-10 Rule** banate hain:

```
WAQT:   |--- 10% ---|---------------- 80% ----------------|--- 10% ---|
KAAM:   Set direction   Orchestrate AI (kaam chalao)        Judge truth
D's:    Delegation +    Description <-> Discernment          Discernment
        Description     baar baar                            (ship se pehle
                                                              critical)
        ===================== DILIGENCE poore 100% mein ==============
```

Diligence koi aakhri checkbox nahi, poore workflow ko gher leti hai.

---

## 8. Four Beginner Mistakes

Zyadatar frustrating AI experiences in 4 mein se ek hoti hain, aur har ek **ek missing skill** hai:

| # | Mistake | Missing skill | Fix |
|---|---|---|---|
| 1 | Success define kiye bagair prompt karna | **Delegation** | Goal, audience, constraints aur human/AI split pehle tay karo |
| 2 | Pehle jawab ko final samajhna (ya kamzor pehle jawab par AI ko bekaar keh dena) | **Description <-> Discernment loop** | Result dekho, specific feedback do, dobara try |
| 3 | Polished jawab ko sahi samajh lena | **Discernment** | Facts, assumptions, calculations, sources verify |
| 4 | Privacy/accountability ke baare mein tab sochna jab masla ho jaye | **Diligence** | Data, disclosure, approval, accountability rules deploy se pehle |

---

## 9. MASTER DIAGRAM

: purpose -> mode -> 4D loop -> scaling -> timeline -> mistakes.

```
=======================================================================
 LAYER 0: PURPOSE
=======================================================================
 AI ke saath kaam ho:  EFFECTIVE + EFFICIENT + ETHICAL + SAFE
 (AI ki nature: hallucination | har baar alag | sirf available info |
  chat-to-chat yaadasht nahi)  ==> isi liye humein 4 human skills chahiye

=======================================================================
 LAYER 1: MODE  -- AI ko kitni freedom?
=======================================================================
                                    |
   +--------------------+-----------+---------+--------------------+
   |                    |                     |
AUTOMATION         AUGMENTATION              AGENCY
"Ye task karo"     "Saath socho"             "Goal pursue karo"
script writer      co-creator                director
                                             (future tasks + for OTHERS)
   |                    |                     |
   +--------------------+-----------+---------+
                                    |
                                    v
=======================================================================
 LAYER 2: THE 4D OPERATING LOOP  (har mode mein same)
=======================================================================

+--------------------+    +--------------------+
| 1. DELEGATION      |    | 2. DESCRIPTION     |
|    (DECIDE)        |--->|    (EXPLAIN)       |
| - problem aware    |    | - product (what)   |
| - platform aware   |    | - process (how)    |
| - task delegation  |    | - performance      |
+---------^----------+    +---------+----------+
          |                         |
          | galat split?            | AI draft banata hai
          | galat tool?             v
+---------+----------+    +---------v----------+
| 4. DILIGENCE       |    | 3. DISCERNMENT     |
|    (OWN)           |<---|    (CHECK)         |
| - creation (pehle) |    | - product (result) |
| - transparency     |    | - process (way)    |
| - deployment (baad)|    | - performance      |
+--------------------+    +--------------------+

 Discernment ko problem dikhe? --> pehle DESCRIPTION theek karo,
 phir zaroorat ho to DELEGATION wapas. Result: Ready / Revise / Human override.

=======================================================================
 LAYER 3: SCALE  -- chat skill se Agent Factory system tak
=======================================================================
 CHAT MEIN (aap)                       AGENT FACTORY MEIN (system)
 -----------------------------         ---------------------------------
 Delegation  = AI se kya karwaoon? --> Digital FTE scope + human/AI boundary
 Description = prompt + context    --> system prompt, SKILL.md, System of Record
 Discernment = jawab review        --> evals, monitoring, sampling, gates
 Diligence   = data + zimmedari    --> governance, permissions, audit, disclosure

=======================================================================
 LAYER 4: WAQT  -- 10-80-10 aur Diligence
=======================================================================
 |--- 10% ---|------------------- 80% -------------------|--- 10% ---|
 Direction     Orchestrate (Description <-> Discernment)    Judge truth
 (Deleg+Desc)  baar baar                                    (Discernment)
 ========================= DILIGENCE 100% =========================

=======================================================================
 LAYER 5: SAFETY NET -- 4 galtiyan = 4 missing skills
=======================================================================
 Bina goal prompt         --> Delegation missing
 Pehla jawab = final      --> Loop missing
 Polish = accuracy        --> Discernment missing
 Privacy baad mein        --> Diligence missing
=======================================================================
 EK LINE: Tay karo. Samjhao. Check karo. Own karo.
=======================================================================
```

### Master Diagram ko parhne ka tareeqa (30 second)

1. **Layer 1** se shuru karo: pehle mode choose karo, yaani AI ko kitni freedom.
2. **Layer 2** loop chalao: Delegate -> Describe -> AI output -> Discern -> Diligent -> repeat.
3. **Layer 3** yaad rakho ke wahi loop chat se lekar Digital FTE tak scale hota hai.
4. **Layer 4** batata hai ke loop waqt mein kahan zyada zor deta hai, aur Diligence poore waqt.
5. **Layer 5** aap ka debugging tool: kuch bura ho to dhoondo kaunsa D missing tha.

---

## 10. Quick Recall Cheat Sheet

| Sawal | Jawab |
|---|---|
| AI Fluency ki 4 qualities? | Effective, Efficient, Ethical, Safe |
| 3 modes? | Automation (task chalao), Augmentation (saath socho), Agency (goal + boundaries dekar future/others ke liye chalao) |
| Delegation ke 3 parts? | Problem awareness, Platform awareness, Task delegation |
| Description ke 3 parts? | Product (what), Process (how), Performance (behavior) |
| Discernment ke 3 parts? | Product, Process, Performance |
| Diligence ke 3 parts? | Creation, Transparency, Deployment |
| Hallucination kya hai? | Confident magar ghalat/invented jawab |
| Automation bias kya hai? | Automated jawab par zaroorat se zyada bharosa |
| Redaction kya hai? | Pehchan wali details hatana, task ka pattern rakhna |
| Numbers rule? | Number compute ho, generate nahi |
| Feedback pattern? | Problem -> Why it matters -> Direction |
| Ship se pehle sawal? | "Kya main is par apna naam confidence se laga sakta/sakti hoon?" |
| 4D loop? | Delegate -> Describe -> Discern -> Be diligent -> Repeat |
| Discernment kaise engineering bani? | Evals, monitoring, sampling, release gates |
| Diligence kaise engineering bani? | Governance, permissions, audit logs, disclosure, human review |
| 10-80-10? | 10% direction, 80% AI orchestrate, 10% truth judge (Diligence poore 100% mein) |

### Practice (10-15 minute)

1. Apne kisi asli kaam ke liye 4D plan banao: *kya AI karega, kya main, kya context dunga, kaise check karunga, kya data sensitive hai?*
2. Ek aise topic par AI se baat karo jise aap achhe se jaante hain aur dekho aap kitni aasani se ghalti pakarte hain. Phir ek aise topic par jis ka aap ko kuch pata nahi, aur mehsoos karo ke **bina expertise** discernment kitni mushkil hai (isi liye deployed agents ko trust nahi, evals chahiye).
3. Ek performance description likho ("weak assumptions challenge karo, uncertainty flag karo, sirf politeness mein agree mat karo") aur dekho agli fresh chat mein wo kitni jaldi gayab ho jati hai. Yahi wajah hai ke deployed agent isay system prompt mein rakhta hai.

---
