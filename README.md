# Bhrigu Samhita Astrology Predictions

A lightweight, purely client-side web application for retrieving traditional Vedic astrological predictions based on planetary positions in houses and ascendants, as detailed in the **Bhrigu Samhita**.

🌐 **Live Demo:** [https://sawithanage.github.io/bhrigu-samhita-astrology/](https://sawithanage.github.io/bhrigu-samhita-astrology/)

---

## 🌟 Features

* **Live Web Application:** Hosted online and immediately accessible at [https://sawithanage.github.io/bhrigu-samhita-astrology/](https://sawithanage.github.io/bhrigu-samhita-astrology/).
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
```

## 🚀 Getting Started

### Live Demo

You can interact with the live application directly in your browser:  
👉 **[Launch Bhrigu Samhita Astrology App](https://sawithanage.github.io/bhrigu-samhita-astrology/)**

### Local Setup

To run the project locally on your machine:

1. Clone or download this repository:
   ```bash
   git clone https://github.com/sawithanage/bhrigu-samhita-astrology.git
   ```
2. Open `index.html` directly in your web browser.
3. Select an **Ascendant**, **Planet**, and **House** from the dropdown controls.
4. Click **Get Prediction** to display the astrological reading.

## 📊 Data & Source Files

* **`bhrigu_samhita_raw.txt`**: The original extracted textual material containing all raw headings and predictions from the Bhrigu Samhita.
* **`bhrigu_database.js`**: Structured JSON array parsed from the source text for querying:

```javascript
{
  heading: "Sun in 1st house in Aries for Aries ascendant",
  interpretation: "The native is learned, gets good education...",
  planet: "Sun",
  house: 1,
  sign: "Aries",
  ascendant: "Aries"
}
```

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
