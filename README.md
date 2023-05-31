# SI_2023_lab2_196019
Втора лабораториска вежба во Софтверско Инженерство 2023
Ана Петреска 196019
1.	CFG за дадениот Java Код





https://1drv.ms/w/s!AtxzCuVKcVn-2y929n-iojnvGWEW?e=qc73uE













2.	Multiple Condition критериумот за условот if (user==null || user.getPassword()==null || user.getEmail()==null). Напишете и објаснете ги тест случаите во документацијата.
A = user , B = user.getPassword() , C = user.getEmail()
T.C.1: A ≠ null, B = null, C = null
T.C.2: A = null, B ≠ null, C = null
T.C.3: A = null, B = null, C ≠ null
T.C.4: A ≠ null, B ≠ null, C = null
T.C.5: A = null, B ≠ null, C ≠  null
T.C.6: A ≠ null, B = null, C ≠  null
T.C.7: A = null, B = null, C = null
T.C.8: A ≠ null, B ≠ null, C ≠ null
За да помине условот мора да имаат вредност различна од null, во спртивен случај функцијата врака exception, која што има порака дека недостасуваат клучни информации за корисникот да се логира. Во тој случај, функцијата ќе помине само во тест случајот 8, а во останатите 7 недостасува барем една од потребните, задолжителни информации.
3.цикломатска комплексност
Е – V + 2 каде што Е се ребра, V  се темиња
Е = 61, V = 54
Цикломатската комплесност изнесува 9






