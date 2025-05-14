Accurate localization of text within images is critical for
downstream vision-language tasks such as Optical Charac-
ter Recognition (OCR) and document analysis. Traditional
methods, including manual Region of Interest (ROI) selec-
tion and heuristic-based approaches, often struggle with di-
verse layouts, low-contrast backgrounds, and non-standard
text arrangements. While deep learning models achieve
high accuracy, they require significant computational re-
sources and time. This study proposes a reinforcement
learning framework based on Deep Q-Networks (DQN) for
adaptive and efficient target text detection.
The system incrementally adjusts ROI position and scale
by maximizing OCR-based similarity scores, halting when
improvements plateau or boundaries are reached. A cus-
tom reward function leveraging Jaccard similarity ensures
precise localization. Compared to large vision-language
models such as Qwen2.5-VL and Qwen-VL-Chat, the pro-
posed method offers a superior trade-off between accuracy
and efficiency, particularly on resource-constrained hard-
ware. The results confirm the robustness and scalability of
the framework. 
