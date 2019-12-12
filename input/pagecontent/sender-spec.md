### Sender Requirements
The Sender abstract actor sends protected health data to a [Recipient](recipient-spec.html), following the [Bundle Specification](structuredefinition-security-gov-regs-bundle.html), using the [subset of security-label vocabulary](ValueSet-security-gov-regs-vs.html)

#### Trigger Event
The Trigger event for sending data are not defined specific to this IG. There is presumed some externally defined Trigger (such as a FHIR REST Query, Transaction, or other).

#### Pre Conditions
The sender shall release data only when proper security and privacy are satisfied. 

The sender has some mechanism under which their data is appropriately segmented such that the security-labels can be used for access control decisions and the resulting security-labeling defined in this IG.

#### Encoding Requirements
The communication bundle shall be conformant with the [Bundle Specification](structuredefinition-security-gov-regs-bundle.html)

#### Post Conditions

##### Audit Logging
In the case of security failure an AuditEvent shall be recorded with sufficient detail to enable investigation and remediation. In the case of a release of data an AuditEvent shall be recorded with sufficient detail to enable privacy reporting and security investigation.

TODO: Should we define a Disclosure AuditEvent specific to this profile?

