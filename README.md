ترتیب کلاس ها برای کامل کردن:

1. Human
2. Student
3. Professor
4. Main


سوال 1:  در کلاس Human متود ()staticPrint را طوری تغییر دهید که خروجی آن در کلاس هایی که کلاس Human را پیاده سازی می کنند قابل تغییر نباشد.

سوال 2:  کلاس Student را طوری تغییر دهید که هنگام صدا زدن متود ()sayMyName بر روی آن، مشخصه fullName آن در خروجی چاپ شود.

سوال 3:  مشخصه های زیر را با توابع Setter و Getter مناسب به کلاس Student اضافه کنید.
### studentNumber, majorName, universityName

سوال 4:  مشخصه های زیر را با توابع Setter و Getter مناسب به کلاس Professor اضافه کنید.
### professorFaculty, numberOfCourse, professorSpecialty

سوال 5: کلاس Professor را طوری تغییر دهید که هنگام صدا زدن متود ()sayMyName بر روی آن، مشخصه fullName و professorFaculty در خروجی چاپ شود.

سوال 6: بعد از کامل کردن کلاس های Student و Professor یک نمونه از هرکدام بسازید و با استفاده از کلمه کلیدی instanceof چک کنید که آیا این دو نمونه واقعا نمونه ای از کلاس Human هستند یا نه.

سوال 7: کد مقابل را بنویسید.
### Human human = new Student();
خروجی ()human.sayMyName چیست؟

سوال 8: حالا این کد را بنویسید.
### Human human = new Professor();
خروجی ()human.sayMyName چیست؟

از این دو مثال چه نتیجه ای می توان گرفت؟

سوال 9: در سوال 7، متغییر human به این شکل نیز قابل تعریف بود:
## Student human = new Student();
اگر متود ()sayMyName را بر روی متغییر human صدا بزنیم ، میبینیم که خروجی آن دقیقا با سوال شماره 7 یکسان است، در این صورت چرا ممکن است نیاز داشته باشیم که این متغیر را به صورت سوال 7 تعریف کنیم؟
به عنوان راهنمایی، سعی کنید لیستی از جنس Human بسازید که در ان هم Student و هم Professor داشته باشیم.
