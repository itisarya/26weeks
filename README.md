# 26-Week Body Recomp Tracker

A mobile-first, zero-dependency web application designed to track a comprehensive 26-week body recomposition journey. 

Navigating a large-scale tracking architecture can be complex, so this project is structured cleanly within a single file. It consolidates daily habit tracking, dynamic week-by-week workout/meal plans, interactive weight visualization, and streak mechanics using vanilla web technologies. All data is stored locally on the user's device for complete privacy and instant load times.

## Key Features

* **Dynamic 4-Block Plan Integration:** Automatically updates daily caloric targets, lifting guidelines, and swimming protocols based on the specific week of the challenge (Foundation, Build, Intensify, Peak).
* **Daily Action Logging:** Track gym sessions, swim volume, diet adherence, and custom habits (like development/study sessions) with a clean, tap-friendly UI.
* **Progress Visualization:** Includes an activity heatmap and a Chart.js integration to visualize weight trends against a target goal line.
* **Streak & Consistency Tracking:** Calculates overall completion percentages and multi-day streaks for individual habits.
* **Local Storage:** Zero backend required. All configurations and historical logs are saved directly to the browser's `localStorage`.

## Tech Stack

* **HTML5 / CSS3:** Custom CSS variables and a mobile-first flexbox/grid layout.
* **Vanilla JavaScript:** Handles DOM manipulation, date math, dynamic week rendering, and local storage management.
* **Chart.js:** Utilized for rendering the interactive weight progression graph.
