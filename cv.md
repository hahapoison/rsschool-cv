# Denis Kushnir

## Contacts:

- **Mail:** kuuushnirrr@gmail.com
- **Telegram:** [@herurgia](https://t.me/herurgia "Link to telegram account")
- **Github:** [@hahapoison](https://github.com/hahapoison "Link to github account")

## About me:

- I'm 18 years old. 
- I am in college with a degree in Computer Science. 
- I enjoy learning and getting new knowledge. 
- I want to get knowledge and skills in web development.

## Skills:

- HTML
- CSS (SCSS/BEM)
- Git/GitHub
- JavaScript (Basic)
- C#/.NET (Basic)
- Photoshop/Figma

## Code example (C#):

**Exercise:** An isogram is a word that has no repeating letters, consecutive or non-consecutive. Implement a function that determines whether a string that contains only letters is an isogram. Assume the empty string is an isogram. Ignore letter case.
```C#
using System;
public class Kata
{
    public static bool IsIsogram(string str) 
    {
        if(str == "")
            return true;
        str = str.ToLower();
        
        for (int i = 0; i < str.Length; i++)
        {
            for (int j = 0; j < str.Length; j++) 
            {
                if (j == i)
                    continue;
                if (str[i] == str[j])
                    return false;
            }
        }
            return true;
    }
}
```

## Education:

- Kramatorsk Professional College of Industry, Information Technologies and Business of Donbass State Machine-Building Academy (**by specialty Computer Science**)
- Courses:
    - [HTML Academy](https://htmlacademy.ru "Link to HTML Academy")
    - [RS School](https://rs.school/ "Link to RS School")