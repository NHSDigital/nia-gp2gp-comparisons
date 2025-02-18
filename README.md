# NIA GP2GP Comparisons

Compares two [FHIR JSON bundles][bundle] to identify discrepancies.

> [!NOTE]  
> This repository has been archived now that the GP2GP FHIR Adaptor assurance for First of Type has completed

> [!WARNING]  
> This repository contains file paths which are not valid on Windows. Cloning from a Windows device may result in errors. See GitHub issue #7

## Requirements

- [Node.JS] version >= 15

[Node.JS]: https://nodejs.org

## Usage

See `./multi-compare-tpp.sh` for usage examples.

See `./raw-compare-results` for output examples.

[bundle]: https://developer.nhs.uk/apis/gpconnect-1-6-0/access_documents_development_bundle.html

## Running the comparator Unit Tests

Run `npm install`

Then run `npm test`
