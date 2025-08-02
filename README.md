# Legacy AI SaaS Development Agents
A comprehensive collection of specialized AI agents designed to accelerate and enhance every aspect of SaaS development. Each agent is an expert in their domain, ready to be invoked when building, scaling, and maintaining SaaS products.

## 📥 Installation
Download this repository:

```bash
git clone https://github.com/legacy-ai/saas-agents.git
```
Copy to your Claude Code agents directory:

```bash
cp -r saas-agents/* ~/.claude/agents/
```
Or manually copy all the agent files to your `~/.claude/agents/` directory.

Restart Claude Code to load the new agents.

## 🚀 Quick Start
Agents are automatically available in Claude Code. Simply describe your task and the appropriate agent will be triggered. You can also explicitly request an agent by mentioning their name.

### Example Usage
- "Design a multi-tenant architecture for our SaaS" → `saas-architect`
- "Implement Stripe billing for our subscription tiers" → `payment-integrator`
- "Analyze our churn rate and suggest improvements" → `metrics-analyst`
- "Create an onboarding flow that converts" → `onboarding-optimizer`

## 📁 Directory Structure
Agents are organized by department for easy discovery:

```
legacy-ai-agents/
├── architecture/
│   ├── saas-architect.md
│   ├── security-engineer.md
│   ├── scalability-planner.md
│   ├── database-designer.md
│   └── api-architect.md
├── development/
│   ├── backend-developer.md
│   ├── frontend-developer.md
│   ├── fullstack-engineer.md
│   ├── mobile-developer.md
│   ├── devops-engineer.md
│   ├── qa-engineer.md
│   ├── performance-optimizer.md
│   └── accessibility-champion.md
├── product/
│   ├── product-manager.md
│   ├── user-researcher.md
│   ├── feature-prioritizer.md
│   ├── roadmap-planner.md
│   └── competitor-analyst.md
├── growth/
│   ├── growth-engineer.md
│   ├── onboarding-optimizer.md
│   ├── retention-specialist.md
│   ├── viral-feature-designer.md
│   └── referral-program-builder.md
├── revenue/
│   ├── pricing-strategist.md
│   ├── payment-integrator.md
│   ├── billing-optimizer.md
│   ├── revenue-analyst.md
│   ├── subscription-manager.md
│   ├── expansion-revenue-specialist.md
│   └── trial-converter.md
├── customer-success/
│   ├── support-engineer.md
│   ├── documentation-writer.md
│   ├── customer-success-manager.md
│   ├── feedback-analyzer.md
│   ├── churn-preventer.md
│   ├── health-score-optimizer.md
│   └── community-builder.md
├── analytics/
│   ├── metrics-analyst.md
│   ├── data-engineer.md
│   ├── dashboard-builder.md
│   ├── kpi-tracker.md
│   └── experiment-analyst.md
├── marketing/
│   ├── content-marketer.md
│   ├── seo-specialist.md
│   ├── email-campaign-manager.md
│   ├── social-media-manager.md
│   └── landing-page-optimizer.md
├── operations/
│   ├── compliance-manager.md
│   ├── infrastructure-optimizer.md
│   ├── cost-controller.md
│   ├── vendor-manager.md
│   └── process-automator.md
├── experience/
│   ├── whimsy-injector.md
│   ├── micro-interaction-designer.md
│   └── delight-engineer.md
├── integrations/
│   ├── api-integrator.md
│   ├── webhook-architect.md
│   ├── oauth-implementer.md
│   └── third-party-connector.md
├── ai-ml/
│   ├── ai-feature-builder.md
│   ├── ml-ops-engineer.md
│   ├── prompt-engineer.md
│   └── data-scientist.md
└── special/
    ├── launch-coordinator.md
    ├── pivot-strategist.md
    ├── saas-mentor.md
    ├── chaos-tester.md
    └── hil-advisor.md
```

## 📋 Complete Agent List

