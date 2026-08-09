# my-political-sim

यह रिपॉज़िटरी मोबाइल‑फर्स्ट राजनीतिक सिम्युलेटर के लिए स्केफोल्ड है।

इस प्रोजेक्ट में निम्न मुख्य हिस्से हैं:

- simulation/parliament — लोकसभा/सरकार/कोआालिशन का core engine
- simulation/election — निर्वाचन (constituency) इंजन
- simulation/diplomacy — विश्व राजनीति, देश, क्षेत्र, युद्ध/संधि आदि
- simulation/game — दोनों को जोड़ने वाला GameEngine
- app/src/main/assets/countries.json — विश्व के देशों का प्रारम्भिक डेटा (195 देश जोड़े जाने हैं)
- .github/workflows/android-build.yml — GitHub Actions workflow जो debug APK बनाता है

अगर आप चाहें तो मैं अब feature/diplomacy-engine ब्रांच बना कर ऊपर की फाइलें जोड़ दूँगा और एक Pull Request बनाऊँगा।

---

Usage (mobile friendly):
1) GitHub → Pull requests → open PR देखेँ और Merge karein.
2) GitHub Actions tab → workflow run → artifact (APK) download karein aur mobile par install karein.

