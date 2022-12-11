# Anton Kasich
---
## Contacts:
* e-mail: [toxa0321@gmail.com](mailto:toxa0321@gmail.com)
* Phone: +375296794402
* Telegram: [@antkasich](https://t.me/antkasich)
* vk: [id180468283](https://vk.com/id180468283)
---
## About myself
I am 21 years old, I am a student of the Faculty of Chemistry at Belarusian State University, but I want to try to become a front-end developer, let's see where it leads...
>“All depends on how determined we are to be successful.” – Robert Kiyosaki.
---
## Skills
* HTML
* CSS 
---
## Code Examples
```
k = int(input('Количество дисков: '))
A = sorted(list(range(1, k + 1)), reverse=True)
B = []
C = []
print(A, B, C, '____________', sep='\n')


def move(k, s, t, a):
    if k > 0:
        move(k - 1, s, a, t)
        t.append(s.pop())
        print(A, B, C, '____________', sep='\n')
        move(k - 1, a, t, s)


move(k, A, C, B)
print('Количество ходов:', 2 ** k - 1)
```