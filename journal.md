Week 1

Day 1 — [30/06/2026]


Problem: After Creating 'Pagila Database' and importing the schema and data, it wasn't showing with '\dt' or '\dn'
Insight: Check pgAdmin4 for the tables and schema to check if they have imported correctly, if they've imported correctly, it's a visibility problem relating to the search_path, if when SHOW search_path is blank, that's the cause and needs to be set to public. This is done by running 'SET search_path TO public;' to fix for the session. But you can use 'ALTER ROLE <user_name> SET search_path TO public to fix it permanantely'.
Tags: #search_path, #import, #public


Day 2 — [Date]


Problem:
Insight:
Tags:


Day 3 — [Date]


Problem:
Insight:
Tags:


Day 4 — [Date]


Problem:
Insight:
Tags:


Day 5 — [Date]


Problem:
Insight:
Tags:


Day 6 — [Date]


Problem:
Insight:
Tags:


Day 7 — Review


What's still shaky?
What clicked this week?

Week 2

Day 1 — [Date]


Problem:
Insight:
Tags:


Day 2 — [Date]


Problem:
Insight:
Tags:


Day 3 — [Date]


Problem:
Insight:
Tags:


Day 4 — [Date]


Problem:
Insight:
Tags:


Day 5 — [Date]


Problem:
Insight:
Tags:


Day 6 — [Date]


Problem:
Insight:
Tags:


Day 7 — Review


What's still shaky?
What clicked this week?