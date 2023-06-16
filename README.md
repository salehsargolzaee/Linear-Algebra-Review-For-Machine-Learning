<details>
  <summary>If you don't speak Persian, click to find out more about this repository.</summary>
  <p>
One of the best Machine Learning courses I have watched is <a href="http://cs229.stanford.edu/syllabus-summer2019.html">CS229: Machine Learning - The Summer Edition"</a> by Stanford. Unlike other courses that offer quick, superficial definitions, this course thoroughly reviews the essential concepts in Probability, Statistics, and Linear Algebra. Recently, I was studying the Linear Algebra section of the course and taking notes. I realized that many of the topics covered in the course were asked during a Ph.D. interview I had a few months ago. Since few good Persian resources are available, I decided to share my notes here in hopes of helping others succeed in the Linear Algebra part of their interviews.</p>
</details>

<br/>

<div dir = "rtl" align="center">

<h3 align="center">مروری بر مباجث جبرخطی</h3>

  <p align="center">
    مورد نیاز برای یادگیری ماشین
    <br />
  </p>
</div>

<br>
<div dir="rtl">
یکی از دوره‌های مورد علاقه‌ی من در <a href= "http://cs229.stanford.edu/syllabus-summer2019.html">حوزه‌ی یادگیری ماشین، دوره CS229 ترم تابستان دانشگاه استنفورد است.</a> در‌حالی که دوره‌های آنلاین زیادی در تلاشند که این حوزه‌ را به صورت فست‌فودی ارائه کنند، این دوره به طور جامع مطالب مربوط به آمار و احتمال و جبرخطی مربوطه را توضیح می‌دهد. به تازگی مروری بر جبرخطی که در ابتدای این دوره ارائه می‌شود، داشتم و مطالبش را به فارسی یادداشت کرده‌ام. تعداد زیادی از مطالب مرور شده، در مصاحبه‌ای که مدتی پیش برای یک موقعیت دکترای مستقیم داشتم از من پرسیده شده بود. با توجه به کمبود منابع فارسی، فکر کردم که شاید یادداشت‌های من به درد دوست دیگری بخورد و تصمیم گرفتم یادداشت‌های خودم را اینجا به اشتراک بگذارم.
</div>
<br/>

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image1.png){width="7.791666666666667in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image3.png){width="8.027777777777779in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image4.png){width="7.847222222222222in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image5.png){width="7.916666666666667in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image6.png){width="7.986111111111111in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image7.png){width="7.916666666666667in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image8.png){width="7.972222222222222in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image9.png){width="7.902777777777778in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image10.png){width="7.930555555555555in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image11.png){width="8.0in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image12.png){width="7.777777777777778in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image13.png){width="8.01388888888889in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image14.png){width="7.791666666666667in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image15.png){width="7.958333333333333in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image16.png){width="8.01388888888889in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image17.png){width="8.055555555555555in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image18.png){width="8.0in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image19.png){width="8.11111111111111in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image20.png){width="7.986111111111111in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image21.png){width="8.0in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image22.png){width="7.875in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image23.png){width="8.180555555555555in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image24.png){width="7.944444444444445in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image25.png){width="8.083333333333334in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image26.png){width="7.833333333333333in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image27.png){width="7.986111111111111in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image28.png){width="7.972222222222222in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image29.png){width="7.916666666666667in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image30.png){width="7.763888888888889in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image31.png){width="7.861111111111111in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image32.png){width="7.861111111111111in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image33.png){width="7.805555555555555in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image34.png){width="8.0in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image35.png){width="7.930555555555555in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image36.png){width="7.930555555555555in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image37.png){width="8.125in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image38.png){width="7.791666666666667in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image39.png){width="8.152777777777779in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image40.png){width="8.041666666666666in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image41.png){width="7.75in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image42.png){width="7.694444444444445in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image43.png){width="7.930555555555555in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image44.png){width="7.916666666666667in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image45.png){width="8.097222222222221in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image46.png){width="7.944444444444445in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image47.png){width="7.930555555555555in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image48.png){width="7.972222222222222in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image49.png){width="8.069444444444445in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image50.png){width="8.0in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image51.png){width="7.916666666666667in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image52.png){width="7.847222222222222in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image53.png){width="7.833333333333333in"
height="11.0in"}

![](vertopal_c4f0ffde513149a9b80459c18a383245/media/image54.png){width="7.986111111111111in"
height="11.0in"}
