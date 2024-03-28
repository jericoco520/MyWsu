# Vulnerability Taxonomy CWE Homework

---
### My Fake CPE

```
**Chosen CWE**: CWE-190 Integer Overflow or Wraparound

**Link**: https://cwe.mitre.org/data/definitions/190.html

**Explanation**:
My experience with CWE-190 is when I am using a short integer variable that is
incremented to a number greater than the max value of a short integer.
An integer overflow occurs and essentially the variable counts up from
the max negative value a short integer can have.
The short integer has a min value of -32,768 and a max value of 32,767. If
my variable becomes greater 32,767 then it wraps to -32,768 and keeps incrementing
from there.

CPE: cpe:/a:corneja:javaprogram:0.1.9:::en


```
---
### Summary of the Parts of my CPE
**Part** - `a`
```
This section of my CPE refers to whether my sofware is an application "a" or
an operating system "o." The software I chose to write my CPE on is a simple
application I remember having overflow problems.
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
### My Code Vulnerability
- My chosen CWE is not in the **Top 10 KEV List**

**Severity of Weakness**
```

```
