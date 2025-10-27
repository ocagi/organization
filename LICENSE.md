# About Licensing

**Status:** Under Discussion

We're deciding which license is most appropriate for the OC-AGI organization documents. This document outlines the options and helps clarify what we're trying to achieve.

## What We Want to Achieve

For our founding documents (manifesto, privacy guide, README), we want:
- ✅ Anyone can read and share them freely
- ✅ Anyone can adapt them for their own use (with attribution)
- ✅ Derivatives should remain open (copyleft principle)
- ✅ Clear that this is open, collective work
- ❓ Should commercial use be allowed?
- ❓ What about future code/software projects?

## License Options

### Creative Commons (for Documents/Content)

**Best for:** Documents, manifestos, educational content, writings

**CC-BY-SA 4.0** (Attribution-ShareAlike)
- ✅ Anyone can share and adapt
- ✅ Must give credit
- ✅ Derivatives must use same license (keeps it open)
- ✅ Allows commercial use
- 🎯 **Most similar to software copyleft licenses**
- 📌 Used by: Wikipedia, many open educational resources

**CC-BY 4.0** (Attribution only)
- ✅ Anyone can share and adapt
- ✅ Must give credit  
- ⚠️ Derivatives can be closed/proprietary
- ✅ Allows commercial use

**CC-BY-NC-SA 4.0** (Non-Commercial + ShareAlike)
- ✅ Same as CC-BY-SA but...
- ❌ No commercial use allowed
- ⚠️ Can limit spreading of ideas

### Software Licenses (for Code/Software)

**Best for:** Actual code, software projects, technical implementations

These are what you mentioned: Apache 2.0, MIT, EPL 2.0

**MIT License**
- ✅ Very permissive
- ✅ Simple and well-understood
- ⚠️ Allows proprietary derivatives
- 📌 Used by: React, Node.js, many JS libraries

**Apache License 2.0**
- ✅ Permissive like MIT
- ✅ Includes patent grants (important for AI/ML)
- ✅ More legally robust
- ⚠️ Allows proprietary derivatives
- 📌 Used by: Android, Kubernetes, TensorFlow

**Eclipse Public License 2.0**
- ✅ Weak copyleft (only modifications must be open)
- ✅ Includes patent provisions
- ✅ Good for commercial/corporate participation
- 📌 Used by: Eclipse IDE, various enterprise projects

**GNU GPL v3** (not mentioned, but worth considering)
- ✅ Strong copyleft (all derivatives must be open)
- ✅ Prevents proprietary forks
- ✅ Includes patent grants
- ⚠️ Can discourage some corporate contributors
- 📌 Used by: Linux kernel, many GNU projects

**GNU AGPL v3** (strongest copyleft)
- ✅ Like GPL but closes "SaaS loophole"
- ✅ If you use it as a web service, you must share code
- ✅ Prevents proprietary cloud services built on open code
- ⚠️ More restrictive, limits some use cases
- 📌 Used by: Some open-source AI projects wanting to prevent corporate exploitation

## Key Distinction

**Documents vs. Code:**
- Use **Creative Commons** for documents, writings, educational content
- Use **Software Licenses** for actual code and technical implementations

## Recommendation for OC-AGI

### For Current Documents (Manifesto, Privacy Guide, README)
**Suggested: CC-BY-SA 4.0**

Why?
- Keeps documents open and freely shareable
- Requires derivatives to remain open (copyleft)
- Allows anyone to adapt for their context
- Widely understood and respected
- Philosophical alignment with "collective" values

### For Future Software/Code Projects
**Suggested: Apache 2.0 or AGPL v3** (depending on goals)

**Choose Apache 2.0 if:**
- You want maximum participation and adoption
- You're okay with companies building proprietary tools on top
- You want to be pragmatic about corporate involvement

**Choose AGPL v3 if:**
- You want to prevent companies from taking code and closing it
- You want to ensure derivative works remain open
- You prioritize collective ownership over rapid adoption

## What About Mixing Licenses?

You can (and probably should) use different licenses for different parts:
- **Documents:** CC-BY-SA 4.0
- **Code repositories:** Apache 2.0 or AGPL v3 (decided per project)
- **Datasets:** CC-BY-SA 4.0 or specific data licenses

This is common in open-source organizations.

## Questions to Decide

1. Should people be able to use our manifesto commercially (e.g., print it in a book they sell)?
   - If yes: CC-BY-SA 4.0
   - If no: CC-BY-NC-SA 4.0

2. For future code, do we want to prevent proprietary forks?
   - If yes: Consider GPL/AGPL
   - If no: Apache 2.0 or MIT

3. Is patent protection important? (probably yes for AGI work)
   - If yes: Apache 2.0 or GPL/AGPL (include patent clauses)

## Let's Discuss

This is a collective decision. Share your thoughts:
- Open a [Discussion](../../discussions) about licensing
- What values should our license reflect?
- What uses should we encourage or prevent?

---

<!-- AI: CC2:Claude Sonnet 4.5 (Cursor-MCP) -->

