# NEXT CHANGELOG

## [Unreleased]

### Added
- Added DCO (Developer Certificate of Origin) check workflow for pull requests to ensure all commits are properly signed-off
- Added support for SSL client certificate authentication via parameter: SSLTrustStoreProvider
- Added case-insensitive column name support for JDBC ResultSet operations

### Updated
- 

### Fixed
- Fixed Bouncy Castle registration conflicts by using local provider instance instead of global security registration.
- Fixed Azure U2M authentication issue.

---
*Note: When making changes, please add your change under the appropriate section with a brief description.* 