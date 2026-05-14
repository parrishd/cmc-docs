# CMC Data Management Platform Notes

Last updated: 2026-05-13

This documentation site tracks project notes, dashboard progress, technical decisions, open issues, and meeting summaries for the Chesapeake Monitoring Cooperative data-management platform.

## Current Focus

The current development focus includes:

- Vue 3 / Quasar frontend migration
- FastAPI backend services
- SQL Server table and stored procedure updates
- Authentication and role-based access control
- Manage Data section and user-management workflows
- Dashboard development and modernization

## Major Work Areas

| Area | Description |
| --- | --- |
| Dashboard modules | Development and modernization of CMC dashboard tools |
| SQL table migration | Migration from legacy identity/user tables into new auth structures |
| Auth and roles | Role-based access control for Admin, Officer, Member, Coordinator, and Monitor users |
| Manage Data section | Authenticated tools for users and data-management workflows |

## Recent Progress

- Added new authentication and role-related SQL tables.
- Continued migration away from the legacy AngularJS / ASP.NET Identity-style user system.
- Added Manage Data layout structure.
- Updated Manage Users role and group visibility rules.
- Debugged route guard behavior around login, registration, profile, and Manage Data pages.

## Current Open Items

| Item | Priority | Notes |
| --- | ---: | --- |
| Profile edit routing | High | Edit profile button appears to remain on the profile page |
| Member visibility rules | High | Confirm group-scoped user visibility |
| Role editing rules | Medium | Continue testing role changes by current user role |