# OPI_LB_2

## DishGuide

## Опис проєкту
DishGuide — це система рекомендацій страв у ресторанах на основі відгуків користувачів.

## Functional Requirements

| ID | Опис |
| :---: | :--- |
| FR-01 | Користувач може шукати ресторан |
| FR-02 | Користувач може шукати ресторани за місцем розташування |
| FR-03 | Користувач може переглядати найкращі страви в ресторані |
| FR-04 | Користувач може бачити рейтинг ресторану |
| FR-05 | Користувач може бачити популярні ресторани |
| FR-06 | Система надає рекомендації страв на основі відгуків |
| FR-07 | Користувач може фільтрувати ресторани за кухнею |

## Use Case Diagram

<img width="445" height="578" alt="OPI_2_1" src="https://github.com/user-attachments/assets/61dbb670-22a0-4bd0-ba84-24bd84b79d1d" />

## Class Diagram

<img width="574" height="587" alt="OPI_2_2" src="https://github.com/user-attachments/assets/ae83e00f-d42c-4bdf-9a5a-e367d9a34616" />

## Sequence Diagram

<img width="632" height="323" alt="OPI_2_3" src="https://github.com/user-attachments/assets/ff580e2e-702f-4b32-a966-0e1b27a0dbbe" />

## Traceability Matrix

| Functional Requirement | Use Case | Classes | Sequence Diagram |
| :---: | :--- | :--- | :--- |
| FR-01 | Пошук ресторану | User, Restaurant | ✔ |
| FR-02 | Пошук ресторану за місцем розташування | User, Restaurant | — |
| FR-03 | Перегляд найкращих страв | User, RecommendationService | ✔ |
| FR-04 | Перегляд рейтингу ресторану | User, Review, Restaurant | — |
| FR-05 | Перегляд популярних ресторанів | User, Restaurant | — |
| FR-06 | Аналіз відгуків |RecommendationService, Review | ✔ |
| FR-07 | Фільтрація за кухнею | User, Filter | — |
