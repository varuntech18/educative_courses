# Educative Courses

<img width="1181" alt="194501785-3c44b7e3-26cc-4f17-a819-93bd972e54b6" src="https://github.com/gdsc-bit/educative_courses/assets/116020663/bc8bc050-f13c-4741-bc39-56ba953d714d">

## Introduction

The world is teeming with educational opportunities across various domains, especially in the technical and digital sectors. Online courses have emerged as a key enabler for learning and skill development, with platforms like Educative providing a wealth of high-quality courses.

However, navigating this vast sea of educational content can be overwhelming. That's where this project comes in. We're creating a user-friendly, community-driven database to catalog and curate these educational gems. The aim is to make it easier for learners, whether beginners or experts, to discover and access courses that align with their interests and ambitions.

This is a part of an educative course database being built as part of Hacktoberfest 2023. Refer to [CONTRIBUTING.MD](CONTRIBUTING.md) for contribution guidelines.

## Getting Started

To contribute to this project, follow these steps:

1. Fork this repository.
2. Edit the database following the rules outlined in the [CONTRIBUTING.MD](CONTRIBUTING.md) file.
3. Once the information is added and properly structured, create a pull request.
4. Wait for your pull request to get merged.

## Rules for Contributions

1. `id` is the number assigned by your mentor.
2. `module_number` should be an integer - refer to the table of contents for module numbers.
3. `free_courses` can have either 'yes' or 'no'.
4. `difficulty` can be 'beginner', 'intermediate', or 'advanced'.
5. `certification` can be 'free' (for free courses with free certifications), 'paid' (either for paid courses or free courses with paid certifications), or 'none'.
6. Commit message should be 'Added course_name' or a similar message stating the course name.
7. Make sure the courses you're entering into the database don't already exist there.
8. PRs that don't abide by the rules won't be merged.

### Reference

You can use the following example as a reference for structuring your information:

```json
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
