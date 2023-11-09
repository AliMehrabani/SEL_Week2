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
