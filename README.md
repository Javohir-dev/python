<h1>Python asoslari:</h1>
<p>Bu yerda Python asoslari bo'yicha eng kerakli ma'lumotlar saqlangan.</p>


<h2>Lists(ro'yxatlar)</h2>
<pre><code><span>fruits = ["apple", "banana", "cherry"]
print(fruits)</span></code></pre>

<h5>List ichida nechta item borligini aniqlaydi.</h5>
<pre><code><span>fruits = ["apple", "banana", "cherry"]
print(len(fruits))
# >>> 3</span></code></pre>

<h5>List ichidagi itemlarga indexi bo'yicha 0dan boshlab murojat qilamiz.</h5>
<pre><code><span>fruits = ["apple", "banana", "cherry"]
print(fruits[0])
# >>> "apple"</span></code></pre>

<h5>For loop orqali list bilan ishlash.</h5>
<pre><code><span>fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
# >>> apple
# >>> banana
# >>> cherry</span></code></pre>

<h5>Listdan itemlarni ohirdan boshlab sug'urib olish chun ishlatamiz.</h5>
<code>.pop()</code>

<h5>Listdan itemlarni ohirdan boshlab o'chirishga chun ishlatamiz.</h5>
<code>.remove()</code>

<h5>Listdan itemlarni ohirdan boshlab qo'shish chun ishlatamiz.</h5>
<code>.append()</code>

<h5>Listdan itemlarni ohirdan boshlab o'chirishga chun ishlatamiz.</h5>
<code>.remove()</code>

<h2>Methods</h2>
<h5><code>.sort()</code> metodi alifbo tartibida itemlarni joylashtirishga yordam beradi.</h5>
<pre><code><span>cars = ['bmw','mercedes benz', 'volvo', 'general motors', 'tesla', 'audi']
cars.sort()
print(cars)
# >>> ['audi', 'bmw', 'general motors', 'mercedes benz', 'tesla', 'volvo']</span></code></pre>

<br />
<ul>
    <li>
        📍 Diqqat! Tartiblashda katta harflar kichik harflardan avval kelishini hisobga oling. Agar matndagi so'zlarning bosh harfi katta-kichik aralash yozilgan        bo'lsa, ularni bir ko'rinishga keltirib olish maqsadga muvofiq bo'ladi.
    </li>
</ul>
<br />
<pre><code><span>cars = ['Bmw','mercedes benz', 'volvo', 'gm', 'tesla', 'audi']
cars.sort()
print(cars)
# >>> ['Bmw', 'audi', 'gm', 'mercedes benz', 'tesla', 'volvo']</span></code></pre>

