# MultiLingua master specification — implementation audit

**Status: prototype only.** This document is the acceptance baseline; it does not certify production readiness.

| Requirement | Current state | Acceptance needed |
|---|---|---|
| Nine languages | Selector implemented | Native-script UI, locale tests, translation review |
| 72 language directions | Pair selection works | Verified quality across all pairs |
| Swap languages | Implemented | Preserve per-direction curriculum progress in cloud |
| Beginner curriculum | 10 illustrative words | Complete structured beginner lessons |
| Intermediate curriculum | Missing | B1/B2 units and assessments |
| Expert curriculum | Missing | C1/C2 units and assessments |
| Verbs/nouns/adjectives/tenses | Missing | Linguist-authored grammar lessons |
| Food/travel/transport/taxi/airlines | Illustrative words only | Real themed lessons and dialogues |
| Materials/clothes/electronics/time | Missing | Illustrated categorized lessons |
| Africa/world/capitals/universe | Missing | Reviewed geography and science content |
| Visual vocabulary cards | Text cards only | Licensed imagery and examples |
| Textbooks | Missing | Interactive, accessible offline readers |
| Search | Basic two-language word search | Search lessons, grammar, transliterations |
| Hamburger/navigation | Basic navigation | Full accessible menu and mobile QA |
| Multiple-choice quiz | Implemented, 15 seconds | Deterministic options, distractor quality and tests |
| True/false quiz | Missing | Scored and explained |
| Fill in blanks | Missing | Input normalization per script |
| Timed tests | Basic 15-second quiz | Configurable durations, accessibility |
| Voice repeat | Browser TTS only | Speech recognition and pronunciation scoring |
| Counting/numbers | Missing | Progressive numeracy lessons |
| Email accounts | Missing | Supabase Auth, confirmation and recovery |
| User profiles | Local display name | Protected cloud profiles |
| Progress | Local storage only | Per-user secure sync and spaced repetition |
| Maps/flags | Missing | Licensed maps, accurate flags and capital data |
| Subscriptions | Missing | Server-verified entitlements, payments, refunds |
| Offline | Static assets only | Cached lessons and sync conflict resolution |
| Admin/content management | Missing | Moderation, content review and roles |
| Android/iOS | Browser prototype | Signed native packages and device testing |
| Security | No server yet | RLS, privacy policy, abuse and payment testing |
| Accessibility | Partial semantic markup | Screen-reader, RTL and keyboard QA |
| Production deployment | Missing | Build, preview, smoke tests, monitoring |

## Recommended release gates
1. **Foundation:** dedicated Supabase project, authentication, profile/progress RLS, CI and automated browser tests.
2. **Education:** native-speaker-reviewed beginner content for all nine languages, grammar and examples, audio coverage.
3. **Assessments:** multiple-choice, true/false, fill-blanks, review algorithm, timed practice and analytics.
4. **Advanced learning:** intermediate/expert curriculum, textbooks, AI conversation and pronunciation evaluation.
5. **Commercial launch:** secure billing, maps, content licensing, privacy compliance, Android/iOS builds and real-device QA.

Do not advertise the prototype as a complete educational product. Content examples are provisional and require language specialists.
