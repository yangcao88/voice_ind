# Voice-Indistinguishability: Protecting Voiceprint with Differential Privacy


With the rising adoption of advanced voice-based technology together with increasing consumer demand for smart devices, voice-controlled “virtual assistants” such as Apple’s Siri and Google Assistant have been integrated into people’s daily lives.
However, privacy and security concerns may hinder the development of such voice-based applications since speech data contain the speaker's biometric identifier, i.e., voiceprint (as analogous to ﬁngerprint).
To alleviate privacy concerns in speech data collection, we proposed the first formal privacy notion for voiceprint privacy, called *Voice-Indistinguishability*.
In our work in **ICME 2020**, we designed a method to release private voice record datasets satisfyinng our privacy notion.
We also demonstrated how to use Voice-Indistinguishability in a local setting in our demo paper accepted by **ACM CCS 2020** (demo/poster track):
we designed a fast speech data de-identification system that allows a single user to share her speech data with formal privacy guarantee to an untrusted server.
Our open-sourced system could be integrated into other speech processing systems for collecting users' voice data in a privacy-preserving way.
Experiments on public datasets verify the effectiveness and efficiency of the proposed system.

## Implementation
The code "tts1_ccs" was used in the experiments of the above paper.
This is implemented based on espnet. <br>
https://github.com/espnet/espnet


## References

- [**ICME 2020**] Voice-Indistinguishability: Protecting Voiceprint In Privacy-Preserving SpeechData Release. <br>
Yaowei Han, Sheng Li, Yang Cao, Qiang Ma, and Masatoshi Yoshikawa. <br>
https://ieeexplore.ieee.org/abstract/document/9102875

- [**ACM CCS 2020 demo**] Voice-Indistinguishability: Protecting Voiceprint with Differential Privacy under an Untrusted Server. <br>
Yaowei Han, Yang Cao, Sheng Li, Qiang Ma, and Masatoshi Yoshikawa. <br>



## Contributors

Yaowei Han (Kyoto University)

Yang Cao (Kyoto University) yang@i.kyoto-u.ac.jp
