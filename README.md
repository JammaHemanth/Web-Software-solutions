# Web-Software Solutions

A corporate recruitment portal with online assessment tests — Programming and Aptitude — for evaluating job applicants.

## Pages

| Page | Purpose |
|------|---------|
| `home.html` | Landing page |
| `about.html` | About the company |
| `service.html` | Services overview |
| `carrer.html` | Job openings with **Apply Now** per role |
| `rules.html` | Test guidelines, then proceeds to the assessment |
| `multiple.html` | Combined **Programming + Aptitude** test (30 questions, 30-min timer) |
| `multiples.html` | Redirects to `multiple.html` |
| `combined-results.html` | Test results with per-section scores and wrong-answer review |
| `Register.html` | User registration |
| `login form.html` | Login page |
| `forgot.html` | Password recovery |
| `feedback.html` / `feedback1.html` | Feedback forms |
| `gallery.html` | Image gallery |
| `quotes.html` | Quotes page |
| `bsforms.html` | Bootstrap form examples |

## Assessment Flow

1. Browse job openings on `carrer.html`
2. Click **Apply Now** → goes to `rules.html` (test guidelines)
3. Click **Start Test** → begins the combined assessment at `multiple.html`
4. Complete Programming (15 Qs) and Aptitude (15 Qs) sections within 30 minutes
5. Submit → results displayed on `combined-results.html` with score breakdown and review

## Styling

- Dark glass-morphism theme
- CSS variables in `css/style.css`
- Bootstrap 5.3.3, FontAwesome 6.5.1, Google Fonts (Inter)
