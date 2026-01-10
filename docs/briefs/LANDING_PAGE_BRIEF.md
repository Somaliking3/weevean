# Landing Page Design & Development Brief

## Project Overview

**Product**: Weevean - Open-source team chat platform with AI assistance  
**Page Type**: Marketing landing page  
**Target URL**: `/` (root domain)  
**Goal**: Convert visitors to sign up and create their first workspace

---

## 1. Objectives & Success Metrics

### Primary Objectives

- Clearly communicate what Weevean is and why teams need it
- Drive sign-ups and workspace creation
- Establish credibility and trust in the developer community
- Differentiate from Slack/Discord

### Success Metrics

- Sign-up conversion rate > 5%
- Average time on page > 45 seconds
- Scroll depth > 75%
- CTA click-through rate > 10%

---

## 2. Target Audience

### Primary Persona: "Alex - Tech Lead"

- **Role**: Engineering Manager / Tech Lead
- **Age**: 28-40
- **Pain Points**:
  - Existing chat tools lack AI-powered assistance
  - Poor code sharing and formatting
  - Expensive for small teams
  - Want open-source for customization
- **Motivations**:
  - AI-powered collaboration and context understanding
  - Better team collaboration
  - Control over data and infrastructure
  - Cost-effective solution
  - Support for technical discussions

### Secondary Persona: "Sam - Developer"

- **Role**: Junior/Mid-level Developer
- **Age**: 22-30
- **Pain Points**:
  - Hard to follow technical discussions in regular chat
  - Need better code sharing
  - Want AI assistance for debugging and learning
  - Need to learn from team conversations
- **Motivations**:
  - AI-powered coding assistance
  - Cleaner developer experience
  - Better code readability
  - Free/open-source tools
  - Easier collaboration

---

## 3. Page Structure & Content

### 3.1 Hero Section (Above the Fold)

**Goal**: Immediate clarity on what Weevean is

**Required Elements**:

- **Headline**: Clear, benefit-driven (35-50 characters)
  - Primary: "Team Chat, Powered by AI"
  - Alternative: "Collaborate Smarter with AI"
- **Subheadline**: Expand on the value proposition (80-120 characters)
  - Example: "Open-source team chat with AI assistance, code execution, and markdown support. Built for modern teams."
  - Alternative: "Self-hosted Slack alternative with AI-powered context, smart summaries, and code analysis. Your data, your control."
- **Primary CTA**: "Start Free" / "Create Workspace"
- **Secondary CTA**: "View Demo" / "See GitHub"
- **Hero Visual**:
  - Screenshot/mockup of the chat interface showing:
    - Clean, dark-mode design
    - Code snippet with syntax highlighting
    - Multiple channels visible
    - AI assistant providing contextual help
  - Dimensions: 1200x800px minimum
  - Format: PNG with transparency or high-quality WebP

**Design Notes**:

- Use gradient background (subtle, not overwhelming)
- Hero should occupy 70-80vh on desktop
- Clear visual hierarchy: headline → subheadline → CTAs → visual
- Ensure accessibility: AA contrast minimum

---

### 3.2 Social Proof Section

**Goal**: Build immediate trust

**Required Elements**:

- "Trusted by developers at" with company logos
- GitHub star count (dynamic, fetched from API)
- Early user testimonials (2-3 quotes)
- Statistics:
  - "Open Source"
  - "Self-Hosted"

**Design Notes**:

- Subtle animation on scroll-in
- Mobile: single column, stack vertically

---

### 3.3 Features Section

**Goal**: Show why Weevean is better than alternatives

**Feature Blocks** (6 core features):

1. **AI-Powered Context Assistant**

   - Icon: Sparkles or brain icon? Experiment.
   - Headline: "AI that understands your conversations"
   - Description: "Get instant answers, code assistance, and smart summaries from an AI trained on your team's context. Debug faster, onboard quicker, collaborate smarter."
   - Visual: Screenshot showing AI assistant answering a technical question with context

2. **Smart Thread Summaries**

   - Icon: List or document icon
   - Headline: "Never lose track of long discussions"
   - Description: "AI-generated summaries for lengthy threads. Catch up on 50+ messages in seconds with key points and action items extracted automatically."
   - Visual: Before/after showing collapsed summary

3. **Markdown & Code Support**

   - Icon: Code brackets `</>` or terminal icon.
   - Headline: "Write code, not plain text"
   - Description: "Full markdown support with syntax highlighting for 50+ languages. Share code snippets that actually look like code."
   - Visual: Animated GIF or screenshot showing markdown rendering

