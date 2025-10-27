# Setting Up Community Discussion Spaces

This document provides step-by-step instructions for setting up GitHub Discussions and a Discord server for the OC-AGI community.

---

## Part 1: GitHub Discussions

### Why GitHub Discussions?

GitHub Discussions provides:
- **Transparency**: All conversations are public and archived
- **Integration**: Native integration with your repository
- **Searchability**: Easy to search and reference past discussions
- **Threading**: Organized conversation threads
- **Categories**: Structured topics for different discussion types

### Enabling GitHub Discussions

#### Step 1: Enable Discussions Feature

1. Go to your repository on GitHub: `https://github.com/ocagi/organization`
2. Click on **Settings** (top navigation bar)
3. Scroll down to the **Features** section
4. Check the box for **Discussions**
5. Click **Set up discussions**

#### Step 2: Configure Discussion Categories

GitHub will create default categories. You should customize them:

**Recommended Categories for OC-AGI:**

1. **📢 Announcements** (Announcement type)
   - For official updates and news
   - Set maintainers as the only ones who can create posts

2. **💡 Ideas & Proposals**
   - For new ideas and proposals
   - Anyone can post
   - Enable "Mark as answer" for accepted proposals

3. **🗳️ Governance**
   - For governance discussions and decision-making
   - Discussion format
   - Enable "Mark as answer"

4. **🔬 Technical**
   - For technical discussions about AGI development
   - Q&A format recommended
   - Enable "Mark as answer"

5. **❓ Q&A**
   - General questions about the project
   - Q&A format
   - Enable "Mark as answer"

6. **🌍 General**
   - Open-ended conversations
   - Discussion format

7. **🤝 Introductions**
   - For new members to introduce themselves
   - Discussion format

#### Step 3: Customize Category Settings

For each category:
1. Go to **Discussions** tab
2. Click the ⚙️ gear icon next to category name
3. Configure:
   - **Name**: Clear, descriptive name
   - **Description**: What belongs in this category
   - **Format**: Discussion, Q&A, or Announcement
   - **Emoji**: Visual identifier

#### Step 4: Create a Welcome/Pinned Post

1. Create a new discussion in **General** or **Announcements**
2. Title: "Welcome to OC-AGI Discussions"
3. Content should include:
   - Overview of what Discussions are for
   - Link to Code of Conduct
   - Guidelines for participation
   - How to get started
4. Pin the post (three dots menu → Pin discussion)

#### Step 5: Update README

Add links to Discussions in your README.md:
```markdown
**Questions?** Open a [Discussion](https://github.com/ocagi/organization/discussions)
```

### Best Practices for GitHub Discussions

**Moderation:**
- Respond to new discussions promptly
- Move off-topic discussions to appropriate categories
- Convert issues to discussions when appropriate
- Lock/hide discussions that violate Code of Conduct

**Engagement:**
- Mark helpful answers
- Thank contributors
- Summarize long discussions
- Link related discussions together

**Organization:**
- Use labels for cross-cutting themes
- Archive or close resolved discussions
- Regularly review and organize categories

---

## Part 2: Discord Server

### Why Discord?

Discord provides:
- **Real-time chat**: Immediate, informal conversations
- **Voice channels**: For meetings and discussions
- **Community building**: Social interaction and relationship building
- **Notifications**: Real-time updates
- **Bots**: Automation and integration possibilities

### Creating a Discord Server

#### Step 1: Create the Server

1. Open Discord (desktop app or web)
2. Click the **+** button in the left sidebar
3. Select **Create My Own**
4. Choose **For a club or community**
5. Name it: **Open Collective AGI** (or **OC-AGI Community**)
6. Upload server icon (use OC-AGI logo if available)

#### Step 2: Set Up Basic Channels

**Recommended Channel Structure:**

**📢 INFORMATION** (Category)
- `#welcome` - Welcome message and rules
- `#announcements` - Official announcements (read-only)
- `#guidelines` - Code of conduct and community guidelines
- `#resources` - Links to important resources

**💬 GENERAL** (Category)
- `#general` - General discussion
- `#introductions` - New member introductions
- `#random` - Off-topic casual chat

**🔬 PROJECT** (Category)
- `#manifesto-discussion` - Discuss the manifesto
- `#governance` - Governance discussions
- `#technical` - Technical discussions
- `#ideas` - Share ideas and proposals

**🤝 COMMUNITY** (Category)
- `#questions` - Ask questions
- `#help` - Community support
- `#feedback` - Feedback about the project

**🔧 META** (Category)
- `#server-feedback` - Feedback about Discord server
- `#bot-commands` - For bot interactions

**Voice Channels:**
- `General Voice` - Open voice chat
- `Meeting Room` - For organized meetings
- `Breakout Room` - Additional meeting space

#### Step 3: Configure Server Settings

1. **Server Settings → Overview**
   - Set server name and icon
   - Add server description
   - Set default notification settings

2. **Server Settings → Roles**
   Create roles:
   - `@Admin` - Full permissions
   - `@Moderator` - Moderation permissions
   - `@Core Team` - For core contributors
   - `@Member` - Verified members
   - `@New` - New members (limited permissions)

3. **Server Settings → Moderation**
   - Set verification level: Medium or High
   - Enable explicit content filter
   - Set up automod rules (if available)

