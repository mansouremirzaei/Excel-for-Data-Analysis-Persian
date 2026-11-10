
# Scatter Plot and Box Plot

## هدف یادگیری
آشنایی با Scatter Plot و Box Plot و درک تفاوت کاربرد آن‌ها در تحلیل داده‌ها.

## 1. Scatter Plot

نمودار Scatter Plot برای نمایش رابطه بین دو متغیر کمی (Quantitative Variables) استفاده می‌شود.

- **X-axis:** متغیر توضیحی یا پیش‌بین (Explanatory / Predictor Variable) که با توجه به سؤال پژوهش انتخاب می‌شود.
- **Y-axis:** متغیر پاسخ یا نتیجه (Outcome / Response Variable) که با توجه به سؤال پژوهش انتخاب می‌شود.

### Example

نمودار Starting Salary را روی محور X و Current Salary را روی محور Y رسم کنید.

در نمودار به موارد زیر توجه کنید:

- **Positive Direction:** رابطه مثبت
- **Negative Direction:** رابطه منفی
- **Linear / Nonlinear Pattern:** الگوی خطی یا غیرخطی
- **Clusters:** خوشه‌ها
- **Potential Unusual Points:** نقاط غیرعادی احتمالی

خط روند (Trend Line) می‌تواند الگوی خطی را خلاصه کند، اما به‌تنهایی اثبات نمی‌کند که X باعث تغییر Y شده است.

## 2. Box Plot

نمودار Box Plot توزیع یک متغیر را با استفاده از شاخص‌های زیر نمایش می‌دهد:

- **Q1 (Lower Quartile):** چارک اول
- **Median (Q2):** میانه
- **Q3 (Upper Quartile):** چارک سوم
- **IQR:** دامنه بین چارکی

```text
IQR = Q3 - Q1
```

### Whiskers

در روش رایج، Whiskers تا دورترین نقاطی امتداد می‌یابند که در محدوده 1.5 × IQR از چارک‌ها قرار دارند.

### Potential Outliers

نقاطی که خارج از محدوده Whiskers قرار می‌گیرند، ممکن است به‌صورت نقاط جداگانه نمایش داده شوند؛ این موضوع به نرم‌افزار رسم نمودار بستگی دارد.

## 3. Interpretation Example

فرض کنید:

- Median Salary = 30,000
- Q1 = 25,000
- Q3 = 35,000

محاسبه IQR:

```text
IQR = Q3 - Q1
IQR = 35,000 - 25,000
IQR = 10,000
```

بنابراین، 50% میانی حقوق‌ها در بازه 25,000 تا 35,000 قرار دارند.

## 4. Practice

1. یک Scatter Plot برای دو ستون کمی از مجموعه داده خود ایجاد کنید.
2. یک Box Plot برای متغیر Salary رسم کنید.
3. نتایج دو نمودار را با یکدیگر مقایسه کنید.

**نکته:** Scatter Plot رابطه بین دو متغیر را بررسی می‌کند؛ درحالی‌که Box Plot توزیع یک متغیر را خلاصه می‌کند.
