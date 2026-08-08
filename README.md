# Django `models.py` — 50 ta test savoli
---

## Savol 1

Django'da **Model** nima?
- [A] Foydalanuvchi formasining Python ko‘rinishi

- [B] Ma'lumotlar bazasidagi jadvalning Python ko‘rinishi

- [C] URL tizimining asosiy Python ko‘rinishi

- [D] Admin sahifasining maxsus Python ko‘rinishi

---

## Savol 2

Django model odatda qaysi faylda yoziladi?
- [A] Model kodi odatda `views.py` faylida yoziladi

- [B] Model kodi odatda `urls.py` faylida yoziladi

- [C] Model kodi odatda `models.py` faylida yoziladi

- [D] Model kodi odatda `admin.py` faylida yoziladi

---

## Savol 3

Model yaratishda qaysi klassdan meros olish majburiy?
- [A] `models.Database` klassidan meros olish kerak

- [B] `models.Model` klassidan meros olish kerak

- [C] `models.Table` klassidan meros olish kerak

- [D] `models.Base` klassidan meros olish kerak

---

## Savol 4

Django modelidagi klass ma'lumotlar bazasidagi nimaga mos keladi?
- [A] Klass ma'lumotlar bazasidagi ustunga mos keladi

- [B] Klass ma'lumotlar bazasidagi qatorga mos keladi

- [C] Klass ma'lumotlar bazasidagi jadvalga mos keladi

- [D] Klass ma'lumotlar bazasidagi indeksga mos keladi

---

## Savol 5

Django modelidagi field ma'lumotlar bazasidagi nimaga mos keladi?
- [A] Field ma'lumotlar bazasidagi jadvalga mos keladi

- [B] Field ma'lumotlar bazasidagi ustunga mos keladi

- [C] Field ma'lumotlar bazasidagi qatorga mos keladi

- [D] Field ma'lumotlar bazasidagi modelga mos keladi

---

## Savol 6

`Student(...)` kabi model obyekti ma'lumotlar bazasidagi nimaga mos keladi?
- [A] Model obyekti ma'lumotlar bazasidagi jadvalga mos keladi

- [B] Model obyekti ma'lumotlar bazasidagi ustunga mos keladi

- [C] Model obyekti ma'lumotlar bazasidagi qatorga mos keladi

- [D] Model obyekti ma'lumotlar bazasidagi bazaga mos keladi

---

## Savol 7

Django modelida `id` maydoni yozilmasa nima bo‘ladi?
- [A] Django modelni avtomatik ravishda o‘chirib yuboradi

- [B] Django `id` maydonini avtomatik ravishda qo‘shib beradi

- [C] Django modelni jadval sifatida tan olmay qo‘yadi

- [D] Django barcha maydonlarni avtomatik ravishda o‘chiradi

---

## Savol 8

Django avtomatik qo‘shadigan `id` maydoni qanday vazifani bajaradi?
- [A] Maydon odatda obyektni aniqlash uchun xizmat qiladi

- [B] Maydon odatda email formatini tekshirishga xizmat qiladi

- [C] Maydon odatda fayl manzilini saqlashga xizmat qiladi

- [D] Maydon odatda matn uzunligini tekshirishga xizmat qiladi

---

## Savol 9

`CharField` asosan qanday ma'lumotlar uchun ishlatiladi?
- [A] `CharField` odatda qisqa matnlarni saqlash uchun ishlatiladi

- [B] `CharField` odatda sana qiymatlarini saqlash uchun ishlatiladi

- [C] `CharField` odatda rasm fayllarini saqlash uchun ishlatiladi

- [D] `CharField` odatda mantiqiy qiymatlarni saqlash uchun ishlatiladi

---

## Savol 10

`TextField` qaysi maqsadda ishlatiladi?
- [A] `TextField` odatda qisqa sonlarni saqlash uchun ishlatiladi

- [B] `TextField` odatda uzun matnlarni saqlash uchun ishlatiladi

- [C] `TextField` odatda sana qiymatlarini saqlash uchun ishlatiladi

- [D] `TextField` odatda email manzillarini saqlash uchun ishlatiladi

---

## Savol 11

`CharField` va `TextField` o‘rtasidagi asosiy farq qaysi?
- [A] `CharField` sana saqlaydi, `TextField` esa raqam saqlaydi

