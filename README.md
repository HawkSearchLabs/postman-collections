# HawkSearch Postman Collections
# Overview

This repository contains a series of Postman collections for use with HawkSearch, an AI-powered site search, merchandising, and product discovery platform designed for eCommerce, B2B, and content-rich websites. Learn more about HawkSearch here: [www.hawksearch.com/](https://www.hawksearch.com/).

These collections have been created for use with **Postman**, a popular testing platform for APIs. It can be downloaded from [www.getpostman.com](https://www.getpostman.com).

These collections let users quickly send pre-built API requests to set up, manage, and test their search environment without writing code. More information about HawkSearch's APIs can be found here: [HawkSearch v4.0 API](https://developerdocs.hawksearch.com/docs/hawksearch-v40-api). 

# Getting Started 
These collections are for use within a HawkSearch engine. If you do not have your own HawkSearch engine, you can set up your own via the QuickStart guide: [QuickStart: Getting Started](https://developerdocs.hawksearch.com/docs/quickstart-getting-started). 

To import a collection, `clone` this repository and open Postman. Select the `Import` option. When prompted by the pop-up, drag and drop or select the cloned repository folder. If successful, the collection will appear underneath the `Collections` tab. 

The Postman collections in this repository contain the following variables. Replace these environment variables with your engine-specific data. *It is highly recommended to download and import the HawkSearch Sample Environment to make managing these client variables easier*.
- YOUR_API_KEY / {{api_key}}
    - Found by following these instructions: https://developerdocs.hawksearch.com/reference/authentication
- YOUR_CLIENT_GUID / {{client_guid}}
    - Found by following these instructions: https://developerdocs.hawksearch.com/reference/authentication
- YOUR_INDEX_NAME / {{index_name}}
    - Returned via the `Get Current Index` or `Create Index` API call.

# Available Collections

- QuickStart
  - HawkSearch QuickStart 
- Indexing API
- Search API
- Recommendation API
- Dashboard API
- Tracking API
- QA and Testing
- Misc.
  - HawkSearch Sample Environment

## QuickStart 

Inside this section are Postman collections designed as a quick-start toolkit for setting up and testing a HawkSearch implementation. These collections guide users through the core workflow of creating fields and facets, building and managing an index, uploading product data, and executing search queries to validate the setup end-to-end. 

### HawkSearch Quickstart 
This Postman collection is designed to be used in tandem with the HawkSearch QuickStart guide, linked [here](https://developerdocs.hawksearch.com/docs/for-blank-engines). This guide has step by step instructions on using these API endpoints to populate a blank HawkSearch engine. The following collection is intended to be a starting point for beginners looking to use HawkSearch, and inlcudes some of HawkSearch's most commonly used API endpoints.

- **Bulk Field Creation** - Creates multiple fields. 
- **Create Single Field** - Creates a single field. 
- **Bulk Facet Creation** - Creates multiple facets. 
- **Create Single Facet** - Creates a single facet.
- **Create Index** - Creates a new index and returns its name. Learn [more](https://developerdocs.hawksearch.com/docs/indexing-api-examples#create:~:text=Create,-This).
- **Bulk Product Creation** - Creates multiple products within a specified index.
- **Create Single Product** - Creates a single product within a specified index.
- **Set Current Index** - Sets a specific index as the active index that HawkSearch will use for search queries. Learn [more](https://developerdocs.hawksearch.com/docs/indexing-api-examples#set-current-index:~:text=Set%20Current%20Index).
- **Get Current Index** - Retrieves the currently active index being used for search operations. Learn [more](https://developerdocs.hawksearch.com/docs/indexing-api-examples#get-current-index-name:~:text=Get%20Current%20Index%20Name).
- **View Indexes** - Returns a list of all indexes. Each engine has a maximum of one active index and one idle index. Learn [more](https://developerdocs.hawksearch.com/docs/indexing-api-examples#get-all-indexes:~:text=Get%20All%20Indexes).
- **Delete Index** - Deletes a specified index. Learn [more](https://developerdocs.hawksearch.com/docs/indexing-api-examples#delete-index:~:text=Delete%20Index,-This).
- **Search** - Retrieves search results of a given keyword in the specified index. Learn [more.](https://developerdocs.hawksearch.com/docs/search-api-examples#search-v2:~:text=Search%20V2)


## Indexing API

## Search API

## Recommendation API

## Dashboard API

## Tracking API

## QA and Testing

## Misc.

Miscellaneous utilities for Postman.

### HawkSearch Sample Environment

The HawkSearch Sample Environment defines a minimal configuration layer for running HawkSearch Postman collections, allowing the user to avoid manually entering values for API keys, index names, and client GUID. It is encouraged to expand upon this environment to suit your personal needs and include other variables as seen fit.
