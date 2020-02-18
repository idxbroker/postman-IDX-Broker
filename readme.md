# IDX Broker API and Postman

This repo contains collections for use with Postman and the IDX Broker API.

The collections vary in size and tests. Collections are created for specific versions of this API.

## Requirements

To pass all tests:
* Environment variable url
* Environment variables for request headers
* A valid IDX Broker Client API key is required for non partner calls.
* A valid IDX Broker Partner API key is required for partner calls.
* An account with a featured listing is required for use in the collection runner.

Note: Some endpoints may fail if they are prohibited from use for an MLS. Your response coude should indicate the request was not allowed.

## Install

Ddownload a collection then import to your postman.

Download an environment and import to your postman.

If you don't have postman you might want to get it because it's awesome.

[Postman](https://www.getpostman.com/)


## Testing

There is a sample of tests in this repo. You can write your own tests based on my samples and or with the aid of the postman docs.

[Postman docs](https://www.getpostman.com/docs/writing_tests)
