# 🎯 DSAdManager — Ad Slot Allocation with Advanced DSA

Simulates an ad platform's campaign scheduler. It uses algorithmic techniques (greedy, heaps, interval scheduling) to maximize revenue or ad impressions by placing ad campaigns in optimal slots.

---

## ✅ Features

- Ad campaign simulation (random start, end, bid)
- Slot allocation using priority queues and scheduling
- Benchmark results for allocation efficiency
- Unit-tested logic
- Easy to extend with dynamic programming or segment trees

---

## 🧪 Example

AdCampaign(start=1, end=4, bid=100)  
AdCampaign(start=3, end=5, bid=200)  

📌 Result: [Campaign 2 wins due to higher bid]

---

## 📦 How to Run

```bash
python simulator/ad_generator.py
