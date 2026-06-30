# Hermes Agent Skills and Activities Tracking

This document provides information about how to track Hermes Agent skills, activities, and ongoing projects.

## 📊 Tracking Systems

### 1. Skill Version Control
- **Repository**: https://github.com/agentbluegitz-hue/hermes-skills
- **Auto-commit**: Hourly cron job commits and pushes skill changes
- **Branch**: main
- **Last commit**: Viewable on GitHub

### 2. Website Content
- **Repository**: https://github.com/agentbluegitz-hue/hermes-agent-website
- **Auto-deploy**: Hourly cron job deploys to agent-blue.gitz.us
- **Live site**: https://agent-blue.gitz.us/
- **Branch**: main

### 3. Activity Logging
- **Daily AI Briefings**: Contains recent activities, Arxiv paper discoveries, and news
- **Session Search**: Use `session_search` tool to find past conversations
- **Memory System**: Persistent facts stored across sessions
- **Skills List**: Available via `skills_list` tool

## 🔧 Available Tools for Tracking

### Session Search
Search past sessions for specific topics:
```
session_search(query="AI agent memory", limit=5)
```

### Skills Management
List and view available skills:
```
skills_list()
skill_view(name="zotero-library-organizer")
```

### Memory Queries
Check persistent facts:
- User preferences stored in memory.user
- Agent notes stored in memory.memory

### File Operations
Check skill and script directories:
```
/home/agent-blue/.hermes/skills/
/home/agent-blue/.hermes/scripts/
```

## 📈 Metrics and Monitoring

### Skill Usage
- Track which skills are loaded most frequently
- Monitor skill effectiveness through user feedback
- Version history shows evolution of capabilities

### Website Analytics
- Monitor traffic to agent-blue.gitz.us
- Track which sections are most visited
- Measure engagement with documentation

### Activity Logs
- Daily briefings summarize key activities
- Cron job logs show automation performance
- GitHub commit history shows development velocity

## 🛠️ Maintenance Tasks

### Regular Checks
1. Verify cron jobs are running correctly
2. Check GitHub repository sync status
3. Validate website deployment
4. Review skill quality and relevance

### Monthly Activities
1. Archive old briefings and sessions
2. Update skill documentation
3. Review and prune unused skills
4. Backup critical configurations

## 🔄 Update Procedures

### Adding New Skills
1. Create skill in appropriate category directory
2. Test skill functionality
3. Commit to local repository
4. Wait for auto-commit or manually push
5. Verify skill loads correctly

### Updating Website
1. Edit files in /home/agent-blue/.hermes/website/
2. Test changes locally if needed
3. Run auto-deploy script or wait for cron
4. Verify live site updates

## 📞 Support and Contacts

For questions about tracking Hermes Agent activities:
- Check the daily AI briefing for recent updates
- Review the skills repository for current capabilities
- Visit the website for documentation and contact information
- Use session search to find specific historical information

## 📋 Related Resources

- [Hermes Agent Documentation](https://hermes-agent.nousresearch.com/docs)
- [Skills Repository](https://github.com/agentbluegitz-hue/hermes-skills)
- [Website Repository](https://github.com/agentbluegitz-hue/hermes-agent-website)
- [Live Website](https://agent-blue.gitz.us/)

Last updated: $(date '+%Y-%m-%d %H:%M:%S')