# Alfred Workflows Collection

A curated collection of Alfred workflows for WordPress.com, Automattic, and general productivity tasks.

## Installation

### Quick Install
1. Download the workflow file (.alfredworkflow) you want from the `workflows/` folder
2. Double-click the downloaded file
3. Alfred will open and prompt you to install the workflow
4. Click "Import" to add it to your Alfred

### Bulk Install
To install all workflows at once:
1. Clone this repository: `git clone <repository-url>`
2. Navigate to the `workflows/` folder
3. Double-click each `.alfredworkflow` file you want to install

## Workflows

### WordPress.com & Automattic

#### AlfredMattic
Advanced workflow for Automattic employees with multiple integrations and features.
- **File**: `AlfredMattic.alfredworkflow`
- **Dependencies**: Node.js (bundled in workflow)

#### WordPress.com Site Searches
Quick search functionality for WordPress.com sites.
- **File**: `WordPress.com Site Searches.alfredworkflow`

#### WordPress.com User Searches
Search for WordPress.com users quickly.
- **File**: `WordPress.com User Searches.alfredworkflow`

#### WordPress.com User Links
Quick access to user-related links and tools.
- **File**: `WordPress.com User Links.alfredworkflow`

#### WordPress.com Support Articles Search
Search through WordPress.com support documentation.
- **File**: `WordPress.com Support Articles Search.alfredworkflow`

#### WordPress.com Theme Quick Links
Fast access to theme-related resources.
- **File**: `WordPress.com Theme Quick Links.alfredworkflow`

#### WordPress.com Internal Searches
Internal search tools for WordPress.com.
- **File**: `WordPress.com Internal Searches.alfredworkflow`

#### WordPress.com Jetpack Tests
Testing utilities for Jetpack.
- **File**: `WordPress.com Jetpack Tests.alfredworkflow`

#### WPcom University Searches
Search WordPress.com University resources.
- **File**: `WPcom University Searches.alfredworkflow`

#### Support Articles
Search all WordPress.com support articles locally with fuzzy matching and usage tracking.
- **Keyword**: `sa` - Search support articles
- **Keyword**: `saupdate` - Update local database
- **Keyword**: `sareset` - Reset usage statistics
- **File**: `Support Articles.alfredworkflow`
- **First Time Setup**: After installation, run `saupdate` in Alfred to download the support articles database
- **Features**:
  - Searches 600+ WordPress.com support articles
  - Fuzzy matching for better results
  - Usage tracking (frequently used articles rank higher)
  - No external dependencies - uses Python 3 standard library

#### Site Profiler
Quick domain query in the WordPress.com Site Profiler.
- **Keyword**: `sp`
- **Usage**: `sp example.com`
- **File**: `Site Profiler.alfredworkflow`

#### Plugin Search
Search for WordPress plugins.
- **File**: `Plugin Search.alfredworkflow`

#### Signups Validator
Validate signups and user data.
- **File**: `Signups Validator.alfredworkflow`

#### Transaction ID Search
Search for transaction IDs.
- **File**: `Transaction ID Search.alfredworkflow`

#### A8c Product Price Currency Checker
Check product prices across different currencies for Automattic products.
- **File**: `A8c Product Price Currency Checker.alfredworkflow`

#### Gravatar Search
Search Gravatar profiles by email, username, or hash.
- **Keyword**: `gra`
- **Usage**: `gra user@example.com` or `gra username`
- **File**: `Gravatar Search.alfredworkflow`

#### Account Checker
Check for an email address across Gravatar, WordPress.com Users, Store Admin, and Subscriptions — all in one go. Opens four tabs simultaneously so you can quickly verify account presence across all systems. Useful for data deletion requests and account lookups.
- **Keyword**: `acct`
- **Usage**: `acct user@example.com`
- **File**: `Account Checker.alfredworkflow`
- **Opens**:
  - Gravatar profile search
  - WP.com Store Admin (paid upgrades)
  - WP.com Network Users search
  - WP.com Subscriptions lookup

### Security & Development Tools

#### SecurityTrails DNS Lookup
Query historical DNS records from SecurityTrails.
- **Keyword**: `dnsrec`
- **Usage**: `dnsrec example.com [a|aaaa|mx|ns|txt|soa]`
- **File**: `SecurityTrails DNS Lookup.alfredworkflow`
- **API Key Required**: Yes (get from https://securitytrails.com/app/account)
- **Setup**:
  1. Install the workflow
  2. Open Alfred Preferences > Workflows
  3. Select "SecurityTrails DNS Lookup"
  4. Click the [x] icon (top right) to open configuration
  5. Add your API key for `SECURITYTRAILS_API_KEY`

#### Rewind Debugger LookUp
Quick lookup tool for Rewind debugging.
- **File**: `Rewind Debugger LookUp.alfredworkflow`

### Utilities

#### Fake Address Generator
Generate fake addresses for testing purposes.
- **File**: `Fake Address Generator.alfredworkflow`

## Security Notes

All workflows in this repository have been configured to protect sensitive information:
- API keys and tokens are NOT included in the exported workflows
- Users must configure their own API keys after installation
- No credentials or personal data are stored in the workflow files

## Requirements

- Alfred 5 or later (with Powerpack)
- macOS
- For specific workflows:
  - **AlfredMattic**: Node.js dependencies are bundled
  - **SecurityTrails DNS Lookup**: Requires SecurityTrails API key
  - **Python-based workflows**: Use system Python 3

## Contributing

Feel free to suggest improvements or report issues with any workflow.

## Author

Ricardo Ramos

## License

These workflows are provided as-is for use by Automattic employees and colleagues.
