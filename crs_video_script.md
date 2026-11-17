# CRS OECD XML — Video Script (60–90 Seconds)

## Visual Style
- Dark code editor theme (syntax-highlighted XML)
- Clean callout boxes with plain-English explanations
- Sequential highlighting of XML sections
- Turkish/English bilingual labels (since your XML uses Turkish comments)

---

## Scene 1: Hook (0:00–0:10)
**Screen:** Full-screen XML file opens.  
**Text overlay:** "CRS OECD v3.0 — What is this XML?"

**Narrator:**  
"This is a CRS OECD v3.0 XML file — the global standard for automatic exchange of financial account information between tax authorities."

---

## Scene 2: The Header (0:10–0:20)
**Screen:** Highlight `<crs:MessageSpec>` block.  
**Callout:** "Message Header — Who sent it, to whom, and when."

**Narrator:**  
"The MessageSpec block contains the sending company, transmitting and receiving country (both TR — Turkey), message type, and a unique reference ID: TR2026TR-FI1234567890-0001."

---

## Scene 3: The Reporting Financial Institution (0:20–0:30)
**Screen:** Highlight `<crs:ReportingFI>`.  
**Callout:** "ReportingFI — The bank sending the report."

**Narrator:**  
"Here's the Reporting Financial Institution: Ornek Katilim ve Mevduat Bankasi A.S. in Istanbul, Turkey, with tax ID 1234567890."

---

## Scene 4: Account Reports — Three Scenarios (0:30–0:60)
**Screen:** Highlight `<crs:ReportingGroup>` containing three `<crs:AccountReport>` blocks.

**Callout 1:** "Scenario 1: Individual — Joint deposit account (Germany)."  
**Callout 2:** "Scenario 2: Organisation — Passive NFE with controlling persons (Netherlands/Turkey)."  
**Callout 3:** "Scenario 3: Electronic money product / Trust beneficiary (UK)."

**Narrator:**  
"The ReportingGroup holds three different account reports:  
First, a joint euro deposit account for Hans Mueller in Berlin.  
Second, a USD investment account for Anadolu Global Yatirim, with controlling person Sophie Van Dijk in Amsterdam.  
Third, a GBP electronic money product for Oliver Smith in London."

---

## Scene 5: Key v3.0 Fields (0:60–0:75)
**Screen:** Quick flashes of: `<crs:SelfCert>`, `<crs:DDProcedure>`, `<crs:AccountType>`, `<crs:JointAccount>`.  
**Callout:** "New in v3.0: Self-certification, due diligence, account type, joint account count."

**Narrator:**  
"Version 3.0 adds mandatory fields like self-certification status, due diligence procedure, account type, and for joint accounts — how many holders there are."

---

## Scene 6: Wrap Up (0:75–0:90)
**Screen:** Full XML file again, fading out.  
**Text overlay:** "CRS OECD XML — Structured tax data, worldwide."

**Narrator:**  
"This XML lets banks and tax authorities exchange structured, machine-readable financial data securely across borders. That's CRS OECD in under 90 seconds."

---

## Production Notes
- **Resolution:** 1080x1920 (vertical for Shorts/TikTok/Reels) or 1920x1080 (YouTube)
- **Font:** Monospace (Fira Code, JetBrains Mono, or Consolas)
- **Background music:** Low-volume corporate/tech track
- **Voiceover:** Clear, steady pace (~130 words per minute)
