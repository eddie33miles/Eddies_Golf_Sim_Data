# golf_df: Personal Golf Performance Tracker

**Author**: Eddie Miles Waldron  
**Goal**: To become a scratch golfer through data-driven analysis.

## Overview

This project is a comprehensive tracking system for every shot and round I play. The data is pulled from both simulator sessions (E6 Connect) and real-life rounds at various courses. I'm using Python to analyze everything from club speed and launch angle to strokes gained and course-specific tendencies.

If you're a golfer who wants to stop guessing and start improving, you'll love this.

---

## Features

- Track performance per club and per course
- Visualize trends in launch angle, spin rates, apex, carry, and more
- Compare your game to scratch benchmarks
- Identify weaknesses in real time (e.g. short game under pressure)
- Analyze simulator vs. real-course variance
- Experimental predictive modeling (coming soon)

---

## Folder Structure
---

## Sample Metrics Tracked

- `carry_distance`
- `club_speed`
- `ball_speed`
- `smash_factor`
- `back_spin`, `side_spin`, `spin_axis`
- `launch_angle`, `launch_dir`
- `AoA`, `dynamic_loft`, `face_to_path_angle`
- `distance_to_pin`, `GIR`, `penalty`, `terrain`
- `round_score`, `hole-by-hole strokes gained`

---

## Quickstart

Clone the repo and set up your Python environment:

```bash
git clone https://github.com/yourusername/golf_df.git
cd golf_df
pip install -r requirements.txt
