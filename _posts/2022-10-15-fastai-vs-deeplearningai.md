# Bitta tanganing ikkita tarafi: Jeremi Hovard ning fast.ai va Andryu Ng ning deeplearning.ai kurslari

Mundarija:

1. TOC
{:toc}

Qanday qilib fast.ai va deeplearning.ai kurslarining ikkalasini ham o’rganib ‘overfit’ bo’lib qolmaslik haqida

![](/images/first-blog/fastai-deeplearningai.png "Qaysi biri yaxshiroq? BALKI IKKALASI HAMDIR")

Data Science va Sun’iy Intellekt sohalari qiziquvchilar kundan kunga ortib bormoqda. Ham izlanish ham haqiqiy hayotda qo’llanilish jihatidan ulkan yutuqlarga erishilmoqda. Bu esa albatta o’quvchi va bu sohaga qiziqqanlar uchun imkoniyatlar eshigini ochadi. Ammo, o’rganish uchun algoritmlar, dasturlash va muhandislik ko’nikmalari va yangidan-yangi maqolalar nixoyatda ko’p.

O’rganish uzoq va mashaqqatli, ammo bu sohlarning salohiyati shunchalik kattaligidan aqlli odamlarni o’ziga jalb qilmoqda. Yaxshi yangilik esa bizda bu jarayondagi qiyinchiliklarni yengillashtirish, va jarayonni son va qiziqarliroq qilish uchun mohir ta’lim beruvchilar bor. Shularning orasidan bizga eng foydali yo’llarni taklif qilayotgan 2 tasi haqida umumiy ma’lumot berishga harakat qilamiz.

## Sun’iy Intellektni o’rganishdagi ‘Burn-out’

![](/images/first-blog/chapter-1.png "Toa Heftiba ning Unsplash dagi rasmi")

Agar ‘yaxshi’ Data Scientist yoki Machine Learning(ML) muhandis bo’lish uchun bilish kerak bo’lgan bilimlar ro’yxatini tuzmoqchi bo’lsangiz, taxminan shunday ro’yxatga duch kelasiz:

**Matematika**: Chiziqli Algebra, Calculus, Statistika, Algoritmlar, …

**Kodlash**: Python, R, SQL/NoSQL, Hadoop, Spark, TensorFlow/PyTorch, Keras, Numpy, Pandas, OpenCV, Data Vizualization, …

**Algoritmlar**: Chiziqli Regressiya, Logistik Regressiya, SVM, PCA, Anomaliyalarni aniqlash, kollaborativ filtrlash, neyron tarmoqlar, CNN, RNN, K-Means, NLP, Deep Learning, Reinforcement Learning, …

**Muhandislik**: Command, Cloud platformalari(AWS, GCP, Azure), DevOps, Deploy qilish, NGINX/Apache, Docker, …

Ro’yxat endi boshlovchilarning boshini osongina qotirib qo’yishi mumkin. Va ba’zilar katta orzular bilan bunga sho’ng’ib ketadi va ko’p holatlarda nima qilayotganlarini bilmay ishtiyoqlari ishtiyoqni yo’qotishadi. Sizga ham bu yerda nimadir xatodek tuyulayabdimi?

## Ularda ‘overfit’ jarayoni ketmoqda

![](/images/first-blog/chapter-2.png "Andryu Ng ning Machine Lerning kursidan")

Overfitting ML ni biluvchilar orasidagi mashxur atama hisoblanadi. Bu algoritmningiz ma’lumotlarni shuncalik chuqur o’rganishidan mayda detallarga aralshib qolib umumiy ma’noni yo’qotganligini bildiradi. Tushunish uchun, ba’zida bizlar ham biror narsani o’rganishga shunchalik kirib ketganimizdan nega bu ishni qilayotganimizni unutganimizga o’xshaydi. Bu o’rganishdagi ‘overfitting’ deyiladi. Bu asosan akademik karyeraga ega odamlarda kuzatiladi. Matematikadan doktorlik darajasi bor odam ishga kirishishdan oldin har bir teoremani tushunib olishga harakat qiladi. Bu matematika uchun yaxshi. Nazariyalarni chuqur tushunish sizga katta sezish qobiliyati va ishonch bag’ishlaydi. Bu sizga boshqalar osonlikcha ko’ra olmaydigan muammolarni ko’rish imkonini beradi, ammo Data Science ko’proq narsani talab qiladi.

Ya'ni nazariydan tashqari amaliy qismi ham mavjud. Faqatgina algoritmdan tashqari samarali kodlar, ehtiyotkorlik bilan sozlangan giperparametrlar va yaxshi tuzilgan yo’l xaritasi bilan birgalikda yaxshi natijalarga erishadi.Nazariy qismiga sho’ng’ib ketish bilan amaliy qismini xavf ostida qoldirishingiz mumkin. Shuning uchun o’rganish bilan bir qatorda uni hayotiy muammolarni yechish uchun qo’llash ham muhimdir. Buni qanday qilamiz? Albatta, fast.ai va deeplearning.ai kurslarini o’rgangan holda.