- [B] `CharField` uzunligi cheklangan, `TextField`da esa shart emas

- [C] `CharField` email saqlaydi, `TextField` esa URL saqlaydi

- [D] `CharField` fayl saqlaydi, `TextField` esa rasm saqlaydi

---

## Savol 12

`CharField` uchun qaysi parametr majburiy?
- [A] `CharField` uchun `default` parametri majburiy hisoblanadi

- [B] `CharField` uchun `null` parametri majburiy hisoblanadi

- [C] `CharField` uchun `max_length` parametri majburiy hisoblanadi

- [D] `CharField` uchun `blank` parametri majburiy hisoblanadi

---

## Savol 13

`max_length` nimani bildiradi?
- [A] Maydon uchun saqlanadigan maksimal qatorlar sonini bildiradi

- [B] Maydon uchun saqlanadigan maksimal belgilar sonini bildiradi

- [C] Maydon uchun saqlanadigan maksimal obyektlar sonini bildiradi

- [D] Maydon uchun saqlanadigan maksimal raqamlar sonini bildiradi

---

## Savol 14

`EmailField`ning asosiy vazifasi nima?
- [A] Email qiymatining formatini tekshirish uchun ishlatiladi

- [B] Email qiymatining uzunligini avtomatik belgilash uchun ishlatiladi

- [C] Email qiymatini sana ko‘rinishida saqlash uchun ishlatiladi

- [D] Email qiymatini URL ko‘rinishida saqlash uchun ishlatiladi

---

## Savol 15

`URLField` nima uchun ishlatiladi?
- [A] URL manzillarini saqlash va tekshirish uchun ishlatiladi

- [B] Sana qiymatlarini saqlash va tekshirish uchun ishlatiladi

- [C] Rasm fayllarini saqlash va tekshirish uchun ishlatiladi

- [D] Butun sonlarni saqlash va tekshirish uchun ishlatiladi

---

## Savol 16

`SlugField` odatda qanday ma'lumot uchun ishlatiladi?
- [A] Slug odatda foydalanuvchi parolini saqlash uchun ishlatiladi

- [B] Slug odatda maqola matnini saqlash uchun ishlatiladi

- [C] Slug odatda URL uchun qulay manzil saqlashda ishlatiladi

- [D] Slug odatda foydalanuvchi yoshini saqlash uchun ishlatiladi

---

## Savol 17

`IntegerField` qanday qiymatlarni saqlaydi?
- [A] `IntegerField` odatda butun sonlarni saqlash uchun ishlatiladi

- [B] `IntegerField` odatda uzun matnlarni saqlash uchun ishlatiladi

- [C] `IntegerField` odatda sana va vaqtni saqlash uchun ishlatiladi

- [D] `IntegerField` odatda rasm va fayllarni saqlash uchun ishlatiladi

---

## Savol 18

`PositiveIntegerField`ning `IntegerField`dan asosiy farqi nimada?
- [A] `PositiveIntegerField` faqat matn qiymatlarini saqlaydi

- [B] `PositiveIntegerField` faqat sana qiymatlarini saqlaydi

- [C] `PositiveIntegerField` musbat butun qiymatlarga mo‘ljallangan

- [D] `PositiveIntegerField` faqat kasr qiymatlarni saqlashga mo‘ljallangan

---

## Savol 19

Pul qiymatlarini saqlash uchun qaysi field tavsiya qilingan?
- [A] Pul qiymatlari uchun `FloatField` ishlatish tavsiya qilingan

- [B] Pul qiymatlari uchun `DecimalField` ishlatish tavsiya qilingan

- [C] Pul qiymatlari uchun `TextField` ishlatish tavsiya qilingan

- [D] Pul qiymatlari uchun `IntegerField` ishlatish tavsiya qilingan

---

## Savol 20

Nima sababdan pul uchun `FloatField` ishlatish tavsiya etilmaydi?
- [A] `FloatField` matn qiymatlarini saqlashda xatolik beradi

- [B] `FloatField` sana qiymatlarini saqlashda xatolik beradi

- [C] `FloatField` yaxlitlash xatoliklariga olib kelishi mumkin

- [D] `FloatField` rasm qiymatlarini saqlashda xatolik beradi

---

