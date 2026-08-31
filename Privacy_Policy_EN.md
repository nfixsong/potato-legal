# Potato — Privacy Policy

NFIX ("the Company") values your personal information and complies with the Personal Information Protection Act and other applicable laws. This Privacy Policy explains how personal information is collected, used, stored, and destroyed in the "Potato" service ("the Service").

**Last updated: August 31, 2026**
**Effective date: July 11, 2026**

---

## Article 1 (Personal Information Collected)

**1. At registration (required)**
- Information via Google or Apple OAuth: email address, name or nickname, profile image URL, unique identifier

**2. During use (optional)**
- Investment profile (survey), holdings and watchlist information, cash balance

**3. Camera and Photos (Images)**
- Photos and images you select or capture when using the **Portfolio Import (photo recognition)** or **AI Debate image attachment** features (e.g., portfolio screenshots, charts). Camera/photo access occurs only when using these features and is limited to images you choose.

**4. Automatically collected**
- Device information (OS type/version, model), app version, IP address, service usage records, AI debate conversation content

**5. At payment**
- **Payment instrument details such as card numbers are not collected.** Payment happens entirely in the store's in-app purchase system (App Store / Google Play); we receive only the **subscription product, payment/refund dates, and subscription status**.
- For refund handling we also process the **transaction identifier, refund reason, and refund amount** the store sends us.

**8. Brokerage account linking (optional — only if you connect it yourself)**
- Only if you connect an account under **[Account] > Brokerage linking**, we store: **brokerage name, account number, the Open API app key and secret you issued, the access token, connection status, and last sync time**.
- **The API key, secret, and access token are stored encrypted** and are never displayed again.
- This link is **read-only for holdings and cash**. The Company **does not place orders, trade, or withdraw funds**, and does not request those permissions.
- Deletion: removed immediately when you disconnect under **[Account] > Brokerage linking**, and also by **"Reset all my data."**

**9. Support inquiries**
- Questions and conversation context you enter in the **support chatbot**. These are sent to the AI processors in Article 5 to generate an answer, and **before sending we automatically mask anything recognized as an email address, phone number, card number, national ID, bank account number, or order number.**
- ⚠ Automatic masking is not perfect. **Please do not enter sensitive personal information into support inquiries.**

**10. Referrals**
- Your referral code, the link between referrer and referee, and reward issuance history.

**11. Bot protection (human verification)**
- To prevent automated abuse of guest sign-ups, we run a **human check (CAPTCHA)** when a guest enters. In this process your **IP address and browser/device signals** are sent to the processor in Article 5 (Cloudflare).

**6. Conversation-based personalization data (optional — only with separate consent)**
- Only if you turn on **[Account] > [Data] > "Conversation-based personalization"**, we generate and store a summary of tendencies observed in your AI debates (a behavioral summary, question patterns, and internal-reference indicators).
- **Nothing is generated without your consent.** You can turn it off at any time on the same screen; generation stops from that point.
- This data is used **only to adjust how things are explained** (length, examples, ordering, pace). It is **not used to change the AIs' conclusions, factual judgments, or explanations of risk.**
- It is used only when responding to you. It is not exposed to other users and is not provided externally.
- Deletion: removed immediately via **[Account] > "Reset all my data."**

