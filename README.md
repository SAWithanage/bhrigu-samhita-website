# Bhrigu Samhita Astrology Predictions

A lightweight, purely client-side web application for retrieving traditional Vedic astrological predictions based on planetary positions in houses and ascendants, as detailed in the **Bhrigu Samhita**.

## 🌟 Features

* **Instant Predictions:** Pure client-side execution with fast query processing.
* **Structured Dataset:** JavaScript object database mapping astrological combinations (`Planet`, `House`, `Ascendant`, `Sign`) to specific interpretations.
* **Raw Source Text Included:** Includes the extracted reference text file containing headings and original predictions.
* **Responsive UI:** Clean, modern interface designed with HTML5 and CSS flexbox for cross-device support.
* **Zero Dependencies:** Built with vanilla HTML, CSS, and JS — no external frameworks or npm installations required.

## 🛠️ Project Structure

```text
.
├── index.html              # Frontend user interface and query logic
├── bhrigu_database.js      # Structured JS database of planetary combinations and predictions
├── bhrigu_samhita_raw.txt  # Extracted raw text, headings, and predictions from original Bhrigu Samhita
└── README.md               # Project documentation
