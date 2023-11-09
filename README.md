# آزمایش دوم - آزمایشگاه مهندسی نرم‌افزار
اعضای گروه: امیرحسین ندایی پور، علی مهربانی

## گام 1

<table dir='rtl'>
<tbody>
<tr>
<td width="64">
<p><strong>ردیف</strong></p>
</td>
<td width="198">
<p><strong>محل اعمال تغییرات (کلاس/واسط)</strong></p>
</td>
<td width="141">
<p><strong>عنوان تغییر</strong></p>
</td>
<td width="292">
<p><strong>شرحی کوتاه از تغییر</strong></p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>1</strong></p>
</td>
<td width="198">
<p>Order Service</p>
</td>
<td width="141">
<p>افزودن تابع پرداخت تلفنی</p>
</td>
<td width="292">
<p>افزودن یک تابع void با عنوان phone Order Payment</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>2</strong></p>
</td>
<td width="198">
<p>Order Service</p>
</td>
<td width="141">
<p>افزودن تابع ثبت سفارش تلفتی</p>
</td>
<td width="292">
<p>افزودن یک تابع void با عنوان phone Order Register</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>3</strong></p>
</td>
<td width="198">
<p>OnSiteOrderService</p>
</td>
<td width="141">
<p>override کردن تابع ثبت سفارش تلفنی</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع Phone Order Register از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>4</strong></p>
</td>
<td width="198">
<p>OnSiteOrderService</p>
</td>
<td width="141">
<p>override کردن تابع پرداخت تلفنی</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع Phone Order Payment از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>5</strong></p>
</td>
<td width="198">
<p>OnlineOrderService</p>
</td>
<td width="141">
<p>override کردن تابع ثبت سفارش تلفنی</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع Phone Order Register از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>6</strong></p>
</td>
<td width="198">
<p>OnlineOrderService</p>
</td>
<td width="141">
<p>override کردن تابع پرداخت تلفنی</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع Phone Order Payment از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>7</strong></p>
</td>
<td width="198">
<p>PhoneOrderService</p>
</td>
<td width="141">
<p>افزودن کلاس جدید</p>
</td>
<td width="292">
<p>ساختن کلاس PhoneOrderService که واسط OrderService را پیاده‌سازی می‌کند</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>8</strong></p>
</td>
<td width="198">
<p>PhoneOrderService</p>
</td>
<td width="141">
<p>override کردن تابع OnSiteOrderRegister</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع OnSite Order Register از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>9</strong></p>
</td>
<td width="198">
<p>PhoneOrderService</p>
</td>
<td width="141">
<p>override کردن تابع OnSiteOrderPayment</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع OnSite Order Payment از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>10</strong></p>
</td>
<td width="198">
<p>PhoneOrderService</p>
</td>
<td width="141">
<p>override کردن تابع OnlineOrderRegister</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع Online Order Register از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>11</strong></p>
</td>
<td width="198">
<p>PhoneOrderService</p>
</td>
<td width="141">
<p>override کردن تابع OnlineOrderPayment</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع Online Order Payment از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>12</strong></p>
</td>
<td width="198">
<p>PhoneOrderService</p>
</td>
<td width="141">
<p>override کردن تابع PhoneOrderRegister</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع Phone Order Register از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>13</strong></p>
</td>
<td width="198">
<p>PhoneOrderService</p>
</td>
<td width="141">
<p>override کردن تابع PhoneOrderPayment</p>
</td>
<td width="292">
<p>پیاده‌سازی تابع Phone Order Payment از واسط Order Service</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>14</strong></p>
</td>
<td width="198">
<p>Main</p>
</td>
<td width="141">
<p>تغییر در پیام راهنمای بخش پرداخت</p>
</td>
<td width="292">
<p>اضافه شدن گزینه پرداخت تلفنی با وارد کردن شماره سه</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>15</strong></p>
</td>
<td width="198">
<p>Main</p>
</td>
<td width="141">
<p>امکان ثبت سفارش تلفنی</p>
</td>
<td width="292">
<p>اضافه کردن یک شرط اضافه در کد که با وارد شدن عدد 3 سفارش تلفنی ثبت کند</p>
</td>
</tr>
<tr>
<td width="64">
<p><strong>16</strong></p>
</td>
<td width="198">
<p>Main</p>
</td>
<td width="141">
<p>امکان پرداخت تلفنی</p>
</td>
<td width="292">
<p>اضافه کردن یک شرط اضافه در کد که در صورت تلفنی بودن سفارش ثبت شده به صورت تلفنی آن را پرداخت می‌کند</p>
</td>
</tr>
<tr>
</tbody>
</table>

مجموع تعداد تغییرات: 16

## گام 2