## Savol 21

`DecimalField(max_digits=10, decimal_places=2)`dagi `max_digits` nimani bildiradi?
- [A] `max_digits` verguldan keyingi raqamlar sonini bildiradi

- [B] `max_digits` jami raqamlar sonini bildiradi

- [C] `max_digits` faqat butun qism raqamlarini bildiradi

- [D] `max_digits` maksimal belgilar sonini bildiradi

---

## Savol 22

`decimal_places=2` nimani bildiradi?
- [A] `decimal_places=2` jami ikkita raqam bo‘lishini bildiradi

- [B] `decimal_places=2` verguldan keyin ikkita raqam bo‘lishini bildiradi

- [C] `decimal_places=2` butun qismda ikkita raqam bo‘lishini bildiradi

- [D] `decimal_places=2` maksimal qiymat ikkiga tengligini bildiradi

---

## Savol 23

`DateField` qanday ma'lumotni saqlaydi?
- [A] `DateField` faqat vaqt qiymatini saqlash uchun ishlatiladi

- [B] `DateField` faqat sana qiymatini saqlash uchun ishlatiladi

- [C] `DateField` sana va vaqt qiymatini saqlash uchun ishlatiladi

- [D] `DateField` davomiylik qiymatini saqlash uchun ishlatiladi

---

## Savol 24

`DateTimeField` qanday ma'lumotni saqlaydi?
- [A] `DateTimeField` faqat sana qiymatini saqlash uchun ishlatiladi

- [B] `DateTimeField` faqat vaqt qiymatini saqlash uchun ishlatiladi

- [C] `DateTimeField` sana va vaqt qiymatini saqlash uchun ishlatiladi

- [D] `DateTimeField` faqat davomiylik qiymatini saqlash uchun ishlatiladi

---

## Savol 25

`TimeField` nimani saqlaydi?
- [A] `TimeField` faqat sana qiymatini saqlash uchun ishlatiladi

- [B] `TimeField` faqat vaqt qiymatini saqlash uchun ishlatiladi

- [C] `TimeField` sana va vaqt qiymatini saqlash uchun ishlatiladi

- [D] `TimeField` faqat davomiylik qiymatini saqlash uchun ishlatiladi

---

## Savol 26

`BooleanField` qanday qiymatlar uchun ishlatiladi?
- [A] `BooleanField` sana va vaqt qiymatlari uchun ishlatiladi

- [B] `BooleanField` matn va URL qiymatlari uchun ishlatiladi

- [C] `BooleanField` `True` yoki `False` qiymatlar uchun ishlatiladi

- [D] `BooleanField` kasr va butun son qiymatlar uchun ishlatiladi

---

## Savol 27

`ImageField`dan foydalanish uchun manbaga ko‘ra qaysi kutubxona kerak?
- [A] `ImageField` uchun Django Forms kutubxonasi kerak bo‘ladi

- [B] `ImageField` uchun Pillow kutubxonasi kerak bo‘ladi

- [C] `ImageField` uchun Django Admin kutubxonasi kerak bo‘ladi

- [D] `ImageField` uchun Python Math kutubxonasi kerak bo‘ladi

---

## Savol 28

`FileField`ning asosiy vazifasi nima?
- [A] `FileField` faqat rasm fayllarini saqlash uchun ishlatiladi

- [B] `FileField` faqat matn qiymatlarini saqlash uchun ishlatiladi

- [C] `FileField` har qanday faylni saqlash uchun ishlatiladi

- [D] `FileField` faqat URL manzillarini saqlash uchun ishlatiladi

---

## Savol 29

`upload_to='avatars/'` nimani bildiradi?
- [A] Fayl `media/avatars/` papkasiga saqlanishini bildiradi

- [B] Fayl `media/documents/` papkasiga saqlanishini bildiradi

- [C] Fayl `media/images/` papkasiga saqlanishini bildiradi

- [D] Fayl `media/files/` papkasiga saqlanishini bildiradi

---

## Savol 30

`default` parametrining vazifasi nima?
- [A] Qiymat berilmasa, maydonga avtomatik qiymat beradi

- [B] Qiymat berilmasa, maydonni avtomatik ravishda o‘chiradi

- [C] Qiymat berilmasa, maydonni avtomatik ravishda yashiradi

