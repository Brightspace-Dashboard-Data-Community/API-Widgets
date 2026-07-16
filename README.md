# API Widgets

Custom **Brightspace (D2L) homepage widgets** shared by the [Brightspace Dashboard Data Community](https://github.com/Brightspace-Dashboard-Data-Community).

These widgets run in the browser on your Brightspace homepage. They use built-in D2L APIs, Content topics, and/or CSV files you host in **Manage Files**—no separate server or OAuth application required.

---

## Widgets

| Widget | Folder | Description |
|--------|--------|-------------|
| **D2L Welcome Message** | [`D2L Welcome Message/`](./D2L%20Welcome%20Message/) | Personalized welcome by role; nudges students who have not accessed an active course in 4+ days |
| **Upcoming Courses** | [`Upcoming Courses/`](./Upcoming%20Courses/) | Shows a student's or instructor's enrolled courses for the upcoming term from an SIS enrollment CSV |
| **Tech Tips** | [`Tech Tips/`](./Tech%20Tips/) | Faculty-only random D2L tech tips loaded from a Content topic in your organization |
| **Browser Specific Notification** | [`Browser Specific Notification/`](./Browser%20Specific%20Notification/) | Device-specific notices for Mac/Safari, Chromebook/Respondus, and Windows S Mode |
| **Faculty Navigation Menu** | [`Faculty Navigation Menu/`](./Faculty%20Navigation%20Menu/) | Faculty accordion with training links, grade due dates, and sandbox course creation |
| **Faculty Incomplete Students** | [`Faculty Incomplete Students/`](./Faculty%20Incomplete%20Students/) | Count and list of students with Incomplete role across instructor courses |
| **Student Incomplete Courses** | [`Student Incomplete Courses/`](./Student%20Incomplete%20Courses/) | Student view of incomplete course enrollments with instructor and course link |

Each folder contains the widget HTML and, where available, a README with setup and adaptation instructions.

---

## Widget screenshots

### D2L Welcome Message

![D2L Welcome Message widget](D2L%20Welcome%20Message/D2L-welcome-widget.jpg)

### Upcoming Courses

![Upcoming Courses widget](Upcoming%20Courses/Upcoming-Courses-Widget.jpg)

### Tech Tips

![D2L Tech Tips widget](Tech%20Tips/D2L-Tech-Tip.jpg)

### Browser Specific Notification

![Browser Specific Notification widget](Browser%20Specific%20Notification/browser-specific-notification.jpg)

### Faculty Navigation Menu

![Faculty Navigation Menu widget](Faculty%20Navigation%20Menu/faculty-information-menu.jpg)

### Faculty Incomplete Students

The three images show the widget’s privacy states: the initial count-only view, expanded details with names blurred, and names deliberately revealed by the instructor. See the [widget README](./Faculty%20Incomplete%20Students/) for the full privacy explanation.

![Faculty Incomplete Students — count only](Faculty%20Incomplete%20Students/FAC-Incomplete-Student-1.jpg)

![Faculty Incomplete Students — names blurred](Faculty%20Incomplete%20Students/FAC-Incomplete-Student-2.jpg)

![Faculty Incomplete Students — names revealed](Faculty%20Incomplete%20Students/FAC-Incomplete-Student-3.jpg)

### Student Incomplete Courses

![Student Incomplete Courses widget](Student%20Incomplete%20Courses/Incomplete-Student.jpg)

---

## Quick start

1. Open the widget folder you need.
2. Read the README (if present) for CSV and configuration requirements.
3. Copy the `.html` file contents into a Brightspace **Custom Widget** or homepage HTML widget.
4. Upload any required CSV files to **Manage Files**, or create a **Content topic** for tips-based widgets.
5. Update institution-specific settings (URLs, org unit IDs, topic IDs, term codes, branding).

**Delta College staff:** use production-ready copies in [`delta-production/`](./delta-production/) (gitignored, not on GitHub) when pasting into live D2L.

---

## Contributing

To add a widget:

1. Create a new folder under this repository with a clear name.
2. Include the widget HTML and a `README.md` explaining setup, data sources, and customization.
3. Open a pull request to [Brightspace-Dashboard-Data-Community/API-Widgets](https://github.com/Brightspace-Dashboard-Data-Community/API-Widgets).

---

## Credits

Widgets in this repository are maintained by Brightspace administrators in the community. Several widgets were developed by **Delta College** eLearning, including D2L Welcome Message, Upcoming Courses, Tech Tips, Browser Specific Notification, Faculty Navigation Menu, Faculty Incomplete Students, and Student Incomplete Courses.

---

## License

Community members may use, adapt, and share these widgets. Replace institution-specific URLs, identifiers, and branding before deploying to your own Brightspace environment.
