```python
import introduction
from flattery import swagger

def about_me():

    who_am_i = swagger.makeSummary()
    what_have_i_achieved = swagger.getSomeExperience()
    what_are_my_expertise = introduction.getReleventSkills(what_have_i_achieved)

    description = [who_am_i, what_have_i_achieved, what_are_my_expertise]

    for i in range(len(description)):
        print(description[i])


if __name__ == "__main__":
    about_me()
```

```python
>_  python3 about.py █   
```

```python
      
     ◍- I am a scientist by education, a researcher
         by passion, and a Computational physicist
         by profession!
          
     ◍- I hold a master's degree in Computer science and
         a bachelor's in Physics.



      ⬡- Professionally, I have ⤵
      
      
          🚀 delivered 10k+ lines of classified,
              cross-platform, high-efficiency programs
               
          🤖 constructed automation solutions to enhance
              Research & development by more than 70%
               
          🕹️ developed a complex 3-D video game in a
              collaborative, agile workflow
          
          🎲 constructed comprehensive mathematical tools and
              methods to analyze deterministic and non-deterministic
              classical and Quantum algorithms
               
          📝 authored more than 25 pages in computational
              neurophysics
          
```
```python
>_ █   
```


<!---
sabneet95/sabneet95 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
