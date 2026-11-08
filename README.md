# Quality-Control-System

# Coating Process Monitoring and Customer-Specific Quality Control System

## Project Overview

This project focuses on monitoring coating and baking operations while maintaining customer-specific quality requirements.

The system tracks process cycles for each production batch, validates whether the required process sequence is followed and checks final inspection measurements against customer specifications.

It provides batch-wise process information, quality status and deviation alerts to support production monitoring and product quality.

## Project Motivation

Different customers and products may have different coating requirements.

Maintaining the correct number of coating and baking cycles and ensuring that the final coating meets the specified quality limits are important for consistent product quality.

This project focuses on bringing process monitoring and customer-specific quality inspection together in one system.

## Main Objectives

- Monitor coating and baking cycles for each batch.
- Configure requirements based on customer and product specifications.
- Identify missing, repeated or incorrectly sequenced operations.
- Compare coating thickness with specified limits.
- Maintain batch-wise process and inspection records.
- Generate alerts when process or quality deviations are detected.

## Main Features

### 1. Batch Registration
Register each production batch using batch ID, customer ID and product details.

### 2. Customer-Specific Configuration
Load the required coating cycles, baking cycles and coating thickness limits based on customer and product requirements.

### 3. Process Monitoring
Track completed coating and baking operations against the required cycle counts.

### 4. Process Validation
Check process completion, operation sequence and missing or repeated operations.

### 5. Quality Inspection
Record final coating thickness and other configured inspection measurements.

### 6. Specification Comparison
Compare inspection measurements with customer-specific limits and identify deviations.

### 7. Batch Traceability
Display batch details, process progress, inspection results and quality status.

### 8. Deviation Review
Review recorded process and inspection information to identify recurring deviations.


# Project Flow
## Coating Process Monitoring and Customer-Specific Quality Control System

```text
                    START
                      |
                      v
              Batch Registration
                      |
                      v
       Customer-Specific Requirement
               Configuration
                      |
                      v
          Coating Process Monitoring
                      |
                      v
           Baking Process Monitoring
                      |
                      v
               Process Validation
                      |
                      v
          Are All Process Requirements
                  Satisfied?
                /           \
              No             Yes
              |               |
              v               v
       Process Deviation   Final Quality
           Alert            Inspection
              |               |
              v               v
        Review Process   Enter Inspection
          Deviation       Measurements
                              |
                              v
                    Customer Specification
                         Comparison
                              |
                              v
                    Are Measurements Within
                       Customer Limits?
                        /          \
                      No            Yes
                      |              |
                      v              v
                Quality Deviation  Within
                     Alert       Specification
                      |              |
                      +------+-------+
                             |
                             v
                    Batch Status Update
                             |
                             v
                    Batch Traceability
                             |
                             v
                      Deviation Review
                             |
                             v
                            END
```



## Tools and Technologies

- PLC Programming
- Structured Text (ST)
- Function Blocks
- PLC Development Environment

## Expected Outputs

- Batch-wise process status
- Planned and completed cycle counts
- Process sequence validation
- Final coating inspection measurements
- Customer specification comparison
- Process and quality deviation alerts

## Future Scope

- Integration with physical coating equipment
- Automatic thickness measurement through sensors
- Permanent production data storage
- Production trend analysis
- Industrial equipment integration
