# color-blocks-spreadsheet
A simple spreadsheet for tracking time on task during the work week.

## What is this?

I wanted some visibility into how I was spending my time and how on-task I was, so I made complicated system of colorful index cards that I attached to my wall during the workday to represent what I've been doing. That was too complicated so I simplified it. I reduced the number of categories and colors and put it into a spreadsheet in Google Sheets. You can find a blank version [here](https://docs.google.com/spreadsheets/d/1HDEh-Xr_3kGn8nW-VSxqYQt9W3Qdvwi3635HSL1brNU/edit?usp=sharing) if you want to copy it for your own use.

### Here it is with some imaginary data

![image](https://github.com/jacob-sewell/color-blocks-spreadsheet/assets/890809/5f2f8886-a80d-41bc-ac23-92983219543c)

## How it works

Each sheet is a week, and each day has a column. All the dates are calculated relative to the Week Start date at the top. Each row represents a chunk of time. In this version the chunks are fifteen minutes long but it doesn't matter for the math. Each cell that's part of your workday gets a two-letter code, and conditional formatting rules apply a color corresponding to that activity in the Key. To the right of the day columns there's a section that calculates Time on Task percentage for each day and the number of "Work Blocks" and "Total Blocks". Custom formatting applies a color scale to the Time on Task Percentage: red at 0%, yellow at 50%, green at 100%.

### Activity Codes

There are five codes in this version of the template:
- wc (Work: Coding) - dark green
- wm (Work: Meetings) - green
- wo (Work: Other) - light green
- nc (Non-work: Constructive) - dark red
- no (Non-work: Other) - bright red

## Other files in this repo

I downloaded the blank template in .xlsx and .ods formats and it seems to work, at least in LibreOffice Calc, but I have only ever used it in Google Sheets so YMMV.
