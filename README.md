# banner_uh_salesforce_adm_upay

Salesforce-based admissions app integration with TouchNet uPay.

## Overview

This repository hosts a static HTML test harness via [GitHub Pages](https://universityofhawaii.github.io/banner_uh_salesforce_adm_upay/) for verifying the configuration of the 10 UH campus TouchNet uPay test sites (`https://epay.hawaii.edu:8443/C24372test_upay/web/index.jsp`).

## Test uPay Sites

| Code | uPay Site Name | Site ID | Campus | Type | Fee |
| :--- | :--- | :---: | :--- | :---: | ---: |
| **HAW** | `ADM_APP_HAW` | `257` | Hawaiʻi Community College | CC | $25 |
| **HIL** | `ADM_APP_HIL` | `258` | University of Hawaiʻi at Hilo | U | $50 |
| **HON** | `ADM_APP_HON` | `259` | Honolulu Community College | CC | $25 |
| **KAP** | `ADM_APP_KAP` | `260` | Kapiʻolani Community College | CC | $25 |
| **KAU** | `ADM_APP_KAU` | `261` | Kauaʻi Community College | CC | $25 |
| **LEE** | `ADM_APP_LEE` | `262` | Leeward Community College | CC | $25 |
| **MAN** | `ADM_APP_MAN` | `263` | University of Hawaiʻi at Mānoa | U | $70 |
| **MAU** | `ADM_APP_MAU` | `264` | University of Hawaiʻi Maui College | CC | $25 |
| **WIN** | `ADM_APP_WIN` | `265` | Windward Community College | CC | $25 |
| **WOA** | `ADM_APP_WOA` | `266` | University of Hawaiʻi – West Oʻahu | U | $50 |

## Usage

Open the [GitHub Pages test site](https://universityofhawaii.github.io/banner_uh_salesforce_adm_upay/) (or open `index.html` locally) and click any campus button to submit a `POST` request with the corresponding `UPAY_SITE_ID` in a new tab.
