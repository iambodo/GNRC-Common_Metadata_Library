# Common metadata library - Installation Guide { #gnrc-installation }

This document includes an installation guide for the common metadata library.

System default language: English

Available translations: French, Spanish, Portuguese, Arabic

## Overview

### DHIS2.35

=== "Common metadata library (complete)"

    ```json
    "package": {
        "DHIS2Build": "35d663a",
        "DHIS2Version": "2.35.11",
        "code": "GNRC00",
        "description": "",
        "lastUpdated": "",
        "locale": "en",
        "name": "Common metadata library (complete)",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Common tracker metadata library"

    ```json
    "package": {
        "DHIS2Build": "35d663a",
        "DHIS2Version": "2.35.11",
        "code": "GNRCT0",
        "description": "",
        "lastUpdated": "20220302T113237",
        "locale": "en",
        "name": "Common tracker metadata",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Core Case profile"

    ```json
    "package": {
        "DHIS2Build": "35d663a",
        "DHIS2Version": "2.35.11",
        "code": "GNRCTC",
        "description": "",
        "lastUpdated": "20220302T113237",
        "locale": "en",
        "name": "Core case profile",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Common aggregate metadata"

    ```json
    "package": {
        "DHIS2Build": "834b25f",
        "DHIS2Version": "2.35.8",
        "code": "GNRCA0",
        "description": "",
        "lastUpdated": "20220228T152841",
        "locale": "en",
        "name": "Common aggregate metadata",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

### DHIS2.36

=== "Common metadata library (complete)"

    ```json
    "package": {
        "DHIS2Build": "aa38c7f",
        "DHIS2Version": "2.36.8",
        "code": "GNRC00",
        "description": "",
        "lastUpdated": "",
        "locale": "en",
        "name": "Common metadata library (complete)",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Common tracker metadata library"

    ```json
    "package": {
        "DHIS2Build": "aa38c7f",
        "DHIS2Version": "2.36.8",
        "code": "GNRCT0",
        "description": "",
        "lastUpdated": "20220302T113237",
        "locale": "en",
        "name": "Common tracker metadata",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Core Case profile"

    ```json
    "package": {
        "DHIS2Build": "aa38c7f",
        "DHIS2Version": "2.36.8",
        "code": "GNRCTC",
        "description": "",
        "lastUpdated": "20220302T113237",
        "locale": "en",
        "name": "Core case profile",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Common aggregate metadata library"

    ```json
    "package": {
        "DHIS2Build": "aa38c7f",
        "DHIS2Version": "2.36.8",
        "code": "GNRCA0",
        "description": "",
        "lastUpdated": "20220228T152841",
        "locale": "en",
        "name": "Common aggregate metadata",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "DHIS2.37"

=== "Common metadata library (complete)"

    ```json
    "package": {
        "DHIS2Build": "aa38c7f",
        "DHIS2Version": "2.36.8",
        "code": "GNRC00",
        "description": "",
        "lastUpdated": "",
        "locale": "en",
        "name": "Common metadata library (complete)",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Common tracker metadata library"

    ```json
    "package": {
        "DHIS2Build": "a7328e1",
        "DHIS2Version": "2.37.3",
        "code": "GNRCT0",
        "description": "",
        "lastUpdated": "20220302T113237",
        "locale": "en",
        "name": "Common tracker metadata",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Core Case profile"

    ```json
    "package": {
        "DHIS2Build": "a7328e1",
        "DHIS2Version": "2.37.3",
        "code": "GNRCTC",
        "description": "",
        "lastUpdated": "20220302T113237",
        "locale": "en",
        "name": "Core case profile",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

=== "Common aggregate metadata library"

    ```json
    "package": {
        "DHIS2Build": "a7328e1",
        "DHIS2Version": "2.37.3",
        "code": "GNRCA0",
        "description": "",
        "lastUpdated": "20220228T152841",
        "locale": "en",
        "name": "Common aggregate metadata",
        "type": "GEN",
        "version": "1.0.0"
    }
    ```

## Installation

The table below will help you identify which metadata file/s are relevant for your implementation:

| Metadata file                      | Application area |
|------------------------------------|------------------|
| Common metadata library (complete) | DHIS2 environment containing both tracker and aggregate modules, utilisation of published metadata packages, development of custom programs and modules that utilise common metadata |
| Common tracker metadata library    | Tracker-based DHIS2 environment, utilisation of published tracker packages, development of custom tracker programs that utilise common tracker metadata |
| Core case profile                  | Tracker-based DHIS2 environment, development of custom tracker programs that utilise core case profile data (Person) |
| Common aggregate metadata          | Utilisation of published aggregate modules, development of custom aggregate modules that utilise common aggregate metadata |

Carefully read through each section of the installation guide before importing the metadata files into your DHIS2 instance!

### Importing common metadata into a new DHIS2 instance

The application area of the DHIS2 instance will help you identify, which metadata file/s to import. The table below will 

### Importing common metadata into an existing DHIS2 instance


