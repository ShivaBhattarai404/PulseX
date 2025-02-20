# PulseX

**PulseX** is a lightweight and powerful JavaScript library designed to help developers track user activity on websites. With PulseX, you can seamlessly monitor interactions like page visits, clicks, time spent, and engagement patterns, enabling you to make data-driven decisions to improve your application.

---

## 🌟 **Features**

- **Effortless Integration**: Easily set up PulseX in your project with minimal configuration.
- **Real-Time Tracking**: Track user interactions as they happen.
- **Customizable Events**: Monitor specific actions like button clicks, form submissions, or custom-defined events.
- **Lightweight**: Built with performance in mind, ensuring minimal impact on your website's load time.
- **Flexible Reporting**: Collect data in the format you prefer for easy integration with analytics tools.

---

## 🚀 **Getting Started**

Follow these steps to integrate PulseX into your project:

### **1. Installation**

Install PulseX via npm:

```bash
npm install pulsex
```

Or using Yarn:

```bash
yarn add pulsex
```

---

### **2. Usage**

Start tracking user activity with a few lines of code:

```javascript
import PulseX from "pulsex";

// Initialize PulseX
const tracker = new PulseX({
  trackingId: "YOUR_TRACKING_ID", // Optional unique identifier
  debug: true, // Enable console logs for debugging
});

// Track page views
tracker.trackPageView();

// Track custom events
tracker.trackEvent("button_click", {
  buttonId: "subscribe-btn",
  label: "Subscribe Button",
});

// Track user time on a specific section
tracker.trackTimeOnSection("homepage");
```

---

## ⚙️ **Configuration Options**

You can customize PulseX to suit your project needs. Here are the available options:

| Option           | Type    | Default | Description                                    |
| ---------------- | ------- | ------- | ---------------------------------------------- |
| `trackingId`     | String  | `null`  | A unique identifier for your tracking session. |
| `debug`          | Boolean | `false` | Enables debug mode for console logs.           |
| `captureClicks`  | Boolean | `true`  | Automatically tracks all button clicks.        |
| `sessionTimeout` | Number  | `30`    | Session timeout in minutes.                    |

---

## 📈 **Available Methods**

### **1. `trackPageView()`**

Tracks when a user visits a new page.

### **2. `trackEvent(eventName, eventData)`**

Tracks a specific event.

- `eventName`: Name of the event (e.g., `button_click`).
- `eventData`: Additional data about the event (e.g., `buttonId`, `label`).

### **3. `trackTimeOnSection(sectionName)`**

Tracks how much time a user spends on a specific section.

- `sectionName`: Name of the section (e.g., `homepage`).

---

## 🌐 **Browser Compatibility**

PulseX is compatible with all modern browsers, including:

- Chrome
- Firefox
- Edge
- Safari

---

## 📦 **Contributing**

We welcome contributions from the community! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

---

## 🛡️ **License**

PulseX is open-source and available under the [MIT License](LICENSE).

---

## 💬 **Support**

If you have any questions, feature requests, or feedback, feel free to [open an issue](https://github.com/your-username/pulsex/issues) or reach out to us at `support@pulsex.io`.

---

### Keep your finger on the pulse of your users with **PulseX**!
