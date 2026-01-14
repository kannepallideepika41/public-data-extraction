# System Architecture

## Overview
The system extracts public government data from multiple portals and converts it into a unified, structured format.

## Components
1. Data Ingestion
   - Web scraping from procurement portals
   - PDF and scanned document extraction

2. AI Extraction Layer
   - NLP for entity extraction (items, quantity, price, vendor)
   - Indic language support and translation

3. Data Standardization
   - Unified schema for all portals
   - Deduplication across platforms

4. Storage & Access
   - Structured database (CSV/SQL)
   - API for analytics and dashboards

## Output
- Searchable tenders
- Project progress tracking
- Delay and cost overrun insights
