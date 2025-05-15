# FRTB Risk Factor Eligibility Test (RFET) in Excel and Python

## Project Summary

This repository contains an Excel and Python-based implementation of the **Risk Factor Eligibility Test (RFET)** as defined under the **FRTB (Fundamental Review of the Trading Book)** rules from Basel III. The test is used to determine whether a risk factor is **modellable** or **non-modellable** for the Internal Models Approach (IMA) for market risk capital.

## Key Features

- Excel-based RFET framework for internal and regulatory use
- Implements the 24-observation rule within 1-month windows
- Highlights modellable vs. non-modellable risk factors
- Easily auditable and modifiable by business users

## How it Works

Under FRTB:
- A risk factor is modellable if there are **≥24 real price observations in the past year**, with **no more than 1 month between observations**.
- This model uses trade/quote data and checks eligibility for each risk factor.

## Project Structure

