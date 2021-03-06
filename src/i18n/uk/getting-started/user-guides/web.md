# <i class="fa fa-firefox"></i> Посібник користувача веб-клієнта

---

Для користувачів, які не хочуть встановлювати додаткове програмне забезпечення 
на своєму комп'ютері, є доступним простий веб-гаманець. Вона базується на
[Copay](https://github.com/bitpay/copay) зі специфічними змінами,
доданими Decred. Його можна знайти за адресою
[https://wallet.decred.org](https://wallet.decred.org)

Є кілька речей, які Вам потрібно знати про веб-клієнта,
перш ніж почати їм користуватися:

* YВи не можете "майнити"
  [stake mine](/mining/proof-of-stake.md)
  з його допомогою.
* Ваш гаманець повністю зберігається в локальному сховищі Вашого веб-
  браузера. Це означає, що якщо Ви видалите локальне сховище, Ви тим самим
  видалите гаманець і має відновлювати його потім із seed.
* Безпека Вашого гаманця цілком залежить від безпеки Вашого
  веб-браузера.
* Ви можете поставити pin на свій гаманець, щоб запобігти відправленню коштів, але будь-який
  інший доступ повністю залежить від елементів керування доступом на Вашому 
  комп'ютері, а не від сервера або облікових даних.

---

## <i class="fa fa-plus-circle"></i> Створіть гаманець свого веб-клієнта 

> Крок перший

Перейдіть на сторінку [https://wallet.decred.org](https://wallet.decred.org). З`явиться екран "Умови користування" (Terms and Conditions`). Зверніть особливу
увагу на таке:

Так само, як і з гаманцем командного рядка, якщо Ви втратите seed-слова або свій
пароль для відправлення коштів, Ви втратите доступ до свого гаманця. Скидання
пароля немає. Також зауважте, що всі транзакції Decred є незворотніми у відповідності
до задуму розробників. Якщо Ви випадково надіслали кошти на неправильну
адресу, Вам доведеться прохати одержувача відправити їх назад.
Розробники не в змозі повернути транзакцію у зворотній бік.

Клацніть `I Agree` прочитавши `Terms and Conditions`. Ви
побачите екран привітання. Якщо це перший раз, коли Ви використовуєте Decred,
натисніть "Почати" `Get Started`. If you want to restore a
previously used wallet, click `Import Backup`. Якщо Ви хочете відновити гаманець, який раніше використовувався,
натисніть "Імпортувати резервну копію" `Get Started`.У цьому посібнику ми будемо
виходити з того, що Ви тільки починаєте, тому натисніть "Почати

> Крок другий

Click the dropdown in the top left, then click `Add wallet`. Click
`Create New Wallet`. Give your wallet a name then click `Create New Wallet`.

A wallet will be generated for you.


> Крок третій

Ваш гаманець тепер створений та готовий до використання. Однак, перш ніж Ви почнете робити
щось іще, Ви маєте додати пароль для відправки коштів та скопіювати для зберігання 
seed-слова, які використовувались для створення Вашого гаманця. Це вдвічі важливіше
для веб-клієнта, який не зберігає постійний запис про Ваш гаманець.
Дані Вашого гаманця зберігаються в кеші браузера та можуть бути видалені
досить легко. Якщо Ви працюєте в режимі анонімного перегляду,
вони будуть видалені, як тільки Ви закриєте веб-браузер. ** БЕЗ ЦІЄЇ
SEED-ФРАЗИ ВИ ВТРАЧАЄТЕ ДОСТУП ДО ВСІХ КОШТІВ ВАШОГО ГАМАНЦЯ **, як тільки 
видаляються дані гаманця. Самі кошти все ще існують у блокчейні
однак, без seed Ви не маєте до них доступу.

<i class="fa fa-exclamation-triangle"></i> **НЕ ВИКОРИСТОВУЙТЕ ТОЙ САМИЙ SEED У ДЕКІЛЬКОХ ГАМАНЦЯХ! Для того, щоб зрозуміти, чому це важливо, відвідайте розділ "Поширені запитання щодо гаманців та seeds"][Wallets and Seeds FAQ](/faq/wallets-and-seeds.md#3-can-i-run-multiple-wallets) Рекомендовано, по можливості, щоб для кожного нового гаманця генерувався новий seed.** 

Натисніть кнопку "Параметри" `Preferences` праворуч, навпроти імені Вашого гаманця. Тут Вас цікавлять в основному тільки три речі:

Параметр                                | Опис
---                                   | ---
`Wallet Alias`                        | Ви можете перейменувати гаманець, якщо захочетеВи можете перейменувати гаманець, якщо захочете.
`Request Password for Spending Funds` | Оскільки Ваш гаманець зберігається в кеші браузера, для доступу до нього не потрібно додаткового пароля. Встановивши тут пароль, Ви будете впевнені, що тільки Ви зможете надсилати кошти, якщо ще хтось отримав доступ до Вашого браузера. Надрукуйте пароль і натисніть "Встановити" `Set`. Зверніть увагу на попередження, де зазначено, що паролі не можуть бути відновлені. У гаманці немає функції скидання пароля. Якщо Ви втратите пароль, Ви ніколи не зможете вилучити свої монети з гаманця або використовувати їх для proof-of-stake голосування.
`Backup`                              | Тут Ви знайдете свої seed-слова.

> Крок четвертий

Натисніть `Backup`. Ви побачите наступний екран:

Перш за все, прочитайте інформацію. З наявним seed використовуйте лише ОДИН 
гаманець за один раз (див [FAQ](#)). Ви можете встановити кілька гаманців на
різних машинах, але тільки один з них повинен працювати за один раз. Натисніть
"Показати seed гаманця" `Show Wallet Seed`. Запишіть його де-небудь у безпечному місці
або помістіть його в зашифрований документ, від якого Ви не забудете
пароль. Цей список слів використовується для генерування ключа аутентифікації
для Вашого гаманця. Кожен, хто має цей список, може отримати доступ до
коштів у Вашому гаманці.

> **ДУЖЕ ВАЖЛИВО**

**НІКОЛИ, ЗА БУДЬ-ЯКИХ ОБСТАВИН, НЕ НАДАВАЙТЕ НІКОМУ СВОЇХ SEED-СЛІВ! НАВІТЬ РОЗРОБНИКАМ!**

Після того, як Ви записали слова (і тричі перевірили, що вони правильні, великі літери важливі), перейдіть до наступного кроку.

> Крок п'ятий

Тепер, коли Ви записали seed-слова та перевірили їх, зробіть це ще раз.
Серйозно. Цей крок має вирішальне значення. Без цього списку Ваш гаманець
неможливо відтворити, і ніхто, навіть розробники, не зможуть його відновити.
Тепер, коли Ви впевнені, що список збережено правильно, клікніть "Видалити слова"
`Delete Words`. Click `Двічі натисніть "Назад"` щоб повернутися на головний екран гаманця.

---

## <i class="fa fa-long-arrow-right"></i> Відправка коштів за допомогою веб-клієнта 

> Крок перший

Натисніть кнопку "Надіслати" `Send` внизу головної сторінки веб-гаманця. 
Ви опиняєтесь на наступній сторінці. Зверніть увагу, що розділ меню "Додаткові параметри" `Advanced Options`
вже розгорнуто. В полі "Кому" `To` введіть Decred-
адресу одержувача.

> Step Two

У полі `Amount`, введіть кількість DCR, що треба надіслати одержувачу. Якщо Ви
бажаєте, можете ввести необов'язкове повідомлення у полі `Note` . Натисніть
`Send`. Опція "Використовувати непідтверджені кошти" `Use Unconfirmed Funds` дозволяє Вам використовувати кошти, 
щодо яких мережі відомо, що вони Вам відправлені, але ще не підтверджені
proof-of-work майнерами
[proof-of-work miners](/mining/proof-of-work.md). Якщо
трапиться таке, що зазначену суму можна бути покрити лише із використанням
непідтверджених коштів, транзакція не буде виконана, доки
необхідні кошти не будуть підтверджені.

---

## <i class="fa fa-long-arrow-left"></i> Отримання коштів за допомогою веб-клієнта 

> Крок перший

Натисніть кнопку "Отримати" `Receive` у нижній частині вікна. Ви побачите
таку сторінку:

Надайте особі, що надсилає Вам DCR, вказану адресу (вона починається
з `Ds`) або ж вони можуть використовувати QR-код, якщо їхній гаманець або сервіс
їх приймає. Ви можете використовувати ту саму адресу так часто, як бажаєте, але
задля забезпечення конфіденційності рекомендується створювати нову адресу кожного
разу. Не хвилюйтеся про те, що адреса може бути продубльована. Існує
близько `2.08x10^93` можливих адрес, тому ми скоріше дочекаємося
теплової смерті Всесвіту, ніж закінчаться Decred адреси.

