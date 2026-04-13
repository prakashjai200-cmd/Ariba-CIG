# ARIBA SLP (Supplier Lifecycle Performance) Integration with SAP ECC

This document outlines the detailed configuration steps required to integrate ARIBA SLP with SAP ECC.

## Prerequisites
- Ensure that you have appropriate access to both ARIBA and SAP ECC.
- Install necessary connector or middleware, if applicable.

## Configuration Steps

### Step 1: Configure ARIBA SLP
1. Log into your ARIBA account.
2. Navigate to the **Integration** section.
3. Set up your **API credentials**.
4. Enable the **SLP** feature in the ARIBA settings.

### Step 2: Configure SAP ECC
1. Log into your SAP ECC system.
2. Go to the **Transaction Codes** for integration - e.g., `WE20` for partner profiles.
3. Set up the necessary **RFC destinations** using transaction `SM59`.
4. Ensure IDocs are properly configured to communicate with ARIBA.

### Step 3: Middleware Configuration (if applicable)
1. Set up middleware (e.g., SAP PI/PO).
2. Define the communication channels, and ensure they align with both ARIBA and SAP ECC.
3. Map the data fields between SLP and SAP ECC.

### Step 4: Testing the Integration
1. Perform integration testing in a sandbox environment.
2. Validate data exchange between ARIBA and SAP ECC.
3. Check for any error logs and resolve them accordingly.

### Step 5: Go Live
1. After successful testing, move the configuration to the production environment.
2. Monitor integration logs for any issues in the initial days after going live.

## Conclusion
Following these steps will ensure a successful integration of ARIBA SLP with SAP ECC. Always keep this document updated with any changes in configuration or procedures.