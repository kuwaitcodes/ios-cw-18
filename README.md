

# صفحة التوجيه Navigation View



## في هذا التمرين سنقوم بتخمين رقم من الظاهر بالصورة وستقوم navigation view باخبارنا ما إن كان الرقم صحيح او خاطئ في الصفحة الثانية كما هو موضح بالصورة.


## لعمل كود صفحة التوجيه :

```
 NavigationView {

       NavigationLink(destination: Text(“النص المراد ظهوره بالصفحة الثانية”)) {

                            Text("النص بالصفحة الأولى")

                        }.navigationBarTitle("العنوان")

          }
```

---

## تمرين




### 1. عمل مصفوفة من الارقام وجعل المتغير يأخذ قيمة عشوائية ومقارنته بالرقم الذي تم الضغط عليه.


### 2. عمل navigation view عشان تنقلنا للصفحة الثانية وتبين النتيجة هل صحيح الرقم او غلط.


### 3. ولاننسى نضيف عنوان حق navigation view 