4. **Real-Time Collaboration**

   - Icon: Lightning bolt or chat bubbles
   - Headline: "Instant, persistent messaging"
   - Description: "Channels, direct messages, and threading. All the features you expect from Slack, built for speed and reliability."
   - Visual: Screenshot of threaded conversation with multiple participants

5. **Code Execution (Coming Soon)**

   - Icon: Play button or terminal
   - Headline: "Run code directly in chat"
   - Description: "Execute Python and JavaScript snippets without leaving the conversation. Perfect for debugging, demos, and collaborative coding."
   - Visual: Code execution preview with output showing in chat

6. **Open Source & Self-Hosted**
   - Icon: Unlock or GitHub logo
   - Headline: "Your data, your infrastructure"
   - Description: "Deploy on your servers. Full control over your data. No vendor lock-in. MIT licensed and community-driven."
   - Visual: Architecture diagram or deployment graphic

**Layout Options**:

- **Option A**: Bento grid (2x2 on desktop, 1 column mobile). My Fav!
- **Option B**: Alternating left/right layout with large visuals
- **Option C**: Card grid with hover effects

**Design Notes**:

- Each feature needs an icon (custom or from Lucide React)
- Icons should be consistent style (outline or solid, not mixed)
- Visual hierarchy: Icon → Headline → Description
- Add subtle hover animations on desktop

---

### 3.4 How It Works Section

**Goal**: Remove friction by showing simplicity

**Steps** (3-step process):

1. **Sign Up** → "Create your account in 30 seconds"
2. **Create Workspace** → "Set up your team workspace"
3. **Invite Team** → "Share an invite link with your team"

**Visual Treatment**:

- Numbered steps with connecting line/arrows
- Screenshot or illustration for each step
- Keep it minimal and scannable

---

### 3.5 Comparison Section

**Goal**: Show competitive advantages with AI as primary differentiator

**Format**: Comparison table

- **Columns**: Weevean | Slack | Discord | Mattermost
- **Rows**:
  - **AI Assistant** ✓ | Add-on ($$$) | ✗ | ✗
  - **Smart Thread Summaries** ✓ | ✗ | ✗ | ✗
  - **Code Analysis** ✓ | ✗ | ✗ | ✗
  - **Open Source** ✓ | ✗ | ✗ | ✓
  - **Code Execution** ✓ | ✗ | ✗ | ✗
  - **Self-Hosted** ✓ | ✗ | ✗ | ✓
  - **Free for Small Teams** ✓ | Limited | ✓ | ✓
  - **Markdown Support** ✓ | ✓ | Limited | ✓

**Design Notes**:

- Mobile: Show only Weevean vs Slack
- Highlight AI features at the top of comparison
- Use checkmarks (✓) and crosses (✗)
- Highlight Weevean column with subtle background color

---

### 3.6 CTA Section

**Goal**: Convert visitors who scrolled this far

**Required Elements**:

- **Headline**: Direct and urgent
  - Example: "Ready to upgrade your team chat?"
- **Subheadline**: Remove objections
  - Example: "Free forever for small teams. No credit card required."
- **Primary CTA**: Large button "Get Started Free"
- **Secondary CTA**: "Talk to our team"

**Design Notes**:

- Full-width section with contrasting background
- Large, prominent CTA button
- Add urgency without being pushy

---

### 3.7 Footer

**Goal**: Provide additional resources and build trust

**Sections**:

- **Product**: Features, Pricing, Roadmap, Changelog
- **Resources**: Documentation, API Docs, GitHub, Community
- **Company**: About, Blog, Contact, Privacy Policy
- **Social**: GitHub, Twitter, Discord, LinkedIn

**Design Notes**:

- Dark feel/background
- 4-column layout on desktop, accordion on mobile
- Include newsletter signup (optional). I love substack.

---

### 3.8 AI Features Showcase Section

**Goal**: Highlight AI as key differentiator from Slack and other platforms

**Layout**: 3-column feature grid with prominent placement

**AI Features**:

1. **Context-Aware Assistant**

   - Description: "Ask questions and get answers based on your team's conversation history and codebase context"
   - Example: "What did Sarah say about the API migration?" → AI provides answer with message citations
   - Visual: Chat interface showing AI response with contextual citations
   - Badge: "Powered by Vercel AI SDK"

