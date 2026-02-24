# Change Log

All notable changes to this project will be documented in this file. The format
is based on [Keep a Changelog](https://keepachangelog.com/), and this project adheres to [Semantic Versioning](https://semver.org/).

## [1.0.0] - 2026-02-24

This is the first official release of HelloID-Conn-SA-Full-Microsoft-EntraID-AccountDisable. This release includes functionality to disable Entra ID user accounts through HelloID Service Automation delegated forms.

### Added

• PowerShell data source to search for active Entra ID users with wildcard support across DisplayName, Mail, UserPrincipalName, and other user attributes
• Task to disable Entra ID user accounts using Microsoft Graph API with required Entra ID permissions
• Support for searching users across the entire Entra ID tenant
• Audit logging for all account disable operations
• Delegated form with user search and selection functionality
• All-in-one setup script for HelloID form deployment
• PowerShell data sources for generating user search tables with various attribute combinations
• Dynamic form configuration with search field validation and grid filtering support

### Changed

### Deprecated

### Removed
