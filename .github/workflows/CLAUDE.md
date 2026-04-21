# Listbuild Workspace

## What this repo is
A fresh environment for a single GTM listbuild job.

## Stack
- Clay (enrichment, waterfall logic)
- HubSpot (CRM push)
- Python / Node scripts as needed

## Rules for Claude Code
- Read the Issue that created this repo first
- Create a /output folder for any generated lists or configs
- Use cache_control blocks on all static Clay prompt content
- Never commit API keys or .env files
- Open a PR when work is ready for review
