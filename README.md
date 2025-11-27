# Right to be & Right to know (R&R)

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 📖 תיאור הפרויקט | Project Description

### עברית
אתר מקיף לעולים חדשים בישראל המספק מידע משפטי, חיבור לעורכי דין ומערכת ביקורות. האתר מכיל מידע בנושאים שונים כגון מיסים, שיכון, תעסוקה ומלגות, ומאפשר לעולים חדשים לקבל ייעוץ משפטי מקצועי.

### English
A comprehensive website for new immigrants in Israel providing legal information, lawyer connections, and a review system. The site contains information on various topics such as taxes, housing, employment, and scholarships, enabling new immigrants to receive professional legal advice.

---

## ✨ תכונות עיקריות | Main Features

### 🔐 מערכת משתמשים | User System
- **רישום והתחברות** - Registration and login system
- **שני סוגי משתמשים** - Two user types:
  - משתמשים רגילים (Regular users)
  - עורכי דין (Lawyers)
- **אזור אישי** - Personal area for each user type

### 👨‍⚖️ מערכת עורכי דין | Lawyer System
- **פרופילים מקצועיים** - Professional lawyer profiles
- **מערכת דירוג וביקורות** - Rating and review system
- **אישור ביקורות** - Review approval system (for lawyers)
- **איזור אישי לעורכי דין** - Personal area for lawyers

### 💬 פורום ותקשורת | Forum & Communication
- **פורום שאלות** - Q&A forum for legal questions
- **אישור קישורים** - Link approval system
- **אינטראקציה בין משתמשים** - User interaction

### 📚 דפי מידע | Information Pages
- **מיסים** (tax.html) - Tax information
- **שיכון** (שיכון.html) - Housing information
- **תעסוקה** (תעסוקה.html) - Employment information
- **מלגה** (מלגה.html) - Scholarship information
- **אודות** (אודות.html) - About page

### 🛡️ ניהול מערכת | System Management
- **פאנל אדמין** - Admin control panel
- **ניהול משתמשים** - User management
- **בקרת תוכן** - Content control

---

## 🗂️ מבנה הפרויקט | Project Structure

```
HTML-CSS-JS/
│
├── 📄 דפי HTML עיקריים | Main HTML Pages
│   ├── homePage.html              # דף הבית | Homepage
│   ├── login.html                 # התחברות/הרשמה | Login/Register
│   ├── forum.html                 # פורום | Forum
│   ├── lawyer_profile.html        # פרופיל עורך דין | Lawyer Profile
│   ├── lawyer_personal_area.html  # אזור אישי עורך דין | Lawyer Personal Area
│   ├── lawyer_review_rating.html  # דירוג וביקורות | Reviews & Ratings
│   ├── review.html                # דף ביקורת | Review Page
│   ├── approve_review.html        # אישור ביקורות | Approve Reviews
│   ├── approve_link.html          # אישור קישורים | Approve Links
│   └── admin_control_user.html    # ניהול משתמשים | User Management
│
├── 📄 דפי מידע | Information Pages
│   ├── tax.html                   # מיסים | Taxes
│   ├── שיכון.html                 # שיכון | Housing
│   ├── תעסוקה.html                # תעסוקה | Employment
│   ├── מלגה.html                  # מלגות | Scholarships
│   ├── אודות.html                 # אודות | About
│   └── פרופיל עורכי דין.html      # פרופיל ע"ד | Lawyer Profile
│
├── 🎨 קבצי CSS | CSS Files
│   ├── pj_style.css               # עיצוב כללי | General styling
│   ├── login_page.css             # עיצוב התחברות | Login styling
│   ├── styleForum.css             # עיצוב פורום | Forum styling
│   └── admin_control_user.css     # עיצוב אדמין | Admin styling
│
├── 💻 קבצי JavaScript | JavaScript Files
│   ├── homepage.js                # לוגיקת דף הבית | Homepage logic
│   ├── login_page.js              # לוגיקת התחברות | Login logic
│   ├── forum.js                   # לוגיקת פורום | Forum logic
│   ├── lawyer_review_rating.js    # לוגיקת ביקורות | Review logic
│   └── admin_control_user.js      # לוגיקת אדמין | Admin logic
│
└── 🧪 קבצי בדיקה | Test Files
    ├── lawyer_review_rating.test.js
    └── forum_test.js
```

