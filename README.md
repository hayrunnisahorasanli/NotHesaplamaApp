# NotHesaplamaApp
kotlin ile geliştirilmiştir.
### **1. XML Dosyası (`activity_main.xml`)**

Bu dosya, uygulamanın arayüzünü tanımlar. Kullanıcıdan not girişi almak için bir metin kutusu (**`EditText`**), hesaplama butonu (**`Button`**) ve sonucu göstermek için bir metin alanı (**`TextView`**) içerir.

```kotlin
<!-- EditText: Kullanıcıdan not girişini alır -->
<EditText
    android:id="@+id/editTextNumber"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:inputType="number"
    android:hint="Notu girin"
    android:layout_marginTop="16dp"
    android:layout_marginStart="32dp"
    android:layout_marginEnd="32dp"
    />

<!-- Button: Hesaplama işlemini başlatır -->
<Button
    android:id="@+id/buttonCalculate"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Hesapla"
    android:layout_marginTop="16dp"
    android:layout_marginStart="32dp"
    android:layout_marginEnd="32dp"
    />

<!-- TextView: Hesaplama sonucunu gösterir -->
<TextView
    android:id="@+id/textViewResult"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text=""
    android:textSize="24sp"
    android:textStyle="bold"
    android:layout_marginTop="16dp"
    android:layout_marginStart="32dp"
    android:layout_marginEnd="32dp"
    />

```

###2. Kotlin Dosyası (MainActivity.kt)
Bu dosya, uygulamanın işlevselliğini sağlar. Kullanıcının girdiği notu alır, değerlendirir ve sonucu gösterir.Bu kod, XML dosyasındaki görünümleri (views) bulur ve hesaplama butonuna tıklandığında yapılacak işlemi tanımlar. Kullanıcının girdiği notu alır, değerlendirir ve sonucu ekranda gösterir.
### **1. XML Dosyası (`activity_main.xml`)**

Bu dosya, uygulamanın arayüzünü tanımlar. Kullanıcıdan not girişi almak için bir metin kutusu (**`EditText`**), hesaplama butonu (**`Button`**) ve sonucu göstermek için bir metin alanı (**`TextView`**) içerir.

```kotlin
<!-- EditText: Kullanıcıdan not girişini alır -->
<EditText
    android:id="@+id/editTextNumber"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:inputType="number"
    android:hint="Notu girin"
    android:layout_marginTop="16dp"
    android:layout_marginStart="32dp"
    android:layout_marginEnd="32dp"
    />

<!-- Button: Hesaplama işlemini başlatır -->
<Button
    android:id="@+id/buttonCalculate"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Hesapla"
    android:layout_marginTop="16dp"
    android:layout_marginStart="32dp"
    android:layout_marginEnd="32dp"
    />

<!-- TextView: Hesaplama sonucunu gösterir -->
<TextView
    android:id="@+id/textViewResult"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text=""
    android:textSize="24sp"
    android:textStyle="bold"
    android:layout_marginTop="16dp"
    android:layout_marginStart="32dp"
    android:layout_marginEnd="32dp"
    />

```

### **2. Kotlin Dosyası (`MainActivity.kt`)**

Bu dosya, uygulamanın işlevselliğini sağlar. Kullanıcının girdiği notu alır, değerlendirir ve sonucu gösterir.Bu kod, XML dosyasındaki görünümleri (views) bulur ve hesaplama butonuna tıklandığında yapılacak işlemi tanımlar. Kullanıcının girdiği notu alır, değerlendirir ve sonucu ekranda gösterir.
