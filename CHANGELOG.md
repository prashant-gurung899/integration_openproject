# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Changed
- Add application's support for Nextcloud 30
- Log admin configuration to  audit log (`/audit.log`)
- Improve button text visibility when selecting different background images in Nextcloud's UI

## 2.6.3 - 2024-04-17
### Changed
- This release expects OpenProject version 13.2 or newer
- Drop application's support for Nextcloud 25
- Add application's support for Nextcloud 29

## 2.6.2 - 2024-04-04
### Changed
- This release expects OpenProject version 13.2 or newer
- Improves form validation for creating workpackages from nextcloud.
- Fixes wrong option text while searching workpackage.
- Add quick link for `group folder` app when not downloaded and enabled (project folder setup).
- Adjust dashboard panel of `integration app` consistent to that dashboard panel of other nextcloud apps.
- Adjust padding for assignee avatar in `workpackage` template.
- Added setup and user guide documentation link for integration app.
- Added description for settings in admin and personal panel.

## 2.6.1 - 2024-02-19
### Changed
- This release expects OpenProject version 13.2 or newer
- Fixes: Signing terms and services for special user "OpenProject" when `terms_of_service` app is enabled
- Fixes: Error when fetching non-existent work package from `talk` app chat

## 2.6.0 - 2024-01-17
### Changed
- This release expects OpenProject version 13.2 or newer
- [What's Changed](https://github.com/nextcloud/integration_openproject/releases/tag/v2.6.0)

## 1.0.5 – 2021-06-28
### Changed
- stop polling widget content when document is hidden
- bump js libs
- get rid of all deprecated stuff
- bump min NC version to 22
- cleanup backend code

## 1.0.4 – 2021-04-27
### Fixed
- Avatar API URL

## 1.0.3 – 2021-04-27
### Changed
- improve activity notifications
- bump js libs

## 1.0.2 – 2021-04-26
### Changed
- cleaner avatar image response
[#1](https://github.com/eneiluj/integration_openproject/issues/1) @birthe

## 1.0.1 – 2021-04-21
### Changed
- Support NC 20
- bump js libs

## 1.0.0 – 2021-03-19
### Added
* the app
