# Smart Digital - Admin Guide

## 🔒 Password Protection for Notifications

The **Edit** button for notifications is now **password protected**. Only you (the admin) can edit notifications after entering the correct password.

---

## 📝 How to Change Your Admin Password

1. **Open** `index.html` in a text editor
2. **Find** this line (around line 1104):
   ```javascript
   const ADMIN_PASSWORD = "smartdigital2026"; // ⚠️ CHANGE THIS TO YOUR OWN SECURE PASSWORD!
   ```
3. **Replace** `"smartdigital2026"` with your own secure password:
   ```javascript
   const ADMIN_PASSWORD = "your-new-password-here";
   ```
4. **Save** the file

---

## 🔑 Password Requirements

- Use a **strong password** (mix of letters, numbers, and special characters)
- Avoid common words or easily guessable passwords
- **Example:** `SmartDigital@Admin123`

---

## ✏️ How Users See It

When a user clicks the "Edit" button:

1. A popup appears asking for the admin password
2. If they enter the wrong password → ❌ Error message
3. Only with the correct password → ✅ Edit mode opens

**Regular visitors CANNOT edit notifications without the correct password.**

---

## 💾 What Gets Saved?

- Notifications are saved in **browser localStorage**
- They persist even after page refresh
- No need for a database or server
- Each browser/device has its own saved notifications

---

## 🛠️ Default Password (Change This!)

**Current Password:** `smartdigital2026`

**⚠️ IMPORTANT:** Change this to something unique and secure that only you know!

---

## 🎮 Game Section

Update the placeholder links in the Games section with your actual:

- **GitHub Repository URLs** (for "View Code" buttons)
- **Deployed Game URLs** (for "Play" buttons)

Search for: `"https://github.com/yourusername/"` in the HTML and replace with your actual GitHub profile.

---

## 📞 Support

For any issues or questions about the website, contact your developer.

---

**Last Updated:** February 3, 2026