<table dir='rtl'>
<tbody>
<tr>
<td rowspan="2" width="240">
<p>اصل 1</p>
<p>Single Responsibility</p>
</td>
<td width="95">
<p><strong>موارد تحقق</strong></p>
</td>
<td width="454">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p><strong>موارد نقض</strong></p>
</td>
<td>
<p>توابع مربوط به Register و Payment برای هر روش پرداخت باید در کلاس مربوط به دیگر روش‌های پرداخت نیز override شوند. در نتیجه اگر بخواهیم برای یک روش پرداخت این دو تابع را تغییر دهیم، میبایست تغییرات در 3 کلاس متفاوت اعمال شوند.</p>
</td>
</tr>
<tr>
<td rowspan="2">
<p>اصل 2</p>
<p>Open-Close Principle (OCP)</p>
</td>
<td>
<p><strong>موارد تحقق</strong></p>
</td>
<td>
<p>در کلاس Main، برای اضافه کردن روش پرداخت تلفنی نیازی به تغییر عملکرد برنامه نبود و صرفا با اضافه کردن یک شرط جدید این قابلیت به کد افزوده شد.</p>
</td>
</tr>
<tr>
<td>
<p><strong>موارد نقض</strong></p>
</td>
<td>
<p>برای اضافه کردن PhoneOrderService باید دو تابع پرداخت و ثبت سفارش به واسط OrderService اضافه می‌کردیم که نیاز بود به کلاس دو روش دیگر نیز override کردن این دو تابع را اضافه کنیم که اصل 2 را نقض می‌کند.</p>
</td>
</tr>
<tr>
<td rowspan="2">
<p>اصل 3</p>
<p>Liskov Substitution Principle</p>
</td>
<td>
<p><strong>موارد تحقق</strong></p>
</td>
<td>
<p>در پیاده‌سازی OrderService چون از واسط استفاده شده، همه کلاس‌هایی که این واسط را پیاده‌سازی می‌کنند توابع آن را هم با توجه به ویژگی خاص خودشان override می‌کنند. در نتیجه رابطهIs-A برقرار است.</p>
</td>
</tr>
<tr>
<td>
<p><strong>موارد نقض</strong></p>
</td>
<td>
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td rowspan="2">
<p>اصل 4</p>
<p>Interface Segregation Principle</p>
</td>
<td>
<p><strong>موارد تحقق</strong></p>
</td>
<td>
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td>
<p><strong>موارد نقض</strong></p>
</td>
<td>
<p>واسط OrderService متدهای زیادی دارد که در پیاده‌سازی کلاس‌های فرزند عموما تعداد قابل توجهی از آنها بدنه خالی خواهند داشت. این یعنی تعریف واسط به هیچ هنوان بهینه نیست و موجب الزام تغییرات زیاد هنگام توسعه کد می‌شود.</p>
</td>
</tr>
<tr>
<td rowspan="2">
<p>اصل 5</p>
<p>Dependency Inversion Principle</p>
</td>
<td>
<p><strong>موارد تحقق</strong></p>
</td>
<td>
<p>در کلاس Main موجودیت order از نوع OrderService در نظر گرفته شده است که بتوان هر نوع از Order را به آن نسبت داد.</p>
</td>
</tr>
<tr>
<td>
<p><strong>موارد نقض</strong></p>
</td>
<td>
<p>توابع موجود در واسط OrderSerive به گونه‌ای هستند که با وجود استفاده از یک متغیر مشخص برای هر 3 نوع از سفارش، باید هر بار نوع سفارش را جهت اسافتاده درست از توابع بررسی کنیم.</p>
</td>
</tr>
</tbody>
</table>

در خصوص هرکدام از موارد نقض هرکدام از اصول، یک راهکار را به منظور رفع آن مشکل ارایه داده و در جدول زیر ثبت نمایید:

<table dir='rtl'>
<tbody>
<tr>
<td width="168">
<p><strong>اصل مربوطه (از اصول </strong><strong>SOLID</strong><strong>)</strong></p>
</td>
<td width="246">
<p><strong>علت نقض</strong></p>
</td>
<td width="284">
<p><strong>راه حل پیشنهادی</strong></p>
</td>
</tr>
<tr>
<td width="168">
<p>&nbsp;</p>
</td>
<td width="246">
<p>&nbsp;</p>
</td>
<td width="284">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="168">
<p>&nbsp;</p>
</td>
<td width="246">
<p>&nbsp;</p>
</td>
<td width="284">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="168">
<p>&nbsp;</p>
</td>
<td width="246">
<p>&nbsp;</p>
</td>
<td width="284">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="168">
<p>&nbsp;</p>
</td>
<td width="246">
<p>&nbsp;</p>
</td>
<td width="284">
<p>&nbsp;</p>
</td>
</tr>
</tbody>
</table>
