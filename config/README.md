# Configuration Directory

This directory contains all configuration files for the Transform Videos AI project.

## Structure

- `credentials/` - API keys and sensitive data (Git ignored)
- `environments/` - Environment-specific configurations
- `templates/` - Configuration templates

## Setup

1. Copy template files from `templates/` to appropriate environment folders
2. Add your API credentials to `credentials/` directory
3. Configure platform-specific settings as needed

## Security

- Never commit files from the `credentials/` directory
- Use environment variables for sensitive data
- Regularly rotate API keys
