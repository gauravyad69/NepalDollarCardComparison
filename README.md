# Nepal Bank Dollar Card Fee Comparison

This repository contains a comprehensive comparison of dollar card services provided by various banks in Nepal. The data includes details on issuance fees, annual fees, loading fees, transaction fees, and more. This README provides an overview of the dataset and guidelines for contributing.

[The Actual Comparison Can Be Found Here](https://github.com/gauravyad69/NepalDollarCardComparison/blob/main/CARDS.md)

## Overview

The dataset provides the following details for each bank:

- **Bank Name**: Name of the bank providing the dollar card.
- **Issuance Fee**: Fee charged for issuing the dollar card.
- **Annual Fee**: Recurring annual fee, if applicable.
- **Loading Fee**: Fee for loading funds onto the card.
- **Minimum Load**: Minimum amount required for loading the card.
- **Maximum Load/Year**: Annual maximum load limit.
- **Transaction Fee**: Fee charged per transaction.
- **USD Earner Suitability**: Whether the card supports USD earning.
- **Validity (Years)**: Card validity period.
- **Remarks**: Additional features or conditions.

## Example Data Format, [The Actual Comparison Can Be Found Here](https://github.com/gauravyad69/NepalDollarCardComparison/blob/main/CARDS.md)

The data is structured as follows:

| **Bank Name**           | **Issuance Fee**                 | **Annual Fee** | **Loading Fee** | **Minimum Load** | **Maximum Load/Year** | **Transaction Fee**                        | **USD Earner**            | **Validity (Years)** | **Remarks**                                              |
|--------------------------|-----------------------------------|----------------|-----------------|------------------|-----------------------|--------------------------------------------|---------------------------|-----------------------|-----------------------------------------------------------|
| Kumari Bank             | Rs. 500                          | Nil            | Rs. 500         | Nil              | $500                 | Nil                                        | No                        | 5                     |                                                       |
| Nabil Bank              | Rs. 1000 (1st load free)         | Nil            | Rs. 500         | Nil              | $500                 | 1% cross-border + 0.5% or $0.50, whichever is higher | Yes                       | 4                     | Easy load on request at nearest branch                  |
| Everest Bank            | $5 (Virtual) / $10 (Physical)    | Nil            | Nil             | Nil              | $500                 | Same as Nabil                              | No                        | 4                     |                                                       |

## Features

- **Ranking of Banks**: Highlighted top performers based on customer convenience and fee structures.
- **"Winners" Section**: Banks offering the best overall experience despite high fees.
- Data easily extendable for new banks or updated fee structures.

## How to Use

- Clone this repository:
  ```bash
  git clone https://github.com/yourusername/nepal-bank-dollar-card-comparison.git
  ```
- Open the dataset file to view the comparison.
- Use the table to choose the best dollar card for your needs.

## Contribution Guidelines

We welcome contributions to improve and update this dataset. Please follow the steps below:

1. **Fork the Repository**: Click the "Fork" button on the top-right corner of this page.
2. **Update the Dataset**:
   - Add new banks or update existing data.
   - Ensure the data adheres to the format described in the "Example Data Format" section.
3. **Create a Pull Request**: Submit your changes for review.

### Requirements for Contributions

- Ensure all monetary values are accurate and in the appropriate currency.
- Add clear remarks or notes for any special conditions.
- Include sources or references for any updates.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or feedback, please open an issue or contact the repository maintainer.

---

### Notes for Scalability

- Future updates to the dataset can be automated using a structured CSV or JSON file.
- The table structure allows for easy addition or removal of columns as new features are introduced.
