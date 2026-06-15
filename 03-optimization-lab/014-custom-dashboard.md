# SOP: Custom Dashboard Setup
**Category:** Optimization Lab | **Duration:** 1h 58m

## Objective
Build a custom AI authority dashboard that consolidates all key metrics — citations, reviews, rankings, AI visibility scores — into one real-time view for client reporting and internal tracking.

## Prerequisites
- Data sources identified (GBP, Search Console, Semrush, BrightLocal)
- Google LookerStudio access (free)

## Step-by-Step Process

### Dashboard Planning
1. Define metrics to track:
   - **Citations**: total, net new / month, consistency score
   - **Reviews**: count, average rating, response rate, velocity
   - **AI Visibility**: Knowledge Panel status, AI mention count (weekly)
   - **Content**: indexed pages, featured snippets, AI answer inclusion
   - **Rankings**: average position, visibility score, competitor compare
   - **Schema**: errors, warnings, rich result appearances
2. Identify data sources and connection methods
3. Sketch dashboard layout:
   - Top: KPI summary row (4-6 key numbers)
   - Middle: trending charts (weekly/daily)
   - Bottom: detailed tables (citation list, review log)

### Build Phase (LookerStudio)
4. Create new LookerStudio report → blank template
5. Add data sources:
   - Google Search Console (direct connector)
   - Google Business Profile (direct connector)
   - Google Analytics 4 (direct connector)
   - Manual sheets: citation tracker, review tracker, AI audit log
6. Build pages:
   - **Page 1**: Executive Overview (KPIs + trends)
   - **Page 2**: AI Visibility & Mentions
   - **Page 3**: Reviews & Reputation
   - **Page 4**: Citations & Directories
   - **Page 5**: Content & Rankings
7. Add date range controls → apply to all charts
8. Set up auto-email delivery (weekly to client)

### Data Maintenance
9. Update manual sheets every Monday (citation count, AI audit)
10. Review automated data sources for accuracy
11. Adjust dashboard as new metrics become important

## Key Deliverables
- [ ] LookerStudio dashboard live with 5+ pages
- [ ] All data sources connected
- [ ] Auto-email report scheduled
- [ ] Client access granted

## Verification
Dashboard shows real-time data from 3+ automated sources
Manual data entry takes < 15 min/week
Client receives auto-report without manual effort

## Fireflies Reference
https://app.fireflies.ai/view/E-Forge-Ai-Authority-Call-Jess-Agency-Dashboard-Rollout-mp4::01KTMZV4S38640Q5WD9C6PEQ3D
