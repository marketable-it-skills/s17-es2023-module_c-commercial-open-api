# Project Plan: Updating s17-es2023-module_c-commercial-open-api

## Analysis of Current State

After carefully reviewing the standardized task guide and current project structure, I've identified critical alignment issues:

### CRITICAL ISSUES:
1. **Wrong metadata.json**: Currently has "WS2024 S17 - Module B" and "Products Management" - completely wrong task
2. **Incorrect marking scheme**: The marking-scheme.json contains product management criteria, not API development criteria
3. **Missing required files**: No `development-and-deployment.md`
4. **Wrong README title**: Says "Products Management" instead of "Commercial Open API"
5. **Project description structure**: Doesn't follow the standardized format exactly

### Correct Information Analysis:
- **Task**: Commercial Open API (REST API for AI services)
- **Competition**: EuroSkills Gdansk 2023
- **Module**: Module C
- **Duration**: 3 hours  
- **Total marks**: 17 points
- **Focus**: Back-end development (15 points) + organization (1) + communication (1)
- **Technologies**: Should include TypeScript, Node.js, REST API, Docker

### Required Files Per Guide:
1. `/README.md` ✓ (exists but wrong content)
2. `/project-description.md` ✓ (exists but wrong structure)  
3. `/development-and-deployment.md` ❌ (missing)
4. `/metadata.json` ✓ (exists but completely wrong)
5. `/marking/marking-scheme.json` ✓ (exists but wrong content)
6. `/assets/` ✓ (exists)
7. `/assets/project-description-images` ❌ (missing proper structure)

## Todo List

### Phase 1: File Structure and Organization
- [ ] Create missing `development-and-deployment.md` file
- [ ] Create proper `/assets/project-description-images/` folder structure
- [ ] Move/organize any images needed for project description

### Phase 2: Content Standardization
- [ ] Update `project-description.md` to follow standardized format:
  - [ ] Fix heading to "Test Project Outline – Module C – Commercial Open API"
  - [ ] Add proper competition time section
  - [ ] Restructure Introduction section
  - [ ] Reorganize General Description section
  - [ ] Standardize Requirements section formatting
  - [ ] Update Assessment section
  - [ ] Fix Mark Distribution table formatting

### Phase 3: Metadata and Configuration
- [ ] **COMPLETE REWRITE** of `metadata.json` with correct information:
  - [ ] Fix name field: "ES2023 S17 - Module C" (currently wrong: "WS2024 S17 - Module B")
  - [ ] Update displayName to "Commercial Open API" (currently wrong: "Products Management")
  - [ ] Fix description to match REST API for AI services task
  - [ ] Correct competition field to "EuroSkills Gdansk 2023" 
  - [ ] Add proper technology tags: ["TypeScript", "Node.js", "REST API", "Docker", "Express"]
  - [ ] Add estimated time: 3 hours
  - [ ] Add authors: Cyril Wanner (CH) and Sebastian Häni (CH)
  - [ ] Fix skillDomains to use array format: ["Web Technologies"]
  - [ ] Add correct GitHub URL when known

### Phase 4: Documentation Updates
- [ ] Update `README.md` to follow standardized format:
  - [ ] Fix title to match actual project
  - [ ] Add proper skill domains
  - [ ] Update task origin information
  - [ ] Add links to all required documents
  - [ ] Include MITS project section

### Phase 5: Technical Setup  
- [ ] **COMPLETE REWRITE** of `/marking/marking-scheme.json`:
  - [ ] Remove all product management criteria (currently wrong content)
  - [ ] Create proper API development marking scheme
  - [ ] Include authentication, quotas, billing, error handling criteria
  - [ ] Follow the JSON structure from standardized guide
  - [ ] Ensure total marks = 17 (15 back-end + 1 organization + 1 communication)
- [ ] Create proper `development-and-deployment.md`:
  - [ ] Follow the template structure from standardized guide
  - [ ] Update for Node.js/TypeScript project (not HTML/JS)
  - [ ] Include Docker setup instructions
  - [ ] Include API testing instructions
- [ ] Ensure all file paths and references are correct
- [ ] Check that all assets are properly organized

### Phase 6: Quality Assurance
- [ ] Review all content for clarity and consistency
- [ ] Ensure all original technical content is preserved
- [ ] Verify all links work correctly
- [ ] Cross-check against standardized guide requirements

## Key Principles for Updates:
1. **Preserve all original content** - No technical requirements or instructions should be changed
2. **Improve structure and clarity** - Make the content more student-friendly
3. **Follow standardized format** - Ensure consistency with other MITS tasks
4. **Maintain pedagogical value** - Keep the learning objectives clear

## Expected Outcome:
A fully standardized project task that:
- Follows the exact structure outlined in the standardized task guide
- Maintains all original technical requirements
- Provides clear, student-friendly instructions
- Integrates properly with the MITS repository and web application
- Demonstrates professional formatting and organization

## Approval Needed:
Before proceeding with implementation, please review this plan and confirm:
1. The analysis is accurate
2. The proposed changes align with your expectations
3. The approach preserves the original task integrity
4. Any additional considerations I should include