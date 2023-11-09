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
<p>توابع موجود در واسط OrderSerive به گونه‌ای هستند که با وجود استفاده از یک متغیر مشخص برای هر 3 نوع از سفارش در کلاس Main، باید هر بار نوع سفارش را جهت استفاده درست از توابع بررسی کنیم.</p>
</td>
</tr>
</tbody>
</table>

در خصوص هرکدام از موارد نقض هرکدام از اصول، راهکار مناسب در جدول زیر آورده شده است:

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
<p>اصل 1: SRP</p>
</td>
<td width="246">
<p>پیاده‌سازی تمام توابع در تمام فرزندان واسط OrderService</p>
</td>
<td width="284">
<p>به دو صورت می‌توان این مشکل را حل کرد. روش اول این است که پیاده‌سازی والد را تغییر دهیم که فرزندان مجبور نباشند تمام توابع، حتی آن‌هایی که مربوط به خودشان نیست را هم override کنند. روش دوم این است که برای register و payment یک تابع در نظر بگیریم و هر فرزند آن را متناسب با روش خود override کند.</p>
</td>
</tr>
<tr>
<td width="168">
<p>اصل 2: OCP</p>
</td>
<td width="246">
<p>نیاز به تغییر کلاس تمام روش‌های ثبت سفارش برای اضافه کردن یک روش جدید</p>
</td>
<td width="284">
<p>برای حل این مشکل همان دو راه‌حلی که برای اصل 1 پیشنهاد داده شدند قابل استفاده خواهند بود.</p>
</td>
</tr>
<tr>
<td width="168">
<p>اصل 4: ISP</p>
</td>
<td width="246">
<p>واسط پیاده‌سازی شده بیش از حد بزرگ است و عملکردهای زیادی را پوشش می‌دهد</p>
</td>
<td width="284">
<p>برای حل این مشکل نیازی به ساختن واسط‌های کوچک‌تر نیست، بلکه می‌توان توابع را به دو عملکرد register و payment خلاصه کرد و جزئیات آن را به کلاس فرزند منتقل کنیم.</p>
</td>
</tr>
<tr>
<td width="168">
<p>اصل 5: DIP</p>
</td>
<td width="246">
<p>برای استفاده از توابع روش‌های سفارش، باید هر بار نوع کلاس آن را بررسی کنیم</p>
</td>
<td width="284">
<p>همانطور که در اصل‌های قبل نیز پیشنهاد داده شد، اگر توابع موجود در واسط را صرفا به دو تابع register و payment محدود کنیم، دیگر نیازی به بررسی نوع سفارش نبوده و به راحتی می‌توان از این دو تابع استفاده کرد.</p>
</td>
</tr>
</tbody>
</table>

## گام 3

در این گام ابتدا کد اصلی را بهبود دادیم و کامیت کردیم. سپس تغییرات خواسته شده در گام 1 را دوباره بر روی ان اعمال کردیم.

## گام 4

با توجه به تغییرات اعمال شده در کد مطابق پیشنهادات بخش 2، تعداد تغییرات بسیار کم می‌شود. در گام اول لازم بود دو تابع جدید به واسط اضافه کنیم، به هر کدام از دو روش قبل دو تابع جدید را اضافه کنیم و در کلاس روش جدید باید 6 تابع را override می‌کردیم که دیگر نیازی به انجام آن‌ها نیست. همچنین در کلاس Main تنها کافیست بخش ورودی گرفتن و ساختن روش پرداخت جدید را اضافه کنیم. در نتیجه از تغییرات 1، 2 ، 3، 4 ، 5، 6، 8، 9، 10، 11، 16 در گام 1 معاف خواهیم بود. پس تعداد کل تغییرات لازم 5 عدد خواهد بود که معادل تغییرات 7، 12، 13، 14، 15 از گام 1 می‌باشد.

## گام 5

با نگاه به گام 3 و 4 درمیابیم که با به کارگیری صحیح اصول SOLID می‌توان به چند مزیت عمده دست یافت:
- افزودن یک ویژگی یا رفتار جدید به کد با تغییرات کمتر و محدودتری همراه خواهد بود که این یعنی کد ما مقیاس‌پذیرتر (Scalable) و مناسب‌تر برای توسعه (Maintainable) است.
- برای پیاده‌سازی رفتاری کاملا مشابه، حجم کد و میزان تکرار قطعه‌های مشخصی از کد در حالت جدید کمتر خواهد بود.
- به علت حذف توابع و موارد نامربوط از هر کلاس، اگر برنامه ما به مشکلی بخورد، پیدا کردن مشکل راحت‌تر خواهد بود، چرا که مشخص است هر کلاس مسئول انجام چه کارهایی است.
