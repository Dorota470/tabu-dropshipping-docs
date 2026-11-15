# TABU Dropshipping

## Application overview

TABU Dropshipping is a private Windows-based integration project developed for the account owner's own sales operations.

## Purpose

The application is designed to integrate product data from the TABU wholesale supplier with the owner's Allegro seller account.

## Planned functionality

- Import product catalogue data from TABU XML files.
- Synchronize product prices and stock quantities.
- Calculate selling prices using configurable pricing rules.
- Read and manage the owner's Allegro offers.
- Support automated offer creation and updates.

## Authentication

The application is designed to use Allegro REST API with OAuth 2.0 Authorization Code Flow.

## API permissions

The registered application requests:
- allegro:api:sale:offers:read
- allegro:api:sale:offers:write

## Environment

The integration is developed for Windows and runs locally on the account owner's computer.

## Privacy

This is a private application for the owner's own sales operations. It is not intended to provide services to other sellers. API credentials and access tokens are stored locally and are not published in this repository.

## Development status

The TABU XML import and CSV export component is operational. Allegro API integration and automated marketplace operations are under development.
