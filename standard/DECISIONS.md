## Project: The Hazzard Continuum (Decision Document)

**Official Name:** The Hazzard Continuum
**Version:** 1.0
**Date:** June 7, 2025

### 1. Vision & Mission

To create a more logical, intuitive, and globally unified system for measuring daily life. The Hazzard Continuum simplifies the calendar, universalizes time, and re-centers temperature on human comfort. This application will serve as the primary tool for users to learn, adopt, and integrate this new standard into their lives, while maintaining full compatibility with existing global standards.

### 2. Core Principles

-   **Interoperability:** The Continuum is designed to be useful immediately, without requiring the rest of the world to change. The app will provide seamless conversion and comparison tools, enabling users to base their lives on the Continuum while collaborating effortlessly with those using the Gregorian system.
-   **Future-Proof Design:** As technology advances, the world shrinks. Supersonic travel and instant global communication make traditional timezones an obstacle. The Continuum's Universal Time is a robust system designed for a future where a person might experience multiple "timezones" in a single day, reducing confusion and simplifying global synchronization.
-   **Logical Consistency:** The system is built on patterns and simple math. This allows for quick mental calculations, such as determining the day of the week for a future date or scheduling international meetings without timezone errors.
-   **Human-Centric:** All aspects of the Continuum are designed to benefit the human experience. The calendar is predictable, time is unambiguous, and temperature is based on the intuitive feeling of hot and cold.
-   **English-Based Standardization:** The system uses standardized, English-based names for its components to ensure clarity and accessibility.

### 3. Feature Breakdown

#### 3.1. Main Dashboard

The at-a-glance home screen.

-   **Widgets:**
    -   **Date Widget:** Displays the current Hazzard Continuum date (e.g., **14 Quintilis, 2025**), the day of the week, and the corresponding Gregorian date for reference.
    -   **Time Widget:** Displays the current 24-hour UTC time with the sub-heading "Universal Time." Includes a visual 24-hour arc showing the user's local sunrise, solar noon, and sunset times in UTC.
    -   **Temperature Widget:** Displays the current Hazzen temperature (e.g., **2 H**) with a dynamic color background and a simple descriptor ("Pleasant," "Chilly," etc.).

#### 3.2. The Continuum Calendar Page

A deep dive into the new calendar system.

-   **User Story:** As a user, I want to explore the 13-month calendar to understand its structure, see how it relates to the Gregorian calendar, and appreciate its logical consistency.

-   **Features & Content:**
    -   **Interactive Calendar Component:** A full-screen calendar displaying the 13 months in their new order. Each month is a perfect 4x7 grid of 28 days.
        -   **Month Order & Names:**
            1.  March
            2.  April
            3.  May
            4.  June
            5.  Quintilis
            6.  Sextilis
            7.  September
            8.  October
            9.  November
            10. December
            11. January
            12. February
            13. **Gormanuary**
    -   **The Hazzard New Year:** The year begins on March 1st. The app will clearly explain this offset. For example, "The year 2026 in the Hazzard Continuum begins on March 1, 2026 (Gregorian) and ends on February 28, 2027 (Gregorian)."
    -   **Intermission Day(s):** The day(s) following Gormanuary 28th are marked as "Intermission." They are visually distinct, have no day of the week, and serve as a year-end holiday before the new year begins on March 1st.
    -   **Explanatory Text & Media:**
        -   **"Origins & Inspiration":** This section will credit the thinkers behind the system.
            -   It will feature **Dave Gorman's** explanation, noting that his popularization and perfection of the system inspired the 13th month's name, "Gormanuary."
            -   It will include an embedded link to his definitive YouTube video: `https://www.youtube.com/watch?v=vunESk53r5U`
            -   It will also give historical credit to **Moses B. Cotsworth** for the original 13x28 "International Fixed Calendar" concept.
    -   **Visualizations & Tools:**
        -   **Date Converter:** Convert any Gregorian date to its Continuum equivalent and vice-versa.
        -   **"The Date Calculator" (New Feature):** A powerful tool demonstrating the calendar's consistency.
            -   Input: "What day of the week is 53 days from now?" Output: "A Tuesday."
            -   Input: "What is the date 100 days from today?" Output: "June 16th."
            -   This leverages the predictable \(13 \times 28 + 1 = 365\) structure.

#### 3.3. The Universal Time Page

A deep dive into living on a single, global timezone.

-   **User Story:** As a user, I want to understand how to use Universal Time in my daily life and how it relates to the sun's position and my local schedule.

-   **Features & Content:**
    -   **Primary Clock & Day Arc:** The large UTC clock and the visual arc showing local sunrise/sunset remain key features.
    -   **Personal Schedule Converter:** Helps users translate their local time habits (e.g., "Wake up: 07:00") into Universal Time (e.g., "Your day begins at **12:00 UTC**").
    -   **Explanatory Text:**
        -   **"One Time for a Shrinking World":** This essay will explain the "why" behind Universal Time, focusing on the **Future-Proof Design** principle. It will use examples like planning a video call with someone on the other side of the world, or a future scenario of taking a supersonic flight from New York to London and wanting to know what time dinner will be upon arrival, all using a single, unambiguous time reference.

#### 3.4. The Hazzen Temperature Page

A deep dive into the human-centric temperature scale.

-   **User Story:** As a user, I want to understand the Hazzen scale so I can intuitively know what the weather feels like and how I should dress.

-   **Features & Content:**
    -   **The "Comfort-O-Meter" & "What to Wear" Widgets:** These visual tools remain the core of the page, directly supporting the **Human-Centric** principle.
    -   **Converter & Formulas:** The easy-to-use calculator for converting between Hazzen, Fahrenheit, and Celsius, with formulas displayed.
        -   From Fahrenheit: $$ H = \frac{F - 66}{4} $$
        -   From Celsius: $$ H = \frac{1.8 \times C - 34}{4} $$
    -   **Explanatory Text:**
        -   **"Temperature for Humans":** This text will explain the philosophy, emphasizing that while scientific scales are useful for science, the Hazzen scale is designed for daily life.

### 4. Open Development & The RFC Process

The Hazzard Continuum is intended to be a living standard.

-   **Public RFC (Request for Comments):** Before version 1.0 is finalized, the core concepts of the Continuum will be published as a formal RFC document.
-   **GitHub Repository:** A public GitHub repository will be created to host the RFC. This will be the official channel for the community to:
    -   Submit proposals for changes or improvements.
    -   Report inconsistencies.
    -   Discuss the philosophy and implementation of the system.
-   **App Integration:** The app will include a page or link that directs users to the GitHub repository, encouraging participation and making it clear that this is an open, community-influenced project.
