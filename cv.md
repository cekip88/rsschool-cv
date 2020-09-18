1. Ruslan Sekerbayev
2. My contacts: **[mail](cekip@mail.ru)**, **[vk](vk.com/sekerbaev)**
3. I want to be a professional programmer, I want to solve interesting tasks. Programming is interesting)
4. My skills: **JavaScript(_beginner_)**, **HTML&CSS(_user_)**.
5. Code Example (
createEl(tag,className,data = {},childs = []){
<br>let temp = document.createElement(`${tag}`);
<br>if(className) temp.className = className;
<br>if(data){
<br>for(let key in data){
<br>if(key === 'text') {
<br>if(tag === 'INPUT' || tag === 'TEXTAREA') temp.value = data[key];
<br>else temp.textContent = data[key];
<br>} else if(key === 'innerHTML') temp.innerHTML = data[key];
<br>else temp.setAttribute(`${key}`,`${data[key]}`);
<br>}
<br>}
<br>if(childs) {
<br>if(typeof childs === 'object'){
<br>childs.forEach(function (el) {
<br>temp.append(el)
<br>});}}
<br>return temp;
<br> })
6. I am working in small company web-developers and learning to coding on JS. I have not portfolio. Now I write small library that can show some information in modal windows.
7. My education: **I am learning in small web-programming courses "GrammlaSchool" in my city**. That's all)
8. My English is not very well, last practice was in university more than 10 years ago. I planing to learn english that autumn, but it only will)
9. Thats all I have to say)))
