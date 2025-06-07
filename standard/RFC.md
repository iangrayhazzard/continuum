# The Hazzard Continuum: Formal Specification

-   **Version:** 1.0
-   **Status:** Proposal
-   **Date:** June 7, 2025

## Abstract

The Hazzard Continuum is a comprehensive system for measuring date, time, and temperature, designed to be more logical, consistent, and human-centric than existing standards. It is comprised of three components: the Continuum Calendar, a perennial 13-month calendar; Universal Time (UT), a single global time standard; and the Hazzen (H) temperature scale, based on human comfort. This document provides the formal specification for Version 1.0 of the Hazzard Continuum.

## Table of Contents

1.  [Introduction](#1-introduction)
    1.  [Purpose](#11-purpose)
    2.  [Core Principles](#12-core-principles)
    3.  [Terminology](#13-terminology)
2.  [The Continuum Calendar](#2-the-continuum-calendar)
    1.  [Year Structure](#21-year-structure)
    2.  [Month Structure](#22-month-structure)
    3.  [Month Naming and Order](#23-month-naming-and-order)
    4.  [Week Structure](#24-week-structure)
    5.  [The New Year](#25-the-new-year)
3.  [Universal Time (UT)](#3-universal-time-ut)
    1.  [Definition](#31-definition)
    2.  [Notation](#32-notation)
    3.  [Principle of Application](#33-principle-of-application)
4.  [The Hazzen Temperature Scale (H)](#4-the-hazzen-temperature-scale-h)
    1.  [Definition](#41-definition)
    2.  [The Unit](#42-the-unit)
    3.  [Reference Points](#43-reference-points)
    4.  [Conversion Formulas](#44-conversion-formulas)
5.  [Governance and Evolution](#5-governance-and-evolution)

---

## 1. Introduction

### 1.1. Purpose

This document establishes the official rules and definitions for the Hazzard Continuum system. It is intended to be the single source of truth for software implementations, conversions, and discussions related to the standard.

### 1.2. Core Principles

-   **Interoperability:** The system is designed for seamless conversion to and from Gregorian standards.
-   **Future-Proof Design:** The system is built to reduce complexity in an increasingly interconnected and fast-paced world.
-   **Logical Consistency:** The system is founded on simple patterns and mathematics to allow for intuitive calculations.
-   **Human-Centric:** The system is designed to be practical and intuitive for everyday human life.
-   **English-Based Standardization:** The system uses clear, English-based names for its components.

### 1.3. Terminology

-   **Continuum Year:** A full cycle of the Continuum Calendar.
-   **Intermission Day:** A year-end day that exists outside of any month or week.
-   **Universal Time (UT):** The single, global time standard.
-   **Hazzen (H):** The unit of measurement for the temperature scale.

## 2. The Continuum Calendar

### 2.1. Year Structure

A standard Continuum Year consists of **365** days. A Continuum Leap Year consists of **366** days.

The calendar is composed of 13 months of 28 days each (\(13 \times 28 = 364\) days), plus one or two Intermission Days.

-   The 365th day of every year is designated **Intermission Day**.
-   In a Leap Year, the 366th day is designated **Leap Intermission Day**. A Leap Year occurs in any year whose number is divisible by 4, except for years divisible by 100 but not by 400.
-   Intermission Days do not belong to any month and do not have an assigned day of the week, thus preserving the perennial nature of the calendar.

### 2.2. Month Structure

The Continuum Calendar consists of **13** months. Each month contains exactly **28** days, structured as four perfect weeks.

### 2.3. Month Naming and Order

The 13 months of the Continuum Calendar are ordered and named as follows:

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
13. Gormanuary

### 2.4. Week Structure

A week consists of 7 days. The days of the week are: Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday.

-   The 1st day of every month is always a **Sunday**.
-   The 28th day of every month is always a **Saturday**.

### 2.5. The New Year

The first day of the Continuum Year (March 1st) corresponds to **March 1st** of the Gregorian calendar. The Continuum year number is the same as the Gregorian year number during this period of overlap.

## 3. Universal Time (UT)

### 3.1. Definition

Universal Time (UT) is defined by and equivalent to **Coordinated Universal Time (UTC)**, as maintained by the International Bureau of Weights and Measures (BIPM).

### 3.2. Notation

Time is expressed in a 24-hour format, from `00:00:00` to `23:59:59`. The standard notation is **HH:MM:SS**.

### 3.3. Principle of Application

Universal Time is applied uniformly across the globe. There are no timezones, daylight saving adjustments, or other local offsets. An event scheduled for **14:00 UT** occurs at that single moment for all observers worldwide, regardless of their geographical location or the local position of the sun.

## 4. The Hazzen Temperature Scale (H)

### 4.1. Definition

The Hazzen scale is a relative temperature scale designed to be intuitive to human comfort. Positive values represent warmth, negative values represent coolness, and zero is set to a comfortable indoor room temperature.

### 4.2. The Unit

The unit of the scale is the **Hazzen**, denoted by the symbol **H**.

### 4.3. Reference Points

-   The primary reference point is **\(0 \text{ H}\)**, which is defined as **\(66^\circ\text{F}\)** (Fahrenheit).
-   The scale interval is defined as **\(1 \text{ H} = 4^\circ\text{F}\)**.

### 4.4. Conversion Formulas

Let \(H\) be the temperature in Hazzen, \(F\) be the temperature in Fahrenheit, and \(C\) be the temperature in Celsius.

-   **From Fahrenheit to Hazzen:**
    $$ H = \frac{F - 66}{4} $$
-   **From Hazzen to Fahrenheit:**
    $$ F = (H \times 4) + 66 $$
-   **From Celsius to Hazzen:**
    $$ H = \frac{(C \times \frac{9}{5} + 32) - 66}{4} = \frac{1.8 \times C - 34}{4} $$
-   **From Hazzen to Celsius:**
    $$ C = \frac{((H \times 4) + 66) - 32}{1.8} = \frac{4 \times H + 34}{1.8} $$

## 5. Governance and Evolution

The Hazzard Continuum is an open standard. Proposals for changes or amendments to this specification should be submitted to the official project repository. All proposals will be subject to community review and discussion before being considered for inclusion in future versions of the standard.
