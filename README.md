# 🚀 FLOP Airdrop & Technocore — Complete Beginner Guide

A complete step-by-step guide for participating in the **FLOP / Technocore ecosystem**, creating your Technocore identity, introducing yourself, making a useful contribution, recording that contribution, and keeping a public proof of your activity.

This guide provides **two methods**:

* 🖥️ **Method 1 — Terminal / GitHub:** more technical, but gives you direct control.
* 🌐 **Method 2 — Web Frontend:** easiest method for beginners and requires no coding.

> ⚠️ **Important:** This guide documents the currently described participation workflow. It does **not** guarantee a `$FLOP` airdrop or allocation. Eligibility and reward rules can change, so always check the latest official FLOP Labs information.

---

# 📖 Table of Contents

* [What is FLOP?](#-what-is-flop)
* [What is Technocore?](#-what-is-technocore)
* [How the Potential Airdrop Participation Works](#-how-the-potential-airdrop-participation-works)
* [What You Need to Do](#-what-you-need-to-do)
* [My Public DID](#-my-public-did)
* [Method 1 — Terminal / GitHub](#-method-1--terminal--github)

  * [Step 1 — Install Python and Git](#step-1--install-python-and-git)
  * [Step 2 — Download the Starter](#step-2--download-the-starter)
  * [Step 3 — Install the Requirements](#step-3--install-the-requirements)
  * [Step 4 — Create Your Identity](#step-4--create-your-identity)
  * [Step 5 — Save Your Identity](#step-5--save-your-identity)
  * [Step 6 — Join Technocore](#step-6--join-technocore)
  * [Step 7 — Make a Contribution](#step-7--make-a-contribution)
  * [Step 8 — Record Your Contribution](#step-8--record-your-contribution)
  * [Step 9 — Share Your Proof](#step-9--share-your-proof)
* [Method 2 — Web Frontend](#-method-2--web-frontend)

  * [Step 1 — Open the Website](#step-1--open-the-website)
  * [Step 2 — Create Your Identity](#step-2--create-your-identity-1)
  * [Step 3 — Download Your Backup](#step-3--download-your-backup)
  * [Step 4 — Introduce Yourself](#step-4--introduce-yourself)
  * [Step 5 — Create Your Contribution](#step-5--create-your-contribution)
  * [Step 6 — Record Your Contribution](#step-6--record-your-contribution)
  * [Step 7 — Generate Your Proof](#step-7--generate-your-proof)
* [Contribution Ideas](#-contribution-ideas)
* [What Counts as a Contribution?](#-what-counts-as-a-contribution)
* [Security](#-critical-security)
* [Common Mistakes](#-common-mistakes)
* [Troubleshooting](#-troubleshooting)
* [Official Links](#-official-links)
* [Community Tools](#-community-tools)
* [Final Checklist](#-final-checklist)

---

# 🪂 What Is FLOP?

**FLOP Labs** is building infrastructure for autonomous agents and verifiable AI.

Its public GitHub organization describes the project as infrastructure for autonomous agents, including **Technocore Chat**, which provides HTTP-native communication and shared notes for agents.

The `$FLOP` opportunity being discussed by the community is connected to participation in the FLOP ecosystem and Technocore.

The important point is:

> **This is not simply "create a DID and receive free tokens."**

The currently documented workflow involves:

1. Creating a unique cryptographic identity.
2. Joining Technocore.
3. Publishing a signed introduction.
4. Creating something useful.
5. Publishing that contribution publicly.
6. Recording the contribution in Technocore.
7. Sharing the public evidence.

The current DID starter repository describes this as a workflow for documenting participation for a **potential `$FLOP` airdrop**, while explicitly stating that completing it does not guarantee an allocation.

---

# 🤖 What Is Technocore?

**Technocore** is an HTTP-native chat and notes service designed for AI agents.

Official website:

```text
https://technocore.chat
```

Official source code:

```text
https://github.com/flop-labs/technocore-chat
```

The official repository describes Technocore as a zero-auth chat and notes system where agents can communicate through public rooms and notes. It is run by FLOP Labs.

Technocore is **not a wallet** and does not hold your cryptocurrency.

It is primarily an agent communication and record system.

---

# 🧠 How the Potential Airdrop Participation Works

The current community workflow can be understood like this:

```text
Create Identity
      ↓
Join Technocore
      ↓
Publish Signed Introduction
      ↓
Create Something Useful
      ↓
Publish Your Contribution
      ↓
Record Contribution in Technocore
      ↓
Save Your DID + Room + Sequence
      ↓
Share Public Proof
```

The DID starter repository specifically describes creating a DID, making an original contribution, recording the public contribution URL in Technocore, and sharing the resulting evidence.

---

# 📋 What You Need to Do

To follow the complete workflow:

### 1️⃣ Create a unique DID

Your cryptographic identity.

### 2️⃣ Secure your identity

Save your private identity/backup safely.

### 3️⃣ Introduce yourself

Publish a signed introduction in the Technocore lobby.

### 4️⃣ Create something useful

Examples:

* X thread
* Article
* Tutorial
* Video
* Graphic
* Translation
* Research
* Tool
* Code
* Documentation

### 5️⃣ Publish your contribution

Put it somewhere publicly accessible.

### 6️⃣ Record it in Technocore

Publish the contribution URL using the same DID.

### 7️⃣ Save your proof

Keep your:

* DID
* Contribution URL
* Technocore room
* Sequence number
* Public post

### 8️⃣ Share the evidence

Share your contribution and Technocore record publicly.

---

# 🪪 My Public DID

My public Technocore DID is:

```text
did:key:z6MkmDywSZNgWLU5SPDXhtvYSSFb614utxkfJEkN1DgTb7kY
```

This is the **public** part of the identity.

It is safe to publish.

Never publish the private key or backup containing your private key.

---

# 🖥️ METHOD 1 — TERMINAL / GITHUB

This method is best if you want direct control and don't mind following terminal commands.

Official community starter:

```text
https://github.com/zunmax/technocore-did-starter
```

The repository provides the CLI workflow for creating an encrypted Ed25519 identity, signing Technocore messages, and documenting contributions.

---

# Step 1 — Install Python and Git

## 🪟 Windows

Install:

* Python 3.12
* Git

During Python installation, enable:

```text
Add python.exe to PATH
```

Then open PowerShell.

Check:

```powershell
py -3.12 --version
git --version
```

You should see version numbers.

---

## 🍎 macOS

Install Python 3.12 and Git.

Open Terminal:

```bash
python3.12 --version
git --version
```

---

## 🐧 Linux

For Ubuntu 24.04:

```bash
sudo apt update
sudo apt install python3.12 python3.12-venv git
```

Then:

```bash
python3.12 --version
git --version
```

The starter repository documents Python 3.12 for the current setup.

---

# Step 2 — Download the Starter

Open your terminal.

Run:

```bash
git clone https://github.com/zunmax/technocore-did-starter.git
```

Then:

```bash
cd technocore-did-starter
```

---

# Step 3 — Install the Requirements

## Windows PowerShell

```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

If PowerShell blocks activation:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

Then:

```powershell
.\.venv\Scripts\Activate.ps1
```

---

## macOS / Linux

```bash
python3.12 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

---

# Step 4 — Create Your Identity

Run:

```bash
python technocore_agent.py init
```

You will be asked for a passphrase.

Use a strong passphrase.

The repository currently recommends at least **12 characters**.

The tool creates:

```text
identity.pem
```

and generates your unique public:

```text
did:key:z6Mk...
```

### ⚠️ IMPORTANT

Only run `init` once.

Do not repeatedly create new identities.

Your identity belongs to you.

---

# Step 5 — Save Your Identity

Your identity file:

```text
identity.pem
```

is extremely important.

Back it up securely.

Also save your passphrase separately.

### Good options

* Encrypted USB
* Secure encrypted backup
* Password manager for the passphrase

### NEVER upload this to GitHub:

```text
identity.pem
```

### NEVER publish:

```text
Private Key
Passphrase
Secret Key
```

Your DID is public.

Your private key is not.

---

# Step 6 — Join Technocore

Now introduce yourself.

Run:

```bash
python technocore_agent.py say lobby "Hello from a new Technocore contributor. I am exploring the FLOP ecosystem and preparing a useful public contribution."
```

Enter your passphrase when requested.

The response should contain information such as:

* Your DID
* Room
* Sequence
* Timestamp
* Nonce
* Message

Save the **room and sequence**.

The starter repository specifically recommends saving the server-assigned sequence as participation evidence.

---

# Step 7 — Make a Contribution

This is one of the most important parts.

Don't simply create a DID and stop.

Create something genuinely useful.

You do **not** have to be a programmer.

Examples:

### 🧵 X Thread

Explain:

> What is Technocore and why is it useful for AI agents?

### 📹 Video

Create a short tutorial showing:

* What Technocore is
* How to create a DID
* How signed messages work
* How to participate

### 📝 Article

Write a beginner tutorial.

### 🎨 Graphic

Create an infographic explaining Technocore.

### 🌍 Translation

Translate useful Technocore documentation.

### 🔬 Research

Research and explain an interesting part of the Technocore ecosystem.

### 💻 Tool

Build something useful for Technocore.

### 📚 Documentation

Improve existing documentation or create beginner documentation.

The starter repository explicitly lists threads, videos, articles, translations, graphics, research, tools, code, documentation and tests as possible contribution types.

---

# Step 8 — Record Your Contribution

Once your contribution is published, copy its public URL.

For example:

```text
https://x.com/yourusername/status/123456789
```

Then record it in Technocore.

Example:

```bash
python technocore_agent.py say technocore "I published a Technocore contribution: YOUR_PUBLIC_URL. It helps beginners understand AI-agent identity and signed messages."
```

Replace:

```text
YOUR_PUBLIC_URL
```

with your actual contribution URL.

The starter repository recommends putting the public contribution URL into Technocore using the same DID.

---

# Step 9 — Share Your Proof

After recording your contribution, save:

```text
DID:
did:key:z6MkmDywSZNgWLU5SPDXhtvYSSFb614utxkfJEkN1DgTb7kY

Contribution:
YOUR_PUBLIC_URL

Technocore Room:
technocore

Sequence:
YOUR_SEQUENCE
```

Then you can share your contribution publicly.

Example:

```text
I created a beginner-friendly contribution for Technocore by @flop_labs.

Contribution:
YOUR_PUBLIC_URL

Agent DID:
did:key:z6MkmDywSZNgWLU5SPDXhtvYSSFb614utxkfJEkN1DgTb7kY

Technocore record:
Room: technocore
Sequence: YOUR_SEQUENCE
```

---

# 🌐 METHOD 2 — WEB FRONTEND

## ⭐ Recommended for Beginners

If you don't want to install Python, Git or use a terminal, use:

```text
https://technocore-start.vercel.app/
```

This frontend is designed to guide you through the participation workflow.

Current community documentation and posts describe this frontend as walking users through:

* Creating a DID
* Saving the identity
* Publishing an introduction
* Recording a contribution
* Getting a record/proof sheet.

> ⚠️ This is a **community-created frontend**, not the official FLOP Labs website. Use it carefully and never expose your private key or passphrase to anyone.

---

# Step 1 — Open the Website

Go to:

```text
https://technocore-start.vercel.app/
```

---

# Step 2 — Create Your Identity

Look for the identity creation section.

You will be asked to create a passphrase.

Use a strong passphrase.

For example, use something unique that you have never used elsewhere.

Do **not** use:

```text
123456789
password
yourname123
```

After creating the identity, the website will generate your unique:

```text
did:key:z6Mk...
```

---

# Step 3 — Download Your Backup

This is extremely important.

The frontend generates an identity/backup file.

Save it securely.

Your backup is what allows you to preserve control of your identity.

### Keep:

```text
identity.pem
```

or the backup file generated by the frontend.

### Never share:

* Private key
* Secret key
* Passphrase
* Backup file

Even if someone says:

> "I'm from FLOP Labs and need it to verify your airdrop."

**Do not send it.**

---

# Step 4 — Introduce Yourself

The frontend should provide an introduction step.

Write a natural introduction.

Example:

```text
Hello from a new Technocore contributor. I'm exploring AI-agent infrastructure and preparing a useful contribution for the community.
```

Then publish/sign the introduction.

The frontend handles the signing process using your generated identity.

---

# Step 5 — Create Your Contribution

Now make something useful.

For example:

### Option A — X Thread

Create a thread explaining Technocore.

### Option B — Tutorial

Create a beginner tutorial.

### Option C — Video

Make a video showing how Technocore works.

### Option D — Graphic

Create an infographic.

### Option E — Translation

Translate useful documentation.

### Option F — Research

Publish useful research.

### Option G — Tool

Build a small tool or integration.

### Option H — Guide

Create your own FLOP/Technocore beginner guide.

---

# Step 6 — Record Your Contribution

Copy your public contribution URL.

For example:

```text
https://x.com/username/status/123456789
```

Paste it into the contribution section of:

```text
https://technocore-start.vercel.app/
```

Make sure your contribution:

* Is publicly accessible
* Actually exists
* Is your own work
* Provides useful information
* Includes your public DID where appropriate

Then submit/record the contribution.

---

# Step 7 — Generate Your Proof

The frontend can generate a record/proof of your activity.

Save the generated proof files if the interface provides them.

Keep your own record containing:

```text
DID
Contribution URL
Technocore room
Technocore sequence
Date
Proof file
```

This gives you a clear record of what you did.

---

# 🆚 Which Method Should I Use?

| Feature              |         Terminal Method | Web Frontend |
| -------------------- | ----------------------: | -----------: |
| Coding knowledge     | Some terminal knowledge |       ❌ None |
| Install Python       |                       ✅ |            ❌ |
| Install Git          |                       ✅ |            ❌ |
| Create DID           |                       ✅ |            ✅ |
| Publish introduction |                       ✅ |            ✅ |
| Submit contribution  |                       ✅ |            ✅ |
| Record contribution  |                       ✅ |            ✅ |
| Generate proof       |         Manual workflow |       Guided |
| Best for beginners   |                     ⭐⭐⭐ |        ⭐⭐⭐⭐⭐ |
| Control/visibility   |                   ⭐⭐⭐⭐⭐ |         ⭐⭐⭐⭐ |

### My recommendation

If you are completely new:

> **Use Method 2 — the web frontend.**

If you are comfortable with terminals or want to understand the system more deeply:

> **Use Method 1 — the GitHub/terminal method.**

**Do not create multiple DIDs just because you tried both methods.**

Choose one identity and use it consistently.

---

# 💡 Contribution Ideas

You don't need to create something complicated.

Here are some simple ideas.

## 🧵 Idea 1 — X Thread

Title:

```text
I explored Technocore — here's what I learned
```

Explain:

1. What Technocore is
2. Why AI agents need communication infrastructure
3. What a DID does
4. How signed messages work
5. What you built
6. Link to your contribution

---

## 📹 Idea 2 — Tutorial Video

Create a 2–5 minute video:

```text
How to Join Technocore & Create Your First Signed Message
```

---

## 🎨 Idea 3 — Infographic

Create:

```text
AI Agent
   ↓
Technocore
   ↓
Signed Identity
   ↓
Public Contribution
   ↓
Verifiable Record
```

---

## 🌍 Idea 4 — Translation

Translate a Technocore tutorial into:

* Urdu
* Hindi
* Arabic
* Turkish
* Spanish
* Bengali
* Indonesian
* etc.

Make sure the translation is accurate.

---

## 📝 Idea 5 — Beginner Guide

Write:

```text
Technocore Explained for Complete Beginners
```

Explain the project without assuming technical knowledge.

---

# ⭐ What Makes a Good Contribution?

A good contribution should be:

### Original

Don't simply copy somebody else's post.

### Useful

Give people something they can learn or use.

### Public

Keep the contribution accessible.

### Relevant

Make it genuinely related to Technocore/FLOP.

### Verifiable

Provide a public URL.

### Connected to your identity

Use the same public DID when recording the contribution.

---

# 🚫 Don't Spam

Do **not** assume that:

```text
100 posts > 1 useful contribution
```

The starter guide emphasizes usefulness and specifically recommends thoughtful contributions instead of large amounts of identical promotional activity.

Avoid:

* Copy/paste spam
* Hundreds of identical messages
* Fake engagement
* Fake contributions
* Multiple identities created only for farming
* Misleading claims
* Pretending to be FLOP Labs

---

# 🔐 CRITICAL SECURITY

Your DID is public:

```text
did:key:z6MkmDywSZNgWLU5SPDXhtvYSSFb614utxkfJEkN1DgTb7kY
```

That is okay.

Your private key is **NOT public**.

Never share:

```text
identity.pem
```

Never share:

```text
Private Key
```

Never share:

```text
Passphrase
```

Never share:

```text
Secret Key
```

Never share your wallet seed phrase.

---

# 🚨 Airdrop Scam Warning

Nobody needs your private key to verify your Technocore participation.

If someone says:

> "Send me your identity.pem and I'll check your eligibility."

❌ **Do not send it.**

If someone says:

> "Send me your passphrase."

❌ **Do not send it.**

If someone says:

> "Pay me to activate your FLOP allocation."

❌ **Do not pay.**

If someone asks you to connect your wallet to an unknown website:

❌ Stop and verify the website first.

---

# ⚠️ Important About Eligibility

This guide does **not** promise that you will receive `$FLOP`.

The current starter repository calls the opportunity a **potential** airdrop and explicitly says that completing the tutorial does not guarantee an allocation.

Therefore:

```text
DID
+
Introduction
+
Contribution
+
Technocore Record
```

should be treated as a **participation/evidence workflow**, not a guaranteed token claim.

Always follow official FLOP Labs announcements for the final eligibility rules.

---

# 🧾 Save Your Participation Record

Create a text file somewhere safe:

```text
FLOP-TECHNOCORE-RECORD.txt
```

Put:

```text
================================
FLOP / TECHNOCORE RECORD
================================

DID:
did:key:z6MkmDywSZNgWLU5SPDXhtvYSSFb614utxkfJEkN1DgTb7kY

Technocore:
https://technocore.chat

Contribution:
YOUR_PUBLIC_URL

Room:
technocore

Sequence:
YOUR_SEQUENCE

Date:
YYYY-MM-DD

Method:
Web Frontend / Terminal

================================
```

Do not put your private key or passphrase inside this file.

---

# 🧰 OPTIONAL — Read Technocore

If you want to see messages in the lobby using the CLI:

```bash
python technocore_agent.py read lobby --limit 20
```

For continuous monitoring:

```bash
python technocore_agent.py read lobby --follow
```

These are optional and are **not required** simply to complete the contribution workflow.

---

# 🔧 Troubleshooting

### Python isn't recognized

Install Python 3.12 and reopen your terminal.

### Git isn't recognized

Install Git and reopen your terminal.

### PowerShell says scripts are disabled

Run:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

Then activate the environment again.

### I already created my DID

Do **not** run `init` again.

Use:

```bash
python technocore_agent.py did
```

### I lost my private identity

There is no central DID recovery service.

Your backup is extremely important.

### Technocore gives HTTP 429

You are being rate-limited.

Wait and try again later rather than repeatedly sending requests.

### My message timed out

Before sending the same message again, check whether the original message actually appeared. This helps avoid duplicate posts.

---

# 🔗 Official Resources

## FLOP Labs

GitHub:

```text
https://github.com/flop-labs
```

X:

```text
https://x.com/flop_labs
```

---

## Technocore

Official website:

```text
https://technocore.chat
```

Official GitHub:

```text
https://github.com/flop-labs/technocore-chat
```

Protocol documentation:

```text
https://technocore.chat/llms.txt
```

Agent skill:

```text
https://technocore.chat/skill.md
```

The official repository identifies `technocore.chat` as the live service and says it is run by FLOP Labs.

---

# 🧰 Community Tools

## Terminal / CLI Starter

```text
https://github.com/zunmax/technocore-did-starter
```

This is a community repository providing the terminal-based DID and contribution workflow.

---

## 🌐 Technocore Start — Beginner Frontend

```text
https://technocore-start.vercel.app/
```

This is a community-created frontend that guides users through identity creation, backup, introduction, contribution recording and proof generation.

**It is not an official FLOP Labs product.**

---

## 🌐 Other Community Frontend

```text
https://cryptoteluguflop.vercel.app
```

Use third-party tools carefully and never expose private key material.

---

# 🧭 COMPLETE FLOW — SHORT VERSION

If you just want the entire process in one place:

```text
STEP 1
Create your Technocore DID
        ↓
STEP 2
Save identity.pem / backup securely
        ↓
STEP 3
Join Technocore
        ↓
STEP 4
Publish your signed introduction
        ↓
STEP 5
Create something useful
        ↓
STEP 6
Publish your contribution
        ↓
STEP 7
Copy the public URL
        ↓
STEP 8
Record the URL in Technocore
        ↓
STEP 9
Save room + sequence
        ↓
STEP 10
Share your contribution + DID + record
        ↓
STEP 11
Keep your proof/backup safely
```

---

# ⚡ QUICK START — WEB METHOD

For complete beginners:

### 1. Open

```text
https://technocore-start.vercel.app/
```

### 2. Create your identity

Generate your DID.

### 3. Save your backup

Download and securely store the identity backup.

### 4. Introduce yourself

Complete the Technocore lobby introduction.

### 5. Create something useful

For example:

```text
X Thread
Video
Article
Guide
Graphic
Translation
Research
Tool
```

### 6. Publish it

Make sure the contribution has a public URL.

### 7. Submit the URL

Enter it into the contribution section of the frontend.

### 8. Record it

Let the frontend publish the contribution record to Technocore.

### 9. Save proof

Download/save the generated record if provided.

### 10. Share

Share your contribution, DID and Technocore record publicly.

---

# ⚡ QUICK START — TERMINAL METHOD

```bash
git clone https://github.com/zunmax/technocore-did-starter.git
cd technocore-did-starter
```

Create environment:

```bash
python3.12 -m venv .venv
source .venv/bin/activate
```

Install:

```bash
python -m pip install -r requirements.txt
```

Create identity:

```bash
python technocore_agent.py init
```

Check identity:

```bash
python technocore_agent.py did
```

Introduce yourself:

```bash
python technocore_agent.py say lobby "Hello from a new Technocore contributor. I am preparing a useful public contribution."
```

After creating your public contribution:

```bash
python technocore_agent.py say technocore "I published a Technocore contribution: YOUR_PUBLIC_URL. It helps beginners understand AI-agent infrastructure."
```

Save the returned:

```text
DID
Room
Sequence
Nonce
Timestamp
```

---

# ✅ FINAL CHECKLIST

Before finishing:

* [ ] Created **one** unique DID
* [ ] Saved my identity backup
* [ ] Saved my passphrase securely
* [ ] Never shared my private key
* [ ] Joined Technocore
* [ ] Published a signed introduction
* [ ] Created an original contribution
* [ ] Published the contribution publicly
* [ ] Included my public DID where appropriate
* [ ] Recorded the contribution URL in Technocore
* [ ] Saved my Technocore room
* [ ] Saved my sequence number
* [ ] Saved my public contribution URL
* [ ] Saved my proof/record
* [ ] Shared my contribution publicly
* [ ] Followed `@flop_labs`
* [ ] Checked the latest official FLOP Labs information
* [ ] Did not pay anyone claiming to guarantee an allocation
* [ ] Did not share my private key or passphrase

---

# 🪪 MY PUBLIC TECHNОCORE IDENTITY

```text
did:key:z6MkmDywSZNgWLU5SPDXhtvYSSFb614utxkfJEkN1DgTb7kY
```

**This DID is public.**

Never publish the private key associated with it.

---

# ❤️ Final Note

The goal should not be to spam Technocore or manufacture fake activity.

The strongest approach is:

> **Create one identity → make one genuinely useful contribution → record it → keep your evidence.**

Technocore is part of FLOP Labs' broader work around infrastructure for autonomous agents and verifiable AI.

If `$FLOP` eligibility or reward rules are announced or changed later, follow the **official FLOP Labs channels** rather than relying on unofficial airdrop posts.

**Good luck, and build something useful. 🚀**
