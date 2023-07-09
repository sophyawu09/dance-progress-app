# Database Ideas

Data to be stored:
- User
  - username
  - password
- Goals
  - dance name
  - song name
  - artist
  - link
  - start time
  - end time
  - current progress
  - edit times


Tables:
- User
  - user_id
  - username
  - password
- Goal
  - goal_id
  - dance name
  - song name
  - artist name
  - link
  - start time
  - end time
- User-Goal
  - user_id
  - goal_id
- Goal Progress
  - goal_progress_id
  - goal_id
  - time
  - progress
