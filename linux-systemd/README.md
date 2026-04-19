# Linux: systemd & Service Management

## Concepts to Understand

- systemd architecture (units, targets, dependencies)
- service lifecycle (start, stop, restart, failure handling)
- unit types: service, socket, timer
- journald basics and log querying

## Resources

- systemd official documentation
- man systemd, systemctl, journalctl
- DigitalOcean systemd deep dive guides

## Hands-on Labs

- Create custom systemd service (simple script)
- Configure Restart=always and failure handling
- Create systemd timer (cron alternative)
- Enable persistent journald logs
- Use journalctl filters (by unit, time, priority)

## Mini-Project

Custom background service with structured logging

Description:
Implement a service that writes logs and configure journald persistence and filtering.
