# Awarding Organisations — Phase 1 Index

This section provides a version-aware catalogue layer for authoritative awarding-organisation sources used by DBOS.

## Innovate Awarding

Current Phase 1 assets include:

- source register;
- apprenticeship catalogue schema;
- apprenticeship index for publicly listed Level 2–5 products;
- qualification index for publicly listed Level 2–5 qualifications and diplomas;
- version and status fields;
- official catalogue provenance and checked dates.

Primary source: https://innovateawarding.org/services/assessment/

Important limitation: detailed EPA methods, grading descriptors, KSB mappings, units and assessment criteria require individual product-page and document ingestion. Public catalogue records alone do not provide all of that detail.

## City & Guilds Functional Skills

Current Phase 1 assets include:

- source register;
- document register for Functional Skills English Levels 1 and 2;
- document register for Functional Skills Mathematics Levels 1 and 2;
- current handbook, mapping and delivery-guidance versions as listed on the official qualification page.

Primary source: https://www.cityandguilds.com/qualifications-and-apprenticeships/skills-for-work-and-life/english-mathematics-and-ict-skills/4748-functional-skills

## Retrieval rule

For any professional, assessment or compliance question, DBOS must:

1. identify awarding organisation;
2. identify qualification or apprenticeship title;
3. identify level and version;
4. retrieve the applicable official document;
5. cite the source and version used;
6. flag ambiguity rather than merging versions.

## Phase boundary

Phase 1 creates the searchable catalogue and provenance layer. Phase 2 will ingest detailed content from individual specifications and guidance documents where access and licensing permit.