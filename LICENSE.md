# ALWAYS US MODS METADATA LICENSE v2.0

**Last Updated:** 2026-07-12
**Official SPDX Identifier:** `LicenseRef-AlwaysUsMods-Metadata-2.0`

This license applies to the **original metadata structures, documentation formats, and organizational logic** created by **Always Us Mods**. Originally developed for XML-based game modding, these structures have been generalized for use in configuration files and code environments (including Lua and C#). They are designed to remain applicable to any project, program, or modding community.

---

## 🎯 PROTECTED CONTENT

The following components are **protected under this license** and may **not** be reused, modified, or redistributed—publicly or privately—**without clear attribution**:

* Structured metadata blocks and top-of-file headers.

* The core metadata tagging convention, including but not limited to: `@version`, `@date`, `@author`, `@group`, `@description`, `@notes`, `@xref`, and `@ref`.

* Comment-based section headers (`SECTION:`) and their associated formatting syntax.

* In-line documentation style, explanation language, and formatting.

* Cross-referencing conventions and intra-file reference logic.

* Logical file structure and organizational methodology.

These elements are **original to Always Us Mods** and are **not part of the vanilla engine schemas** provided by game developers or general modding APIs.

---

## ✅ WHAT YOU **CAN** USE

You are free to:

* Use standard programming syntax (e.g., XML, Lua, C#) and native modding structures.

* Reference vanilla game data, external APIs, engine functions, or framework hooks.

* Apply similar logic or functions to your code.

* Develop your own documentation or metadata systems.

* Learn from this structure for private use or experimentation.

This license **does not** restrict your ability to:

* Create similar projects from scratch.

* Build on public modding or programming knowledge.

* Share similar ideas in new and original formats.

Just don’t copy the *how* unless you credit the *who*.

---

## 📌 ATTRIBUTION & SPDX REQUIREMENTS

If you reuse this metadata style, organization, or documentation format, you must provide credit and correctly tag your files.

### 1. General Attribution

You must include the following statement in your project's `README`, on your project's description page, or in your master license file:

> "Based in part on structural documentation by Always Us Mods."

### 2. File-Level SPDX Implementation

To ensure automated tooling and linters can recognize the license status of your files, you must include the official SPDX identifier in the **top-of-file metadata block** of any file utilizing this standard.

Add the following line to your header block:
`SPDX-License-Identifier: LicenseRef-AlwaysUsMods-Metadata-2.0`

### 3. Handling Dual Licenses (Code vs. Metadata)

Because this license governs the *metadata tagging convention itself* and not your underlying project code, your files will likely be dual-licensed.

If your code is released under its own license (e.g., MIT, GPL-3.0), simply include **both** SPDX tags in your file header on separate lines.

**Example Implementation:**

> `@version     1.0.0`
> `SPDX-License-Identifier: MIT` *(covers your code)*  
> `SPDX-License-Identifier: LicenseRef-AlwaysUsMods-Metadata-2.0` *(covers this metadata structure)*

If you’re unsure whether your use qualifies—**ask first**. It’s easier than apologizing later.

---

## ❌ NOT PERMITTED WITHOUT PERMISSION

The following actions **require explicit written permission** from Always Us Mods:

* Reposting or distributing any file structure, documentation format, or comment style based on this system without attribution.

* Using this metadata system as the basis for another public-facing project without credit.

* Removing or stripping documentation and re-releasing with minor edits.

* Using any part of this structure for **commercial or paid content**.

---

## ⚖️ LEGAL DECLARATION

This license is a formal declaration of **authorship and intellectual property** under U.S. and international copyright law.

It does **not** claim ownership of any game engines, vanilla assets, or programming languages.

However, it **does** protect the **unique expression** of:

* Metadata formatting and tagging conventions.

* Documentation structure.

* Section organization.

* Commentary and explanation style.

All rights reserved where applicable. This license operates independently of the licensing terms of any specific game or third-party frameworks.

---

## 💬 PERSONAL USE POLICY

You may:

* Use this system as learning material.

* Copy it into private projects.

* Modify it for personal, non-distributed use.

But if you’re publishing a project and borrowing the structure, **credit it.** It’s just respectful.

---

## 📬 CONTACT

For questions, collaboration, or permission requests, reach out to:

**[Always Us Mods](mailto:contact.demonatagaming@alwaysusstudios.com)**
**[YouTube](https://www.youtube.com/@demonatagaming)**
**[NexusMods](https://www.nexusmods.com/profile/AlwaysUsMods)**

---

## 🛡️ FINAL WORD

If you found this structure useful, **credit the creator**.
If you're inspired, that’s great—**just don’t plagiarize**.

---

### ⚠️ GENERAL EULA SCOPE LIMITATION NOTICE

In accordance with the End User License Agreements (EULAs) of the respective platforms and engines this standard interfaces with, I acknowledge that developers may use or adapt content created using their software and tools.

However, I do **not** grant any engine developer, studio, or affiliated party any rights to reuse, repurpose, or adapt this structural metadata content in **any future games, platforms, or software titles** unless I have:

* Installed or used said software.

* Accepted a new EULA that grants additional rights.

* Given **explicit written permission** for reuse.

All rights are otherwise reserved under applicable copyright law.
