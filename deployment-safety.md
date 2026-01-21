# Deployment Safety

## Pre-deployment Checklist
- Docker image builds successfully
- Ports are not conflicting
- Environment variables (secrets) configured
- Must have a backup containers

## Production Restrictions
- No root containers
- No hardcoded secrets inside running containers
- Limited port exposure
- Resource limits applied

## Rollback Strategy
- Keep previous Docker images
- Rollback by redeploying previous image tag
- Use docker-compose down && up with older version
