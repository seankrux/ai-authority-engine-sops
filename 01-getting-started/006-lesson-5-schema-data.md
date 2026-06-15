# SOP: Building and Implementing Schema Data
**Category:** Getting Started — Lesson 5 | **Duration:** 1h 33m

## Objective
Implement a comprehensive schema markup strategy that gives AI engines rich, structured data about your brand, content, services, and authority signals.

## Prerequisites
- Basic schema knowledge (JSON-LD format)
- Access to website code or CMS (WordPress, Webflow, etc.)

## Step-by-Step Process

### Schema Types Priority Matrix
1. **Tier 1 (Critical — install first):**
   - [ ] Organization (with logo, social profiles, contact)
   - [ ] LocalBusiness (with opening hours, address, phone)
   - [ ] Website (with search action)
2. **Tier 2 (High Impact):**
   - [ ] Article/NewsArticle (for blog content)
   - [ ] FAQPage (for Q&A content)
   - [ ] Product/Service (for offerings)
   - [ ] BreadcrumbList (navigation)
3. **Tier 3 (Authority Builders):**
   - [ ] Review (with aggregate rating)
   - [ ] Event (for webinars/promotions)
   - [ ] VideoObject (for video content)
   - [ ] HowTo (for service processes)
   - [ ] Person (for individual experts/team)

### Implementation Process
4. Generate JSON-LD using Google's Structured Data Markup Helper
5. Test each schema with Google Rich Results Test
6. Deploy via:
   - WordPress: Yoast/RankMath SEO plugin
   - Webflow: Custom code embed in <head>
   - Hardcoded: Add to <script type="application/ld+json"> in <head>
7. Verify with Google Search Console → Schema reports

### The Authority Wheel Schema Integration
8. Link schema types together using @id references
9. Create entity relationship: Person → worksFor → Organization
10. Add sameAs references from Organization schema to all social platforms
11. Connect Review schema to Organization via itemReviewed property

### Maintenance
12. Monthly schema validation check (Google Rich Results Test)
13. Update schema when: address changes, hours change, new services added
14. Monitor Search Console for schema errors and warnings

## Key Deliverables
- [ ] Organization + LocalBusiness schema live
- [ ] FAQPage schema on 5+ key pages
- [ ] Review schema with AggregateRating
- [ ] Schema relationship graph documented

## Verification
Google Rich Results Test shows 0 errors, 0 warnings
Search Console shows schema-enhanced results in performance report
AI engines show structured data in knowledge panels

## Fireflies Reference
https://app.fireflies.ai/view/AI-Authority-Engine-Week-5-Schema-the-Authority-Wheel-and-AI-Trust-mp4::01KTMRG1ESCD0GG9A18B0GZSWX
