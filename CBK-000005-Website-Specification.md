# CBK-000005 — Website Specification

**Project:** UK ChatGPT Community  
**Version:** 1.0  
**Status:** Stage 0 — Founder  
**Type:** Product and Engineering Specification

## 1. Purpose

The UK ChatGPT Community website is the public digital home of the community.

It must help people:

- discover the community;
- understand its purpose;
- meet other people;
- find physical meetups;
- discover projects;
- learn;
- contribute;
- find opportunities;
- connect with universities, companies and researchers.

The website is not intended to be a simple blog.

It is the digital front door to a real-world community.

## 2. Core Principle

> **Digital infrastructure connects people. Real-world interaction makes the community alive.**

Physical meetups and human relationships are therefore first-class features.

## 3. Primary Users

The platform should support:

- visitors;
- members;
- students;
- developers;
- researchers;
- founders;
- companies;
- universities;
- meetup organisers;
- project contributors;
- volunteers;
- future community leaders.

## 4. Primary User Journeys

### Visitor

Home → Understand → Explore → Find Event → Join

### Builder

Home → Projects → GitHub → Contribute

### Student

Home → Learning → Meetup → Community → Project

### Researcher

Home → Research → People → Event → Collaboration

### Company

Home → Community → Projects → Partnership

### Meetup Organiser

Community → Start Meetup → Event → Attendees → Event Results

## 5. Main Website Areas

### Home

The homepage should immediately communicate:

- what the community is;
- why it exists;
- what is happening now;
- how someone can participate.

Primary actions:

- Join the Community
- Find a Meetup
- Explore Projects
- Become a Builder

## 6. Community

The Community area should eventually provide:

- member information;
- skills and interests;
- working groups;
- local hubs;
- mentoring;
- community announcements;
- contribution opportunities.

The first release may be much simpler.

## 7. Meetups

Meetups are a central feature.

The platform should eventually support:

- upcoming events;
- event descriptions;
- locations;
- dates;
- organisers;
- registration;
- attendance;
- local chapters;
- event reminders;
- event results.

Each completed meetup should be able to leave behind:

- photographs;
- notes;
- presentations;
- projects;
- recordings where appropriate;
- follow-up actions.

## 8. Meetup Types

Potential examples:

### Build Night

Members work together on projects.

### Robotics Night

Robotics demonstrations and experimentation.

### AI Walk & Talk

Small groups discuss AI while meeting physically.

### University × Industry

Researchers, students and companies collaborate.

### AI + Sport

AI, football, computer vision, robotics and sports technology.

### Research Evening

Researchers and engineers present current work.

### Demo Day

Members demonstrate projects they have built.

## 9. Local Hubs

The platform should eventually support regional communities.

Potential examples:

- London;
- Manchester;
- Birmingham;
- Bristol;
- Leeds;
- Liverpool;
- Cambridge;
- Oxford;
- Glasgow;
- Edinburgh.

The list is not fixed.

A hub should only be created when there are people able to maintain it.

## 10. Projects

The Projects area connects the website to GitHub.

Each project page should eventually display:

- project name;
- purpose;
- status;
- contributors;
- maintainer;
- roadmap;
- GitHub repository;
- documentation;
- progress;
- demo;
- contribution opportunities.

## 11. Learning

Learning should include:

- beginner guides;
- ChatGPT resources;
- AI explainers;
- tutorials;
- research summaries;
- technical guides;
- community presentations.

Content should distinguish:

- verified information;
- opinion;
- speculation;
- community experiments.

## 12. Research

The Research area may eventually contain:

- AI research summaries;
- robotics research;
- automation research;
- community reports;
- open questions;
- research projects;
- university collaborations.

## 13. Innovation Lab

The Innovation Lab is the experimental area.

Potential topics include:

- robotics;
- automation;
- computer vision;
- AI agents;
- low-energy AI;
- local AI;
- AI for manufacturing;
- AI for sport;
- AI for accessibility.

Experimental claims must be clearly labelled as experimental.

## 14. Organisations

Future organisation profiles may include:

- companies;
- startups;
- universities;
- research groups;
- community partners.

No organisation should be presented as a partner without an actual relationship.

## 15. Builder Programme

The website should eventually provide a recruitment area for:

- software engineers;
- designers;
- researchers;
- meetup organisers;
- documentation contributors;
- infrastructure specialists;
- community coordinators;
- security advisers.

Each role should have:

- description;
- responsibilities;
- skills;
- expected commitment;
- application method;
- review process.

## 16. News and Articles

The website may publish:

- community news;
- AI developments;
- event reports;
- research summaries;
- project updates.

Content should prioritise accuracy over publishing speed.

External information should be attributed appropriately.

## 17. Search

The website should eventually support searching:

