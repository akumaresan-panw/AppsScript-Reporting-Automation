Automated Reporting & Insight Engine for Google Workspace
=========================================================

1\. Project Overview
--------------------

This project provides a powerful framework for transforming static, repetitive management reporting into a dynamic, data-driven, and intelligent workflow. By leveraging Google Apps Script and Gemini, this system automates the generation of commentary and the population of Google Slides, Docs, and Sheets.

The core philosophy is to move beyond simple automation of tasks to the **amplification of executive focus**, allowing analysts to spend less time on data administration and more time on strategic decision making.

2\. The Core Problem Solved
---------------------------

In many organizations, the process of creating weekly or quarterly business reviews is highly manual, repetitive, and prone to error. Analysts spend hours copying and pasting data, updating commentary, and formatting slides. This project solves three key problems:

-   **Inefficiency:** Eliminates the time-consuming manual labor of updating recurring reports.

-   **Data Inconsistency:** Ensures that all reports are generated from a single, centralized source of truth, eliminating version control issues and data discrepancies.

-   **Surface-Level Reporting:** Moves beyond simply reporting numbers to actively guiding the user in analyzing *what those numbers mean*.

3\. System Architecture
-----------------------

The platform is built on a synergistic relationship between four key Google Workspace tools:

**Google Sheets**

 |

**The Data Abstraction Layer**

 |


**Apps Script**

 |

**The Automation Engine**

|

**Slides & Docs**

 |

**The Presentation Layer**

 |

The final output destinations containing simple, named placeholders (e.g., `[EC1]`). Formatting is driven by markers (`@@BOLD@@`, `@@COLOR@@`, etc.) from the Sheets script.


4\. Key Features
----------------

-   **Automated Commentary Generation:** Reads raw data from a Google Sheet and constructs complex, formatted narrative commentary.

-   **Multi-Format Placeholder Replacement:** Updates placeholders in Google Slides and Google Docs with the generated text.

-   **Dynamic Text Formatting:** Supports conditional coloring (e.g., green for positive, orange for negative) and bolding of specific text segments using a marker-based system.

-   **"Analysis Co-pilot" Sidebar:** A powerful UI within Google Slides that generates deep, context-rich analytical prompts for the user to explore with Gemini.

-   **Centralized Configuration:** All placeholders, data cell locations, and analytical questions are managed in the script or a simple sheet, making the system easy to update and maintain.


This final architecture represents a true enterprise-grade solution that not only automates reporting but also delivers proactive, data-driven intelligence to the business. Visit this site to learn how to deploy for your own use case: https://akumaresan-panw.github.io/AppsScript-Reporting-Automation/
