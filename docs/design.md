# Design and Scoring

## Purpose

HappyMe is designed as a positive, low-pressure self-reflection tool. It uses simple language, warm colors, and short prompts appropriate for a brief group or classroom activity.

## Quiz structure

The quiz contains five questions. Every question provides four choices mapped to one of four categories:

- `social`
- `calm`
- `creative`
- `adventure`

## Scoring

Each selected choice increases the total for its mapped category. The category with the greatest total determines the result.

If multiple categories tie, the application selects:

1. The category matching the final question's selected answer, if that category is tied for the maximum score.
2. Otherwise, the first tied category encountered in the category definition order.

This is a reflection prompt, not a psychometric model. Results should not be treated as scientific measurements or clinical conclusions.

## Interface principles

- Clear primary action on every step
- Visible progress
- Large, easy-to-select answer cards
- Back navigation that preserves choices
- Responsive single-column layout on narrow screens
- Visible keyboard focus indicators
- Reduced-motion support
- Polite live result announcements
