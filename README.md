# ITSCon23
Supplementary documents for the presentation at Champlain College ITS Conference, 2023.

# Presenting Project: 10DMA

Checkout the google slides here:

[10dma - Google Slides](https://docs.google.com/presentation/d/15KZUzLMRdc4JUfvkgNGkPUKXmODu5ugakiF1TYdyJhM/edit?usp=sharing)

Introduction:

This code is designed to assist malware analysts in generating an automated report on a given malware sample. The report includes various sections such as file information, static analysis, dynamic analysis, and conclusion. The code uses various tools and techniques to extract information and generate a report automatically.

The code starts by analyzing the malware sample using a custom spectrogram classifier and VirusTotal. The resulting prediction is used to generate an introduction section that summarizes the malware and its potential impact on systems.

The code then extracts basic file information such as hashes and other details. The static analysis section provides an overview of the malware behavior capabilities, including any anti-analysis techniques used by the malware.

Dynamic analysis is a crucial technique used to analyze the behavior of malware and identify its capabilities. The code uses Hatching Triage to conduct dynamic analysis and generates a section that includes information about domains, URLs, and IPs associated with the malware. The TTPs associated with the malware are also discussed in this section.

Finally, the code generates a conclusion based on the information extracted from the dynamic and static analysis sections. The conclusion summarizes the findings and provides insights into the potential impact of the malware on systems.

Overall, this code provides an automated solution for generating a malware analysis report. The code is designed to save time and increase the efficiency of malware analysts by automating the process of extracting and summarizing critical information about the malware.