4. **Channel Permissions**
   - Make `#announcements` read-only (except for admins)
   - Restrict posting in `#welcome` and `#guidelines`
   - Consider slower mode for busy channels

#### Step 4: Create Welcome Message

In `#welcome` channel, pin a message:

```
Welcome to the Open Collective AGI community! 👋

We're building transparent, inclusive, open-source AGI for the benefit of all humanity.

**Getting Started:**
1. Read our Code of Conduct in #guidelines
2. Introduce yourself in #introductions
3. Check out #announcements for updates
4. Read our manifesto: [link]

**Important Links:**
📖 GitHub: https://github.com/ocagi/organization
💬 Discussions: https://github.com/ocagi/organization/discussions
🌐 Website: [when available]

**Need Help?**
Ask in #questions or reach out to @Moderator

Let's build the future of AGI together! 🌍
```

#### Step 5: Set Up Moderation Tools

**MEE6 Bot (Recommended):**
1. Go to https://mee6.xyz
2. Add bot to your server
3. Set up:
   - Welcome messages
   - Auto-moderation
   - Leveling system (optional)
   - Custom commands

**Carl-bot (Alternative):**
- Good for reaction roles
- Advanced moderation features

**Discord Native Features:**
- AutoMod (if server is eligible)
- Timeout functionality
- Audit logs

#### Step 6: Create Server Invite

1. Right-click your server name
2. Select **Invite People**
3. Click **Edit invite link**
4. Settings:
   - Expire after: Never
   - Max number of uses: No limit
5. Copy invite link
6. Add to README and GitHub Discussions

### Best Practices for Discord

**Moderation:**
- Have clear rules in `#guidelines`
- Enforce Code of Conduct consistently
- Use timeout before bans
- Keep audit log for decisions
- Have multiple moderators across timezones

**Engagement:**
- Welcome new members
- Pin important messages
- Use threads for long discussions
- Regular voice meetings or AMAs
- Celebrate milestones and contributions

**Organization:**
- Review channels regularly
- Archive inactive channels
- Create temporary channels for events
- Use forum channels for persistent topics (if eligible)

**Safety:**
- Require email verification
- Set verification level appropriately
- Enable explicit content filter
- Watch for spam/scams
- Have reporting process

---

## Part 3: Integration Strategy

### Coordinating Between Platforms

**GitHub (Primary for formal work):**
- Long-form proposals
- Technical documentation
- Code and pull requests
- Formal decision-making
- Permanent record keeping

**GitHub Discussions (Public async):**
- Policy discussions
- Governance decisions
- Q&A that should be searchable
- Proposals requiring community input

**Discord (Informal real-time):**
- Quick questions
- Real-time collaboration
- Community building
- Voice discussions
- Social interaction

### Cross-Platform Guidelines

**Moving Discussions:**
- Start informal ideas on Discord
- Move serious proposals to GitHub Discussions
- Summarize Discord conversations in GitHub when needed

**Announcements:**
- Post major announcements in both places
- Link between platforms
- Maintain consistency

**Moderation:**
- Same Code of Conduct applies everywhere
- Coordinate moderation team across platforms
- Share reports of violations

### Suggested Workflow

1. **Casual idea** → Discord `#ideas`
2. **Refined proposal** → GitHub Discussion
3. **Approved proposal** → GitHub Issue/PR
4. **Implementation updates** → GitHub + Discord announcements
5. **Questions** → Discord for quick answers, GitHub Discussions for searchable Q&A

---

## Part 4: Launch Checklist

### Before Launch

- [ ] GitHub Discussions enabled and configured
- [ ] Discord server created and channels set up
- [ ] Welcome messages created
- [ ] Code of Conduct posted in both places
- [ ] Moderation team identified
- [ ] Invite links created
- [ ] README updated with links
- [ ] Initial announcement prepared

### Launch Day

- [ ] Post announcement on GitHub Discussions
- [ ] Share Discord invite link
- [ ] Pin welcome messages
- [ ] Monitor both platforms actively
- [ ] Welcome early members
- [ ] Address any technical issues

### First Week

- [ ] Seed initial discussions
- [ ] Respond to all questions
- [ ] Adjust channel structure if needed
- [ ] Gather feedback on platform setup
- [ ] Start establishing community norms

---

## Part 5: Long-Term Considerations

### Growth Management

**GitHub Discussions:**
- Add more categories as needed
- Create discussion templates
- Regular cleanup of old/resolved discussions

**Discord:**
- Scale moderation team with growth
- Add channels as specific needs emerge
- Consider server boosts for better features
- May need multiple servers for different regions

### Community Health

- Regular community surveys
- Transparent moderation reports
- Community-driven rule updates
- Recognition of contributors
- Conflict resolution processes

### Integration Opportunities

**Bots:**
- GitHub-Discord bridge bot for announcements
- RSS feeds for GitHub activity
- Automated welcome DMs

**Future Platforms:**
- Consider Matrix for decentralized chat
- Forum software for long-form discussions
- Video conferencing for large meetings

---

## Conclusion

Setting up GitHub Discussions and Discord provides complementary spaces for the OC-AGI community:
- **GitHub** for transparent, permanent, formal discussion
- **Discord** for real-time, informal, community building

Both platforms should reflect OC-AGI values: transparency, inclusivity, and human dignity.

Start simple, gather feedback, and evolve based on community needs.

---

<!-- AI: SA (Claude Code v.2.0.27, CLI) -->
