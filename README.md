# AgilianX Organization Templates

This special repository contains organization-wide default community health files and issue templates for all AgilianX projects. Files in this repository are automatically used as defaults for any repository in the AgilianX organization that doesn't have its own versions.

## What's Included

- **Issue Templates**: Standardized templates for bugs, feature requests, and planned features
- **Pull Request Template**: A standard template for pull requests
- **Contributing Guidelines**: Organization-wide contribution standards
- **User Personas**: Standard personas referenced in feature planning

## How This Works

- Templates in this repository are used when repositories don't have their own custom templates
- Repository-specific templates take precedence over these organization defaults
- Links to documentation are kept repository-agnostic using absolute URLs

## For Repository Owners

### Using Organization Default Templates

To use these templates in your repository, you don't have to do anything special. The templates will be automatically available.

### Overriding Templates for a Specific Repository

If you need custom templates for your repository, simply create the equivalent files in your repository:

1. Create `.github/ISSUE_TEMPLATE/` directory in your repository
2. Add your custom templates there
3. Your templates will override the organization defaults

## Maintaining These Templates

When updating these templates:

1. Ensure links are organization-wide or use repository-relative paths
2. Test templates by creating test issues in repositories without custom templates
3. Notify repository owners of significant changes

## Community Health Files

The following community health files apply to all repositories:

- Contributing Guidelines (CONTRIBUTING.md)
- User Personas (docs/personas.md)
