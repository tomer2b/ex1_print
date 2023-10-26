<div dir="rtl">
<h1>משימת קבצים</h1>
<p> לשימושכם קישור למצגת בנושא קבצים 
<a href="https://drive.google.com/file/d/1-OG-LvU12n7VHXEVbR3hopFG_kdRsLMj/view">מצגת</a>
  </p>
<p> לשימושכם קישור לדוגמאות קוד בנושא קבצים 
<a href="https://www.w3schools.com/python/python_file_handling.asp">קישור ל-w3school</a>
  </p>
<h2>הסברים לגבי הפעולה main 
</h2>
<h3>
במשימה זו נעשה לראשונה שימוש בהעברת פרמטרים לתכנית main מתוך פקודת shell
במשימה זו הרצת התכנית תתבצע באופן הבא מחלונית ה-shell  , להלן מספר דוגמאות פקודות הרצה
</h3>
</div>
<div dir=ltr>

```python
 python main.py printer xyz__hello__.txt
 python main.py copy ./files/stam.txt ../mystam.txt
 python main.py lazy Exercise.txt
```
<div dir="rtl">
  <h3>
אתם תצטרכו לכתוב את הקוד עבור כל אחת מהפקודות הנ"ל
לדוגמא בקובץ printer.py אתם תכתבו את הקוד לשאלה 1 וההרצה לא תתבצע על ידי לחיצה על לחצן  run אלא תתבצע מהרצת הפקודה הבאה ב-shell
  </h3>
  </div>
<div dir=ltr>

  ```python
 python main.py printer xyz__hello__.txt
```

<div dir=rtl>
  <h2>שאלה 1</h2>
  <h3>
    בכל הרצת פקודה כל הפרמטרים בפקודה מתקבלים ברשימה בשם argv אשר מופיעה בתכנית main . ברשימה זו האיבר הראשון הינו שם התכנית שלנו שזה main.py . הפרמטר השני יהיה הפקודה עצמה , במקרה שלנו או printer או copy או lazy   והפרמטר השלישי יהיה תלוי בסוג הפקודה שלנו.
  אתם נדרשים להשלים את ה-main כך שתריץ את הפקודה המתאימה בהתאם למה שהתקבל בשורת הפקודה ונכנס לרשימהargv <br><br>
    שימו לב : לא לשנות את שורות הקוד שרצות ב-main !!! אפשר להוסיף שורות אך לא לשנות את הזימונים
  </h3>
  <h2>שאלה 2</h2>
    <h3>
    שימו לב כי בתיקיית הפרויקט שלכם מצוי קובץ טקסט בשם : xyz__hello__.txt . <br>
    המשימה שלכם היא לכתוב פעולה בשם printer אשר תקבל שם של קובץ , תקרא את התוכן של הקובץ ותדפיס למסך את התוכן שלו.<br><br>
      ממשו את הפעולה printer בקובץ printer.py .
    </h3>
  <h2>שאלה 3</h2>
  <h3>
כיתבו פונקציה ששמה paste_copy ,המקבלת שם קובץ ( בכתובת מלאה) ומעתיקה אותו לתיקייה נתונה.<br>
הרצה לדוגמה של הפונקציה:<br>
<div dir=ltr>

  ```python
copy_paste(r"/home/runner/hello.txt", r"/home/runner/hello2.txt")
```
</div>
  <br>
הרצה זו תעתיק את הקובץ שניתן בארגומנט הראשון אל התיקייה בארגומנט השני.<br><br>
שימו לב : 
<ul>
  <li>
    הפעולה צריכה לקבל כפרמטר את שם הקובץ כולל התיקייה שבה הוא נמצא (יחסי או מוחלט) , לפתוח את הקובץ לקריאה ולכתוב את תוכנו במיקום החדש
  </li>
  <li>
באופן ספציפי בתרגיל זה, אין להשתמש באף מודול חיצוני של פייתון אשר מאפשר העתקה של קבצים . וכן יש להשתמש בסלאש רגיל -/  בזימון של הפעולה.
<br>
    
  </li>
  <li>
 ודאו כי הפונקציה עובדת גם על קבצים שתוכנם בעברית.<br>
    </li>
 <li>
 ודאו כי הפונקציה עובדת גם על קבצים לא טקסטואלים (למשל תמונות)<br>
   </li>
   <li>
     לשימושכם טבלה המרכזת הבדלים בודדים בין מערכת ההפעלה של unix ל- windows.  שנועדה לספק היכרות קצרה עם המערכות.
   </li>
     <li>
