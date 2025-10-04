# Awesome Compliance [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome resources for Governance, Risk Management, and Compliance (GRC) professionals.

This list is intended for **compliance officers, risk managers, auditors, and cybersecurity professionals** or for **people with a compliance need** who need trusted resources for **ISO 27001, SOC 2, SOX, ESG compliance, and more**.

## Contents

- [Frameworks & Standards](#frameworks--standards)
  - [Security & Privacy](#security--privacy)
  - [ESG & Sustainability](#esg--sustainability)
  - [Financial & Corporate](#financial--corporate)
  - [Quality & Assurance](#quality--assurance)
  - [Risk Management](#risk-management)
- [Legislative & Regulatory](#legislative--regulatory)
  - [United States](#united-states)
  - [European Union](#european-union)
  - [Other Regions](#other-regions)
- [Learning Resources](#learning-resources)
  - [Courses](#courses)
  - [Books & e-Books](#books--e-books)
  - [Podcasts](#podcasts)
  - [Newsletters](#newsletters)
  - [Tutorials & Videos](#tutorials--videos)
- [Certifications](#certifications)
- [Community & Organizations](#community--organizations)
- [Guides & Best Practices](#guides--best-practices)
- [Tools & Platforms](#tools--platforms)
  - [GRC Platforms](#grc-platforms)
  - [Reconnaissance & Response](#reconnaissance--response)
  - [Vulnerabilities & Threats](#vulnerabilities--threats)
  - [Trust & Customer Assurance](#trust--customer-assurance)
- [Security Architecture & Engineering](#security-architecture--engineering)
  - [Network Security](#network-security)
  - [Cloud Security](#cloud-security)
  - [Threat Modeling](#threat-modeling)
  - [Identity & Access Management](#identity--access-management)
  - [Supply Chain Security](#supply-chain-security)
  - [Assessment & Testing](#assessment--testing)
- [Contributing](#contributing)
- [Related Lists](#related-lists)

## Frameworks & Standards

### Security & Privacy

- **[SOC 1](https://www.aicpa.org/soc)** - Focuses on controls relevant to financial reporting for service organizations.
- **[SOC 2](https://www.aicpa.org/soc)** - Service Organization Control 2, an AICPA framework for security, availability, confidentiality, processing integrity, and privacy controls. Annual audits and attestation reports required.
- **[SOC 3](https://www.aicpa.org/soc)** - General use report based on SOC 2, designed for public distribution without detailed testing information.
- **[ISO/IEC 27001](https://www.iso.org/isoiec-27001-information-security.html)** - International standard for establishing an Information Security Management System (ISMS). Requires annual certification audits.
- **[ISO/IEC 27002](https://www.iso.org/standard/75652.html)** - Implementation guidance for ISO 27001 controls.
- **[ISO/IEC 27017](https://www.iso.org/standard/43757.html)** - Cloud security controls based on ISO 27002.
- **[ISO/IEC 27018](https://www.iso.org/standard/76559.html)** - Code of practice for protecting personally identifiable information in public cloud.
- **[ISO/IEC 27701](https://www.iso.org/standard/71670.html)** - Privacy Information Management System (PIMS) extension to ISO 27001.
- **[NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)** - Voluntary risk-based model for managing cybersecurity risk (Identify, Protect, Detect, Respond, Recover).
- **[NIST Risk Management Framework](https://csrc.nist.gov/projects/risk-management)** - Framework for integrating security and risk management into system development lifecycle.
- **[NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)** - Security and privacy controls for federal information systems and organizations. Widely adopted beyond government.
- **[NIST SP 800-171](https://csrc.nist.gov/publications/detail/sp/800-171/rev-2/final)** - Protecting Controlled Unclassified Information in nonfederal systems.
- **[NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework)** - AI Risk Management Framework for trustworthy AI development and deployment.
- **[NIST SP 800-82](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-82r3.pdf)** - Guide to Industrial Control Systems (ICS) Security for operational technology environments.
- **[NIST SP 800-160](https://csrc.nist.gov/publications/detail/sp/800-160/final)** - Systems Security Engineering for developing trustworthy secure systems.
- **[NIST SP 800-161](https://csrc.nist.gov/publications/detail/sp/800-161/rev-1/final)** - Cybersecurity Supply Chain Risk Management Practices for Systems and Organizations.
- **[NIST SP 800-172](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-172.pdf)** - Enhanced Security Requirements for Protecting Controlled Unclassified Information.
- **[NIST SP 800-218](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf)** - Secure Software Development Framework (SSDF) for integrating security into SDLC.
- **[NIST SP 800-63B](https://pages.nist.gov/800-63-3/sp800-63b.html)** - Digital Identity Guidelines for authentication and lifecycle management.
- **[NIST SP 800-66](https://csrc.nist.gov/pubs/sp/800/66/r2/final)** - Implementing the Health Insurance Portability and Accountability Act (HIPAA) Security Rule.
- **[NIST Privacy Framework](https://www.nist.gov/privacy-framework)** - Tool for improving privacy risk management.
- **[PCI DSS](https://www.pcisecuritystandards.org/)** - Payment Card Industry Data Security Standard. Required for handling credit card data. Version 4.0 emphasizes continuous compliance.
- **[HIPAA](https://www.hhs.gov/hipaa/index.html)** - US Health Insurance Portability and Accountability Act. Mandates safeguards for protected health information.
- **[HITRUST CSF](https://hitrustalliance.net/hitrust-csf/)** - Common certifiable framework combining HIPAA, NIST, ISO, and other requirements for healthcare.
- **[HICP](https://www.phe.gov/Preparedness/planning/405d/Pages/hic-practices.aspx)** - Health Industry Cybersecurity Practices for healthcare organizations (small, medium, and large practice guidance).
- **[FedRAMP](https://www.fedramp.gov/)** - Federal Risk and Authorization Management Program. Required for cloud services used by US federal agencies based on NIST 800-53.
- **[CMMC](https://www.acq.osd.mil/cmmc/)** - Cybersecurity Maturity Model Certification for US DoD contractors. Version 2.0 streamlines requirements.
- **[FISMA](https://www.cisa.gov/federal-information-security-modernization-act)** - Federal Information Security Modernization Act for US federal agency information security.
- **[StateRAMP](https://www.stateramp.org/)** - Standardized approach to cloud security for US state and local governments.
- **[FERPA](https://www2.ed.gov/policy/gen/guid/fpco/ferpa/index.html)** - Family Educational Rights and Privacy Act protecting student education records.
- **[Microsoft SSPA](https://www.microsoft.com/en-us/securityengineering/sdl/)** - Microsoft Security Software Privacy Assurance framework.
- **[CIS Controls](https://www.cisecurity.org/controls)** - Center for Internet Security 18 Critical Security Controls (formerly 20).
- **[CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)** - Configuration security benchmarks for systems and applications.
- **[CSA Cloud Controls Matrix](https://cloudsecurityalliance.org/research/cloud-controls-matrix)** - Cloud Security Alliance control framework for cloud computing.
- **[MITRE ATT&CK](https://attack.mitre.org/)** - Knowledge base of adversary tactics and techniques based on real-world observations.
- **[OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)** - Application Security Verification Standard.
- **[CPS234](https://www.apra.gov.au/information-security)** - Australian Prudential Regulation Authority information security requirements.
- **[CISA](https://www.cisa.gov/)** - Cybersecurity Information Sharing Act and CISA agency resources.
- **[NERC CIP](https://www.nerc.com/pa/Stand/Pages/CIPStandards.aspx)** - North American Electric Reliability Corporation Critical Infrastructure Protection standards.
- **[CJIS](https://www.fbi.gov/services/cjis/cjis-security-policy-resource-center)** - Criminal Justice Information Services Security Policy.
- **[Secure Control Framework](https://securecontrolsframework.com/scf-download/)** - Comprehensive control framework with mappings across multiple standards and regulations.
- **[NIST National Online Informative References Program (OLIR)](https://csrc.nist.gov/projects/olir)** - Machine-readable mappings between NIST frameworks and other standards.
- **[Adobe Common Controls Framework](https://www.adobe.com/trust/compliance/adobe-ccf.html)** - Adobe's unified control framework for compliance.
- **[Equifax Security Controls Framework](https://controlsframework.equifax.com/home)** - Equifax's control framework with mappings to major standards.
- **[CIS Controls Navigator](https://www.cisecurity.org/controls/cis-controls-navigator)** - Tool for navigating and implementing CIS Controls.
- **[MITRE NIST 800-53 to ATT&CK Mappings](https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/nist-800-53-control-mappings/)** - Maps NIST security controls to adversary techniques.
- **[NIST AI RMF Crosswalks](https://airc.nist.gov/AI_RMF_Knowledge_Base/Crosswalks)** - Mappings between AI RMF and other frameworks, standards, and regulations.
- **[CSF Tools](https://csf.tools/)** - Tools and resources for implementing the NIST Cybersecurity Framework.

### ESG & Sustainability

- **[B Corp Certification](https://www.bcorporation.net/)** - Certification for companies meeting high standards of social and environmental performance.
- **[CDP](https://www.cdp.net/)** - Carbon Disclosure Project for environmental impact reporting.
- **[GRI Standards](https://www.globalreporting.org/)** - Global Reporting Initiative for sustainability reporting.
- **[ISO 14001](https://www.iso.org/iso-14001-environmental-management.html)** - Environmental Management Systems.
- **[ISO 45001](https://www.iso.org/iso-45001-occupational-health-and-safety.html)** - Occupational Health and Safety Management Systems.
- **[ISO 50001](https://www.iso.org/iso-50001-energy-management.html)** - Energy Management Systems.
- **[SASB Standards](https://www.sasb.org/)** - Sustainability Accounting Standards Board standards for ESG disclosure.
- **[TCFD](https://www.fsb-tcfd.org/)** - Task Force on Climate-related Financial Disclosures recommendations.
- **[UN SDGs](https://sdgs.un.org/)** - United Nations Sustainable Development Goals.

### Financial & Corporate

- **[SOX](https://www.congress.gov/bill/107th-congress/house-bill/3763)** - Sarbanes-Oxley Act for financial reporting and corporate governance.
- **[SOX ITGC](https://www.aicpa.org/)** - IT General Controls for Sarbanes-Oxley compliance.
- **[Basel Framework](https://www.bis.org/basel_framework/)** - International banking regulations on capital adequacy, stress testing, and market liquidity.
- **[FCRA](https://www.ftc.gov/legal-library/browse/statutes/fair-credit-reporting-act)** - Fair Credit Reporting Act regulating credit information collection and use.
- **[IFRS](https://www.ifrs.org/)** - International Financial Reporting Standards for accounting and financial reporting.
- **[GLBA](https://www.ftc.gov/business-guidance/privacy-security/gramm-leach-bliley-act)** - Gramm-Leach-Bliley Act requiring financial institutions to protect customer information.
- **[NYDFS](https://www.dfs.ny.gov/industry_guidance/cyber_regulations)** - New York Department of Financial Services Cybersecurity Regulation (23 NYCRR 500).
- **[SWIFT CSF](https://www.swift.com/myswift/customer-security-programme-csp/security-controls)** - SWIFT Customer Security Controls Framework for financial messaging and payment systems.
- **[FFIEC](https://www.ffiec.gov/pdf/cybersecurity/FFIEC_CAT_App_B_Map_to_NIST_CSF_June_2015_PDF4.pdf)** - Federal Financial Institutions Examination Council cybersecurity assessment tool.
- **[FINRA](http://www.finra.org/industry/cybersecurity)** - Financial Industry Regulatory Authority cybersecurity requirements for broker-dealers.
- **[SAMA CSF](https://www.sama.gov.sa/en-US/Laws/FinanceRules/SAMA%20Cyber%20Security%20Framework%20v1.0%20final_updated.pdf)** - Saudi Arabian Monetary Authority Cyber Security Framework for financial sector.
- **[EBA ICT Guidelines](https://www.eba.europa.eu/regulation-and-policy/internal-governance/guidelines-on-ict-and-security-risk-management)** - European Banking Authority ICT and security risk management guidelines.
- **[OFDSS](https://www.ofdss.org/)** - Office of Federal Student Aid Security Standards.

### Quality & Assurance

- **[ISO 9001](https://www.iso.org/iso-9001-quality-management.html)** - Quality Management Systems standard.
- **[AS9100](https://www.sae.org/standards/content/as9100d/)** - Quality management for aerospace industry.
- **[ISO 13485](https://www.iso.org/standard/59752.html)** - Quality management for medical devices.
- **[ISO 22000](https://www.iso.org/iso-22000-food-safety-management.html)** - Food Safety Management Systems.
- **[ISO/TS 16949](https://www.iso.org/standard/52844.html)** - Quality management for automotive industry (superseded by IATF 16949).
- **[ISO 22301](https://www.iso.org/standard/75106.html)** - Security and resilience business continuity management systems requirements.
- **[cGMP](https://www.fda.gov/drugs/pharmaceutical-quality-resources/current-good-manufacturing-practice-cgmp-regulations)** - Current Good Manufacturing Practice for pharmaceuticals.
- **[FDA 21 CFR Part 11](https://www.gpo.gov/fdsys/pkg/CFR-2012-title21-vol1/pdf/CFR-2012-title21-vol1-part11.pdf)** - Electronic records and electronic signatures in FDA-regulated industries.
- **[IEC TR 60601-4-5](https://webstore.iec.ch/publication/64703)** - Medical electrical equipment cybersecurity requirements.
- **[IEC 62443-4-2](https://webstore.iec.ch/publication/34421)** - Security for industrial automation and control systems technical requirements.
- **[ISO/SAE 21434](https://www.iso.org/standard/70918.html)** - Road vehicles cybersecurity engineering standard.
- **[UN R155](https://unece.org/transport/documents/2021/03/standards/un-regulation-no-155-cyber-security-and-cyber-security)** - UN Regulation cybersecurity and cyber security management system for vehicles.
- **[TISAX](https://portal.enx.com/en-us/TISAX/downloads/)** - Trusted Information Security Assessment Exchange for automotive industry information security assessment.
- **[ITIL](https://www.axelos.com/certifications/itil-service-management)** - Information Technology Infrastructure Library for IT service management.
- **[COBIT](https://www.isaca.org/resources/cobit)** - Control Objectives for Information and Related Technologies governance framework.
- **[ISO 42001](https://www.iso.org/standard/81230.html)** - AI Management System standard.

### Risk Management

- **[COSO ERM](https://www.coso.org/Pages/erm.aspx)** - Committee of Sponsoring Organizations Enterprise Risk Management framework.
- **[FAIR](https://www.fairinstitute.org/)** - Factor Analysis of Information Risk, quantitative risk analysis framework.
- **[ISO 27005](https://www.iso.org/standard/75281.html)** - Information security risk management.
- **[ISO 31000](https://www.iso.org/iso-31000-risk-management.html)** - Risk management guidelines and principles.
- **[NIST SP 800-37](https://csrc.nist.gov/publications/detail/sp/800-37/rev-2/final)** - Risk Management Framework for Information Systems.
- **[NIST SP 800-39](https://csrc.nist.gov/publications/detail/sp/800-39/final)** - Managing Information Security Risk: Organization, Mission, and Information System View.
- **[OCTAVE](https://www.cmu.edu/sei/our-work/projects/display.cfm?customel_datapageid_4050=21281)** - Operationally Critical Threat, Asset, and Vulnerability Evaluation by Carnegie Mellon.
- **[Rapid Risk Assessment](https://infosec.mozilla.org/guidelines/risk/rapid_risk_assessment)** - Mozilla's lightweight risk assessment methodology.
- **[TARA](https://www.mitre.org/publications/technical-papers/threat-assessment-and-remediation-analysis-tara)** - Threat Assessment and Remediation Analysis by MITRE.

## Legislative & Regulatory

### United States

#### Federal Privacy Legislation

The U.S. federal government has proposed dozens of privacy bills covering consumer rights, workplace privacy, health data, financial privacy, children's privacy, and governmental obligations. As of 2024, no comprehensive federal privacy law has been enacted.

**Trackers and Resources:**
- **[IAPP US Federal Privacy Legislation Tracker](https://iapp.org/resources/article/us-federal-privacy-legislation-tracker/)** - Comprehensive tracking of 50+ federal privacy bills in the 118th Congress (2023-2024).

**Consumer Privacy Bills:**
- **[American Privacy Rights Act of 2024 (H.R.8818)](https://www.congress.gov/bill/118th-congress/house-bill/8818)** - Bipartisan comprehensive privacy bill with data minimization, privacy by design, individual rights, and preemption of state law.
- **[Informing Consumers about Smart Devices Act (S.90/H.R.538)](https://www.congress.gov/bill/118th-congress/senate-bill/90)** - Requires disclosure of cameras/microphones in internet-connected devices.
- **[Platform Accountability and Transparency Act (S.1876)](https://www.congress.gov/bill/118th-congress/senate-bill/1876)** - Privacy-protected research pathways for data held by large internet companies.
- **[DELETE Act (S.2121/H.R.4311)](https://www.congress.gov/bill/118th-congress/senate-bill/2121)** - Centralized system for deletion requests to data brokers.
- **[Deceptive Experiences to Online Users Reduction Act (S.2708)](https://www.congress.gov/bill/118th-congress/senate-bill/2708)** - Prohibits manipulation of consumers into providing personal information.
- **[Data Care Act of 2023 (S.744)](https://www.congress.gov/bill/118th-congress/senate-bill/744)** - Imposes duties of care, loyalty, and confidentiality on online service providers.
- **[Online Privacy Act of 2023 (H.R.2701)](https://www.congress.gov/bill/118th-congress/house-bill/2701)** - Creates Digital Privacy Agency with comprehensive individual rights and data minimization.
- **[Algorithmic Justice and Online Platform Transparency Act (S.2325/H.R.4624)](https://www.congress.gov/bill/118th-congress/senate-bill/2325)** - Prohibits discriminatory practices and establishes data portability rights.
- **[Defending Each and Every Person from False Appearances by Keeping Exploitation Subject to Accountability Act (H.R.5586)](https://www.congress.gov/bill/118th-congress/house-bill/5586)** - Disclosure requirements for deepfakes with criminal penalties.
- **[Digital Accountability and Transparency to Advance Privacy Act (S.3337)](https://www.congress.gov/bill/118th-congress/senate-bill/3337)** - Privacy notices and privacy protection officer requirements.

**Workplace Privacy Bills:**
- **[Stop Spying Bosses Act (H.R.7690/S.262)](https://www.congress.gov/bill/118th-congress/house-bill/7690)** - Prohibits or requires disclosure of workplace surveillance and monitoring.
- **[No Robot Bosses Act (H.R.7621/S.2419)](https://www.congress.gov/bill/118th-congress/house-bill/7621)** - Prohibits exclusive reliance on automated decision-making in employment.
- **[Protecting Healthcare Employee Privacy Act (H.R.7216)](https://www.congress.gov/bill/118th-congress/house-bill/7216)** - Rescinds COVID-19 vaccination status reporting requirements.

**Health Privacy Bills:**
- **[HHS Reproductive and Sexual Health Ombuds Act (H.R.445)](https://www.congress.gov/bill/118th-congress/house-bill/445)** - Establishes ombuds to coordinate on reproductive/sexual health data privacy.
- **[No Vaccine Passports Act (S.181)](https://www.congress.gov/bill/118th-congress/senate-bill/181)** - Restricts use and disclosure of COVID-19 emergency health data.
- **[Upholding Protections for Health and Online Location Data Privacy Act (S.631)](https://www.congress.gov/bill/118th-congress/senate-bill/631)** - Protections for health and location data including prohibition of data broker sales.
- **[My Body, My Data Act (S.1656/H.R.3420)](https://www.congress.gov/bill/118th-congress/senate-bill/1656)** - Privacy protections for reproductive and sexual health information.
- **[Protect Sexual and Reproductive Health Act (H.R.4281)](https://www.congress.gov/bill/118th-congress/house-bill/4281)** - Office of Sexual and Reproductive Health within HHS with privacy protection strategies.
- **[No Biometric Barriers to Housing Act (H.R.5358)](https://www.congress.gov/bill/118th-congress/house-bill/5358)** - Prohibits biometric recognition technology in federally assisted housing.
- **[American Genetic Privacy Act (H.R.5830)](https://www.congress.gov/bill/118th-congress/house-bill/5830)** - Prohibits commercial DNA testing disclosure to Chinese-controlled entities.
- **[Patient Privacy and Caregiver Awareness Act (H.R.6764)](https://www.congress.gov/bill/118th-congress/house-bill/6764)** - Two-year expiration for HIPAA mental health/substance abuse consent.
- **[Reproductive Data Privacy and Protection Act (H.R.7841)](https://www.congress.gov/bill/118th-congress/house-bill/7841)** - Protects reproductive/sexual health information from compelled disclosure.

**Financial Privacy Bills:**
- **[Moving Americans Privacy Protection Act (S.758/H.R.1568)](https://www.congress.gov/bill/118th-congress/senate-bill/758)** - Restricts public disclosure of PII in vessel/aircraft manifests.
- **[Homebuyers Privacy Protection Act (H.R.7297/S.3502)](https://www.congress.gov/bill/118th-congress/house-bill/7297)** - Requires consumer authorization for credit reports in mortgage transactions.
- **[Data Privacy Act of 2023 (H.R.1165)](https://www.congress.gov/bill/118th-congress/house-bill/1165)** - Modernizes Gramm-Leach-Bliley Act protections with consumer rights.
- **[Bank Privacy Reform Act (H.R.1220)](https://www.congress.gov/bill/118th-congress/house-bill/1220)** - Bank Secrecy Act reforms with search warrant requirements.
- **[Bank Loan Privacy Act (H.R.1810)](https://www.congress.gov/bill/118th-congress/house-bill/1810)** - CFPB rulemaking on small business loan data deletions.
- **[Protect Taxpayers' Privacy Act (S.1051)](https://www.congress.gov/bill/118th-congress/senate-bill/1051)** - Increased penalties for unauthorized taxpayer information disclosure.
- **[Protecting Privacy in Purchases Act (S.4075/H.R.7450)](https://www.congress.gov/bill/118th-congress/senate-bill/4075)** - Prohibits firearms-specific merchant category codes.

**Children's and Educational Privacy Bills:**
- **[Kids Online Safety Act (H.R.7891/S.1409)](https://www.congress.gov/bill/118th-congress/house-bill/7891)** - Platform safety requirements for minors including restricted data access.
- **[Children and Teens' Online Privacy Protection Act (H.R.7890/S.1418)](https://www.congress.gov/bill/118th-congress/house-bill/7890)** - Extends COPPA protections to ages 12-16.
- **[Protecting Kids on Social Media Act (H.R.6149)](https://www.congress.gov/bill/118th-congress/house-bill/6149)** - Age verification and parental consent for minors on social platforms.
- **[Privacy in Education Regarding Individuals' Own Data Act (H.R.951)](https://www.congress.gov/bill/118th-congress/house-bill/951)** - Prohibits educational institutions from requiring menstrual cycle information.
- **[Parents Bill of Rights Act (H.R.5)](https://www.congress.gov/bill/118th-congress/house-bill/5)** - FERPA amendments prohibiting student information sales.
- **[Kids PRIVACY Act (H.R.2801)](https://www.congress.gov/bill/118th-congress/house-bill/2801)** - Expands COPPA with access, correction, and deletion rights.
- **[Protecting Education Privacy Act (H.R.4252)](https://www.congress.gov/bill/118th-congress/house-bill/4252)** - FERPA clarification on authorized representative disclosures.
- **[Verifying Kids' Online Privacy Act (H.R.7534)](https://www.congress.gov/bill/118th-congress/house-bill/7534)** - Defines child as under 16 and requires age verification.

**Governmental Privacy Obligations Bills:**
- **[Protecting Americans' Data From Foreign Surveillance Act (S.1974/H.R.4108)](https://www.congress.gov/bill/118th-congress/senate-bill/1974)** - Export controls for personal data of U.S. nationals.
- **[Taxpayer Notification and Privacy Act (S.2111)](https://www.congress.gov/bill/118th-congress/senate-bill/2111)** - IRS notification when taxpayer information sought by third parties.
- **[Privacy Enhancing Technology Research Act (H.R.4755)](https://www.congress.gov/bill/118th-congress/house-bill/4755)** - NSF research support for privacy enhancing technologies.
- **[Digital Consumer Protection Commission Act (S.2597)](https://www.congress.gov/bill/118th-congress/senate-bill/2597)** - Establishes commission to regulate digital platforms.
- **[Fourth Amendment Is Not For Sale Act (S.2576/H.R.4639)](https://www.congress.gov/bill/118th-congress/senate-bill/2576)** - Prevents law enforcement from purchasing subscriber/customer records.
- **[Transparent Automated Governance Act (H.R.6886)](https://www.congress.gov/bill/118th-congress/house-bill/6886)** - Federal agency transparency in automated system use.
- **[Fourth Amendment Restoration Act (H.R.237)](https://www.congress.gov/bill/118th-congress/house-bill/237)** - Repeals FISA with prohibitions on surveilling U.S. citizens.
- **[Facial Recognition and Biometric Technology Moratorium Act (S.681/H.R.1404)](https://www.congress.gov/bill/118th-congress/senate-bill/681)** - Prohibits federal biometric surveillance without statutory authorization.
- **[Improving Digital Identity Act (S.884)](https://www.congress.gov/bill/118th-congress/senate-bill/884)** - Digital Identity Task Force to coordinate physical/digital credential improvements.
- **[Digital Platform Commission Act (S.1671)](https://www.congress.gov/bill/118th-congress/senate-bill/1671)** - Commission with rulemaking authority for digital platform consumer protection.
- **[Civil Liberties Protection Act (H.R.4107)](https://www.congress.gov/bill/118th-congress/house-bill/4107)** - Civil Liberties Protection Officer for Financial Crimes Enforcement Network.
- **[E-Verify Data Privacy and Wrongful Unemployment Act (H.R.4430)](https://www.congress.gov/bill/118th-congress/house-bill/4430)** - Improves employment verification system data privacy.
- **[Speech Privacy Act (H.R.4417)](https://www.congress.gov/bill/118th-congress/house-bill/4417)** - Prohibits collecting donor information for tax-exempt organizations.
- **[Purchased Data Inventory Act (S.2292)](https://www.congress.gov/bill/118th-congress/senate-bill/2292)** - Transparency obligations for federal agencies purchasing PII.
- **[Exploitative Workplace Surveillance and Technologies Task Force Act (S.2440)](https://www.congress.gov/bill/118th-congress/senate-bill/2440)** - Interagency task force on employer surveillance practices.
- **[Financial Privacy Act (H.R.5485)](https://www.congress.gov/bill/118th-congress/house-bill/5485)** - Treasury transparency enhancements for Bank Secrecy Act reports.
- **[Algorithmic Accountability Act (S.2892/H.R.5628)](https://www.congress.gov/bill/118th-congress/senate-bill/2892)** - FTC impact assessments of automated decision systems including privacy risks.
- **[Protecting Gun Owners' Privacy Act (H.R.5949)](https://www.congress.gov/bill/118th-congress/house-bill/5949)** - Prevents federal storage of firearms sales records.
- **[Facial Recognition Act (H.R.6092)](https://www.congress.gov/bill/118th-congress/house-bill/6092)** - Limits law enforcement facial recognition access with audit requirements.
- **[Promoting Digital Privacy Technologies Act (S.3325)](https://www.congress.gov/bill/118th-congress/senate-bill/3325)** - NSF research support and collaboration on privacy enhancing technologies.
- **[Traveler Privacy Protection Act (S.3361)](https://www.congress.gov/bill/118th-congress/senate-bill/3361)** - Prohibits TSA facial recognition without Congressional authorization.
- **[Medicare Telehealth Privacy Act (H.R.6364)](https://www.congress.gov/bill/118th-congress/house-bill/6364)** - Prevents HHS from publicizing telehealth provider home addresses.

#### State Privacy Laws

Twenty states have enacted comprehensive consumer privacy laws as of 2025.

**Resources:**
- **[IAPP US State Privacy Legislation Tracker](https://iapp.org/resources/article/us-state-privacy-legislation-tracker/)** - Comprehensive tracking of state privacy legislation across all US states.

**California:**
- **[CCPA](https://oag.ca.gov/privacy/ccpa)** - California Consumer Privacy Act. Privacy rights for California residents.
- **[CPRA](https://cppa.ca.gov/)** - California Privacy Rights Act. Expands CCPA with new protections effective 2023.

**Other States:**
- **[Virginia CDPA](https://lis.virginia.gov/cgi-bin/legp604.exe?212+ful+CHAP0035+pdf)** - Virginia Consumer Data Protection Act providing privacy rights to Virginia residents.
- **[Colorado Privacy Act](https://leg.colorado.gov/sites/default/files/2021a_190_signed.pdf)** - Colorado comprehensive privacy law with consumer rights and business obligations.
- **[Connecticut CTDPA](https://www.cga.ct.gov/2024/sup/chap_743jj.htm)** - Connecticut Data Privacy Act comprehensive consumer privacy law.
- **[Utah UCPA](https://le.utah.gov/xcode/Title13/Chapter61/13-61.html)** - Utah Consumer Privacy Act providing consumer rights and business obligations.
- **[Iowa ICDPA](https://www.legis.iowa.gov/docs/publications/iactc/90.1/CH17.pdf)** - Iowa Consumer Data Protection Act effective January 1, 2025.
- **[Indiana ICDPA](https://iga.in.gov/laws/2024/ic/titles/24#24-15-1)** - Indiana Consumer Data Protection Act comprehensive privacy law.
- **[Tennessee TIPA](https://publications.tnsosfiles.com/acts/113/pub/pc0408.pdf)** - Tennessee Information Protection Act effective July 1, 2025.
- **[Montana MCDPA](https://archive.legmt.gov/bills/mca/title_0300/chapter_0140/part_0280/sections_index.html)** - Montana Consumer Data Privacy Act with consumer privacy rights.
- **[Texas TDPSA](https://statutes.capitol.texas.gov/Docs/BC/htm/BC.541.htm)** - Texas Data Privacy and Security Act comprehensive privacy framework.
- **[Delaware DPDPA](https://delcode.delaware.gov/title6/c012d/index.html)** - Delaware Personal Data Privacy Act consumer privacy protections.
- **[Oregon OCPA](https://www.oregonlegislature.gov/bills_laws/ors/ors646a.html)** - Oregon Consumer Privacy Act (ORS 646A.570-646A.589) comprehensive data privacy law.
- **[Florida FDBR](https://www.flsenate.gov/Session/Bill/2023/262)** - Florida Digital Bill of Rights effective July 1, 2024.
- **[New Hampshire Privacy Act](https://legiscan.com/NH/text/SB255/id/2750381)** - New Hampshire comprehensive privacy law (SB 255) effective January 1, 2025.
- **[New Jersey NJDPL](https://pub.njleg.state.nj.us/Bills/2022/S0500/332_I1.PDF)** - New Jersey Data Privacy Law comprehensive consumer protections.
- **[Maryland MODPA](https://mgaleg.maryland.gov/mgawebsite/Legislation/Details/sb0541)** - Maryland Online Data Privacy Act effective October 1, 2025.
- **[Minnesota MCDPA](https://www.revisor.mn.gov/statutes/cite/325O)** - Minnesota Consumer Data Privacy Act comprehensive privacy legislation.
- **[Nebraska NDPA](https://nebraskalegislature.gov/FloorDocs/108/PDF/Slip/LB1074.pdf)** - Nebraska Data Privacy Act enacted in 2024.
- **[Rhode Island DTPPA](https://webserver.rilegislature.gov/BillText/BillText24/SenateText24/S2989A.pdf)** - Rhode Island Data Transparency and Privacy Protection Act effective January 1, 2026.
- **[Kentucky KCDPA](https://apps.legislature.ky.gov/law/statutes/chapter.aspx?id=49859)** - Kentucky Consumer Data Protection Act comprehensive privacy law.

**Sector-Specific and State Data Security Laws:**
- **[NY SHIELD Act](https://legislation.nysenate.gov/pdf/bills/2019/s5575b)** - New York Stop Hacks and Improve Electronic Data Security Act with breach notification and data security requirements.
- **[NY DFS 23 NYCRR 500](https://www.dfs.ny.gov/system/files/documents/2023/12/rf23_nycrr_part_500_amend02_20231101.pdf)** - Cybersecurity requirements for financial services companies in New York.
- **[Illinois BIPA](https://www.ilga.gov/legislation/ilcs/ilcs3.asp?ActID=3004&ChapterID=57)** - Biometric Information Privacy Act regulating collection and storage of biometric data.
- **[Massachusetts 201 CMR 17.00](http://www.mass.gov/ocabr/docs/idtheft/201cmr1700reg.pdf)** - Comprehensive data security regulation for personal information of Massachusetts residents.

#### State AI Governance Laws

**Resources:**
- **[IAPP US State AI Governance Legislation Tracker](https://iapp.org/resources/article/us-state-ai-governance-legislation-tracker/)** - Comprehensive tracking of 60+ state AI bills across governance, transparency, and assurance requirements.

**Enacted Laws:**
- **[Colorado SB 205](https://leg.colorado.gov/bills/sb24-205)** - Comprehensive AI decision-making law with developer and deployer obligations for risk assessments, transparency, and nondiscrimination. First comprehensive state AI law.
- **[California AB 2013](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202320240AB2013)** - Generative AI transparency and labeling requirements.
- **[California SB 942](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202320240SB942)** - Generative AI watermarking and provenance standards.
- **[Utah SB 149](https://le.utah.gov/~2024/bills/static/SB0149.html)** - Generative AI disclosure requirements.
- **[Utah SB 226](https://le.utah.gov/~2024/bills/static/SB0226.html)** - AI transparency in government services.
- **[Texas HB 149](https://capitol.texas.gov/BillLookup/History.aspx?LegSess=89R&Bill=HB149)** - Comprehensive AI governance for all covered systems.

**Active State Bills:**

*California:*
- **[AB 1018](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202520260AB1018)** - Automated decision-making system requirements for deployers.
- **[AB 412](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202520260AB412)** - Generative AI labeling and notification requirements.
- **[SB 11](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202520260SB11)** - Automated decision-making system governance and assessments.
- **[SB 53](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202520260SB53)** - Foundation model documentation and transparency requirements.
- **[SB 420](https://leginfo.legislature.ca.gov/faces/billNavClient.xhtml?bill_id=202520260SB420)** - Automated decision-making with comprehensive governance requirements.

*Hawaii:*
- **[SB 59](https://www.capitol.hawaii.gov/measure_indiv.aspx?billtype=SB&billnumber=59)** - Comprehensive automated decision-making requirements including assessments, training, and individual rights.

*Illinois:*
- **[HB 3506](https://www.ilga.gov/legislation/BillStatus.asp?DocNum=3506&GAID=17&DocTypeID=HB&SessionID=112)** - Foundation model transparency and documentation requirements.
- **[SB 1929](https://www.ilga.gov/legislation/BillStatus.asp?DocNum=1929&GAID=17&DocTypeID=SB&SessionID=112)** - Generative AI labeling requirements.
- **[SB 1792](https://www.ilga.gov/legislation/BillStatus.asp?DocNum=1792&GAID=17&DocTypeID=SB&SessionID=112)** - Generative AI general notice and labeling requirements.
- **[SB 2203](https://www.ilga.gov/legislation/BillStatus.asp?DocNum=2203&GAID=17&DocTypeID=SB&SessionID=112)** - Comprehensive automated decision-making governance framework.

*Iowa:*
- **[HB 406](https://www.legis.iowa.gov/legislation/BillBook?ga=90&ba=HF406)** - AI systems trained on personal data with labeling requirements.

*Massachusetts:*
- **[HB 94](https://malegislature.gov/Bills/194/H94)** - Comprehensive AI governance for all covered systems and automated decision-making.
- **[HB 97](https://malegislature.gov/Bills/194/H97)** - Similar comprehensive AI governance requirements.

*Minnesota:*
- **[SF 1886](https://www.revisor.mn.gov/bills/bill.php?b=Senate&f=SF1886&ssn=0&y=2025)** - All covered AI systems with governance program requirements.

*Nebraska:*
- **[LB 642](https://nebraskalegislature.gov/bills/view_bill.php?DocumentID=53642)** - Comprehensive automated decision-making governance with assessments and nondiscrimination.

*New York:*
- **[AB 768/SB 1962](https://nyassembly.gov/leg/?default_fld=&leg_video=&bn=A00768&term=2025)** - Comprehensive governance for all covered systems, foundation models, and automated decision-making.
- **[AB 3265](https://nyassembly.gov/leg/?default_fld=&leg_video=&bn=A03265&term=2025)** - Automated decision-making transparency and individual rights.
- **[AB 3356](https://nyassembly.gov/leg/?default_fld=&leg_video=&bn=A03356&term=2025)** - Automated decision-making labeling and explanation requirements.
- **[AB 3411/SB 934](https://nyassembly.gov/leg/?default_fld=&leg_video=&bn=A03411&term=2025)** - Generative AI general notice and labeling.
- **[AB 6453/SB 6953](https://nyassembly.gov/leg/?default_fld=&leg_video=&bn=A06453&term=2025)** - Foundation model developer documentation requirements.
- **[AB 6540/SB 6954](https://nyassembly.gov/leg/?default_fld=&leg_video=&bn=A06540&term=2025)** - Generative AI labeling requirements.
- **[AB 6578/SB 6955](https://nyassembly.gov/leg/?default_fld=&leg_video=&bn=A06578&term=2025)** - Generative AI labeling requirements.
- **[AB 8884/SB 1169](https://nyassembly.gov/leg/?default_fld=&leg_video=&bn=A08884&term=2025)** - Comprehensive automated decision-making requirements for deployers and developers.

*Oklahoma:*
- **[HB 1916](http://www.oklegislature.gov/BillInfo.aspx?Bill=HB1916&Session=2500)** - All covered AI systems and automated decision-making governance.

*Vermont:*
- **[HB 340](https://legislature.vermont.gov/bill/status/2026/H.340)** - Comprehensive automated decision-making governance for deployers and developers.
- **[HB 341](https://legislature.vermont.gov/bill/status/2026/H.341)** - Foundation model, automated decision-making, and generative AI requirements.

#### Federal AI Legislation

**Proposed Legislation:**
- **[Algorithmic Accountability Act of 2023 (S.2892/H.R.5628)](https://www.congress.gov/bill/118th-congress/senate-bill/2892)** - Directs FTC to require impact assessments of automated decision systems including evaluation of privacy risks.
- **[AI Transparency Act](https://www.congress.gov/bill/118th-congress/senate-bill/2325)** - Platform transparency and nondiscrimination requirements for AI systems.
- **[No Robot Bosses Act (S.2419/H.R.7621)](https://www.congress.gov/bill/118th-congress/senate-bill/2419)** - Prohibits exclusive reliance on automated decision-making in employment.

**Executive Actions:**
- **[NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework)** - AI Risk Management Framework for trustworthy AI development and deployment.
- **[Executive Order 14110](https://www.whitehouse.gov/briefing-room/presidential-actions/2023/10/30/executive-order-on-the-safe-secure-and-trustworthy-development-and-use-of-artificial-intelligence/)** - Safe, Secure, and Trustworthy Development and Use of Artificial Intelligence (October 2023).

### European Union

**Privacy and Data Protection:**
- **[GDPR](https://gdpr.eu/)** - EU General Data Protection Regulation governing personal data protection. Self-attestation via Data Protection Officer with demonstrated compliance.
  - **[GDPR-info.eu](https://gdpr-info.eu/)** - Complete GDPR text with recitals and commentary.
  - **[GDPR Expert](https://www.gdpr-expert.com/)** - GDPR compliance resources.
  - **[GDPRhub](https://gdprhub.eu/)** - Free and open database of GDPR case law.
- **[NIS2 Directive](https://digital-strategy.ec.europa.eu/en/policies/nis2-directive)** - EU Network and Information Security Directive establishing cybersecurity requirements for critical infrastructure and digital services.
- **[EU DORA](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32022R2554&from=EN)** - Digital Operational Resilience Act for financial sector ICT risk management in the EU.
- **[ePrivacy Directive](http://ec.europa.eu/newsroom/dae/document.cfm?doc_id=41241)** - EU directive on privacy and electronic communications (under revision).
- **[ENISA Guidelines](https://resilience.enisa.europa.eu/article-13/guideline-for-minimum-security-measures/Article_13a_ENISA_Technical_Guideline_On_Security_Measures_v2_0.pdf)** - European Union Agency for Network and Information Security technical guidelines and security measures.

**EU Member States:**
- **[Germany C5](https://www.bsi.bund.de/EN/Topics/CloudComputing/Compliance_Criteria_Catalogue/Compliance_Criteria_Catalogue_node.html)** - Cloud Computing Compliance Controls Catalogue for cloud service security assessment.
- **[UK GDPR](https://www.legislation.gov.uk/eur/2016/679/data.pdf)** - UK implementation of GDPR post-Brexit.
- **[UK CAF](https://www.ncsc.gov.uk/files/Cyber-Assessment-Framework-v3-1.pdf)** - UK National Cyber Security Centre Cyber Assessment Framework for critical infrastructure.

**AI Governance:**
- **[EU AI Act](https://artificialintelligenceact.eu/)** - Comprehensive AI regulation with risk-based approach, prohibitions on high-risk uses, and transparency requirements. First comprehensive AI law globally.

### Other Regions

**North America:**
- **[PIPEDA](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/)** - Canada's federal privacy law for private-sector organizations.

**Asia-Pacific:**
- **[PDPA](https://www.pdpc.gov.sg/Overview-of-PDPA/The-Legislation/Personal-Data-Protection-Act)** - Singapore Personal Data Protection Act.
- **[Japan ISMAP](https://www.ismap.go.jp/csm/en?id=kb_article_view&sysparm_article=KB0010301&sys_kb_id=4d06b8701b4f011013a78665cc4bcbd2&spa=1)** - Information System Security Management and Assessment Program for cloud services in Japan.

**Latin America:**
- **[LGPD](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd)** - Brazil's Lei Geral de Proteção de Dados (General Data Protection Law).

**Global Resources:**
- **[Data Protection Laws of the World](https://www.dlapiperdataprotection.com/)** - DLA Piper's comprehensive global privacy law database covering 100+ jurisdictions.

## Learning Resources

### Courses

- **[Penn State University - Privacy Courses](https://online.psu.edu/)** - Online privacy and security courses.
- **[University of Pennsylvania - Privacy Law](https://www.coursera.org/learn/privacy-law-data)** - Privacy law and data protection course.
- **[Washington University in St. Louis - Cybersecurity](https://cybersecurity.wustl.edu/)** - Comprehensive cybersecurity programs.
- **[CMU - Privacy Engineering](https://www.cmu.edu/privacy-engineering/)** - Privacy engineering master's program.
- **[Caltech - Data Privacy](https://www.caltech.edu/)** - Data privacy research and courses.
- **[Harvard - Cybersecurity](https://www.extension.harvard.edu/professional-development/programs/cybersecurity)** - Cybersecurity management and policy.
- **[Georgia Tech - Cybersecurity](https://pe.gatech.edu/degrees/cybersecurity)** - Online master's in cybersecurity.
- **[University of Vermont - Privacy](https://learn.uvm.edu/)** - Privacy and data protection courses.
- **[Udemy - Compliance Courses](https://www.udemy.com/)** - Wide range of compliance certification prep courses.
- **[Coursera - Cybersecurity Specializations](https://www.coursera.org/)** - University-backed cybersecurity programs.
- **[edX - Privacy and Security](https://www.edx.org/)** - Free and paid courses from top universities.
- **[Noah - Free Courses for Cyber](https://medium.com/@noahsec/free-courses-for-cyber-c2979ad3c9ee)** - Curated list of free cybersecurity courses.

### Books & e-Books

**Security & Privacy:**
- **[ISO 27001 Controls: A Guide to Implementing and Auditing](https://www.amazon.com/ISO-27001-Controls-Implementing-Auditing/dp/1849284695)** - Practical guide to implementing and auditing ISO 27001 controls.
- **[Security Risk Management: Building an Information Security Risk Management Program from the Ground Up](https://www.amazon.com/Security-Risk-Management-Information-Program/dp/1597496154)** by Evan Wheeler - Comprehensive guide to building security risk programs.
- **[Security Chaos Engineering](https://www.oreilly.com/library/view/security-chaos-engineering/9781492080350/)** - Experimental approach to building security resilience.
- **[Third-Party Risk Management](https://www.amazon.com/Third-Party-Risk-Management-Practical-Enterprise/dp/1498753779)** - Best practices for vendor risk assessment and management.

**Privacy:**
- **[Data and Goliath: The Hidden Battles to Collect Your Data and Control Your World](https://www.amazon.com/Data-Goliath-Battles-Collect-Control/dp/039335217X)** by Bruce Schneier - Critical examination of privacy in the digital age.
- **[Privacy by Design: The 7 Foundational Principles](https://www.ipc.on.ca/wp-content/uploads/resources/7foundationalprinciples.pdf)** by Ann Cavoukian - Seminal work on privacy engineering principles.
- **[The Privacy Engineer's Manifesto](https://www.amazon.com/Privacy-Engineers-Manifesto-Building-Future/dp/1430263555)** - Practical approaches to privacy engineering.
- **[Information Privacy: A Practical Guide](https://www.amazon.com/Information-Privacy-Practical-Guide-Executives/dp/1881334759)** - Accessible introduction to privacy compliance.
- **[Privacy by Design](https://www.manning.com/books/privacy-by-design)** by Nishant Bhajaria - Privacy engineering methodology.
- **[The Algorithmic Foundations of Differential Privacy](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf)** - Technical privacy-preserving techniques (free PDF).
- **[Differential Privacy: A Primer for a Non-technical Audience](https://privacytools.seas.harvard.edu/files/privacytools/files/pedagogical-document-dp_new.pdf)** - Accessible introduction to differential privacy concepts.
- **[The Complexity of Differential Privacy](http://privacytools.seas.harvard.edu/files/privacytools/files/complexityprivacy_1.pdf)** - Advanced differential privacy theory and complexity.
- **[Lectures on Data Security - Modern Cryptology in Theory and Practice](https://www.springer.com/us/book/9783540657576)** - Data security and cryptology fundamentals.
- **[The Art of Invisibility](https://www.amazon.com/Art-Invisibility-Worlds-Teaches-Brother/dp/0316380504)** by Kevin Mitnick - How to protect privacy in the age of big data and surveillance.
- **[Permanent Record](https://amzn.to/30wxxXi)** by Edward Snowden - Personal account of surveillance and privacy.
- **[Sandworm](https://amzn.to/2FVByeJ)** by Andy Greenberg - Cybersecurity threats and state-sponsored attacks.

**Governance & Risk Management:**
- **[Absolute Essentials of Corporate Governance](https://github.com/user-attachments/files/15688633/Absolute.Essentials.of.Business.and.Economics.Stephen.Bloomfield.-.Absolute.Essentials.of.Corporate.Governance-Routledge.2020.pdf)** by Stephen Bloomfield - Beginner-friendly guide to corporate governance principles and risk management.
- **[Corporate Governance: Principles, Policies, and Practices](https://github.com/user-attachments/files/15937929/E.K.Satheesh.K.P.Muraleedharan.A.C.Fernando.-.Corporate.Governance_.Principles.Policies.and.Practices-Pearson.India.2018.pdf)** by E. K. Satheesh, K. P. Muraleedharan, and A. C. Fernando - Comprehensive exploration of corporate governance for advanced professionals.
- **[GRC For Dummies](https://github.com/user-attachments/files/15688457/Broady.Denise.Vu_Roland.Holly.A.-.Sap.grc.for.dummies-John.Wiley.Sons.2013.pdf)** by Denise Vu Broady and Holly A. Roland - Accessible introduction to governance, risk, and compliance fundamentals.
- **[Governance, Risk Management, and Compliance: It Can't Happen to Us](https://github.com/user-attachments/files/15687876/Richard.M.Steinberg.auth.-.Governance.Risk.Management.and.Compliance_.It.Can.t.Happen.to.Us.-.Avoiding.Corporate.Disaster.While.Driving.Success.pdf)** by Richard M. Steinberg - Foundational GRC book with real-world examples.
- **[Enterprise Risk Management: From Incentives to Controls](https://github.com/user-attachments/files/15688444/James.Lam.-.Enterprise.Risk.Management_.From.Incentives.to.Controls-Wiley.2014.pdf)** by James Lam - Comprehensive ERM introduction.
- **[Implementing Enterprise Risk Management: From Methods to Applications](https://github.com/user-attachments/files/15937827/Wiley.finance.series.Lam.James.-.Implementing.enterprise.risk.management._.from.methods.to.applications-John.Wiley.Sons.2017.pdf)** by James Lam - Advanced ERM methodologies and applications.
- **[COSO Enterprise Risk Management: Establishing Effective Governance, Risk, and Compliance Processes](https://github.com/user-attachments/files/15748308/Robert.R.Moeller.-.COSO.Enterprise.Risk.Management_.Establishing.Effective.Governance.Risk.and.Compliance.Processes.-John.Wiley.Sons.2011.pdf)** by Robert R. Moeller - Deep dive into COSO framework implementation.
- **[Risk Management: A Very Short Introduction](https://github.com/user-attachments/files/15688535/Very.Short.Introductions.267.Fischhoff.Baruch_.Kadvany.John.-.Risk_.A.Very.Short.Introduction-Oxford.University.Press.2011.pdf)** by Baruch Fischhoff and John Kadvany - Concise risk management primer.
- **[The Essentials of Risk Management](https://github.com/user-attachments/files/15688630/Michel.Crouhy.Dan.Galai.Robert.Mark.-.The.Essentials.of.Risk.Management-McGraw-Hill.2014.pdf)** by Michel Crouhy, Dan Galai, and Robert Mark - Overview of key risk management concepts.
- **[Operational Risk Management: A Complete Guide to a Successful Operational Risk Framework](https://github.com/user-attachments/files/15748616/Philippa.X.Girling.-.Operational.Risk.Management_.A.Complete.Guide.to.a.Successful.Operational.Risk.Framework-Wiley.2013.pdf)** by Philippa X. Girling - Detailed operational risk guidance.
- **[Operational Risk Management: Best Practices in the Financial Services Industry](https://github.com/user-attachments/files/15937893/Wiley.finance.series.Chapelle.Ariane.-.Operational.risk.management_.best.practices.in.the.financial.services.industry.2019.pdf)** by Ariane Chapelle - Advanced operational risk practices.
- **[Implementing Enterprise Risk Management: Case Studies and Best Practices](https://github.com/user-attachments/files/15937938/Robert.W.Kolb.series.in.finance.Fraser.John.R.S._Narvaez.Kristina_Simkins.Betty.J.-.Implementing.enterprise.risk.management_.case.studies.and.best.practices-Wiley.2015_2014.pdf)** edited by John Fraser, Kristina Narvaez, and Betty J. Simkins - ERM research and best practices.
- **[Measuring and Managing Information Risk: A FAIR Approach](https://www.amazon.com/Measuring-Managing-Information-Risk-Approach/dp/0124202314)** - Quantitative risk analysis using FAIR methodology.
- **[How to Measure Anything in Cybersecurity Risk](https://www.amazon.com/How-Measure-Anything-Cybersecurity-Risk/dp/1119085292)** - Quantitative approaches to security risk.

**IT Governance:**
- **[IT Governance: How Top Performers Manage IT Decision Rights for Superior Results](https://github.com/user-attachments/files/15748408/Peter.Weill.Jeanne.Ross.-.IT.Governance_.How.Top.Performers.Manage.IT.Decision.Rights.for.Superior.Results.2004._compressed.pdf)** by Peter Weill and Jeanne Ross - Case studies and frameworks for IT governance excellence.
- **[IT Governance: An International Guide to Data Security and ISO 27001/ISO 27002](https://github.com/user-attachments/files/15937869/Steve.Watkins_.Alan.Calder.-.IT.governance._.an.international.guide.to.data.security.and.ISO.27001_ISO.27002.2020.pdf)** by Alan Calder and Steve Watkins - Comprehensive guide to IT governance and ISO standards.
- **[Governance, Risk, and Compliance Handbook for Oracle Applications](https://github.com/user-attachments/files/15748622/Nigel.King.Adil.R.Khan.-.Governance.Risk.and.Compliance.Handbook.for.Oracle.Applications-Packt.Publishing.2012.pdf)** by Nigel King and Adil R Khan - Practical GRC implementation for Oracle environments.
- **[Financial Management for IT Services Complete Self-Assessment Guide](https://github.com/user-attachments/files/15937879/Blokdyk.Gerardus.-.Financial.Management.for.It.Services.Complete.Self-Assessment.Guide-Createspace.Independent.Publishing.Platform.2017.pdf)** by Gerardus Blokdyk - IT financial management framework and self-assessment.

**Career Development:**
- **[Cybersecurity Cannon](https://icdt.osu.edu/cybercanon/bookreviews)** - Must-read books for cybersecurity professionals.

### Podcasts

- **[Security & Compliance Weekly](https://securityweekly.com/)** - Weekly news and discussion on security and compliance topics.
- **[Risk, Governance and Cyber Compliance](https://www.riskgovernanceandcybercompliance.com/)** - Deep dives into GRC topics.
- **[The GRC Podcast](https://www.auditboard.com/podcast)** - Governance, risk, and compliance discussions by AuditBoard.
- **[CISO Series](https://cisoseries.com/)** - Podcasts for security and compliance leaders.
- **[Cloud Security Podcast](https://cloudsecuritypodcast.tv/)** - Google's cloud security podcast.
- **[Risky Business](https://risky.biz/)** - Information security news and analysis.
- **[The Privacy, Security, & OSINT Show](https://inteltechniques.com/podcast.html)** - Privacy and security techniques.
- **[Unsupervised Learning](https://podcasts.apple.com/us/podcast/unsupervised-learning/id1099711235)** - Daniel Miessler's security and technology insights.
- **[CISO Tradecraft](https://www.cisotradecraft.com/episode-list)** - Practical CISO leadership and management.
- **[Life of a CISO](https://podcasts.apple.com/us/podcast/life-of-a-ciso-with-dr-eric-cole/id1458386656)** - CISO career and leadership with Dr. Eric Cole.
- **[Bulletproof Cyber](https://podcasts.apple.com/us/podcast/bulletproof-cyber/id1690068665)** - Cybersecurity strategies and insights.
- **[The New CISO](https://podcasts.apple.com/us/podcast/the-new-ciso/id1460075361)** - Modern CISO challenges and approaches.
- **[Hacker Valley Studio](https://hackervalley.com/)** - Security culture and career development.
- **[Resilient Cyber](https://podcasts.apple.com/us/podcast/resilient-cyber/id1555928024)** - Cybersecurity resilience strategies.
- **[The Cyberlaw Podcast](https://podcasts.apple.com/us/podcast/the-cyberlaw-podcast/id830593115)** - Legal aspects of cybersecurity.
- **[Down the Security Rabbithole](https://podcasts.apple.com/us/podcast/down-the-security-rabbithole-podcast-dtsr/id466659176)** - Technical security deep dives.
- **[The Cloudcast](https://www.thecloudcast.net/)** - Cloud computing and security.
- **[Software Defined Talk](https://www.softwaredefinedtalk.com/)** - Cloud, containers, and DevOps.
- **[Cloud Security Today](https://www.cloudsecuritytoday.com/)** - Daily cloud security news and insights.
- **[Cloud Computing Insider](https://podcasts.apple.com/us/podcast/cloud-computing-insider/id1752181924)** - Cloud trends and technology.
- **[Heavy Strategy](https://podcasts.apple.com/us/podcast/heavy-strategy/id1536001488)** - Strategic security thinking.
- **[The Cyber Ranch Podcast](https://podcasts.apple.com/us/podcast/the-cyber-ranch-podcast/id1549705840)** - Cybersecurity for all levels.

### Newsletters

- **[Unsupervised Learning - Daniel Miessler](https://danielmiessler.com/)** - Weekly insights on security, technology, and meaning.
- **[CloudSecList - Marco Lancini](https://cloudseclist.com/)** - Weekly cloud security news and resources.
- **[TLDR Sec - Clint Gibler](https://tldrsec.com/)** - Weekly top security links for busy people.
- **[SANS Cyber Security Newsletters](https://www.sans.org/newsletters/)** - Multiple specialized security newsletters.
- **[Wall Street Journal - Cybersecurity](https://www.wsj.com/newsletters)** - Business perspective on cybersecurity news.
- **[Detection Engineering Weekly](https://www.detectionengineering.net/)** - Detection engineering best practices and tools.
- **[Venture in Security](https://ventureinsecurity.net/)** - Security industry trends and analysis.
- **[Return on Security](https://www.returnonsecurity.com/)** - Strategic security leadership insights.

### Tutorials & Videos

- **[Simons Institute - Differential Privacy Tutorial](https://www.youtube.com/watch?v=ekIL65D0R3o)** - Comprehensive differential privacy introduction.
- **[Microsoft Research - Differential Privacy Series](https://www.youtube.com/playlist)** - Five-part differential privacy video series.
- **[CERIAS Purdue - Practical Beginners' Guide to Differential Privacy](https://www.youtube.com/watch?v=Gx13lgEudtU)** - Practical differential privacy implementation.
- **[USENIX - Differential Privacy: From Theory to Deployment](https://www.youtube.com/watch?v=Nvy-TspgZMs)** - Real-world differential privacy deployment.

## Certifications

**Security:**
- **[CISSP](https://www.isc2.org/Certifications/CISSP)** - Certified Information Systems Security Professional by (ISC)².
- **[CISM](https://www.isaca.org/credentialing/cism)** - Certified Information Security Manager by ISACA.
- **[CISA](https://www.isaca.org/credentialing/cisa)** - Certified Information Systems Auditor by ISACA.
- **[CEH](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)** - Certified Ethical Hacker by EC-Council.
- **[Security+](https://www.comptia.org/certifications/security)** - CompTIA Security+ entry-level certification.

**Privacy:**
- **[CIPP](https://iapp.org/certify/cipp/)** - Certified Information Privacy Professional by IAPP.
- **[CIPM](https://iapp.org/certify/cipm/)** - Certified Information Privacy Manager by IAPP.
- **[CIPT](https://iapp.org/certify/cipt/)** - Certified Information Privacy Technologist by IAPP.

**GRC & Audit:**
- **[CRISC](https://www.isaca.org/credentialing/crisc)** - Certified in Risk and Information Systems Control by ISACA.
- **[CGEIT](https://www.isaca.org/credentialing/cgeit)** - Certified in the Governance of Enterprise IT by ISACA.
- **[CIA](https://www.theiia.org/en/certifications/cia/)** - Certified Internal Auditor by IIA.

**Cloud:**
- **[CCSP](https://www.isc2.org/Certifications/CCSP)** - Certified Cloud Security Professional by (ISC)².
- **[AWS Security Specialty](https://aws.amazon.com/certification/certified-security-specialty/)** - AWS Certified Security Specialty.
- **[Azure Security Engineer](https://learn.microsoft.com/en-us/certifications/azure-security-engineer/)** - Microsoft Azure Security Engineer Associate.

**Career Resources:**
- **[Paul Jerimy Security Certification Roadmap](https://pauljerimy.com/security-certification-roadmap/)** - Comprehensive visualization of security certification paths.
- **[NICE Cybersecurity Workforce Framework](https://niccs.cisa.gov/workforce-development/nice-framework)** - National framework for cybersecurity career paths and roles.

## Community & Organizations

**Professional Organizations:**
- **[IAPP](https://iapp.org/)** - International Association of Privacy Professionals.
- **[ISACA](https://www.isaca.org/)** - Information Systems Audit and Control Association.
- **[(ISC)²](https://www.isc2.org/)** - International Information System Security Certification Consortium.
- **[FAIR Institute](https://www.fairinstitute.org/)** - Advancing quantitative risk management.
- **[Cloud Security Alliance](https://cloudsecurityalliance.org/)** - Promoting best practices in cloud security.
- **[ISSA](https://www.issa.org/)** - Information Systems Security Association.
- **[InfraGard](https://www.infragard.org/)** - Partnership between FBI and private sector for cybersecurity.

**Forums & Communities:**
- **[ISO 27001 Forum](https://www.iso27001security.com/html/forum.html)** - Community for ISO 27001 practitioners.
- **[r/compliance](https://www.reddit.com/r/compliance/)** - Reddit compliance community.
- **[r/privacy](https://www.reddit.com/r/privacy/)** - Privacy discussion and news.
- **[r/netsec](https://www.reddit.com/r/netsec/)** - Network security community.
- **[r/AskNetsec](https://www.reddit.com/r/AskNetsec/)** - Security Q&A community.

**Advocacy & Research:**
- **[Electronic Frontier Foundation](https://www.eff.org/)** - Digital rights and privacy advocacy.
- **[Privacy International](https://privacyinternational.org/)** - Defending privacy worldwide.
- **[NOYB](https://noyb.eu/)** - European privacy enforcement organization.
- **[EPIC](https://epic.org/)** - Electronic Privacy Information Center.
- **[Future of Privacy Forum](https://fpf.org/)** - Privacy research and advocacy.
- **[Center for Democracy & Technology](https://cdt.org/)** - Digital rights and civil liberties.

## Guides & Best Practices

### Security Guides

- **[OWASP Top 10](https://owasp.org/www-project-top-ten/)** - Top 10 web application security risks.
- **[OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)** - Concise security guidance for developers.
- **[SANS Security Policy Templates](https://www.sans.org/information-security-policy/)** - Free security policy templates.
- **[CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks/)** - Configuration security benchmarks for systems and applications.
- **[Microsoft Security Baselines](https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-security-configuration-framework/windows-security-baselines)** - Recommended security configurations for Microsoft products.
- **[NIST SP 800-63](https://pages.nist.gov/800-63-3/)** - Digital Identity Guidelines.
- **[NIST SP 800-207](https://csrc.nist.gov/publications/detail/sp/800-207/final)** - Zero Trust Architecture.
- **[Cloud Security Alliance Security Guidance](https://cloudsecurityalliance.org/research/guidance/)** - Best practices for cloud security.

### Privacy Guides

- **[CNIL GDPR Developer Guide](https://www.cnil.fr/en/gdpr-developers-guide)** - Privacy by design for developers.
- **[Norwegian DPA Software Development with Data Protection](https://www.datatilsynet.no/en/)** - Privacy in software development lifecycle.
- **[ENISA Privacy and Data Protection by Design](https://www.enisa.europa.eu/publications/privacy-and-data-protection-by-design)** - Privacy engineering methodologies.
- **[ENISA Pseudonymisation Techniques](https://www.enisa.europa.eu/publications/pseudonymisation-techniques-and-best-practices)** - Best practices for pseudonymisation.
- **[ICO Data Protection Impact Assessments](https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/accountability-and-governance/data-protection-impact-assessments/)** - UK guidance on DPIAs.
- **[EDPB Guidelines](https://edpb.europa.eu/our-work-tools/general-guidance_en)** - European Data Protection Board GDPR guidance.
- **[IAPP Privacy Program Management Tools](https://iapp.org/resources/topics/privacy-program-management/)** - Templates and frameworks for privacy programs.
- **[OWASP User Privacy Protection Cheat Sheet](https://www.owasp.org/index.php/User_Privacy_Protection_Cheat_Sheet)** - Security and privacy best practices for user data protection.
- **[Mobile Privacy Guide for App Developers](https://www.oaic.gov.au/resources/agencies-and-organisations/guides/guide-for-mobile-app-developers.pdf)** - Australian guide for mobile app privacy.
- **[Securing Personal Information: Self-Assessment Tool](https://www.oipc.bc.ca/guidance-documents/1439)** - Organizational privacy self-assessment tool.
- **[Reasonable Security Checklist for Personal Information](https://oipc.novascotia.ca/sites/default/files/publications/Reasonable%20Security%20Checklist%20for%20Personal%20Information%20(22%20Sept%2015)_0.pdf)** - Privacy security checklist.
- **[Pro Privacy: Encryption for Privacy Guide](https://proprivacy.com/guides/the-ultimate-privacy-guide)** - Comprehensive encryption and privacy guide.
- **[EFF: Surveillance Self-Defense](https://ssd.eff.org)** - Electronic Frontier Foundation's guide to protecting against surveillance.
- **[Privacy Patterns](https://privacypatterns.org/)** - Software engineering design patterns for privacy problems.

### Incident Management

- **[NIST SP 800-61](https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final)** - Computer Security Incident Handling Guide.
- **[ENISA Incident Management](https://www.enisa.europa.eu/topics/incident-response)** - Good practice guide for incident management.
- **[CISA Incident Response Playbooks](https://www.cisa.gov/cyber-incident-response)** - Federal incident response guidance and playbooks.
- **[SANS Incident Handler's Handbook](https://www.sans.org/white-papers/33901/)** - Step-by-step incident response procedures.
- **[PagerDuty Incident Response](https://response.pagerduty.com/)** - Open source incident response documentation.
- **[No More Ransom Project](https://www.nomoreransom.org/en/index.html)** - Public-private partnership with ransomware defense resources.
- **[Institute for Security and Technology - Ransomware Defense](https://securityandtechnology.org/ransomwaretaskforce/blueprint-for-ransomware-defense/)** - Blueprint for ransomware defense.
- **[CISA Stop Ransomware Resources](https://www.cisa.gov/stopransomware/resources)** - Comprehensive ransomware prevention and response resources.
- **[OSINT Framework](https://osintframework.com/)** - Open source intelligence gathering tools and resources.
- **[VirusTotal](https://www.virustotal.com)** - File and URL analysis for malware detection.
- **[Shodan](https://www.shodan.io/)** - Search engine for Internet-connected devices.
- **[Web Check](https://web-check.xyz/)** - Website security and configuration analysis.
- **[MITRE Sensor Mappings to ATT&CK](https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/sensor-mappings-to-attack/)** - Mapping security sensors to adversary techniques.
- **[Cybersecurity Incident Tracker](https://www.board-cybersecurity.com/incidents/tracker/)** - Track major cybersecurity incidents.
- **[Microsoft Incident Response Ninja Hub](https://techcommunity.microsoft.com/t5/microsoft-security-experts-blog/welcome-to-the-microsoft-incident-response-ninja-hub/ba-p/4243594)** - Microsoft IR resources and tools.
- **[DHS Harmonization of Cyber Incident Reporting](https://www.dhs.gov/publication/harmonization-cyber-incident-reporting-federal-government)** - Federal incident reporting requirements inventory.
- **[NCSL Security Breach Legislation](https://www.ncsl.org/technology-and-communication/2022-security-breach-legislation)** - US state breach notification laws.

### Policy Templates

- **[SANS Security Policy Templates](https://www.sans.org/information-security-policy/)** - Free security policy templates for 40+ topics.
- **[North Carolina Statewide Information Security Policies](https://it.nc.gov/programs/cybersecurity-risk-management/esrmo-initiatives/statewide-information-security-policies)** - Comprehensive state policies aligned with NIST 800-53.
- **[Information Security Policies and Procedures: A Practitioner's Reference](https://github.com/user-attachments/files/15748664/Dimitris.N.Chorafas.-.Information.Security.Policies.and.Procedures_.A.Practitioner.s.Reference-Auerbach.Publications.1998.pdf)** by Dimitris N. Chorafas - Comprehensive guide to producing complete sets of security policies and procedures.
- **[Building an Information Security Awareness Program](https://www.amazon.com/Building-Information-Security-Awareness-Program/dp/0849322650)** - Creating effective security training programs and policies.

### Implementation Guides

- **[ISO27001.zip](https://github.com/opencontrol/compliance-masonry)** - Open-source ISO 27001 implementation templates.
- **[SOC2.fyi](https://soc2.fyi/)** - Free SOC 2 compliance guide.
- **[DPIA Templates](https://iapp.org/resources/article/sample-dpia-template/)** - Data Protection Impact Assessment templates.
- **[Privacy Notice Templates](https://iapp.org/resources/article/privacy-notice-template-generator/)** - IAPP privacy notice generator.
- **[NIST Privacy Framework Implementation Guide](https://www.nist.gov/privacy-framework/resource-repository)** - Tools for implementing NIST Privacy Framework.
- **[FedRAMP Templates](https://www.fedramp.gov/documents-templates/)** - Official FedRAMP documentation templates.
- **[CMMC Assessment Guides](https://www.acq.osd.mil/cmmc/documentation.html)** - Official CMMC assessment documentation.

### Compliance Artifacts & Reports

- **[AWS Artifact](https://aws.amazon.com/artifact/)** - Access AWS compliance reports (SOC, ISO, PCI, etc.).
- **[Azure Compliance](https://learn.microsoft.com/en-us/azure/compliance/)** - Microsoft Azure compliance documentation and reports.
- **[GCP Compliance](https://cloud.google.com/security/compliance)** - Google Cloud compliance resources and certifications.
- **[Unified Compliance Framework](https://www.unifiedcompliance.com/)** - Common Controls Hub with 1000+ mapped authorities (Commercial).
- **[NIST OSCAL](https://pages.nist.gov/OSCAL/)** - Open Security Controls Assessment Language for machine-readable compliance.
- **[OpenControl](http://open-control.org/)** - YAML-based compliance documentation framework.
- **[ComplianceForge](https://www.complianceforge.com/)** - Commercial policy libraries and toolkits for multiple frameworks.
- **[SANS Security Policy Project](https://www.sans.org/information-security-policy/)** - Free sample security policies for 40+ topics.
- **[Regulations.gov](https://www.regulations.gov/)** - US federal regulations repository.

### Cheat Sheets

- **[SANS - Ultimate List of SANS Cheat Sheets](https://www.sans.org/blog/the-ultimate-list-of-sans-cheat-sheets/)** - Comprehensive collection of security cheat sheets.
- **[SANS Posters & Cheat Sheets](https://www.sans.org/posters/?msc=Cheat%20Sheet%20Blog)** - Visual security reference materials.
- **[Google Cloud Incident Response Cheat Sheet](https://medium.com/google-cloud/google-cloud-incident-response-cheat-sheet-dfde9054ac16)** - Quick reference for GCP incident response.

### Additional Resources

- **[CISA Resources](https://www.cisa.gov/resources-tools/resources)** - Comprehensive cybersecurity resources from CISA.
- **[CISA Free Cybersecurity Services and Tools](https://www.cisa.gov/resources-tools/resources/free-cybersecurity-services-and-tools)** - No-cost security tools and services.
- **[CISA High-Risk Communities Resources](https://www.cisa.gov/audiences/high-risk-communities)** - Targeted resources for high-risk organizations.
- **[NIST CSRC Projects](https://csrc.nist.gov/projects)** - All NIST Computer Security Resource Center projects.
- **[NIST Computer Security Resource Center](https://csrc.nist.gov/)** - Complete NIST security publications repository.
- **[Federal Register](https://www.federalregister.gov/)** - US federal regulations and rules.
- **[EUR-Lex](https://eur-lex.europa.eu/)** - Official EU legal documents and legislation database.
- **[ENISA Publications](https://www.enisa.europa.eu/publications)** - European cybersecurity guidance and research.
- **[G2 Product Reviews](https://www.g2.com/)** - Software and services product reviews and comparisons.
- **[FOIA Search Tools](https://www.foia.gov/)** - Freedom of Information Act document search.
- **[HIPAA COW](https://hipaacow.org/)** - HIPAA Collaborative of Wisconsin resources.
- **[CISO MindMap](https://rafeeqrehman.com/2023/03/25/ciso-mindmap-2023-what-do-infosec-professionals-really-do/)** - Visual reference for CISO responsibilities.
- **[Boston Consulting Group Strategy Frameworks](https://media-publications.bcg.com/HTML5Interactives/strategy_frameworks/History_of_Strategy_2015.html)** - Strategic planning frameworks.
- **[Microsoft CISO Workshop Training](https://learn.microsoft.com/en-us/security/ciso-workshop/the-ciso-workshop)** - Free CISO leadership training by Microsoft.
- **[CloudSecDocs](https://cloudsecdocs.com/)** - Cloud security documentation by Marco Lancini.
- **[UK NCSC Cyber Security Toolkit for Boards](https://www.ncsc.gov.uk/collection/board-toolkit)** - Board-level cybersecurity governance guidance.
- **[NIST Building a Cybersecurity Learning Program](https://csrc.nist.gov/pubs/sp/800/50/r1/final)** - Framework for security awareness training programs.
- **[DoD CIO Library](https://dodcio.defense.gov/library/)** - Department of Defense CIO policy and guidance documents.
- **[CIS Reasonable Cybersecurity Guide](https://www.cisecurity.org/insights/white-papers/reasonable-cybersecurity-guide)** - Practical cybersecurity guidance for organizations.
- **[Cybersecurity 10-K Tracker](https://www.board-cybersecurity.com/annual-reports/tracker/)** - Track cybersecurity disclosures in public company filings.
- **[NSA Enduring Security Framework](https://www.nsa.gov/About/Cybersecurity-Collaboration-Center/Enduring-Security-Framework/)** - Cross-sector cybersecurity collaboration resources.
- **[FDA Cybersecurity in Medical Devices](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-system-considerations-and-content-premarket-submissions)** - Medical device cybersecurity guidance.
- **[UK NCSC Risk Management Guidance](https://www.ncsc.gov.uk/collection/risk-management)** - UK national cyber security centre risk management resources.
- **[CISA Critical Infrastructure Sectors](https://www.cisa.gov/topics/critical-infrastructure-security-and-resilience/critical-infrastructure-sectors)** - Sector-specific risk management guidelines.
- **[CMMC Center of Awesomeness](https://www.cmmc-coa.com/)** - CMMC resources and community.
- **[CMMC Accreditation Body](https://cyberab.org/)** - Official CMMC assessor accreditation organization.
- **[SANS Cybersecurity Regulations Requirements](https://www.sans.org/blog/cybersecurity-regulations-risk-assessment-requirements/)** - Overview of regulatory risk assessment requirements.

## Tools & Platforms

### GRC Platforms

**Open Source:**
- **[Openlane](https://www.theopenlane.io/)** - Comprehensive compliance automation platform for SOC 2, ISO 27001, and custom frameworks (Apache-2.0). Transforms compliance from static annual process to continuous collaborative workflow with risk register, policy management, evidence lifecycle, and control validation. ([GitHub](https://github.com/theopenlane) | [Docs](https://docs.theopenlane.io/))
- **[Comply](https://github.com/strongdm/comply)** - SOC 2 compliance automation framework by StrongDM (Apache-2.0). Provides markdown-based policy templates and document pipeline for auditor-ready policies.
- **[Compliance Masonry](https://github.com/opencontrol/compliance-masonry)** - CLI tool to build compliance documentation using OpenControl YAML schema. Supports FedRAMP, NIST, and other frameworks.
- **[Auditree Framework](https://github.com/ComplianceAsCode/auditree-framework)** - IBM's framework for automated evidence collection and verification (Apache-2.0). Treats compliance checks as code with version-controlled evidence locker.
- **[Trestle](https://github.com/IBM/compliance-trestle)** - IBM's compliance-as-code toolset using NIST's OSCAL format. Manages compliance catalogs and automates documentation generation.
- **[InSpec](https://www.inspec.io/)** - Chef's compliance and security testing framework. Write automated compliance tests in Ruby DSL with pre-built profiles for CIS, DISA STIGs.
- **[OpenSCAP](https://www.open-scap.org/)** - Security Content Automation Protocol toolset for automated system scanning against SCAP benchmarks (Red Hat sponsored).
- **[Lynis](https://cisofy.com/lynis/)** - Security auditing tool for Unix/Linux systems. Performs host configuration scans and generates hardening reports.
- **[Cloud Custodian](https://cloudcustodian.io/)** - CNCF Sandbox rules engine for cloud compliance. Write policies in YAML to enforce and remediate violations in AWS, Azure, GCP.
- **[Prowler](https://github.com/prowler-cloud/prowler)** - AWS security and compliance scanner. Checks against AWS CIS Benchmark, GDPR, HIPAA, PCI DSS, SOC 2.
- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** - Multi-cloud security auditing tool by NCC Group. Detects misconfigurations in AWS, Azure, GCP.
- **[Steampipe](https://steampipe.io/)** - Query cloud and SaaS APIs as SQL tables. Includes compliance mod packs for CIS AWS Foundations, HIPAA, PCI.
- **[PacBot](https://github.com/tmobile/pacbot)** - T-Mobile's cloud compliance platform. Continuously monitors AWS for violations with auto-remediation capabilities.
- **[OSQuery](https://osquery.io/)** - Endpoint monitoring using SQL queries (Linux Foundation). Query running processes, configurations, and compliance-related data across fleet.
- **[Wazuh](https://wazuh.com/)** - Open source security platform with SIEM and HIDS capabilities. Provides compliance rule sets for PCI DSS, GDPR, HIPAA with reporting.
- **[CISO Assistant](https://github.com/intuitem/ciso-assistant-community)** - Open-source GRC app supporting 40+ frameworks. Manages risks, controls, audits with one-click audit reports.
- **[Comp AI](https://github.com/compai-org/compai)** - Open source compliance platform (AGPL-3.0) for SOC 2, ISO 27001, HIPAA, GDPR. Community-driven alternative to commercial tools.
- **[Eramba](https://www.eramba.org/)** - Enterprise GRC platform with free Community Edition. Modules for compliance, risk management, incidents, vendor assessments.
- **[Trivy](https://github.com/aquasecurity/trivy)** - Comprehensive security scanner for containers and IaC. Detects vulnerabilities, misconfigurations, secrets.
- **[kube-bench](https://github.com/aquasecurity/kube-bench)** - Checks Kubernetes clusters against CIS Kubernetes Benchmark.
- **[Kyverno](https://kyverno.io/)** - Kubernetes-native policy management. Enforce, validate, and mutate configurations.
- **[OPA Gatekeeper](https://open-policy-agent.github.io/gatekeeper/)** - Policy controller for Kubernetes using Open Policy Agent.
- **[Havengrc](https://havengrc.com/)** - Open-source GRC platform for compliance management.
- **[GGRC Core](https://github.com/google/ggrc-core)** - Google's governance, risk, and compliance platform (archived but historically significant).
- **[Govready](https://github.com/GovReady/govready-q)** - Open-source GRC platform for automated compliance assessments.
- **[Probo](https://github.com/ProboCI/probo)** - Open source compliance automation focused on continuous integration workflows.

**Commercial:**
- **[Drata](https://drata.com/)** - Cloud platform for continuous compliance monitoring and automation. Connects to tech stack for evidence collection. Supports SOC 2, ISO 27001, PCI DSS.
- **[Vanta](https://www.vanta.com/)** - Compliance automation platform for SOC 2, ISO 27001. Continuous monitoring with AI-powered questionnaire responses.
- **[Secureframe](https://secureframe.com/)** - End-to-end compliance platform for SOC 2, ISO 27001, HIPAA. Includes policy templates, evidence collection, training, auditor coordination.
- **[Tugboat Logic](https://www.onegrc.com/)** - Security assurance platform now part of OneTrust. Automated evidence collection and audit project management.
- **[Hyperproof](https://hyperproof.io/)** - Compliance operations platform for ongoing risk and compliance management. Workflow automation and continuous control monitoring.
- **[Sprinto](https://sprinto.com/)** - Automated compliance platform for SOC 2, ISO 27001, GDPR, HIPAA.
- **[Oneleet](https://oneleet.com/)** - Continuous compliance monitoring and automation platform.
- **[Scrut](https://scrut.io/)** - Automated compliance platform with integrations for real-time monitoring.
- **[Thoropass](https://thoropass.com/)** - Information security and compliance software.
- **[AuditBoard](https://www.auditboard.com/)** - Leading platform for audit and compliance management. One-stop solution for managing audits, controls, risks, and reporting.
- **[Archer](https://www.archerirm.com/)** - RSA's GRC platform widely used in enterprises.
- **[LogicGate](https://www.logicgate.com/)** - Risk Cloud platform tailored for IT Risk, Compliance, Third-Party Risk.
- **[MetricStream](https://www.metricstream.com/)** - Enterprise GRC platform for integrated risk management.
- **[Onspring](https://onspring.com/)** - No-code GRC platform for risk, compliance, and audit management.
- **[OneTrust](https://www.onetrust.com/)** - Privacy, security, and data governance platform. Extensive GRC suite including Vendorpedia.
- **[ServiceNow GRC](https://www.servicenow.com/products/governance-risk-compliance.html)** - Integrated risk and compliance management on ServiceNow platform.
- **[TrustCloud](https://trustcloud.ai/)** - GRC platform with free trust center offering. Compliance tracking with integrations. (Freemium)
- **[Benchmark ESG](https://www.benchmarkesg.com/)** - ESG data management and reporting platform.
- **[Diligent ESG](https://www.diligent.com/solutions/esg)** - ESG governance and reporting solution.
- **[Locus Technologies](https://www.locustec.com/)** - Environmental, health, safety, and sustainability management software.
- **[Novata](https://www.novata.com/)** - ESG data management for private markets.
- **[Novisto](https://www.novisto.com/)** - ESG reporting automation platform.
- **[Proof](https://www.proof.com/)** - ESG performance management platform.
- **[Sametrica](https://www.sametrica.com/)** - ESG impact measurement software.
- **[Workiva](https://www.workiva.com/)** - Cloud platform for ESG, financial, and compliance reporting.

### Reconnaissance & Response

**Open Source:**
- **[amass](https://github.com/OWASP/Amass)** - OWASP tool for network mapping and attack surface discovery.
- **[subfinder](https://github.com/projectdiscovery/subfinder)** - Fast passive subdomain enumeration tool.
- **[assetfinder](https://github.com/tomnomnom/assetfinder)** - Find domains and subdomains related to a target.
- **[nmap](https://nmap.org/)** - Network discovery and security auditing tool.
- **[masscan](https://github.com/robertdavidgraham/masscan)** - Fast TCP port scanner.
- **[httpx](https://github.com/projectdiscovery/httpx)** - Fast HTTP toolkit for web reconnaissance.
- **[nuclei](https://github.com/projectdiscovery/nuclei)** - Fast vulnerability scanner with customizable templates.
- **[metasploit](https://www.metasploit.com/)** - Penetration testing framework.
- **[sqlmap](https://sqlmap.org/)** - Automatic SQL injection and database takeover tool.
- **[dalfox](https://github.com/hahwul/dalfox)** - XSS scanner and parameter analysis tool.
- **[commix](https://github.com/commixproject/commix)** - Command injection exploitation tool.
- **[trufflehog](https://github.com/trufflesecurity/trufflehog)** - Find leaked credentials in repositories.
- **[gitleaks](https://github.com/gitleaks/gitleaks)** - Scan git repositories for secrets.
- **[detect-secrets](https://github.com/Yelp/detect-secrets)** - Enterprise-friendly secret detection tool.
- **[TheHive](https://thehive-project.org/)** - Open source Security Incident Response Platform (SIRP).
- **[GRR Rapid Response](https://github.com/google/grr)** - Google's incident response framework for remote forensics.
- **[Graylog](https://www.graylog.org/)** - Open source log management and SIEM platform. (Open Source/Commercial)
- **[OpenCTI](https://www.opencti.io/)** - Open source cyber threat intelligence platform.
- **[MISP](https://www.misp-project.org/)** - Malware Information Sharing Platform for threat intelligence sharing.

**Commercial:**
- **[Microsoft Azure Sentinel](https://azure.microsoft.com/en-us/services/azure-sentinel/)** - Cloud-native SIEM and SOAR platform.
- **[Sekoia.io XDR](https://www.sekoia.io/)** - Extended Detection and Response platform.
- **[Splunk](https://www.splunk.com/)** - Data analytics platform widely used as SIEM.
- **[IBM Resilient](https://www.ibm.com/security/intelligent-orchestration/resilient)** - Security Orchestration, Automation and Response (SOAR) platform.
- **[SwimLane](https://swimlane.com/)** - Security automation and orchestration platform.
- **[PAN Cortex XSOAR](https://www.paloaltonetworks.com/cortex/cortex-xsoar)** - Palo Alto Networks SOAR platform.
- **[Microsoft Logic Apps](https://azure.microsoft.com/en-us/services/logic-apps/)** - Cloud automation for workflows and SOA.

### Vulnerabilities & Threats

**Open Source:**
- **[OpenVAS](https://www.openvas.org/)** - Open vulnerability assessment scanner for security compliance testing.
- **[OSSEC](https://www.ossec.net/)** - Host-based intrusion detection system with compliance monitoring capabilities.
- **[grype](https://github.com/anchore/grype)** - Vulnerability scanner for container images and filesystems.

**Threat Intelligence & Vulnerability Databases:**
- **[MITRE ATT&CK](https://attack.mitre.org/)** - Knowledge base of adversary tactics and techniques.
- **[STIX](https://oasis-open.github.io/cti-documentation/)** - Structured Threat Information Expression for threat intelligence sharing.
- **[TAXII](https://oasis-open.github.io/cti-documentation/taxii/intro)** - Trusted Automated Exchange of Intelligence Information.
- **[TLP](https://www.cisa.gov/tlp)** - Traffic Light Protocol for information sharing.
- **[CVE](https://cve.mitre.org/)** - Common Vulnerabilities and Exposures database.
- **[CVSS](https://www.first.org/cvss/)** - Common Vulnerability Scoring System.
- **[CISA Known Exploited Vulnerabilities](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)** - Catalog of actively exploited vulnerabilities.
- **[NVD](https://nvd.nist.gov/)** - National Vulnerability Database by NIST.
- **[CAPEC](https://capec.mitre.org/)** - Common Attack Pattern Enumeration and Classification.
- **[NIST CVSS](https://nvd.nist.gov/vuln-metrics/cvss)** - Common Vulnerability Scoring System maintained by NIST.
- **[FIRST CVSS](https://www.first.org/cvss/)** - CVSS specification and calculator by FIRST.
- **[CVE Details](https://www.cvedetails.com/)** - Security vulnerability database with detailed CVE information.
- **[VulDB](https://vuldb.com/)** - Vulnerability database with threat intelligence.
- **[Exploit Database](https://www.exploit-db.com/)** - Archive of public exploits and vulnerable software by OffSec.
- **[MITRE Common Weakness Enumeration (CWE)](https://cwe.mitre.org/)** - Dictionary of software and hardware weakness types.

### Trust & Customer Assurance

**Open Source:**
- **[Openlane](https://www.theopenlane.io/)** - Open source trust center, questionnaire automation, and vendor risk management integrated with comprehensive compliance platform. (Apache-2.0)

**Commercial:**
- **[SafeBase](https://safebase.io/)** - Leading Trust Center as a Service platform (acquired by Drata). Host public-facing security portal with compliance certifications gated by NDAs.
- **[TrustCloud](https://trustcloud.ai/)** - Free trust center product. Host security documentation and compliance reports with optional NDA gating. (Freemium)
- **[Vanta Trust Center](https://www.vanta.com/)** - Built-in trust page showing real-time compliance status backed by continuous monitoring.
- **[Secureframe Trust Portal](https://secureframe.com/)** - Showcase security posture to customers via embedded portal.
- **[Whistic](https://www.whistic.com/)** - Vendor security review platform with public Whistic Profiles for trust sharing.
- **[Conveyor](https://www.conveyor.com/)** - AI-driven questionnaire automation using GPT. 95%+ accuracy on first-pass answers with cited responses. (Freemium)
- **[Loopio](https://www.loopio.com/)** - RFP response management with automated questionnaire database.
- **[RFPIO](https://www.rfpio.com/)** - Response management for RFPs including security questionnaires.
- **[1Password Answer](https://1password.com/)** - AI security questionnaire tool by 1Password with privacy-focused LLM.
- **[SecurityScorecard](https://securityscorecard.com/)** - External security rating platform. Continuously scans domain footprint and assigns letter grade A-F.
- **[BitSight](https://www.bitsight.com/)** - Security ratings using open-source intelligence and breach data. Used by cyber insurance and enterprises.
- **[RiskRecon](https://www.riskrecon.com/)** - Mastercard's third-party cyber risk platform with contextual security findings.
- **[Panorays](https://www.panorays.com/)** - Third-party risk management combining automated scanning with vendor questionnaires.
- **[OneTrust Vendorpedia](https://www.onetrust.com/)** - Database of companies with security profiles and completed questionnaires.
- **[CyberGRX Exchange](https://www.cybergrx.com/)** - Crowd-sourced third-party assessment exchange. Standardized assessments shared across clients.
- **[Prevalent](https://www.prevalent.net/)** - Third-party risk management platform with full workflow.
- **[ProcessUnity](https://www.processunity.com/)** - Vendor risk management and compliance platform.
- **[RiskOptics](https://www.reciprocity.com/)** - Reciprocity's GRC platform including vendor risk management.
- **[Nudge Security](https://www.nudgesecurity.com/)** - SaaS discovery and shadow IT detection for vendor risk assessment.

### Privacy & Data Protection Tools

**Open Source:**
- **[ARX](https://arx.deidentifier.org/)** - Open source data anonymization tool with extensive privacy models.
- **[Amnesia](https://amnesia.openaire.eu/)** - Data anonymization tool supporting k-anonymity, l-diversity, t-closeness.
- **[Anonymizer](https://github.com/DivanteLtd/anonymizer)** - Universal data anonymization tool for databases.
- **[sdcMicro](https://cran.r-project.org/web/packages/sdcMicro/)** - R package for statistical disclosure control.
- **[Microsoft Presidio](https://microsoft.github.io/presidio/)** - Context-aware PII detection and anonymization SDK.
- **[IBM Differential Privacy Library](https://github.com/IBM/differential-privacy-library)** - General-purpose library for differential privacy.
- **[Google Differential Privacy](https://github.com/google/differential-privacy)** - Google's differential privacy libraries in multiple languages.
- **[diffpriv](https://github.com/brubinstein/diffpriv)** - R package for differential privacy.
- **[TensorFlow Privacy](https://github.com/tensorflow/privacy)** - Library for training machine learning models with differential privacy.
- **[RAPPOR](https://github.com/google/rappor)** - Robust privacy-preserving data collection by Google.

## Security Architecture & Engineering

### Network Security

- **[OSI Model](https://en.wikipedia.org/wiki/OSI_model)** - Open Systems Interconnection reference model for network communications.
- **[IP Subnet Calculator](https://www.calculator.net/ip-subnet-calculator.html)** - Tool for calculating IP subnets and network addressing.
- **[TCP & UDP Ports List](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)** - Comprehensive list of network protocol ports.
- **[Wireshark](https://www.wireshark.org/)** - Network protocol analyzer for troubleshooting and analysis.
- **[ENISA DoS Attacks Threat Landscape](https://www.enisa.europa.eu/publications/enisa-threat-landscape-for-dos-attacks)** - Analysis of denial-of-service threat landscape.

### Cloud Security

**Cloud Provider Documentation:**
- **[Microsoft Security Documentation](https://learn.microsoft.com/en-us/security/)** - Comprehensive Microsoft security documentation and best practices.
- **[Azure Security Documentation](https://learn.microsoft.com/en-us/azure/security/)** - Azure-specific security guidance and resources.
- **[AWS Security Documentation](https://docs.aws.amazon.com/security/)** - AWS security best practices and implementation guides.
- **[Google Cloud Security Overview](https://cloud.google.com/docs/security/overview/whitepaper)** - GCP security whitepaper and overview.
- **[AWS to Azure Services Comparison](https://learn.microsoft.com/en-us/azure/architecture/aws-professional/services)** - Service comparison for multi-cloud environments.
- **[AWS Services in Plain English](https://expeditedsecurity.com/aws-in-plain-english/)** - Simple explanations of AWS services.
- **[Microsoft Cloud Security Benchmark](https://learn.microsoft.com/en-us/security/benchmark/azure/)** - Security benchmark for Microsoft cloud services.

**Cloud Architecture & Frameworks:**
- **[Cloud Security Alliance Enterprise Architecture Reference Guide](https://cloudsecurityalliance.org/artifacts/enterprise-architecture-reference-guide-v2/)** - Reference architecture for enterprise cloud security.
- **[Microsoft Cybersecurity Reference Architectures](https://learn.microsoft.com/en-us/security/cybersecurity-reference-architecture/mcra)** - Comprehensive cybersecurity reference architecture.
- **[AWS Security Reference Architecture](https://docs.aws.amazon.com/prescriptive-guidance/latest/security-reference-architecture/welcome.html)** - AWS security architecture best practices.
- **[Google Cloud Architecture Framework - Security](https://cloud.google.com/architecture/framework/security)** - GCP security architecture principles.
- **[CISA Cloud Security Technical Reference Architecture](https://www.cisa.gov/resources-tools/resources/cloud-security-technical-reference-architecture)** - Federal cloud security architecture guidance.
- **[Azure Well-Architected Framework](https://learn.microsoft.com/en-us/azure/well-architected/)** - Azure architecture best practices including security.
- **[AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)** - AWS architecture best practices with security pillar.
- **[Google Cloud Architecture Framework](https://cloud.google.com/architecture/framework)** - GCP holistic architecture framework.
- **[CISA Secure Cloud Business Applications (SCuBA)](https://www.cisa.gov/resources-tools/services/secure-cloud-business-applications-scuba-project)** - Guidance for securing cloud business applications.
- **[DoD Cloud Computing Security](https://public.cyber.mil/dccs/)** - DoD cloud security requirements and guidance.
- **[Wiz Cloud Threat Landscape](https://threats.wiz.io/)** - Real-time cloud threat intelligence.
- **[NSA Top Ten Cloud Security Mitigation Strategies](https://www.nsa.gov/Press-Room/Press-Releases-Statements/Press-Release-View/Article/3699169/nsa-releases-top-ten-cloud-security-mitigation-strategies/)** - NSA cloud security guidance.
- **[Cloud Security Maturity Model v2](https://www.iansresearch.com/resources/cloud-security-maturity-model)** - IANS, Securosis, CSA cloud security maturity assessment.

**Shared Responsibility Models:**
- **[Azure Shared Responsibility](https://learn.microsoft.com/en-us/azure/security/fundamentals/shared-responsibility)** - Azure shared responsibility model explanation.
- **[AWS Shared Responsibility](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/shared-responsibility.html)** - AWS shared responsibility model for security.
- **[GCP Shared Responsibility](https://cloud.google.com/architecture/framework/security/shared-responsibility-shared-fate)** - GCP shared responsibility and shared fate model.

**Cloud Compliance Resources:**
- **[Azure Compliance Offerings](https://learn.microsoft.com/en-us/compliance/regulatory/offering-home)** - Complete list of Azure compliance certifications.
- **[AWS Compliance Programs](https://aws.amazon.com/compliance/programs)** - AWS compliance certifications and programs.
- **[GCP Compliance Offerings](https://cloud.google.com/security/compliance/offerings)** - Google Cloud compliance certifications.
- **[Microsoft Service Trust Portal](https://servicetrust.microsoft.com/)** - Access Microsoft compliance reports and resources.
- **[AWS Artifact](https://aws.amazon.com/artifact/)** - On-demand access to AWS compliance reports.

### Threat Modeling

- **[NIST Systems Security Engineering](https://csrc.nist.gov/projects/systems-security-engineering-project)** - Comprehensive systems security engineering guidance.
- **[CMS Threat Modeling Handbook](https://security.cms.gov/policy-guidance/threat-modeling-handbook)** - Practical threat modeling guidance.
- **[Threat Modeling - Adam Shostack](https://shostack.org/resources/threat-modeling)** - Comprehensive threat modeling resources and methodologies.
- **[STRIDE Threat Model](https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-threats)** - Microsoft STRIDE threat modeling methodology.
- **[DREAD Threat Modeling](https://threat-modeling.com/dread-threat-modeling/)** - DREAD risk assessment methodology.
- **[MITRE ATT&CK Enterprise](https://attack.mitre.org/matrices/enterprise/)** - Enterprise adversary tactics and techniques matrix.
- **[MITRE ATT&CK Cloud](https://attack.mitre.org/matrices/enterprise/cloud/)** - Cloud-specific adversary techniques.
- **[MITRE ATT&CK Network](https://attack.mitre.org/matrices/enterprise/network/)** - Network-based adversary techniques.
- **[MITRE EMB3D Threat Model](https://emb3d.mitre.org/)** - Embedded device threat modeling framework.
- **[MITRE ATLAS](https://atlas.mitre.org/)** - Adversarial Threat Landscape for AI Systems.
- **[Universal Cloud Threat Model](https://securosis.com/research/papers/the-universal-cloud-threat-model-for-cloud-native-security/)** - Comprehensive cloud-native threat model.
- **[Cyber Kill Chain](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html)** - Lockheed Martin's framework for understanding cyberattacks.
- **[ENISA Threat Landscape Methodology](https://www.enisa.europa.eu/publications/enisa-threat-landscape-methodology)** - European threat landscape analysis methodology.

### Identity & Access Management

**Zero Trust Architecture:**
- **[Zero Trust - US Government](https://zerotrust.cyber.gov/)** - Federal zero trust strategy and resources.
- **[NIST Zero Trust Architecture (SP 800-207)](https://www.nist.gov/publications/zero-trust-architecture)** - NIST zero trust architecture standard.
- **[Microsoft Zero Trust](https://www.microsoft.com/en-us/security/business/zero-trust)** - Microsoft's zero trust framework and implementation.
- **[Microsoft Entra ID - Identity Standards](https://learn.microsoft.com/en-us/azure/active-directory/standards/)** - Implement identity standards with Microsoft Entra ID.
- **[Federal Zero Trust Strategy](https://zerotrust.cyber.gov/federal-zero-trust-strategy/)** - US federal government zero trust strategy.
- **[Zero Trust Maturity Model](https://zerotrust.cyber.gov/zero-trust-maturity-model/)** - CISA zero trust maturity assessment model.
- **[CISA Zero Trust Maturity Model](https://www.cisa.gov/zero-trust-maturity-model)** - CISA's detailed zero trust maturity guidance.
- **[DoD Zero Trust Reference Architecture](https://dodcio.defense.gov/Portals/0/Documents/Library/(U)ZT_RA_v2.0(U)_Sep22.pdf)** - Department of Defense zero trust architecture.
- **[DoD Zero Trust Strategy](https://dodcio.defense.gov/Portals/0/Documents/Library/DoD-ZTStrategy.pdf)** - DoD strategy for zero trust implementation.
- **[DoD Zero Trust Capability Execution Roadmap](https://dodcio.defense.gov/Portals/0/Documents/Library/ZTCapabilitiesActivities.pdf)** - DoD zero trust implementation roadmap.
- **[DHS Zero Trust Implementation Strategy](https://www.dhs.gov/publication/zero-trust-implementation-strategy)** - Department of Homeland Security zero trust strategy.
- **[NSA Data Pillar Zero Trust](https://media.defense.gov/2024/Apr/09/2003434442/-1/-1/0/CSI_DATA_PILLAR_ZT.PDF)** - NSA guidance on zero trust data protection.

**Remote Access Security:**
- **[CISA Guide to Securing Remote Access Software](https://www.cisa.gov/resources-tools/resources/guide-securing-remote-access-software)** - Best practices for remote access security.

### Supply Chain Security

- **[NIST Software Supply Chain Security Guidance](https://www.nist.gov/itl/executive-order-14028-improving-nations-cybersecurity/software-supply-chain-security-guidance)** - Federal guidance on software supply chain security.
- **[NIST Cybersecurity Supply Chain Risk Management](https://csrc.nist.gov/projects/cyber-supply-chain-risk-management)** - C-SCRM framework and resources.
- **[CISA ICT Supply Chain Risk Management](https://www.cisa.gov/information-and-communications-technology-supply-chain-risk-management)** - ICT supply chain risk guidance.
- **[MITRE System of Trust](https://sot.mitre.org/framework/system_of_trust.html)** - Framework for establishing supply chain trust.
- **[Compliance Forge C-SCRM Implementation Plan](https://content.complianceforge.com/graphics/example-cybersecurity-scrm-prioritized-implementation-plan.pdf)** - Prioritized supply chain risk management implementation.
- **[ENISA Supply Chain Cybersecurity Best Practices](https://www.enisa.europa.eu/publications/good-practices-for-supply-chain-cybersecurity)** - European supply chain security guidance.
- **[CISA Software Bill of Materials (SBOM)](https://www.cisa.gov/sbom)** - SBOM guidance and resources.
- **[ESF Securing the Software Supply Chain](https://media.defense.gov/2023/Dec/11/2003355557/-1/-1/0/ESF_SECURING_THE_SOFTWARE_SUPPLY_CHAIN%20RECOMMENDED%20PRACTICES%20FOR%20MANAGING%20OPEN%20SOURCE%20SOFTWARE%20AND%20SOFTWARE%20BILL%20OF%20MATERIALS.PDF)** - DoD recommendations for OSS and SBOM.
- **[CISA Software Acquisition Guide](https://www.cisa.gov/resources-tools/resources/software-acquisition-guide-government-enterprise-consumers-software-assurance-cyber-supply-chain)** - Software assurance in acquisition lifecycle.

### Assessment & Testing

- **[Qualys Free Services](https://www.qualys.com/free-services/)** - Free security assessment and testing tools.
- **[OWASP](https://owasp.org/)** - Open Worldwide Application Security Project resources.
- **[OWASP Cheat Sheets](https://cheatsheetseries.owasp.org/index.html)** - Quick reference guides for secure development.
- **[NIST Secure Software Development Framework](https://csrc.nist.gov/projects/ssdf)** - Framework for integrating security into SDLC.
- **[NIST SP 800-84 - Testing, Training, and Exercise Programs](https://www.nist.gov/privacy-framework/nist-sp-800-84)** - Guide for IT plan testing and capabilities.
- **[SANS Securing Web Application Technologies Checklist](https://www.sans.org/cloud-security/securing-web-application-technologies/)** - Web application security testing checklist.
- **[OWASP AI Exchange](https://owaspai.org/)** - Resources for AI/ML security.
- **[Global Resilience Federation Operational Resilience Framework](https://www.grf.org/orf)** - Framework for operational resilience.
- **[CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages)** - Ready-to-use cybersecurity exercise scenarios.

### Security Engineering Resources

- **[NIST Cryptographic Module Validation Program](https://csrc.nist.gov/projects/cryptographic-module-validation-program)** - Cryptographic module testing and validation.
- **[CIS Hardened Images](https://www.cisecurity.org/cis-hardened-images)** - Pre-configured secure system images.
- **[STIG Viewer](https://www.stigviewer.com/)** - Security Technical Implementation Guides viewer.
- **[CISA Secure By Design](https://www.cisa.gov/securebydesign)** - Principles for building secure products.
- **[Google Site Reliability Engineering](https://sre.google/)** - Google's SRE principles and practices.
- **[Detection Engineering Maturity Assessment](https://medium.com/@harrisonpomeroy/assessing-a-detection-engineering-program-for-maturity-b896955bba66)** - Framework for assessing detection capabilities.

## Contributing

Contributions welcome! Please read the contribution guidelines before submitting.

### How to Contribute

1. Check existing entries to avoid duplicates
2. Ensure your contribution fits into an existing category or propose a new one
3. Write a concise description (1-2 sentences)
4. Include official links (no affiliate links)
5. Mark items as (Open Source), (Commercial), (Freemium) where applicable
6. Submit a pull request

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