## DeepLearning.ai va fast.ai

Bu sohalarni o’rganayotganlar uchun ko’plab kurslar ishlab chiqilgan bo’lib bularning orasida DeepLearning.ai va fast.ai o’zlarining noyob yondashuviga ega bo’lib, bizga bu yo’lda katta yordam berishi mumkin.

## DeepLearning.ai

![](/images/first-blog/deeplearningai.png "Andryu Ng")

DeepLearning.ai Andryu Ng tomonidan ishlab chiqilgan pullik kurs. Uning boshqa kurslariga o’xshab, bu yaxshi tuzilgan o’quv tizimi, qiziqarli o’qitish uslubi va qiyin ammo qiziqarli topshiriqlari bilan mashxur. Bu adashib ketmaslikni xohlovchilar uchun kurs sifatida qabul qilingan. Bunda fundamental teoriyalardan boshlanib, haqiqiy hayotiy muammolarni hal qilish uchun barcha qismlarni qanday qilib birlashtirishga qaratilgan. Bu yondashuvning nomi “PASTDAN YUQORIGA” .

## fast.ai

![](/images/first-blog/fastai.png "Jeremi Hovard va Reychel Tomas")

fast.ai Jeremi Hovard va Reychel Tomas tomonidan kodlash tajribasiga ega bo’lgan odamlarga san’at darajasidagi ML o’rgatish uchun bepul kurs sifatida tanishtirilgan. Bu kurs talabalri asosiy teoriyalarni bilmasdan turib bir necha qator kod bilan o’z sohalarida misli ko’rilmagan yutuqlarga erisha oladi.(Men 1-darsdan so’ng [Xitoy kaliligrafiyalarini 96% aniqlikda ajratadigan model yaratdim](https://medium.com/datadriveninvestor/deep-learning-models-by-fast-ai-library-c1cccc13e2b3) va uni [Cloud Serverga joylashtirdim](https://towardsdatascience.com/how-to-deploy-your-machine-learning-web-app-to-digital-ocean-64bd19ce15e2)). Bunda sizga dastlab hayotiy muammolar yechimi birinchi ko’rsatilib, keyin chuqurroq o’rganishgacha olib boradi. Bu yondashuvning nomi esa ‘TEPADAN PASTGA’ deyiladi.

## Demak qaysi bir yaxshiroq? Javob: ikkalasi ham

![](/images/first-blog/chapter-5.png "Maarten Deckers ning Unsplash dagi rasmi")

Bu ikki kurs bir-birini to’ldiruvchidir. Dastlab Andryu Ng ning kurslaridan boshlanadigan o’rganishning dastlabki haftalarida ko’plab formulalar orqali bu sohadagi intuitsiyangiz oshadi, ammo hali ham do’stlaringizga ko’rsatadigan hech narsangiz yo’q va yangi olingan bilimlaringizni qachon qo’llashingiz mumkinligini aniq bilmaysiz. O’rganganlaringizni yodda saqlashda qiyinchiliklar mavjud. Miyangiz sekinlashadi va siz zerikishni boshlaysiz. Aynan shu payt fast.ai kursining dastlabki videolaridan boshlashning ayni payti. Kuchli fast.ai librarysi va bir necha qator kod yordamida hayotiy muammolarni, va hatto ba’zi Kaggle musobaqalarida yaxshi natija ko’rsata boshlaysiz. Bu sizning miyangizga mutlaqo boshqa turdagi stimulyatsiya beradi va chuqurroq o’rganish uchun ko’proq ishonch beradi. Bir nechta loyihalar qilganingizdan keyin sizda yana fundamental bilimlarni o’rganishga ishtiyoq oshadi va deeplearning.ai kurslariga olib keladi. Bu ikki kurs bir-birini oldinga siljitadi va bu jarayonni to tugatguningizgacha takrorlashingiz mumkin.

![](/images/first-blog/chapter-6.png "Maarten Deckers ning Unsplash dagi rasmi")

Bu ikki kursni birgalikda tugatishdan oladigan eng yaxshi narsalarigizdan biri siz deyarli tayyorsiz. Sizdan fast.ai kursidan ish beruvchilarga ko’rsatishingiz mumkin bo’lgan ko’plab loyihalar va bular haqida yaxshigina tasovvur bo’ladi. Endi siz har tomonlama rivojlangan Data Scientistsiz. Ajoyib, shunday emasmi?

P.S. Maqola Michael Li tomonidan [towardsdatascience.com](https://towardsdatascience.com/two-sides-of-the-same-coin-fast-ai-vs-deeplearning-ai-b67e9ec32133) saytida 2019-yil 24-sentabrda yozilgan.
