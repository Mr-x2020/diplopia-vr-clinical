# 🩺 Diplopia VR — Clinical Interpretation Manual

دليل سريري موجه لأطباء العيون، وأخصائيي البصريات، وتقويم الحول (*Orthoptists*) لتفسير تقارير JSON الصادرة عن النظام وتقييم مدى استجابة المريض للتدريب ثنائي الرؤية (*Dichoptic VR*).

---

## 1. بنية ملف التقرير الطبي (`.json`)

```json
{
  "metadata": {
    "exportDate": "2026-10-15T14:20:00.000Z",
    "protocol": "James Blaha Dichoptic Triad VR Protocol",
    "systemVersion": "v2.5.1 Clinical Master",
    "userConfig": {
      "targetLazyEye": "left",
      "measuredIPD": "63 mm",
      "digitalPrismOffset": { "x": 0.0210, "y": -0.0045 },
      "currentContrastLevel": 0.42
    }
  },
  "sessionLogs": [
    {
      "id": 1729002000000,
      "timestamp": "2026-10-15T14:15:00.000Z",
      "game": "TETRIS",
      "durationSec": 900,
      "startContrast": 0.38,
      "endContrast": 0.42,
      "contrastDelta": 0.04,
      "hits": 34,
      "misses": 2,
      "averageReactionTimeMs": null,
      "endReason": "NORMAL_EXIT"
    }
  ]
}