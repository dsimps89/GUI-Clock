# GUI-Clock
Value Clock GUI v3

User Guide & Technical Reference

Overview

Value Clock GUI v3 is a browser-based behavioral tracking, spending visualization, and time-value monitoring system.

The application combines:

* Time-based accumulation clocks
* Spending usage tracking
* 365-day spiral visualization
* 5-day behavioral blocks
* Progress monitoring
* Historical persistence
* Statistical reporting
* Break-even analysis

All data is stored locally in the browser and automatically saved.

⸻

Core Concept

Each tracked category accumulates value over time based on its assigned rate.

Examples:

Category	Rate
OLG	$1.00 per second
Browsing	$1.00 per minute
Cigars/Smoking	$3.50 per hour
Claudia	$120.00 per hour
Restaurants	$20.00 per day
Drinking	$52.99 bi-weekly
Cannabis	$20.00 weekly
Escorts	$160.00 monthly
Holidays	Annual allowance

The timer continuously builds value.

Whenever usage is entered:

Current Balance = Accumulated Value − Usage

Balances may become negative.

Maximum range:

* +$999,999.99
* -$99,999,999.99

⸻

Main Screen Layout

Center Value Clock

The center displays:

* Total accumulated value
* Net balance
* Current tracking status
* Run/Pause indicator

⸻

Variable Rings

Each variable has:

* Independent timer
* Independent accumulation
* Independent usage history
* Independent progress bar

Rings continuously expand as time passes.

⸻

Spiral Year View

The spiral represents:

365 days

organized as:

73 five-day blocks

Each block contains:

5 individual day cells

Benefits:

* Easier visual tracking
* Faster trend recognition
* Compact year overview

⸻

Color Tracking

Each day can be assigned a category.

Example:

Green = Cannabis
Red = Drinking
Blue = Restaurants
Orange = Browsing

A single day may record one primary activity.

⸻

Block Coloring Logic

For each 5-day block:

5/5 same activity
→ Block becomes full category color

4/5 same activity
→ Block mostly category color

3/5 mixed
→ Mixed representation

1/5 activity
→ Block displays warning color

This creates a high-level behavioral heatmap.

⸻

Variable Management

Users may:

* Add variables
* Edit variables
* Remove variables
* Change rates
* Change colors

There are no protected variables.

All categories are fully editable.

⸻

Timer Engine

Each variable stores:

* Name
* Color
* Accumulation rate
* Time unit
* Usage history
* Balance

Supported units:

* Per Second
* Per Minute
* Per Hour
* Per Day
* Per Week
* Bi-Weekly
* Monthly
* Yearly

⸻

Usage Entry

When spending occurs:

1. Select category
2. Enter amount
3. Save

The system:

* Records timestamp
* Updates history
* Reduces balance
* Preserves audit trail

Example:

Escorts accumulates:

$160/month

After 5 months:

Accumulated = $800

Usage entered:

$160

New balance:

$640

Timer continues accumulating.

⸻

Progress Bars

Every category includes:

24-hour progress tracking

Bars fill based on:

Current cycle completion

Examples:

Daily category:

* Resets every day

Weekly category:

* Resets every 7 days

Monthly category:

* Resets every month

Yearly category:

* Resets every 365 days

⸻

Auto Save

Application automatically saves:

Every 15 minutes

Additional saves occur when:

* Variables are edited
* Usage is entered
* Days are marked
* Manual save is triggered

Storage method:

Browser Local Storage

No internet connection required.

⸻

Import & Export

Export creates:

JSON backup file

Includes:

* Variables
* Balances
* Usage history
* Spiral data
* Settings
* Statistics

Import restores:

Entire application state

⸻

CPI Adjustment

At the end of each:

365-day cycle

All rates automatically increase by:

2.5%

Formula:

New Rate = Current Rate × 1.025

Manual override is disabled.

This preserves inflation-adjusted tracking.

⸻

Holidays

Holiday categories:

* Occur once per year
* Can only be recorded once annually
* Included in annual calculations

Examples:

* Birthday
* Christmas
* Anniversary
* Vacation
* Veterans Events

⸻

Run / Pause

Run:

* Timers accumulate
* Progress bars update
* Statistics update

Pause:

* Timers freeze
* Values remain unchanged

Data continues to be saved.

⸻

Reset Options

Soft Reset

Resets:

* Current balances
* Active timers

Keeps:

* History
* Statistics

⸻

Full Reset

Deletes:

* All balances
* All history
* All spiral markings
* All reports

Returns application to factory state.

⸻

Reports

Print no longer prints the dashboard.

Instead it generates:

Statistics Report

Contains:

* Total accumulated value
* Total usage
* Net position
* Category rankings
* Usage frequency
* Spending trends
* Break-even analysis

⸻

Break-Even Graph

The graph compares:

Accumulated Value

vs

Actual Usage

Across time.

Used to identify:

* Surplus periods
* Deficit periods
* Long-term trends
* Recovery rates

Crossing point:

Accumulation = Usage

This is considered break-even.

⸻

Recommended Usage

The application is most effective when:

* Updated daily
* Categories remain consistent
* Usage entries are recorded immediately
* Monthly exports are performed

⸻

Data Storage Location

Browser Local Storage

Suggested backups:

* Weekly export
* Monthly archive
* Annual report export

⸻

Version

Value Clock GUI v3

Features:

✓ Spiral 365-day tracker

✓ Independent value clocks

✓ Variable editor

✓ Usage subtraction

✓ Auto-save every 15 minutes

✓ Import/Export

✓ CPI adjustment

✓ Statistical reporting

✓ Break-even graphing

✓ Print-ready reports

✓ Run/Pause controls

✓ Unlimited custom categories