- people;
- events;
- projects;
- articles;
- research;
- organisations;
- locations.

The initial version may use simple site search.

## 18. Accessibility

The website should be designed for broad accessibility.

It should consider:

- keyboard navigation;
- readable typography;
- sufficient contrast;
- semantic HTML;
- image alternatives;
- captions where appropriate;
- mobile access;
- reduced-motion preferences.

Accessibility should be part of the design system rather than added later.

## 19. Design

The visual identity should be:

- modern;
- professional;
- welcoming;
- technically credible;
- approachable;
- responsive.

The website must not rely on excessive animation, unnecessary visual effects or complicated navigation.

## 20. Mobile

The website must work well on:

- desktop;
- laptop;
- tablet;
- mobile.

Mobile visitors should be able to:

- find a meetup;
- read the mission;
- join;
- view projects;
- access GitHub.

## 21. Performance

The initial site should prioritise:

- fast loading;
- lightweight assets;
- efficient images;
- minimal JavaScript where possible;
- reliable hosting.

The community should not pay for infrastructure before actual usage requires it.

## 22. Hosting Strategy

Stage 0 should prefer simple managed or static hosting.

Potential options include:

- GitHub Pages;
- Cloudflare Pages;
- similar managed static hosting.

The website must be designed so that its public domain can later be moved to more powerful infrastructure without redesigning the entire platform.

## 23. Deployment

The intended long-term workflow is:

GitHub

↓

Automated Build

↓

Tests

↓

Preview

↓

Review

↓

Production

No routine production deployment should depend on manually uploading files from a personal computer.

## 24. Security

Security requirements will increase as the platform becomes more interactive.

Stage 0 should avoid collecting unnecessary sensitive information.

Future systems must consider:

- authentication;
- authorisation;
- rate limiting;
- secure secrets;
- backups;
- audit logs;
- incident response.

## 25. Privacy

The platform should collect only information necessary for its stated purposes.

Future account systems must clearly explain:

- what information is collected;
- why it is collected;
- how long it is kept;
- who can access it.

## 26. Community Safety

The website must eventually support:

- reporting;
- moderation;
- appeals;
- anti-harassment procedures;
- account restrictions where necessary.

Community safety requirements increase as membership grows.

## 27. Governance Pages

The website should provide public access to appropriate governance information:

- Constitution;
- Code of Conduct;
- Community Builder Kit;
- leadership structure;
- important decisions;
- transparency information.

## 28. GitHub Integration

Where possible, public projects should connect directly to GitHub.

The website should not attempt to replace GitHub's engineering functionality during Stage 0.

The website explains and presents the work.

GitHub remains the engineering workspace.

## 29. Analytics

Analytics should be used responsibly to understand:

- useful pages;
- event interest;
- project discovery;
- community growth.

Analytics should not become the primary objective of the website.

## 30. Search Engine Discoverability

The website should be designed so that useful pages can be discovered through search engines.

The goal is to create genuinely useful pages around topics such as:

- UK AI community;
- AI meetups;
- robotics events;
- AI projects;
- AI learning;
- automation;
- AI research.

Search visibility should come from useful content rather than manipulative techniques.

## 31. Stage-0 Website Scope

The first public website should be deliberately small.

Minimum release:

- Home;
- About;
- Vision;
- Community;
- Meetups;
- Projects;
- Become a Builder;
- GitHub;
- Contact;
- Governance.

Advanced systems such as full member accounts, messaging and complex social features are deferred until there is a demonstrated need.

## 32. Stage-0 Success Criteria

The website is successful if a new visitor can:

1. understand the community in under five minutes;
2. discover an upcoming meetup;
3. discover a project;
4. find the GitHub repository;
5. understand how to contribute;
6. understand the community's independence and governance.

## 33. Scalation Requirements

Before adding a major website feature, apply:

**CBK-000003 — Scalation Protocol**

Consider:

- people;
- infrastructure;
- cost;
- security;
- maintenance;
- moderation;
- future scale.

## 34. Reality Check Requirements

Before major releases, apply:

**CBK-000004 — Reality Check Panel**

The release must be understandable, operable, maintainable and sufficiently tested for its stage.

## 35. Future Architecture

The platform may eventually evolve toward:

- member accounts;
- profiles;
- personalised dashboards;
- event registration;
- local hubs;
- messaging;
- project dashboards;
- organisation pages;
- mentoring;
- community search;
- notifications.

These are future capabilities, not Stage-0 requirements.

## 36. Dependencies

This document depends on:

- CBK-000001 — Community Builder Blueprint;
- CBK-000002 — Community Constitution;
- CBK-000003 — Scalation Protocol;
- CBK-000004 — Reality Check Panel.

## 37. Revision History

### Version 1.0

Initial Stage-0 Website Specification.
