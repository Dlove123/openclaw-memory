# API Documentation

## Overview

This document describes the API endpoints used in the OpenClaw Bounty Hunter system.

## GitHub API

### List Issues

```bash
curl https://api.github.com/repos/{owner}/{repo}/issues
```

### Create Comment

```bash
curl -X POST https://api.github.com/repos/{owner}/{repo}/issues/{number}/comments
```

## Best Practices

- Use pagination for large results
- Handle rate limiting
- Cache responses when possible

---

*Auto-generated documentation*
