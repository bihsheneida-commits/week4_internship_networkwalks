# NETWORKWALKS

## Penetration Testing Report — Mediroza General Hospital

**Client:** Mediroza General Hospital
**Target:** `https://medirozahospital.com`
**Engagement Type:** Black-Box Web Application Assessment
**Prepared By:** BIH SHENEIDA
**Assessment:** Week 4 Cybersecurity Internship
**Authorization:** Testing was performed within the authorized educational environment.

---

## 1. Summary

This penetration-testing assessment was carried out as part of the Week 4 cybersecurity practical exercise.

The main objective was to identify possible security weaknesses in the target web application, discover exposed web resources, and assess whether these resources could present a security risk.

The assessment included reconnaissance, web-server enumeration, directory and resource discovery, access-control assessment, and analysis of resources identified during the exercise.

---

## 2. Scope

The assessment was performed against the following authorized target:

**Target:** `https://medirozahospital.com`

The testing activities included:

* Web reconnaissance
* Web-server enumeration
* Directory and resource discovery
* Review of authentication and access controls
* Analysis of discovered files and resources
* Assessment of potential security impact

Testing was limited to the authorized educational environment.

---

## 3. Methodology

### Phase 1 — Reconnaissance

Information about the target website and its available services was collected to understand the target's attack surface.

### Phase 2 — Web Enumeration

Web enumeration and directory discovery were performed to identify available directories, files, and other potentially exposed resources.

### Phase 3 — Access-Control Assessment

The discovered resources were reviewed to determine whether appropriate access restrictions were implemented.

### Phase 4 — File Analysis

Files discovered during the assessment were examined to determine whether they contained sensitive information or had inadequate protection.

### Phase 5 — Security Impact Assessment

The information collected during the previous phases was reviewed to determine the possible security impact of the identified exposure.

---

## 4. M3 — Critical Exposure

### Objective

The objective of M3 was to investigate whether information or resources identified during the previous phases could result in further exposure of sensitive organizational information.

### Finding

During the assessment, potentially exposed web resources were identified.

unprotected directory listing exposing ful database backup

Resources that are accessible without appropriate authorization can create an information-disclosure risk. If sensitive files or directories are unintentionally exposed, unauthorized users may be able to obtain information that should not be publicly available.

### Potential Impact

Depending on the type of information exposed, an attacker could potentially use the information to:

* Learn more about the organization's systems and resources.
* Identify additional targets for further security testing.
* Obtain information that should be restricted.
* Support future unauthorized access attempts.

The actual impact depends on the sensitivity of the exposed information and the access controls applied to the affected resources.

---

## 5. Security Recommendations

The following security improvements are recommended:

1. Implement strong authentication and authorization controls.
2. Restrict access to sensitive directories and files.
3. Disable unnecessary directory listing or indexing.
4. Remove sensitive or unnecessary resources from public access.
5. Review web-server permissions and configuration.
6. Regularly scan the web application for vulnerabilities and exposed resources.
7. Monitor server logs for unusual or unauthorized access attempts.
8. Apply the principle of least privilege when configuring access to sensitive resources.

---

## 6. Conclusion

The assessment demonstrated how reconnaissance and web enumeration can be used to identify resources that may present security risks.

The main concern identified during the assessment was the potential exposure of resources that should have appropriate access restrictions.

Proper authentication, authorization, secure web-server configuration, and regular security testing can help reduce the risk of information disclosure and unauthorized access.

---

## 8. Tools Used

* Nmap
* Gobuster
* Nikto
* Web Browser
* Kali Linux
* hash calculator
* networkwalks cracker

---

## 9. Ethical Considerations

The assessment was conducted for educational and cybersecurity training purposes within the authorized environment.

Testing activities were limited to the defined target and were performed with authorization. No attempt was made to access information outside the approved scope.
