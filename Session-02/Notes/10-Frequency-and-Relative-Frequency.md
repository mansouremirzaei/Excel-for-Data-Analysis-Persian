
# Frequency and Relative Frequency

## هدف یادگیری
آشنایی با Frequency، Relative Frequency و Percentage برای خلاصه‌سازی متغیرهای دسته‌ای (Categorical Variables).

## 1. Key Concepts

- **Frequency (Count):** تعداد مشاهدات موجود در یک دسته
- **Relative Frequency:** نسبت تعداد مشاهدات یک دسته به تعداد کل مشاهدات
- **Percentage:** درصد فراوانی نسبی؛ برابر با Relative Frequency × 100

## 2. Example

### Frequency Table

| Department | Frequency |
|---|---:|
| Sales | 30 |
| IT | 25 |
| HR | 15 |
| Finance | 30 |
| **Total** | **100** |

### Frequency and Relative Frequency Table

| Department | Frequency | Relative Frequency | Percentage |
|---|---:|---:|---:|
| Sales | 30 | 0.30 | 30% |
| IT | 25 | 0.25 | 25% |
| HR | 15 | 0.15 | 15% |
| Finance | 30 | 0.30 | 30% |
| **Total** | **100** | **1.00** | **100%** |

## 3. Excel Formulas

فرض کنید نام دسته‌ها در سلول‌های D2 تا D5 و داده‌های اصلی در ستون A قرار دارند.

### Count Category

```excel
=COUNTIF($A$2:$A$101,D2)
```

این فرمول تعداد دفعات مشاهده دسته مشخص‌شده در D2 را محاسبه می‌کند.

### Relative Frequency

```excel
=E2/SUM($E$2:$E$5)
```

این فرمول فراوانی دسته را بر مجموع فراوانی‌ها تقسیم می‌کند.

### Percentage

برای نمایش Relative Frequency به‌صورت درصد:

1. سلول‌های مربوط به Relative Frequency را انتخاب کنید.
2. از تب Home گزینه Percentage را انتخاب کنید.

## 4. Interpretation

- Frequency تعداد واقعی مشاهدات هر دسته را نشان می‌دهد.
- Relative Frequency سهم هر دسته از کل داده‌ها را نشان می‌دهد.
- Percentage مقایسه سهم دسته‌ها را ساده‌تر می‌کند.

مجموع Relative Frequency باید برابر با 1 و مجموع Percentage باید برابر با 100% باشد؛ با در نظر گرفتن خطاهای احتمالی ناشی از گرد کردن.

## 5. Practice

یک Frequency Table برای یکی از متغیرهای زیر در مجموعه داده خود ایجاد کنید:

- Gender
- Education
- Job Category

سپس بررسی کنید که مجموع فراوانی‌ها برابر با تعداد مشاهدات غیرگمشده (Non-Missing Observations) باشد.
