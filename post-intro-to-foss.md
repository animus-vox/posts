# מבוא לקוד פתוח
##### או - מה הייתי רוצה לדעת קודם

### קדם דבר
קוד פתוח הוא תחום ענק, וקצת באופן דתי - כל אחד רואה אותו בצורה מעט שונה.  
על הנייר, המושג לא אומר יותר מכך שעבור תוכנה \ פרויקט מסוים, יש גישה פומבית לקהילה (Open source).  
עם זאת, מאחורי זה יש רבדים רבים, של סוגי אינטרסים ואידיאולוגיות של אנשים וארגונים שמניעים פרויקטי קוד פתוח רבים.  
בסדרת הפוסטים הזאת, אנסה לתמצת עד כדי quick-start guide, להנגיש את עולם הקוד הפתוח ולמעשה לתת לאנשים שרוצים אבל מרגישים שהם צריכים מישהו ש"יחזיק להם את היד" לפחות בהתחלה, כדי לשים את הרגל בדלת.  
עם סייג יחיד - כאן ברוב המקרים כשכתוב קוד פתוח, הכוונה היא ל-FOSS - "תוכנה חופשית וקוד פתוח" (שהקריטריונים שלה מעט שונים מההגדרה הרחבה יותר של קוד פתוח).  
כאן אנסה לענות על השאלות: למה קוד פתוח, למי קוד פתוח, ואיך קוד פתוח?  
אה, וכול התוכן הזה הוא 'תוכן פתוח', מנוהל [בגיט](https://github.com/animus-vox/posts/blob/main/post-intro-to-foss.md).  מוזמנים למצוא איפה היה עדיף לרדת שורה, איפה חסרה דוגמה, ומה לא - ולשפר את התוכן עבור כולם. 

#### למה קוד פתוח?
מקורות הקוד הפתוח הוא נושא רחב, ותיק, וקצרה היריעה מלהכיל.  
בעולם הזה משתתפים תאגידים, אינדיבידואלים וחברות ללא מטרות רווח.  
כיום, התמריצים העיקריים עבור המשתתף/ת הבודד/ת הם:
-    *תרומה* - פרויקטים רבים בקוד פתוח [מהווים בסיס לטכנולוגיות](https://xkcd.com/2347/) שמשמשות מיליוני אנשים בעולם.  
    סיוע לפרויקט כזה משמעו סיוע לאותם משתמשים ושירותים שנתמכים בו.  
    בסוף, גם תוכנה קטנה לכאורה שמתוחזקת ע"י מפתח בודד, עושה גלים כשכלים רבים נשענים עליה (לדוגמה, XZ Utils, [שלאחרונה עשתה כותרות](https://boehs.org/node/everything-i-know-about-the-xz-backdoor) כשניסו להחדיר דרכה רוגלה).  
    לא משכנע? תרומות קוד פתוח יכולות להמצא בכורים גרעיניים, משחקים, לימוד והדרכה, או סתם באפליקציה שעוזרת לנו לשמור על הקופונים במקום מסודר (חבל, יש פג תוקף).  
לתרום לקוד פתוח, אמנם בדרך כלל לא יביא הילולים רבים, אך תחושת המשמעות היא אמיתית.
-   *ניסיון* - כאשר מצטרפים לפרויקט קיים, בין אם לצוות חדש בעבודה או לפרויקט קוד פתוח - לומדים איך להשתלב בפרויקט קיים ואיך לעבוד עם צוות חדש, ולמרות זאת, גם איך לעבוד לבד - לא תמיד (ולמעשה, בדרך כלל) לא יהיה חבר צוות זמין במיוחד כדי לעזור בכל רגע נתון.  
    מצופה מכם להיות 'קומנדו', לתת באופן יחידני למאמץ הקבוצתי, ולשאול שאלות בצורה מדויקת.  
    כל שיפור שתגישו יעבור בדיקה ע"י לפחות בן אדם אחד אחר אם לא כמה.  
    לכן חשוב לזכור - Professionals have standards. אז עדיף לא לחשוב שהבייבי שלכם הוא נזר הבריאה כי תמיד יהיה מישהו שיוכיח שוואלה, התפספס נקודה פסיק. תהיו מוכנים לביקורת - כי היא תבוא.
-   *קהילה* - עבודה בקוד פתוח, ברוב המקרים, משמעה עבודה בקהילה. כדי להצטרף לפרויקט קיים תצטרכו להכיר את העבודה הקיימת, אז באופן טבעי - יעזור לדבר עם האנשים שכתבו אותה.  
    יעזור שיש מי שבודק שהעבודה שלכם מתאימה למה שמנסים להשיג.  
    יעזור שיש מי שמתאם מטלות בין חברי הצוות.  
    יעזור שיש מי שבודק, שמייעל, שמדווח באגים, ועוד אין-סוף פעולות לשיפור הפרויקט.  
    מכאן הדרך להכיר אנשים שיהיו מנטורים, קשרים וגם סתם חברים - קצרה.
    
-   *כי צריך* - לפעמים, ניתן למצוא ארגונים גדולים שמקצים משאבים (כסף, כוח אדם) לקידום דברים שיהיו נחלת הכלל. מבלבל? מפתיע?  
    לא!  
    כמו שנכתב קודם - קוד פתוח הוא בכול מקום. גם אצל ענקיות הטכנולוגיה.  
    לפעמים הן צריכות לשפר משהו, ובהתאם לרישיון של התוכנה, הן חייבות לשתף את התוצר.
    
כן, אחרי מסע השכנועים הזה, אני בטוח שחיי הקוד הפתוח נשמעים נוצצים, נפלאים ומלאי תהילה - אך למען ההגינות, חובה להתחבר למציאות.  
להשקיע שעות על גבי שעות במשהו שהוא, בתמצית דבר, side-project, זה קשה.
תמצאו מה מניע אתכם, בין אם חיבה לעשייה או מטרה ברורה כלשהי, אחרת יהיה קשה להתמיד.  
> "גוף שלא רוצה להיות בתנועה, יחזור למנוחה" -אני, עכשיו.

ועכשיו, with this new found knowledge, תוכלו לגשת לגיט, לקרוא את הכתבה לפני כולם, ולהציע נקודות לשיפור.  
נתראה בחלק הבא - למי קוד פתוח?

### למי קוד פתוח?
לכולם!  
פרויקטי קוד פתוח, למרות השם, לא תמיד דורשים קוד.
משחק יצטרך מעצבים גרפיים, כותבי תוכן, ועוד. עוד המון.  
אפליקציה תצטרך מתרגמים, מודול יצטרך אלגוריתמיקאים, ובקיצור - יש מקום לכולם.
  
בקדם דבר הזכרנו אידיאולוגיה? שווה להתעכב על זה!  
העיקרון המנחה מאחורי פרויקטי קוד פתוח חינמיים (FOSS) הוא שרוב התוכנות צריכות להיות נחלת הכלל - זמינות לכולם, לשימוש, שינוי, והפצה.
או לפחות, שתוכנות כאלו טובות מאלו שלא.
הרעיון חזק מספיק, כדי שקהילות שלמות יתאגדו, דמויות מפתח יוכתרו (ריצ'רד סטולמן מישהו?), ועל הדרך ליצור לא מעט מהטכנולוגיות שאנחנו משתמשים בהן היום, גם אם בעקיפין.

התחברתם? איזה כיף! לא? לא נורא.  
גם לתרום מצורך אנוכי יותר, כמו להשתפשף על פרויקט או לצבור צ'יזבט לראיונות ולחבר'ה זה בסדר.

למעשה - לא תהיו לבד. חלק מהפיתוח בתחום הקוד הפתוח נעשה בכלל ע"י תאגידים, בעזרת עובדים שמקבלים שכר עבור ההתעסקות שלהם בקוד הפתוח.
סביר להניח שאם זאת חברה טכנולוגית גדולה שכולם מכירים, היא תורמת כסף או כוח אדם לקוד פתוח.  
גוגל, מיקרוסופט, פייסבוק, ורבות נוספות, קטנות יותר ופחות.  
במקרה, הפירצה שהוזכרה מוקדם יותר? התגלתה ע"י עובד מיקרוסופט ששם לב להתנהגות מוזרה של אותו מודול.  
לא משנה הסיבה, בין אם עם רוח התנדבותית או קפיטליזם טהור, כולם מתקבלים בברכה.

### איך קוד פתוח?
הבשר! אז איך בעצם מתחילים?

כמו גיל ההתבגרות, התהליך הזה קצת משתנה מאדם לאדם.
ובכל זאת, נראה אם אפשר לסכם ולהסביר את זה עקרונית על רגל אחת.

בתור התחלה - או שיש לנו רעיון שנרצה לשתף עם העולם בתצורת מקור פתוח, או שאנחנו הולכים לעזור למישהו אחר או לקבוצה לממש רעיון קיים.
במקרה הראשון, זה די פשוט:
- לבחור רישיון תואם קוד פתוח (FOSS) שאנחנו אוהבים (לדוגמה, The Unlicense).
- לפי הרישיון הזה, אנשים וארגונים ידעו מה התנאים, הזכויות והחובות שלהם במידה והם משתמשים בפרויקט.
ניתן להיעזר באתר [choosealicense](https://choosealicense.com/).
- לפרסם את הפרויקט במקום מתאים, ולבחור צורה שבה ניתן לנהל/לשלוח הצעות לשיפורים.
  שיטה נפוצה היא שימוש בגיט (Git), אך יש אלטרנטיבות.
- חשוב להצמיד את הרישיון שנבחר לפרויקט, בד"כ בקובץ בשם license.
- להמשיך כרגיל, ולחכות לתורמים נוספים לפרויקט.
	כמנהלי פרויקטים, עליכם להוביל את החזון, לברור איזה תרומות יהפכו לחלק מהפרויקט, ועוד.

**האלטרנטיבה:**

לנעול מגפיים, להפשיל שרוולים, ולהיכנס לעומק הפרויקט של מישהו אחר.
-   *חיפוש* - למצוא פרויקט שאנחנו מתחברים אליו, או צריכים לשפר בו משהו.
אבל איפה? בקהילות [קוד פתוח ישראליות](https://maakaf-landing-page.netlify.app/) או בכול מקום שמתוייג כ-[Good first issue](https://goodfirstissue.dev/). [כזה](https://github.com/topics/good-first-issue) או [אחר](https://www.firsttimersonly.com/).
-   *קאה"מ \ RTFM* - במידה וקיימת תשתית לתורמים (wiki כלשהו, FAQ), כדאי (וחובה) להתחיל משם.  
    פרויקטים קהילתיים בדרך כלל ינסו לתת כמה שיותר הכוונה בתצורה של תיעוד כתוב, כדי למנוע שאלות חוזרות.
- לחזור לסעיף הקודם ולעשות אותו שוב. חברי קהילות יעריכו שאלות שבאות ממקום של הבנה.  
לפעמים יש אנשים שיענו לשאלות בצורה מכילה יותר, או מכילה פחות, אבל כולם רוצים לעבוד עם אנשים מקצועיים, ואף אחד לא רוצה להשקיע את הזמן שלו על מישהו שלא השקיע בעצמו ובדק את ה-FAQ.
- ליצור קשר עם המנהל/הקהילה ולשאול איפה אפשר לעזור,  
או לחילופין לבדוק אם יש רשימה קיימת של מטלות, ולבחור מטלה. בגיטהאב אפשר למצוא רשימה כזאת תחת טאב Issues.

-   מכאן, ניתן להגיש את התיקונים בפלטפורמה המתאימה של הפרויקט, ולומר מזל טוב!  
סתם - לא אומרים הופ לפני שקופצים, ולא אומרים תרמתי לפני שאושר ה-Pull request.  
עד כאן, הרווחתם מעט ניסיון, עכשיו נותר להרוויח שיעור נוסף: review.  
  בשלב הזה מקבלים הערות (בונות, בתקווה) ונדרשים לתקן בהתאם.
כמה כאלה back and forth, עד שבסופו של דבר מאשרים את הבקשה. עכשיו באמת אפשר להתמלא תחושת גאווה :)
   
	בשלב הזה כבר אפשר להמשיך ללמוד את הפרויקט, ולתרום לו בכל צורה נוספת, Rinse and repeat.

