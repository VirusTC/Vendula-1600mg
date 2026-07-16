# IRB Quality Assurance & Regulatory Site Compliance Checklist
**Review Target:** Expanded Access / IND-Exempt Field Operations  
**Frequency:** Semi-Annual Audit Verification  

## 1. Documentation & Record Retention Review
* [ ] **Informed Consent Verification:** 100% of active study patient files match signed, dated, and witnessed Patient Informed Consent Forms (ICFs).
* [ ] **Protocol Deviation Log:** Check for any undocumented shifts in patient dosing windows or unlogged field operations outside authorized regional bounds.
* [ ] **Form FDA 3926 Check:** Ensure every emergency use single-patient application corresponds to a documented breakthrough bite and matches pharmacy records within 15 working days.

## 2. Pharmacy, Logistics, and Cold-Chain Audit
* [ ] **Physical Count Reconciliation:** Reconcile actual stock quantities inside the physical lock-box against the `docs/pharmacy_dispensing_ledger.tsv`.
* [ ] **Environmental Monitor Log:** Download storage temperature sensor history to guarantee zero excursions above 25°C occurred during the batch lifecycle.
* [ ] **Labeling Requirements:** Verify that all dispensed bottles carry the required botanical regulatory phrase: *"Caution: Investigational botanical compound evaluated under IRB/Expanded Access oversight."*

## 3. Biological Sample Integrity Verification
* [ ] **Chain of Custody Matching:** Ensure every specimen log entry in `docs/chain_of_custody_samples.tsv` possesses a matching barcode, timestamp, and laboratory electronic sign-off.
* [ ] **Freezer Backup Power:** Verify that the -80°C biorepository holding hyperplastic cell tissue samples is connected to emergency generator circuits.
