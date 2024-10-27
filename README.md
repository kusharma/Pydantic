# Pydantic use examples in Sustainability reports

![Pydantic](images/Pydantic_logo.png)

This project leverages **Pydantic** to create structured, validated models for handling sustainability data, focusing on metrics relevant to SwissRe. It ensures data reliability by validating fields for investments, emissions reduction, ESG scores, and climate risks, supporting high-quality data integration for further analysis and reporting.

## Project Overview

This project provides:

- **Validated Data Models**: Includes Pydantic models for:
  - **Green Bond Investment**: Structured data model for tracking investment details in green bonds.
  - **GHG Emissions Reduction**: Validates emission reduction targets, including base year and current reduction percentage.
  - **ESG Score**: Ensures standardization of company names and ESG scoring format.
  - **Climate Risk Assessment**: Consistency checks between risk level and mitigation score.
- **Error Handling**: Models include custom validation rules that trigger errors for inconsistencies, ensuring only accurate data moves through the pipeline.

## Key Components

### Models

- **GreenBondInvestment**: Fields for bond type, amount invested, and date of investment.
- **GHGReduction**: Fields for target year, base year emissions, and percentage reduction achieved.
- **ESGData**: Handles ESG data with pre-validation and post-validation for formatting consistency.
- **ClimateRiskModel**: Enforces relationships between risk levels and mitigation scores.

### Example Usage

The notebook includes examples of each model, illustrating how to create, validate, and handle data entries.

### Data Display

Data from each model can be displayed in tabulated form, making it easier to review and interpret validated information.

## License

This project is licensed under the MIT License.
