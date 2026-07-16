# API Widgets

Custom **Brightspace (D2L) homepage widgets** shared by the [Brightspace Dashboard Data Community](https://github.com/Brightspace-Dashboard-Data-Community).

These widgets run in the browser on your Brightspace homepage. They use built-in D2L APIs and CSV files you host in **Manage Files**—no separate server or OAuth application required.

---

## Widgets

| Widget | Folder | Description |
|--------|--------|-------------|
| **D2L Welcome Message** | [`D2L Welcome Message/`](./D2L%20Welcome%20Message/) | Personalized welcome by role; nudges students who have not accessed an active course in 4+ days |
| **Upcoming Courses** | [`Upcoming Courses/`](./Upcoming%20Courses/) | Shows a student's or instructor's enrolled courses for the upcoming term from an SIS enrollment CSV |

Each folder contains the widget HTML and, where available, a README with setup and adaptation instructions.

---

## Quick start

1. Open the widget folder you need.
2. Read the README (if present) for CSV and configuration requirements.
3. Copy the `.html` file contents into a Brightspace **Custom Widget** or homepage HTML widget.
4. Upload any required CSV files to **Manage Files** on your Brightspace site.
5. Update institution-specific settings (URLs, org unit IDs, term codes, branding).

---

## Contributing

To add a widget:

1. Create a new folder under this repository with a clear name.
2. Include the widget HTML and a `README.md` explaining setup, data sources, and customization.
3. Open a pull request to [Brightspace-Dashboard-Data-Community/API-Widgets](https://github.com/Brightspace-Dashboard-Data-Community/API-Widgets).

---

## Credits

Widgets in this repository are maintained by Brightspace administrators in the community. The **D2L Welcome Message** widget was developed by Delta College eLearning.

---

## License

Community members may use, adapt, and share these widgets. Replace institution-specific URLs, identifiers, and branding before deploying to your own Brightspace environment.
