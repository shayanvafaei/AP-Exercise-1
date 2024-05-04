ترتیب کلاس ها برای کامل کردن:

1. Human
2. Student
3. Professor
4. Main

سوال ها

1. در کلاس Human متود staticPrint() را به طوری تغییر دهید که خروچی ان در کلاس هایی که کلاس Human را پیاده سازه میکنند
   قابل تغییر نباشد
2. کلاس Student را طوری تغییر دهید که هنگام صدا زدن متود sayMyName() بر روی ان، مشخصه fullName ان در خروجی چاپ شود
3. studentNumber, majorName, universityName مشخصه های مقابل را با توابع ستر و گتر مورد نیاز به کلاس Student اضافه کنید
4. مشخصه های مقابل را با توابع ستر و گتر مورد نیاز به کلاس Professor اضافه کنید professorSpecialty, professorFaculty,
   numberOfCourse
5. کلاس Professor را طوری تغییر دهید که هنگام صدا زدن متود sayMyName() بر روی ان، مشخصه fullName و professorFaculty در
   خروجی چاپ شود
6. بعد از کامل کردن کلاس های Student و Professor یک نمونه از هرکدام بسازید و با استفاده از کلمه کلیدی instanceof چک کنید
   که ایا این دو نمونه واقعا نمونه ای از کلاس Human هستند یا نه
7. کد مقابل را بنویسید
   Human human = new Student();
   خروجی human.sayMyName() چیست؟
8. حالا این کد را بنویسید
   Human human = new Professor();
   خروجی human.sayMyName() چیست؟
از این دو مثال چه نتیجه ای میتوان گرفت؟
9. در سوال هفت، متغییر human به این شکل نیز قابل تعریف بود:
Student human = new Student();<br>
اگر متود sayMyName() را بر روی متغییر human صدا بزنیم ، میبینیم که خروجی ان دقیقا با سوال شماره هفت یکسان است، در این صورت چرا ممکن است نیاز داشته باشیم که این متغیر را به صورت سوال هفت تعریف کنیم؟ <br>
به عنوان راهنمایی، سعی کنید لیستی از جنس Human بسازید که در ان هم Student و هم Professor داشته باشیم