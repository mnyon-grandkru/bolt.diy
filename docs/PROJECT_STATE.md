# PROJECT STATE

## Project Type
- Internal

## Current Phase
- Active Development

## Current Goal
Maintain custom fork of bolt.diy for Grand Kru use with regular upstream syncs.

## Definition of Done (Phase)
- Set up regular upstream sync schedule
- Document all custom modifications
- Test AI features with custom models
- Consider contributing custom features back upstream

## Current Branch
- main

## Last Completed Step
- Added ARCHAEOLOGY.md and updated PROJECT_STATE.md

## Next 3 Micro Tasks
1. Document all custom env vars and their purposes
2. Test AI features with your specific models/API keys
3. Set up upstream sync schedule

## Blockers / Risks
- Complex fork - upstream updates may cause merge conflicts
- Need to manage secrets carefully

## Technical Notes
- Fork of bolt.diy (AI-powered web dev tool)
- Next.js App Router
- Vercel AI SDK for LLM integration
- Supabase + other databases
- Cloudflare Workers deployment option
- Docker deployment option

## Deployment Notes
- Cloudflare Workers: `wrangler deploy`
- Docker: `docker build && docker run`
- See .env.example for required environment variables

## Exit Criteria for This Phase
What triggers moving this project to:
- Paused: AI dev tool no longer needed
- Archived: Replaced by upstream or alternative
- Production release: N/A - internal tool
