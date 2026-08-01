# Autopsy Digital Forensics Investigation

## Objective

Perform a digital forensic investigation using Autopsy to analyze Windows artifacts and recover forensic evidence.

---

## Lab Environment

- Windows 10
- Autopsy
- Sample Windows Image

---

## Tools Used

- Autopsy Digital Forensics

---

## 1. Install Autopsy

![Autopsy Installation](images/autopsy-installation.png)

---

## 2. Create a New Case

![Case Information](images/case-information.png)

---

## 3. Configure Ingest Modules

![Configure Ingest Modules](images/configure-ingest-modules.png)

---

## 4. Review Installed Programs

![Installed Programs](images/installed-programs.png)

---

## 5. Analyze Artifacts of Interest

![Artifacts of Interest](images/artifacts-of-interest.png)

---

## 6. Recover Thumbnail Cache

![Recovered Thumbnail](images/recovered-thumbnail.png)

Autopsy recovered a cached thumbnail from **thumbcache_32.db**, demonstrating how thumbnail cache artifacts can provide evidence that an image was viewed on the system even if the original image has been deleted.

---

## Findings

- Successfully created a forensic case.
- Configured Autopsy ingest modules.
- Identified installed applications.
- Examined Windows forensic artifacts.
- Recovered thumbnail cache evidence.

---

## Digital Forensic Significance

Windows thumbnail cache can preserve evidence of previously viewed images. This artifact is useful during forensic investigations because it may remain available even after the original file has been removed.

---

## Conclusion

This laboratory exercise demonstrates the use of Autopsy to collect, analyze, and interpret Windows forensic artifacts. The investigation successfully identified system information, user artifacts, and recovered thumbnail cache evidence, highlighting the importance of digital forensics in incident response and criminal investigations.