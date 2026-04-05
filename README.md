@@ -1 +1,23 @@
# trendpulse-vani goswami
# TrendPulse: Task 1 (Data Collection)

A Python script that fetches and categorizes trending stories from the **HackerNews API**.

## Quick Start
1.  **Install dependencies**: `pip install requests`
2.  **Run the script**: `python task1_data_collection.py`

## How it Works
* **Fetch**: Pulls the top 500 story IDs from HackerNews.
* **Categorize**: Matches titles against keywords for 5 categories (Tech, World News, Sports, Science, Entertainment).
* **Limit**: Collects a maximum of 25 stories per category (125 total).
* **Rate Limiting**: Pauses for 2 seconds between categories to avoid API spamming.

## Output
Data is saved to the `data/` folder as a JSON file:
* **Path**: `data/trends_YYYYMMDD.json`
* **Fields**: `post_id`, `title`, `category`, `score`, `num_comments`, `author`, and `collected_at`.

---

**Author:** Vani goswami
THANK YOU
