[Case Name] — Digital Forensic Analysis Report

1. Executive Summary
2-3 sentences: what was investigated, what tool(s) were used, and the key finding — written so a non-technical reader (like a hiring manager skimming GitHub) gets the point immediately.

2. Scope & Objectives
What questions were you trying to answer? (e.g., "Determine whether data was exfiltrated, identify the method, and establish a timeline.")

3. Tools & Methodology
List tools (Autopsy version, plugins used, etc.) and your process step-by-step — not just "I ran Autopsy" but why you looked where you looked. This is the section that shows investigative thinking, not just tool literacy.

4. Evidence Handling / Chain of Custody
Even for a practice image: note hash verification (MD5/SHA1), where the image came from, and how you preserved integrity throughout analysis. This is a section most CS-background candidates skip — it's where your CJ background gives you a real edge.

5. Findings
The actual analysis — organized by question or by artifact type (deleted files, timeline, metadata, network activity, etc.). Screenshots here, but always with your interpretation next to them, not just raw output.

6. Timeline of Events
A reconstructed chronological summary of what happened, in plain language — this is often the single most useful section for a reader.

7. Conclusion
Direct answers to your scope/objectives, stated plainly, plus a note on the significance of the findings (why it matters, what it would mean in a real case).

8. Appendix
Full command outputs, hash values, raw artifact lists — anything a reader can skip but should be available for verification.
