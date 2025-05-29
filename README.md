# Shubham-Jadhav
My Financial Space
# 👋 Hi, I'm Shubham Jadhav

🎯 **Insurance & Mutual Fund Consultant | Financial Guide | Serving 400+ Happy Families**

📍 Based in Mumbai, India  
📞 +91 8369744837  
📧 shubham1205jadhav@gmail.com  

---

## 🛡️ Services I Offer

- ✅ **Insurance Advisory**  
  - LIC, TATA AIA, ICICI Prudential, HDFC Life
  - Term plans, ULIPs, health & critical illness covers
  - Claims assistance, renewals & tax-saving guidance

- 💰 **Mutual Fund Investment Planning**  
  - SIPs, lumpsum investments
  - Goal-based wealth creation
  - Regular portfolio reviews

- 📄 **Financial Assistance**  
  - Income Tax Return (ITR) Filing
  - Provident Fund (PF) Claims
  - Financial documentation help

---

## 🎓 Qualifications & Certifications

- M.Com (IDOL, Mumbai University) – 86.5%
- BMS (D. G. Ruparel College) – 81.28%
- 📜 NISM Certified Mutual Fund Distributor (Series V)
- 📜 NISM Equity Derivatives Certification (Series VIII)
- 🧠 Currently pursuing: Data Analytics (Excel, SQL, Power BI, Tableau)

---

## 🙌 Trusted by 400+ Families

I believe in **honest advice**, **transparent planning**, and **long-term relationships**. I’ve helped hundreds of families across India secure their financial future and achieve their life goals.

---

## 📲 Let’s Connect!

- 📞 **Call or WhatsApp**: [+91 8369744837](https://wa.me/918369744837)
- 📧 **Email**: [shubham1205jadhav@gmail.com](mailto:shubham1205jadhav@gmail.com)

---

> "Helping you make smart, stress-free financial decisions."

<!-- sip-calculator.html -->
<!DOCTYPE html>
<html>
<head>
  <title>SIP Calculator</title>
</head>
<body>
  <h2>SIP Calculator</h2>
  <label>Monthly Investment (₹):</label>
  <input type="number" id="monthly" /><br /><br />
  <label>Expected Annual Return (%):</label>
  <input type="number" id="rate" /><br /><br />
  <label>Investment Duration (Years):</label>
  <input type="number" id="years" /><br /><br />
  <button onclick="calculateSIP()">Calculate</button>

  <h3 id="result"></h3>

  <script>
    function calculateSIP() {
      const monthly = parseFloat(document.getElementById("monthly").value);
      const rate = parseFloat(document.getElementById("rate").value) / 12 / 100;
      const months = parseInt(document.getElementById("years").value) * 12;

      const futureValue = monthly * ((Math.pow(1 + rate, months) - 1) * (1 + rate)) / rate;

      document.getElementById("result").innerText =
        "Estimated Value: ₹" + futureValue.toFixed(2);
    }
  </script>
</body>
</html>