המערכת ב-REPLIT היא עם מערכת הפעלה מסוג unix אתם יכולים לנסות פקודות בטאב שכותרתו shell<br>
  </li>
</ul>

<div align="right">
    <table dir="rtl" border="1" cellspacing="0" cellpadding="0">
        <tbody>
            <tr>
                <td width="212" valign="top">
                </td>
                <td width="252" valign="top">
                    <p align="center" dir="RTL">
                        Unix
                    </p>
                </td>
                <td width="270" valign="top">
                    <p align="center" dir="RTL">
                        windows
                    </p>
                </td>
            </tr>
            <tr>
                <td width="212" valign="top">
                    <p dir="RTL">
                        הצגת קבצים בתיקייה
                    </p>
                </td>
                <td width="252" valign="top">
                    <p dir="LTR">
                        ls -l
                    </p>
                </td>
                <td width="270" valign="top">
                    <p dir="LTR">
                        dir
                    </p>
                </td>
            </tr>
            <tr>
                <td width="212" valign="top">
                    <p dir="RTL">
                        הצגת שם תיקייה נוכחית
                    </p>
                </td>
                <td width="252" valign="top">
                    <p dir="LTR">
                        pwd
                    </p>
                </td>
                <td width="270" valign="top">
                    <p dir="LTR">
                        cd
                    </p>
                </td>
            </tr>
            <tr>
                <td width="212" valign="top">
                    <p dir="RTL">
                        מעבר לתיקיית במיקום מוחלט
                    </p>
                </td>
                <td width="252" valign="top">
                    <p dir="LTR">
                        cd /home/user/music
                    </p>
                </td>
                <td width="270" valign="top">
                    <p dir="LTR">
                      cd c:\users\tomer\music
                    </p>
                </td>
            </tr>
            <tr>
                <td width="212" valign="top">
                    <p dir="RTL">
                        מעבר לתיקייה יחסי למיקום שלנו (למשל מ-music) לתיקייה
                        ראשית.
                        <br/>
                        .. הפנייה לתיקייה שמעל
                    </p>
                    <p dir="RTL">
                        . הפנייה לתיקייה הנוכחית
                    </p>
                </td>
                <td width="252" valign="top">
                    <p dir="LTR">
                        cd ../../../
                    </p>
                </td>
                <td width="270" valign="top">
                    <p dir="LTR">
                        cd ..\..\..\
                    </p>
                </td>
            </tr>
            <tr>
                <td width="212" valign="top">
                    <p dir="RTL">
                        מיקום תיקייה ראשית Root
                    </p>
                </td>
                <td width="252" valign="top">
                    <p dir="LTR">
                        /
                    </p>
                </td>
                <td width="270" valign="top">
                    <p dir="LTR">
                        C:\
                    </p>
                </td>
            </tr>
            <tr>
                <td width="212" valign="top">
                    <p dir="RTL">
                        העתקת קבצים מהתיקייה הנוכחית
                    </p>
                </td>
                <td width="252" valign="top">
                    <p dir="LTR">
                        cp ./file1.txt ./file2.txt<br>
                      או<br>
                        cp file1.txt file2.txt
                    </p>
                </td>
                <td width="270" valign="top">
                    <p dir="LTR">
                        Copy .\file1.txt .\file2.txt<br>
                      או<br>
                        Copy file1.txt file2.txt
                    </p>
                </td>
            </tr>
            <tr>
                <td width="212" valign="top">
                </td>
                <td width="252" valign="top">
                </td>
                <td width="270" valign="top">
                </td>
            </tr>
            <tr>
                <td width="212" valign="top">
                </td>
                <td width="252" valign="top">
                </td>
                <td width="270" valign="top">
                </td>
            </tr>
        </tbody>
    </table>
</div>


</h3>
<h2> שאלה 4</h2>
<h3>
  מכיוון שאיננו יודעים האם הקבצים שמועברים כפרמטרי בכלל קיימים , אנו נרצה להוסיף בדיקה האם הקבצים קיימים לפני שנשלח לפעולה שמעתיקה או מדפיסה שכן אחרת הפעולה תיכשל והתכנית תסיים בצורה לא צפויה
  חפשו איך אפשר לבדוק האם קובץ קיים בפייתון וממשו זאת בקוד שלכם
</h3>
<h2>   שאלה 5 להגשה ,תיבדק עם ציון כאירוע הערכה</h2>
<h3>
ממשו את הפעולה lazy_student
אני ממליץ לכם לבצע בעצמכם ולא להעתיק 
<img src="./assets/2022-09-25 02_21_17.jpg">
</h3>
</div>
