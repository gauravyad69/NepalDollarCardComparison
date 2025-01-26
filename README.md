# Nepal Bank Dollar Card Fee Comparison

This repository contains a comprehensive comparison of dollar card services provided by various banks in Nepal. The data includes details on issuance fees, annual fees, loading fees, transaction fees, and more. This README provides an overview of the dataset and guidelines for contributing.


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



## Features

- **Ranking of Banks**: Highlighted top performers based on customer convenience and fee structures.
- **"Winners" Section**: Banks offering the best overall experience despite high fees.
- Data easily extendable for new banks or updated fee structures.


##  [The Actual Comparison Can Be Found Here](https://github.com/gauravyad69/NepalDollarCardComparison/blob/main/CARDS.md)

## How to Use

- Clone this repository:
  ```bash
  git clone https://github.com/yourusername/nepal-bank-dollar-card-comparison.git
  ```
- Open the dataset file to view the comparison.
- Use the table to choose the best dollar card for your needs.

## Contribution Guidelines

##Example Data Set
```[
  {
    "bankName": "Example Bank",
    "issuanceFee": "Rs. 500",
    "annualFee": "Nil",
    "loadingFee": "Rs. 500",
    "minimumLoad": "Nil",
    "maximumLoadPerYear": "$500",
    "transactionFee": "Nil",
    "usdEarner": "No",
    "validityYears": 5,
    "knownIssues": "Example Issue, Example Issue",
    "features": "Online Load, Examle Feature",
    "totalTimeOfIssuance": "15 Days",
    "remarks": "",
    "lastUpdated": "2024-01-26"
  },
]
```

We welcome contributions to improve and update this dataset. Please follow the steps below:

1. **Fork the Repository**: Click the "Fork" button on the top-right corner of this page.
2. **Update the Dataset**:
   - Add new banks or update existing data at [cards.json](https://github.com/gauravyad69/NepalDollarCardComparison/blob/main/cards.json), The update of the table is automated so you don't have to worry about that.
   - Ensure the data adheres to the format described in the "Example Data Set" section.
3. **Create a Pull Request**: Submit your changes for review.

### Requirements for Contributions

- Ensure all monetary values are accurate and in the appropriate currency.
- Add clear remarks or notes for any special conditions.
- Include sources or references for any updates.

## License

This project is licensed under the GNU License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or feedback, please open an issue or contact the repository maintainer.

---

### Notes for Scalability

- ~~Future updates to the dataset can be automated using a structured CSV or JSON file.~~, Done
- The json structure allows for easy addition or removal of data as new features are introduced.
