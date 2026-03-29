# Awesome Open Source Tools for Fitness Trainers 2026

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@main/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Stars](https://img.shields.io/github/stars/GagnDeep/awesome-best-ai-tools-for-fitness-trainers-2026?style=social)

> A curated list of **100% open source fitness-specific tools** for personal trainers, fitness coaches, and gym professionals. Every tool listed here is directly related to fitness training, nutrition, or gym management.

## Table of Contents

- [TL;DR](#tldr)
- [Why Open Source for Fitness Professionals?](#why-open-source-for-fitness-professionals)
- [Workout & Exercise Tracking](#workout--exercise-tracking)
- [Nutrition & Diet Planning](#nutrition--diet-planning)
- [Exercise Databases & APIs](#exercise-databases--apis)
- [Gym & Client Management](#gym--client-management)
- [Gaps in Open Source Fitness](#gaps-in-open-source-fitness)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## TL;DR

- **Workout Tracking:** Use [wger](https://github.com/wger-project/wger) or [workout-cool](https://github.com/Snouzy/workout-cool) for comprehensive workout logging
- **Exercise Database:** Use [ExerciseDB API](https://github.com/ExerciseDB/exercisedb-api) with 11,000+ exercises
- **Nutrition Tracking:** Use [waistline](https://github.com/davidhealey/waistline) or [OpenFoodFacts](https://github.com/openfoodfacts/openfoodfacts-server) for food databases
- **Gym Management:** Use [GYM-One](https://github.com/mayerbalintdev/GYM-One) for gym operations
- **iOS Tracking:** Use [Iron](https://github.com/karimknaebel/Iron) for Swift-based weightlifting

## Why Open Source for Fitness Professionals?

Fitness trainers handle **sensitive client data** — body measurements, health history, progress photos, and personal schedules. Open source tools give you:

- **Data sovereignty** — Client data stays on your servers, not fitness SaaS platforms
- **No vendor lock-in** — Export client data anytime
- **Cost control** — Self-host on your own infrastructure or cheap VPS
- **Full ownership** — If a startup shuts down, your client data remains accessible
- **Customization** — Build custom workout templates and integrations

> ⚠️ **Important:** This list contains **ONLY fitness-specific tools with public GitHub repositories**. General business tools (CRM, invoicing, generic scheduling) are excluded unless they're specifically designed for fitness use.

## Workout & Exercise Tracking

### wger
> **Description:** wger (ˈvɛɡɐ) is a free workout and fitness manager. It offers custom workout routines with automatic weight progression rules, comprehensive tracking for diet plans, body weight and custom measurements, nutrition management with food logging via Open Food Facts integration, progress photos with body weight charting, and full iOS and Android app support.

- **GitHub:** [github.com/wger-project/wger](https://github.com/wger-project/wger)
- **Stars:** 5,870 ⭐
- **Language:** Python/Django
- **License:** AGPL-3.0
- **Last Commit:** 2026-03-28
- **Category:** Workout Tracking, Nutrition, Weight Tracking
- **Best for:** Personal trainers managing client workouts and nutrition plans

---

### workout-cool
> **Description:** 🏋 Modern open-source fitness coaching platform. Create workout plans, track progress, and access a comprehensive exercise database. Built with TypeScript for modern web deployment. Features include workout logging, exercise library, and progress visualization.

- **GitHub:** [github.com/Snouzy/workout-cool](https://github.com/Snouzy/workout-cool)
- **Stars:** 7,152 ⭐
- **Language:** TypeScript
- **License:** MIT
- **Last Commit:** 2026-03-28
- **Category:** Workout Planning, Exercise Database, Coaching
- **Best for:** Building custom workout programs for clients

---

### workout-tracker (jovandeginste)
> **Description:** A workout tracking web application for personal use (or family, friends), geared towards running and other GPX-based activities. Import GPS tracks, track outdoor workouts, and visualize training progress with charts and maps.

- **GitHub:** [github.com/jovandeginste/workout-tracker](https://github.com/jovandeginste/workout-tracker)
- **Stars:** 1,209 ⭐
- **Language:** Go
- **License:** NOASSERTION
- **Last Commit:** 2026-03-28
- **Category:** Workout Tracking, GPS, Running, Cycling
- **Best for:** Run coaches and trainers working with athletes who use GPS devices

---

### Iron
> **Description:** A modern and completely free weightlifting workout tracker for iOS, written in SwiftUI. Track your lifts, view progression charts, and manage your workout routines with a beautiful native interface.

- **GitHub:** [github.com/karimknaebel/Iron](https://github.com/karimknaebel/Iron)
- **Stars:** 206 ⭐
- **Language:** Swift
- **License:** GPL-3.0
- **Last Commit:** 2026-03-17
- **Category:** Weightlifting, iOS, Workout Tracking
- **Best for:** iOS users who want a native weightlifting experience

---

### wingfit
> **Description:** Minimalist fitness app to plan your workouts, track your personal records and leverage smartwatch data. Simple interface for logging workouts and viewing progress over time.

- **GitHub:** [github.com/itskovacs/wingfit](https://github.com/itskovacs/wingfit)
- **Stars:** 472 ⭐
- **Language:** TypeScript
- **License:** NOASSERTION
- **Last Commit:** 2026-03-28
- **Category:** Workout Tracking, Fitness App
- **Best for:** Trainers wanting a lightweight, modern workout tracker

---

### MyFit
> **Description:** Workout tracker inspired by the RP Hypertrophy App. Create customized training programs with exercise selection, set/rep schemes, and progression tracking for strength and hypertrophy training.

- **GitHub:** [github.com/WhyAsh5114/MyFit](https://github.com/WhyAsh5114/MyFit)
- **Stars:** 127 ⭐
- **Language:** TypeScript
- **License:** AGPL-3.0
- **Last Commit:** 2026-03-16
- **Category:** Workout Tracker, Strength Training
- **Best for:** Bodybuilders and strength trainers using RPE-based training

---

### WorkoutTracker (jerichoi224)
> **Description:** An app to record and track workout routines. Simple and intuitive interface for logging exercises, sets, reps, and weights during training sessions.

- **GitHub:** [github.com/jerichoi224/WorkoutTracker](https://github.com/jerichoi224/WorkoutTracker)
- **Stars:** 104 ⭐
- **Language:** Dart
- **License:** None
- **Last Commit:** 2026-02-24
- **Category:** Workout Tracking, Mobile App
- **Best for:** General workout logging with a clean mobile interface

---

### Gym-Routine-Tracker-Watch-App
> **Description:** Minimalist gym workout tracker, as an independent watchOS app. Track your workouts directly from your Apple Watch without needing your phone.

- **GitHub:** [github.com/open-trackers/Gym-Routine-Tracker-Watch-App](https://github.com/open-trackers/Gym-Routine-Tracker-Watch-App)
- **Stars:** 54 ⭐
- **Language:** Swift
- **License:** MPL-2.0
- **Last Commit:** 2026-03-27
- **Category:** watchOS, Workout Tracking
- **Best for:** Apple Watch users who want standalone gym tracking

---

### gym-log
> **Description:** Workout tracker built with Django & React. Web-based application for logging workouts, tracking exercises, and visualizing progress over time.

- **GitHub:** [github.com/vlad-moroshan/gym-log](https://github.com/vlad-moroshan/gym-log)
- **Stars:** 35 ⭐
- **Language:** JavaScript
- **License:** Apache-2.0
- **Last Commit:** 2026-03-11
- **Category:** Workout Tracking, Django, React
- **Best for:** Web-based workout logging with modern frontend

---

### liftapp
> **Description:** A WIP rewrite of LiftApp, a workout tracker for Android. Track your lifts, manage workouts, and monitor your strength progression on Android devices.

- **GitHub:** [github.com/patrykandpatrick/liftapp](https://github.com/patrykandpatrick/liftapp)
- **Stars:** 93 ⭐
- **Language:** Kotlin
- **License:** None
- **Last Commit:** 2026-02-21
- **Category:** Android, Workout Tracking
- **Best for:** Android users wanting a dedicated lifting tracker

---

### HA-hevy
> **Description:** HEvy is a free workout tracker for iOS and Android. Build routines and track progress with friends. Features include workout logging, routine building, and progress sharing.

- **GitHub:** [github.com/hudsonbrendon/HA-hevy](https://github.com/hudsonbrendon/HA-hevy)
- **Stars:** 22 ⭐
- **Language:** Python
- **License:** MIT
- **Last Commit:** 2026-03-16
- **Category:** Workout Tracking, iOS, Android
- **Best for:** Social workout tracking with routine building

---

### OpenWorkoutTracker (msimms)
> **Description:** A workout tracker for iOS that includes cycling, running, as well as strength exercises. Supports Bluetooth sensors for heart rate monitors and other fitness devices.

- **GitHub:** [github.com/msimms/OpenWorkoutTracker](https://github.com/msimms/OpenWorkoutTracker)
- **Stars:** 74 ⭐
- **Language:** Objective-C
- **License:** None
- **Last Commit:** 2026-03-12
- **Category:** iOS, Workout Tracking, Bluetooth
- **Best for:** Multi-sport athletes with Bluetooth sensors

---

### WorkoutExporter
> **Description:** Exporting Workouts tracked by Apple Watch into files ready for sharing. Transfer workout data from Apple Fitness to other platforms and formats.

- **GitHub:** [github.com/WorkoutExporter/WorkoutExporter](https://github.com/WorkoutExporter/WorkoutExporter)
- **Stars:** 27 ⭐
- **Language:** Swift
- **License:** MIT
- **Last Commit:** 2026-03-10
- **Category:** Apple Watch, Data Export
- **Best for:** Moving Apple Watch workout data to other fitness platforms

---

### InFit
> **Description:** A simple workout tracker app, to keep track of your progress. Clean interface for logging daily workouts and monitoring fitness goals.

- **GitHub:** [github.com/KenAli77/InFit](https://github.com/KenAli77/InFit)
- **Stars:** 66 ⭐
- **Language:** Kotlin
- **License:** Apache-2.0
- **Last Commit:** 2026-03-10
- **Category:** Android, Workout Tracking
- **Best for:** Android users wanting simple workout logging

---

### MuscleBook
> **Description:** [ABANDONED] Muscle Book is an iOS workout tracker for strength training and body building. Track lifts, view muscle group coverage, and plan your training splits.

- **GitHub:** [github.com/cfilipov/MuscleBook](https://github.com/cfilipov/MuscleBook)
- **Stars:** 46 ⭐
- **Language:** Swift
- **License:** GPL-3.0
- **Last Commit:** 2026-01-06
- **Category:** iOS, Bodybuilding, Strength Training
- **Best for:** iOS bodybuilders (note: project appears abandoned)

---

### FitLife
> **Description:** Clean and simple Workout Tracker. Log exercises, track sets and reps, and monitor your fitness journey with straightforward tracking.

- **GitHub:** [github.com/sanderdebr/FitLife](https://github.com/sanderdebr/FitLife)
- **Stars:** 27 ⭐
- **Language:** JavaScript
- **License:** None
- **Last Commit:** 2024-05-08
- **Category:** Workout Tracking
- **Best for:** Simple, no-frills workout logging

---

### reactgym
> **Description:** Workout-Tracking app built in ES6 using React, Flux and ImmutableJS. Web-based workout logging with a modern frontend architecture.

- **GitHub:** [github.com/zupzup/reactgym](https://github.com/zupzup/reactgym)
- **Stars:** 37 ⭐
- **Language:** JavaScript
- **License:** MIT
- **Last Commit:** 2025-07-15
- **Category:** Workout Tracking, React
- **Best for:** Developers who want a React-based workout tracker reference

---

### Workout-Tracker (enrique-paulino)
> **Description:** 🏋 A simple and self-hostable workout tracking web app built with Flask, SQLite, and Docker. Easy to deploy and customize for personal training use.

- **GitHub:** [github.com/enrique-paulino/workout-tracker](https://github.com/enrique-paulino/workout-tracker)
- **Stars:** 27 ⭐
- **Language:** HTML
- **License:** None
- **Last Commit:** 2026-03-27
- **Category:** Workout Tracking, Flask, Self-hosted
- **Best for:** Self-hosted workout tracking with Docker deployment

---

### fittrak
> **Description:** A data-driven workout tracking tool for the quantified-self 💪 🤓. Track workouts, analyze patterns, and optimize training based on data.

- **GitHub:** [github.com/tsoporan/fittrak](https://github.com/tsoporan/fittrak)
- **Stars:** 21 ⭐
- **Language:** Python
- **License:** GPL-3.0
- **Last Commit:** 2025-09-08
- **Category:** Workout Tracking, Data Analysis
- **Best for:** Data-driven trainers who want detailed analytics

---

### Fitness-Tracker-App (ssqueen)
> **Description:** A fitness tracker mobile application developed with Flutter. The app allows users to log workouts, track progress, and set fitness goals. Cross-platform mobile development example.

- **GitHub:** [github.com/ssqueen/Fitness-Tracker-App](https://github.com/ssqueen/Fitness-Tracker-App)
- **Stars:** 26 ⭐
- **Language:** Dart
- **License:** None
- **Last Commit:** 2025-02-15
- **Category:** Flutter, Workout Tracking
- **Best for:** Flutter developers building fitness apps

---

### sigmafit
> **Description:** 💪 SigmaFit makes workout tracking easy! Simple interface for logging workouts and tracking progress over time.

- **GitHub:** [github.com/SigmaFitness/sigmafit](https://github.com/SigmaFitness/sigmafit)
- **Stars:** 22 ⭐
- **Language:** TypeScript
- **License:** GPL-3.0
- **Last Commit:** 2025-05-28
- **Category:** Workout Tracking
- **Best for:** Simple workout logging with progress tracking

---

## Nutrition & Diet Planning

### OpenFoodFacts
> **Description:** Open Food Facts is a free, open database of food products from around the world. It includes ingredients, allergens, nutrition facts, and Eco-Score. The database contains over 3 million products and is maintained by a community of contributors. Perfect for building nutrition-focused applications or integrating food lookup into client tracking.

- **GitHub:** [github.com/openfoodfacts/openfoodfacts-server](https://github.com/openfoodfacts/openfoodfacts-server)
- **Stars:** 15,966 ⭐
- **Language:** Perl
- **License:** AGPL-3.0
- **Last Commit:** 2026-03-28
- **API:** Yes - REST API at [world.openfoodfacts.org/api](https://world.openfoodfacts.org/api)
- **Category:** Food Database, Nutrition API
- **Best for:** Integrating food lookup and nutrition calculations into fitness apps

---

### waistline
> **Description:** Libre calorie counter app for Android. Built with Cordova. Track calories, macros, and nutrition with a privacy-focused approach - all data stays on your device.

- **GitHub:** [github.com/davidhealey/waistline](https://github.com/davidhealey/waistline)
- **Stars:** 691 ⭐
- **Language:** JavaScript
- **License:** None
- **Last Commit:** 2026-03-22
- **Category:** Calorie Counter, Nutrition Tracking, Android
- **Best for:** Privacy-focused calorie and macro tracking for clients

---

### calorie (karpathy)
> **Description:** Nice and effective super simple calorie counter web app. Minimal interface for logging food intake and tracking daily calories.

- **GitHub:** [github.com/karpathy/calorie](https://github.com/karpathy/calorie)
- **Stars:** 133 ⭐
- **Language:** HTML
- **License:** None
- **Last Commit:** 2026-03-17
- **Category:** Calorie Counter, Web App
- **Best for:** Simple, no-backend calorie tracking

---

### FoodYou
> **Description:** A free, open-source, and privacy-focused food diary and nutrition tracker. Track daily food intake, monitor macros, and analyze nutrition patterns with all data stored locally.

- **GitHub:** [github.com/maksimowiczm/FoodYou](https://github.com/maksimowiczm/FoodYou)
- **Stars:** 377 ⭐
- **Language:** Kotlin
- **License:** GPL-3.0
- **Last Commit:** 2026-03-26
- **Category:** Food Diary, Nutrition Tracker, Android
- **Best for:** Privacy-focused nutrition tracking on Android

---

### PriceAndNutritionTrackingSystem
> **Description:** PANTS is a self-hosted, open-source nutrition tracker and tool for nutritional data analysis of ingredients and recipes. Track food costs along with nutritional values.

- **GitHub:** [github.com/dylanleigh/PriceAndNutritionTrackingSystem](https://github.com/dylanleigh/PriceAndNutritionTrackingSystem)
- **Stars:** 132 ⭐
- **Language:** Python
- **License:** Apache-2.0
- **Last Commit:** 2026-03-22
- **Category:** Nutrition Tracking, Cost Analysis
- **Best for:** Track nutrition and food costs together

---

### HealthTracker (joshhedstrom)
> **Description:** A Fitness and Nutrition Tracking App built with JavaScript. Simple web-based interface for logging workouts and meals together.

- **GitHub:** [github.com/joshhedstrom/healthTracker](https://github.com/joshhedstrom/healthTracker)
- **Stars:** 55 ⭐
- **Language:** JavaScript
- **License:** MIT
- **Last Commit:** 2020-08-20 (Limited active development)
- **Category:** Fitness Tracking, Nutrition
- **Best for:** Combined fitness and nutrition tracking

---

### Fit-track (DavieObi)
> **Description:** Open-source Python-based fitness tracker web app using Flask. Features include workout logging, nutrition tracking, and progress visualization. Ideal for developers and fitness enthusiasts looking to contribute to a health-tech project.

- **GitHub:** [github.com/DavieObi/Fit-track](https://github.com/DavieObi/Fit-track)
- **Stars:** 53 ⭐
- **Language:** Python/Flask
- **License:** MIT
- **Last Commit:** 2025-10-18
- **Category:** Workout Tracking, Nutrition, Flask
- **Best for:** Developers wanting to extend or customize fitness tracking

---

### manatee-fitness
> **Description:** Free and open source calorie counter and nutrition tracker. Simple interface for tracking daily food intake and monitoring nutritional goals.

- **GitHub:** [github.com/femiaf13/manatee-fitness](https://github.com/femiaf13/manatee-fitness)
- **Stars:** 47 ⭐
- **Language:** TypeScript
- **License:** AGPL-3.0
- **Last Commit:** 2025-10-09
- **Category:** Calorie Counter, Nutrition Tracker
- **Best for:** Open source nutrition tracking with calorie focus

---

### KAJU-Calorie-Counter
> **Description:** KAJU is an app used to calculate BMI and daily calorie needs, tracks user calories, and offers over 600,000 foods and recipes. Comprehensive food database for accurate nutrition tracking.

- **GitHub:** [github.com/duhanboblanli/KAJU-Calorie-Counter](https://github.com/duhanboblanli/KAJU-Calorie-Counter)
- **Stars:** 36 ⭐
- **Language:** Swift
- **License:** MIT
- **Last Commit:** 2026-02-16
- **Category:** Calorie Counter, iOS, Nutrition
- **Best for:** iOS users wanting comprehensive food database

---

### NutriScan (Jerryzjx)
> **Description:** iOS App - Nutrition Tracker with barcode scanning for food logging. Scan. Understand. Eat Smart. Uses camera to scan food labels and track nutrition.

- **GitHub:** [github.com/Jerryzjx/NutriScan](https://github.com/Jerryzjx/NutriScan)
- **Stars:** 21 ⭐
- **Language:** Swift
- **License:** Apache-2.0
- **Last Commit:** 2026-01-23
- **Category:** Nutrition Tracker, iOS, Barcode Scanner
- **Best for:** iOS users who want to scan food labels

---

### ai-calorie-counter (open-kbs)
> **Description:** An LLM-based app to easily track calories and exercise by taking a photo of your meal or describing your physical activity. Uses AI for food recognition and calorie estimation.

- **GitHub:** [github.com/open-kbs/ai-calorie-counter](https://github.com/open-kbs/ai-calorie-counter)
- **Stars:** 19 ⭐
- **Language:** JavaScript
- **License:** MIT
- **Last Commit:** 2026-03-17
- **Category:** AI, Calorie Counter, Food Recognition
- **Best for:** AI-powered food photo calorie estimation

---

## Exercise Databases & APIs

### ExerciseDB API
> **Description:** ExerciseDB API is a fitness exercise database API that allows users to access high-quality exercises data which consists of 11,000+ exercises. This API offers extensive information on each exercise, including target body parts, equipment needed, video, gifs, images for visual guidance, and step-by-step instructions.

- **GitHub:** [github.com/ExerciseDB/exercisedb-api](https://github.com/ExerciseDB/exercisedb-api)
- **Stars:** 182 ⭐
- **Language:** Python/Go
- **License:** AGPL-3.0
- **Last Commit:** 2025-11-25
- **Category:** Exercise Database, API
- **Best for:** Building custom workout apps with comprehensive exercise data

---

### Exercise Database API (davejt)
> **Description:** An open exercise database API providing structured data on exercises, muscles targeted, and equipment required. Essential building block for workout planning applications.

- **GitHub:** [github.com/davejt/exercise](https://github.com/davejt/exercise)
- **Stars:** 160 ⭐
- **Language:** JavaScript
- **License:** MIT
- **Last Commit:** 2013-05-10 (Archived)
- **Category:** Exercise Database
- **Best for:** Reference for exercise data structure (note: archived)

---

## Gym & Client Management

### GYM-One
> **Description:** GYM One is an open-source, free gym management software designed to optimize the operations of fitness centers, personal trainers, and sports clubs. Features membership management, class scheduling, and trainer management.

- **GitHub:** [github.com/mayerbalintdev/GYM-One](https://github.com/mayerbalintdev/GYM-One)
- **Stars:** 172 ⭐
- **Language:** PHP
- **License:** MIT
- **Last Commit:** 2026-02-28
- **Category:** Gym Management, Member Management
- **Best for:** Small gyms and personal trainers needing member tracking

---

## Gaps in Open Source Fitness

The following categories have **no credible open source options**. These represent opportunities for developers:

### AI Workout Generation
**Status:** No credible open source option exists

- TrainHeroic, Fitbod, JuggernautAI are all closed SaaS platforms
- No GitHub repos found for AI-powered workout planning with genuine exercise science
- **Opportunity:** Build an open source AI workout generator using exercise databases and LLMs

### Custom Training Program SaaS
**Status:** No open source alternatives

- Most platforms (TrainHeroic, Fitbod, JuggernautAI) are closed-source SaaS
- wger offers basic program templates but lacks modern UI and mobile apps
- **Opportunity:** Create a modern, self-hosted training program builder

### Gym Management with Modern Features
**Status:** Very limited options

- GYM-One provides basic membership tracking
- Most comprehensive gym software is proprietary (Mindbody, GymMaster)
- **Opportunity:** Build a modern gym management system with mobile apps

### Yoga & Pilates Specific Tools
**Status:** No dedicated open source platforms found

- No GitHub repos specifically for Yoga or Pilates instruction
- General workout trackers can be adapted but lack pose libraries
- **Opportunity:** Create a Yoga/Pilates focused platform with pose databases

### Nutrition AI Meal Planning
**Status:** No open source option

- OpenFoodFacts exists but lacks AI planning capabilities
- No open source recipe generation or macro optimization
- **Opportunity:** Build AI meal planning on top of OpenFoodFacts data

---

## FAQ

### Are there open source alternatives to TrainHeroic or Fitbod?
Not yet. While tools like wger and workout-cool exist, they lack the AI-powered personalization and modern mobile apps that proprietary platforms offer. The fitness industry has a significant gap in open source AI fitness tools.

### How do I build a fitness app with open source tools?
Start with ExerciseDB API for exercise data, OpenFoodFacts for nutrition data, and build your custom frontend. Consider using wger as a reference or backend. For AI features, you would need to integrate with Ollama or similar (self-hosted).

### What open source tools can replace Mindbody for gym management?
GYM-One provides basic gym management including membership tracking and class scheduling. For a complete solution, you would need to combine GYM-One with other fitness-specific tools for scheduling and tracking.

### How do I track client progress with open source tools?
wger and workout-cool provide workout logging and progress tracking. waistline handles nutrition tracking. You can combine these tools or build custom integrations based on your client tracking needs.

### Can I self-host all these fitness tools?
Most can be self-hosted using Docker and Docker Compose. Tools like wger and GYM-One have official Docker images. Some require more technical setup than others.

### What about personal training client management?
Currently, GYM-One is the most comprehensive open source option for member management. For client progress tracking, wger offers workout logging with body weight and measurement tracking.

## GitHub Search Queries Used

These queries helped build this list:

```bash
gh search repos "workout tracker" --stars >20 --limit 50
gh search repos "fitness exercise" --stars >20 --limit 50
gh search repos "gym management" --stars >20 --limit 50
gh search repos "nutrition tracking" --stars >20 --limit 50
gh search repos "personal trainer" --stars >10 --limit 50
gh search repos "calorie counter" --stars >10 --limit 50
gh search repos "exercise database" --stars >20 --limit 50
gh search repos "bodybuilding app" --stars >10 --limit 50
```

## Contributing

Contributions welcome! Please read the contribution guidelines:

1. Tools must have a public GitHub repository
2. Tools must be **fitness-specific** (workout tracking, nutrition, gym management, exercise databases)
3. General business tools (CRM, invoicing, generic scheduling) will not be accepted
4. Tools must be actively maintained (commits within last 2 years)
5. Include stars count, language, and license from GitHub
6. Descriptions must be from actual README, not fabricated

## License

This awesome list is licensed under the MIT License.

The individual tools retain their original licenses as listed in their respective GitHub repositories.
