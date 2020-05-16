# Awesome ASN.1

## Standards

### ASN.1 Standards

- [ITU X.680 - Specification of basic notation](https://www.itu.int/rec/T-REC-X.680/en)
- [ITU X.681 - Information object specification](https://www.itu.int/rec/T-REC-X.681/en)
- [ITU X.682 - Constraint specification](https://www.itu.int/rec/T-REC-X.682/en)
- [ITU X.683 - Parameterization of ASN.1 specifications](https://www.itu.int/rec/T-REC-X.683/en)
- **WITHDRAWN** [ITU X.208 - Specification of Abstract Syntax Notation One (ASN.1)](https://www.itu.int/rec/T-REC-X.208/en)

### Codec Standards

- **WITHDRAWN** [ITU X.209 - Specification of Basic Encoding Rules for Abstract Syntax Notation One (ASN.1)](https://www.itu.int/rec/T-REC-X.209-198811-W/en)
- [ITU X.690 - ASN.1 encoding rules: Specification of Basic Encoding Rules (BER), Canonical Encoding Rules (CER) and Distinguished Encoding Rules (DER)](https://www.itu.int/rec/T-REC-X.690/en)
- [ITU X.691 - ASN.1 encoding rules: Specification of Packed Encoding Rules (PER)](https://www.itu.int/rec/T-REC-X.691/en)
- [ITU X.692 - ASN.1 encoding rules: Specification of Encoding Control Notation (ECN)](https://www.itu.int/rec/T-REC-X.692/en)
- [ITU X.693 - ASN.1 encoding rules: XML Encoding Rules (XER)](https://www.itu.int/rec/T-REC-X.693/en)
- [ITU X.694 - ASN.1 encoding rules: Mapping W3C XML schema definitions into ASN.1](https://www.itu.int/rec/T-REC-X.694/en)
- [ITU X.695 - ASN.1 encoding rules: Registration and application of PER encoding instructions](https://www.itu.int/rec/T-REC-X.695/en)
- [ITU X.696 - ASN.1 encoding rules: Specification of Octet Encoding Rules (OER)](https://www.itu.int/rec/T-REC-X.696/en)
- [ITU X.697 - ASN.1 encoding rules: Specification of JavaScript Object Notation Encoding Rules (JER)](https://www.itu.int/rec/T-REC-X.697/en)
- [IETF RFC 3641 - Generic String Encoding Rules (GSER) for ASN.1 Types](https://tools.ietf.org/html/rfc3641)
- [ASHRAE 135-2016 - BACnet](https://www.techstreet.com/standards/ashrae-135-2016?product_id=1918140) (Section 20 defines the encoding rules.)
- [NEMA 100033 - Octet Encoding Rules (OER) Base Protocol](https://www.nema.org/Standards/Pages/Octet-Encoding-Rules-Base-Protocol.aspx)
- [ISO 16484-5:2017 - Building automation and control systems (BACS) — Part 5: Data communication protocol](https://www.iso.org/standard/71935.html)

## Protocols Using ASN.1

- [Interledger Protocol](https://interledger.org/rfcs/asn1/index.html)
- [NTCIP 1103 - Transport Management Protocols](https://www.ntcip.org/wp-content/uploads/2018/11/NTCIP1103v0352b.pdf)
- [ISO 14827-2:2005 - DATEX-ASN](https://www.iso.org/standard/41362.html)
- [X.509 Certificates](https://www.itu.int/rec/T-REC-X.509-201610-I/en), used in [SSL/TLS](https://tools.ietf.org/html/rfc5246)
- [Lightweight Directory Access Protocol (LDAP)](https://www.ietf.org/rfc/rfc4511.txt)
- [X.400 Message Handling](https://www.itu.int/rec/T-REC-X.400/en)
- [X.500 Directory Services](https://www.itu.int/rec/T-REC-X.500-201610-I/en)
- The [magnetic stripes](https://www.iso.org/standard/43317.html) on credit cards and debit cards
- Microsoft's [Remote Desktop Protocol (RDP)](https://msdn.microsoft.com/en-us/library/mt242409.aspx)
- [Simple Network Management Protocol (SNMP)](https://www.ietf.org/rfc/rfc1157.txt)
- [Common Management Information Protocol (CMIP)](https://www.itu.int/rec/T-REC-X.711/en)
- [Signalling System Number 7 (SS7)](https://www.itu.int/rec/T-REC-Q.700-199303-I/en),
  used to make most phone calls on the Public Switched Telephone Network (PSTN).
- [H.323](https://www.itu.int/rec/T-REC-H.323-200912-I/en) Video conferencing
- Biometrics Protocols:
  - [BioAPI Interworking Protocol (BIP)](https://www.iso.org/standard/43611.html)
  - [Common Biometric Exchange Formats Framework (CBEFF)](http://nvlpubs.nist.gov/nistpubs/Legacy/IR/nistir6529-a.pdf)
  - [Authentication Contexts for Biometrics (ACBio)](https://www.iso.org/standard/41531.html)
- [Computer Supported Telecommunications Applications (CSTA)](https://www.ecma-international.org/activities/Communications/TG11/cstaIII.htm)
- [Dedicated Short Range Communications (SAE J2735)](http://standards.sae.org/j2735_200911/)
- Cellular telephony:
  - [Global System for Mobile Communications (GSM)](http://www.ttfn.net/techno/smartcards/gsm11-11.pdf)
  - [Global Packet Radio Service (GPRS) / Enhanced Data Rates for Global Evolution (EDGE)](http://www.3gpp.org/technologies/keywords-acronyms/102-gprs-edge)
  - [Universal Mobile Telecommunications System (UTMS)](http://www.3gpp.org/DynaReport/25-series.htm)
  - [Long-Term Evolution (LTE)](http://www.3gpp.org/technologies/keywords-acronyms/98-lte)
- [Common Alerting Protocol](https://www.itu.int/rec/T-REC-X.1303-200709-I/en)
- Controller Pilot Data Link Communications (CPDLC)
- Space Link Extension Services (SLE) (Used in space systems communications)
- [Manufacturing Message Specification (MMS)](https://www.iso.org/standard/37079.html) - Used in manufacturing
- File Transfer, Access and Management (FTAM)
- Remote Operation Service Element (ROSE)
- Association Control Service Element (ACSE)

## Codec Implementations

| Codec | Language | Link | Notes |
|-------|----------|------|-------|
| BER   | C        | [Link](https://github.com/openldap/openldap/tree/master/libraries/liblber) | OpenLDAP's Implementation |
| DER   | C        | [Link](https://github.com/openssl/openssl/tree/master/crypto/asn1) | OpenSSL's Implementation |
| DER   | Rust     | [Link](https://crates.io/crates/der-parser)
| OER   | Python   | [Link](https://github.com/eerimoq/asn1tools/blob/master/asn1tools/codecs/oer.py) | |
| BER and DER | JavaScript | [Link](https://github.com/lapo-luchini/asn1js) | |
| BER and DER | Go | [Link](https://golang.org/pkg/encoding/asn1/) | |
| BER, CER, and DER | Python | [Link](https://github.com/etingof/pyasn1) | |
| BER, CER, and DER | TypeScript | [Link](https://github.com/JonathanWilbur/asn1-ts) | \* |
| BACNet | Java | [Link](https://github.com/empeeoh/BACnet4J/tree/master/src/com/serotonin/bacnet4j/type) | |
| BACNet | C# | [Link](https://github.com/ela-compil/BACnet/blob/master/Serialize/ASN1.cs) | |
| BACNet | JavaScript | [Link](https://github.com/fh1ch/node-bacstack) | |
| PER | C | [Link](https://github.com/FreeRDP/FreeRDP/blob/master/libfreerdp/crypto/per.c) | FreeRDP's Implementation |

\* Full disclosure: I wrote this library.

## ASN.1 Compilers

- [OSS Nokalva's ASN.1 Compilers](https://www.oss.com/asn1/products/asn1-products.html)
- [Objective System's ASN.1-to-C Compiler](https://www.obj-sys.com/products/asn1c/index.php)
- [PyCrate](https://github.com/P1sec/pycrate)
- [asn1c](http://lionet.info/asn1c/compiler.html) ([GitHub Repository](https://github.com/vlm/asn1c))

## Miscellaneous

- [IETF RFC 6025 - ASN.1 Translation](https://tools.ietf.org/html/rfc6025)
  - This document gives guidance on how to transition from the withdrawn X.208 definition of ASN.1 to the up-to-date X.680-series ASN.1
- [OSS Nokalva JSON-to-ASN.1 and JSON-Schema-to-ASN.1 Translator](https://asn1.io/json2asn/default.aspx)
- [Hacker News Thread on ASN.1](https://news.ycombinator.com/item?id=8871604)
- [Proposal to use ASN.1 & ECN in ISO/IEC 7816-4](https://www.itu.int/en/ITU-T/asn1/Documents/ASN1+ECN-in-7816-4.pdf)
  - ISO/IEC 7816-4 is the specification for the protocol used by identification cards (including credit cards)
- [ASN.1 Modules Database](https://www.itu.int/ITU-T/recommendations/fl.aspx?lang=1)
- [OID Info](http://oid-info.com/) - The de facto central database of all Object Identifiers.
- [The ASN.1 Homepage](https://www.itu.int/en/ITU-T/asn1/Pages/asn1_project.aspx)
- [ASN.1 Flyer](https://www.itu.int/oth/T0B04000049/en)
- [ECN for 3GPP RRC](https://www.itu.int/en/ITU-T/asn1/Documents/rrc_ecn.pdf)
- [SS7.net](http://ss7.net/) - Signalling System No. 7 Training
- [BACNet.org](http://www.bacnet.org/) - The official BACNet website
- [Useful Old Technologies: ASN.1](https://www.thanassis.space/asn1.html)
- [Apache Harmony](http://harmony.apache.org/subcomponents/classlibrary/asn1_framework.html)
- [Standards using ASN.1](https://www.oss.com/asn1/resources/standards-use-asn1.html)

## Help Needed

I have read Olivier Dubuisson's ASN.1 book, and he briefly discusses Lightweight Encoding Rules (LWER). I cannot find any documentation of these encoding rules ever existing other than this book, and unfortunately, the book does not even specify where the LWER were specified. If anybody can point me to where I can find the Lightweight Encoding Rules specification, I would greatly appreciate it.

It would also be very helpful if somebody can point out where I can find the official ASN.1 specifications for the Controller Pilot Data Link Communications (CPDLC) and Space Link Extension Services (SLE) protocols.

Also, this is not "my" list. This is "our" list. Feel free to submit a pull request (or even just an issue if that is more convenient for you) if you have something you think is worthy of inclusion in this list. Cheers!
