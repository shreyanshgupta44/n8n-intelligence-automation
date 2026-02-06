
---

## ⏰ Scheduling

- Uses **n8n Schedule Trigger**
- Runs **every 15 days**
- Fully automatic once the workflow is activated
- No manual execution required

> ⚠️ Manual Trigger is intentionally not used in production.

---

## 🛠️ Requirements

Before importing the workflow, ensure you have:

- An active **n8n** instance (self-hosted or cloud)
- Google Gemini API access
- Required credentials configured in n8n:
  - Google Gemini
  - Google Drive (if file storage is enabled)

---

## 📦 Installation & Setup

1. Clone this repository or download the workflow JSON file
2. Open your n8n editor
3. Click **Import Workflow**
4. Upload the JSON file
5. Configure credentials:
   - Google Gemini
   - Any file storage integrations
6. Review the Schedule Trigger timing
7. Activate the workflow

Once activated, the workflow will run automatically based on the defined schedule.

---

## 🧪 Testing

For testing purposes:
- You can manually execute the workflow from the n8n editor
- Or temporarily change the schedule interval (e.g. every 1 minute)

⚠️ Remember to revert schedule settings after testing.

---

## 🔐 Security Notes

- No API keys or secrets are stored in this repository
- Credentials must be configured directly inside n8n
- Always review exported workflows before publishing

---

## 📈 Use Cases

- Competitive intelligence automation
- Market research generation
- Periodic AI research reports
- Scheduled content or document creation

---

## 🤝 Contributing

Contributions are welcome:
- Workflow improvements
- Documentation updates
- Optimization suggestions

Feel free to open an issue or pull request.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## ⭐ Acknowledgements

Built with:
- n8n
- Google Gemini
- Automation-first design principles
