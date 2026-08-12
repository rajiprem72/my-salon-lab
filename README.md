# ✂️ My Salon Lab – Queue Management System

A simple, mobile-friendly, QR-code-based queue management system designed for **My Salon Lab**.

Customers can scan a QR code displayed inside the salon, register themselves, and receive a unique personal queue session. Their queue position is automatically updated as the salon owner completes each haircut.

The system eliminates the need for customers to physically stand in a queue or repeatedly ask the salon owner about their turn.

---

## 🌟 Features

### Customer Features

- 📱 Scan a QR code to join the queue
- 👤 Enter Name and Mobile Number
- 🎫 Receive a unique queue position
- 🔗 Get a unique personal queue session
- 📊 View current queue position in real time
- 👥 See how many people are ahead
- 🔄 Queue position updates automatically
- 📳 Vibration alert when it becomes the customer's turn
- ❌ No WhatsApp messages required
- 🔇 No audio notifications
- 💾 Customer session can be restored after refreshing the page
- 📱 Designed primarily for mobile phones

---

## 💈 Owner Features

The salon owner has a dedicated dashboard to manage the queue.

The owner can:

- 👀 View the current queue
- ✂️ See the customer currently being served
- ⏳ See waiting customers
- ✅ Mark a haircut as **Job Done**
- 🔄 Automatically move the next customer to position #1
- 📊 See the updated queue immediately
- 📱 Use the dashboard from a mobile phone

---

## 🔔 Notification Philosophy

The system deliberately avoids WhatsApp and audio notifications.

When the owner completes a haircut:

### All waiting customers

Their queue pages are updated silently.

Example:

```text
Customer #3 → #2
Customer #4 → #3
Customer #5 → #4
