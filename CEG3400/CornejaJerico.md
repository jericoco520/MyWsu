# Vulnerability Taxonomy CWE Homework

## My Fake CPE


**Chosen CWE**: `CWE-190 Integer Overflow or Wraparound`

**Link**: https://cwe.mitre.org/data/definitions/190.html

**Explanation**:
```
My experience with CWE-190 originates from using a short integer variable that is
incremented to a number greater than the max value of a short integer.
When nn integer overflow the short variable goes above the max value. It then wraps around
and starts counting up from its minimum value.
The short integer has a min value of -32,768 and a max value of 32,767. If
my variable becomes greater than 32,767 then it wraps to -32,768 and keeps incrementing
from there.
```
**Fake CPE**: `cpe:/a:corneja:javaprogram:0.1.9:::en`

---
**Severity of Weakness**

- My chosen CWE is not in the **Top 10 KEV List**

**Prevention**
```
- One way of preventing this weakness is by using a language that performs automatic
bound checking.
- If the variable is not a loop counter, then one could implement input validation
to ensure that the variable is within bounds.
```
---
**Actual CVE**
- `CVE-2022-24310`
- Link: `https://www.cve.org/CVERecord?id=CVE-2022-24310`

**Actual CPE**
- `cpe:2.3:a:schneider-electric:interactive_graphical_scada_system_data_server:*:*:*:*:*:*:*:*`
- Link: `https://nvd.nist.gov/vuln/detail/CVE-2022-24310#range-7572619`
---
### Summary of the Parts of my CPE
**Part** - `a`
```
This section of my CPE refers to whether my sofware is an application "a" or
an operating system "o".
The software I chose to write my CPE on is a simple application I remember
having overflow problems.
```

**Vendor** - `myself/corneja`
```
This section of my CPE refers to the creator of the application I am referring to.
```

**Product** - `javaprogram`
```
This section of my CPE refers to the name of my application which is javaprogram.
```

**Version** - `0.1.9`
```
This section of my CPE refers to the version number of my application.
I decided to include this because of the iterations I went through
before deciding the application was functioning well enough.
```

**Language** - `en`
```
This section refers to the language support I have which is english. 
```
---
