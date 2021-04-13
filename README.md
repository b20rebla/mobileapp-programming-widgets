
# Rapport

Jag använde mig av Linearlayout. Därefter så lade jag först till en knapp och skrev vad knappen skulle heta samt ett tillhörande ID till knappen.
ID är unikt för den knappen och gjorde det möjligt att kunna få till kodningen i MainActivity för att det skulle gå att klicka på knappen i appen och skicka
datan som hade skrivits ut i MainActivity. Därefter lade jag till ImageView och EditText. I ImageView valde jag att lägga till en färg istället för en bild
samt att jag lade till hur bred och hög bilden skulle vara. EditText gjorde jag även där möjligt att istället för att skicka data som i knappen så kunde man
skriva en text i appen och sedan skicka datan.

```
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
```
Linearlayout valdes

```
android:id="@+id/button"
```
ID för att göra denna knapp unik

```
android:orientation="vertical"
```
Jag ändrade positioneringen för alla widgets med hjälp av denna kod samt att jag lade till en Linearlayout i den redan tidigare existerande Linearlayout.



![](bild1.png)
![](bild2.png)