### Architecture Department (`architecture/`)
- **saas-architect** - Design multi-tenant architectures that scale to millions
- **security-engineer** - Implement enterprise-grade security and compliance
- **scalability-planner** - Plan for 100x growth without rewrites
- **database-designer** - Optimize data models for SaaS workloads
- **api-architect** - Build APIs that developers love to integrate

### Development Department (`development/`)
- **backend-developer** - Build robust server-side SaaS features
- **frontend-developer** - Create responsive, performant web applications
- **fullstack-engineer** - Handle end-to-end feature development
- **mobile-developer** - Build native mobile experiences for your SaaS
- **devops-engineer** - Automate deployments and maintain uptime
- **qa-engineer** - Ensure quality at every release
- **performance-optimizer** - Make your SaaS blazing fast
- **accessibility-champion** - Ensure your SaaS works for everyone

### Product Department (`product/`)
- **product-manager** - Define features that users actually need
- **user-researcher** - Understand your users deeply
- **feature-prioritizer** - Build the right things in the right order
- **roadmap-planner** - Create achievable product roadmaps
- **competitor-analyst** - Stay ahead of the competition

### Growth Department (`growth/`)
- **growth-engineer** - Build features that drive viral growth
- **onboarding-optimizer** - Convert trials to paying customers
- **retention-specialist** - Keep users engaged and subscribed
- **viral-feature-designer** - Create features users share naturally
- **referral-program-builder** - Design referral systems that work

### Revenue Department (`revenue/`)
- **pricing-strategist** - Optimize pricing for maximum revenue
- **payment-integrator** - Implement payment systems that convert
- **billing-optimizer** - Reduce failed payments and involuntary churn
- **revenue-analyst** - Understand and grow your revenue metrics
- **subscription-manager** - Handle complex subscription scenarios
- **expansion-revenue-specialist** - Grow revenue from existing customers
- **trial-converter** - Optimize trial-to-paid conversion rates

### Customer Success (`customer-success/`)
- **support-engineer** - Build self-service support features
- **documentation-writer** - Create docs users actually read
- **customer-success-manager** - Ensure customer value realization
- **feedback-analyzer** - Turn user feedback into features
- **churn-preventer** - Identify and save at-risk customers
- **health-score-optimizer** - Track and improve customer health
- **community-builder** - Foster user communities and advocates

### Analytics Department (`analytics/`)
- **metrics-analyst** - Track what matters for SaaS success
- **data-engineer** - Build data pipelines that scale
- **dashboard-builder** - Create actionable analytics dashboards
- **kpi-tracker** - Monitor critical SaaS KPIs
- **experiment-analyst** - Run A/B tests that drive growth

### Marketing Department (`marketing/`)
- **content-marketer** - Create content that attracts ideal customers
- **seo-specialist** - Dominate organic search for SaaS keywords
- **email-campaign-manager** - Build email sequences that convert
- **social-media-manager** - Build community and drive signups
- **landing-page-optimizer** - Create pages that convert visitors

### Operations Department (`operations/`)
- **compliance-manager** - Handle GDPR, SOC2, and compliance
- **infrastructure-optimizer** - Reduce costs while improving performance
- **cost-controller** - Keep your burn rate sustainable
- **vendor-manager** - Optimize third-party service costs
- **process-automator** - Automate repetitive operational tasks

### Experience Department (`experience/`)
- **whimsy-injector** - Add delightful moments throughout your SaaS
- **micro-interaction-designer** - Create small interactions with big impact
- **delight-engineer** - Build features that make users smile

### Integrations Department (`integrations/`)
- **api-integrator** - Connect your SaaS to the ecosystem
- **webhook-architect** - Build real-time event systems
- **oauth-implementer** - Handle secure third-party authentication
- **third-party-connector** - Integrate with popular tools seamlessly

### AI/ML Department (`ai-ml/`)
- **ai-feature-builder** - Add intelligent features to your SaaS
- **ml-ops-engineer** - Deploy and maintain ML models in production
- **prompt-engineer** - Optimize AI interactions for users
- **data-scientist** - Extract insights from your SaaS data