- [D] Qiymat berilmasa, maydon uzunligini avtomatik belgilaydi

---

## Savol 31

`timezone.now()` va `timezone.now` o‘rtasidagi muhim farq nima?
- [A] `timezone.now()` qiymat, `timezone.now` esa funksiya sifatida beriladi

- [B] `timezone.now()` funksiya, `timezone.now` esa sana qiymati sifatida beriladi

- [C] `timezone.now()` matn, `timezone.now` esa raqam qiymati sifatida beriladi

- [D] `timezone.now()` vaqt, `timezone.now` esa sana qiymati sifatida beriladi

---

## Savol 32

`null=True` asosan nimaga tegishli?
- [A] `null=True` asosan forma validatsiyasiga tegishli hisoblanadi

- [B] `null=True` asosan ma'lumotlar bazasidagi bo‘shlikka tegishli

- [C] `null=True` asosan admin panel ko‘rinishiga tegishli hisoblanadi

- [D] `null=True` asosan URL manzillariga tegishli hisoblanadi

---

## Savol 33

`blank=True` nimani anglatadi?
- [A] `blank=True` bazada `NULL` saqlanishiga imkon beradi

- [B] `blank=True` forma orqali maydonni bo‘sh qoldirishga imkon beradi

- [C] `blank=True` maydonni faqat raqam qabul qilishga majbur qiladi

- [D] `blank=True` maydon qiymatini avtomatik ravishda o‘zgartiradi

---

## Savol 34

Manbadagi “oltin qoida”ga ko‘ra ixtiyoriy matn maydoni qanday yoziladi?
- [A] Ixtiyoriy matn uchun `null=True` ishlatish tavsiya qilinadi

- [B] Ixtiyoriy matn uchun `null=True, blank=True` ishlatish kerak

- [C] Ixtiyoriy matn uchun faqat `blank=True` ishlatish tavsiya qilinadi

- [D] Ixtiyoriy matn uchun `default=None` ishlatish tavsiya qilinadi

---

## Savol 35

`auto_now_add=True` va `auto_now=True` o‘rtasidagi asosiy farq qaysi?
- [A] `auto_now_add` har saqlashda, `auto_now` yaratishda yangilanadi

- [B] `auto_now_add` yaratishda, `auto_now` har saqlashda yangilanadi

- [C] `auto_now_add` va `auto_now` faqat yaratishda bir marta yangilanadi

- [D] `auto_now_add` va `auto_now` faqat forma yuborilganda yangilanadi

---

# II. Amaliy savollar — 15 ta
## Savol 36

Talabaning ismi uchun qaysi kod manbadagi tavsiyaga mos?
- [A] `first_name = models.IntegerField()`

- [B] `first_name = models.CharField(max_length=50)`

- [C] `first_name = models.DateField()`

- [D] `first_name = models.URLField()`

---

## Savol 37

Maqola matnini saqlash uchun qaysi field mos keladi?
- [A] `body = models.CharField(max_length=200)`

- [B] `body = models.IntegerField()`

- [C] `body = models.TextField()`

- [D] `body = models.URLField()`

---

## Savol 38

Mahsulot narxini saqlash uchun qaysi kod mos keladi?
- [A] `price = models.FloatField()`

- [B] `price = models.TextField()`

- [C] `price = models.DecimalField(max_digits=10, decimal_places=2)`

- [D] `price = models.IntegerField()`

---

## Savol 39

Ombordagi mahsulot soni manfiy bo‘lmasligi kerak. Qaysi field mos?
- [A] `stock = models.IntegerField()`

- [B] `stock = models.FloatField()`

- [C] `stock = models.PositiveIntegerField()`

- [D] `stock = models.DecimalField(max_digits=5, decimal_places=2)`

---

## Savol 40

Talabaning tug‘ilgan sanasi ixtiyoriy bo‘lishi kerak. Qaysi variant mos?
- [A] `birth_date = models.DateField()`

- [B] `birth_date = models.DateField(blank=True)`

- [C] `birth_date = models.DateField(null=True, blank=True)`

- [D] `birth_date = models.DateField(default=True)`

---

## Savol 41

Talabaning ixtiyoriy `bio` matni uchun qaysi kod mos?
- [A] `bio = models.TextField(null=True)`

