# Audacity Similar Label Finder
[Open in Colab](https://colab.research.google.com/github/seanfagan/audacity-similar-label-finder/blob/main/Audacity_similar_label_finder.ipynb)

This tool scans Audacity label tracks to find labels with similar timecodes. You can upload one or multiple label track files to be scanned. The tool will compare all label timecodes and, if they are _similar enough_, note those labels as a "match". You can adjust the tolerance for what is _"similar enough"_ in terms of seconds. Afterwards, the results can be downloaded in JSON format.