---

## 🚀 התקנה והפעלה | Installation & Setup

### דרישות מקדימות | Prerequisites
- דפדפן אינטרנט מודרני (Chrome, Firefox, Safari, Edge)
- Modern web browser (Chrome, Firefox, Safari, Edge)

### הפעלה מקומית | Local Setup

1. **שכפל את הפרויקט | Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/HTML-CSS-JS.git
cd HTML-CSS-JS
```

2. **פתח את הפרויקט | Open the project**
   - פתח את הקובץ `homePage.html` בדפדפן
   - Open `homePage.html` in your browser
   - או השתמש ב-Live Server ב-VS Code
   - Or use Live Server in VS Code

3. **אין צורך בהתקנה נוספת** - הפרויקט עובד עם HTML, CSS ו-JavaScript טהור
   **No additional installation needed** - Pure HTML, CSS, and JavaScript

---

## 🧪 הרצת בדיקות | Running Tests

הפרויקט כולל בדיקות יחידה עבור מרכיבים מרכזיים:

```bash
# בדיקות מערכת הביקורות
# Review system tests
node lawyer_review_rating.test.js

# בדיקות פורום
# Forum tests
node forum_test.js
```

---

## 📱 שימוש באתר | Usage

### למשתמשים | For Users
1. **הרשמה** - לחץ על "התחברות/הרשמה" ובחר "משתמש"
2. **עיון במידע** - עיין בדפי המידע השונים (מיסים, שיכון, תעסוקה, מלגות)
3. **חיפוש עורך דין** - לחץ על "עורך דין" לצפייה בפרופילים
4. **כתיבת ביקורת** - לחץ על "ביקורות" לכתיבת ביקורת על עורך דין
5. **פורום** - שאל שאלות בפורום ותקבל תשובות מעורכי דין

### לעורכי דין | For Lawyers
1. **הרשמה** - לחץ על "התחברות/הרשמה" ובחר "עורך דין"
2. **ניהול פרופיל** - עדכן את הפרופיל האישי שלך
3. **מענה לשאלות** - ענה על שאלות בפורום
4. **ניהול ביקורות** - צפה ואשר ביקורות באזור האישי

### למנהלי מערכת | For Admins
1. **התחבר כאדמין** - Access admin control panel
2. **ניהול משתמשים** - User management and moderation
3. **בקרת תוכן** - Content approval and moderation

---

## 🛠️ טכנולוגיות | Technologies

- **HTML5** - מבנה הדפים | Page structure
- **CSS3** - עיצוב ואנימציות | Styling and animations
- **JavaScript (Vanilla)** - לוגיקה ואינטראקציה | Logic and interaction
- **LocalStorage** - שמירת נתונים מקומית | Local data storage

---

## 👥 תרומה לפרויקט | Contributing

אנו מברכים תרומות לפרויקט! אם ברצונך לתרום:

We welcome contributions! If you'd like to contribute:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 רישיון | License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 📧 יצירת קשר | Contact

**קבוצה 25 | Group 25**

כל הזכויות שמורות © 2024

---

## 🙏 תודות | Acknowledgments

- תודה לכל העולים החדשים שהשתמשו באתר
- Thanks to all new immigrants who used the site
- תודה לעורכי הדין המשתתפים
- Thanks to the participating lawyers
- תודה למפתחים והתורמים
- Thanks to all developers and contributors

---

## 🔮 תכונות עתידיות | Future Features

- [ ] מערכת צ'אט בזמן אמת
- [ ] Real-time chat system
- [ ] אפליקציית מובייל
- [ ] Mobile application
- [ ] תרגום לשפות נוספות
- [ ] Translation to additional languages
- [ ] מערכת תשלומים
- [ ] Payment system
- [ ] אינטגרציה עם לוח השנה
- [ ] Calendar integration

---

**Made with ❤️ for new immigrants in Israel**