- [B] `bio = models.TextField(blank=True)`

- [C] `bio = models.TextField(default=None)`

- [D] `bio = models.TextField(null=True, blank=True)`

---

## Savol 42

`age` bo‘sh qoldirilsa, bazada `NULL` saqlanishi kerak. Qaysi kod mos?
- [A] `age = models.IntegerField(blank=True)`

- [B] `age = models.IntegerField(null=True)`

- [C] `age = models.IntegerField(default=0)`

- [D] `age = models.IntegerField(null=True, blank=True)`

---

## Savol 43

Quyidagi modelda asosiy muammo nimada?
```python
from django.db import models
class Student:
    name = models.CharField(max_length=100)
```
- [A] `CharField` bu yerda noto‘g‘ri tanlangan

- [B] `max_length=100` bu yerda noto‘g‘ri berilgan

- [C] `Student` `models.Model`dan meros olmagan

- [D] `django.db.models` bu yerda noto‘g‘ri import qilingan

---

## Savol 44

`name` maydoni ko‘pi bilan 5 ta belgi qabul qilishi kerak. Qaysi kod mos?
- [A] `name = models.CharField(max_length=5)`

- [B] `name = models.CharField(max_length=50)`

- [C] `name = models.CharField(max_length=500)`

- [D] `name = models.CharField(max_length=5000)`

---

## Savol 45

Har bir yangi obyekt uchun yangi vaqt olinishi kerak. Qaysi kod mos?
- [A] `created_at = models.DateTimeField(default=timezone.now())`

- [B] `created_at = models.DateTimeField(default=timezone.now)`

- [C] `created_at = models.DateTimeField(default=True)`

- [D] `created_at = models.DateTimeField(blank=True)`

---

## Savol 46

`JSONField` uchun o‘zgaruvchan default ro‘yxatdan saqlanishi kerak. Qaysi kod mos?
- [A] `tags = models.JSONField(default=[])`

- [B] `tags = models.JSONField(default="")`

- [C] `tags = models.JSONField(default=list)`

- [D] `tags = models.JSONField(default=None)`

---

## Savol 47

Postning yaratilgan va oxirgi tahrir vaqtini avtomatik saqlash uchun qaysi variant mos?
- [A]

```python
created_at = models.DateTimeField(auto_now=True)
updated_at = models.DateTimeField(auto_now_add=True)
```
- [B]

```python
created_at = models.DateTimeField(auto_now_add=True)
updated_at = models.DateTimeField(auto_now=True)
```
- [C]

```python
created_at = models.DateTimeField(default=True)
updated_at = models.DateTimeField(default=True)
```
- [D]

```python
created_at = models.DateTimeField(blank=True)
updated_at = models.DateTimeField(blank=True)
```
---

## Savol 48

Talabaning rasmi ixtiyoriy bo‘lib, `students/` papkasiga saqlanishi kerak. Qaysi kod mos?
- [A] `photo = models.FileField(upload_to='students/')`

- [B] `photo = models.ImageField(upload_to='students/')`

- [C] `photo = models.TextField(blank=True)`

- [D] `photo = models.ImageField(upload_to='students/', null=True, blank=True)`

---

## Savol 49

Quyidagi modelda `price` berilmasa, nima sodir bo‘ladi?
```python
class Product(models.Model):
    name = models.CharField(max_length=100)
    price = models.DecimalField(
        max_digits=10,
        decimal_places=2,
        default=0
    )
    stock = models.PositiveIntegerField(default=0)
    is_available = models.BooleanField(default=True)
```
- [A] `price` qiymati avtomatik `NULL` bo‘ladi

- [B] `price` qiymati avtomatik `1` bo‘ladi

- [C] `price` qiymati avtomatik `0` bo‘ladi

- [D] `price` qiymati berilmaganda xatolik chiqadi

---

## Savol 50

Telefon raqami ixtiyoriy bo‘lishi kerak. Qaysi kod mos?
```python
class Student(models.Model):
    phone = models.CharField(max_length=20, ________)
```
- [A] `phone = models.CharField(max_length=20, null=True)`

- [B] `phone = models.CharField(max_length=20, blank=True)`

- [C] `phone = models.CharField(max_length=20, default=True)`

- [D] `phone = models.CharField(max_length=20, primary_key=True)`

---


