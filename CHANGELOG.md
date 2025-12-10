# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.0.3] - 2020-12-10
### Added
- Tracking url
### Changed
- Structure of tracking info

## [3.0.2] - 2025-12-10
### Changed
- Allow inheritance of AltapayMerchantAPI

## [3.0.1] - 2020-11-23
### Changed
- Corrected filenames to match classnames

## [3.0.0] - 2020-11-03
### Added
- Support for installation and autoloading via composer
- Document all function arguments
- Added DynamicJavascriptUrl on PensioCreatePaymentRequest
### Changed
- Rebranding to AltaPay
- Removed hardcoded require_once
- Tests now use PHPUnit and can be run publically
### Fixes
- Correct minor type issues
- Handle non conformant http header casing

## [2.1.0] - 2020-05-15
### Added
- Added new parameters, according to the payment gateway Klarna Payments updates, for the following:
    - Create payment request
    - Capture and refund
### Changed
- Code refactored according to latest coding standards

## [2.0.0] - 2020-05-14
### Added
- New paramaters added to the createPaymentRequest and captureReservation endpoints
- Additional customer information sent to the payment gateway
### Changed
- Rebranding to Valitor
- Improvements on various API endpoints (i.e. getPayment)

## [1.0.6] - 2018-10-09
### Changed
- ChargeSubscription can take reconciliationIdentifier

## [1.0.5] - 2018-10-03
### Added
- Expose CreatedDate and UpdatedDate for payments

## [1.0.4] - 2018-06-22
### Added
- New child element [IsTokenized] in Transaction

## [1.0.3] - 2018-03-16
### Added
- Add composer.lock
### Fixed
- Typo in package name

## [1.0.2] - 2018-02-28
### Fixed
- PensioCallbackHandler - xml body response with error and Transactions element

## [1.0.1] - 2018-02-21
### Fixed
- PensioCallbackHandler - xml body response without Transaction element

## [1.0.0] - 2018-02-16
### Changed
- Set the base for the version number

## [0.1.0] - 2018-02-16
### Added
- New child element [PaymentSource] in Transaction

## [0.0.1] - 2018-02-16
### Added
- Created the change log