### 🎁 Special Agents
- **launch-coordinator** - Orchestrate successful product launches
- **pivot-strategist** - Navigate strategic pivots successfully
- **saas-mentor** - Get strategic advice for your SaaS journey
- **chaos-tester** - Find breaking points before users do
- **hil-advisor** - Pre-flight check for human dependencies before coding

## 🎯 Proactive Agents
Some agents trigger automatically in specific contexts:

- **hil-advisor** - ALWAYS runs first to identify human dependencies
- **saas-mentor** - When facing complex strategic decisions
- **security-engineer** - When handling sensitive data or auth flows
- **metrics-analyst** - When implementing new features without tracking
- **churn-preventer** - When user engagement metrics drop
- **whimsy-injector** - After creating UI/UX elements that need personality

## 💡 Best Practices
- **HIL-First Approach** - Always run pre-flight checks before coding begins
- **Let agents collaborate** - Complex SaaS features benefit from multiple perspectives
- **Be specific** - Clear requirements help agents deliver better solutions
- **Think in iterations** - SaaS is about continuous improvement
- **Measure everything** - Data-driven decisions are SaaS decisions
- **Prioritize user experience** - Happy users = lower churn
- **Build for scale** - What works at 100 users must work at 100,000

## 🔧 Technical Details

### Agent Structure
Each agent includes:
- **name**: Unique identifier
- **description**: When to use with SaaS-specific examples
- **color**: Visual identification
- **tools**: Specific tools the agent can access
- **System prompt**: Deep SaaS expertise and best practices

### Adding New Agents
1. Create a new `.md` file in the appropriate department
2. Follow the YAML frontmatter format
3. Include 3-4 SaaS-specific examples
4. Write comprehensive system prompt (500+ words)
5. Test with real SaaS scenarios

## 📊 Agent Performance Metrics
Track agent effectiveness through:
- Feature delivery speed
- Code quality metrics
- User satisfaction scores
- Revenue impact
- Bug reduction rates

## 🛠️ Customizing Agents for Your SaaS

### Agent Customization Checklist

#### 📋 Required Components
- [ ] **YAML Frontmatter**
  - [ ] name: Unique agent identifier (kebab-case)
  - [ ] description: When to use + 3-4 detailed SaaS examples
  - [ ] color: Visual identification
  - [ ] tools: Specific tools (Write, Read, MultiEdit, Bash, etc.)

#### 📝 System Prompt Requirements (500+ words)
- [ ] **Agent Identity**: Clear role in SaaS context
- [ ] **Core Responsibilities**: 5-8 SaaS-specific duties
- [ ] **Domain Expertise**: Technical skills for SaaS
- [ ] **SaaS Best Practices**: Industry standards and patterns
- [ ] **Constraints**: What to avoid in SaaS context
- [ ] **Success Metrics**: SaaS KPIs and measurements

### 🎯 Required Examples by Agent Type

**Architecture Agents** need examples for:
- [ ] Multi-tenant design decisions
- [ ] Scaling challenges
- [ ] Security implementations
- [ ] API design patterns

**Growth Agents** need examples for:
- [ ] Viral feature implementations
- [ ] Onboarding flow optimizations
- [ ] Retention improvements
- [ ] Referral program designs

**Revenue Agents** need examples for:
- [ ] Pricing model changes
- [ ] Payment flow optimizations
- [ ] Billing issue resolutions
- [ ] Subscription management

**Analytics Agents** need examples for:
- [ ] KPI dashboard creation
- [ ] Cohort analysis
- [ ] Funnel optimization
- [ ] A/B test design

### ✅ Testing & Validation Checklist
- [ ] **Trigger Testing**: Agent activates for SaaS scenarios
- [ ] **Tool Access**: Can use all specified tools
- [ ] **Output Quality**: Produces SaaS-ready solutions
- [ ] **Integration**: Works with other SaaS agents
- [ ] **Performance**: Delivers within sprint timelines
- [ ] **Documentation**: Examples reflect real SaaS use cases

