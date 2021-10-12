# product-changelog
This repository contains changelogs published for each new product release.

## Changelog writing rules
1. A changelog name corresponds to the release date.

2. A changelog may contain the following sections, depending on the changes:

    | Section                    | Desc.                                                                                                                   |
    |----------------------------|-------------------------------------------------------------------------------------------------------------------------|
    | **Announcements**          | If there is a specific announcement to communicate, it can be expressed here. (e.g. new version, new big feature, etc.) |
    | **New features**           | list new features.                                                                                                      |
    | **Improvements and fixes** | list improvements and fixes.                                                                                            |
    | **Unreleased**             | list unreleased changes, as customers can see what changes they might expect in coming releases.                         |

3. Each listed change has to be classed in one of the following category:
 
    | **CATEGORY**   | Desc.                                  |
    |----------------|----------------------------------------|
    | **ADDED**      | for new features.                      |
    | **CHANGED**    | for changes in existing functionality. |
    | **DEPRECATED** | for soon-to-be removed features.       |
    | **REMOVED**    | for now removed features.              |
    | **FIXED**      | for any bug fixes.                     |
    | **SECURITY**   | in case of vulnerabilities.            |

4. Changelog is for humans and not machines, do not hesitate to formulate sentences.

## Template
 [TEMPLATE.md](./TEMPLATE.md) can be used to create a new changelog.

## Sources
Changelog rules are based on the following articles [Keep a changelog](https://keepachangelog.com/en/1.0.0/)