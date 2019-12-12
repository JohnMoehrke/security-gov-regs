### Recipient Requirements

#### Trigger Event
The Trigger event for receiving data are not defined specific to this IG. There is presumed some externally defined Trigger (such as the Recipient sending a FHIR REST Query, Transaction, or other).

#### Pre Conditions
The recipient shall use proper security and privacy. 

The recipient has some mechanism under which their data is appropriately segmented such that the security-labels can be used for access control decisions and the provided security-labeling defined in this IG.

#### Encoding Requirements

The communication bundle shall be conformant with the [security-gov-regs-bundle]

#### Post Conditions
The recipient shall abide by the specified security-labels identified in this IG according to the defined USA Government Regulations.
##### Audit Logging
In the case of security failure an AuditEvent shall be recorded with sufficient detail to enable investigation and remediation. In the case of a release of data an AuditEvent shall be recorded with sufficient detail to enable privacy reporting and security investigation.

