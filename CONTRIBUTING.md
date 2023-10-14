# Educative courses database
This comprises of data on courses assisting in learning technical subjects

## Procedure :
1. Fork this repository and edit as per the following rules.
2. Once the infomration is added and is in a proper structured format, create a pull request.
3. Wait for it to get merged !

### Rules:
1. ***id*** is the number assigned by your mentor
2. ***module_number*** should be an **integer**, *refer the table of contents for module numbers !*
3. ***free_courses*** - can have either **'yes'** or **'no'** against them
4. ***difficulty*** can be either one of three options- **'beginner'** , **'intermediate'** or **'advanced'**.
5. ***certification*** can be either one of three options- **'free'** (for *free courses with free certifications*), **'paid'** (either for *paid courses* or *free courses with paid certifications* ) and **'none'**.
6. Commit message should be 'Added *course_name* ' or similar message stating the course name.
7. Make sure that the courses you're entering into the database don't already exist there !
8. ***PRs which don't abide by the rules won't be merged***

### Reference :
You can take the reference from below example and structure your information similar to that.

   
  ```
  [
     {
       "id" :  1,
       "platform" : "educative",
       "free_course" : "no",
       "course_name" : "Accelerated Linux Core Dump Analysis",
       "link" : "https://www.educative.io/courses/accelerated-linux-core-dump-analysis",
       "difficulty" : "expert",
       "module_number" : 15,
       "certification" : "paid"
     },
     {
       "id" :  2,
       "platform" : "educative",
       "free_course" : "no",
       "course_name" : "Foundations of Linux ARM64: Debug, Disassemble, and Reverse",
       "link" : "https://www.educative.io/courses/foundations-of-linux-arm64-debug-disassemble-and-reverse",
       "difficulty" : "intermediate",
       "module_number" : 15,
       "certification" : "paid"
     }
]
 ```
### Module Number Reference :

![github educative](https://github.com/gdsc-bit/educative_courses/assets/100427124/86e36964-7063-412d-882a-5ae9838492e3)


#### Bonus :
Improve the layout and functionality of the deployed webpage - quality PRs will get merged !

