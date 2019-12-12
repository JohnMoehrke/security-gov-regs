# Name
Subset of security label vocabulary to enable computable and interoperable security labeling for the use-cases of CUI, 42 CFR Part 2, and Title 38 Section 7332. 
# Description
To address the goals of the 21st Century Cures Act, participants in US healthcare exchange will be required to share sensitive information in accordance with governing privacy policies. Requirements to meet these laws are addressed in the latest version of the Trusted Exchange Framework and Common Agreement proposal. This project focuses on two national privacy laws governing sensitive information, 42 CFR Part 2 and Title 38 Section 7332; and the needs of 32 CFR Part 2002 CUI. This IG intends to show how to achieve standards based consensus on security labels for each policy to ensure interoperability and Share with Protections Trust Contracts .

# Source of specifics
https://confluence.hl7.org/display/SEC/Cross+Paradigm+CUI%2C+Part+2%2C+and+7332+Structure

## PSS
https://confluence.hl7.org/display/SEC/Cross+Paradigm+CUI+32+CFR+Part+2002%2C+42+CFR+Part+2%2C+and+Title+38+Section+7332+Security+Labeling+IG+PSS

# Continuous build 
When built the output can be viewed here http://build.fhir.org/ig/JohnMoehrke/security-gov-regs/branches/master/index.html 

# TODO
1. I have profiled only Bundle. I did not find a way to profile ANY DomainResource. However I don't think that is not needed
1. I have created one valueSet holding all the codes given by Kathleen. These have not been discussed by the committee, but seem reasonable to get started
1. I have created one example of a Bundle. It is from the IHE-MHD IG, with addition of ALL of the codes in our valueset. 
1. This is saved on JohnMoehrke GitHub. This will move to HL7 GitHub after the FMG approval of the IG Proposal.


