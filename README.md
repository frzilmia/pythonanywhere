# Factorial Calculator Testing Project

This repository contains exploratory testing documentation for the Factorial Calculator web application hosted at https://qainterview.pythonanywhere.com/.

## Project Overview

This project documents comprehensive testing performed on a factorial calculator web application, including functionality testing, input validation analysis, UI/UX evaluation, and security considerations.

## Contents

- **`factorial_calculator_testing_report.md`** - Detailed exploratory testing report covering:
  - Functional testing results
  - Input validation analysis
  - UI/UX evaluation
  - Error handling assessment
  - Security and performance observations
  - Issues identification and recommendations

## Application Under Test

**URL:** https://qainterview.pythonanywhere.com/  
**Description:** A web-based factorial calculator with a simple interface for calculating factorial values  
**Testing Date:** October 30, 2025  

## Key Findings

### ✅ Working Features
- Correct factorial calculations for valid positive integers
- Clean, intuitive user interface
- Basic navigation functionality
- HTTPS security implementation

### ⚠️ Issues Identified
- **Critical:** No input validation for invalid inputs
- **Critical:** Mathematical errors with negative numbers
- **Medium:** Incomplete legal documentation (Terms & Privacy)
- **Medium:** Limited accessibility features
- **Minor:** Missing user guidance for valid inputs

## Testing Approach

The testing was conducted using **exploratory testing methodology**, covering:

1. **Functional Testing** - Verifying correct factorial calculations
2. **Input Validation** - Testing boundary conditions and invalid inputs
3. **UI/UX Testing** - Evaluating user interface and navigation
4. **Error Handling** - Assessing application response to invalid scenarios
5. **Security Testing** - Basic security considerations and input sanitization
6. **Performance Testing** - Application behavior with large numbers

## Test Results Summary

- **Total Test Cases:** 12
- **Passed:** 6 ✅
- **Failed:** 2 ❌
- **Requires Investigation:** 4 🔍
- **Overall Risk Level:** Medium

## Recommendations

### Immediate Priority
1. Implement proper input validation
2. Add clear error messaging
3. Set reasonable calculation limits
4. Complete legal documentation

### Future Enhancements
1. Improve accessibility features
2. Add mobile responsiveness testing
3. Implement security hardening
4. Enhance user experience with better feedback

## Repository Structure

```
pythonanywhere/
├── README.md                                    # This file
└── factorial_calculator_testing_report.md      # Detailed testing report
```

## Usage

This repository serves as documentation for QA testing activities. The testing report can be used by:

- **Development Teams** - Understanding application issues and improvement areas
- **QA Teams** - Reference for testing methodologies and comprehensive coverage
- **Product Teams** - Prioritizing feature improvements and bug fixes
- **Stakeholders** - Assessing application quality and risk levels

## Testing Tools & Environment

- **Browser Testing:** Manual testing across different browsers
- **Testing Type:** Black-box exploratory testing
- **Documentation:** Markdown-based reporting
- **Version Control:** Git with GitHub hosting

## Contributing

This repository documents testing findings and can be extended with:
- Additional test cases
- Automated testing scripts
- Updated findings from retesting
- Performance benchmarking results

## Contact

For questions about this testing documentation, please refer to the detailed findings in the testing report or create an issue in this repository.

---

**Note:** This is a testing documentation repository. The actual application being tested is hosted separately at https://qainterview.pythonanywhere.com/