2. **Smart Thread Summaries**

   - Description: "Long discussion? Get AI-generated summaries instantly with key points and action items"
   - Example: "Summarize this 50-message thread" → Condensed summary with highlights
   - Visual: Before/after showing thread collapsed into summary view

3. **Code Analysis & Debugging**
   - Description: "AI reviews code snippets, explains errors, and suggests improvements in real-time"
   - Example: "What's wrong with this Python function?" → AI explains bug and suggests fix
   - Visual: Code snippet with AI-generated feedback and corrections

**Design Notes**:

- Use gradient background to distinguish from other sections
- Include "Privacy First" callout: "AI runs on your workspace data only. Never trained on your conversations."
- Show "Multi-Provider Support" badge: OpenAI, Anthropic, Google, local models
- Add trust indicators: "SOC2 Compliant" (We don't have this yet, but we will), "Zero-Data Retention Mode"

---

### 3.9 FAQ Section

**Goal**: Address common concerns about AI, privacy, and platform

**Questions**:

1. **How does the AI work?**

   - "Weevean uses the Vercel AI SDK with support for multiple providers (OpenAI, Anthropic, Google, etc.). It analyzes your conversation context to provide relevant answers and assistance."

2. **Is my data used to train AI models?**

   - "No. Your data stays private. We use AI APIs in zero-data-retention mode, meaning your conversations are never stored by AI providers or used for training."

3. **Can I use my own AI API key?**

   - "Yes! Self-hosted deployments support bring-your-own-key for any supported AI provider (OpenAI, Anthropic, Google, or local models)."

4. **What makes Weevean different from Slack + ChatGPT?**

   - "Weevean's AI is deeply integrated with your workspace context, understands your conversations and codebase, and doesn't require copy-pasting. It's designed for seamless collaboration, not bolt-on chat."

5. **How much does AI cost?**

   - "For cloud deployments, AI features are included in pricing. For self-hosted, you bring your own API key and pay your provider directly (typically $0.001-0.01 per query)."

6. **What about AI privacy and security?**
   - "All AI queries use zero-data-retention mode. Your data never trains external models. Self-hosted deployments give you complete control over AI provider selection and data flow."

**Design Notes**:

- Keep questions concise and answers informative
- Use a clean, readable font
- Include icons or illustrations where relevant
- Ensure accessibility: proper heading hierarchy and focus states

---

## 4. Design Requirements

### 4.1 Visual Design System

**Color Palette**:

```css
// I don't know yet... I'll provide but you're free to surprise me.
```

**Typography**:

```
 // I'll talk to a designer for better perspective
```

---

### 4.2 Responsive Breakpoints

```css
/* Mobile First */
// Use tailwindcss
```

**Mobile Considerations**:

- Stack all sections vertically
- Hero visual below headline/CTA on mobile
- Feature cards in single column
- Comparison table: show only 2 columns (Weevean vs Slack)
- Footer: accordion or stacked sections

---

### 4.3 Animation & Interactions

**Scroll Animations**:

Anything good

**Hover States**:

Subtle

**Performance**:

- Use `will-change` sparingly
- Prefer CSS transforms over position changes
- Lazy load images below fold

---

## 5. Technical Specifications

### 5.1 Stack

- **Framework**: Next.js 16 (App Router)
- **Styling**: Tailwind CSS v4
- **Components**: shadcn/ui
- **Animations**: Framer Motion or CSS animations
- **Icons**: Lucide React
- **Images**: Next.js `<Image>` component with WebP

### 5.2 Performance Requirements

- Lighthouse Score:
  - Performance: > 90
  - Accessibility: > 95
  - Best Practices: > 90
  - SEO: > 90
- First Contentful Paint: < 1.5s
- Largest Contentful Paint: < 2.5s
- Cumulative Layout Shift: < 0.1

### 5.3 SEO Requirements

**Meta Tags**:

```html
<title>Weevean - Team Chat with AI Assistance | Open Source</title>
<meta
  name="description"
  content="Open-source team chat with AI-powered assistance, code execution, and markdown support. Self-hosted Slack alternative built for modern collaboration."
/>
<!--  name="keywords"? keywords meta are now obsolete. Please don't bother using them -->

<!-- Open Graph -->
<meta property="og:title" content="Weevean - Team Chat with AI Assistance" />
<meta
  property="og:description"
  content="Open-source collaboration with AI-powered context, smart summaries, and code execution."
/>
<meta property="og:image" content="/og-image.png" />
<meta property="og:type" content="website" />

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="Weevean - Team Chat with AI Assistance" />
<meta
  name="twitter:description"
  content="Open-source team chat built for modern collaboration."
/>
<meta name="twitter:image" content="/twitter-image.png" />
```

**Structured Data** (JSON-LD):

```json
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "Weevean",
  "applicationCategory": "BusinessApplication",
  "offers": {
    "@type": "Offer",
    "price": "0",
    "priceCurrency": "USD"
  },
  "description": "Open-source team chat with AI assistance"
}
```

### 5.4 Accessibility Requirements

- All images have `alt` text
- Proper heading hierarchy (H1 → H2 → H3)
- Focus states visible on all interactive elements
- Keyboard navigation works throughout
- ARIA labels on icon-only buttons
- Color contrast meets WCAG AA standards (4.5:1 minimum)

---

## 6. Assets Needed

### From Design Team:

- [ ] Hero visual/screenshot (1200x800px)
- [ ] Feature screenshots/illustrations (6 images)
- [ ] AI feature screenshots/illustrations (3 images)
- [ ] OG image for social sharing (1200x630px)
- [ ] Favicon set (16x16, 32x32, 180x180, 192x192, 512x512)
- [ ] Logo variations (light mode, dark mode, icon only)

### From Content Team:

- [ ] Finalized headline and subheadline copy
- [ ] Feature descriptions (50-80 words each)
- [ ] AI feature descriptions (50-80 words each)
- [ ] User testimonials (We'll get em, let's keep building)
- [ ] Company logos for social proof (We'll get em, let's keep building)

### From Development Team:

- [ ] GitHub star count API endpoint
- [ ] Sign-up flow integration
- [ ] Analytics tracking setup
- [ ] AI assistant integration (Vercel AI SDK)
- [ ] Smart thread summaries feature
- [ ] Code analysis feature

---

## 7. File Structure

```
app/
├── (marketing)/
│   ├── layout.tsx          # Marketing layout (different from app)
│   ├── page.tsx            # Landing page
│   └── components/
│       ├── hero-section.tsx
│       ├── features-section.tsx
│       ├── how-it-works.tsx
│       ├── comparison-table.tsx
│       ├── ai-features-showcase.tsx
│       ├── faq-section.tsx
│       ├── cta-section.tsx
│       └── footer.tsx
└── globals.css

public/
├── images/
│   ├── hero.png
│   ├── feature-*.png
│   ├── ai-feature-*.png
│   └── og-image.png
└── logos/
    └── companies/
```

---

## 8. Acceptance Criteria

### Design Phase

- [ ] Design mockups approved for desktop, tablet, mobile
- [ ] Component library/design system documented
- [ ] All assets exported and optimized
- [ ] Accessibility audit completed

### Development Phase

- [ ] All sections implemented and responsive
- [ ] Lighthouse scores meet requirements
- [ ] SEO meta tags implemented
- [ ] Analytics tracking verified
- [ ] AI assistant integration tested
- [ ] Smart thread summaries feature tested
- [ ] Code analysis feature tested
- [ ] Cross-browser testing passed (Chrome, Firefox, Safari, Edge)
- [ ] Accessibility testing passed (keyboard nav, screen reader)

### Content Phase

- [ ] All copy finalized and approved
- [ ] Images have proper alt text
- [ ] CTAs are clear and actionable
- [ ] Links all work correctly

---

## 9. Timeline Estimate

**Design Phase**: 2 weeks

- Wireframes
- High-fidelity mockups
- Revisions

**Development Phase**: 4 weeks

- Component development
- Responsive implementation
- AI assistant integration
- Optimization & testing

**Total**: 6 weeks

---

## 10. References & Inspiration

**Good Examples**:

- Linear.app - Clean, developer-focused design
- Supabase.com - Great use of code examples and dark mode
- Vercel.com - Minimalist, high-performance landing page
- Raycast.com - Excellent product screenshots and feature presentation
- Anthropic.com - Strong AI feature communication

**What to Avoid**:

- Generic stock photos
- Cluttered layouts with too much information
- Aggressive sales language
- Auto-playing videos (use click-to-play)
- Slow loading images

---

## 12. Post-Launch

**Analytics to Track**:

- Conversion rate (visitor → sign-up)
- Scroll depth and engagement
- CTA click-through rates
- Traffic sources
- Bounce rate

**A/B Testing Ideas**:

- Headline variations
- CTA button text ("Start Free" vs "Create Workspace")
- Hero visual (screenshot vs illustration)
- Feature order and presentation
- AI assistant visibility (above the fold vs below)
