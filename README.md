# Awesome Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources, examples, and tools for [AGENTS.md](https://agents.md) — a simple, open format for guiding coding agents.

AGENTS.md is used by over 20,000 open-source projects. Think of it as a README for agents: a dedicated, predictable place to provide context and instructions to help AI coding agents work on your project.

## Contents

- [Specification](#specification)
- [Projects Using AGENTS.md](#projects-using-agentsmd)
- [AGENTS.md files](#agentsmd-files)
- [Tooling & Services](#tooling--services)
- [Contribute](#contribute)

## Specification

- [OpenAI/agents.md](https://github.com/openai/agents.md) - The official spec of the `AGENTS.md` format. ![](https://img.shields.io/github/stars/openai/agents.md?style=social)
- [agentmd/agent.md](https://github.com/agentmd/agent.md) - The singular variant `AGENT.md` and universal config file concept. ![](https://img.shields.io/github/stars/agentmd/agent.md?style=social)

## Projects Using AGENTS.md

Real-world projects implementing AGENTS.md, AGENT.md, or CLAUDE.md for AI agent configuration.

### Memory & Knowledge Management

- [supermemory/CLAUDE.md](https://github.com/supermemoryai/supermemory/blob/main/CLAUDE.md) - Memory engine and app that is extremely fast, scalable. The Memory API for the AI era. ([source](https://github.com/supermemoryai/supermemory))

### Model Context Protocol (MCP)

- [fastmcp/AGENTS.md](https://github.com/jlowin/fastmcp/blob/main/AGENTS.md) - The fast, Pythonic way to build MCP servers and clients. ([source](https://github.com/jlowin/fastmcp))
- [mcp-go/AGENTS.md](https://github.com/mark3labs/mcp-go/blob/main/AGENTS.md) - A Go implementation of the Model Context Protocol (MCP), enabling seamless integration between LLM applications and external data sources and tools. ([source](https://github.com/mark3labs/mcp-go))

### AI & LLM Frameworks

- [openai-agents-python/AGENTS.md](https://github.com/openai/openai-agents-python/blob/main/AGENTS.md) - A lightweight, powerful framework for multi-agent workflows. ([source](https://github.com/openai/openai-agents-python))

### Agent Platforms

- [giselle/AGENTS.md](https://github.com/giselles-ai/giselle/blob/main/AGENTS.md) - Giselle: AI App Builder. Open Source. ([source](https://github.com/giselles-ai/giselle))

### Development Tools & Frameworks

- [Archon/AGENTS.md](https://github.com/coleam00/Archon/blob/main/AGENTS.md) - Beta release of Archon OS - the knowledge and task management backbone for AI coding assistants. ([source](https://github.com/coleam00/Archon))

## AGENTS.md files

### AI Specialists

- [AI Ethics Advisor](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ai-specialists/ai-ethics-advisor.md) - AI ethics and responsible AI development specialist.
- [Hackathon AI Strategist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ai-specialists/hackathon-ai-strategist.md) - Expert hackathon strategist and judge.
- [Llms Maintainer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ai-specialists/llms-maintainer.md) - LLMs.txt roadmap file generator and maintainer.
- [Model Evaluator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ai-specialists/model-evaluator.md) - AI model evaluation and benchmarking specialist.
- [Prompt Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ai-specialists/prompt-engineer.md) - Expert prompt optimization for LLMs and AI systems.
- [Search Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ai-specialists/search-specialist.md) - Expert web researcher using advanced search techniques and synthesis. Masters search operators, result filtering, and multi-source verification. Handles competitive analysis and fact-checking.
- [Task Decomposition Expert](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ai-specialists/task-decomposition-expert.md) - Complex goal breakdown specialist.

### Api GraphQL

- [GraphQL Architect](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/api-graphql/graphql-architect.md) - GraphQL schema design and API architecture specialist.
- [GraphQL Performance Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/api-graphql/graphql-performance-optimizer.md) - GraphQL performance analysis and optimization specialist.
- [GraphQL Security Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/api-graphql/graphql-security-specialist.md) - GraphQL API security and authorization specialist.

### Blockchain Web3

- [Smart Contract Auditor](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/blockchain-web3/smart-contract-auditor.md) - Conducting security audits of smart contracts. Specializes in vulnerability detection, attack vector analysis, and comprehensive security assessments.
- [Smart Contract Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/blockchain-web3/smart-contract-specialist.md) - Developing production-level smart contracts. Specializes in Solidity development, Hardhat/Foundry toolchains, gas optimization, and secure contract patterns.
- [Web3 Integration Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/blockchain-web3/web3-integration-specialist.md) - Building Web3 frontend applications and wallet integrations. Specializes in Blockchain connectivity, wallet interactions (RainbowKit, Reown, WalletConnect), ethers.js/viem, and dApp development.

### Business Marketing

- [Business Analyst](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/business-analyst.md) - Business metrics analysis and reporting specialist.
- [Content Marketer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/content-marketer.md) - Content marketing and SEO optimization specialist.
- [Customer Support](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/customer-support.md) - Support documentation and user assistance specialist.
- [Legal Advisor](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/legal-advisor.md) - Legal documentation and compliance specialist.
- [Marketing Attribution Analyst](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/marketing-attribution-analyst.md) - Marketing attribution and performance analysis specialist.
- [Payment Integration](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/payment-integration.md) - Payment systems integration specialist.
- [Product Strategist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/product-strategist.md) - Product strategy and roadmap planning specialist.
- [Risk Manager](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/risk-manager.md) - Risk management and portfolio analysis specialist.
- [Sales Automator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/business-marketing/sales-automator.md) - Sales automation and outreach specialist.

### Data AI

- [AI Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/data-ai/ai-engineer.md) - LLM application and RAG system specialist.
- [Computer Vision Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/data-ai/computer-vision-engineer.md) - Computer vision and image processing specialist.
- [Data Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/data-ai/data-engineer.md) - Data pipeline and analytics infrastructure specialist.
- [Data Scientist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/data-ai/data-scientist.md) - Data analysis and statistical modeling specialist.
- [Ml Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/data-ai/ml-engineer.md) - ML production systems and model deployment specialist.
- [Mlops Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/data-ai/mlops-engineer.md) - ML infrastructure and operations specialist.
- [Nlp Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/data-ai/nlp-engineer.md) - Natural Language Processing and text analytics specialist.
- [Quant Analyst](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/data-ai/quant-analyst.md) - Quantitative finance and algorithmic trading specialist.

### Database

- [Database Admin](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/database-admin.md) - Database administration specialist for operations, backups, replication, and monitoring.
- [Database Architect](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/database-architect.md) - Database architecture and design specialist.
- [Database Optimization](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/database-optimization.md) - Database performance optimization and query tuning specialist.
- [Database Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/database-optimizer.md) - SQL query optimization and database schema design specialist.
- [Neon Auth Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/neon-auth-specialist.md) - Neon Auth implementation specialist.
- [Neon Database Architect](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/neon-database-architect.md) - Neon database architecture specialist.
- [Neon Expert](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/neon-expert.md) - General Neon Serverless PostgreSQL consultant.
- [NoSQL Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/nosql-specialist.md) - NoSQL database specialist for MongoDB, Redis, Cassandra, and document/key-value stores.
- [Supabase Schema Architect](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/database/supabase-schema-architect.md) - Supabase database schema design specialist.

### Deep Research Team

- [Academic Researcher](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/academic-researcher.md) - Academic research specialist for scholarly sources, peer-reviewed papers, and academic literature.
- [Competitive Intelligence Analyst](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/competitive-intelligence-analyst.md) - Competitive intelligence and market research specialist.
- [Data Analyst](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/data-analyst.md) - Quantitative analysis, statistical insights, and data-driven research specialist.
- [Fact Checker](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/fact-checker.md) - Fact verification and source validation specialist.
- [Query Clarifier](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/query-clarifier.md) - Analyzes research queries for clarity and determines if user clarification is needed before proceeding with research.
- [Report Generator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/report-generator.md) - Transforms synthesized research findings into comprehensive, well-structured final reports.
- [Research Brief Generator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/research-brief-generator.md) - Transforms user research queries into structured, actionable research briefs.
- [Research Coordinator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/research-coordinator.md) - Strategically plans and coordinates complex research tasks across multiple specialist researchers.
- [Research Orchestrator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/research-orchestrator.md) - Coordinates comprehensive research projects requiring multiple specialized agents working in sequence.
- [Research Synthesizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/research-synthesizer.md) - Consolidates and synthesizes findings from multiple research sources into unified, comprehensive analyses.
- [Technical Researcher](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/deep-research-team/technical-researcher.md) - Analyzes code repositories, technical documentation, implementation details, and evaluates technical solutions.

### Development Team

- [Backend Architect](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-team/backend-architect.md) - Backend system architecture and API design specialist.
- [Cli Ui Designer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-team/cli-ui-designer.md) - CLI interface design specialist.
- [Devops Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-team/devops-engineer.md) - DevOps and infrastructure specialist for CI/CD, deployment automation, and cloud operations.
- [Frontend Developer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-team/frontend-developer.md) - Frontend development specialist for React applications and responsive design.
- [Fullstack Developer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-team/fullstack-developer.md) - Full-stack development specialist covering frontend, backend, and database technologies.
- [iOS Developer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-team/ios-developer.md) - Native iOS development specialist with Swift and SwiftUI.
- [Mobile Developer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-team/mobile-developer.md) - Cross-platform mobile development specialist for React Native and Flutter.
- [Ui Ux Designer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-team/ui-ux-designer.md) - UI/UX design specialist for user-centered design and interface systems.

### Development Tools

- [Code Reviewer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/code-reviewer.md) - Expert code review specialist for quality, security, and maintainability.
- [Command Expert](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/command-expert.md) - CLI command development specialist for the claude-code-templates system.
- [Context Manager](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/context-manager.md) - Context management specialist for multi-agent workflows and long-running tasks.
- [Debugger](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/debugger.md) - Debugging specialist for errors, test failures, and unexpected behavior.
- [Dx Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/dx-optimizer.md) - Developer Experience specialist for tooling, setup, and workflow optimization.
- [Error Detective](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/error-detective.md) - Log analysis and error pattern detection specialist.
- [Flutter Go Reviewer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/flutter-go-reviewer.md) - Code review specialist for Flutter and Go applications.
- [MCP Expert](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/mcp-expert.md) - Model Context Protocol (MCP) integration specialist for the cli-tool components system.
- [Performance Profiler](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/performance-profiler.md) - Performance analysis and optimization specialist.
- [Test Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/test-engineer.md) - Test automation and quality assurance specialist.
- [Unused Code Cleaner](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/development-tools/unused-code-cleaner.md) - Detects and removes unused code (imports, functions, classes) across multiple languages.

### Devops Infrastructure

- [Cloud Architect](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/devops-infrastructure/cloud-architect.md) - Cloud infrastructure design and optimization specialist for AWS/Azure/GCP.
- [Deployment Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/devops-infrastructure/deployment-engineer.md) - CI/CD and deployment automation specialist.
- [Devops Troubleshooter](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/devops-infrastructure/devops-troubleshooter.md) - Production troubleshooting and incident response specialist.
- [Monitoring Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/devops-infrastructure/monitoring-specialist.md) - Monitoring and observability infrastructure specialist.
- [Network Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/devops-infrastructure/network-engineer.md) - Network connectivity and infrastructure specialist.
- [Security Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/devops-infrastructure/security-engineer.md) - Security infrastructure and compliance specialist.
- [Terraform Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/devops-infrastructure/terraform-specialist.md) - Terraform and Infrastructure as Code specialist.
- [Vercel Deployment Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/devops-infrastructure/vercel-deployment-specialist.md) - Expert in Vercel platform features, edge functions, middleware, and deployment strategies.

### Documentation

- [Api Documenter](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/documentation/api-documenter.md) - Create OpenAPI/Swagger specs, generate SDKs, and write developer documentation. Handles versioning, examples, and interactive docs.
- [Changelog Generator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/documentation/changelog-generator.md) - Changelog and release notes specialist.
- [Docusaurus Expert](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/documentation/docusaurus-expert.md) - Docusaurus documentation specialist.
- [Technical Writer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/documentation/technical-writer.md) - Technical writing and content creation specialist.

### Expert Advisors

- [Agent Expert](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/expert-advisors/agent-expert.md) - AI agent architecture and implementation specialist.
- [Architect Review](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/expert-advisors/architect-review.md) - Use this agent to review code for architectural consistency and patterns. Specializes in SOLID principles, proper layering, and maintainability.
- [Dependency Manager](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/expert-advisors/dependency-manager.md) - Use this agent to manage project dependencies. Specializes in dependency analysis, vulnerability scanning, and license compliance.
- [Documentation Expert](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/expert-advisors/documentation-expert.md) - Use this agent to create, improve, and maintain project documentation. Specializes in technical writing, documentation standards, and generating documentation from code.

### FFmpeg Clip Team

- [Audio Mixer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ffmpeg-clip-team/audio-mixer.md) - Multi-track audio mixing and mastering specialist.
- [Audio Quality Controller](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ffmpeg-clip-team/audio-quality-controller.md) - Audio quality enhancement and analysis specialist.
- [Podcast Content Analyzer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ffmpeg-clip-team/podcast-content-analyzer.md) - Podcast content analysis specialist.
- [Podcast Metadata Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ffmpeg-clip-team/podcast-metadata-specialist.md) - Podcast metadata and show notes specialist.
- [Podcast Transcriber](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ffmpeg-clip-team/podcast-transcriber.md) - Audio transcription specialist.
- [Social Media Clip Creator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ffmpeg-clip-team/social-media-clip-creator.md) - Social media video clip optimization specialist.
- [Timestamp Precision Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ffmpeg-clip-team/timestamp-precision-specialist.md) - Frame-accurate timestamp extraction specialist.
- [Video Editor](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ffmpeg-clip-team/video-editor.md) - Video editing and production specialist.

### Game Development

- [3D Artist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/game-development/3d-artist.md) - 3D art and asset creation specialist for game development.
- [Game Designer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/game-development/game-designer.md) - Game design specialist focusing on mechanics, balancing, player psychology, and system design.
- [Unity Game Developer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/game-development/unity-game-developer.md) - Expert Unity game developer specializing in C# scripting, 3D graphics, mobile optimization, and complete game development workflows. Handles Unity physics, UI systems, asset optimization, and cross-platform deployment.
- [Unreal Engine Developer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/game-development/unreal-engine-developer.md) - Expert Unreal Engine developer specializing in C++ programming, Blueprint visual scripting, and AAA game development. Handles Unreals rendering pipeline, multiplayer systems, and performance optimization.

### Git

- [Git Flow Manager](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/git/git-flow-manager.md) - Git Flow workflow manager.

### MCP Dev Team

- [MCP Deployment Orchestrator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/mcp-dev-team/mcp-deployment-orchestrator.md) - MCP server deployment and operations specialist.
- [MCP Integration Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/mcp-dev-team/mcp-integration-engineer.md) - MCP server integration and orchestration specialist.
- [MCP Protocol Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/mcp-dev-team/mcp-protocol-specialist.md) - MCP protocol specification and standards specialist.
- [MCP Registry Navigator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/mcp-dev-team/mcp-registry-navigator.md) - MCP registry discovery and integration specialist.
- [MCP Security Auditor](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/mcp-dev-team/mcp-security-auditor.md) - MCP server security specialist.
- [MCP Server Architect](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/mcp-dev-team/mcp-server-architect.md) - MCP server architecture and implementation specialist.
- [MCP Testing Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/mcp-dev-team/mcp-testing-engineer.md) - MCP server testing and quality assurance specialist.

### Modernization

- [Architecture Modernizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/modernization/architecture-modernizer.md) - Software architecture modernization specialist.
- [Cloud Migration Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/modernization/cloud-migration-specialist.md) - Cloud migration and infrastructure modernization specialist.
- [Legacy Modernizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/modernization/legacy-modernizer.md) - Refactor legacy codebases, migrate outdated frameworks, and implement gradual modernization. Handles technical debt, dependency updates, and backward compatibility.

### Obsidian Ops Team

- [Connection Agent](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/obsidian-ops-team/connection-agent.md) - Obsidian vault connection specialist.
- [Content Curator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/obsidian-ops-team/content-curator.md) - Obsidian content curation and quality specialist.
- [Metadata Agent](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/obsidian-ops-team/metadata-agent.md) - Obsidian metadata management specialist.
- [Moc Agent](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/obsidian-ops-team/moc-agent.md) - Obsidian Map of Content specialist.
- [Review Agent](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/obsidian-ops-team/review-agent.md) - Obsidian vault quality assurance specialist.
- [Tag Agent](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/obsidian-ops-team/tag-agent.md) - Obsidian tag taxonomy specialist.
- [Vault Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/obsidian-ops-team/vault-optimizer.md) - Obsidian vault performance optimization specialist.

### Ocr Extraction Team

- [Document Structure Analyzer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ocr-extraction-team/document-structure-analyzer.md) - Document structure analysis specialist.
- [Markdown Syntax Formatter](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ocr-extraction-team/markdown-syntax-formatter.md) - Markdown formatting specialist.
- [Ocr Grammar Fixer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ocr-extraction-team/ocr-grammar-fixer.md) - OCR text correction specialist.
- [Ocr Preprocessing Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ocr-extraction-team/ocr-preprocessing-optimizer.md) - OCR preprocessing and image optimization specialist.
- [Ocr Quality Assurance](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ocr-extraction-team/ocr-quality-assurance.md) - OCR pipeline validation specialist.
- [Text Comparison Validator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ocr-extraction-team/text-comparison-validator.md) - Text comparison and validation specialist.
- [Visual Analysis Ocr](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/ocr-extraction-team/visual-analysis-ocr.md) - Visual analysis and OCR specialist.

### Performance Testing

- [Load Testing Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/performance-testing/load-testing-specialist.md) - Load testing and stress testing specialist.
- [Performance Engineer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/performance-testing/performance-engineer.md) - Profile applications, optimize bottlenecks, and implement caching strategies. Handles load testing, CDN setup, and query optimization.
- [React Performance Optimization](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/performance-testing/react-performance-optimization.md) - Specialist in optimizing React application performance and speed.
- [Test Automator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/performance-testing/test-automator.md) - Create comprehensive test suites with unit, integration, and e2e tests. Sets up CI pipelines, mocking strategies, and test data.
- [Web Vitals Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/performance-testing/web-vitals-optimizer.md) - Core Web Vitals optimization specialist.

### Podcast Creator Team

- [Academic Research Synthesizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/academic-research-synthesizer.md) - Academic research synthesis specialist.
- [Comprehensive Researcher](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/comprehensive-researcher.md) - Comprehensive research specialist.
- [Episode Orchestrator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/episode-orchestrator.md) - Episode workflow orchestrator.
- [Guest Outreach Coordinator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/guest-outreach-coordinator.md) - Podcast guest outreach and coordination specialist.
- [Market Research Analyst](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/market-research-analyst.md) - Market research and competitive analysis specialist.
- [Podcast Editor](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/podcast-editor.md) - Podcast editing and post-production specialist.
- [Podcast Trend Scout](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/podcast-trend-scout.md) - Podcast trend analysis specialist.
- [Project Supervisor Orchestrator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/project-supervisor-orchestrator.md) - Project workflow orchestrator.
- [Seo Podcast Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/seo-podcast-optimizer.md) - SEO podcast optimization specialist.
- [Social Media Copywriter](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/social-media-copywriter.md) - Social media content creation specialist.
- [Twitter AI Influencer Manager](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/podcast-creator-team/twitter-ai-influencer-manager.md) - Twitter AI influencer engagement specialist.

### Programming Languages

- [C Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/c-pro.md) - Write efficient C code with proper memory management, pointer arithmetic, and system calls. Handles embedded systems, kernel modules, and performance-critical code.
- [C Sharp Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/c-sharp-pro.md) - Write idiomatic C# code with modern language features, async patterns, and LINQ. Masters .NET ecosystem, Entity Framework Core, and ASP.NET Core.
- [CPP Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/cpp-pro.md) - Write idiomatic C++ code with modern features, RAII, smart pointers, and STL algorithms. Handles templates, move semantics, and performance optimization.
- [Golang Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/golang-pro.md) - Write idiomatic Go code with goroutines, channels, and interfaces. Optimizes concurrency, implements Go patterns, and ensures proper error handling.
- [JavaScript Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/javascript-pro.md) - Master modern JavaScript with ES6+, async patterns, and Node.js APIs. Handles promises, event loops, and browser/Node compatibility.
- [PHP Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/php-pro.md) - Write idiomatic PHP code with generators, iterators, SPL data structures, and modern OOP features.
- [Python Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/python-pro.md) - Write idiomatic Python code with advanced features like decorators, generators, and async/await. Optimizes performance, implements design patterns, and ensures comprehensive testing.
- [Rust Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/rust-pro.md) - Write idiomatic Rust with ownership patterns, lifetimes, and trait implementations. Masters async/await, safe concurrency, and zero-cost abstractions.
- [Shell Scripting Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/shell-scripting-pro.md) - Write robust shell scripts with proper error handling, POSIX compliance, and automation patterns. Masters bash/zsh features, process management, and system integration.
- [SQL Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/sql-pro.md) - Write complex SQL queries, optimize execution plans, and design normalized schemas. Masters CTEs, window functions, and stored procedures.
- [TypeScript Pro](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/programming-languages/typescript-pro.md) - Write idiomatic TypeScript with advanced type system features, strict typing, and modern patterns. Masters generic constraints, conditional types, and type inference.

### Realtime

- [Supabase Realtime Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/realtime/supabase-realtime-optimizer.md) - Supabase realtime performance specialist.

### Security

- [Api Security Audit](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/security/api-security-audit.md) - Specialist in auditing API security and identifying vulnerabilities.
- [Compliance Specialist](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/security/compliance-specialist.md) - Security compliance and regulatory framework specialist.
- [Incident Responder](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/security/incident-responder.md) - Handles production incidents with urgency and precision.
- [Penetration Tester](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/security/penetration-tester.md) - Penetration testing and ethical hacking specialist.
- [Security Auditor](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/security/security-auditor.md) - Review code for vulnerabilities, implement secure authentication, and ensure OWASP compliance. Handles JWT, OAuth2, CORS, CSP, and encryption.

### Web Tools

- [Next.js Architecture Expert](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/web-tools/nextjs-architecture-expert.md) - Master of Next.js best practices, App Router, Server Components, and performance optimization.
- [React Performance Optimizer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/web-tools/react-performance-optimizer.md) - Specialist in React performance patterns, bundle optimization, and Core Web Vitals.
- [Seo Analyzer](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/web-tools/seo-analyzer.md) - SEO analysis and optimization specialist.
- [Url Context Validator](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/web-tools/url-context-validator.md) - URL validation and contextual analysis specialist.
- [Url Link Extractor](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/web-tools/url-link-extractor.md) - URL and link extraction specialist.
- [Web Accessibility Checker](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/agents/web-tools/web-accessibility-checker.md) - Web accessibility compliance specialist.

### Development & Programming
- [Ethereum Developer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/ethereum-developer.md) - Smart contract development.
- [Senior Frontend Developer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/senior-frontend-developer.md) - Frontend development expertise.
- [Fullstack Software Developer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/fullstack-software-developer.md) - Full-stack development.
- [Machine Learning Engineer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/machine-learning-engineer.md) - ML systems and models.
- [DevOps Engineer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/devops-engineer.md) - Infrastructure and automation.
- [Code Reviewer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/code-reviewer.md) - Code quality and review.
- [Software Quality Assurance Tester](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/software-quality-assurance-tester.md) - QA and testing.
- [Linux Script Developer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/linux-script-developer.md) - Bash and shell scripting.
- [GitHub Expert](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/github-expert.md) - Git and GitHub workflows.

### Security & IT
- [Cyber Security Specialist](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/cyber-security-specialist.md) - Security analysis.
- [IT Architect](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/it-architect.md) - IT architecture design.
- [IT Expert](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/it-expert.md) - Technical support.
- [Large Language Models Security Specialist](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/large-language-models-security-specialist.md) - LLM security.

### Data & Analysis
- [Data Scientist](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/data-scientist.md) - Data analysis and insights.
- [Scientific Data Visualizer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/scientific-data-visualizer.md) - Data visualization.
- [LLM Researcher](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/llm-researcher.md) - Language model research.

### Business & Management
- [Product Manager](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/product-manager.md) - Product strategy.
- [Project Manager](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/project-manager.md) - Project coordination.
- [Chief Executive Officer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/chief-executive-officer.md) - Executive leadership.
- [Startup Idea Generator](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/startup-idea-generator.md) - Business ideation.
- [Career Counselor](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/career-counselor.md) - Career guidance.

### Design & UX
- [UX/UI Developer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/uxui-developer.md) - User experience design.
- [Web Design Consultant](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/web-design-consultant.md) - Web design.
- [SVG Designer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/svg-designer.md) - Vector graphics.
- [Interior Decorator](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/interior-decorator.md) - Interior design.
.
### Writing & Content
- [Tech Writer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/tech-writer.md) - Technical documentation.
- [Essay Writer](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/essay-writer.md) - Essay composition.
- [Screenwriter](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/screenwriter.md) - Script writing.
- [Cover Letter](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/cover-letter.md) - Professional application letters.
- [Commit Message Generator](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/commit-message-generator.md) - Git commit messages.
.
### Education & Training
- [Instructor in a School](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/instructor-in-a-school.md) - Teaching and instruction.
- [Career Coach](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/career-coach.md) - Career development.
- [Study Planner](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/study-planner.md) - Study organization.
- [Knowledgeable Software Development Mentor](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/knowledgeable-software-development-mentor.md) - Mentorship.

### Specialized Tools
- [Regex Generator](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/regex-generator.md) - Regular expressions.
- [SQL Terminal](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/sql-terminal.md) - SQL queries.
- [Python Interpreter](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/python-interpreter.md) - Python code execution.
- [Linux Terminal](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/linux-terminal.md) - Command line.
- [JavaScript Console](https://github.com/tairov/awesome-agents.md/blob/master/agentsmd-files/javascript-console.md) - JS debugging.

## Tooling & Services

- [OpenAI/openai-agents-python](https://github.com/openai/openai-agents-python) - Official agents SDK from OpenAI. ![](https://img.shields.io/github/stars/openai/openai-agents-python?style=social)
- [OpenBMB/RepoAgent](https://github.com/OpenBMB/RepoAgent) - Repository-level agent for documentation & repo understanding. ![](https://img.shields.io/github/stars/OpenBMB/RepoAgent?style=social)
- [mitmedialab/MDAgents](https://github.com/mitmedialab/MDAgents) - Multi-agent system for medical reasoning and tasks. ![](https://img.shields.io/github/stars/mitmedialab/MDAgents?style=social)
- [langchain-ai/agents-from-scratch](https://github.com/langchain-ai/agents-from-scratch) - Tutorial for building ambient agents (email assistant etc.). ![](https://img.shields.io/github/stars/langchain-ai/agents-from-scratch?style=social)
- [drivly/agentic.md](https://github.com/drivly/agentic.md) - Define and visualize agents and workflows in Markdown/Mermaid. ![](https://img.shields.io/github/stars/drivly/agentic.md?style=social)
- [attogram/agents](https://github.com/attogram/agents) - Contains `AGENTS.md`, plus human-persona and platform files; layered architecture. ![](https://img.shields.io/github/stars/attogram/agents?style=social)
- [ChatTeach/Awesome-AI-Agents](https://github.com/ChatTeach/Awesome-AI-Agents) - A curated list of open-source AI agents; includes an `AGENTS.md`. ![](https://img.shields.io/github/stars/ChatTeach/Awesome-AI-Agents?style=social)
- [hfblog/hfblog](https://github.com/AnswerDotAI/hfblog/blob/main/agents.md) - A blog repo demonstrating usage of `agents.md`. ![](https://img.shields.io/github/stars/AnswerDotAI/hfblog?style=social)
- [sst/opencode](https://github.com/sst/opencode) - Issue/discussion on `AGENT.md` vs `AGENTS.md`, showing ecosystem early-stage. ![](https://img.shields.io/github/stars/sst/opencode?style=social)
- [anthropics/claude-code](https://github.com/anthropics/claude-code) - Discussion of adding support for `AGENTS.md`. ![](https://img.shields.io/github/stars/anthropics/claude-code?style=social)
- [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) - CLI tool with 160+ ready-to-use AI agents, custom commands, MCPs, and complete project templates for Claude Code. [Browse templates](https://www.aitmpl.com/agents) ![](https://img.shields.io/github/stars/davila7/claude-code-templates?style=social)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