## 🔧 Agent File Structure Template

```yaml
---
name: your-saas-agent
description: Use this agent when [SaaS scenario]. This agent specializes in [SaaS expertise]. Examples:\n\n<example>\nContext: [SaaS situation]\nuser: "[user request]"\nassistant: "[SaaS-focused response]"\n<commentary>\n[why this matters for SaaS]\n</commentary>\n</example>\n\n[3 more SaaS examples...]
color: agent-color
tools: Write, Read, MultiEdit, Bash
---

You are a [SaaS role] who specializes in [specific SaaS area]. Your expertise spans [SaaS domains]. You understand that in SaaS, [key principle], so you [approach].

Your primary responsibilities:
1. [SaaS-specific responsibility 1]
2. [SaaS-specific responsibility 2]
...

You follow SaaS best practices including:
- Multi-tenant architecture considerations
- Subscription business model optimization
- User retention and engagement
- Scalability and performance
- Security and compliance

[Detailed system prompt content focused on SaaS...]

Your goal is to [SaaS objective]. You prioritize [SaaS values]. Remember: In SaaS, [key philosophy].
```

## 🎨 Customization Guidelines

### Department-Specific Focus Areas
- **Architecture**: Scalability, multi-tenancy, performance
- **Development**: Feature velocity, code quality, testing
- **Product**: User value, market fit, competitive advantage
- **Growth**: Viral loops, activation, retention
- **Revenue**: Pricing optimization, payment success, expansion
- **Customer Success**: Satisfaction, retention, advocacy
- **Analytics**: Data-driven decisions, experimentation
- **Marketing**: Acquisition, conversion, brand building
- **Operations**: Efficiency, compliance, cost optimization
- **Experience**: Delight, personality, memorable interactions

## 🤝 Contributing
To improve existing agents or suggest new ones:
1. Follow the customization checklist
2. Test with real SaaS scenarios
3. Document performance improvements
4. Share successful patterns

## 📈 Success Metrics
Track these key SaaS metrics:
- **MRR/ARR Growth**
- **Churn Rate**
- **Customer Acquisition Cost (CAC)**
- **Lifetime Value (LTV)**
- **Net Promoter Score (NPS)**
- **Feature Adoption Rate**
- **Time to Value**
- **Support Ticket Volume**

---

*Built for Legacy AI - Accelerating SaaS Development with AI-Powered Expertise*

## 🚨 Human-In-the-Loop (HIL) Advisor Protocol

The **hil-advisor** agent is a critical orchestration component that MUST run before any coding begins. This agent performs a comprehensive pre-flight check to identify all human dependencies.

### HIL Advisor Responsibilities:

1. **Pre-Code Analysis** - Scans requirements for external dependencies
2. **Dependency Identification** - Lists all required:
   - API keys and credentials
   - Third-party service accounts
   - OAuth app configurations
   - Database connection strings
   - Environment variables
   - Domain verifications
   - SSL certificates
   - Payment processor accounts
   - Email service configurations
   - Cloud service credentials

3. **Human Action Checklist** - Creates a complete list of items YOU need to provide
4. **Blocks Coding** - Prevents other agents from starting until all dependencies are confirmed
5. **Validates Completeness** - Ensures no placeholders or mock data will be used

### Example HIL Advisor Output:
```
🚨 HUMAN ACTION REQUIRED - Pre-Flight Check

Before we begin coding your payment integration, I need:

✅ Required Immediately:
- [ ] Stripe API keys (publishable & secret)
- [ ] Webhook endpoint secret
- [ ] Product IDs for subscription tiers

⚠️ Required Before Deploy:
- [ ] Production Stripe account
- [ ] Domain verification for Stripe
- [ ] Terms of Service URL

📋 Optional Enhancements:
- [ ] Custom receipt email template
- [ ] Tax configuration settings

Please provide these items before we proceed to avoid any placeholders in the code.
```

This ensures your builds are production-ready from the start!
