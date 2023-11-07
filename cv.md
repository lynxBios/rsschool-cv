# **Tatsiana Radzkovich**
## Frontend developer

![avatar1.jpg](assets/img/avatar1.jpg)
--------------------------------------

## **Contacts**

* Phone: +375293203861
* E-mail: stv20595@gmail.com
* Discord: lynxbios
* location: Belarus

## **About myself**

I'm 38 years old and I currently working as senior legal counsel. However, I started learning programming last year and I have become very passionate about it. I want to pursue a career in frontend development and work as programmer. I'm also interested in system administration. So far, I have learned the basic syntax of Python.  I continue to enthusiastically learn and develop myself in this field. 

## **Skills**

* Python
* Flask
* Postgres
* MySQL
* AWS
* Docker
* Git
* JavaScript
* HTML/CSS
* Yandex.Direct

## **Code Examples**

```
Напишите программу создания небольшого словаря сленговых программерских выражений, чтобы она потом по запросу возвращала 
значения из этого словаря.

Формат входных данных
В первой строке задано одно целое число n — количество слов в словаре. В следующих n строках записаны слова и их определения, 
разделенные двоеточием и символом пробела. В следующей строке записано целое число m — количество поисковых слов, чье 
определение нужно вывести. В следующих m строках записаны сами слова, по одному на строке.

Формат выходных данных
Для каждого слова, независимо от регистра символов, если оно присутствует в словаре, необходимо вывести его определение. 
Если слова в словаре нет, программа должна вывести "Не найдено", без кавычек.

Примечание. Гарантируется, что в определяемом слове или фразе отсутствует двоеточие (:), следом за которым идёт пробел.

n = int(input())

phrases = [input().split(': ') for _ in range(n)]
sleng_dict = {}

for key in phrases:
    sleng_dict.setdefault(key[0].lower(), key[1])

m = int(input())

for value in range(m):
    print(sleng_dict.get(input().lower(), 'Не найдено'))
```

## **Experience**

I have participated in a small project as a backend developer. I have also explored some aspects of DevOps engineering. I have experience with AWS, Docker, Postgres, MySQL and Flask.
Also I have several frontend mini-projects.
### Projects:
* [Memory-game](https://rolling-scopes-school.github.io/lynxbios-JSFEPRESCHOOL2023Q2/memory-game)
* [Audio-player](https://rolling-scopes-school.github.io/lynxbios-JSFEPRESCHOOL2023Q2/js30-1.2-audio-player)
* [Image-Gallery](https://rolling-scopes-school.github.io/lynxbios-JSFEPRESCHOOL2023Q2/image-galery)
* [CSS-Mem-Slider](https://lynxbios.github.io/cssMemeSlider/cssMemeSlider/index.html)
    

## **Education**

* Mogilev State A. Kuleshov University (2002-2007)
    + Faculty of Economics and Law
    + Specialties: Lawyer

* Courses:
    + School of Internet Professions PROFI-INTERNET (01.10.2019-28.12.2019). Specialties: Yandex.Direct specialist 5.0

    + Stepik (2022)
    "Python Generation": a course for beginners

    + Stepik (2022-2023)
    "Python Generation": advanced course

    + Stepik (2023)
    "Generation Python": a course for professionals

    + The Rolling Scopes School (2023)
    JavaScript Front-End Pre-School 2023Q2: a course for beginners


## **Languages**

* Belorussian (nativ)
* English (B2)
* Russian