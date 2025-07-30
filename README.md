This interactive web tool helps users quantify Method employees benefits of adopting better knowledge management practices. Built with HTML, CSS, and JavaScript, the calculator estimates time savings, productivity boosts, and financial value based on the user's archetype and role level.

## Features
### User Archetype Selection
Users can choose their KM personality type — Navigator, Seeker, Expert, or Explorer.
### Personalized Productivity Gains
Calculates time saved and productivity increased based on user's typical weekly knowledge management habits.
### Annual Value Creation
Calculates the potential monetary gain from improved knowledge workflows.
### Benchmarking Against Industry
Compares employee's weekly time usage on KM to McKinsey’s industry average.
### Career Growth Insights
Displays role-specific career benefits aligned to employee's knowledge archetype.
## Technologies Used
__HTML5__ Structure and layout<br>
__CSS3__ Responsive and modern UI/UX with gradients and animations<br>
__Vanilla JavaScript__ Dynamic calculations and DOM manipulation<br>
## How It Works
### User Inputs <br>
Select your archetype and role level.<br>
Enter weekly hours spent on
* Searching for information<br>
* Answering repetitive questions<br>
* Recreating existing work<br>
* Input your estimated hourly value<br>
### Calculation Logic
Applies an efficiency multiplier based on archetype for each activity.<br>
Calculates
+ Weekly Time Savings
+ Annual Value Creation (based on 50 weeks/year)
+ % Productivity Boost (relative to 35-hour week)
## Contextual Benchmarking
Displays a McKinsey comparison as industry average time spent on knowledge friction  ~7 hours/week.<br>
Flags users above or below this baseline.<br>
## Career Benefits Display
Shows a list of career growth opportunities based on the user's archetype and role level.
## Prerequisites
A modern browser is needed.
* Download or clone the repository.
* Open index.html in any browser.
## Archetype efficiency multipliers per time used to search, recreate, and address repetitive questions.
| Archetype | Search | Question | Recreate |
| --------- | ------ | -------- | -------- |
| Navigator | 0.6    | 0.4      | 0.7      |
| Seeker    | 0.8    | 0.3      | 0.8      |
| Expert    | 0.5    | 0.7      | 0.6      |
| Explorer  | 0.7    | 0.3      | 0.8      |<br>
These multipliers determine how much time can be saved by user archetype for each task type based on behavioral psychology guesstimates.
### Notes
The calculator assumes a 35-hour work week, of which 3 hours/day (15/week) are allocated to other activities (i.e., a baseline of 32 hours is used in productivity percentage calculations).
Career benefits are illustrative and intended to spark reflection on the value of knowledge behaviors.

### Feedback & Customization
If you'd like to customize user archetypes, adjust multipliers, or tailor the career benefits to your organization or use case, feel free to reach out or fork the project.