**7. Per-holding memory (when you use AI Debate)**
- From what you say during AI debates, we store the parts identified as **reasons for buying or your stance on a stock**, and use them as context for understanding your situation in later conversations.
- Extraction draws only on **your own messages** (the AIs' statements are not used as a source). Because the extraction is performed by AI, it **may not match your intent**, and a stock you do not actually hold may be recorded.
- This is a **separate item from the conversation-based personalization data in Article 1(6)** and is **not governed by that consent toggle.** It may be generated whenever you use AI Debate.
- It is used only when responding to you and is not exposed to other users. However, it is **transmitted together with your question to the AI processors listed in Article 5** in order to generate responses.
- Deletion: removed immediately via **[Account] > "Reset all my data."**

## Article 2 (Purposes of Collection and Use)

1. Member identification and management
2. Service provision: AI debate, personalized investment information, conversation history, **image-based portfolio recognition (OCR), and AI debate image analysis**
3. Provision and management of paid services
4. Customer support and inquiries
5. Service improvement (statistical analysis, anonymized processing)
6. Marketing (with separate consent)
7. Compliance with legal obligations

## Article 3 (Retention and Use Period)

1. In principle, the Company retains personal information from registration until account deletion.
   However, the **conversation-based personalization data in Article 1(6)** is **deleted immediately** when you withdraw consent or run "Reset all my data,"
   and the **per-holding memory in Article 1(7)** is **deleted immediately** when you run "Reset all my data."
2. The following are retained for legally required periods:
   - Records on contracts, payment, and supply of goods: 5 years (E-Commerce Act)
   - Records on consumer complaints or disputes: 3 years
   - Records on advertising: 6 months
   - Service access logs: 3 months (Protection of Communications Secrets Act)

## Article 4 (Provision to Third Parties)

The Company does not process personal information beyond the original purpose or provide it to third parties without the data subject's prior consent, except where: the data subject has consented in advance; or law requires it or an investigative agency requests it under law.

## Article 5 (Outsourcing of Processing)

The Company outsources personal information processing as follows to provide the Service smoothly.

| Processor | Task | Items | Country |
|---|---|---|---|
| Supabase Inc. | Database hosting, authentication | Member information | Korea (Seoul) |
| OpenAI, L.L.C. | AI responses (Gee / GPT), **support chatbot answers** | Question, anonymized profile, attached/captured images, **masked support inquiry content** | USA |
| Anthropic, PBC | AI responses (Clo / Claude) | Question, anonymized profile, images you attach or capture | USA |
| Google LLC | AI responses (Gem / Gemini), OAuth, **push notifications (Firebase)** | Question, anonymized profile, images, OAuth info, **device push token** | USA |
| Apple Inc. | OAuth, in-app purchase | OAuth info, payment and refund related info | USA |
| **Cloudflare, Inc.** | **Bot protection (human check · Turnstile)** | **IP address, browser/device signals** | USA |

**About brokerage account linking** — if you link a brokerage account, lookup requests go **directly to that brokerage using the Open API key you issued yourself**. We do not provide your personal information to the brokerage; we receive **holdings and cash balances** from it and use them to provide the Service. **We do not place orders, trade, or withdraw funds.**

- Directly identifying information such as email or real name is not transmitted. Please avoid including identifying information in attached images.

## Article 6 (Cross-Border Transfer)

1. For AI responses and authentication, the following are transferred to the USA: your questions, anonymized profile, attached/captured images, and OAuth information.
2. Transfers occur in real time over HTTPS and are retained per each processor's policy (OpenAI and Anthropic typically delete within 30 days).
3. By agreeing to this Privacy Policy at registration, you consent to the above cross-border transfer.

## Article 7 (Destruction of Personal Information)

1. The Company destroys personal information without delay once the retention period expires or the processing purpose is achieved.
2. Method of destruction:
   - Electronic files: permanently deleted by technical means that prevent recovery
   - Printouts: shredded or incinerated

## Article 8 (Rights of Users and Legal Representatives)

1. You may request access, correction, deletion, or suspension of processing of your personal information at any time.
2. How to exercise:
   - In the app **[Account] tab**, review/edit data, or permanently delete your account and data via **"Delete account."**
   - Or contact sci.nfix@gmail.com

## Article 9 (Children Under 14)

The Company does not accept registration by children under 14. If personal information of a child under 14 is found to have been collected, it is destroyed without delay.

## Article 10 (Security Measures)

- Administrative: internal management plan, regular staff training
- Technical: HTTPS/TLS encryption on all communications, database access control (Row Level Security), intrusion prevention systems
- Physical: data center access control

## Article 11 (Automatic Collection and Tracking)

1. **The Service does not collect or use advertising identifiers (IDFA / AAID).** We serve no in-app advertising and do not track you for advertising purposes.
2. For push notifications we store a **per-device push token** (Firebase Cloud Messaging). It is used only to deliver notifications and never for advertising.
3. How to opt out:
   - Push notifications: OS settings or in-app **[Account] > Notification settings**
   - Deleting your account also deletes the push token

## Article 12 (Optional Consent Items)

1. Marketing communications (optional): new features and events. Withdraw via app "Settings > Notifications."
2. Premium notifications (Premium subscribers): market briefings, watchlist alerts. Withdraw individually via "Settings > Premium notifications."
3. **Conversation-based personalization (optional)**: consent to generate and use the data in Article 1(6). **The default is "not consented."** You can turn it on or off at any time under **[Account] > [Data] > "Conversation-based personalization."** Declining does not restrict your use of AI debates or any other part of the service.

## Article 13 (Data Protection Officer)

- Officer: In Cheol Song (Representative)
- Phone: +82-10-5450-5944
- Email: sci.nfix@gmail.com

## Article 14 (Remedies for Rights Infringement)

- Personal Information Dispute Mediation Committee: 1833-6972 (Korea)
- Korea Internet & Security Agency (Privacy report center): 118
- Supreme Prosecutors' Office Cybercrime: 1301
- National Police Agency Cyber Bureau: 182

## Article 15 (Changes to This Policy)

Changes are announced in the app at least 7 days before taking effect; material changes are announced 30 days in advance with individual notice.

---

## Addendum & Business Information

- Effective date: July 11, 2026
- Last amended: August 31, 2026
- Company: NFIX
- Business Registration No.: 604-19-13861
- Address: 576, 5F, 36 Banseok-ro, Yuseong-gu, Daejeon, Republic of Korea
- Email: sci.nfix@gmail.com
